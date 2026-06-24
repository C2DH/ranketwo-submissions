---
title: "Historical metro maps as data visualisations"
layout: unit
date: 2026-06-22
publication_date: 
toc: on
research-phase:
  - hermeneutics 
activities: 
  - spatial-analysis
  - data-visualization 
mediatypes:
  - map
authors:
  - Aida Horaniet Ibanez
  - Mariia Meleshko-Sudina
editors: 
  - sofia-papastamkou
reviewers:
- tbd
lang: en
unit_id: historical-metromaps-as-dataviz
link: /u/historical-metromaps-as-dataviz/
permalink: /u/historical-metromaps-as-dataviz/
audience: 
components:
  small: 
  medium:
cover:
  url: 
order: 
og:
  description: 
---
<!-- Check British/US english visualisation/visualization -->

# Code as Heritage

[Introduction](#introduction)

[1 From real world phenomena to data visualization](#1-from-real-world-phenomena-to-data-visualization)

[2 Does data really speak for itself?](#2-does-data-really-speak-for-itself?)

[3 Metro maps as data visualisations and historical sources in context](#3-metro-maps-as-data-visualisations-and-historical-sources-in-context)


## Introduction

This lesson offers an introduction to the critical analysis of metro maps both as historical sources and as data visualisations, using the case study of Kyev’s metro. What you learn in this lesson can be applied to other types of data visualisations, as well as to metro maps of other cities and historical periods.

Data visualisation is the process of representing data visually to support understanding, exploration, and communication. It is important to understand that there are many ways to visualise data where complexity is central to both the representation and the exploration of the data. However, in this lesson we are going to focus on data visualisation with the aim of extracting information as quickly as possible; in the case of the metro, this involves a network graph.

The critical analysis of a data visualisation shares most of the key questions frequently asked about digitised and born digital sources. However, further consideration is required to assess for example the level of abstraction, the impact on cognition and, as we will see in our case study, certain additional questions specific to metro maps (e.g., perceived geography).

In this lesson, you will learn that:
1. **Metro maps as data visualisations** are the result of a transformation pipeline from real world phenonema such as geography or distances, captured as data into nodes and edges, and finally represented as a network graph visualisation.
2. **Data does not speak for itself (and neither does its visualisation)**. There are economic, cultural, political, social and historical histories that metro maps can tell.
3. **Contextualisation is a fundamental practice in data analysis and visualisation**, as well as in the interpretation of historical sources. For that purpose, we will explore how to combine and compare metro maps for a deeper analysis.

Each section includes practical exercises designed to develop your critical thinking, as well as additional resources where you can explore the content further if required.

## 1 From real world phenomena to data visualization

[!NOTE]
*Learning objectives:*
By completing this section, you will be able to:
- Understand the different levels of abstraction from data collection to representation.
- To understand how this translates specfically to metro maps

Does data objectively capture the phenomena taking place in the real world? Drucker says that "by recognizing the always interpreted character of data we have shifted from data to capta, acknowledging the constructed-ness of the categories according to the uses and expectations for which they are put in service" (Drucker,2011). Loukissas explains that "in thinking about when something becomes data, we must lend weight to the material processes involved; measuring, recording, and otherwise capturing the world are processess with physical constraints. (...) Aspects of the original subject are inevitably lost in translation" (Loukissas, 2019).

A data visualisation is a representation of information that involves transforming real-world phenomena into a simplified visual form through a process of abstraction. This process usually includes four steps: 1)A real-world event, system, or situation is observed. 2)Data collection: Information about the phenomenon is gathered through observation, measurement, surveys, records, or technology. 3)Representation: The data is converted into a visual form, 4) The representation is pereceived by the human perceptual and cognitive system.

There is a "widespread belief that large data sets offer a higher form of intelligence and knowledge that can generate insights that were previously impossible, with the aura of truth, objectivity, and accuracy” (Boyd et al., 2012) and "data visualization is often the visual enactment of this "aura of truth". Learning to be a critical reader and designer entails learning productive ways to challenge that aura" (D'Ignazio, 2019). This is therefore the focus of this first section.

### 1.a From phenomena to data

What exactly does this mean? If we look, for example, at a metro map like the one in Image 1, what sort of real-world events lie behind the data needed to create this map? Could you name at least five? How are they collected as data? What sort of decisions do you think might have been made between observing these phenomena and recording them as data? Make a list of five key questions.

<details>
  <summary>Do you need help?</summary>

  Some examples would include geographic phenomena such as distances between stations, elevation changes, administrative boundaries, rivers and waterways; mobility phenomena such as passenger movements, peak-hour demand, origin-destination flows, accessibility needs; socio-economic phenomena such as population density, employment density, urban growth, turist activity; environmental phenomena such as noise levels or weather changes, among many others. These are essentially all the observable events that exist before they are converted into data and then represented into a metro map.

Different phenomena are captured into data using different methods. For example, distances, elevation changes or noise levels would be measured, accessibility needs could be collected using a survey, and turistic activity could be recorded through observation (among other options).

The sort of decisions made during the data collection process are refleced in the decisions about what gets measured, why it gets measured and how it gets measured. For example who is the metro system and the metro map designed for (i.e., who is the target population: workers, turists,...)? Why a data collection method is selected and what are the limitations (i.e.,how was the sample selected)? What tools, instruments, or technologies were used to collect the data? When was the data collected? Who was responsible for the data collection?. These are just some examples of decisions that would alter the result significantly. Would it be the same to collect data for a metro system aimed at commuters travelling from the suburbs to the office districts as it would be to cater for the large numbers of tourists visiting the historic districts? It is important to understand that a critical view of the data collection process is important to challenge any "aura of truth". Additionally, as historians, the answers to all these questions bring relevant historical information as we will see in the next sections.

</details>

A network consists of:
- Vertices (nodes): the objects in the network.
- Edges (links): the connections between those objects.

<details>
  <summary>Can you work out what this data relates to in the case of the underground map?</summary>
Exactly – the nodes are the stations and the links are the underground lines.
</details>
<!-- Additional references for network graphs? Expand explanations? Wait to see if the rest of the content is balanced. -->

### 1.b From data to representation
#### Preattentive processing

Once the data has been collected, the next part of the transformation comes into place, its visualisation. In order to critically approach a representation, we first need to understand how attention is captured and how we organise and interpret what we see. For that purpose, we are introducing in this section two relevant concepts in data visualisation: Preattentive attributes and Gestalt principles.

Look at the two images below, how many fives can you count on the first image? What about the second? Can you see the difference? This is an example of how we can leverage color as a preattentive attribute in data visualisation.

![Color as a preattentive attribute](/assets/images/historical-metromaps-as-dataviz/color-preattentive.jpg)

**Figure 1:** Color as a preattentive attribute. Source: Colin Ware, Information Visualization: Perception for Design
<!-- Replace image but actual image from Colin Ware but a-z.lu does not work. This is a similar example -->

Preattentive attributes are visual features that the human brain notices almost instantly. See below what other preattentive attributes we can use a part from color.

![Preattentive attribute](/assets/images/historical-metromaps-as-dataviz/preattentive-attributes.jpg)

**Figure 2:** Pre-attentive attributes. Source: Colin Ware, Information Visualization: Perception for Design
<!-- Replace image but actual image from Colin Ware but a-z.lu does not work. This is a similar example -->

Why is this important? In data visualisation, certain things are shown "at a glance". For example in the case of metro maps, if you want people to instantly identify a certain information, it should be differenciated from all other information in a preattentive way.

#### Exercise

If you look at the metro map in <!-- Figure X, Masha to select an example from her collection -->:
- What do you notice instantly (i.e., pre-attentively: color hue, intensity, orientation, shapes)?
- Which visual encodings are highlighted?
- Which ones are downplayed?
- How do preattentive attributes affect the perception of centrality?
- What do you observe about the shape of the lines?
- Can you find other metro maps where it was not like that?<!-- Masha: This is a potential place to introduce the history of metro maps -->
- Which stations stand out?
- Which lines dominate visually?

<details>
  <summary>Do you need help?</summary>
  <!-- Masha: Do a visual analysis of a metro map of your collection. I add some ideas below, or we can just leave it as it is more general. -->

Examples in metro maps typically include:
- Color: Different lines use distinct colors so passengers can immediately distinguish routes.
- Shape: Symbols such as circles identify stations or transfer points.
- Size: Larger symbols or text may highlight major stations or hubs.
- Position: The placement of stations and lines helps users recognize connections and direction.
- Orientation: Straight horizontal, vertical, or diagonal lines make routes easier to follow visually.
</details>

Do you think that all the preattentive attributes are equally strong?
<details>
  <summary>Do you need help?</summary>

There are degrees of popout, but in general, the strongest effects are based on color, orientation, size and contrast.
</details>
<!-- Add an example image, it can be a generic one or if we find an example especifically for metro maps -->

To explore this topic further: read Ware Chapter five: Visual Saliency and Finding Information <!-- Fix references -->

#### Gestalt laws

"The visual brain is a powerful pattern-finding engine. There is no other way of presenting information so that structures, groups, and trends can be discovered." (Ware 2019) <!-- Fix references -->. In this section we will discuss: what does it take for us to see a group and what does constitute a visual connection between objects?

The Gestalt Laws of pattern perception are a set of rules that describe the way we see patterns in visual displays, and these translate into a set of design principles for data visualization: 1) proximity, 2) similarity, 3) connectedness, 4) continuity, 5) symmetry, 6) closure, 7) relative size, and 8) common fate.

![Gestalt laws](/assets/images/historical-metromaps-as-dataviz/gestalt.jpg)

**Figure X:** Gestalt laws. Source: Colin Ware, Information Visualization: Perception for Design
<!-- Replace image but actual image from Colin Ware but a-z.lu does not work. This is a similar example -->

#### Exercise
Which Gestalt principles can you observe in Figure <!-- Masha to select a metro map -->? 
- How does the principle of similarity apply: are all the stations represented consistently? Are similar symbols used for differet purposes?Do line colors clearly communicate membership to a specific route?
- What about the principle of proximity: are transfer stations close enough to suggest connectivity? Does spacing help users identify routes?
- Can you maybe observe any features that comply with the principle of Continutiy? (e.g., facility to follow a line without interruption, confusing crosses, line bends to support visual flow,...)

<!-- Masha, this is an alternative place to introduce the history of metro maps as they also evolved based on these principles. -->

As you now understand, there are many decisions behind the data collection and visualisation process, starting from what is counted, to how it's organised and categorised and finally represented. Data visualisation is leveraged to reduce cognitive load so that the user can focus on a specific objective, as in the case of metro maps. However, as we have seen, this also implies abstraction and omission of information <!-- Maybe we can find an additional reference discussing these two terms -->, that we need to be aware of when exploring metro maps as historical sources. 

In the next section we will analyse the specific implications on how metro maps as data visualisations communicate certain historical and political narratives, that require a critical analysis of what is there and how it is represented, and what has been omitted and the potential reasons behind.

To explore this topic further: read Ware Chapter six: Static and Moving patterns <!-- Fix references -->

### Reading/viewing suggestions  <!-- I have also added references here, is it correct? They are mostly the same -->
Drucker, J. (2011). Humanities approaches to graphical display. Digital Humanities Quarterly, 5(1), 1-21.

Loukissas, Y. A. (2019). All data are local: Thinking critically in a data-driven society. MIT press.

d’Ignazio, C., & Klein, L. F. (2016, October). Feminist data visualization. In Workshop on Visualization for the Digital Humanities (VIS4DH), Baltimore. IEEE (Vol. 2, No. 10).

Boyd, danah, & Crawford, K. (2012). CRITICAL QUESTIONS FOR BIG DATA: Provocations for a cultural, technological, and scholarly phenomenon. Information, Communication & Society, 15(5), 662–679. https://doi.org/10.1080/1369118X.2012.678878

D’Ignazio, C. (2019). Data Visualization. In R. Hobbs & P. Mihailidis (Eds), The International Encyclopedia of Media Literacy (1st edn, pp. 1–10). Wiley. https://doi.org/10.1002/9781118978238.ieml0095

Ware, C. (2019). Information visualization: perception for design. Morgan Kaufmann.


## 2 Does data really speak for itself?

[!NOTE]
*Learning objectives:*
By completing this section, you will be able to:
- Understand that data does not speak for itself, nor does its visualization and how a narrative can be controlled through visual saliency.
- How this applies specifically to metro maps and how to read implicit narratives.

Data does not speak for itself, nor does its visualizations. A metro map, for example, encodes economic, cultural, political, social, and historical narratives. Now that you understand how data can be visually encoded, you can examine how saliency is used to emphasize certain narratives. This section focuses on developing an awareness of that saliency in any representation.

### 2.a Controlling the saliency 

#### Exercise

We will start this section with an exercise, exploring the following example: 
 [The New York Times' One Report Diverging Perspectives](https://archive.nytimes.com/www.nytimes.com/interactive/2012/10/05/business/economy/one-report-diverging-perspectives.html)

- How does the same report present diverging perspectives? Switch between "How a democrat might see things" and "How a republican might see things?"
- What visual elements change in the representation?
- How does the visualisation look like without any of those elements? Click on "September Jobs Report".
- How do you think would the readers decide what's the narrative?
- Can you make a list of the visual elements used to control the saliency?

<details>
  <summary>Do you need help?</summary>
Some of the elements used to control the narrative in the example include:
- Modifying the x-axis to present partial data.
- Using color to highlight specific values or a range of values.
- Adding reference lines as a baseline for comparison, to measure success or failure.
- The use of titles, subtitles, and explanatory text.
- The use of annotations to highlight important figures.

If we look at the visualization without any of these elements, the readers could be influenced by their expertise in the subject, their political opinions or their level or visual data literacy, among others.
</details>

"If grouping, highlighting, and annotation can guide viewers toward a certain comparison or pattern, then for better or worse, a visualization designer has some control over what their viewers see in a data set. "(Franconeri et al, 20212)<!-- Fix references -->

To know more about the complexities of truth and deception in visualisation, please read:
Cairo, A. (2016). The truthful art: Data, charts, and maps for communication. New Riders.
Cairo, A. (2019). How charts lie: Getting smarter about visual information. W.W. Norton <!-- Move to suggested reading and keep here only the references -->

### 2.b Controlling saliency in metro maps

#### Exercise

Now, we will focus on a metro map. )<!-- Masha to select a metro map -->

Please try to answer the following questions, grounding your answers in the visual elements and how the saliency of the map is controlled:

- What kind of city does the metro map suggest: ordered, complex, dense, accesible, equal, hierarchical, modern,...?
- What routes are perceived as more used, more important, more efficient?
- Which aspects of the map have been highlighted or simplified and why could that be? What assumptions did the designers make about the passengers’ perspective and priorities? Whose mobility is prioritised?
- Is it tourist-centric, commuter centric, etc. and why? What are the key stations? 
- Do the choices about language or naming conventions encode colonial, political and cultural legacies?
- What additional modes of transport are shown?
- How does the metro map encode power structures?

<details>
  <summary>Do you need help?</summary>
  <!-- Masha to do an analysis of the selected metro map -->
</details>

### Reading/viewing suggestions 

Franconeri, S. L., Padilla, L. M., Shah, P., Zacks, J. M., & Hullman, J. (2021). The science of visual data communication: What works. Psychological Science in the public interest, 22(3), 110-161.

Cairo, A. (2016). The truthful art: Data, charts, and maps for communication. New Riders.

Cairo, A. (2019). How charts lie: Getting smarter about visual information. W.W. Norton

## 3 Metro maps as data visualisations and historical sources in context 
<!-- This section is mostly the historical section for Masha to develop. Structure it differently if needed, also include the visualization from your thesis about depth, etc. -->

"Meaning is context-bound, and context is boundless" (Culler, 1998) - from a lecture at Cornell University (mentioned in All data is Local, Loukissas page 15)<!-- Fix references -->

Contextualisation is a key practice both in critical analysis of data visualisation and historical sources. How do we look at metro maps in combination with other maps? What new perspectives does it offer to look at the multiple versions of the same metro maps (e.g., official one vs. construction map), the official map over time, or in combination with other maps (e.g, Olympics, Internet coverage)? What contradictions do we find, and what information appears and disappears among them or over time?

[!NOTE]
*Learning objective:*
By completing this section, you will be able to:
- Contextualise the historical setting of a metro map by comparing it with other metro and geographical maps.

### 3.a 
The evolution of the same map and multiple versions of a mal
<!-- Masha to work on this section, doing a critical analysis comparing multiple maps -->

### 3.b
Other maps: thematic, internet coverage, etc.
<!-- Masha to work on this section, doing a critical analysis comparing multiple maps -->

### Reading/viewing suggestions  
This is mostly Masha's section to add plenty of examples and guided analysis.
<!-- Masha to add the reading suggestions -->
