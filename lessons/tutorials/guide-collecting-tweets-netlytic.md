---
layout: 
lang: en
unit:
slug: guide-collecting-tweets-netlytic
title: A guide to collecting tweets with Netlytic
requirements: [free text] 
learning outcomes: [list of sentences]
tags: 
author: 
- Frédéric Clavert
- Hannah Smyth 
date: 2022-11-17
---

{% include toc.html %}

## Introduction <a id="section0></a> 
The main learning goal of this tutorial is to enable historians and social scientists to gather Twitter data they can then use as primary sources for research purposes. We will first introduce the reader to the [Twitter application programming interface (API)](https://help.twitter.com/en/rules-and-policies/twitter-api) with particular attention to the limitations of the search API. We will then guide them through a first harvesting of tweets that will be hashtag-based, i.e. using selected hashtags (some examples of historical memory hashtags will be provided). Finally, we will provide a basic analysis of the corpus of the collected tweets, by operating text and social network analysis. 

There are various ways to collect this kind of data; we propose here to use [Netlytic](https://netlytic.org/), an online tool that does not require specific skills in programming. For this tutorial, you need to have both a [Twitter](https://www.twitter.com) and a Netlytic account.   


<!-- 
(optional) Highest level: CSV-related analyses.
nodegoat
VoyantTools 
-->

## Overview of Netlytic <a id="section1"></a>
Netlytic is a cloud-based tool for collecting, visualising, and analysing social media data from several platforms such as Twitter, YouTube, and Reddit. It has specifically been conceived for researchers who need not be familiar with a programming language or with the Twitter API. Netlytic offers three types of accounts (called ‘Tiers’), two of which are free of charge and offer the basic functionalities a user needs to create small projects. For larger projects, a third option is offered via subscription that allows to create more and larger datasets. A free account is largely sufficient to follow this tutorial. 

Once you have an account, you can select the data to collect either using [hashtags](https://en.wikipedia.org/wiki/Hashtag) (#keyword) or simple keywords (not preceded by hashtags), or even replies/mentions (@username), and other custom-built filters. To collect the data, the current version of Netlytic uses the Twitter REST API v1.1. Once collected, the datasets are stored online by default, so users should consider whether this complies with their university's ethical guidelines for social media research. The number of tweets and datasets a user can store at any one time is limited. However, datasets can be downloaded as [CSV files](https://en.wikipedia.org/wiki/Comma-separated_values) for working offline with other programmes and freeing up space for more data collection. After collecting the data, users can also carry out network analysis and basic text analysis. Furthermore, existing datasets can also be uploaded for analysis.

<!-- moved to the Introduction and mentioned as requirements, for what it is of having a Twitter and a Netlytic account. Omitted nodegoat account as nowhere in the tutorial the use of nodegoat is explained.
  
Requirements
Twitter account (https://www.twitter.com)
Netlytic account (https://netlytic.org/)
 
(optional) nodegoat account
-->
## Setting the scene: what is the Twitter API and how does it work? <a id="section2"</a>


*Provide here a definition and a link to a resource (Wikipedia is fine)* 
First assignment: find a definition of an API
(see on wikipedia)

*Present here briefly what the Twitter API is and how it can be useful to the reader. Explain the possibilities but also the limitations* 
Second assignment: the Twitter API
Go there: https://developer.twitter.com/en/docs.


And rephrase with your own words what you understand by the Twitter API. *Let us avoid this and provide instead the basic information to someone who wants to understand what the Twitter API is* 

To have a broader image of the possibilities of the Twitter API, you can read this post: https://help.twitter.com/en/rules-and-policies/twitter-api *Please present here the possibilities*

Third assignment: the twitter API limitations *Please present here the limitations instead of assigning this to the reader - they will very probably not do it*

Go to: https://developer.twitter.com/en/docs/twitter-api/v1/tweets/search/api-reference/get-search-tweets and to: https://developer.twitter.com/en/docs/twitter-api/search-overview 

You will be using the standard Search API for this lesson.

What is the main difference between the Search API and the Streaming API?
Can you name 2-3 limitations of the Search API?

Possible answers:
7 day limit
rate limits
not all matching tweets are captured through the free API
only Premium (i.e., paid) or approved academic accounts can access the full gamot of tweets available through the API
https://developer.twitter.com/en/docs/twitter-api/v1/tweets/search/api-reference/get-search-tweets 
Further reading section:

What is a REST API: https://www.redhat.com/en/topics/api/what-is-a-rest-api 
The COVID-19 stream: https://developer.twitter.com/en/docs/labs/covid19-stream/overview 

## Your first harvest of tweets <a id="section3"</a>

After creating an account on Netlytic, once you are connected, please go to the "My account" bar in the main menu and link your Netlytic account to your Twitter account. Then click on the “Sign in with Twitter” button and follow the instructions. 
This is a mandatory step. If you do not authorize your Netlytic account to access your Twitter account, you will not be able to collect Twitter data.

Before you can begin to collect data, you will need to choose a topic and find your hashtags. To choose a hashtags / keywords, please go the the “How to choose your hashtag?” section below.
Go to “New Dataset” and choose the “Twitter” tab

As you see, you will be asked to choose:
A name for your dataset,
Search keywords
Filters (language, geographic limitations, include / exclude / number of retweets / number of likes / to / from)

Caution, the filters may not be perfect. For instance, while setting the “language” filter to “French” you will have a dataset with a very large majority of tweets in French, but it will also harvest a minority of tweets in other languages. Similarly, because most users do not disclose their location, the geolocation filter may greatly reduce the number of tweets you can collect. You can try the filters by going to the Twitter advanced search interface.  

We will not use those filters, but depending on your research, they might be of great use. For instance, if you are studying the interactions between a museum and its audience, you might want to limit your query to tweets published by the museum’s accounts or the replies to those tweets (using one of the @mention filters). 

Fill in the form (screenshots)



### How to choose your hashtag? <a id="section3-1"</a>
Find a trending topics website or use Twitter’s
Go to Twitter, search for the hashtags, follow the chain of hashtag links to collect the most relevant ones for your query. This is known as the “snowballing” technique.
How big should your corpus be? This will depend on what you want to study and how you want to study it
How to maximise your query - create Boolean queries using keyword combinations, AND and OR statements, exact matches by “putting statements inside smart quotes”, and grouping search terms and operators (inside parentheses) to broaden the corpus. E.g. If I want to find tweets about the commemoration of the women involved in the 1916 Easter rebellion in Ireland, ‘women AND centenary’ would not be specific enough, and we would request (women centenary AND (1916 OR "Easter Rising")) ...
[more advanced] It may not suffice to follow a small set of hashtags depending on the topic. Topics like #Brexit or #Covid19 produce millions of tweets a day; with some exceptions, commemorations generate far less tweets. Therefore you may need to use keywords in addition to hashtags. This type of query can become complex, but can be tested using the Twitter search bar to make sure they return the expected results before implementing them in Netlytic. (use the ‘Test Query on Twitter’ button at the bottom of the page)
Examples of “memorial” hashtags: #ww1 #lestweforget #bloomsday #armisticeday
build corpus over a few days if necessary (anticipate a major/annual commemoration or historic event)
Netlytic allows you to apply filters to search queries for tailored results e.g. limiting to tweets above a certain number of likes, tweets that are from or in-reply-to a specified @user, or tweets that include media (images, links, videos, polls), filtering by language etc.
If there are no tweets that match your query, you will receive an error message.

queue your request / analyses by enabling Netlytic to continue collecting tweets every 15 minutes for a specified number of days (up to one month).

Please beware: the “Test Query on Twitter” will send you to the Twitter search interface (which we advise you to do) but it will not create your dataset. You need to then click on the “import” button to create the dataset. A new page will be loaded: do not close your window and wait for the “You can now close the browser!” message.




Congratulations! You now have your first Twitter dataset ready. Click on “Next Step.”

### Text analysis <a id="section3-2"</a>
In “Preview” you will see a table of the tweets you have collected. Here, you can download an Exel or CSV of your Tweets if you wish. You can also search tweets using the search bar at the top.


Next, click on “Text Analysis” in the tab. Here, you will see two options: “Keyword Extractor” and “Dictionaries”. In the Keyword Extractor, make sure the “field” is set to “description” and then click “Analyze” to generate a word cloud of top terms and hashtags in your dataset (this will be queued in the server and you may need to wait a few moments). Click “Visualize” to see and explore the word cloud. You may also download this as a CSV if you wish.
Click on a keyword or hashtag to see it in context (i.e. where the term appears in the tweets).


In “Dictionaries” click “Analyze”. Dictionaries are groups of words that are linked to concepts. Netlytic has preloaded dictionaries, but you can create your own. From the dictionary, this analysis will create groups of tweets that are linked to those concepts.

You may then visualize the Dictionaries as a “tree graph”. Click on the boxes to dig deeper into the categories, and see the different keywords in context.

If you wish to use a bit more the dictionaries, here is a good example of how you can use them: https://netlytic.org/home/?p=11810 

Task: After exploring your word cloud that you have generated in this assignment, reflect on whether word clouds are useful for analysis and discuss with your classmates. Explain why you think word clouds are useful, or why not.

Further reading on the limitations of word clouds: https://towardsdatascience.com/word-clouds-are-lame-263d9cbc49b7 

(Optional) Download the CSV and explore your data in another text analysis tool such as Voyant Tools (https://voyant-tools.org/) or another tool from TAPOR http://tapor.ca/home. However, this requires data cleaning.

### Network analysis <a id="section3-3"</a>
Next, click on the “Network Analysis” tab. You will see several options for different types of “ties”. Ties are the different relationships between tweeters based on the type of interaction (retweeting, quoting, mentioning, replying).



Choose one, e.g. Retweets and click “Analyze”. You will see the number of tweeters who are tied by retweets or tied in self-loops. Next click “Visualize” and a pop-out will appear of a retweet network visualisation.

There are here two important things to mention:
the nodes (ie twitter accounts) are grouped by clusters. Clusters are calculated based on an algorithm that detects communities of users (see: https://netlytic.org/home/?page_id=2#cmtoc_anchor_id_11 for more details)
you can choose a layout. A layout is a way to display nodes (Twitter accounts) and edges (the links / ties). It allows you to see patterns. There are different possible layouts. For more details on the layouts, see: https://netlytic.org/home/?page_id=2#cmtoc_anchor_id_8 
The “best” layout depends on your dataset and the analysis you would like to perform. There are no “good” or “bad” layouts per se.



Hover over the “nodes” to see usernames. Experiment with different layouts and node sizes (degrees). Uncheck “layers” to remove noise and focus on larger nodes. Uncheck “Edges” (these tie the nodes together) to focus on nodes only. These are different ways of representing the data - remember, visualisations are interpretations, they are not raw data. 
You can also “Save Image” for your report/presentation later.

Task: What do you think network visualization might be useful for? What do you expect to be able to find out from this type of analysis? (Discuss with classmates)

Task: What is the difference between in- and outdegree in a retweet network visualisation?

How can those two types of degree help you identify the dominant “voices” (nodes / Twitter account) in the network ? Official, news media, themed accounts, cultural institutions, individual influencers?

(non mandatory / more advanced) Task: Degree (whether total, in- or out-) are a way to define “centrality” in social networks. Can you define “Centrality”?
Can you define “betweenness centrality” and write why it can be useful for your analysis?

Task: Focus on the two or three biggest communities and try to characterize them.





You can download the file, and then do further analyses with Gephi. To learn how to use Gephi, you can follow this tutorial: http://www.martingrandjean.ch/gephi-introduction/

For a more general introduction to social networks analysis in history, please go to: http://www.martingrandjean.ch/introduction-to-social-network-analysis/ 

## Further Reading and Links <a id="section4"</a>

For more case studies and tutorials using Netlytic see: https://netlytic.org/home/?page_id=11204 

LSE Blog - Using Twitter as a Data Source

Going viral: How a single tweet spawned a COVID-19 conspiracy theory on Twitter

Ahmed, Wasim, Peter A. Bath, and Gianluca Demartini. 2017. “Using Twitter as a Data Source: An Overview of Ethical, Legal, and Methodological Challenges.” In The Ethics of Online Research, edited by Bath Peter A. and Kandy Woodfield, 2:79–107. Advances in Research Ethics and Integrity. Emerald Publishing Limited. https://doi.org/10.1108/S2398-601820180000002004.
Boyd, Danah, and Kate Crawford. 2012. “Critical Questions for Big Data: Provocations for a Cultural, Technological, and Scholarly Phenomenon.” Information Communication and Society 15 (5): 662–79. https://doi.org/10.1080/1369118X.2012.678878.
Clavert, Frederic. 2018. “Commémorations, Scandale et Circulation de l’information : Le Centenaire de La Bataille de Verdun Sur Twitter.” French Journal for Media Research. Special Issue: Le Web 2.0 : Lieux de Perception Des Transformations Des Sociétés 10. http://orbilu.uni.lu/handle/10993/36120.
Janetzko, Dietmar. 2016. “The Role of APIs in Data Sampling from Social Media.” In The SAGE Handbook of Social Media Research Methods, edited by Luke Sloan and Anabel Quan-Haase, 146–60. London: SAGE Publications Ltd. https://doi.org/10.4135/9781473983847.
Rantasila, A, A Sirola, A Kekkonen, K Valaskivi, and R Kunelius. 2018. “#fukushima Five Years On: A Multimethod Analysis of Twitter on the Anniversary of the Nuclear Disaster.” International Journal Of Communication 12: 928–49.
Rockwell, Geoffrey, and Stéfan Sinclair. 2016. Hermeneutica: Computer-Assisted Interpretation in the Humanities. Cambridge, Massachusetts: The MIT Press.
Rogers, Richard. 2019. Doing Digital Methods. London: SAGE Publications.
