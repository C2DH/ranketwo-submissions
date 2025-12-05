---
title: "Code as Heritage"
layout: unit
date: 2025-11-12
publication_date: 
toc: on
research-phase: 
activities: 
  -  
mediatypes:
  - 
authors:
  - titayna-kauffmann-will
editors: 
  - valerie-schafer
  - sofia-papastamkou
reviewers:
- tbd
lang: en
unit_id: code-as-heritage
link: /u/code-as-heritage/
permalink: /u/code-as-heritage/
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
# Code as Heritage

[Introduction](#introduction)
[1 Understanding Digital Heritage Recognition](#1-understanding-digital-heritage-recognition)
[2 Learning to Read Code as Cultural Text](#2-learning-to-read-code-as-cultural-text)
[3 Software Heritage: Preserving Code for the Future](#3-software-heritage-preserving-code-for-the-future)
[4 Potential uses of preserved code](#4--potential-uses-of-preserved-code)

## Introduction
Source code represents one of the most important forms of born-digital heritage today. Why preserve and study historical code? This lesson will help you answer these questions, and demonstrates how the intellectual, cultural, and social contexts of code’s creation matter, making it a valuable historical resource for understanding our digital age. This lesson introduces you to applying traditional source criticism methods to digital materials, teaching you to view code as both a technical and cultural artifact. At its most basic level, source code consists of human-readable computer instructions, but as we will explore, it is much more than mere technical documentation. The methodological approach through this lesson focuses on three key skills: contextual analysis, critical evaluation, and comparative assessment—rather than technical programming skills. While designed for beginners in digital source criticism, some exercises will require basic digital navigation skills and familiarity with academic research practices.

In this lesson, we will guide you through four key dimensions of understanding code as heritage:
1.	Heritage Classification: We will first examine what qualities make source code a distinctive type of born-digital heritage. This includes understanding how UNESCO recognizes it and exploring the unique preservation challenges it presents.
2.	Interpretive Methods: Next, we will learn strategies for reading and interpreting code that go beyond its technical functionality. We will approach code as a cultural artifact that reveals important insights about its creators' assumptions, values, and practices.
3.	Preservation Initiatives: We will then analyse several important preservation efforts, with special focus on Software Heritage, an international initiative dedicated to preserving software source code. We'll also examine complementary projects like GitHub Archive and the Internet Archive.
4.	Practical Applications: Finally, we will explore some valuable ways preserved code can be used in research—ranging from artificial intelligence development to historical research.
Each section includes practical exercises designed to develop your critical thinking about digital sources rather than technical programming skills. By the end of this lesson, you will understand how to approach source code as a historian, recognizing its possibilities as historical evidence. 

## 1 Understanding Digital Heritage Recognition

### 1.a Defining Source Code: Between Technical Function and Cultural Expression - 25 min
To define our object of study, let's consider Harold Abelson and Gerald Jay Sussman's insightful 1996 observation that remains highly relevant in today's programming best practices: "Programs must be written for people to read, and only incidentally for machines to execute." What does this mean? Source code can be defined as the fundamental set of instructions of a program; human-readable computer commands written in higher-level programming languages that require compilation or interpretation to become executable ([Krysa & Sedek 2008: 237](https://monoskop.org/images/a/a1/Fuller_Matthew_ed_Software_Studies_A_Lexicon.pdf#%5B%7B%22num%22%3A515%2C%22gen%22%3A0%7D%2C%7B%22name%22%3A%22Fit%22%7D%5D)). 

This definition helps us understand an essential tension in computing: while source code is ultimately designed to be executed on a machine, it is also fundamentally a form of human communication that bears witness to its historical context and contains valuable traces of the past.

Computer scientist Darrell Ronald Raymond emphasizes this in his 1991 article Reading source code: "the main role of source code is not a compilable entity, but a human-readable statement of intent and mechanism in the program" ([1991:3](https://dl.acm.org/doi/10.5555/962111.962113)). This also implies that code is more than written words. It is both an object and an action, simultaneously enabling and constraining activities ([Méadel and Sire 2017](https://shs.cairn.info/revue-reseaux-2017-6-page-9?lang=fr&tab=texte-integral)).

The socio-technical nature of source code creates definitional challenges in our terminology. What exactly do we mean by "programs," "software," and "source code"? Though often used interchangeably, each term has distinct meanings: source code refers to human-readable instructions intended to be executed by the machine; software encompasses the broader ecosystem including compiled programs, documentation, and user interfaces; programs typically denote the executable files that run on computers. 

### 1.b Born-Digital Heritage: How Source Code Gained Official Recognition - 20 min
Let's explore how source code became recognized as cultural heritage. The 2003 UNESCO Charter on the Preservation of Digital Heritage represented a significant milestone in this journey. It formally acknowledged that born-digital materials—content that originates in digital form—constitute an important part of our cultural legacy. These materials include databases, websites, software, and other digital content that have never existed in physical form.
Why was this recognition important? By officially affirming the historical and cultural value of digital materials, UNESCO effectively placed them on equal footing with traditional heritage forms like monuments and artifacts, highlighting their significance for future generations.

However, it did not explicitly address source code preservation ([UNESCO 2009](https://unesdoc.unesco.org/ark:/48223/pf0000179529)). How did this evolve? It wasn't until 2023 that UNESCO clearly articulated the importance of preserving software source code as digital heritage for sustainable development, acknowledging its value across multiple domains: education, research, and cultural preservation ([UNESCO 2023](https://www.unesco.org/en/articles/positioning-software-source-code-digital-heritage-sustainable-development)).

**Exercice – Analyzing UNESCO's Recognition of Source Code**
Now, let's explore two documents to gain a better understanding of how digital heritage recognition has evolved over time and the challenges faced by preservation efforts. These readings will help you grasp the historical context and current thinking around source code preservation.

* [Charter on the Preservation of the Digital Heritage (2003)](https://unesdoc.unesco.org/ark:/48223/pf0000179529) - Focus on definitions and scope (sections 1-3)
* ['Positioning Software Source Code as Digital Heritage for Sustainable Development' (2023)](https://www.unesco.org/en/articles/positioning-software-source-code-digital-heritage-sustainable-development)

Questions for reflection:

1.	How does the 2003 Charter define digital heritage, and where might source code fit within this definition? Consider the language used and the types of materials mentioned.
2.	Looking at the 2023 UNESCO article, what specific arguments are presented for treating source code as heritage? How has this perspective evolved over the twenty years since the original Charter?
3.	What specific benefits does code preservation offer to society, and in which fields (legacy, research, etc.) is it recognized as having particular value?

### 1.c The Fragility of Code: Understanding Digital Preservation Challenges - 15 minutes
Among the key threats to source code is the potential for a Digital Dark Age ([Silva 2022](https://www.softwareheritage.org/2022/06/28/all-of-humankinds-source-code-in-a-nutshell/?lang=fr)), which refers to the possible loss of vast amounts of digital information. To understand this concept better, let's examine three main factors that contribute to this risk:

* Technological obsolescence: When hardware and software systems become outdated
* Platform changes: When services hosting code shut down or significantly change
* The ephemeral nature of digital storage: Digital media degrades over time

Why should we care about preserving historical code? This question is critical for historians and cultural preservationists to consider. Digital materials require intentional and continuous preservation strategies ([Conway 1996](https://www.clir.org/pubs/reports/conway2/index/)). Source code faces particular vulnerabilities: programming languages evolve, development platforms disappear, and the original context of creation can be lost within years of a program's abandonment.

Consider the case of early video games, where entire genres and artistic movements have been lost because the original source code was not preserved ([Lowood 2016](https://ieeexplore.ieee.org/document/5223982)). Many classic arcade games like Jet Set Willy ([Aycock et al. 2017](https://intarch.ac.uk/journal/issue45/2/index.html)) survive only as reverse-engineered approximations after their original code was lost through corporate restructuring, technological changes, or simple neglect. Likewise, early web applications, mobile apps, and desktop software that fundamentally shaped our computer interactions have disappeared, taking with them vital evidence of digital culture's evolution ([Kirschenbaum and Ovenden 2014](https://www.clir.org/pubs/reports/pub149/)).

This loss extends far beyond just individual programs - it affects entire development ecosystems. Think of it like this: as programming languages become obsolete and development tools disappear, the specialized knowledge of working with these particular systems gradually scatters as communities evolve and move on to newer technologies ([Shustek 2006](https://ieeexplore.ieee.org/document/4042496)). The resulting impact is both technical and cultural in nature: we lose valuable access to the creative processes that developers used, the collaborative practices they established, and the innovative solutions they created - all of which defined significant periods in computing history.

Amid these losses, remarkable stories of recovery and reconstruction offer hope. The Apollo 11 source code, once considered lost, was meticulously reconstructed using printed documentation and surviving code fragments ([Cosmo 2019](https://www.softwareheritage.org/2019/07/20/archiving-and-referencing-the-apollo-source-code/?lang=fr)). This restoration revealed more than just the technical brilliance behind the moon landing software—it uncovered the working methods, naming conventions, and even humor embedded by NASA's programming team. These discoveries provide unique insights into 1960s aerospace computing culture that descriptive historical sources alone could never capture.

**Exercise – Examining some Heritage needs and Efforts**
In this activity, you will compare and analyze two perspectives on code preservation. Read both articles carefully to identify their approaches to digital heritage preservation and the challenges they address.

* [I tried to find a way to preserve code for 69 years (this is not a joke)](https://museumofscreens.wordpress.com/2022/12/09/how-to-preserve-code-for-69-years-this-is-not-a-joke/) 
* [Vanishing Culture: Recovering Lost Software](https://blog.archive.org/2025/05/07/vanishing-culture-recovering-lost-software/)

Questions for reflection:

1.	Identify common elements: What shared goals, concerns, and types of code do both articles discuss?
2.	Analyze preservation challenges: What specific technical and cultural obstacles do both authors encounter in their preservation efforts?
3.	Compare methodological approaches: How do their different approaches reflect the broader challenge of code preservation?

## Reading/viewing suggestions 

Digital Heritage Theory and Practice

Musiani, F., & Schafer, V. (2016). Digital Heritage and Heritagization. RESET. Recherches En Sciences Sociales Sur Internet, 6. https://doi.org/10.4000/reset.806

Conway, Paul. 1996. Preservation in the Digital World. Commission on Preservation and Access. https://www.clir.org/pubs/reports/pub154/

Foundational Texts on Code as Communication:

Krysa, Joasia, and Grzesiek Sedek. 2008. 'Source Code'. In Software Studies, edited by Matthew Fuller. The MIT Press. https://doi.org/10.7551/mitpress/9780262062749.003.0034

Méadel, Cécile, and Guillaume Sire. 2017. 'Les sciences sociales orientées programmes. État des lieux et perspectives'. Réseaux (Paris) 206 (6): 9–34. https://doi.org/10.3917/res.206.0009

Case Studies in Code Recovery and Loss:

Coding with Dee, dir. 2024. This Is the Code That Sent Apollo 11 to the Moon (and It's Awesome). 19:08. https://www.youtube.com/watch?v=XHN6LV_1dWk

Cosmo, Roberto Di. 2019. 'Archiving and Referencing the Apollo Source Code'. Software Heritage, July 20. https://www.softwareheritage.org/2019/07/20/archiving-and-referencing-the-apollo-source-code/?lang=fr

Lowood, Henry. 2009. 'Videogames in Computer Space: The Complex History of Pong'. IEEE Annals of the History of Computing 31 (3): 5–19. https://doi.org/10.1109/MAHC.2009.53

Aycock, John, Andrew Reinhard, and Archaeogaming. 2017. 'Copy Protection in Jet Set Willy: Developing Methodology for Retrogame Archaeology'. Internet Archaeology, no. 45. https://doi.org/10.11141/ia.45.2

Kirschenbaum, Matthew G., Richard Ovenden, Gabriela Redwine, and Rachel Donahue. 2010. Digital Forensics and Born-Digital Content in Cultural Heritage Collections. CLIR Publication 149. Council on Library and Information Resources. https://www.clir.org/pubs/reports/pub149/

Shustek, Len. 2006. 'What Should We Collect to Preserve the History of Software?' IEEE Annals of the History of Computing 28 (4): 112–111. https://doi.org/10.1109/MAHC.2006.78


## 2 Learning to Read Code as Cultural Text 
Understanding source code as a historical source requires developing new literacy skills that bridge technical and cultural analysis. Think of it this way: just as historians learn to read ancient manuscripts without becoming scribes, you don't need to become a programmer to analyze code historically. If some resources to learn to code are listed below, what you do need is to understand how to read code as a form of human communication and cultural expression.

Source code is fundamentally a form of writing—a way humans communicate instructions, ideas, and solutions to both computers and other humans. Like other written forms, it bears the marks of its author's background, the conventions of its era, and its cultural context. Programming languages function similarly to human languages in that they have their own grammar, style conventions, and cultural associations that evolve across different communities and historical periods.

### 2.a External Criticism: Establishing Authenticity and Some Context - 15 minutes 
	
External criticism focuses on establishing the authenticity, provenance, and historical context of sources - the foundational work that must precede interpretation.

**Establishing Provenance and Authenticity:** When encountering code, begin with fundamental questions of authenticity: Who wrote this code? When was it created? Where did it originate? How did it reach us? Just as historians carefully verify the authenticity of manuscripts or documents, we must establish the credible origins of code. Sometimes, proprietary source code becomes available through unauthorized leaks. For example, in 2023, portions of Twitter's source code were leaked on GitHub, revealing aspects of their recommendation algorithm ([Yu 2023](https://www.wowebsites.com/blog/2023/04/twitter-algorithm-code-leaked-and-released-an-explanation/)).

**Technological and Historical Context:** Programming languages provide crucial chronological markers. FORTRAN indicates scientific/academic origins from the 1950s-60s, JavaScript suggests web development post-1995, while Assembly language points to system-level programming across various eras. Each language connects to specific communities, time periods, and technological constraints.

**Dependencies and Networks:** You should examine what external code a program relies on as it reveals networks of collaboration and influence. Like citations in academic papers, dependencies show how programmers built upon existing work and participated in broader development communities. For example, the Internet is so dependent on Open Source code that in 2016 a single man was capable of breaking the Internet for several minutes by suppressing 11 lines of code ([Collins 2016](https://qz.com/646467/how-one-programmer-broke-the-internet-by-deleting-a-tiny-piece-of-code)).

**Exercise – External Criticism of Microsoft GW-BASIC Code**

Now, let's approach this code analysis systematically. First, we will conduct an external analysis of this code snippet - examining its context, origins, and metadata - before proceeding then to internal criticism. 

```

; [ This translation created 10-Feb-83 by Version 4.3 ]

    .RADIX    8        ; To be safe

CSEG    SEGMENT PUBLIC 'CODESG'
    ASSUME    CS:CSEG

INCLUDE BINTRP.H

    TITLE    GWMAIN Copied from BINTRP.MAC

    .RADIX    10

COMMENT *

--------- ---- -- ---- ----- --- ---- -----
COPYRIGHT 1975 BY BILL GATES AND PAUL ALLEN
--------- ---- -- ---- ----- --- ---- -----

ORIGINALLY WRITTEN ON THE PDP-10 FROM
FEBRUARY 9 TO  APRIL 9 1975

BILL GATES WROTE A LOT OF STUFF.
PAUL ALLEN WROTE A LOT OF OTHER STUFF AND FAST CODE.
MONTE DAVIDOFF WROTE THE MATH PACKAGE (F4I.MAC).

*

    .XLIST

```

Guided Analysis Questions for External Criticism:

1.	**Who is the author of this code according to this snippet?** What evidence do we have about the authorship and dating of this code? How reliable are the internal claims about Gates, Allen, and Davidoff's contributions?
2.	**Carefully analyze the dates mentioned in the code comments.** Why would code originally written in 1975 still be incorporated into software released in 1983? What does this suggest about software longevity and the evolutionary nature of programming?
3.	**Programming Language and Product Type:** Looking at the title "GWMAIN" and knowing this is early Microsoft code from Bill Gates and Paul Allen, what do you think "GW" might stand for? (Hint: Think of a simple programming language that starts with "B" - one that was designed to be easy for beginners to learn and was very popular on early home computers.)
4.	**Consider the concept of code translation:** Think about what it means when code from 1975 needed to be "translated" for use in 1983. Just as human languages evolve with new vocabulary and grammar rules, programming languages and environments change significantly over time. Why might code that's only 8 years old require translation?

### 2.b Internal Criticism: Interpreting Content and Meaning - 20 minutes
Internal criticism examines the content itself - what the source tells us about its creators, context, and the broader historical moment. Having established the basic authenticity and provenance of our source, we can now analyze what its content reveals about historical attitudes, practices, and power structures.

**Question the broader context.** When and why was this code written ? In what environment? What problem did it address? What technological constraints existed? Can you create a technological genealogy ? You can then deepen the provenance and authenticity aspect from the internal criticism. 
**Linguistic and Cultural Markers:** Just as a historian might analyze handwriting or paper type, we can examine source code for cultural fingerprints:
* Naming conventions: Variable names like "colorPreference" versus "couleurPreference" can reveal a developer's native language
* Comments: The style and thoroughness of documentation often reflects cultural attitudes toward collaboration
* Programming style: How code is structured and formatted can indicate where and how a developer was trained

> The use of English-based keywords in programming languages like "if," "else," "for," and "while" reflects the dominance of English-speaking countries in early computing history, creating barriers for non-native English speakers. Cultural factors influence programming language design. Some languages tend toward straightforward, more explicit or verbose syntax with clear variable declarations ([Walton 2024](https://rotel.pressbooks.pub/culturally-responsive-computing/chapter/the-culture-of-programming/)).

**Code structure and style:** Think of code as having its own "writing style," just like how authors have different ways of organizing their paragraphs and sentences. When examining historical code, pay attention to how it's organized and formatted. 
This can tell us a lot about:
* The development environment: Well-structured, clean code with consistent indentation and naming often indicates professional settings with established coding standards
* The development context: Code that appears hastily written might reveal academic prototypes, emergency fixes, or situations where speed was prioritized over elegance
* The programmer's background: Just as handwriting reveals personality traits, coding style can reflect a developer's training and experience

> To better understand what "good code structure" looks like in different contexts, you can explore resources like the [MIT Coding and Comment Style guide](https://mitcommlab.mit.edu/broad/commkit/coding-and-comment-style/), which explains coding conventions used in professional and academic settings.

**Comments and documentation:** Think of comments as the programmer's personal notes and explanations within the code. Comments are portions of text embedded within source code that the compiler or interpreter ignores during execution. These human-readable annotations provide direct windows into their thinking process. Pay attention to how comments explain debugging approaches, clarify complex algorithms, document team decisions, and sometimes include personal reflections or humor that humanizes the technical work.

**Intended audience.** Ask yourself: Is the code written for experienced technical experts or newcomers to programming? Does it include detailed comments that explain complex concepts, or assume prior knowledge? By analyzing these audience considerations, you can better understand broader issues of technological accessibility and the boundaries between different technical communities.

> Code documentation reveals its intended audience through the level of explanation provided. For instance, code intended for expert JavaScript developers typically contains minimal, technical comments assuming significant prior knowledge, while code designed for beginners includes extensive explanations of basic concepts and step-by-step logic ([Emadamerho-Atori, 2024](https://www.altexsoft.com/blog/how-to-write-code-documentation/)).

**Political Dimensions and Power Structures:** Code doesn't exist in a political vacuum - it reflects and shapes power relationships. Who has access to this code? What assumptions about users are embedded in its design? How does it distribute agency between users and systems? The choice between open source and proprietary models reflects different philosophies about technological power and knowledge sharing.

> The ongoing dispute between France and India over Rafale fighter jet source code exemplifies how code embodies political power structures in defense technology. India urgently seeks access to part of the source code of the Rafale, which forms the aircraft's electronic backbone ([Dasgupta, 2025](https://www.india.com/business/what-is-source-code-why-is-it-crucial-for-fighter-planes-know-its-role-in-missile-integration-and-upgrades-7849472/)). This represents a broader tension between India's "Atmanirbhar Bharat" (Self-Reliant India) initiative and Western defense contractors' business model. 

**Cross-referencing and Comparative Analysis:** Just as historians cross-reference multiple sources, code analysis benefits from comparing similar programs from the same period, examining related documentation, or studying the broader software ecosystem. Look for corroborating evidence in contemporary technical manuals, industry publications, or other preserved codebases.

**Don’t forget to consider what's absent or missing from the code.** What programming practices, security measures, or accessibility features that we might expect today are missing? Sometimes what code doesn't include reveals as much about historical context as what it does. These gaps can highlight evolving standards and changing priorities in software development over time.

> Consider the example of the systematic exclusion of the six women who programmed ENIAC for decades from historical documentation. It demonstrates how what is missing reveals as much as what's included ([Light 1999](https://rybn.org/human_computers/articles/when_computers_were_women.pdf)). This gap in the historical record wasn't accidental but reflected broader societal attitudes that marginalized women's technical contributions, showing how the absence of documentation can be as historically significant as its presence ([MacDonald 2016](https://www.sciencealert.com/these-6-women-were-written-out-of-tech-history)).

**Exercise – Internal Criticism of Microsoft GW-BASIC Code**
Let’s come back to our initial snippet of code : 

```

; [ This translation created 10-Feb-83 by Version 4.3 ]

    .RADIX    8        ; To be safe

CSEG    SEGMENT PUBLIC 'CODESG'
    ASSUME    CS:CSEG

INCLUDE BINTRP.H

    TITLE    GWMAIN Copied from BINTRP.MAC

    .RADIX    10

COMMENT *

--------- ---- -- ---- ----- --- ---- -----
COPYRIGHT 1975 BY BILL GATES AND PAUL ALLEN
--------- ---- -- ---- ----- --- ---- -----

ORIGINALLY WRITTEN ON THE PDP-10 FROM
FEBRUARY 9 TO  APRIL 9 1975

BILL GATES WROTE A LOT OF STUFF.
PAUL ALLEN WROTE A LOT OF OTHER STUFF AND FAST CODE.
MONTE DAVIDOFF WROTE THE MATH PACKAGE (F4I.MAC).

*

    .XLIST
```

Guided Analysis Questions for Internal Criticism:
1.	What does this snippet of code tell us about authorship and collaboration? Examine who receives credit for which contributions in this code, and how specifically is each person's work described.
2.	Looking at this code snippet and considering the historical context (Bill Gates, Paul Allen, early Microsoft, 1975-1983), what kind of software product do you think this might be? 
3.	Cross-referencing exercise: To deepen your analysis, look up these contemporary sources:
 	
    * [James, Mike. 2025 ‘Bill Gates Shares The Code That Launched Microsoft’. I Programmer](https://www.i-programmer.info/news/82-heritage/17946-bill-gates-shares-the-code-that-launched-microsoft.html)
    * [Gates, Bill. 2025. ‘Celebrating 50 Years of Microsoft’. Gates Notes.](https://www.gatesnotes.com/home/home-page-topic/reader/microsoft-original-source-code)
4.	How does Gates describe this collaboration in these 2025 sources versus the informal attribution in the 1983 code comments? What additional context do these sources provide about the significance of this early work?

**BONUS Exercise – Exploring Code as Culture**

**What are esoteric programming languages?** Esoteric programming languages (or "esolangs") are intentionally designed not for practical software development, but rather to challenge conventional programming paradigms and provide amusement for programmers ([Paloque-Bergès 2009](https://www.laprocure.com/product/1282150/paloque-berges-camille-poetique-des-codes-sur-le-reseau-informatique)). Think of them as programming's equivalent to experimental art or wordplay—they serve as creative expressions, intellectual puzzles, or even jokes that reveal the playful and cultural dimensions of programming beyond its purely functional aspects.

Explore the [Esoteric File Archive repository](https://github.com/graue/esofiles), a digital repository dedicated to preserving these unusual programming languages that might otherwise be lost to digital obsolescence. As the archive's creator explains in their own words: "websites devoted to esoteric programming languages tended to periodically go down... people who wanted to check out that language were out of luck" (Feeney [2013] 2025)

Simple exploration steps:
1.	Browse the repository folders (hunter, chef, shakespeare, befunge, etc.)
2.	Open one language folder that interests you
3.	Look at the code examples and documentation

For example, let's examine the [hunter folder](https://github.com/graue/esofiles/tree/master/hunter) and its [documentation](https://github.com/graue/esofiles/blob/master/hunter/doc/hunter.txt) file. Here you'll discover a fascinating programming language created by Chris Pressey in 2000 where programs are visualized as "mice in a space interacting with cheese and each other" (Pressey 2000). 

                Concurrent Maze Space Transformation
              (with Authentic Interrodent Communication)
                 In The HUNTER Programming Language


It is perceived that one of the biggest problems in maintaining
interest in programming is the above linear growth of boredom
compared to the usefulness of the program, resulting in an
acute loss of enthusiasm on the part of the programmers and
ultimately the abandonment of the software.
This creative approach wasn't just for amusement - it was actually designed to address "the problem of programmer boredom leading to the abandonment of software" (Esolang, 2025). By making programming more engaging and playful, Pressey hoped to encourage longer-term maintenance of software projects.


**Reflection questions:**
* Why would programmers invest time and effort to create seemingly "useless" languages and then work collaboratively to preserve them?
* What insights does this archive provide about programming as a form of cultural expression and creativity, beyond its practical problem-solving applications?

## Reading/viewing suggestions

Code as Cultural Expression and Context:
 	
Walton, Devan J. 2024. The Culture of Programming. December 31. https://rotel.pressbooks.pub/culturally-responsive-computing/chapter/the-culture-of-programming/
 	
Paloque-Bergès, Camille. 2009. Poétique Des Codes Sur Le Réseau Informatique. With École normale supérieure lettres et sciences humaines. Editions des archives contemporaines

Gender and Inclusion in Computing History:
 	
Light, Jennifer S. 1999. 'When Computers Were Women'. Technology and Culture 40 (3): 455–83

MacDonald, Fiona. 2016. 'These 6 Women Were Written Out of Tech History'. Humans. ScienceAlert, March 8. https://www.sciencealert.com/these-6-women-were-written-out-of-tech-history

Code Documentation and Style:

Emadamerho-Atori, Nefe. 2024. 'Code Documentation: Examples, Tools, Best Practices'. AltexSoft. https://www.altexsoft.com/blog/how-to-write-code-documentation/

'Coding and Comment Style : Broad Institute of MIT and Harvard'. n.d. Accessed 1 September 2025. https://mitcommlab.mit.edu/broad/commkit/coding-and-comment-style/

Learning to code:

[Programming Historian](https://programminghistorian.org/) - Lessons on digital methods for historical research

[freeCodeCamp](https://www.freecodecamp.org/) - Comprehensive free coding curriculum covering web development, data science, and more

[Codecademy](https://www.codecademy.com/catalog/subject/all) - Interactive coding lessons (free tier available)

[Khan Academy Computer Programming](https://www.khanacademy.org/computing/computer-programming) - Beginner-friendly programming courses

[MIT OpenCourseWare Programming](https://ocw.mit.edu/search/?d=Electrical%20Engineering%20and%20Computer%20Science&s=Programming) - University-level computer science courses

[Python.org Tutorial](https://docs.python.org/3/tutorial/) - Official Python programming tutorial

[Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/docs/Learn) - Web development learning resources

[GitHub Learning Lab](https://lab.github.com/) - Interactive courses on Git, GitHub, and software development practices 

## 3 Software Heritage: Preserving Code for the Future
Having explored code preservation and historical analysis techniques, let's now turn our attention to actual archiving initiatives. In this section, we will examine Software Heritage, which stands as one of the most ambitious and comprehensive efforts to systematically preserve our software heritage. Founded in France in 2016 with institutional support from the National Institute for Research in Computer Science and Automation (INRIA), Software Heritage has set itself a clear but challenging mission: to collect, preserve, and make accessible the source code of all publicly available software worldwide.

### 3.a  Software Heritage: Mission, Scope and Technical Infrastructure - 25 minutes
Think of Software Heritage as a response to an important assessment: preserving source code isn't something that can be done through individual, scattered efforts. Instead, it requires well-organized, institutional approaches ([Di Cosmo and Zacchiroli 2017}(https://www.softwareheritage.org/wp-content/uploads/2020/01/ipres-2017-swh.pdf)). To understand its focus, imagine a library that aims to collect all publicly available books - Software Heritage does this for open source code, though it cannot include proprietary code that is legally protected. Despite this necessary limitation, the archive has still managed to collect an impressive collection of millions of software projects and repositories.

Software Heritage aims to preserve everything publicly available. This comprehensive approach is like preserving an entire ecosystem rather than just a few species. Why does this matter? Because historical significance often isn't apparent immediately. By preserving the complete landscape of software development, future researchers will have access to much richer historical evidence than they would with a more selective approach.

**Exercise: Understanding Software Heritage's Development** 
To better understand how Software Heritage developed into a major preservation initiative, explore these complementary resources:
 	
* [Schafer, Valérie (2017). 'Le Logiciel Libre, de l'usage à La Recherche, Entretien avec Roberto Di Cosmo'. Bulletin 1024, 39-52.](https://1024.socinfo.fr/2017/09/1024_11_2017_39.html)

Focus particularly on pages 49 onward, where Di Cosmo discusses the founding vision and early challenges of Software Heritage.

Then examine this milestone report to see how the project matured:
 	
* [Cosmo, Roberto Di. 2022. 'Software Heritage in 2021: Five Years Already!' Software Heritage, January 5.](https://www.softwareheritage.org/2022/01/05/software-heritage-in-2021-five-years-already/)

**Guided reflection questions:**
1.	Who were the key figures in founding Software Heritage, and what specific problems were they trying to solve with this initiative?
2.	How has the project evolved by 2021 in terms of institutional support, technical infrastructure, and preservation achievements?

### 3.b Exploring Software Heritage's Architecture - 20 minutes
Think of Software Heritage's interface as a library with a special organization system designed for two key purposes: safeguarding code for future generations while making it accessible for today's researchers and developers. To help you visualize its structure, imagine the platform as organizing preserved code into three fundamental levels:
 	
* Source files: The individual pieces of code 
* Commits: Snapshots of code at specific moments in time
* Projects: Complete software repositories

This three-tier organization mirrors how software development works in practice, providing stable reference points that historians and researchers can use for consistent analysis.

When exploring Software Heritage, you will find search and browsing tools that open up multiple pathways for historical investigation. One limitation is that the archive lacks currently intuitive browsing capabilities, making it difficult to explore without specific search criteria in mind. If you have one, you could, for example, track how specific algorithms have evolved over decades, examine shifts in programming practices across different time periods, or map out the collaborative networks behind major software projects.

What makes this archive particularly valuable for scholarly work is its system of persistent identifiers - these function like permanent citation codes, ensuring that references to code remain valid indefinitely. This solves a crucial problem in digital scholarship ([Cosmo et al. 2020](https://ieeexplore.ieee.org/document/8946737/)) that researchers in other fields, such as web archiving, have similarly struggled with - how to create stable, lasting references to digital materials that might otherwise change or disappear.

**Exercise: Navigating Software Heritage**

Let's explore the Software Heritage archive together. First, visit the homepage: www.softwareheritage.org

**Step 1: Quick analysis:** As you examine the website, identify and take notes on how the platform communicates these three key aspects:

* Its heritage mission (What problem is it trying to solve? Why preserve code?)
* Community engagement opportunities (How can visitors contribute to this preservation effort?)
* The types and categories of code within Software Heritage's preservation scope

**Step 2: Features exploration:** Next, navigate to the features page: www.softwareheritage.org/software-heritage-features/ In your notes, categorize which features specifically address:

* Searchability and discovery (How do researchers find what they need?)	
* Long-term preservation strategies (How does the archive ensure code remains accessible decades from now?)

**Critical thinking questions:** After your exploration, consider these deeper questions:
1.	How does the three-tier organization system ("Source Files," "Commits," and "Projects") mirror actual software development workflows? How might this organizational approach benefit different types of historical research?
2.	Why are persistent identifiers so crucial for digital scholarship? 

### 3.c Comparative Preservation Approaches	- 20 minutes
Software Heritage represents a major initiative but one approach to digital preservation. To better understand the field, let's compare it with other initiatives. Think of these different preservation strategies as similar to how museums, libraries, and archives might each preserve cultural artifacts differently. Each approach has unique strengths and limitations that reflect their specific preservation goals. By examining these various methodologies side by side, we can develop a more nuanced understanding of the challenges involved in digital preservation and appreciate the diverse solutions that institutions have developed to address them.

To understand another major approach to code preservation, let's examine the GitHub Archive Program, launched in 2020. While sharing similar goals with Software Heritage, this initiative uses different preservation strategies. The program creates secure, long-term backups through multiple storage methods - think of it as creating several types of time capsules simultaneously. Perhaps most fascinating is the [Arctic Code Vault](https://www.youtube.com/watch?v=0v9Rwqxa8eI), housed in an abandoned mine deep within Svalbard's Arctic archipelago, where code is stored in a facility designed to last centuries. What makes this approach educationally valuable is its concept of "pace layers" - different preservation methods designed to function across various time scales, from years to millennia. This layered approach helps ensure that our digital heritage remains accessible to future generations regardless of technological changes ([GitHub Archive Program 2025](https://archiveprogram.github.com/)).

Another fascinating approach to explore is the Internet Archive's Software Collection, established in 2004. While Software Heritage focuses primarily on preserving source code (the building blocks of software), the Internet Archive takes a different educational approach. It preserves the complete software experience by collecting not just executable programs, but also their accompanying documentation, media, and cultural artifacts that help students understand the historical context in which the software was actually used. Think of this as preserving not just a historical building, but also photographs, newspapers, and artifacts showing how people lived in and interacted with that building. This holistic collection ranges from early personal computer applications to beloved classic arcade games, and importantly, offers something unique for hands-on learning: emulated environments where users can actively experience the software functioning as it did decades ago, rather than just passively viewing static code ([Internet Archive 2025](https://archive.org/details/software)).

To understand the different approaches to software preservation, consider this analogy: If software were a book, these preservation strategies would focus on different aspects:
1.	Source code preservation: Preserves the "manuscript" (human-readable instructions and collaborative development processes)
2.	Archive storage: Creates secure "vaults" that protect against catastrophic loss
3.	Executable preservation: Maintains the "reading experience" (how users actually interacted with the software)
Each approach preserves a unique dimension of software as cultural heritage, and together they provide a more complete historical record ([Matthews *et al.* 2010](https://www.ijdc.net/index.php/ijdc/article/view/145/210)).
 
**Exercise: Comparing Preservation Strategies** 
In this structured activity, you'll analyze three different approaches to software preservation, each with unique strengths and philosophies.

**Part 1: GitHub Archive Program**

Visit and carefully examine: archiveprogram.github.com

**Guiding Questions:**
1.	Compare and contrast: What core preservation goals does GitHub Archive Program share with Software Heritage, and what fundamental differences can you identify in their preservation methodologies?
2.	Environmental considerations: What specific properties of the Arctic location make it suitable for the Code Vault, and how does this physical storage strategy reflect GitHub's thinking about different preservation timescales?

**Part 2: Internet Archive Software Collection**

Explore the collection: archive.org/details/software 

For a concrete example, examine: archive.org/details/jsmess_engine_v2 

**Critical Analysis Questions:**
1.	Preservation philosophy: How does the Internet Archive's approach to software preservation fundamentally differ from both Software Heritage and GitHub Archive Program in terms of what aspects of software history it prioritizes?
2.	Historical significance: Browse the main categories visible on the Collection homepage and identify distinct types of software preserved there. Evaluate why preserving this diversity of software types—from early computer programs to web-based applications—contributes to our understanding of technological and cultural evolution.
Comparative reflection: How do these three approaches—comprehensive source code archiving, secure long-term storage, and executable preservation address different aspects of code as heritage?

### Reading/viewing suggestions 

Software Heritage Foundation and Development:
 	
Cosmo, Roberto Di, and Stefano Zacchiroli. 2017. Software Heritage: Why and How to Preserve Software Source Code
 	
Schafer, Valérie. 2017. 'Le Logiciel Libre, de l'usage à La Recherche, Entretien Avec Roberto Di Cosmo'. Bulletin 1024, September 1, 39–52. https://doi.org/10.48556/SIF.1024.11.39
 	
Cosmo, Roberto Di. 2022. 'Software Heritage in 2021: Five Years Already!' Software Heritage, January 5. https://www.softwareheritage.org/2022/01/05/software-heritage-in-2021-five-years-already/

Technical Infrastructure and Citation:
 	
Cosmo, Roberto Di, Morane Gruenpeter, and Stefano Zacchiroli. 2020. 'Referencing Source Code Artifacts: A Separate Concern in Software Citation'. Computing in Science & Engineering 22 (2): 33–43. https://doi.org/10.1109/MCSE.2019.2963148
 	
Bussi, Laura, Roberto Di Cosmo, Carlo Montangero, and Guido Scatena. 2019. The Software Heritage Acquisition Process. https://unesdoc.unesco.org/ark:/48223/pf0000371017

Comparative Preservation Approaches:
 	
GitHub Archive Program. 2025. 'Preserving Open Source Software for Future Generations'. https://archiveprogram.github.com/
 	
Internet Archive. 2025a. 'Digital Library of Free & Borrowable Texts, Movies, Music & Wayback Machine'. https://archive.org/details/software
 	
Kahle, Brewster. 1997. 'Preserving the Internet'. Scientific American, March 1. https://www.infotextmanuscripts.org/djetc/dj-fixing-links-3.pdf
 	
Matthews, Brian, Arif Shaon, Juan Bicarregui, and Catherine Jones. 2010. 'A Framework for Software Preservation'. International Journal of Digital Curation 5 (1): 91–105. https://doi.org/10.2218/ijdc.v5i1.145

Video Resources:
 	
Firebolt, dir. 2022. Analyzing GitHub Archive Data - 1.Introduction. 9:56. https://www.youtube.com/watch?v=NGEVDeUIFs0
 	
Brodie Robertson, dir. 2020. GitHub's Crazy Plan To Archive Your Code In The Arctic. 11:56. https://www.youtube.com/watch?v=0v9Rwqxa8eI

 
## 4 – Potential uses of preserved code 
Preserved source code serves many important purposes beyond just technical reference. In this section, we will explore two key applications that demonstrate both the technological and cultural importance of code preservation: first, how preserved code supports artificial intelligence development, and second, its value for historical and cultural research. These examples will help you understand how preserved code functions as both a practical technical resource and a valuable cultural heritage artifact.

### 4.a Code Transparency: A Framework for Responsible AI Development - 20 minutes
Artificial intelligence systems increasingly rely on vast source code datasets. Machine learning models trained on these repositories can now generate programs, translate between programming languages, and support software development ([Chen et al. 2021](https://arxiv.org/pdf/2107.03374)). Yet most AI systems function as "black boxes" with opaque decision-making processes, making it challenging to understand their operations or ensure ethical functioning ([Adadi and Berrada 2018](https://ieeexplore.ieee.org/document/8466590)).

The CodeCommons initiative by Software Heritage addresses transparency challenges through its curated, ethically-sourced dataset for AI training ([Pietri et al. 2019](https://ieeexplore.ieee.org/document/8816748)). Instead of using code with unclear origins or licensing, CodeCommons creates transparent datasets that clearly document the source, licensing, and cultural context of all training data.

This approach addresses critical ethical concerns in AI development. AI systems trained on code without proper consideration of licensing, attribution, or consent risk reproducing not just technical patterns but also inherent biases, security vulnerabilities, and cultural assumptions from their training data ([Zaimi et al. 2015](https://dl.acm.org/doi/10.1145/2801081.2801087); [Johansen et al. 2023](https://arxiv.org/abs/2005.08231); [Kocetkov et al. 2022](https://arxiv.org/abs/2211.15533)). Initiatives like CodeCommons promote responsible AI development by offering transparently-sourced code datasets that clearly document origins and permissions.

**Exercise: Understanding AI Transparency Challenges**

To deepen your understanding of AI transparency issues, explore this resource:

Martens, David, and Sofie Goethals (2024). 'Opening the black box: how "explainable AI" can help us understand how algorithms work'. The Conversation. http://theconversation.com/opening-the-black-box-how-explainable-ai-can-help-us-understand-how-algorithms-work-244080

**Analysis questions:** After reading the article, consider these key points:
1.	Identify three key arguments explaining why popular AI systems like ChatGPT can be considered "black boxes." What makes their decision-making processes difficult to understand?
2.	According to the authors, what are the main advantages of developing explainable and transparent AI models? How might this benefit society?

**Practical exploration:** Visit the CodeCommons initiative by Software Heritage: codecommons.org/

**Reflection questions:** After exploring the initiative, consider:
1.	What core values does Software Heritage emphasize in developing CodeCommons? How do these values address ethical concerns in AI development?
2.	In what specific ways might preserved code collections help address AI transparency challenges? Consider both technical and ethical dimensions.

### 4.b Code in Historical and Cultural Research - 20 minutes
Source code has emerged as a valuable resource for humanities research, particularly in critical code studies, digital history, and science and technology studies. Source code offers direct insight into the creative and collaborative processes of software development. It illuminates not just the final product, but how programmers approached problems, collaborated, and embedded cultural values into their technical solutions.

Pioneer work in this field began in the early 2000s ([Mackenzie 2006](https://books.google.lu/books?id=083BUgMnLKQC); [Manovich 2001;](https://dss-edit.com/plu/Manovich-Lev_The_Language_of_the_New_Media.pdf) [Fuller 2008)](https://monoskop.org/images/a/a1/Fuller_Matthew_ed_Software_Studies_A_Lexicon.pdf), with notable contributions along the way ([Coleman 2018](https://thesai.org/Publications/ViewPaper?Volume=9&Issue=9&Code=ijacsa&SerialNo=2); [Cox and McLean 2012](https://direct.mit.edu/books/monograph/3964/Speaking-CodeCoding-as-Aesthetic-and-Political); [Berry 2016](https://books.google.lu/books?id=GeYgDAAAQBAJ); [Rushkoff 2010](https://books.google.lu/books?id=e2YCuxBjkq0C); [Hayles 2005](https://press.uchicago.edu/ucp/books/book/chicago/M/bo3622698.html)). The 2020 publication of the [Manifesto for Critical Code Studies](https://books.google.fr/books?id=k4LPDwAAQBAJ&printsec=copyright&redir_esc=y#v=onepage&q&f=false), enriched with detailed case studies, further developed the exploration of code as cultural expression. These initiatives treat programming languages as forms of creative writing, examine the cultural assumptions embedded in algorithms, and investigate how software development practices reflect broader social and political contexts.

These works reveal how seemingly neutral technical decisions actually reflect cultural biases, political assumptions, and aesthetic preferences. By examining code as a form of cultural expression, scholars can explore questions about power, identity, and creativity in digital environments.

**Exercise: Code as Archaeological Evidence**
Reading: [David M. Berry's "Digital Ruins and Critical Code Studies: Towards an Ethics of Historical Software Reconstruction"](https://stunlaw.blogspot.com/2025/01/digital-ruins-and-critical-code-studies.html)

**Analysis questions:** After reading Berry's discussion of "digital ruins," consider:

1.	**Historical parallels:** Berry compares software reconstruction to architectural preservation. Identify two specific principles from architectural preservation (mentioned in the text) that he argues should apply to code reconstruction. How do these principles address the challenge of maintaining historical authenticity?
2.	**Evidence evaluation:** In the ELIZA reconstruction case study, the team had to create entirely new functions (like LETTER and BCDIT) that were missing from the original archives. According to Berry's framework, how should such reconstructions be marked or documented to distinguish them from original historical code?

## Reading/viewing suggestions 
AI and Code Transparency:
 	
Chen, Mark, Jerry Tworek, Heewoo Jun, et al. 2021. 'Evaluating Large Language Models Trained on Code'. arXiv:2107.03374. Preprint, arXiv, July 14. https://doi.org/10.48550/arXiv.2107.03374
 	
Adadi, Amina, and Mohammed Berrada. 2018. 'Peeking Inside the Black-Box: A Survey on Explainable Artificial Intelligence (XAI)'. IEEE Access 6: 52138–60. https://doi.org/10.1109/ACCESS.2018.2870052
 	
Martens, David, and Sofie Goethals. 2024. 'Opening the black box: how "explainable AI" can help us understand how algorithms work'. The Conversation, December 3. http://theconversation.com/opening-the-black-box-how-explainable-ai-can-help-us-understand-how-algorithms-work-244080 
 	
Pietri, Antoine, Diomidis Spinellis, and Stefano Zacchiroli. 2019. 'The Software Heritage Graph Dataset: Public Software Development Under One Roof'. 2019 IEEE/ACM 16th International Conference on Mining Software Repositories (MSR), May, 138–42. https://doi.org/10.1109/MSR.2019.00030

Ethical Considerations in AI Development:
 	
Johansen, Johanna, Tore Pedersen, and Christian Johansen. 2023. 'Studying the Transfer of Biases from Programmers to Programs'. AI & SOCIETY 38 (4): 1659–83. https://doi.org/10.1007/s00146-021-01328-4
 	
Zaimi, Asimina, Apostolos Ampatzoglou, Noni Triantafyllidou, et al. 2015. 'An Empirical Study on the Reuse of Third-Party Libraries in Open-Source Software Development'. Proceedings of the 7th Balkan Conference on Informatics Conference (New York, NY, USA), BCI '15, September 2, 1–8. https://doi.org/10.1145/2801081.2801087
 	
Kocetkov, Denis, Raymond Li, Loubna Ben Allal, et al. 2022. 'The Stack: 3 TB of Permissively Licensed Source Code'. arXiv:2211.15533. Preprint, arXiv, November 20. https://doi.org/10.48550/arXiv.2211.15533

Critical Code Studies and Cultural Analysis:
 	
Mackenzie, Adrian. 2006. Cutting Code: Software and Sociality. Peter Lang
 	
Manovich, Lev. 2001. The Language of New Media. 8. print. A Leonardo Book. MIT Press
 	
Fuller, Matthew. 2008. Software Studies: A Lexicon. The MIT Press. https://doi.org/10.7551/mitpress/9780262062749.001.0001
 	
Cox, Geoff, and Alex McLean. 2012. Speaking Code: Coding as Aesthetic and Political Expression. The MIT Press. https://doi.org/10.7551/mitpress/8193.001.0001
 	
Berry, D. 2016. The Philosophy of Software: Code and Mediation in the Digital Age. Springer
 	
Rushkoff, Douglas. 2010. Program Or Be Programmed: Ten Commands for a Digital Age. OR Books
 	
Hayles, N. Katherine. 2005. My Mother Was a Computer: Digital Subjects and Literary Texts. University of Chicago Press. https://press.uchicago.edu/ucp/books/book/chicago/M/bo3622698.html
 	
Marino, Mark C. 2020. Critical Code Studies. MIT Press

Additional Resources:
 	
CodeCommons. 2025. 'Homepage'. https://codecommons.org/
 	
Simpson, Alison. 2019. 'The History of Programming - a Fast and Furious Tour'. SheCanCode, April 9. https://shecancode.io/the-history-of-programming-a-fast-and-furious-tour/
 	
Alcaras, Gabriel, and Antoine Larribeau. 2022. 'Writing Code, Making Software'. RESET. Recherches En Sciences Sociales Sur Internet, no. 11 (March). https://doi.org/10.4000/reset.3944



