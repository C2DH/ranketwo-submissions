---
authors: tugce-karatas 
date: 2026-04-14
title: Data criticism. Ethics and responsibility
learning-objectives: 
 - Identify key ethical principles — consent, ownership, and cultural sensitivity — in real archival situations
 - Identify the ethical obligations that arise at each phase of the research data lifecycle
 - Apply the FAIR and CARE principles to evaluate how historical datasets are shared

---

LESSON INTRODUCTION 

Historians have long engaged with questions of provenance, reliability, and the integrity of their sources. Ethical concerns are equally central to historical practice, particularly when working with living individuals, collective memories, or oral histories. These concerns encompass consent, ownership, and the responsibilities involved in using and disseminating such materials.

What distinguishes the digital age is not the existence of these issues but their amplification. Digital technologies enable data to circulate at unprecedented scale and speed, to be recombined across contexts, and to reach audiences far beyond those originally envisaged — raising new ethical stakes around control, context, and consent.

This lesson works through these dimensions in three assignments. The first introduces the core ethical principles — consent, ownership, and integrity — through a born-digital oral history case study. The second maps these principles onto the full research data lifecycle, using a Data Management Plan exercise drawn from a local history project. The third applies the FAIR and CARE principles as practical frameworks for responsible data sharing and reuse.


## 1 From data to information to knowledge: ethics in practice

In everyday language, the terms data, information, and knowledge are often used interchangeably. In the context of data management, however, they refer to distinct categories with different ethical implications (Floridi 2013). Clarifying these distinctions is essential for understanding how ethical responsibility operates at different stages of historical research.

Data, in the technical sense, refers to raw material: individual observations, records, measurements, or artefacts considered in isolation. A name, a date, a photograph, a GPS coordinate, or a voice recording are all examples of data. On their own, they do not carry meaning. Information emerges when data is contextualised: a photograph becomes informative once we know who is depicted, when it was taken, and by whom. Knowledge, in turn, is the interpretive outcome produced by connecting and analysing information; it is what historians construct through their engagement with sources. 

Each of these levels introduces distinct ethical considerations. At the level of data, key questions include whether material was collected with [informed consent](https://en.wikipedia.org/wiki/Informed_consent), who holds ownership, and whether the data is accurate <!--here, the third question, data accuracy, is certainly a stake, but it does not correspond to the third key priniple presented in the introduction, which is cultural sensitivity-->. At the level of information — when data is combined and contextualised — new risks emerge. For example, combining datasets may reveal sensitive details that individuals did not agree to disclose, or enable re-identification even when individual data points appear anonymised. <!-- here when talking about datasets etc we should introduce a link to Moritz's lesson -->At the level of knowledge — the interpretations and narratives historians produce — ethical concerns shift again: whose perspectives are represented, whose voices are absent, and who benefits or is potentially harmed by the knowledge being created. 

This hierarchy is also central to understanding metadata, a concept that recurs throughout the lesson. When historians deposit datasets in archives, they are not only sharing data but also producing information about that data. Metadata — descriptive, structural, and administrative — shapes how datasets are discovered, interpreted, and reused. <!--for the descriptive metadata we should introduce a link to Sofia's lesson--> As such, metadata creation is not a neutral act but an interpretive and ethical one: decisions about what to include, emphasise, or omit directly influence future use (Baca 2016).

### 1.a Who owns the traces of the past? - 40 mins 

Watch the lesson video animation in full. 

Based on the video, consider the following:

* The objects in the suitcase — letters, photographs, tapes — were created by different people at different times. Who do you think owns them now that Lea's grandmother has died?
* Lea takes photographs of the objects and begins describing them on her smartphone. At what point, if any, does she become a creator herself — and what rights might that give her? <!--here is a link to make with Sofia lesson, exercice on postcard from WW1 Europeana-->
* At the end of the video, Lea calls her aunt Maria before making the photographs available online via the local history project. Why do you think she does this? What could happen if she shared them without asking?

<!-- The General Data Protection Regulation (GDPR) governs the processing of personal data about living individuals. A photograph showing a recognisable person — such as Aunt Maria — counts as personal data under the GDPR. Sharing it publicly without consent may constitute a violation, regardless of who legally owns the photograph. -->

Explore further the notions of ownership of data and consent. Search for "GDPR personal data photographs" and read the first result that comes from an official EU source. <!--Sofia: the first result I have is this: https://gdpr-info.eu/recitals/no-51/-->

> **What is the GDPR?** The General Data Protection Regulation (GDPR) is a European Union legal framework that came into force in 2018. It regulates how personal data — any information relating to an identifiable living person, including photographs — may be collected, stored, and shared. It applies to anyone processing personal data within the EU, and gives individuals the right to control how their information is used.

In your own words, what does the GDPR framework protect, and who does it protect it for?
Does it change anything about how you answered the questions above?

<!--simpler alternative for this third part of the exercice: Search for the term "GDPR" on the EUR-Lex website (or on the web) and read the first paragraph of the regulation. In your own words, what does it protect, and who does it protect it for?-->

<!-- the short exercice aims at making learners explore the questions of ownership and consent. Watch video = 5 min, answering the two questions 10 mins, explore GDPR 15 minutes -->

### 1.b Consent in a born-digital archive

For this exercice, you will work with the [September 11 Digital Archive](https://911digitalarchive.org/). 

> The September 11 Digital Archive is a born-digital collection created in the aftermath of the 2001 attacks to preserve personal accounts, photographs, and emails contributed by members of the public. At the time of its creation, online social networks did not yet exist; this was one of the first large-scale experiments in crowdsourced digital archiving. The archive was later transferred to the Library of Congress (Cohen and Rosenzweig 2005; Townsend 2010).

Navigate to the archive's collection of [personal testimonies](https://911digitalarchive.org/collections/show/278). Select any testimony that interests you or one randomly and open its individual record page. Read both the content of the testimony and the information provided about it — its description, rights statement, and any other information that accompanies it.

<!--If the screenshot does not have a fucntion, maybe we can omit it. The archive is not under open license, if need, we should ask for rights of use.-->
<!--
- [ IMAGE: Screenshot of a personal account record from the September 11 Digital Archive ] Personal account record, September 11 Digital Archive. Screenshot, [date]. -->

Now focus on the ethical dimensions of metadata and answer the following questions:

* Can you trace any explicit information about how consent was obtained from the person who submitted this account? Can you find a **rights statement, or submission notes** or any other contextual information? 
* The account was submitted voluntarily by a member of the public. Does voluntary submission constitute consent for all future uses? 

* Now read the archive's own statement about its history and purpose (available at https://911digitalarchive.org/about). Does the archive acknowledge any of the ethical questions you identified above? If so, how? If not, what is missing?

> Tip: The September 11 Digital Archive no longer has an active contribution form. You can consult an archived version from 2004 on the Internet Archive: [Contribute form of the September 11 Digital Archive](https://web.archive.org/web/20040202174803/http://911digitalarchive.org/stories/add.html). This gives you a sense of what contributors were asked to agree to at the time of submission.

Now reflect on the following: 

Who, in your assessment, 'owns' this account: the person who wrote it, the archive that holds it, the Library of Congress that now preserves it, or some combination of the three? <!--What different kinds of ownership — legal, moral, emotional — might be at stake?--> You can also check the next exercice to get inspiration. 


### 1.c When everyone contributes, who owns the archive? 

<!--Challenging the ownership of the archive--> 

You have just explored how the September 11 Digital Archive handles — or does not handle — questions of consent and ownership. Now compare it with a more recent crowdsourced archive: HistorEsch Gesinn, a community history project based in Esch-sur-Alzette, Luxembourg, that collects photographs, documents, and testimonies from local residents.

Navigate to the [contribution form](https://historesch.lu/en/contribute/) of the local history project [HistorEsch Gesinn](https://historesch.lu/en/) and read it carefully.

Now compare the two archives on the following two points and write a short response (150–200 words):

* Consent: How does each archive explain its terms of contribution to potential contributors? Is it clear what contributors are agreeing to when they submit materials? Where do you see differences?
* Ownership: How does each archive address the question of who owns the submitted materials? Is this stated explicitly, or do you have to infer it?

> Tip: The September 11 Digital Archive no longer has an active contribution form. You can consult an archived version from 2004 on the Internet Archive: [Contribute form of the September 11 Digital Archive](https://web.archive.org/web/20040202174803/http://911digitalarchive.org/stories/add.html). This gives you a sense of what contributors were asked to agree to at the time of submission.

### 1.d Intentions, expectations and tensions: what the digital amplifies in the archive - 40 mins

The September 11 Digital Archive is an example of a born-digital archive — that is, a collection of materials created in digital form from the outset — built from crowdsourced contributions, meaning materials voluntarily submitted by members of the public rather than selected by a traditional institution.  

While both characteristics expand the scope and inclusivity of archival collections, they also introduce ethical complexities that differ significantly from those associated with traditional archives.
In conventional archival settings, materials are typically deposited by creators or their heirs under formal agreements that define ownership, access conditions, and permitted uses. These frameworks provide a relatively clear structure for consent and control. By contrast, in crowdsourced born-digital archives, the relationship between contributor and institution is often less formalised and more ambiguous. Contributors may submit materials with limited understanding of how they will be preserved, described, or reused, particularly over the long term. Therefore the expectations of contributors may be very different from the uses that the archive subsequently makes of their contributions (Zaagsma 2022).

As digital scholars have noted, contributors to participatory archives may operate with expectations shaped by personal, commemorative, or community-oriented intentions, rather than by an awareness of archival permanence or scholarly reuse (Theimer, 2011). Materials submitted in a moment of immediacy — such as responses to traumatic events — may later be encountered in entirely different interpretive frameworks, raising questions about ongoing consent and ethical reuse.

Based on the exercices of 1.c and the readings below:
Theimer, Kate. “What Is the Meaning of Archives 2.0.” American Archivist* 74, no. 1 (July 9, 2011): 58–68. https://doi.org/10.17723/AARC.74.1.H7TN4M4027407666.

Zaagsma, Gerben. “Digital History and the Politics of Digitization”. *Digital Scholarship in the Humanities* 38 (2), June 2023, 830–851, https://doi.org/10.1093/llc/fqac050


Write a short reflection (150–200 words) addressing the following:

* Think back to the September 11 Digital Archive and HistorEsch Gesinn. In each case, what do you think motivated contributors to submit their materials? Were they likely thinking about long-term archival preservation, or something else entirely? Do you think Lea has such considerations? 
* Based on the contribution forms you consulted in 1.c, do you think either collection adequately prepares contributors for the future uses their materials might serve — including uses they could not anticipate?
<!--* Formal agreements govern how materials are deposited in traditional archives. What are the advantages and limitations of this approach compared to crowdsourced archives?-->

### Reading/viewing suggestions
 
Theimer, Kate. “What Is the Meaning of Archives 2.0.” *American Archivist* 74, no. 1 (July 9, 2011): 58–68. https://doi.org/10.17723/AARC.74.1.H7TN4M4027407666.

Zaagsma, Gerben. “Digital History and the Politics of Digitization”. *Digital Scholarship in the Humanities* 38 (2), June 2023, 830–851, https://doi.org/10.1093/llc/fqac050

<!-- 
We could define levels as folows: core, going further, advanced. This menas that the first two are necessary, the third is a plus and the fourth is if need for a more in depth exercice, for example in groups. 
1.a Who owns the past? — Core — 30 min
1.b Consent and user-generated sources in a born-digital archive — Core — 30 min
1.c When everyone contributes, who owns the archive? — Going further — 20 min
1.d Intentions, expectations and tensions — what the digital amplifies in the archive — Advanced — 40 min
-->

<!-- 
Editor's note: Sections 1.a and 1.b form the core of this part and are suitable for all beginners (approximately 60 minutes). Section 1.c is recommended for students with more time or curiosity (20 minutes). Section 1.d is an optional deepening exercise intended for more advanced students or seminar contexts (40 minutes). Teachers are encouraged to adapt the selection to their course format and learning objectives.
-->

## 2 The data lifecycle: ethical obligations at every stage

Data does not have a single moment at which ethics becomes relevant. Ethical obligations arise at every stage of a dataset's life — from the initial decision to collect data to its eventual archiving or deletion. This assignment introduces the concept of the research data lifecycle, shows how it is described in two prominent data management frameworks, and asks you to apply it to the case study that runs through this lesson: a local history project involving oral testimonies and family photographs.

### 2.a What a data lifecycle is and how it matters for ethics - 20 mins

Simply put, data lifecycles illustrate the stages of the life of data and the notions that are tied to them (datasets, databases, see lesson 1). The notion was developed as part of data management practices. 

RDMkit is the research data management toolkit developed by ELIXIR Europe (https://rdmkit.elixir-europe.org/data_life_cycle) - the European research infrastructure for life science data. Its data management principles are widely applicable across disciplines, including history and the humanities (Coppens et al. 2021).  

![Data lifecycle](/assets/images/from-sources-to-data/data-lifecycle.jpg "Data lifecycle")

Source: [RDMkit: A research data management toolkit for life sciences](https://doi.org/10.1016/j.patter.2025.101345) 

Go to the [website of the model](https://rdmkit.elixir-europe.org/data_life_cycle) and examine the diagram of the lifecycle it proposes.

The RDMkit model describes a research lifecycle with the following stages: 
* Plan 
* Collect 
* Process
* Analyse 
* Preserve
* Share 
* Reuse

Click on each stage that RDMkit diagram provides and read its description. While reading, pay attention to the following: 

* At which stage(s) is the question of consent explicitly present? 
* Where in this lifecycle do you think the question of ownership most naturally arises? And at which stage might it become most urgent?
* Consider the final stage of 'Reuse'. What ethical obligations might arise specifically at this stage — that is, when data created for one purpose is reused for another?
<!--
A second, complementary model is more commonly used in humanities and cultural heritage contexts. It describes the data lifecycle as: 
* Acquisition/Collection 
* Analysis 
* Interpretation/Modelling 
* Publication 
* Archiving 

This model places greater emphasis on the interpretive work that distinguishes humanities research from data science, and on the distinction between publication (sharing findings) and archiving (making the underlying data available for reuse by others) .-->

For the purposes of this lesson, we use a combined model that draws on RDMkit and (Owens 2018; Corti et al. 2019):
* Planning: deciding what data to collect, for what purpose, and under what conditions.
* Acquisition/Collection: gathering data, whether by creating it (interviews, surveys, photographs) or by locating it in existing sources (archives, databases, digitised collections).
* Processing/Analysis: cleaning, transforming, and analysing data to produce findings.
* Interpretation/Modelling: drawing conclusions and representing them in argument, visualisation, or model form.
* Publication: sharing findings — and, increasingly, the underlying data — with other researchers and the public.
* Archiving and Reuse: depositing data in a repository for long-term preservation and potential reuse by others.

### 2.b Ethics at every stage — tracing the data lifecycle

Return to the video animation: we know that Lea has her family's oral testimonies and photographs from community members, and that she digitised them. Now she wishes to make this material available through the online archive of a local history project. 

By digitising these materials, Lea turned them into digital data. Following the data lifecycle stages, we will trace the main ethical questions that arise at each stage for this project.

For each stage below, we provide a brief description of the situation and a set of questions. If you are working in a class, these can be discussed in small groups; if working alone, write brief notes on each.

**Planning**

As Lea turns the materials she inherited into a collection of digitised data, with the intention to share them, she needs to make a series of decisions. Lea is not a researcher, but the situation she is in can be compared to the beginnings of a research project: at this stage, a reflection is necessary for planning the big lines of what to collect, how to handle it, what the intention is to do with it and how to preserve it to avoid risks of the data being unusable or lost. 

Remember, Lea's collection includes oral histories, audio and video recordings, photos... involving several members of her family and local community, some of whom are still living. 
* Who should she approach based on her materials and what is she likely to ask for? 
* People who will respond to Lea are potential contributors to the project: what information should Lea provide to potential contributors about how their material will be used? What constitutes *informed consent* in this context? 
* How will she store what she receives? 
* What will happen to her project's data once Lea starts to work on other things? Remember, a project has a beginning, a life and an end!

> In research projects that take place in the context of universities, there are institutional processes that are necessary to go through before beginning data collection, for example consultation with ethics review boards and data protection officers. 
A Data Management Plan (DMP), is often asked at this stage (please see 2.c.

<!--
What would such a document contain? (We will return to this in the hands-on exercise below.) **EDITOR NOTE: This is treated in the last subpart wholly, and the DMP is not introduced at the present stage. This makes it complicated to use it here.**
--> 

**Acquisition/Collection**

Imagine that Lea conducts recorded interviews with twelve community members; she also receives donations of more family photographs. She obtains consent forms from each participant.
* One participant asks that their interview be kept confidential during their lifetime, but made available after their death. How should Lea record and manage this condition? What happens if she loses the consent form?
* The photographs were taken by various family members over several decades. Who holds copyright: the person who took the photograph, the person depicted in it, the person who donated it, or the family as a whole? How would you find out?
 
> Data minimisation is the principle of collecting only the information actually needed following the objectives of a project. This means that even if you can, and even if contributors offer it, you do not collect more information than necessary. It is both a principle of regulations on personal data, such as the GDPR, and a good research practice. 

Going further: Are there categories of information Lea should not collect, even if contributors offer them? <!--this is too open a question and with not a lot of help provided to answer it-->

**Processing/Analysis**

Lea transcribes the interviews and creates descriptions (metadata) for the photographs. She uses a spreadsheet to organise the collection.
* The transcription process involves a human reader interpreting a spoken recording. What ethical obligations arise at this stage
	* towards the accuracy of the content 
	* towards the privacy of the speaker
* In describing the photographs, Lea needs to identify the people depicted. Some of these people are still alive and were not interviewed. Does she need to seek their consent to name them if these photos go online?

> When data from different sources—such as dates, locations, relationships, or even incidental health details mentioned in interviews—are combined, they can reveal someone’s identity or expose them to harm in ways that a single piece of data would not. This is known as re-identification risk, a well-documented issue in research that uses linked datasets (Ohm 2010).

Going further: Can you think what Lea could do to manage re-identification risks? <!--this is quite advanced as exercice. If maintained, is it possible to give some tips? Or we could turn this question to an advanced exercice and provide a reading with examples, or not propose it as exercice at all and and give one reading or two, not too complicated, to go further if someone wants-->

**Publication**

Lea is now ready to make the collection available online. <!--This is the moment the video extract shows: she realises she needs to return to one participant to confirm consent before proceeding. <!--not sure this corresponds to the video story, need to confirm and if necessary readjust the text --> 

* Two interviewees have died since the interviews were conducted. What are Lea's obligations — should she contact their heirs, and if so, what for? <!--How/where can we find help to answer these questions? This one seems to be a bit difficult --> 

<details>
<summary><strong>What happens to consent when a contributor dies?</strong></summary>
In most legal frameworks, privacy rights do not survive death — meaning that the personal data of a deceased individual is generally no longer protected under regulations such as the GDPR. However, legal frameworks vary by country, and some national laws do extend certain protections beyond death. Beyond the legal question, there is also an ethical one: even if the law does not require it, many archivists and researchers consider it good practice to notify next of kin before publishing materials involving deceased individuals, particularly when those materials are of a sensitive or personal nature. Oral history associations have developed specific guidelines on this matter.
For guidance: <a href="https://oralhistory.org/archives-principles-and-best-practices-complete-manual/">Oral History Association. Archiving Oral History — Ownership and Rights Management</a>
</details>

* What licence should Lea attach to the published materials? What are the implications of choosing a Creative Commons Attribution licence (CC BY) versus a more restrictive licence, or no licence at all? <!--this is the first time the lesson evokes CC licences and has not explained sufficiently definitions and stakes or provided any other information for learners to do this exercice here. We should adress this-->

<details>
<summary><strong>What is a licence?</strong></summary>
When you make a document, a photograph, or any other creation publicly available, a licence tells others what they are and are not allowed to do with it. Without a licence, the default position in most countries is that all rights are reserved — meaning no one can legally reuse the material without asking permission.
Creative Commons (CC) licences offer a flexible middle ground. They allow creators to share their work while specifying the conditions of reuse. The most common conditions are:

BY (Attribution) — anyone can reuse the material, provided they credit the creator
NC (Non-Commercial) — reuse is permitted for non-commercial purposes only
ND (No Derivatives) — the material may not be modified or transformed
SA (Share Alike) — adaptations must be shared under the same licence

These conditions can be combined. For example, CC BY-NC allows reuse with attribution but not for commercial purposes. The most open licence, CC BY, requires only attribution. The most restrictive, CC BY-NC-ND, limits reuse to non-commercial contexts and prohibits any modification.
For more information: [Creative Commons](https://creativecommons.org/)
</details>

> Sometimes, the consent given at the collection stage may not be sufficient for the publication stage. Think about the difference between consenting to an interview and consenting to your words being permanently and publicly accessible on the internet (Thompson and Bornat 2017).

**Archiving and Reuse**

In the end of the video animation, we see that Lea has the intention to contribute the digital data of her collection to a local history project that will then publish them on the project's website. Lea essentially delegates the responsibility of long-term preservation to a regional digital archive. Also, by making them available online, she also offers the possibility for these materials to be downloaded or shared by anyone and reused in new contexts.  
* Should Lea deposit all the materials of her collection or only those for which there is clear consent for archival access? What happens to the materials that might not be deposited?
* Let's suppose that a researcher contacts the archive ten years later, wanting to use the oral testimonies for a study on urban change. She proposes to apply computational text analysis to the transcripts. Is this use covered by the original consent? How would you find out, and what would you do if it is not?
<!--* The archive proposes to assign the collection a persistent identifier (a DOI) so it can be cited in academic publications. Does this constitute a new use of the data, and does it raise any new consent or ownership questions? => the lesson has not entered in details explaining what a DOI really is and how it is used. We cannot ask learners to do this exercice. Perhaps we can limit the exercices of this stage to the two above, as they cover both archiving and reuse contexts -->

### 2.c Hands-on: Drafting a Data Management Plan and provenance table
A Data Management Plan (DMP) is a document that describes how data will be managed throughout a project. Most research funders in Europe now require one (European Commission 2016). For historians, a DMP serves a second purpose: it is a record of the provenance of the data — where it came from, how it was collected, and what decisions were made along the way.

Using the structure below, draft a short DMP for Lea's local history project. You do not need to write more than two or three sentences per section; the goal is to think through the ethical decisions, not to produce a polished policy document.

- Data description: What types of data are in the collection (audio, photographs, transcripts, metadata)? What formats? Approximately what volume?
- Consent and legal basis: How was consent obtained from participants? What is the legal basis for processing personal data (e.g. consent, public task)? How will you manage the case of participants who wish to withdraw consent, or who have died?
- Ownership and intellectual property: Who holds copyright in the photographs and recordings? What agreements have been made with contributors regarding rights?
- Storage and security: Where will the data be stored during the project? Who will have access? How will sensitive data be protected against unauthorised access?
- Publication and sharing: Which data will be made publicly accessible, and under what licence? Which data will be restricted, and why? What level of access will be provided for restricted materials (e.g. researchers only, community members only, embargoed until a specified date)?
- Retention and archiving: How long will the data be retained? In which repository will it be deposited? What will happen to materials that cannot be archived (e.g. materials for which consent cannot be confirmed)?

Now complete a short provenance table for one type of material in the collection — for example, the oral history recordings. A provenance table records the origin and custody history of a data item. Use the following columns:

| Data item | Creator | Date/period | Original purpose | How acquired | Consent status | Rights holder | Transformations applied | Ethical notes | 
| -------- | ------ | ----- | ------ | ------ | ------ | ----- | ----- | ------ | 
| Aunt Maria's recording | Grandmother | 1982 | New Year's Wish | Donation | Consent given | Aunt Maria | No transformations | Mentions names of now deceased people |  


Fill in one row for one item of your choice. This exercise is designed to help you see how much ethical information is embedded in the apparently simple act of describing a source.

### Reading/viewing suggestions for assignment 2

RDMkit (ELIXIR Europe). Data Life Cycle overview. https://rdmkit.elixir-europe.org/data_life_cycle — especially the 'Human Data' section.

Digital Curation Centre. 'Data Management Plans.' https://www.dcc.ac.uk/resources/data-management-plans

The Turing Way Community. 'A Handbook for Reproducible, Ethical and Collaborative Data Science.' https://the-turing-way.netlify.app/

Oral History Society. 'Ethical and Legal Matters.' https://www.ohs.org.uk/ethics/

UK Data Service. 'Consent for Data Sharing.' https://ukdataservice.ac.uk/learning-hub/research-data-management/ethical-issues/consent-for-data-sharing/


## 3 Handling data with care, sharing if possible

<!--
Need for a short introductive text that familiarises learners with the topic: when and why FAIR and CARE principles

Short introductive phrase to present principles of ethical data management: FAIR, CARE

One small paragraph for: 
Context of inception of the FAIR principles: policies of open data and open science, practices, technical infrastructures, stakes of data sharing and reuse
Specific problem to address: handle the data efficiently in the context of the web infrastructures (machine-readability=> FAIR principles)

One small paragraph for: 
Context of inception of the CARE principles: policies of open data and open science, rise of initiatives on biases and who controls the data (in this case, indigenous data) 

Then in parts 3a and 3b present specifically which are the FAIR and CARE principles, and go to the exercices. 

Exercices need to be simplified, they are too technical. 
Problem: these details are not sufficiently explained (for example what is DOI and all the rest of this stuff), so it is not pedagogically efficient to build exercices without introducing these notions before. But this is a huge subject and also it is not necessarily pertinenet for historians (in the sense that too many details go beyond the scope of the lesson which is much more oriented on the "why" question than the "how" question.   
--> 

Sharing research data responsibly requires both technical rigour and ethical awareness. Two complementary frameworks guide this practice: the FAIR principles, which define the conditions for efficient and sustainable data sharing, and the CARE principles, which ask who benefits from that sharing and whose interests must be protected.

The FAIR principles emerged from the open science movement of the 2010s, which pushed for research data to be shared and reused rather than locked in incompatible systems. Sharing data effectively on the web requires that it be structured and described in ways that machines as well as humans can read and process — this is the specific challenge the FAIR principles were designed to address (Wilkinson et al. 2016).

As open data initiatives expanded, marginalised voices pointed out that frameworks designed for scientific efficiency often replicated patterns of unequal relations of power — collecting data about communities without their meaningful participation or benefit. The CARE principles were developed by the Global Indigenous Data Alliance in direct response to this problem (Carroll et al. 2020).


### 3.a The FAIR principles

Handle data with care and, if possible, share: how to do this  
> Learning objective: Apply the FAIR (Findable, Accessible, Interoperable, and Reusable) and CARE (Collective Benefit, Authority to Control, Responsibility, and Ethics) principles to ethical data management and sharing
The FAIR principles were published in 2016 by a consortium of researchers, librarians, and data managers. They have since become a standard reference point in open science, required by major research funders in Europe and elsewhere (Wilkinson et al. 2016). Navigate to the original paper in Scientific Data (https://doi.org/10.1038/sdata.2016.18) and read the abstract and the brief description of each principle (pp. 1–3). Then explore the go-FAIR website (https://www.go-fair.org/fair-principles/) for a more user-friendly explanation.
<!-- Sofia: the learning objective is too vast for the lesson; instead of apply, it ought to be understand or familiarise with the FAIR principles. The article should be used from the author to gove some hints in the introduction of part 3 about context of inception of the FAIR principles; the other link with the FAIR principles can be used to do the exrcice by the learners-->
<!---->
[ IMAGE: Screenshot of the go-FAIR website FAIR principles overview] FAIR Principles overview, go-FAIR.org. Screenshot, [date]. https://www.go-fair.org/fair-principles/*

<!-- Sofia: I propose in the following list of principles, in each case to keep the initial word (for ex. Findable) and then only the first phrase that gives an elementary explanation. Work some important ones through the exercice by making in hands-on in order for learners to understand by problem. If technical details persist, then add links with explanations of the concept, for ex. to Wikipedia-->
FAIR stands for:
* Findable: Data and metadata should be easy to discover<!--, using persistent, globally unique identifiers (such as DOIs) and rich, standardised metadata registered in searchable catalogues.-->
* Accessible: The conditions of access to data should be clearly stated - based on the understanding that accessibility also means that some data may legitimately be restricted. <!--Data should be retrievable under clearly specified conditions, using open and universal protocols. 'Accessible' does not mean 'free for all': some data may legitimately be restricted. What FAIR requires is that the conditions of access be clearly stated.-->
* Interoperable: Data should use standardised formats, vocabularies, and ontologies so that it can be integrated with other datasets and used by different tools. For historians, this means using recognised metadata schemas (Dublin Core, Europeana Data Model) and controlled vocabularies for names, places, and dates.
* Reusable: Data should be accompanied by a clear statement on the rights if use, usually a licence, and sufficient documentation — a README file, a data dictionary, a description of the methodology — so that another researcher can understand and build on it.

<!--You can explore the [go-FAIR website] (https://www.go-fair.org/fair-principles/) for a more user-friendly explanation. You will use this website in the exercices below-->

Now navigate to [Zenodo](https://zenodo.org), a data repository hosted by CERN, the European Organization for Nuclear Research, and [an open infrastructure of the European Community](https://about.zenodo.org/). Search for a dataset related to oral history or cultural heritage. Select one result that interests you and examine its record page carefully.

We suggest that you work with the following dataset: 
Crymble, Adam, and Emma Azid. “Black Lives, British Justice: Black People in London Criminal Justice Records 1720-1841”. Zenodo, August 28, 2021. https://doi.org/10.5281/zenodo.5304501.
-->

* 1. Does the dataset have a unique persistent identifier such as a DOI (Digital Object Identifier) or similar? 

<details>
<summary><strong>What is a DOI?</strong></summary>
A DOI (Digital Object Identifier) is <a href='https://ask.library.uic.edu/faq/345899'>a string of numbers, letters and symbols used to uniquely identify a digital object</a> - an article, a dataset, a report - and to provide it with a permanent web address so that it can be reliably found and cited. A DOI looks like this: <a href='https://doi.org/10.5281/zenodo.5304501'>https://doi.org/10.5281/zenodo.5304501</a>. Think of it as a digital identity card: it stays with the object permanently and always points to the same resource. DOIs are a key component of the FAIR principles, because findability depends on stable, globally recognised identifiers.
</details>

In the record page, look for the DOI. 

Then read [what a unique identifier is in the FAIR principles context](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/) (estimated time of reading: 3 minutes). 

Then go back to the dataset's record page and check the suggested citation: do you think that it would allow another researcher to find the dataset reliably in ten years?   

* 2. Is the dataset fully downloadable, or are there access restrictions? Where do you find this kind of information in the page? 

In comparison, check a dataset with restricted access: Pepe, Antonio Gerardo, Roberta Alilla, Barbara Parisse, and Flora De Natale. “Historical Dataset from the Italian National Agrometeorological Network (RAN)”. Zenodo, January 21, 2025. https://doi.org/10.5281/zenodo.14710779. In this case, are existing restrictions clearly explained? 


* 3. In what format are the data files available? Are these open, non-proprietary formats (such as CSV, plain text, or open XML standards), or are they proprietary formats that may not be readable without specific software?

<details>
<summary><strong>What is an open file format</strong></summary>
An open file format is a type of file that anyone can open and use, because its structure is public. You don’t need special or expensive software to access it. By contrast, proprietary formats are controlled by companies and often require specific programs. Open formats matter because they help make sure your files will still be usable in the future—even if software changes or disappears. Some common open formats are <a href="https://en.wikipedia.org/wiki/Comma-separated_values">CSV</a> (data), <a href="https://en.wikipedia.org/wiki/Text_file">TXT</a> (text), <a href="https://en.wikipedia.org/wiki/PNG">PNG</a> (images), <a href="https://en.wikipedia.org/wiki/Office_Open_XML">Open XML</a> and <a href="https://en.wikipedia.org/wiki/MP3">MP3</a> (audio). Proprietary formats include .xlsx, .docx, and .psd. The FAIR principles recommend open formats because they make it easier to share, access, and reuse data.
</details>


* 4. Is there a [README](https://ubc-library-rc.github.io/rdm/) file or [data dictionary](https://ubc-library-rc.github.io/rdm/content/07_data_dictionary.html) that explains what the data contains and how it was collected? Is this documentation sufficient for you to understand the data without contacting the depositor?
* 5. How are the rights of use specified? Is it possible to reuse the data and under what conditions? (Tip: here you should look for a licence, as we explain in 2.b) 

### 3.b CARE: collective benefit, authority to control, responsibility, and ethics

The FAIR principles focus on the technical aspects of making data accessible and reusable, but they do not address whether data should be shared or whose interests are considered. The CARE principles were developed by the [Global Indigenous Data Alliance](https://www.gida-global.org/care) (GIDA) to address this gap. They respond to concerns that open data practices, while efficient for science, can reinforce unequal power dynamics and extract knowledge from Indigenous communities (Carroll et al., 2020; Tuhiwai Smith, 2012). More broadly, CARE highlights ethical issues that arise in contexts where power is uneven and some voices are marginalized. Their underlying concerns — about consent, power, benefit, and community authority — apply to any situation in which researchers use data about communities that have historically been marginalised, exploited, or excluded from the research process. Historians working with data about enslaved people, colonial subjects, asylum seekers, or victims of state violence should ask the same fundamental questions (Risam 2019; D'Ignazio and Klein 2020).


CARE stands for:
* Collective Benefit: Data ecosystems should be designed so that the communities whose data is used derive genuine benefit from it. Research that extracts value from communities without returning anything to them fails this standard, however technically FAIR it may be.
* Authority to Control: Indigenous peoples' rights and interests in their data must be recognised, and their authority to control that data must be upheld. Communities should have a meaningful role in decisions about how their data is collected and used, not merely a right to refuse.
* Responsibility: Those who work with Indigenous data have a responsibility to explain how the data is used and to demonstrate that this use supports the community's self-determination and collective benefit. This is ongoing, not a one-time compliance exercise.
* Ethics: Indigenous peoples' rights and wellbeing should be the primary concern at all stages of the data lifecycle. This requires engagement with Indigenous ethical frameworks, not merely the application of institutional review board processes.

More on the [GIDA website](https://www.gida-global.org/care).

Now return to the same Zenodo dataset you examined in assignment 3.a. Apply the CARE framework.

* Who does the data describe? Are there living communities — or communities of descendants — whose interests are implicated in this data?
*	Is there any evidence that these communities were involved in designing the data collection, or that they were consulted about how the data would be used and shared?
*	Who benefits from this data being open: researchers, the institution that deposited it, or the communities the data concerns? Try to be specific.
*	Are there uses of this data that would be ethically problematic, even if they are technically permitted by the licence? Can you think of an example?


### 3.c Going further: Traditional Knowledge Labels

> **Optional — estimated time: 20 minutes**

One concrete tool for applying CARE principles to digital cultural heritage is the system of [Traditional Knowledge (TK) Labels](https://localcontexts.org/labels/traditional-knowledge-labels/) developed by the non-profit organisation Local Contexts. TK Labels are digital notices that communities can attach to cultural heritage materials held in archives and museums, specifying their terms for access and use. Unlike licences, they do not define legal rights of use — rather, they add a layer of community-specific information about the cultural context and sensitivity of materials.

Navigate to the [full set of TK Labels](https://localcontexts.org/labels/traditional-knowledge-labels/) and read the descriptions of two or three labels that interest you.

* Choose one label that you think could apply to a collection of oral testimonies or ceremonial photographs.  <!-- this needs to be really specific and limited say to one concrete example.  --> What does it communicate to a researcher browsing the collection? How does it change what you would do with the material?
* Now consider Lea's collection. Could a label of this kind — or something inspired by it — be useful for any of her materials? Which ones, and why? <!-- this is perhaps too much? if it remains, it should be more defined: pick a type of things in her collection, pick a label that could adpat or that is completely inadapted, and give food for thought  --> 

**Further reading:** Carroll, S.R. et al. "The CARE Principles for Indigenous Data Governance." *Data Science Journal* 19, no. 1 (2020). [https://doi.org/10.5334/dsj-2020-043](https://doi.org/10.5334/dsj-2020-043)


[ IMAGE: Screenshot of the Traditional Knowledge Labels gallery, Local Contexts ] Traditional Knowledge Labels gallery, Local Contexts. Screenshot, [date]. https://localcontexts.org/labels/traditional-knowledge-labels/


**Exploring TK Labels in practice: Mukurtu**

[Mukurtu](https://mukurtu.org/) is a content management system designed specifically for Indigenous cultural heritage. Unlike standard repositories such as Zenodo, Mukurtu integrates TK Labels directly into the browsing experience, allowing communities to communicate the cultural protocols that govern access to and use of their materials.

Navigate to the [Mukurtu showcase](https://mukurtu.org/showcase/) and select one collection that interests you. Browse a few records and pay attention to any TK Labels attached to the materials.

* What TK Labels can you identify in the collection? What do they communicate to a researcher about the conditions of access and use?
* How does the presence of TK Labels change the experience of browsing this collection compared to a standard repository like Zenodo or a library catalogue? What information do you have here that you would not have elsewhere?
* The FAIR principles aim to make data as open and reusable as possible. Do the TK Labels you encountered sit comfortably within a FAIR framework, or do they tension with it? What does this tell you about the limits of FAIR as a universal standard?
* Could a system like Mukurtu — or an adaptation of it — be useful for collections that are not Indigenous in origin but concern other historically marginalised communities, such as the September 11 Digital Archive or oral history collections from communities affected by conflict or displacement? What would need to change?


### 3.d Bringing it all together: evaluating Lea's choices

<!-- Sofia: this is too extended and in many ways beyond what has been developed in the other parts. we should discuss in what ways this could be a collective assignment using elements from all 3 lessons-->

<!-- Sofia: I deactivate the initial version that follows to add a revised version

Lea is ready to deposit her collection. She has three categories of material, each raising different ethical questions:
Oral history recordings and transcripts. Nine of the twelve participants have given explicit consent for public access. Two have asked for their contributions to be restricted to researchers at recognised institutions for twenty years. One — the participant mentioned in the video — has consented to sharing within the local history community, but not with the general public or with researchers outside the region.
Digitised family photographs. All were donated by community members, who signed a deposit agreement allowing publication under a Creative Commons Attribution licence (CC BY). However, several photographs depict individuals whose living relatives have not been contacted.

Transcribed letters and diaries. The original authors died before 1854 and the texts are out of copyright. However, the letters contain detailed information about family conflicts, financial difficulties, and health conditions that living descendants might find distressing if published without contextual framing.
For each category, assess:
*	What FAIR steps should Lea take? Propose a metadata schema, licence, and type of repository appropriate to this material <!-- Sofia: the metadata scheme goes beyond this lesson; there is a small part in the lesson on metadata; repositories are beyond the scope of what we developed in each of the 3 lessons. We cannot ask them to do this unless we add such a part in one of the 3 lessons (Moritz part?) --> <!--
*	What CARE considerations apply? Whose interests and authority must be considered beyond the legal minimum?
*	Is there any material that should not be made publicly available — even if it is legally permissible to do so? What alternative levels of access (restricted, embargoed, community-only, unlisted) would be appropriate?

After completing the evaluation, reflect:
*	Is it possible to be both FAIR and CARE compliant at the same time? Do the two frameworks ever pull in different directions? Can you identify a specific case — from Lea's collection or from the repositories you explored — where maximising openness (FAIR) conflicts with protecting community interests (CARE)?
*	The principle 'handle data with care and, if possible, share' is sometimes described as the practical spirit behind FAIR and CARE together. Do you agree that 'if possible' is doing important work in that formulation? What conditions would make sharing impossible, or irresponsible?
--> 

*revised version*


> This exercise can be completed individually or discussed in small groups.

Lea is ready to deposit her collection. She has three categories of material, each raising different ethical questions:

**Oral history recordings and transcripts.** Nine of the twelve participants have given explicit consent for public access. Two have asked for their contributions to be restricted to researchers at recognised institutions for twenty years. One has consented to sharing within the local history community only, not with the general public or with researchers outside the region.

**Digitised family photographs.** All were donated by community members who signed a deposit agreement allowing publication under a Creative Commons Attribution licence (CC BY). However, several photographs depict individuals whose living relatives have not been contacted.

**Transcribed letters and diaries.** The original authors died before 1854 and the texts are out of copyright. However, the letters contain detailed information about family conflicts, financial difficulties, and health conditions that living descendants might find distressing if published without contextual framing.

For each category, consider the following questions:

* Is there any material that should not be made publicly available — even if it is legally permissible to do so? What would you do with it instead: restrict access, embargo it for a period, make it available to specific communities only, or leave it undeposited?
* What CARE considerations apply? Whose interests and authority must be considered beyond the legal minimum?
* What licence would you attach to the materials that can be shared? Refer back to the Creative Commons callout box in 2.b if needed.

Then reflect on the two frameworks together:

* Is it possible to be both FAIR and CARE compliant at the same time? Can you identify a specific case — from Lea's collection or from the repositories you explored in 3.a and 3.b — where maximising openness conflicts with protecting community interests?
* The phrase *handle data with care and, if possible, share* captures the practical spirit of both frameworks together. Do you think *if possible* is doing important work in that formulation? What conditions would make sharing impossible, or irresponsible?

<!-- in the above version, the questions about metadata schemas and repository types have been removed. The exercise now stays within what students have learned, connects back to earlier parts of the lesson, and ends with two reflection questions.-->


### Conclusion
The moment in the video when Lea pauses before publishing her archive — realising she must go back and check consent — is not a mistake or an oversight. It is good research practice. Ethical care is not a hurdle to overcome before the 'real' work of research begins; it is part of the research itself (Hammersley and Traianou 2012).
This lesson has moved through three scales of ethical attention. The first assignment asked you to read existing archival records for the ethical traces they carry: questions of consent, ownership, and cultural sensitivity embedded in the metadata of a born-digital archive and a cultural heritage collection. The second asked you to think systematically about the whole life of a dataset, identifying the ethical obligations that arise at each stage from planning to archiving. The third offered two practical frameworks — FAIR and CARE — and asked you to apply them to real repositories and to the specific dilemma of deciding what to share, how, and on whose terms.
None of these frameworks provides automatic answers. The GDPR sets a minimum legal standard; ethics goes further. FAIR describes what technically responsible sharing looks like (Wilkinson et al. 2016); CARE asks whether sharing serves the interests of those whose lives the data concerns (Carroll et al. 2020). The answer to that question can only come from knowing your sources, knowing the communities behind them, and exercising the kind of informed, reflective judgement that is, in the end, what historical scholarship is for.

### Reading/viewing suggestions
go-FAIR. FAIR Principles. https://www.go-fair.org/fair-principles/

Wilkinson, Mark D. et al. 'The FAIR Guiding Principles for Scientific Data Management and Stewardship.' Scientific Data 3 (2016): 160018. https://doi.org/10.1038/sdata.2016.18

Global Indigenous Data Alliance. CARE Principles. https://www.gida-global.org/care

Carroll, Stephanie Russo, Ibrahim Garba, Oscar L. Figueroa-Rodríguez, Jarita Holbrook, Raymond Lovett, Simeon Materechera, Mark Parsons, et al. 2020. “The CARE Principles for Indigenous Data Governance”. *Data Science Journal* 19 (1): 43. https://doi.org/10.5334/dsj-2020-043.

D'Ignazio, Catherine, and Lauren F. Klein. Data Feminism. MIT Press, 2020. Open access: https://data-feminism.mitpress.mit.edu/ — especially Chapter 4: 'What Gets Counted Counts.'

<!--
Local Contexts. Traditional Knowledge Labels. https://localcontexts.org/labels/traditional-knowledge-labels/

Culture Digital Skills. 'Data Ethics in Cultural Heritage: FAIR and CARE Principles.' https://culturedigitalskills.github.io/2024-ethics-data/fair-and-care-principles.html

### Reading/viewing suggestions 

Further reading and resources
On data ethics and critical data studies
*	D'Ignazio, Catherine, and Lauren F. Klein. Data Feminism. MIT Press, 2020. Open access: https://data-feminism.mitpress.mit.edu/ — especially Chapter 4: 'What Gets Counted Counts.'
*	Corti, Louise et al. Managing and Sharing Research Data: A Guide to Good Practice. SAGE, 2019.
*	TaNC Ethics as Practice Report (2024). https://doi.org/10.5281/zenodo.13273441
On research data management
*	The Turing Way Community. The Turing Way: A Handbook for Reproducible, Ethical and Collaborative Data Science. https://the-turing-way.netlify.app/
*	RDMkit (ELIXIR Europe). https://rdmkit.elixir-europe.org/ — especially the 'Human Data' section.
*	Digital Curation Centre. How-to Guides. https://www.dcc.ac.uk/resources/how-guides
On oral history ethics and consent
*	Oral History Society. Ethical and Legal Matters. https://www.ohs.org.uk/ethics/
*	UK Data Service. Consent for Data Sharing. https://ukdataservice.ac.uk/learning-hub/research-data-management/ethical-issues/consent-for-data-sharing/
On cultural heritage data and Indigenous data sovereignty
*	Global Indigenous Data Alliance. CARE Principles. https://www.gida-global.org/care
*	Local Contexts. Traditional Knowledge Labels and Biocultural Labels. https://localcontexts.org/
*	Mukurtu CMS (content management for Indigenous cultural heritage). https://mukurtu.org/
*	Caswell, Michelle. 'Toward a Survivor-Centered Approach to Human Rights Archives: Lessons from Cambodia.' Archival Science 10 (2010): 307–322.
Open repositories for practical exercises
*	Zenodo. https://zenodo.org
*	DANS Data Station. https://dans.knaw.nl/en/
*	Harvard Dataverse. https://dataverse.harvard.edu
*	September 11 Digital Archive. https://911digitalarchive.org/
*	NYPL Digital Collections / Schomburg Center. https://digitalcollections.nypl.org/



