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

**Illustration:** 

[Introduction](#introduction)

[1 Understanding Digital Heritage Recognition](#1-understanding-digital-heritage-recognition)

[2 Learning to Read Code as Cultural Text](#2-learning-to-read-code-as-cultural-text)

[3 Preserving Code: Initiatives and Infrastructures](#3-preserving-code-initiatives-and-infrastructures)

[Conclusion](#conclusion)

## Introduction

Every app, website, and digital service we use today is built on layers of code that capture decisions, assumptions, and values—traces historians are only beginning to learn how to read. This lesson will help you answer these questions, and demonstrates how the intellectual, cultural, and social contexts of code's creation matter, making it a valuable historical resource for understanding contemporary technological development. This lesson introduces you to applying source criticism methods to code, teaching you to view it as both a technical and cultural artifact. At its most elementary level, source code consists of human-readable computer instructions, but as we will explore, it is much more than mere technical documentation. Code is increasingly being recognized as cultural heritage, raising questions about how it should be preserved and what transformations occur as working software becomes historical artifact. The methodological approach through this lesson focuses on three key skills: contextual analysis, critical evaluation, and comparative assessment—rather than technical mastery. However, understanding code as a historical source does require engaging with its technical dimensions; learners will be guided toward accessible resources to build this foundational knowledge alongside their critical skills. While designed for beginners in digital source criticism, some exercises will require basic digital navigation skills and familiarity with academic research practices.

In this lesson, we will guide you through three key dimensions of understanding code as heritage:

1. **Heritage Recognition:** We will first examine what qualities make source code a distinctive type of born-digital heritage. This includes understanding how UNESCO recognizes it and exploring the unique preservation challenges it presents.
2. **Interpretive Methods:** Next, we will develop strategies for reading and interpreting code that go beyond its technical functionality. We will approach code as a cultural artifact that reveals important insights about its creators' assumptions, values, and practices. Through detailed case studies, we will explore how the traditional tools of source criticism must be adapted for born-digital materials, connecting our analysis to broader questions in digital history and critical code studies.
3. **Preservation Initiatives:** Finally, we will examine how source code is being preserved through major international initiatives, with special focus on Software Heritage. We will also explore complementary approaches like the GitHub Archive Program and the Internet Archive's Software Collection, understanding how different preservation strategies address different aspects of code as heritage.

Each section includes practical exercises designed to develop your critical thinking about digital sources rather than technical programming skills. By the end of this lesson, you will understand how to approach source code as a historian, recognizing its possibilities as historical evidence.

## 1 Understanding Digital Heritage Recognition

> [!NOTE]  
> **Learning Objectives for Section 1:**
> By completing this section, you will be able to:
> - Define source code and explain its dual nature as technical artifact and cultural expression
> - Trace how source code gained official recognition as digital heritage
> - Identify the main threats to code preservation (technological obsolescence, platform changes, storage ephemerality)
> - Evaluate why active preservation strategies are necessary for digital materials

### 1.a Defining Source Code: Between Technical Function and Cultural Expression - 25 min

To define our object of study, consider Harold Abelson and Gerald Jay Sussman's insightful 1996 observation that remains highly relevant in today's programming best practices: "Programs must be written for people to read, and only incidentally for machines to execute" ([Abelson and Sussman 1996](https://sarabander.github.io/sicp/html/index.xhtml)). What does this mean? Source code can be defined as the fundamental set of instructions of a program; human-readable computer commands written in higher-level programming languages that require compilation or interpretation to become executable ([Krysa & Sedek 2008](https://monoskop.org/images/a/a1/Fuller_Matthew_ed_Software_Studies_A_Lexicon.pdf#%5B%7B%22num%22%3A515%2C%22gen%22%3A0%7D%2C%7B%22name%22%3A%22Fit%22%7D%5D)).

Since the 1950s, hundreds of [programming languages](https://en.wikipedia.org/wiki/Programming_language) have been created, each with its own syntax, design philosophy, and community of practitioners. Some languages, like [FORTRAN (1957)](https://en.wikipedia.org/wiki/Fortran) and [COBOL (1959)](https://en.wikipedia.org/wiki/COBOL), emerged in specific institutional contexts—scientific computing and business administration respectively—and continue to run critical systems decades later. Others, like [Python (1991)](https://en.wikipedia.org/wiki/Python_(programming_language)), were designed with readability and accessibility in mind. This diversity means that source code must be understood within its specific historical context: it is written in a particular programming language, at a particular historical moment, and shaped by the practices and priorities of particular technical communities.

Computer scientist Darrell Ronald Raymond emphasizes this in his 1991 article Reading source code: "the main role of source code is not a compilable entity, but a human-readable statement of intent and mechanism in the program" ([1991:3](https://dl.acm.org/doi/10.5555/962111.962113)). This also implies that code is more than written words. It is both an object and an action, simultaneously enabling and constraining activities ([Méadel and Sire 2017](https://shs.cairn.info/revue-reseaux-2017-6-page-9?lang=fr&tab=texte-integral)). Because code is read, taught, and imitated within communities, certain conventions can acquire historical significance—becoming part of programming culture itself.

![The famous "Hello, World!" program written in C by Brian Kernighan on dot-matrix computer paper, from The C Programming Language (1978)](/assets/images/code-as-heritage/Hello_World_Brian_Kernighan_1978.jpg "Hello World program by Brian Kernighan")

**Figure 1:** Brian Kernighan's "Hello, World!" program written in C and printed on dot-matrix computer paper, as featured in *The C Programming Language* (1978). At the time of its publication, this was simply an introductory example; it has since become the universal convention for first programs in computing education. *Credit: Brian Kernighan, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/), via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Hello_World_Brian_Kernighan_1978.jpg)*

If you have ever opened a programming tutorial, textbook, or online course, you have likely encountered "Hello, World!"—a simple program that displays these two words on the screen. This modest example has become a standard convention: when introducing any programming language, authors almost invariably begin with a "Hello, World!" program. The [Rosetta Code repository](https://rosettacode.org/wiki/Hello_world/Text) documents the historical persistence and cultural significance of this convention by collecting implementations of "Hello, World!" in over 300 programming languages, organized chronologically from early mainframe languages through contemporary ones.

But where did this tradition originate? The example traces back to Brian Kernighan, who first documented it in a 1972 Bell Labs memorandum titled *A Tutorial Introduction to the Language B*. It gained widespread adoption through *The C Programming Language* (1978), co-authored by Kernighan and Dennis Ritchie, one of the most influential programming textbooks ever published ([Wikipedia: "Hello, World!" program](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program)). The persistence of this convention across five decades and hundreds of programming languages illustrates that programming, like any human practice, develops shared traditions. The appearance of "Hello, World!" in contemporary Python tutorials represents direct historical lineage from Kernighan's 1972 memorandum and a form of cultural transmission preserved in code.

This example helps us understand an essential tension in computing: while source code is ultimately designed to be executed on a machine, it is also fundamentally a form of human communication that bears witness to its historical context and contains valuable traces of the past.

### 1.b Born-Digital Heritage: How Source Code Gained Official Recognition - 20 min

The institutional recognition of source code as cultural heritage began with the [2003 UNESCO Charter on the Preservation of Digital Heritage](https://unesdoc.unesco.org/ark:/48223/pf0000179529), which represented a significant milestone in this journey. It formally acknowledged that born-digital materials—content that originates in digital form—constitute an important part of our cultural legacy. These materials include databases, websites, software, and other digital content that have never existed in physical form.

Why was this recognition important? By officially affirming the historical and cultural value of digital materials, UNESCO effectively placed them on equal footing with traditional heritage forms like monuments and artifacts, highlighting their significance for future generations.

However, it did not explicitly address source code preservation ([UNESCO 2009](https://unesdoc.unesco.org/ark:/48223/pf0000179529)). That changed in 2023, when UNESCO formally recognized the importance of preserving software source code as digital heritage for sustainable development, acknowledging its value across education, research, and cultural preservation ([UNESCO 2023](https://www.unesco.org/en/articles/positioning-software-source-code-digital-heritage-sustainable-development)).

**Exercise – Analyzing UNESCO's Recognition of Source Code**

These two documents show how digital heritage recognition has evolved and the challenges preservation efforts face. They provide important historical context and current thinking on source code preservation.

* [Charter on the Preservation of the Digital Heritage (2003)](https://unesdoc.unesco.org/ark:/48223/pf0000179529) - Focus on definitions and scope (articles 1-3)
* ['Positioning Software Source Code as Digital Heritage for Sustainable Development' (2023)](https://www.unesco.org/en/articles/positioning-software-source-code-digital-heritage-sustainable-development)

Questions for reflection:

1. How does the 2003 Charter define digital heritage, and where might source code fit within this definition? Consider the language used and the types of materials mentioned.
2. Looking at the 2023 UNESCO article, what specific arguments are presented for treating source code as heritage? How has this perspective evolved over the twenty years since the original Charter?
3. What specific benefits does code preservation offer to society, and in which fields (legacy, research, etc.) is it recognized as having particular value?

### 1.c The Fragility of Code: Understanding Digital Preservation Challenges - 15 minutes

Among the key threats to source code is the potential for a Digital Dark Age ([Silva 2022](https://www.softwareheritage.org/2022/06/28/all-of-humankinds-source-code-in-a-nutshell/?lang=fr)), which refers to the possible loss of vast amounts of digital information. Three main factors contribute to this risk:

* Technological obsolescence: When hardware and software systems become outdated
* Platform changes: When services hosting code shut down or significantly change
* The ephemeral nature of digital storage: Digital media degrades over time

Why should we care about preserving historical code? This question is critical for historians and cultural preservationists to consider. Digital materials require intentional and continuous preservation strategies ([Conway 1996](https://www.clir.org/pubs/reports/conway2/index/)). Source code faces particular vulnerabilities: programming languages evolve, development platforms disappear, and the original context of creation can be lost within years of a program's abandonment.

A 2023 study by the Video Game History Foundation and the Software Preservation Network measured the scale of this loss. The study found that 87 percent of classic video games released in the United States before 2010 are no longer commercially available. The situation is even more severe for early games: less than 3 percent of titles released before 1985 remain in print. The period from roughly 1977 to 1985 marked the emergence of home computing and the first generation of commercial video games—yet these availability rates are comparable to the survival rates of American silent films (14 percent) and pre-World War II audio recordings (10 percent) ([Video Game History Foundation 2023](https://gamehistory.org/study-explainer/)).

Many classic games like *Jet Set Willy* ([Aycock et al. 2017](https://intarch.ac.uk/journal/issue45/2/index.html)) survive only as reverse-engineered approximations after their original code was lost through corporate restructuring, technological changes, or simple neglect. Reverse engineering—the process of analyzing a finished product to understand how it works without access to its original design documentation ([Wikipedia](https://en.wikipedia.org/wiki/Reverse_engineering))—allows programmers to recreate software functionality, but the resulting code is an approximation rather than the historical original. Likewise, early web applications, mobile apps, and desktop software that fundamentally shaped our computer interactions have disappeared, taking with them vital evidence of digital culture's evolution ([Kirschenbaum and Ovenden 2014](https://www.clir.org/pubs/reports/pub149/)).

![Original cassette tape of Jet Set Willy for the Commodore 64, showing the game label on a standard audio cassette](/assets/images/code-as-heritage/Jet_Set_Willy_Cassette.jpg "Jet Set Willy cassette tape")

**Figure 2:** Original cassette tape of *Jet Set Willy* (Commodore 64 version, 1984), a platform game originally created by Matthew Smith for the ZX Spectrum and then ported to other platforms. In the early home computing era (late 1970s–mid 1980s), software was distributed on audio cassettes: game data was encoded as sound, and users loaded programs by playing the tape into their computer. Crucially, what cassettes preserved was the *executable code*—the machine-readable version of the program—not the *source code* originally written by the programmer. Source code, with its human-readable logic, comments, and variable names, typically remained with the developer or publisher. When companies went bankrupt, restructured, or simply failed to archive their materials, this source code was often lost. What researchers can recover from surviving cassettes through reverse engineering is a reconstruction of how the program functions, not the original code as written. The game can be [played in a browser-based emulator on the Internet Archive](https://archive.org/details/Jet_Set_Willy_1984_Software_Projects). *Credit: Cassette scan from [Internet Archive](https://archive.org/details/uta_Jet_Set_Willy_1984_Software_Projects_387), "The Ultimate Tape Archive" collection.*

This loss extends far beyond individual programs—it affects entire development ecosystems. As programming languages become obsolete and development tools disappear, the specialized knowledge of working with these particular systems gradually scatters as communities evolve and move on to newer technologies ([Shustek 2006](https://ieeexplore.ieee.org/document/4042496)). The resulting impact is both technical and cultural: we lose valuable access to the creative processes that developers used, the collaborative practices they established, and the innovative solutions they created—all of which defined significant periods in computing history.

Amid these losses, remarkable stories of recovery and reconstruction offer hope. The Apollo 11 source code, once considered lost, was meticulously reconstructed from printed documentation and surviving fragments—a case we will examine in detail in Section 2. Such recoveries reveal not just technical achievement but the working methods, naming conventions, and even humor embedded by programming teams. These discoveries provide unique insights into computing culture that descriptive historical sources alone could never capture.

**Exercise – Examining some Heritage Needs and Efforts**

For this exercice, you will compare and analyze two perspectives on code preservation. Read both articles carefully to identify their approaches to digital heritage preservation and the challenges they address.

* [I tried to find a way to preserve code for 69 years (this is not a joke)](https://museumofscreens.wordpress.com/2022/12/09/how-to-preserve-code-for-69-years-this-is-not-a-joke/) 
* [Vanishing Culture: Recovering Lost Software](https://blog.archive.org/2025/05/07/vanishing-culture-recovering-lost-software/)

Questions for reflection:

1. Identify common elements: What shared goals, concerns, and types of code do both articles discuss?
2. Analyze preservation challenges: What specific technical and cultural obstacles do both authors encounter in their preservation efforts?
3. Compare methodological approaches: How do their different approaches reflect the broader challenge of code preservation?

### Reading/viewing suggestions 

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

> [!NOTE]  
> **Learning Objectives for Section 2:**
> By completing this section, you will be able to:
> - Apply source criticism methods to code, attending simultaneously to its technical function, textual content, historical context, and archival transmission
> - Use programming language choices as chronological and cultural markers
> - Analyze comments, naming conventions, and documentation for cultural and historical evidence
> - Recognize the limits of what code alone can reveal about its creation context

Understanding source code as a historical source requires developing new literacy skills that bridge technical and cultural analysis. Source code is fundamentally a form of writing—a way humans communicate instructions, ideas, and solutions to both computers and other humans. Like other written forms, it bears the marks of its author's background, the conventions of its era, and its cultural context. Programming languages function similarly to human languages in that they have their own grammar, style conventions, and cultural associations that evolve across different communities and historical periods.

### 2.a Source Criticism in the Digital Age — 25 minutes

Approaching code as a historical source does not require you to become a programmer—but it does require developing a new kind of literacy. Just as art historians learn to see paintings differently than casual viewers, and musicologists learn to hear compositions with trained attention, historians of computing must learn to read code with awareness of its technical, textual, and cultural dimensions simultaneously. This lesson develops that awareness without assuming prior programming experience, while recognizing that code is not simply "text in another language" but a distinctive form of human expression with its own material and logical properties.

The relationship between historical analysis and technical understanding operates at several levels:

* **Reading code as cultural text** does not require programming expertise—you can analyze naming conventions, comments, documentation practices, and embedded cultural references without being able to write or execute code yourself.
* **Understanding what code does** benefits from basic familiarity with programming concepts—not expertise, but enough literacy to recognize structures, follow logic, and understand why certain choices were made.
* **Evaluating code's technical quality or reconstructing functionality** requires genuine programming knowledge—a level beyond what this lesson addresses.

This lesson focuses primarily on the first level while acknowledging that deeper engagement benefits from the second.

#### Source Criticism and Born-Digital Heritage

Historians trained in source criticism will recognize familiar questions when approaching code: Who created this? When? For what purpose? Has it been altered? Can we trust it? How did it reach us? These questions remain essential when working with code, just as they are for manuscripts, photographs, or oral testimonies.

Source code has emerged as a valuable resource for humanities research, particularly in critical code studies, digital history, and science and technology studies. Pioneer work in this field began in the early 2000s ([Mackenzie 2006](https://books.google.lu/books?id=083BUgMnLKQC); [Manovich 2001](https://dss-edit.com/plu/Manovich-Lev_The_Language_of_the_New_Media.pdf); [Fuller 2008](https://monoskop.org/images/a/a1/Fuller_Matthew_ed_Software_Studies_A_Lexicon.pdf)), with notable contributions along the way ([Coleman 2018](https://thesai.org/Publications/ViewPaper?Volume=9&Issue=9&Code=ijacsa&SerialNo=2); [Cox and McLean 2012](https://direct.mit.edu/books/monograph/3964/Speaking-CodeCoding-as-Aesthetic-and-Political); [Berry 2016](https://books.google.lu/books?id=GeYgDAAAQBAJ); [Rushkoff 2010](https://books.google.lu/books?id=e2YCuxBjkq0C); [Hayles 2005](https://press.uchicago.edu/ucp/books/book/chicago/M/bo3622698.html)). The 2020 publication of the [Manifesto for Critical Code Studies](https://books.google.fr/books?id=k4LPDwAAQBAJ&printsec=copyright&redir_esc=y#v=onepage&q&f=false) by Mark Marino, enriched with detailed case studies, further developed the exploration of code as cultural expression. As Marino argues, we must attend to "the extra-functional significance of computer source code"—what code means beyond what it does. These initiatives treat programming languages as forms of creative writing, examine the cultural assumptions embedded in algorithms, and investigate how software development practices reflect broader social and political contexts. These works reveal how seemingly neutral technical decisions actually reflect cultural biases, political assumptions, and aesthetic preferences. By examining code as a form of cultural expression, scholars can explore questions about power, identity, and creativity in digital environments.

Every type of historical source—from medieval charters to nineteenth-century newspapers to twentieth-century film—requires adapted methods of analysis suited to its specific material and communicative properties. Code is no different: it demands approaches attentive to its particular characteristics. The historian's fundamental questions endure; what changes is where we find answers and what new questions the source itself raises.

#### Specificities of Code as Historical Evidence

Born-digital sources possess characteristics that distinguish them from paper-based or analog materials. Understanding these differences helps us approach code with appropriate analytical tools.

**Self-Documenting Artifacts:** Code often contains its own contextual information. Comments may explain the programmer's intentions, name the author, or record the date of creation. When code is preserved through platforms like GitHub or other version control systems, the artifact includes not just the code itself but commit messages, branch histories, contributor identities, and timestamps. The "source" becomes intertwined with its documentary apparatus. This intertwining can be analytically productive. Traditional historians often lament the loss of context: who wrote this manuscript? Under what circumstances? With some code, particularly from the era of collaborative software development, contextual information may be preserved *within* the artifact itself. Version control systems and comment histories can provide contextual density that paper archives rarely offer. However, this advantage applies unevenly to historical code. Software from the 1960s, 1970s, or 1980s typically lacks version control metadata entirely. Comments may be sparse or absent. The programmer's name may appear nowhere in the artifact. For such sources, establishing provenance requires the same external detective work familiar from traditional archives—correspondence, institutional records, oral histories, contemporary publications.

**Dependency on Technical Infrastructure:** Historical code survives in various forms: printed listings, magnetic tapes, optical disks, migrated files, or even photographs of screens. Each form of survival carries different implications for historical analysis. Code preserved on paper can be read like any textual source, but cannot be executed. Code preserved on obsolete media may require specialized equipment to access. Code that has been migrated to modern formats may have been altered—intentionally or inadvertently—in ways that affect its meaning. When historians seek to understand not just what code *says* but what it *does*, they often depend on reconstructed environments. This dependency on technical infrastructure means that our access to the *functional* dimension of historical code is always mediated by preservation decisions and technical interventions.

**Dependency on Technical Infrastructure:** Code exists in a dual state: it can be read as text, but it can also be executed as a functional program. These two modes of engagement have different requirements. Reading code as text—whether on paper printouts, in archived files, or in documentation—requires no special infrastructure beyond what any textual source demands. However, understanding what code *does* when executed often requires access to the original technical environment: the hardware, operating system, compilers, and libraries for which it was written. A program written for a 1970s mainframe will not run on a modern laptop without substantial reconstruction. Historical code survives in various forms—printed listings, magnetic tapes, optical disks, migrated files, or even photographs of screens—and each form of survival carries different implications for historical analysis. Code preserved on paper can be read but not executed. Code preserved on obsolete media may require specialized equipment to access. Code that has been migrated to modern formats may have been altered—intentionally or inadvertently—in ways that can affect its meaning. When historians seek to understand not just what code *says* but what it *does*, they depend on reconstructed environments: emulators, virtual machines, or restored hardware. This dependency means that our access to the *functional* dimension of historical code is always mediated by preservation decisions and technical interventions—sometimes in ways that are not immediately visible.

**Multiple Temporalities:** A single code artifact may contain traces of multiple moments: the original creation, subsequent modifications, the moment of archival deposit, later preservation interventions. These temporalities coexist within what appears to be a single document. Historians must ask not just "when was this created?" but "which version of this are we examining, and how did it reach this state?" For contemporary code preserved in version control systems, these questions may have ready answers: commit histories record who changed what, when, and sometimes why. The artifact documents its own temporal layers.

**Archival Gaps and Lost Context:** But for historical code, the situation is often reversed. Computer programs have only recently become objects of systematic archival attention, and their preservation remains fragile ([Ernst 2013](https://www.upress.umn.edu/book-division/books/digital-memory-and-the-archive)). Much early software was never systematically preserved; what survives often does so accidentally, incompletely, or through unofficial channels—sometimes even through software piracy, which functions as an unofficial archive for otherwise abandoned code. This is a reminder that code sometimes reaches us through paths its creators never intended. Historical code also frequently arrives stripped of its original documentary context. The technical manuals, design documents, internal memoranda, and institutional knowledge that once surrounded a program may be lost, leaving the code as an orphaned artifact. Where modern version control systems embed provenance within the object itself, older code often preserves no trace of authorship, revision history, or purpose. Establishing such context requires external investigation—archival research, oral histories, contemporary publications—much like traditional historical detective work.

**Reborn Digital Heritage:** A further complication arises when historical code undergoes digital rebirth. Code originally preserved on paper printouts, punched cards, or obsolete magnetic media is sometimes transcribed into modern repositories like GitHub, making it accessible to new audiences. This process transforms the artifact: what was once a static paper document becomes a navigable, searchable, and potentially modifiable digital object. Such transcription is an act of interpretation, introducing new temporal layers—the moment of transcription, the decisions of the transcriber—onto an artifact that may already have passed through multiple states. In digital storage, objects exist in constant movement, and the notion of an original state becomes difficult to maintain ([Ernst 2013](https://www.upress.umn.edu/book-division/books/digital-memory-and-the-archive)). For historians, this means attending carefully to the archival history of the code we examine, recognizing that what we see may be several removes from what the original programmers produced.

#### Approaching Code: Key Analytical Questions

When approaching any code artifact, the following questions can guide your analysis. These are not sequential steps but concurrent concerns—a single element of code may illuminate several at once. This is not an exhaustive methodology but a starting point; the field of digital source criticism remains open, and specific sources may raise questions not anticipated here.

**Establishing Provenance and Authenticity:** When encountering code, begin with fundamental questions of authenticity: Who wrote this code? When was it created? Where did it originate? How did it reach us? Just as historians carefully verify the authenticity of manuscripts or documents, we must establish the credible origins of code. Sometimes, proprietary source code becomes available through unauthorized leaks. For example, in 2023, portions of Twitter's source code were leaked on GitHub, revealing aspects of their recommendation algorithm ([Yu 2023](https://www.wowebsites.com/blog/2023/04/twitter-algorithm-code-leaked-and-released-an-explanation/)). Such cases raise distinct questions about authenticity and completeness that historians must consider.

**Questioning the Broader Context:** When and why was this code written? In what environment? What problem did it address? What technological constraints existed? Can you create a technological genealogy? Understanding what a program was designed to accomplish provides essential context for interpretation. You need not understand every technical detail, but grasping the general purpose—Is this a game? A scientific calculation? A business application?—shapes all subsequent analysis. Consider also what technological constraints existed at the time: memory limitations, processing speed, available programming languages, and hardware capabilities all influenced how programmers worked.

**Dependencies and Networks:** You should examine what external code a program relies on, as dependencies reveal networks of collaboration and influence. Like citations in academic papers, dependencies show how programmers built upon existing work and participated in broader development communities. The networked nature of modern software development means that seemingly isolated programs often rely on extensive external code. In 2016, a single developer removing 11 lines of code temporarily disrupted much of the Internet, revealing hidden dependencies in the software ecosystem ([Collins 2016](https://qz.com/646467/how-one-programmer-broke-the-internet-by-deleting-a-tiny-piece-of-code)). Just as historians cross-reference multiple sources, code analysis benefits from comparing similar programs from the same period, examining related documentation, or studying the broader software ecosystem. Look for corroborating evidence in contemporary technical manuals, industry publications, or other preserved codebases.

**Linguistic and Cultural Markers:** Just as a historian might analyze handwriting or paper type, we can examine source code for cultural fingerprints:

* Naming conventions: Variable names like "colorPreference" versus "couleurPreference" can reveal a developer's native language
* Comments: The style and thoroughness of documentation often reflects cultural attitudes toward collaboration
* Programming style: How code is structured and formatted can indicate where and how a developer was trained

> The use of English-based keywords in programming languages like "if," "else," "for," and "while" reflects the dominance of English-speaking countries in early computing history, creating barriers for non-native English speakers. Cultural factors influence programming language design. Some languages tend toward straightforward, more explicit or verbose syntax with clear variable declarations ([Walton 2024](https://rotel.pressbooks.pub/culturally-responsive-computing/chapter/the-culture-of-programming/)).

**Code Structure and Style:** Think of code as having its own "writing style," just like how authors have different ways of organizing their paragraphs and sentences. When examining historical code, pay attention to how it's organized and formatted. This can tell us a lot about:

* The development environment: Well-structured, clean code with consistent indentation and naming often indicates professional settings with established coding standards
* The development context: Code that appears hastily written might reveal academic prototypes, emergency fixes, or situations where speed was prioritized over elegance
* The programmer's background: Just as handwriting reveals personality traits, coding style can reflect a developer's training and experience

> To better understand what "good code structure" looks like in different contexts, you can explore resources like the [MIT Coding and Comment Style guide](https://mitcommlab.mit.edu/broad/commkit/coding-and-comment-style/), which explains coding conventions used in professional and academic settings.

**Comments and Documentation:** Think of comments as the programmer's personal notes and explanations within the code. Comments are portions of text embedded within source code that the compiler or interpreter ignores during execution. These human-readable annotations provide direct windows into thinking processes. Pay attention to how comments explain debugging approaches, clarify complex algorithms, document team decisions, and sometimes include personal reflections or humor that humanizes the technical work. Ask yourself: Is the code written for experienced technical experts or newcomers to programming? Does it include detailed comments that explain complex concepts, or assume prior knowledge? By analyzing these audience considerations, you can better understand broader issues of technological accessibility and the boundaries between different technical communities.

> Code documentation reveals its intended audience through the level of explanation provided. For instance, code intended for expert JavaScript developers typically contains minimal, technical comments assuming significant prior knowledge, while code designed for beginners includes extensive explanations of basic concepts and step-by-step logic ([Emadamerho-Atori, 2024](https://www.altexsoft.com/blog/how-to-write-code-documentation/)).

**Political Dimensions and Power Structures:** Code doesn't exist in a political vacuum - it reflects and shapes power relationships. Who has access to this code? What assumptions about users are embedded in its design? How does it distribute agency between users and systems? The choice between open source and proprietary models reflects different philosophies about technological power and knowledge sharing.

> The ongoing dispute between France and India over Rafale fighter jet source code exemplifies how code embodies political power structures in defense technology. India urgently seeks access to part of the source code of the Rafale, which forms the aircraft's electronic backbone ([Dasgupta, 2025](https://www.india.com/business/what-is-source-code-why-is-it-crucial-for-fighter-planes-know-its-role-in-missile-integration-and-upgrades-7849472/)). This represents a broader tension between India's "Atmanirbhar Bharat" (Self-Reliant India) initiative and Western defense contractors' business model.

**What is Absent or Missing:** Sometimes what code *doesn't* include reveals as much about historical context as what it does. What programming practices, security measures, or accessibility features that we might expect today are missing? These gaps can highlight evolving standards and changing priorities in software development over time. Consider also absences in the historical record itself. The systematic exclusion of the six women who programmed ENIAC from historical documentation for decades demonstrates how what is missing reveals as much as what's included ([Light 1999](https://rybn.org/human_computers/articles/when_computers_were_women.pdf)). This gap in the historical record wasn't accidental but reflected broader societal attitudes that marginalized women's technical contributions, showing how the absence of documentation can be as historically significant as its presence ([MacDonald 2016](https://www.sciencealert.com/these-6-women-were-written-out-of-tech-history)).

![Women programmers holding parts of early Army computers including ENIAC, EDVAC, ORDVAC, and BRLESC-I boards](/assets/images/code-as-heritage/Women_holding_parts_of_the_first_four_Army_computers.jpg "Women holding parts of the first four Army computers")

**Figure 3:** Four women programmers—Patsy Simmers, Gail Taylor, Milly Beck, and Norma Stec—holding boards from early U.S. Army computers (1962). *Credit: U.S. Army Photo 163-12-62, Public Domain, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Women_holding_parts_of_the_first_four_Army_computers.jpg)*

### 2.b Applying Source Criticism to Code: A Case Study — 30 minutes

In Section 2.a, we introduced key analytical questions historians bring to code: establishing provenance, understanding context, reading linguistic and cultural markers, analyzing comments, and attending to what is absent. Now we apply these questions to a specific artifact.

> **A note before you begin:** You are encouraged to search the web at any point during this exercise to help identify the artifact and verify your hypotheses. Searching for names, dates, or technical terms you observe in the document is part of the analytical process—just as a historian might consult reference works while examining an unfamiliar source.

#### Artifact 1: The Image

Examine the following image carefully. Before reading further, spend five minutes observing this document. What clues can you identify about its origins, authors, purpose, and historical context?

![A historical code artifact](/assets/images/code-as-heritage/Original-Microsoft-Source-Code.jpg "A historical code artifact")

**Figure X:** A historical code artifact. Before reading further, spend five minutes examining this image. What can you learn about this code from the artifact itself? *Source: Gates Notes, 2025.*

#### Exercise Part 1: Analyzing the Image

Examine the artifact and answer the following questions:

1. **Provenance and dating:** Who is credited as author? What dates appear? Where did this code originate, and how might it have reached us in this form?

2. **Programming language context:** Look at the document header and structure. Can you identify what programming language this is? What does the format tell us about the relationship between high-level and low-level code in this era?

3. **Cultural markers:** Examine how credit is attributed among the people mentioned. What does the language used—its tone, its informality—reveal about early software culture and workplace dynamics?

4. **Material form:** What type of physical document is this? What printing technology produced it? What do the physical characteristics (paper format, margins, perforations) tell you about the technical environment of the time?

<details>
<summary><strong>Catch up: What is this artifact? (click to expand if you skipped the exercise)</strong></summary>

The image above is a photograph of the original source code for Microsoft BASIC, written in 1975 by Bill Gates and Paul Allen (with contributions from Monte Davidoff). This program, developed for the Altair 8800 microcomputer, was the first product Microsoft ever sold and is considered a foundational artifact in the history of personal computing. The photograph was shared by Bill Gates on his blog in 2025, marking the 50th anniversary of Microsoft.

</details>

#### Artifact 2: The Snippet

Now examine this second artifact. This is the source code of GW-BASIC, a version of Microsoft BASIC developed for IBM PC compatibles, dating from 1983. Microsoft published this code on GitHub in 2020 ([Microsoft, 2020](https://github.com/microsoft/GW-BASIC/blob/master/GWMAIN.ASM)). 

Though written eight years after the first artifact, this code is a direct descendant of the 1975 program—and, as you will see, it carries the memory of its origins in its comments.

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

#### Exercise Part 2: Comparing the Artifacts

You now have two related artifacts before you: a photograph of a 1975 printout and a code file from 1983, published online in 2020.

1. **What changed? What stayed the same?** Compare the two artifacts. What elements appear in both? What differences do you notice in the headers, dates, or content?

2. **Understanding multiple temporalities:** As discussed in Section 2.a, a single code artifact may contain traces of multiple moments. This code has traveled through time:
   - **1975:** Originally written for the Altair 8800 microcomputer
   - **1983:** Evolved and adapted for IBM PC compatibles as GW-BASIC
   - **2020:** The 1983 version deposited in a public GitHub repository by Microsoft
   - **2025:** Photograph of the original 1975 printout shared on Gates Notes
   
   What does each moment add or transform? Why might code need to evolve as technical environments change? How does the same program lineage exist in different material forms—paper printout, magnetic storage, digital repository, photographic image?

#### Explore Further

The artifacts you have examined belong to the lineage of Microsoft BASIC—the program that launched Microsoft as a company in 1975. Bill Gates and Paul Allen wrote the original interpreter for the Altair 8800, one of the first commercially successful personal computers. Over the following years, this code evolved and was adapted for numerous platforms, including the IBM PC and compatibles, where it became known as GW-BASIC.

**Visit the GitHub Repository**

Take a moment to visit the GW-BASIC repository on GitHub: [github.com/microsoft/GW-BASIC](https://github.com/microsoft/GW-BASIC). When you examine the commit history, you will notice something unusual: the dates shown are not 2020 (when Microsoft uploaded the code) but rather reflect the original creation dates from the 1980s. GitHub allows repository creators to set commit dates that correspond to when code was originally written, not when it was deposited in the archive. In this case, Microsoft chose to preserve the historical timestamps.

This is a thoughtful archival decision—but not all historical code you find online receives this level of care. Code surfaces on the web through many channels: official corporate releases, personal repositories, abandonware archives, hobbyist preservation efforts, or even unauthorized leaks. In many cases, the person uploading the code may not know—or may not record—when it was originally written. When you encounter historical code online, approach temporal metadata critically. Ask yourself: does this date reflect when the code was written, when it was uploaded, or something else entirely? The answer is not always obvious.

**Code Evolution and Lineage**

Comparing the 1975 printout with the 1983 file reveals something important about how code travels through time. The 1983 GW-BASIC is not simply a copy of the 1975 Altair BASIC—it is its descendant, adapted for different hardware. The 1975 version ran on the Altair 8800 (Intel 8080 processor); the 1983 version was developed for IBM PC compatibles (Intel 8086/8088). The core logic and structure evolved from the original, but the code itself was transformed to work in a new technical environment.

This pattern—code being reused, adapted, and evolved across platforms and decades—is fundamental to software history. Programs are not static artifacts frozen at the moment of creation; they have lineages, descendants, and branches. Understanding a piece of code often means tracing where it came from and what it became.

**How Later Code Remembers Its Origins**

Notice how the 1983 code preserves memory of its 1975 origins. The comments explicitly state: "ORIGINALLY WRITTEN ON THE PDP-10 FROM FEBRUARY 9 TO APRIL 9 1975." This is the code documenting its own history—a form of self-referential provenance that historians can use to trace lineage.

Yet this memory is not perfectly preserved. Compare how the credits appear in each version:

**1975 version:**
```
BILL GATES WROTE THE RUNTIME STUFF.
PAUL ALLEN WROTE THE NON-RUNTIME STUFF.
MONTE DAVIDOFF WROTE THE MATH PACKAGE.
```

**1983 version:**
```
BILL GATES WROTE A LOT OF STUFF.
PAUL ALLEN WROTE A LOT OF OTHER STUFF AND FAST CODE.
MONTE DAVIDOFF WROTE THE MATH PACKAGE (F4I.MAC).
```

The meaning is similar, but the wording has shifted. The specific technical terms ("RUNTIME" / "NON-RUNTIME") have been replaced with vaguer language ("A LOT OF STUFF" / "A LOT OF OTHER STUFF"). This is a small but telling reminder: when code evolves across versions, even the comments—the human-readable parts meant to document the work—can change. As discussed in Section 2.a, historians must attend to what changes when code passes through different hands and contexts.

**Further Reading**

For additional context on this artifact and its historical significance:

- [Gates, Bill. 2025. 'Celebrating 50 Years of Microsoft'. Gates Notes.](https://www.gatesnotes.com/home/home-page-topic/reader/microsoft-original-source-code)
- [James, Mike. 2025. 'Bill Gates Shares The Code That Launched Microsoft'. I Programmer.](https://www.i-programmer.info/news/82-heritage/17946-bill-gates-shares-the-code-that-launched-microsoft.html)

### 2.c The Journey of the Apollo Code: Preservation, Heritagization, and Hidden Histories — 40 minutes

On 20 July 1969, the Apollo 11 Lunar Module descended to the moon's surface, guided by software developed at MIT's Instrumentation Laboratory. The Apollo Guidance Computer (AGC) software represented one of the most complex programming projects of its era—and one whose survival was far from guaranteed. This case study examines how that code became accessible to historians today, and what a critical approach to the artifact can reveal.

In Section 2.a, we introduced analytical questions for approaching code as historical evidence—questions about provenance, authenticity, context, and cultural markers. The Apollo code provides an opportunity to apply these questions to a concrete artifact. We begin with the original form in which much of this code survived: paper.

#### The Original Artifact: Reading the Paper Listing

![Original source code page 731 of Luminary 099 from Apollo 11, showing the beginning of the BURN_BABY_BURN master ignition routine](/assets/images/code-as-heritage/apollo-11-luminary-099-page-731.jpg "Page 731 of Luminary 099: BURN_BABY_BURN--MASTER_IGNITION_ROUTINE")

**Figure 4:** Original scanned page 731 from the Luminary 099 source code listing for Apollo 11's Lunar Module Guidance Computer, showing the beginning of the BURN_BABY_BURN--MASTER_IGNITION_ROUTINE. This hardcopy listing, digitised from the MIT Museum archives, represents one of the most important preserved examples of space program source code. *Source: [ibiblio.org Apollo Archive](http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/), digitised from MIT Museum collections*

This is a page from the printed source code listing for the Apollo 11 Lunar Module software. Before examining the digitised version, consider what the original paper artifact reveals:

**Physical characteristics:**
- Continuous-feed paper with perforated edges, typical of 1960s computer printouts
- Monospace typeface produced by a line printer
- Page numbers printed on the document itself (Page 731)
- Assembly language notation as it appeared when the code was compiled on 14 July 1969

**What is visible without technical expertise:**
- The routine name at the bottom: `BURN, BABY, BURN -- MASTER IGNITION ROUTINE`
- A timestamp and program identifier in the header area
- Columns of abbreviated instructions and numeric codes

**Exercise Part 1: First Encounter with the Artifact**

Examine Figure 4 carefully. Without any programming knowledge, identify:

- What types of information can you extract from this page? (Consider dates, names, structure, formatting)
- What questions does the artifact raise that it cannot answer? (Consider authorship, purpose, context)
- How does the physical format of continuous-feed paper shape what was preserved?

This exercise demonstrates a key principle: even without technical expertise, historians can extract significant information from code artifacts by attending to their formal properties, visible text, and material characteristics.

#### What Was at Risk: Software Preservation and Archival Silences

The preservation of Apollo's source code represents a rare exception in software history. Software from the 1960s presents particular challenges for historical research. As James Cortada observed in his assessment of the field, "very little software from the 1960s has been preserved," characterising the history of software as "a big, black hole in the history of modern technology" ([Cortada 2002, pp. 72, 77](https://doi.org/10.1109/85.988584)). The Apollo Guidance Computer software survived because paper listings ended up in institutional collections—primarily the MIT Museum—and because dedicated individuals later undertook the labour of digitisation and transcription.

Yet even when code survives, it doesn't carry everything with it. The paper listings document technical decisions but not the conditions under which they were made, the labour that produced them, or the institutional dynamics that shaped the project. These silences become visible when we consider what surrounds the code but is not contained within it. As with any historical source, understanding code requires cross-referencing multiple types of evidence: institutional records, contemporary publications, material artifacts, and testimony from those involved. No single source—however rich—tells the complete story.

#### The Question of Recognition: Gender and Invisible Labour

![Margaret Hamilton standing beside software code listings for the Apollo program](/assets/images/code-as-heritage/Margaret_Hamilton_-_restoration.jpg "Margaret Hamilton with Apollo source code, 1969")

**Figure 5:** Margaret Hamilton in 1969, standing beside the printed source code listings she and her MIT team produced for the Apollo program's Lunar Module and Command Module. The stacks of paper—roughly Hamilton's own height—illustrate the sheer physical scale of 1960s software projects, where code existed primarily as printed documentation. *Credit: Draper Laboratory, Public Domain, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Margaret_Hamilton_-_restoration.jpg)*

This photograph of Margaret Hamilton beside the Apollo code listings vividly illustrates the materiality of software in the 1960s. The physical bulk of the printouts is striking: these stacks, nearly as tall as Hamilton herself, represent hundreds of thousands of lines of code, produced by a team of programmers working under Hamilton's direction at MIT's Instrumentation Laboratory. 

Recovering the conditions behind the code requires sources beyond the artifact itself. Hamilton's oral history interview, conducted by the Computer History Museum in 2004, offers testimony that complements the technical archive. She describes being frequently the only woman in her professional environments and recounts how her coining of the term "software engineering" was initially treated as humorous by hardware engineers before gaining acceptance. She also describes bringing her daughter to the laboratory on nights and weekends to manage the demands of work and family, and facing direct challenges from colleagues who questioned how she could work while having a child at home ([Hamilton 2004](https://www.youtube.com/watch?v=6bVRytYSTEk)). 

These details—about gender dynamics, professional recognition, and the practical conditions of technical labour—do not appear in the code itself. Historians of computing have documented how the programming profession became increasingly masculinised during the 1960s and 1970s. Nathan Ensmenger's research shows that while women had played significant early roles in programming—including the ENIAC programmers of the 1940s—the field's professionalisation involved constructing both a professional and a gender identity, with masculinity serving as one resource for distancing the occupation from its lower-status clerical origins ([Ensmenger 2010, pp. 236-240](https://mitpress.mit.edu/9780262517966/the-computer-boys-take-over/)). Hamilton's testimony provides a first-person account of navigating these dynamics at one of the period's most prominent software projects.

Oral history interviews with software pioneers thus constitute important sources for computing history, capturing dimensions of experience that technical documentation does not record. The Computer History Museum, NASA History Office, and other institutions have conducted interviews that provide context for interpreting archival materials.

#### From Paper to Digital: Questions of Reconstruction

The paper listings held at the MIT Museum are not what most people encounter today when they access the Apollo code. The version available online is a digital reconstruction—transcribed, formatted, and hosted on platforms that did not exist in 1969. For historians, this raises a familiar methodological concern: when we work with a copy or transcription rather than an original, we need to understand the chain of transmission. Who produced the version we are consulting? Under what circumstances? What transformations occurred along the way?

Today, the Apollo 11 source code is accessible on GitHub. Examine the header of the file `BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc`:

**Source:** https://github.com/chrislgarry/Apollo-11/blob/master/Luminary099/BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc

```
# Copyright:	Public domain.
# Filename:	BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc
# Purpose: 	Part of the source code for Luminary 1A build 099.
#		It is part of the source code for the Lunar Module's (LM)
#		Apollo Guidance Computer (AGC), for Apollo 11.
# Assembler:	yaYUL
# Contact:	Ron Burkey <info@sandroid.org>.
# Website:	www.ibiblio.org/apollo.
# Pages:	731-751
# Mod history:	2009-05-19 RSB	Adapted from the corresponding
#				Luminary131 file, using page
#				images from Luminary 1A.
#		2009-06-07 RSB	Corrected 3 typos.
#		2009-07-23 RSB	Added Onno's notes on the naming
#				of this function, which he got from
#				Don Eyles.
#
# This source code has been transcribed or otherwise adapted from
# digitized images of a hardcopy from the MIT Museum.  The digitization
# was performed by Paul Fjeld, and arranged for by Deborah Douglas of
# the Museum.  Many thanks to both.  The images (with suitable reduction
# in storage size and consequent reduction in image quality as well) are
# available online at www.ibiblio.org/apollo.  If for some reason you
# find that the images are illegible, contact me at info@sandroid.org
# about getting access to the (much) higher-quality images which Paul
# actually created.
#
# Notations on the hardcopy document read, in part:
#
#	Assemble revision 001 of AGC program LMY99 by NASA 2021112-061
#	16:27 JULY 14, 1969

# Page 731
## At the get-together of the AGC developers celebrating the 40th anniversary
## of the first moonwalk, Don Eyles (one of the authors of this routine along
## with Peter Adler) has related to us a little interesting history behind the
## naming of the routine.
##
## It traces back to 1965 and the Los Angeles riots, and was inspired
## by disc jockey extraordinaire and radio station owner Magnificent Montague.
## Magnificent Montague used the phrase "Burn, baby! BURN!" when spinning the
## hottest new records. Magnificent Montague was the charismatic voice of
## soul music in Chicago, New York, and Los Angeles from the mid-1950s to
## the mid-1960s.
# BURN, BABY, BURN -- MASTER IGNITION ROUTINE
```

**Exercise Part 2: Tracing the Code's Journey**

Using the header above, answer the questions posed in the previous section:

- Who digitised the original paper listings? Who transcribed them into text files?
- What institution held the source material?
- What changes were made to the files after initial transcription, and when?
- How does the header distinguish between original 1969 content and later additions?

**Exercise Part 3: Comparing Paper and Digital**

Compare the GitHub header with Figure 4 (the original paper listing).

- What information is present in the GitHub version that is absent from the original listing?
- What is present in the original that the digital version cannot fully capture? Consider both informational content and material qualities.
- The modification history notes that Ron Burkey "Corrected 3 typos" in June 2009. In what sense is a corrected transcription "the same" document as its source? How would you describe the relationship between this GitHub file and the 1969 printout in terms of authenticity and fidelity?


**Markers of Heritagization: What the Header Reveals**

The header is a palimpsest—a document where different historical moments coexist, each requiring distinct analytical attention:

**Original historical content (1969):**
- The routine name: `BURN, BABY, BURN -- MASTER IGNITION ROUTINE`
- The assembly timestamp: `16:27 JULY 14, 1969`
- The program identifier: `AGC program LMY99 by NASA`

**Reconstruction and transcription metadata (2009):**
- Transcriber identification: `Ron Burkey <info@sandroid.org>`
- Modification history: dates, initials (RSB), specific changes
- Source documentation: "transcribed or otherwise adapted from digitized images of a hardcopy from the MIT Museum"
- Provenance chain: Paul Fjeld (digitisation), Deborah Douglas (MIT Museum), ibiblio.org

**Added historical context (2009, from oral history):**
- The Magnificent Montague story, added July 2009
- Attribution: "Onno's notes... which he got from Don Eyles"
- The 40th anniversary gathering as source

The header uses different comment markers (`#` vs `##`) to distinguish between transcription notes and added historical context. This transparency is itself a marker of careful heritagization—the archive documents its own construction.

#### Cultural References in Technical Work: The BURN_BABY_BURN Routine

The routine's name warrants attention: BURN_BABY_BURN was not a placeholder or informal label but the official identifier for the master ignition routine controlling the Lunar Module's engine during descent.

**Exercise Part 4: Humour and Cultural References in Code**

Before reading the explanation below, examine the header's account of the routine name's origin. Consider:

- What does the presence of a cultural reference in mission-critical code suggest about the working environment of 1960s aerospace programming?
- The meaning of this name would not be self-evident without Don Eyles' testimony at a 2009 reunion. What does this suggest about the types of sources historians need to interpret code artifacts?

**Humour as a Dimension of Software Culture**

The BURN_BABY_BURN routine name is not an anomaly but an instance of a broader phenomenon. Software development, despite its technical demands, has historically incorporated humour, wordplay, and cultural references as part of its working culture. Recent research has begun to examine this systematically.

Deepika Tiwari, Martin Monperrus, and Benoit Baudry at KTH Royal Institute of Technology studied humour in software projects through analysis of code repositories and a survey of 125 developers. Their findings argue that humour functions as a vector of developer engagement: "The worldwide collaborative effort for the creation of software is technically and socially demanding. The more engaged developers are, the more value they impart to the software they create" ([Tiwari et al. 2024](https://doi.org/10.1109/ICSE-SEIS.2024.12)). Their research found cultural references ranging from film dialogue (*The Big Lebowski*) to literary allusions (*Harry Potter*) to song lyrics embedded in code across diverse projects. Significantly, the researchers note that "humor doesn't detract from the serious side of developing high-quality software"—it coexists with rigorous technical practice.

The BURN_BABY_BURN case illustrates how such references can carry layered meanings. The header explains that the name "traces back to 1965 and the Los Angeles riots, and was inspired by disc jockey extraordinaire and radio station owner Magnificent Montague," who used the phrase when playing hit records on Los Angeles radio station KGFJ. The catchphrase, originally an expression of musical enthusiasm, became associated with the Watts uprising of August 1965, taking on more charged meanings. Montague later reflected on this appropriation with ambivalence, as documented in his autobiography ([Montague and Baker 2003](https://books.google.fr/books?id=tuIY84BT-JIC&printsec=frontcover&source=gbs_book_other_versions_r&redir_esc=y#v=onepage&q&f=false)). MIT programmers Peter Adler and Don Eyles chose this phrase for the master ignition routine in 1966-1967, embedding a reference that carried multiple cultural resonances: musical intensity, social upheaval, and the literal burning of rocket fuel.

#### The Chain of Transmission

The Apollo code's journey can be mapped as a chain of transmission, with each stage enabling certain forms of access while introducing specific transformations:

| Stage | Approximate Date | Form | What Was Preserved | What Was Transformed |
|-------|------------------|------|-------------------|---------------------|
| Original creation | 1966-1969 | Punched cards, magnetic tape | Working software in development environment | — |
| Assembly printout | July 1969 | Paper listings | Human-readable source code | Executability lost |
| Archival deposit | 1970s-2000s | Paper in MIT Museum | Physical artifact | Institutional context, tacit knowledge |
| Digitisation | 2003-2009 | Scanned images | Visual record of pages | Some image quality, materiality |
| Transcription | 2009 | Text files (.agc) | Searchable, executable (via emulator) text | Transcriber's interpretive decisions introduced |
| Platform publication | 2009-present | GitHub repository | Version-controlled, publicly accessible code | Embedded in platform infrastructure |
| Heritage archiving | 2016-present | Software Heritage | Persistent, citable archive | — |

This table illustrates a general principle in archival theory: transmission is never neutral. Each stage enabled certain forms of access—digitisation made the code viewable without visiting MIT; transcription made it searchable and executable via emulators—while introducing particular changes. The modification history ("Corrected 3 typos") shows that even careful transcription involves decisions that alter the artifact. As Wolfgang Ernst has argued, digital objects "exist in constant movement," complicating any straightforward notion of an "original" ([Ernst 2013](https://www.upress.umn.edu/book-division/books/digital-memory-and-the-archive)). 

#### What the Code Cannot Tell Us

To conclude this case study, it is worth reflecting on what we have learned—and what remains beyond the artifact's reach.

The preserved Apollo code allows us to examine technical decisions, trace cultural references, and understand something of how 1960s programmers organised complex software projects. The GitHub header, with its careful documentation of provenance and added historical context, exemplifies thoughtful heritagization that aids future researchers.

Yet the code alone cannot tell us how the team worked day-to-day, what alternatives were considered and rejected, or what it was like to be a woman directing a software division in the 1960s. For those questions, we need other sources: oral histories like Hamilton's interview, institutional records from MIT and NASA, contemporary technical publications, and the broader historiography of computing. The Apollo case thus demonstrates both what code preservation makes possible and why historians must triangulate across multiple source types.

#### Synthesis

This case study has traced how code becomes heritage through a series of decisions, interventions, and transformations. The Apollo software moved from working program to archived printouts to digitised images to transcribed files to online repositories—each stage preserving certain aspects while introducing others. Along the way, we have seen how code documentation captures some forms of authorship while obscuring others, how oral history complements technical archives, and how the chain of transmission shapes what historians can know about the original artifact.

The Apollo code is now preserved across multiple repositories: the Virtual AGC Project at ibiblio.org, the chrislgarry/Apollo-11 GitHub repository, and Software Heritage's persistent archive. These multiple copies serve different preservation functions—accessibility, redundancy, and scholarly citation—illustrating the preservation strategies examined in Section 3.

**Further Reading**

For additional context on the Apollo software and its historical significance:

- Burkey, Ron. Virtual AGC Project. http://www.ibiblio.org/apollo/
- Coding with Dee. 2024. *This Is the Code That Sent Apollo 11 to the Moon (and It's Awesome)*. YouTube video, 19:08. https://www.youtube.com/watch?v=XHN6LV_1dWk
- Di Cosmo, Roberto. 2019. "Archiving and Referencing the Apollo Source Code." *Software Heritage*. https://www.softwareheritage.org/2019/07/20/archiving-and-referencing-the-apollo-source-code/
- Hamilton, Margaret. 2004. Oral history interview. Computer History Museum. https://www.youtube.com/watch?v=6bVRytYSTEk
- Montague, Magnificent, with Bob Baker. 2003. *Burn, Baby! BURN!: The Autobiography of Magnificent Montague*. Urbana: University of Illinois Press.
- Tiwari, Deepika, Tim Toady, Martin Monperrus, and Benoit Baudry. 2024. "With Great Humor Comes Great Developer Engagement." *Proceedings of the IEEE/ACM 46th International Conference on Software Engineering: Software Engineering in Society (ICSE-SEIS)*: 1-11. https://doi.org/10.1109/ICSE-SEIS.2024.12

### 2.d Code as Cultural Expression: Esoteric Languages and Creative Programming - 20 minutes

The examples we have examined so far—GW-BASIC, Apollo guidance software—were created for practical purposes. But programming has always had creative and playful dimensions. Even in mission-critical Apollo code, we found cultural humor embedded in technical work.

Some programmers take this further, creating languages and programs whose primary purpose is expression rather than utility. These reveal programming as a form of cultural practice irreducible to its technical functions.

**Esoteric Programming Languages**

Esoteric programming languages (or "esolangs") are intentionally designed not for practical software development, but rather to challenge conventional programming paradigms and provide amusement for programmers ([Paloque-Bergès 2009](https://www.laprocure.com/product/1282150/paloque-berges-camille-poetique-des-codes-sur-le-reseau-informatique)). Think of them as programming's equivalent to experimental art or wordplay—they serve as creative expressions, intellectual puzzles, or even jokes that reveal the playful and cultural dimensions of programming beyond its purely functional aspects.

**The Esoteric File Archive**

The [Esoteric File Archive repository](https://github.com/graue/esofiles) is a digital repository dedicated to preserving these unusual programming languages that might otherwise be lost to digital obsolescence. As the archive's creator explains in their own words: "websites devoted to esoteric programming languages tended to periodically go down... people who wanted to check out that language were out of luck" (Feeney [2013] 2025)

Simple exploration steps:

1. Browse the repository folders (hunter, chef, shakespeare, befunge, etc.)
2. Open one language folder that interests you
3. Examine the code examples and documentation

For example, the [hunter folder](https://github.com/graue/esofiles/tree/master/hunter) and its [documentation](https://github.com/graue/esofiles/blob/master/hunter/doc/hunter.txt) file reveal a programming language created by Chris Pressey in 2000 where programs are visualized as "mice in a space interacting with cheese and each other" (Pressey 2000). 

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

**BONUS Exercise: Code as Archaeological Evidence**

Reading: [David M. Berry's "Digital Ruins and Critical Code Studies: Towards an Ethics of Historical Software Reconstruction"](https://stunlaw.blogspot.com/2025/01/digital-ruins-and-critical-code-studies.html)

**Analysis questions:** After reading Berry's discussion of "digital ruins," consider:

1. **Historical parallels:** Berry compares software reconstruction to architectural preservation. Identify two specific principles from architectural preservation (mentioned in the text) that he argues should apply to code reconstruction. How do these principles address the challenge of maintaining historical authenticity?
2. **Evidence evaluation:** In the ELIZA reconstruction case study, the team had to create entirely new functions (like LETTER and BCDIT) that were missing from the original archives. According to Berry's framework, how should such reconstructions be marked or documented to distinguish them from original historical code?

### Reading/viewing suggestions 

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


## 3 Preserving Code: Initiatives and Infrastructures

> [!NOTE]  
> **Learning Objectives for Section 3:**
> By completing this section, you will be able to:
> - Apply source criticism to code, analyzing it as technical object, textual artifact, historical trace, and archival construction
> - Navigate the Software Heritage archive and understand its organizational structure
> - Evaluate the strengths and limitations of different preservation strategies
> - Understand the role of persistent identifiers in digital scholarship

Having examined code preservation challenges and historical analysis techniques, we now turn to actual archiving initiatives. This section examines how different institutions with different values and missions have approached the challenge of preserving software heritage. Understanding these institutional contexts helps us interpret their choices and recognize what each approach captures and what it may miss.

### 3.a Software Heritage: Mission, Scope and Infrastructure - 30 minutes

Software Heritage emerged from academic research culture. Founded in France in 2016 by Roberto Di Cosmo (a computer science professor) with institutional support from the National Institute for Research in Computer Science and Automation (INRIA), it reflects scholarly values: comprehensive collection, rigorous documentation, persistent citation through identifiers, and open access. Its organizational model—a nonprofit foundation with academic, governmental, and industry partners—prioritizes long-term preservation over commercial considerations. The initiative's publications appear in academic venues; its methods are documented for scholarly scrutiny.

Think of Software Heritage as a response to an important assessment: preserving source code isn't something that can be done through individual, scattered efforts. Instead, it requires well-organized, institutional approaches ([Di Cosmo and Zacchiroli 2017](https://www.softwareheritage.org/wp-content/uploads/2020/01/ipres-2017-swh.pdf)). To understand its focus, imagine a library that aims to collect all publicly available books - Software Heritage does this for open source code, though it cannot include proprietary code that is legally protected. Despite this necessary limitation, the archive has still managed to collect an impressive collection of millions of software projects and repositories.

Software Heritage aims to preserve everything publicly available. This comprehensive approach is like preserving an entire ecosystem rather than just a few species. Why does this matter? Because historical significance often isn't apparent immediately. By preserving the complete landscape of software development, future researchers will have access to much richer historical evidence than they would with a more selective approach.

**Technical Architecture**

Think of Software Heritage's interface as a library with a special organization system designed for two key purposes: safeguarding code for future generations while making it accessible for today's researchers and developers. The platform organizes preserved code into three fundamental levels:

* Source files: The individual pieces of code 
* Commits: Snapshots of code at specific moments in time
* Projects: Complete software repositories

This three-tier organization mirrors how software development works in practice, providing stable reference points that historians and researchers can use for consistent analysis.

When exploring Software Heritage, you will find search and browsing tools that open up multiple pathways for historical investigation. One limitation is that the archive lacks currently intuitive browsing capabilities, making it difficult to explore without specific search criteria in mind. If you have one, you could, for example, track how specific algorithms have evolved over decades, examine shifts in programming practices across different time periods, or map out the collaborative networks behind major software projects.

What makes this archive particularly valuable for scholarly work is its system of persistent identifiers - these function like permanent citation codes, ensuring that references to code remain valid indefinitely. This solves a crucial problem in digital scholarship ([Cosmo et al. 2020](https://ieeexplore.ieee.org/document/8946737/)) that researchers in other fields, such as web archiving, have similarly struggled with - how to create stable, lasting references to digital materials that might otherwise change or disappear.

**Exercise: Understanding Software Heritage's Development** 

To understand how Software Heritage developed into a major preservation initiative, the following complementary resources merit examination:

*[Note: The Schafer 2017 source below is in French. This exercise will be revised to include English-language alternatives.]*

* [Schafer, Valérie (2017). 'Le Logiciel Libre, de l'usage à La Recherche, Entretien avec Roberto Di Cosmo'. Bulletin 1024, 39-52.](https://1024.socinfo.fr/2017/09/1024_11_2017_39.html)

Focus particularly on pages 49 onward, where Di Cosmo discusses the founding vision and early challenges of Software Heritage.

Then examine this milestone report to see how the project matured:

* [Cosmo, Roberto Di. 2022. 'Software Heritage in 2021: Five Years Already!' Software Heritage, January 5.](https://www.softwareheritage.org/2022/01/05/software-heritage-in-2021-five-years-already/)

**Guided reflection questions:**

1. Who were the key figures in founding Software Heritage, and what specific problems were they trying to solve with this initiative?
2. How has the project evolved by 2021 in terms of institutional support, technical infrastructure, and preservation achievements?

**Exercise: Navigating Software Heritage**

This exercise guides you through the Software Heritage archive. Begin at the homepage: www.softwareheritage.org

**Step 1: Quick analysis:** As you examine the website, identify and take notes on how the platform communicates these three key aspects:

* Its heritage mission (What problem is it trying to solve? Why preserve code?)
* Community engagement opportunities (How can visitors contribute to this preservation effort?)
* The types and categories of code within Software Heritage's preservation scope

**Step 2: Features exploration:** Next, navigate to the features page: www.softwareheritage.org/software-heritage-features/ In your notes, categorize which features specifically address:

* Searchability and discovery (How do researchers find what they need?)	
* Long-term preservation strategies (How does the archive ensure code remains accessible decades from now?)

**Critical thinking questions:** After your exploration, consider these deeper questions:

1. How does the three-tier organization system ("Source Files," "Commits," and "Projects") mirror actual software development workflows? How might this organizational approach benefit different types of historical research?
2. Why are persistent identifiers so crucial for digital scholarship? How do they address challenges we discussed in Section 2 regarding code as archival construction?

### 3.b Comparative Preservation Approaches - 25 minutes

Software Heritage represents one approach to digital preservation. To situate it within the broader field, we can compare it with initiatives that emerge from different institutional contexts and reflect different values. These different preservation strategies function similarly to how museums, libraries, and archives might each preserve cultural artifacts differently. Each approach has unique strengths and limitations that reflect their specific preservation goals and institutional missions.

**GitHub Archive Program: A Corporate Initiative**

The GitHub Archive Program represents a different institutional logic. GitHub, owned by Microsoft since 2018, is a commercial platform where most of the world's open-source development now takes place. The Archive Program—including the Arctic Code Vault—serves multiple purposes: genuine preservation, corporate social responsibility, and platform legitimation. This is not criticism but context: understanding *who* preserves code and *why* shapes how we interpret preservation choices.

Launched in 2020, the program creates secure, long-term backups through multiple storage methods - think of it as creating several types of time capsules simultaneously. Perhaps most fascinating is the [Arctic Code Vault](https://www.youtube.com/watch?v=0v9Rwqxa8eI), housed in an abandoned mine deep within Svalbard's Arctic archipelago, where code is stored in a facility designed to last centuries.

![GitHub Open Source Archive Box with AI-generated design](/assets/images/code-as-heritage/GitHub_Archive_Box.png "GitHub Archive Box")

**Figure 7:** A museum-quality archival case designed by artist and engineer Alex Maki-Jokela for the GitHub Archive Program. The box features 3D-printed and AI-generated artwork, and contains 17,000 open-source repositories archived on hardened film designed to survive 1,000 years. The aesthetic design reflects an important principle: that preservation efforts must be valued as objects in themselves to ensure long-term commitment to heritage protection. *Credit: GitHub Archive Program, Design by Alex Maki-Jokela, via [GitHub Archive Program](https://archiveprogram.github.com/greatest-hits/)*

![Interior of the Svalbard Global Seed Vault storage facility in the Arctic](/assets/images/code-as-heritage/Svalbard_seed_vault_IMG_8894.JPG "Svalbard Global Seed Vault entrance")

**Figure 8:** The entrance to the Svalbard Global Seed Vault, an underground facility in the Arctic designed to preserve plant seeds for centuries. The GitHub Arctic Code Vault was intentionally placed near this seed vault as a conceptual parallel—both preserve humanity's most precious biological and digital heritage in a location designed to survive catastrophic changes. *Credit: Bjoertvedt, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/), via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Svalbard_seed_vault_IMG_8894.JPG)*

What makes this approach educationally valuable is its concept of "pace layers" - different preservation methods designed to function across various time scales, from years to millennia. This layered approach helps ensure that our digital heritage remains accessible to future generations regardless of technological changes ([GitHub Archive Program 2025](https://archiveprogram.github.com/)).

**Internet Archive Software Collection: The Pioneer Spirit**

The Internet Archive, founded by Brewster Kahle in 1996, embodies the idealism of early internet culture—the belief that digital technology could democratize access to human knowledge. Its motto, "Universal Access to All Knowledge," reflects this founding vision. 

While Software Heritage focuses primarily on preserving source code (the building blocks of software), the Internet Archive takes a different approach. It preserves the complete software experience by collecting not just executable programs, but also their accompanying documentation, media, and cultural artifacts that help users understand the historical context in which the software was actually used. Think of this as preserving not just a historical building, but also photographs, newspapers, and artifacts showing how people lived in and interacted with that building. 

This holistic collection ranges from early personal computer applications to beloved classic arcade games, and importantly, offers something unique for hands-on learning: emulated environments where users can actively experience the software functioning as it did decades ago, rather than just passively viewing static code ([Internet Archive 2025](https://archive.org/details/software)).

![Staff at the Internet Archive warehouse sorting physical software materials for the software collection](/assets/images/code-as-heritage/Internet_Archive_software_collection_sorting.jpg "Internet Archive software collection sorting")

**Figure 9:** Archivists at the Internet Archive's warehouse in 2018 sorting physical software materials as part of the ongoing effort to preserve and digitize the software collection. This image reveals the physical labor and curatorial work involved in heritage preservation—the human effort behind digitization and archiving initiatives. *Credit: Jason Scott, [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/), via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:2018-03_Internet_Archive_software_collection_sorting.jpg)*

**Comparing Approaches**

To understand the different approaches to software preservation, consider this analogy: If software were a book, these preservation strategies would focus on different aspects:

1. Source code preservation (Software Heritage): Preserves the "manuscript" (human-readable instructions and collaborative development processes)
2. Archive storage (GitHub Arctic Vault): Creates secure "vaults" that protect against catastrophic loss
3. Executable preservation (Internet Archive): Maintains the "reading experience" (how users actually interacted with the software)

Each approach preserves a unique dimension of software as cultural heritage, and together they provide a more complete historical record ([Matthews *et al.* 2010](https://www.ijdc.net/index.php/ijdc/article/view/145/210)).

| Initiative | Institutional Base | Primary Values | Preservation Focus |
|------------|-------------------|----------------|-------------------|
| **Software Heritage** | Academic/Research | Comprehensiveness, citation, scholarly access | Source code as text |
| **GitHub Archive Program** | Corporate | Longevity, redundancy, visibility | Source code as files |
| **Internet Archive** | Nonprofit/Pioneer | Universal access, experiential preservation | Software as experience |

**Exercise: Comparing Preservation Strategies** 

In this structured activity, you'll analyze three different approaches to software preservation, each with unique strengths and philosophies.

**Part 1: GitHub Archive Program**

Visit and carefully examine: archiveprogram.github.com

**Guiding Questions:**

1. Compare and contrast: What core preservation goals does GitHub Archive Program share with Software Heritage, and what fundamental differences can you identify in their preservation methodologies?
2. Environmental considerations: What specific properties of the Arctic location make it suitable for the Code Vault, and how does this physical storage strategy reflect GitHub's thinking about different preservation timescales?

**Part 2: Internet Archive Software Collection**

Explore the collection: archive.org/details/software Internet Archive Software Collection

For a concrete example, examine: archive.org/details/jsmess_engine_v2 

**Critical Analysis Questions:**

1. Preservation philosophy: How does the Internet Archive's approach to software preservation fundamentally differ from both Software Heritage and GitHub Archive Program in terms of what aspects of software history it prioritizes?
2. Historical significance: Browse the main categories visible on the Collection homepage and identify distinct types of software preserved there. Evaluate why preserving this diversity of software types—from early computer programs to web-based applications—contributes to our understanding of technological and cultural evolution.

**Comparative reflection:** How do these three approaches—comprehensive source code archiving, secure long-term storage, and executable preservation—address different aspects of code as heritage? Which aspects might still be missing from current preservation efforts?

## Conclusion

This lesson has introduced you to source code as a distinctive form of born-digital heritage—one that demands adapted methods of historical analysis while offering unique insights into our digital age.

**Heritage recognition.** Source code has gained official recognition as cultural heritage, but this recognition comes with awareness of its fragility and the active effort required to preserve it. Unlike monuments or manuscripts, code faces threats from technological obsolescence, platform changes, and the ephemeral nature of digital storage. Preservation requires not passive storage but continuous, intentional intervention.

**Interpretive methods.** Reading code as a historian requires adapting traditional source criticism for born-digital materials. The layered reading approach we developed—attending simultaneously to code as technical object, textual artifact, historical trace, and archival construction—offers a framework for this work. As our case studies demonstrated, the boundaries between "external" and "internal" criticism become productively blurred in digital sources: the artifact often documents its own history, embedding provenance information within itself. This is not a failure of method but a characteristic of digital heritage that historians must learn to navigate.

The Apollo case study illustrated how code becomes heritage through a chain of decisions and transformations: from working software to archived printouts to digitized images to transcribed files to online repositories. Each stage shapes what we can know about the original artifact. The journey also revealed what code alone cannot tell us—the gender dynamics, institutional contexts, and invisible labor that require sources beyond the code itself to recover.

**Preservation infrastructure.** Major initiatives like Software Heritage, the GitHub Archive Program, and the Internet Archive Software Collection address different dimensions of code preservation from different institutional positions. Software Heritage, rooted in academic values, prioritizes comprehensive collection and scholarly citation. GitHub's corporate initiative emphasizes longevity and redundancy through dramatic physical storage. The Internet Archive, embodying early internet idealism, focuses on preserving the experiential dimension—how software actually worked and felt to use. No single approach captures everything; together, they work toward a more complete record of our digital heritage.

**Looking forward.** The methods and resources introduced in this lesson open possibilities for research across multiple fields: history of technology, intellectual history, cultural studies, science and technology studies. As more code becomes accessible through preservation initiatives, and as tools for analyzing large codebases improve, the potential for historical research will only grow.

Throughout, we have emphasized that code is never merely technical. It embeds assumptions, reflects power structures, and bears the marks of its creators' cultures and contexts. Approaching code critically means attending to what is present and what is absent, who is credited and who is overlooked, what is preserved and what is lost. This critical stance—borrowed from traditional source criticism but adapted for digital materials—is what distinguishes historical analysis of code from technical documentation.

You are now equipped to begin exploring code as heritage: to read it not just for what it does, but for what it reveals about the humans who created it and the world in which they worked.