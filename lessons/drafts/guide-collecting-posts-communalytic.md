---
layout: tutorial
lang: en
unit:
slug: guide-collecting-tweets-netlytic
title: A guide to collecting posts with Communalytic
requirements: [free text] 
learning outcomes: [list of sentences]
tags: 
author: 
- Frédéric Clavert
- Hannah Smyth 
date: 2025-07-11
toc: true
mediatype: web-social-media
research-phase: heuristics
activity: tbd 
---


## Introduction <a id="section0"></a> 

The main learning goal of this tutorial is to enable historians and social scientists to gather social media data they can use as primary sources for research purposes or as teaching materials. We will mainly focus on [BlueSky](https://bsky.app), though [Communalityc](https://communalytic.org/) provides also connectors to other platforms. We will first introduce the reader to the [BlueSky application programming interface (API)](https://docs.bsky.app/) with particular attention to its limitations. We will then guide them through a first hashtag-based harvesting of posts, for which we will use selected hashtags and provide examples of several that are relevant to historical memory. Finally, we will provide a basic analysis of the corpus of the collected posts, by operating basic text mining operations and social network analysis.

Text mining can be defined as the process to derive information from large corpora of texts through computational operations of diverse nature. As such, it offers a range of methods and techniques to analyze content as data. On the other hand, it may also be interesting to analyze the structure of a social media posts dataset through the prism of social network analysis. Social network analysis (SNA) is ["the process of investigating social structures through the use of networks and graph theory"](https://en.wikipedia.org/wiki/Social_network_analysis). It sees social structures in terms of nodes (actors) and edges (relationships and interactions) that connect nodes. Frequently used in digital humanities or digital history, text mining and SNA are two kinds of analysis that can be applied to social media datasets in social sciences and humanities (SSH). For instance, though bluesky posts contain (short) texts, analysing a dataset of thousands, hundreds of thousands, or millions of those posts will require the use of text mining as it is not possible to read the whole dataset closely. Furthermore, social media posts and their numerous metadata contain many kinds of interactions that can serve as the basis for social network analyses.

Social media posts can be considered today and, more importantly, in the future as primary sources for historians. The two authors of this lesson, for instance, have used datasets of tweets to study the [echoes of the Centenary of the First World War online within a memory studies framework](https://www.vr-elibrary.de/doi/10.13109/gege.2021.47.1.175) and the [Irish Decade of Commemorations](https://journalofdigitalhistory.org/en/article/SLCj9T3MsrEk) from a feminist perspective.

There are various ways to collect social media-related data; we propose here to use [Communalytic](https://communalytic.org/) (formerly Netlytic), an online tool that does not require specific skills in programming. For this tutorial, you need to have a Communalytic account. Note that, if you wish to collect data from other platforms connected to Communalytic (YouTube, Telegram and Reddit), you will have to open an account on those platforms. For X, you will also need to pay a subscription.  


<!-- 
(optional) Highest level: CSV-related analyses.
nodegoat
VoyantTools 
-->

## Overview of Communalytic <a id="section1"></a>

Communalytic, formerly Netlytic, is a cloud-based tool for collecting, visualising, and analyzing social media data from several platforms such as BlueSky, Mastodon, Reddit, Telegram, YouTube, and X (formerly Twitter). It is a “no code” tool that has specifically been conceived for humanities and social sciences researchers who need not be familiar with a programming language or with the Application Programming Interface (API, see below) of those platforms. Communalytic commes with two versions. Communalytic EDU “is designed to help students learn about social media data analytics and social network analysis", while Communalytic PRO “is designed for researchers, journalists and other stakeholders and is ideal for large-scale research projects”. The two versions of Communalytic are hosted on separate servers, have their own account creation and sign-in processes. EDU users will be able to share datasets with other EDU users, but not with PRO users, as well as PRO users can share datasets with other PRO users, but not with EDU users. While Communalytic EDU is free and Communalytic PRO is not, Communalytic EDU has much more limitations than the PRO version: only three datasets can be created, with a maximum of 30 000 posts that can be collected, stored and anlysed in total. Communalytic PRO allow their users to collect up to 3 million records, over 30 datasets with a maximum records per dataset of 1 million (11/07/2025). While both versions of Communalytic can be used to follow this lesson, we will use the EDU one.

Once you have an account, you will be able to see which social media platforms you can collect data from, and which kind of data you can collect. For instance, you can harvest 'historical posts', 'threads' or 'user timeline' from BlueSky. We will have a specific interest in collecting 'historical posts' through [hashtags](https://en.wikipedia.org/wiki/Hashtag) (#keyword) or simple keywords (not preceded by hashtags), including replies. To collect the data, the current version of Communalytic uses the BlueSky XRPC API, that is based on the AT Protocol, a protocol developped by BlueSky “for distributed social networking services.” ([See Wikipedia for more information](https://en.wikipedia.org/wiki/AT_Protocol)). Once collected, the datasets are stored online by default, so users should consider whether this complies with their university's ethical guidelines for social media research. The number of records and datasets a user can store at any one time is limited. However, datasets can be downloaded as [CSV files](https://en.wikipedia.org/wiki/Comma-separated_values) for working offline with other programs and freeing up space for more data collection. After collecting the data, users can also carry out different types of analyses: civility analysis, sentiment analysis, topic analysis and different types of network analyses. Furthermore, existing datasets can also be uploaded for analysis.

## Setting the scene: what is BlueSky, the BlueSky API and how does it work? <a id="section2"></a>

BlueSky was a project of Twitter (now X) started by then Twitter’s CEO Jack Dorsey. Its aim was to develop a new social media protocol (a set of rules that several platforms can follow to be compatible between them), that would allow the setting up of open and decentralised social media platforms. The initial aim was that Twitter would adopt this new protocol (the AT protocol, for Authenticated Transfer Protocol). BlueSky became an independant company in 2021 and, when Elon Musk bought back Twitter, BlueSky, with Mastodon, was presented as the main “alternative” to X. BlueSky launched as a social media platform in February 2023 on an “invite-only” mode for a year, before opening to all early 2024. From a user point of view, BlueSky’s interface is quite similar to Twitter’s. At eh beginning of 2025, BlueSky could claim 30 million users.

One of the functionality that BlueSky offers to developers and also researchers is its Application Programming Interface (API). An API ["is a connection between computers or between computer programs."](https://en.wikipedia.org/wiki/API) (11/07/2025). More precisely, it is an interface that allows one piece of software to offer a service to other pieces of software. An API is usually documented, so that developpers can implement it in their programs. The services accessible through an API can be of different natures. In the case of social media, like buttons from Facebook that you can see on many websites are using the Facebook’s API. In this lesson, we are more interested in another kind of service that can be accessible through an API: data and metadata.

<!-- 
![Twitter API screenshot from Twitter documentation](assets/images/guide-collecting-tweets-netlytic/guide-netlytic-1.png "Fig. 1 What does the Twitter API do?") -->



The BlueSky API allows us to access one of the core primitives of the AT Protocol that BlueSky uses: the [‘firehose’](https://docs.bsky.app/docs/advanced-guides/firehose). The firehose is “an authenticated stream of events used to efficiently sync user updates”. In other words, when you connect to a BlueSky account and read posts from other users, those posts are part of the firehose. Collecting posts from BlueSky implies to connect to this firehose, through diverse endpoints which correspond with specific types of information you can get or send. Among the possibilities offered by the firehose are the possibilities to collect public data from BlueSky and more specifically posts and replies, threads and users’ timeline. If you wish more information about the BlueSky API, please read its [developers documentation](https://docs.bsky.app/). 

Based on this API, the EDU version of Communalytic allows users to collect up to 30 000 BlueSky posts (including replies) in three datasets. Communalytic, whether the EDU or the PRO versions, will take into account BlueSky API's [rate limits](https://docs.bsky.app/docs/advanced-guides/rate-limits), that are implemented to avoid service disruptions because of intense data harvesting. This is all the more important that, with the rise of large language models and the dire need of fresh data to train them, more and more companies are aggressively collecting content, which led to some controversies, including about [BlueSky](https://www.404media.co/someone-made-a-dataset-of-one-million-bluesky-posts-for-machine-learning-research/). This should be known, as it deals with our privacy.

## Your first harvest of posts <a id="section3"></a>

Create an account in Communalytic by signing in through Google. This will create a Communalytic EDU account. Researchers working on larger projects can also create a "PRO" account. Once you are connected, you will directed to "My Datasets" (or click "My Datasets" in the main menu bar). Unlike, for example, Twitter, you do not need to have a BlueSky account to draw down posts through the API.

<!-- insert -->
![Creating a Communalytic account]("Fig. 2 Creating a Communalytic account") 

Before you begin to collect data, you will need to choose a topic and find your hashtags. To choose a hashtag or a simple keyword, please go the ["How to choose your hashtag?" section](#section3-1) below. Once you know what you are looking for, click on "My Datasets" and choose the "Historical Posts" option under the BlueSky tab. 

As you see, you will be asked to:
* Choose a name for your dataset
* Search Query (up to 1024 characters)
* Define filters (start date and end date, max number of posts, include replies)

You will have to fill in a form to register all this information.

<!-- insert -->
![Form of filters to harvest posts with Communalytic]("Fig. 3 Setting the filters to collect your dataset")


You can use a very simple search query or something more complex, more of which below. You might want to use these to manually test the results in the BlueSky interface, which offers some advanced searching: [Tips and Tricks for Bluesky Search](https://bsky.social/about/blog/05-31-2024-search). The option you choose for harvesting posts, whether by Thread, Timeline or keyword-based search, will depend on your research. The Thread or Timeline options might be useful, for instance, for studying the interactions between a museum and its audience. You might want to limit your query to posts published by the museum’s accounts and the replies to those posts using the Timeline option and its filters.


### Choose your hashtag and build your dataset <a id="section3-1"></a>

To build your dataset, you may want to study a trending topic. Trending topics are theoretically a way to understand what people are discussing on BlueSky, but the way they are defined has evolved and became more complex over the years, depending on the context: for instance, if you are consulting BlueSky in the UK, you might see trending topics that are closely linked to this country. You can also go to BlueSky and use the Search bar for hashtags. Posts that appear in the search results might contain other hashtags beyond your initial search: you can then follow the chain of hashtag links to collect the most relevant ones for your query. This is known as the ["snowballing" technique](https://en.wikipedia.org/wiki/Snowball_sampling). Of course, you may already have a defined object of interest and look for specific keywords independently of the trending topics.

You should also consider the expected size of your corpus of posts. How big should your corpus be? Another way to think about this is: how many posts do you need for your research to produce reliable results? The answer will depend on many factors such as your research and topic (what you want to study, how you want to study it), the number of posts that were produced around your chosen topic, and technical limitations (the tool you are using to collect the posts, API’s limitations, etc). It is not a question that we can answer within this lesson, as each case is unique.

Some important points to understand to help you maximise your query:
* You can create complex queries using keyword and hashtag combinations. The BlueSky API specifies certain search operators that work similarly to Boolean operators and are not case sensitive: you can search exact matches by "putting statements inside double quotes"; if you want to search for posts containing both words or phrases, you simply use a space between the two keywords e.g. 1916 commemoration; if you want to search either of two words or phrases you must use the vertical line between the words e.g. commemoration | "easter rising". For example, if I want to find posts about the commemoration of the women involved in the 1916 Easter rebellion in Ireland, "women centenary" would not be specific enough, and we would request: women centenary #1916rising | "easter rising"... See more about writing  BlueSky search queries here: https://communalytic.org/docs/bluesky-historical-posts-data-collector/#step-2nbsp
* Depending on the topic you work on, it may not suffice to follow a small set of hashtags to build your corpus. Topics like #Trump or #ukrainewar produce a large number of posts a day; however, with some exceptions, commemorations generate far fewer posts. If your preferred topic is of the kind to produce a very small corpus, which might hinder a meaningful analysis, you may need to use keywords in addition to hashtags. This type of query can become complex, but still you can test it using the BlueSky search bar to make sure it returns the expected results before implementing them in Communalytic. To do this, you can test the query directly in the BlueSky interface using the Search bar. To create the dataset in Communalytic, click on the "Start Data Collection" button. A new page will then be loaded while the data is being captured.
* You can build your corpus over a few days if necessary. You may, however, need to anticipate a major/annual commemoration or historic event. Some examples of annual "memorial" hashtags include: #WW1 #LestWeForget #BloomsDay #ArmisticeDay.
* If there are no posts that match your query, you will receive an error message.

<!-- insert -->

![Progress of the dataset import from the BlueSky API]( "Fig. 4 Importing your dataset")


Congratulations! You now have your first BlueSky dataset ready and can analyze it in various ways. A summary of this will appear at the bottom of the page. To begin analysing your data, click on the magnifying glass symbol under "Records" to access an overview of the dataset. From here, you can also download an Excel or CSV file of your posts, if you wish to use another analysis tool. When you go to "Download Dataset", you will also see a table of the posts that you have collected; a search bar is available for you at the top if necessary to search individual posts. You can export your data and analyze them with any method and tool that you prefer - we mention some at the end of the next section. We also strongly recommend you download your dataset to preserve your data and be able to reuse them in your future research activities.

<!-- insert -->

![View of the table of the BlueSky dataset in Communalytic after preview]("Fig. 5 The table of the posts in your dataset in Communalytic")


### Text analysis <a id="section3-2"></a>

Text analysis is one of the basic operations of analysis you can apply to a corpus of posts. Below we present how you can use the functionalities for text analysis offered by Communalytic.  

Once you have your dataset, as shown in the [previous step](#section3-1), go to "Dataset Overview Module" where you can browse some high-level data such as posts per day and accounts that post most frequently on your topic ("Top Posters"). This overview includes a Word Cloud [word cloud](https://en.wikipedia.org/wiki/Tag_cloud), which visualizes the words that are the most frequent in your corpus. But you can do more than this. For example, you can also click on a keyword or hashtag to inspect it [in context](https://en.wikipedia.org/wiki/Key_Word_in_Context) (i.e. where the term appears in the posts). Likewise, you can do the same in the Emoji Cloud.

Next, let's see how you can explore topics within the dataset. The "Topic Analysis" function creates groups, or "clusters", of posts that are similar in meaning to each other. These "cluster embeddings" may then allow you to identify abstract concepts, topics or themes within the dataset. Using the default clustering algorithm click "Visualize Embeddings" [embedding = numerical representation of information] - this will be queued in the server and you may need to wait a few moments. Then click on "Open Visualization" to view and explore the word clusters, which will appear as datapoints in a "similarity map". You can then adjust the clustering parameters and re-analyze the data. For example, if you lower the "minimum cluster size" you will see a higher number of distinct clusters of posts. Use the exploration tool in the sidebar to zoom in on different clusters and label them. You may also download these data as a CSV file, if you wish - and again, we strongly recommend you download and preserve any data you use for your analysis.

<!-- insert -->

![Topic analysis module in Communalytic]("Fig. 6 Text analysis with Communalytic")


You have learnt a lot of things, now let's take some time to reflect. Netlytic has allowed you to generate and explore a word cloud based on your corpus, but in what ways precisely did this help you to understand and analyze your data? How useful, or not, has this been for your research? To help you think through these questions, you can read this article that discusses the limits of [word clouds](https://towardsdatascience.com/word-clouds-are-lame-263d9cbc49b7). You can even try to use other tools and compare the visualizations that you get: [Voyant Tools](https://voyant-tools.org/) is one option, but you can browse the [Text Analysis Portal for Research (TAPOR)](http://tapor.ca/home) to pick your preferred tool. Note that using different tools may require you to do some data cleaning  - for instance, you might observe that BlueSky handles are appearing in the word cloud and this is not of great interest - or special formatting. [A quite comprehensive article on data cleaning can be found on Wikipedia](https://en.wikipedia.org/wiki/Data_cleansing). You can also discuss your experience with your colleagues or classmates or even a community of users. 

### Network analysis <a id="section3-3"></a>
Network analysis involves a second kind of analytical operation that one can apply to a social media data corpus. If you are not familiar with this domain, [Marten Duering's lesson on data extraction and network visualization of historical sources](https://programminghistorian.org/en/lessons/creating-network-diagrams-from-historical-sources) offers a nice introduction for beginners. [Once you have your dataset](#section3-1), click on the "Network Analyzer" module and you will see several options for different types of "ties". The ties represent interactions between BluSky accounts, which can be of different types: replying (using the "reply" functionality: your post will then appear below the original post and start or continue a conversation) and quoting (quoting another account’s post with a comment); reposting (quoting another account’s post with no modification), mentioning (publishing a post with another account’s handle in it); and link sharing, which is to say "account-to-website" ties. The BlueSky accounts are the nodes of the network you wish to inspect and the ties of different types are the relationships that connect these nodes between them.  

<!-- insert -->
![Network Analyzer module in Communalytic]("Fig. 7 Network analysis with Communalytic")

Choose the type of interaction you want to examine and click on "Generate Network". You will have the options to download the network data as a GraphML file or a Gephi file, "Visualise Network" or reset the type of interaction you want to worK with.

Here there are two important things to mention. First, the nodes - the BlueSky accounts - are grouped in clusters which means these accounts share some form of similarity. These clusters are calculated by [an algorithm that detects the properties of the network graph and chooses an appropriate layout algorithm](https://rdrr.io/cran/igraph/man/layout_nicely.html). Second, you can [choose a layout](https://communalytic.org/docs/network-analyzer/#network-layout) for the visualisation of the network you study. A layout is a way to display the nodes (BlueSky accounts) and the "edges", which is another way of saying ties or links. A layout allows you to see patterns in the structure of your network. Layouts are based on algorithms, which is why there are different possible layouts. The best layout is the one that fits your dataset and your research purpose, there are no "good" or "bad" layouts per se.

<!-- insert -->

![Graph produced with a dataset of posts]("Fig. 8 Network visualisation of a BlueSky dataset")

You can use the in-built visualiser to experiment with different layouts and see what kinds of visualisations they produce for your network. You can also take a closer look at what constitutes your network. For example, you can explore the metrics that define in what ways the network's nodes are central or not and make these metrics visible by playing with the layout algorithms and exploring in-degree and out-degree filters (the number of inward connections with a node from other accounts versus the number of accounts the node has outwardly connected with). If you wish to focus on different parts of your network, you can can explore "Community Clusters". This will help you to isolate and focus on larger nodes, i.e. have a less detailed but clearer view of your network. Larger nodes represent BlueSky accounts with more interactions with other accounts, the highest being ranked number 1.

Furthermore, Communalytic allows you to layer multiple types of analysis within the network, for example, by running a "Sentiment" analysis on the text of the posts, which uses Natural Lnaguage Processessing (NLP) to score posts for positivity, neutrality, or negativity and can then be represented in the density of edges in the network visualisation. You can explore more in-depth the ways in which sentiment analysis can be used for analyzing social media data in [an article that examines xxx ]. However, the ways in which language in a social media dataset is interpreted will also depend on your research questions and must be read context. All these are different ways of representing the data - but remember, visualisations are interpretations, they are not raw data. If you are happy with the results, you can also save and export your visualisation to integrate it in a future report/presentation.

How can network visualisations be useful for historians? There is a vast bibliography but this is not the object of the current tutorial. What is useful to remember, however, is that you need to fix and focus on a research objective that is part of a historical question. You may benefit from [Martin Grandjean's general introduction to social networks analysis in history](http://www.martingrandjean.ch/introduction-to-social-network-analysis/), which will also help you to learn more about network metrics and structure such as centrality degrees or communities. These are metrics that help analyze social media, and specifically tweets, networks, in order to identify dominant voices (nodes / BlueSky account) in the network (official, news media, themed accounts, cultural institutions, individual influencers...). 

![Communities formed in a graph produced with a dataset of posts]("Fig. 9 Network visualisation of a BlueSky dataset: communities formed by the BlueSky accounts") 

As in the previous type of analysis, you can download your network's data as well and do further analyses with [Gephi](https://gephi.org/) software or your preferred tool of social network analysis. To learn how to use Gephi, you can follow [Martin Grandjean's tutorial](http://www.martingrandjean.ch/gephi-introduction/). 


## Reading suggestions <a id="section4"></a>

For more case studies and tutorials using Communalytic see: https://communalytic.org/how-to/  

LSE Blog - [Using Twitter as a Data Source](https://blogs.lse.ac.uk/impactofsocialsciences/2019/06/18/using-twitter-as-a-data-source-an-overview-of-social-media-research-tools-2019/)

Bruns, Axel, Adam Edwards, Roser Beneito-Montagut, Richard Fitzgerald, and William Housley. 2023. “Social Media Analytics: Boom and Bust?” In *The SAGE Handbook of Digital Society*, edited by William Housley, Adam Edwards, Roser Beneito-Montagut, and Richard Fitzgerald, 249–64. 55 City Road London: SAGE Publications Ltd. https://doi:10.4135/9781529783193.n15.

Ahmed, Wasim, Peter A. Bath, and Gianluca Demartini. 2017. “Using Twitter as a Data Source: An Overview of Ethical, Legal, and Methodological Challenges.” In *The Ethics of Online Research (Advances in Research Ethics and Integrity, vol. 2)*, edited by Bath Peter A. and Kandy Woodfield, 79–107. Bingley: Emerald Publishing Limited. https://doi.org/10.1108/S2398-601820180000002004.

Boyd, Danah, and Kate Crawford. 2012. “Critical Questions for Big Data: Provocations for a Cultural, Technological, and Scholarly Phenomenon.” *Information Communication and Society* 15, no. 5: 662–79. https://doi.org/10.1080/1369118X.2012.678878.

Clavert, Frederic. 2018. “Commémorations, Scandale et Circulation de l’information : Le Centenaire de La Bataille de Verdun Sur Twitter.” *French Journal for Media Research* 10, (special issue: Le Web 2.0 : lieux de perception des transformations des sociétés). http://orbilu.uni.lu/handle/10993/36120.

Gruzd, Anatoliy, and Mai, Philip. 2020. “Going viral: How a single tweet spawned a COVID-19 conspiracy theory on Twitter.” In *Big Data & Society* 7, no. 2. https://doi.org/10.1177/2053951720938405.

Janetzko, Dietmar. 2016. “The Role of APIs in Data Sampling from Social Media.” In *The SAGE Handbook of Social Media Research Methods*, edited by Luke Sloan and Anabel Quan-Haase, 146–60. London: SAGE Publications Ltd. https://doi.org/10.4135/9781473983847.

Rantasila, Anna, Anu Sirola, Arto Kekkonen, Katja Valaskivi, and Risto Kunelius. 2018. “#fukushima Five Years On: A Multimethod Analysis of Twitter on the Anniversary of the Nuclear Disaster.” *International Journal Of Communication* 12: 928–49.

Rockwell, Geoffrey, and Stéfan Sinclair. 2016. *Hermeneutica: Computer-Assisted Interpretation in the Humanities*. Cambridge, Massachusetts: The MIT Press.

Rogers, Richard. 2019. *Doing Digital Methods*. London: SAGE Publications.

Smyth, Hannah and Diego Ramírez Echavarría. 2021. “Twitter and feminist commemoration of the 1916 Easter Rising.” *Journal of Digital History*, 1, no.1. https://journalofdigitalhistory.org/en/article/SLCj9T3MsrEk

Thoreau, Henry David. 2016. "Walking.” In *The Making of the American Essay*, edited by John D’Agata, 167–95. Minneapolis: Graywolf Press.
