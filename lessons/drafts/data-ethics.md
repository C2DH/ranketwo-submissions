---
authors: tugce-karatas 
date: 2026-04-14
title: From sources to data. Ethics and responsibility
learning-objectives: 
 - Conceive the different roles and functions of data, information, and knowledge in managing data for historians
---

Watch the lesson video extract from 00:02:00 to 00:02:07. There, Lea wishes to make digital copies of her grandmother's holdings available through a local history project. To do so, she needs to ensure she has the consent of her aunt, who is the other remaining family member. 

This leads us the ethical dimensions of managing, using, and sharing historical data, though its framing could be tightened for clarity and precision. Ethical concerns—particularly those relating to consent—open onto a broader set of questions central to historical practice, especially when working with living individuals, collective memories, or oral histories. These include not only consent, but also data ownership and the ethical responsibilities involved in the use and dissemination of such materials.

These ethical concerns are not novel. Historians have long engaged with questions of provenance, reliability, and the integrity of their sources. What distinguishes the digital age, however, is not the existence of these issues but their amplification. Digital technologies enable data to circulate at unprecedented scale and speed, to be recombined across contexts, and to reach audiences far beyond those originally envisaged. For instance, a family photograph shared on an online platform can be rapidly downloaded, republished, and algorithmically indexed, while an oral testimony collected for a local history project may be incorporated into widely accessible digital repositories and reused by unforeseen audiences. This shift raises new ethical stakes around control, context, and consent.

This lesson works through the ethical dimensions of historical data management in three assignments that draws on the publicly accessible resources that you will encounter in your own research. The first introduces the core ethical principles in focus — consent, ownership, and cultural sensitivity — through a concrete case study: a record from the Internet Archive of a born-digital oral history project. The second assignment maps these principles onto the full lifecycle of research data, using a Data Management Plan exercise drawn from Lea's local history project. The third brings together the FAIR (Wilkinson et al. 2016) and CARE (Carroll et al. 2020) principles as practical frameworks for responsible data sharing and reusing.

By the end of this lesson, you will be able to:

* identify three key ethical principles and recognise them in real archival situations: 
	* consent
	* ownership
	* cultural sensitivity
* distinguish the phases of the research data lifecycle and name the ethical considerations that may arise at each;
* apply what are called the FAIR and CARE principles to evaluate how a dataset has been — or should be — shared, using real open access repositories.


<!--
### a. Critique systems of data and metadata, while understanding the ethical responsibilities associated with their use.  

> Learning objective: Understand key concepts of data storage, exchange, security, and privacy, while recognizing the ethical implications of data handling.
*Can we identify, say, three important ethical condiderations/principles related to cultural heritage data?*
-->

### From data to information to knowledge — and back again
In everyday language, the terms data, information, and knowledge are often used interchangeably. In the context of data management, however, they refer to distinct categories with different ethical implications (Floridi 2013). Clarifying these distinctions is essential for understanding how ethical responsibility operates at different stages of historical research.
Data, in the technical sense, refers to raw material: individual observations, records, measurements, or artefacts considered in isolation. A name, a date, a photograph, a GPS coordinate, or a voice recording are all examples of data. On their own, they do not carry meaning. Information emerges when data is contextualised: a photograph becomes informative once we know who is depicted, when it was taken, and by whom. Knowledge, in turn, is the interpretive outcome produced by connecting and analysing information; it is what historians construct through their engagement with sources. 
Each of these levels introduces distinct ethical considerations. At the level of data, key questions include whether material was collected with informed consent, who holds ownership, and whether the data is accurate. At the level of information—when data is combined and contextualised—new risks emerge. For example, combining datasets may reveal sensitive details that individuals did not agree to disclose, or enable re-identification even when individual data points appear anonymised. At the level of knowledge—the interpretations and narratives historians produce—ethical concerns shift again: whose perspectives are represented, whose voices are absent, and who benefits or is potentially harmed by the knowledge being created. 
This hierarchy is also central to understanding metadata, a concept that recurs throughout the lesson. When historians deposit datasets in archives, they are not only sharing data but also producing information about that data. Metadata—descriptive, structural, and administrative—shapes how datasets are discovered, interpreted, and reused. As such, metadata creation is not a neutral act but an interpretive and ethical one: decisions about what to include, emphasise, or omit directly influence future use (Baca 2016).


*Exercise*
The oral history archive and the question of consent
The September 11 Digital Archive (https://911digitalarchive.org/) is a born-digital collection created in the aftermath of the 2001 attacks to preserve personal accounts, photographs, and emails contributed by members of the public. At the time of its creation, online social networks did not yet exist; this was one of the first large-scale experiments in crowdsourced digital archiving. The archive was later transferred to the Library of Congress (Cohen and Rosenzweig 2005; Townsend 2010).

Navigate to the archive's collection of personal accounts (https://911digitalarchive.org/items/browse?collection=3). Select any account that interests you and open its individual record page. Read both the content of the account and the information provided about it — its description, rights statement, and any other metadata that accompanies it.

- [ IMAGE: Screenshot of a personal account record from the September 11 Digital Archive ] Personal account record, September 11 Digital Archive. Screenshot, [date].
Now focus on the ethical dimensions of metadata and answer the following questions:

* Is there any information about how consent was obtained from the person who submitted this account? Look carefully at the rights statement, the submission notes, and any contextual description provided by the archive.
* The account was submitted voluntarily by a member of the public. Does voluntary submission constitute consent for all future uses — including uses the submitter could not have anticipated in 2001, such as computational text analysis or AI training data? What do you think, and why?
* Who, in your assessment, 'owns' this account: the person who wrote it, the archive that holds it, the Library of Congress that now preserves it, or some combination of the three? What different kinds of ownership — legal, moral, emotional — might be at stake?
* Now read the archive's own statement about its history and purpose (available at https://911digitalarchive.org/about). Does the archive acknowledge any of the ethical questions you identified above? If so, how? If not, what is missing?

The September 11 Digital Archive is an example of what is called a born-digital archive created from crowdsourced contributions. “Born-digital” indicates that the materials were created in digital form from the outset, rather than being digitised from physical originals. “Crowdsourcing,” meanwhile, refers to the practice of assembling a collection through contributions from a large number of individuals rather than through traditional institutional selection.  

While both characteristics expand the scope and inclusivity of archival collections, they also introduce ethical complexities that differ significantly from those associated with traditional archives.
In conventional archival settings, materials are typically deposited by creators or their heirs under formal agreements that define ownership, access conditions, and permitted uses. These frameworks provide a relatively clear structure for consent and control. By contrast, in crowdsourced born-digital archives, the relationship between contributor and institution is often less formalised and more ambiguous. Contributors may submit materials with limited understanding of how they will be preserved, described, or reused, particularly over the long term. Therefore the expectations of contributors may be very different from the uses that the archive subsequently makes of their contributions (Zaagsma 2022).

As scholars of digital memory have noted, contributors to participatory archives may operate with expectations shaped by personal, commemorative, or community-oriented intentions, rather than by an awareness of archival permanence or scholarly reuse (Theimer, 2011). This creates a potential gap between the perceived context of contribution and the actual conditions of access and circulation. Materials submitted in a moment of immediacy—such as responses to traumatic events—may later be encountered in entirely different interpretive frameworks, raising questions about ongoing consent, contextual integrity, and ethical reuse. 


### b. Data lifecycle 

Learning objective(s): differentiate the distinct phases of life of data and apply the appropriate metadata scheme to each

![Data lifecycle](/images/data-lifecycle.png "Data lifecycle")

Source: [RDMkit: A research data management toolkit for life sciences](https://doi.org/10.1016/j.patter.2025.101345) 

Exercises:
 - Research lifecycle (Plan,Collect, Process, Analyses, Preserve, Share, Reuse)
Technical Specification - 


Exercises: 
- Data Management plan and provenanace table 
- Consent form -Privacy -Ownership of the data 
- Legal perspectives 
- GDPR 
- Data lifecycle (Acquisition, collection, analysis, interpretation, modelling, publication, archiving) 
- Research lifecycle (Plan,Collect, Process, Analyses, Preserve, Share, Reuse) 
- Technical Specification

### The data lifecycle: ethical obligations at every stage
Data does not have a single moment at which ethics becomes relevant. Ethical obligations arise at every stage of a dataset's life — from the initial decision to collect data to its eventual archiving or deletion. This assignment introduces the concept of the research data lifecycle, shows how it is described in two prominent data management frameworks, and asks you to apply it to the case study that runs through this lesson: a local history project involving oral testimonies and family photographs.

Learning outcome: Distinguish the phases of the research data lifecycle and name the ethical and metadata obligations that arise at each.

### Two lifecycle models — and what they have in common
Open the data life cycle overview published by RDMkit, the research data management toolkit developed by ELIXIR Europe (https://rdmkit.elixir-europe.org/data_life_cycle). RDMkit was originally designed for life sciences research, but its data management principles are widely applicable across disciplines, including history and the humanities (Coppens et al. 2021). Read the overview page and examine the diagram of the lifecycle it proposes.
![Data lifecycle](/images/data-lifecycle.png "Data lifecycle")

Source: [RDMkit: A research data management toolkit for life sciences](https://doi.org/10.1016/j.patter.2025.101345) 

The RDMkit model describes a research lifecycle with the following stages: Plan — Collect — Process — Analyse — Preserve — Share — Reuse. Read the brief description of each stage that RDMkit provides.
* At which stage does RDMkit place the question of consent? Is it addressed in the Collection stage only, or does it appear elsewhere?
* Where in this lifecycle do you think the question of ownership most naturally arises? And at which stage might it become most urgent?
* The RDMkit lifecycle ends with 'Reuse'. What ethical obligations might arise specifically at this stage — that is, when data created for one purpose is reused for another?

A second, complementary model is more commonly used in humanities and cultural heritage contexts. It describes the data lifecycle as: Acquisition/Collection — Analysis — Interpretation/Modelling — Publication — Archiving. This model places greater emphasis on the interpretive work that distinguishes humanities research from data science, and on the distinction between publication (sharing findings) and archiving (making the underlying data available for reuse by others) (Owens 2018; Corti et al. 2019).
For the purposes of this lesson, we use a combined model that draws on both:
* Planning: deciding what data to collect, for what purpose, and under what conditions.
* Acquisition/Collection: gathering data, whether by creating it (interviews, surveys, photographs) or by locating it in existing sources (archives, databases, digitised collections).
* Processing/Analysis: cleaning, transforming, and analysing data to produce findings.
* Interpretation/Modelling: drawing conclusions and representing them in argument, visualisation, or model form.
* Publication: sharing findings — and, increasingly, the underlying data — with other researchers and the public.
* Archiving and Reuse: depositing data in a repository for long-term preservation and potential reuse by others.

### Ethics at every stage: an example
Return to the case introduced in the lesson video: a local history project in which Lea has collected oral testimonies and family photographs from community members, and now wishes to make this material available through an online archive. We will trace the ethical questions that arise at each stage of the lifecycle for this project.
For each stage below, we provide a brief description of the situation and a set of questions. If you are working in a class, these can be discussed in small groups; if working alone, write brief notes on each.
Planning
Before collecting any material, Lea needs to make a series of decisions: Who will she approach? What will she ask for? How will she store what she receives? What will happen to it when the project ends?
* At the planning stage, what information should Lea provide to potential contributors about how their material will be used? What constitutes 'informed consent' in this context?
* Should Lea prepare a Data Management Plan (DMP) at this stage? What would such a document contain? (We will return to this in the hands-on exercise below.)
* If Lea is working at a university, what institutional processes might she need to go through before beginning data collection? Think about ethics review boards and data protection officers.
Acquisition/Collection
Lea conducts recorded interviews with twelve community members and receives donations of family photographs. She obtains consent forms from each participant.
* One participant asks that their interview be kept confidential during their lifetime, but made available after their death. How should Lea record and manage this condition? What happens if she loses the consent form?
* The photographs were taken by various family members over several decades. Who holds copyright: the person who took the photograph, the person depicted in it, the person who donated it, or the family as a whole? How would you find out?
* Data minimisation — collecting only what you actually need — is a principle of both the GDPR and good research practice. Are there categories of information Lea should not collect, even if contributors offer them?
Processing/Analysis
Lea transcribes the interviews and creates descriptions (metadata) for the photographs. She uses a spreadsheet to organise the collection.
* The transcription process involves a human reader interpreting a spoken recording. What ethical obligations arise at this stage — both towards accuracy and towards the privacy of the speaker?
* In describing the photographs, Lea needs to identify the people depicted. Some of these people are still alive and were not interviewed. Does she need to seek their consent to name them in the metadata?
* Could the combination of data from different contributors — dates, places, relationships, health information mentioned incidentally in interviews — allow individuals to be identified or harmed in ways that a single record would not? This is called re-identification risk — a well-documented problem in research using linked datasets (Ohm 2010). How would you manage it?
Publication
Lea is now ready to make the collection available online. This is the moment the video extract shows: she realises she needs to return to one participant to confirm consent before proceeding.
* Why might the consent given at the collection stage not be sufficient for the publication stage? Think about the difference between consenting to an interview and consenting to your words being permanently and publicly accessible on the internet (Thompson and Bornat 2017).
* Two participants have died since the interviews were conducted. Their heirs have not been contacted. What are Lea's obligations?
* What licence should Lea attach to the published materials? What are the implications of choosing a Creative Commons Attribution licence (CC BY) versus a more restrictive licence, or no licence at all?
Archiving and Reuse
After the project ends, Lea deposits the collection in a regional digital archive for long-term preservation.
* Should all the materials be deposited, or only those for which there is clear consent for archival access? What happens to the materials that cannot be deposited?
* A researcher contacts the archive ten years later, wanting to use the oral testimonies for a study on urban change. She proposes to apply computational text analysis to the transcripts. Is this use covered by the original consent? How would you find out, and what would you do if it is not?
* The archive proposes to assign the collection a persistent identifier (a DOI) so it can be cited in academic publications. Does this constitute a new use of the data, and does it raise any new consent or ownership questions?

### 2.c Hands-on: Drafting a Data Management Plan and provenance table
A Data Management Plan (DMP) is a document that describes how data will be managed throughout a project. Most research funders in Europe now require one (European Commission 2016). For historians, a DMP serves a second purpose: it is a record of the provenance of the data — where it came from, how it was collected, and what decisions were made along the way.
Using the structure below, draft a short DMP for Lea's local history project. You do not need to write more than two or three sentences per section; the goal is to think through the ethical decisions, not to produce a polished policy document.
Data description: What types of data are in the collection (audio, photographs, transcripts, metadata)? What formats? Approximately what volume?
Consent and legal basis: How was consent obtained from participants? What is the legal basis for processing personal data (e.g. consent, public task)? How will you manage the case of participants who wish to withdraw consent, or who have died?
Ownership and intellectual property: Who holds copyright in the photographs and recordings? What agreements have been made with contributors regarding rights?
Storage and security: Where will the data be stored during the project? Who will have access? How will sensitive data be protected against unauthorised access?
Publication and sharing: Which data will be made publicly accessible, and under what licence? Which data will be restricted, and why? What level of access will be provided for restricted materials (e.g. researchers only, community members only, embargoed until a specified date)?
Retention and archiving: How long will the data be retained? In which repository will it be deposited? What will happen to materials that cannot be archived (e.g. materials for which consent cannot be confirmed)?

Now complete a short provenance table for one type of material in the collection — for example, the oral history recordings. A provenance table records the origin and custody history of a data item. Use the following columns:
Data item | Creator | Date/period | Original purpose | How acquired | Consent status | Rights holder | Transformations applied | Ethical notes
Fill in one row for one item of your choice. This exercise is designed to help you see how much ethical information is embedded in the apparently simple act of describing a source.

Reading/viewing suggestions for assignment 2
* RDMkit (ELIXIR Europe). Data Life Cycle overview. https://rdmkit.elixir-europe.org/data_life_cycle — especially the 'Human Data' section.
* Digital Curation Centre. 'Data Management Plans.' https://www.dcc.ac.uk/resources/data-management-plans
* The Turing Way Community. 'A Handbook for Reproducible, Ethical and Collaborative Data Science.' https://the-turing-way.netlify.app/
* Oral History Society. 'Ethical and Legal Matters.' https://www.ohs.org.uk/ethics/
* UK Data Service. 'Consent for Data Sharing.' https://ukdataservice.ac.uk/learning-hub/research-data-management/ethical-issues/consent-for-data-sharing/


### c. Handle data with care and, if possible, share: how to do this  
> Learning objective: Apply the FAIR (Findable, Accessible, Interoperable, and Reusable) and CARE (Collective Benefit, Authority to Control, Responsibility, and Ethics) principles to ethical data management and sharing
The FAIR principles were published in 2016 by a consortium of researchers, librarians, and data managers. They have since become a standard reference point in open science, required by major research funders in Europe and elsewhere (Wilkinson et al. 2016). Navigate to the original paper in Scientific Data (https://doi.org/10.1038/sdata.2016.18) and read the abstract and the brief description of each principle (pp. 1–3). Then explore the go-FAIR website (https://www.go-fair.org/fair-principles/) for a more user-friendly explanation.
[ IMAGE: Screenshot of the go-FAIR website FAIR principles overview] FAIR Principles overview, go-FAIR.org. Screenshot, [date]. https://www.go-fair.org/fair-principles/
### FAIR stands for:
* Findable: Data and metadata should be easy to discover, using persistent, globally unique identifiers (such as DOIs) and rich, standardised metadata registered in searchable catalogues.
* Accessible: Data should be retrievable under clearly specified conditions, using open and universal protocols. 'Accessible' does not mean 'free for all': some data may legitimately be restricted. What FAIR requires is that the conditions of access be clearly stated.
* Interoperable: Data should use standardised formats, vocabularies, and ontologies so that it can be integrated with other datasets and used by different tools. For historians, this means using recognised metadata schemas (Dublin Core, Europeana Data Model) and controlled vocabularies for names, places, and dates.
* Reusable: Data should be accompanied by a clear licence and sufficient documentation — a README file, a data dictionary, a description of the methodology — so that another researcher can understand and build on it.
Now navigate to Zenodo (https://zenodo.org), an open repository hosted by CERN and supported by the European Commission. Search for a dataset related to oral history or cultural heritage. Select one result that interests you and examine its record page carefully.
* Does the dataset have a persistent identifier (DOI or similar)? Is it cited in a way that would allow another researcher to find it reliably in ten years?
* Is the dataset fully downloadable, or are there access restrictions? If restrictions exist, are they clearly explained?
* What format are the data files in? Are these open, non-proprietary formats (such as CSV, plain text, or open XML standards), or are they proprietary formats that may not be readable without specific software?
* Is there a README file or data dictionary that explains what the data contains and how it was collected? Is this documentation sufficient for you to understand the data without contacting the depositor?
* What licence is attached? Does the licence allow you to use the data for your research purposes? Does it place any conditions on reuse (attribution, non-commercial use, share-alike)?
### CARE: collective benefit, authority to control, responsibility, and ethics
The FAIR principles are technically and administratively powerful, but they say nothing about whether data should be shared, or whose interests should be considered in making that decision. This gap is addressed by the CARE principles, developed by the Global Indigenous Data Alliance (GIDA) in response to growing recognition that open data frameworks designed for scientific efficiency often replicate colonial patterns of extraction from Indigenous communities (Carroll et al. 2020; Tuhiwai Smith 2012).
Navigate to the GIDA website (https://www.gida-global.org/care) and read the brief descriptions of each CARE principle. Then read the executive summary of the original paper (https://doi.org/10.5334/dsj-2020-043 — the abstract and the 'Background' section, pp. 1–3).

CARE stands for:
* Collective Benefit: Data ecosystems should be designed so that the communities whose data is used derive genuine benefit from it. Research that extracts value from communities without returning anything to them fails this standard, however technically FAIR it may be.
* Authority to Control: Indigenous peoples' rights and interests in their data must be recognised, and their authority to control that data must be upheld. Communities should have a meaningful role in decisions about how their data is collected and used, not merely a right to refuse.
* Responsibility: Those who work with Indigenous data have a responsibility to explain how the data is used and to demonstrate that this use supports the community's self-determination and collective benefit. This is ongoing, not a one-time compliance exercise.
* Ethics: Indigenous peoples' rights and wellbeing should be the primary concern at all stages of the data lifecycle. This requires engagement with Indigenous ethical frameworks, not merely the application of institutional review board processes.

While the CARE principles were developed specifically in the context of Indigenous data governance, their underlying concerns — about consent, power, benefit, and community authority — apply to any situation in which researchers use data about communities that have historically been marginalised, exploited, or excluded from the research process. Historians working with data about enslaved people, colonial subjects, asylum seekers, or victims of state violence should ask the same fundamental questions (Risam 2019; D'Ignazio and Klein 2020).
Now return to the same Zenodo dataset you examined in assignment 3.a, or choose a different one from a cultural heritage or historical context. Apply the CARE framework:
* Who does the data describe? Are there living communities — or communities of descendants — whose interests are implicated in this data?
*	Is there any evidence that these communities were involved in designing the data collection, or that they were consulted about how the data would be used and shared?
*	Who benefits from this data being open: researchers, the institution that deposited it, or the communities the data concerns? Try to be specific.
*	Are there uses of this data that would be ethically problematic, even if they are technically permitted by the licence? Can you think of an example?
### Traditional Knowledge Labels: a practical tool
One concrete tool for applying CARE principles to digital cultural heritage is the system of Traditional Knowledge (TK) Labels developed by Local Contexts (https://localcontexts.org/labels/traditional-knowledge-labels/). TK Labels are digital notices that communities can attach to cultural heritage materials held in archives and museums, communicating their terms for access and use.
Navigate to the Local Contexts website and explore the gallery of TK Labels. Each label has a specific meaning — for example, TK Community Use Only indicates that a resource should only be used within the community of origin; TK Sacred indicates that it contains sacred content and should not be reproduced or shared publicly.
[ IMAGE: Screenshot of the Traditional Knowledge Labels gallery, Local Contexts ] Traditional Knowledge Labels gallery, Local Contexts. Screenshot, [date]. https://localcontexts.org/labels/traditional-knowledge-labels/

*	Look at the full set of TK Labels. Which ones would be most relevant to a collection of oral testimonies? Which would apply to photographs of ceremonial events?
*	Now search for a collection on Mukurtu (https://mukurtu.org/), a content management system designed specifically for Indigenous cultural heritage that incorporates TK Labels. How does the presence of TK Labels change the experience of browsing a collection, compared to a standard repository like Zenodo or a library catalogue?
*	Could TK Labels — or something like them — be useful for collections that are not Indigenous in origin but concern other historically marginalised communities? Think about the September 11 Digital Archive or the Schomburg Center collection from assignment 1. What would a community label for those collections look like?

 ### Bringing it all together: evaluating Lea's choices
Lea is ready to deposit her collection. She has three categories of material, each raising different ethical questions:
Oral history recordings and transcripts. Nine of the twelve participants have given explicit consent for public access. Two have asked for their contributions to be restricted to researchers at recognised institutions for twenty years. One — the participant mentioned in the video — has consented to sharing within the local history community, but not with the general public or with researchers outside the region.
Digitised family photographs. All were donated by community members, who signed a deposit agreement allowing publication under a Creative Commons Attribution licence (CC BY). However, several photographs depict individuals whose living relatives have not been contacted.
Transcribed letters and diaries. The original authors died before 1854 and the texts are out of copyright. However, the letters contain detailed information about family conflicts, financial difficulties, and health conditions that living descendants might find distressing if published without contextual framing.
For each category, assess:
*	What FAIR steps should Lea take? Propose a metadata schema, licence, and type of repository appropriate to this material.
*	What CARE considerations apply? Whose interests and authority must be considered beyond the legal minimum?
*	Is there any material that should not be made publicly available — even if it is legally permissible to do so? What alternative levels of access (restricted, embargoed, community-only, unlisted) would be appropriate?

After completing the evaluation, reflect:
*	Is it possible to be both FAIR and CARE compliant at the same time? Do the two frameworks ever pull in different directions? Can you identify a specific case — from Lea's collection or from the repositories you explored — where maximising openness (FAIR) conflicts with protecting community interests (CARE)?
*	The principle 'handle data with care and, if possible, share' is sometimes described as the practical spirit behind FAIR and CARE together. Do you agree that 'if possible' is doing important work in that formulation? What conditions would make sharing impossible, or irresponsible?


### Conclusion
The moment in the video when Lea pauses before publishing her archive — realising she must go back and check consent — is not a mistake or an oversight. It is good research practice. Ethical care is not a hurdle to overcome before the 'real' work of research begins; it is part of the research itself (Hammersley and Traianou 2012).
This lesson has moved through three scales of ethical attention. The first assignment asked you to read existing archival records for the ethical traces they carry: questions of consent, ownership, and cultural sensitivity embedded in the metadata of a born-digital archive and a cultural heritage collection. The second asked you to think systematically about the whole life of a dataset, identifying the ethical obligations that arise at each stage from planning to archiving. The third offered two practical frameworks — FAIR and CARE — and asked you to apply them to real repositories and to the specific dilemma of deciding what to share, how, and on whose terms.
None of these frameworks provides automatic answers. The GDPR sets a minimum legal standard; ethics goes further. FAIR describes what technically responsible sharing looks like (Wilkinson et al. 2016); CARE asks whether sharing serves the interests of those whose lives the data concerns (Carroll et al. 2020). The answer to that question can only come from knowing your sources, knowing the communities behind them, and exercising the kind of informed, reflective judgement that is, in the end, what historical scholarship is for.

Reading/viewing suggestions for assignment 3
*	Wilkinson, Mark D. et al. 'The FAIR Guiding Principles for Scientific Data Management and Stewardship.' Scientific Data 3 (2016): 160018. https://doi.org/10.1038/sdata.2016.18
*	Carroll, Stephanie Russo et al. 'The CARE Principles for Indigenous Data Governance.' Data Science Journal 19 (2020): 43. https://doi.org/10.5334/dsj-2020-043
*	Global Indigenous Data Alliance. CARE Principles. https://www.gida-global.org/care
*	Local Contexts. Traditional Knowledge Labels. https://localcontexts.org/labels/traditional-knowledge-labels/
*	go-FAIR. FAIR Principles. https://www.go-fair.org/fair-principles/
*	Culture Digital Skills. 'Data Ethics in Cultural Heritage: FAIR and CARE Principles.' https://culturedigitalskills.github.io/2024-ethics-data/fair-and-care-principles.html

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



