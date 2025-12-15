# Todo List - Code as Heritage

## Corrections

### Text Clarifications Needed

- [ ] **Section 2.a, "The Inheritance of Source Criticism"** - Reword the following sentence as it overstates the accessibility claim:
  
  **Current:** "Understanding what code does benefits from basic familiarity with programming concepts—not expertise, but enough literacy to recognize structures, follow logic, and understand why certain choices were made."
  
  **Issue:** This sentence minimizes the actual expertise required. Recognizing structures, following logic, and understanding technical choices *does* require substantive programming knowledge—more than "basic familiarity."
  
  **Suggested revision:** Clarify the level of expertise actually needed, or more accurately describe what can be understood without programming experience versus what requires deeper technical knowledge.

- [ ] **Section 2.a, "The Entanglement Problem"** - Develop this section with more theoretical depth:
  
  **Current issue:** The section identifies the problem (that external/internal criticism distinction breaks down for born-digital sources) but lacks sufficient theoretical scaffolding to explain *why* this matters methodologically or how it changes our approach to historical analysis.
  
  **Needs expansion on:**
  - The epistemological implications: How does this challenge traditional source criticism methods?
  - Specific examples of how metadata embedding creates interpretive challenges
  - Theoretical frameworks from digital humanities/digital history scholarship to contextualize the problem
  - How this "entanglement" might actually provide advantages for historical analysis

- [ ] **Section 2.b, "Programming Languages as Historical Markers" - Exercise using Rosetta Code** - Enhance with concrete examples and better pedagogical guidance:
  
  **Current issue:** The exercise asks students to "compare implementations across three eras" but provides only generic prompting ("What differences do you notice?") without sufficient scaffolding or concrete examples to guide analysis.
  
  **Needs improvement:**
  - Provide 2-3 actual code examples from Rosetta Code (complete "Hello World" programs in languages from different eras)
  - Include specific analytical questions that walk students through what to look for (verbosity levels, syntax structure, commenting patterns, memory constraints reflected in code)
  - Add expected observations/insights so instructors and students can calibrate their analysis
  - Consider providing side-by-side comparison format to make differences more visible
  - Clarify what students should conclude about how historical context shaped language design

- [ ] **Section 2.c, "The Journey of the Apollo Code"** - Complete rework required:
  
  **Current status:** This entire section needs to be written/substantially reworked by hand.
  
  **Purpose:** This section should serve as the major case study for the lesson, using the Apollo 11 code (particularly the BURN_BABY_BURN--MASTER_IGNITION_ROUTINE) to demonstrate all the analytical methods introduced in sections 2.a and 2.b.
  
  **Should include:**
  - Narrative of how Apollo code was lost and then recovered
  - Close reading of specific code excerpts using the "layered reading" approach
  - Analysis of naming conventions, comments, and cultural context
  - Discussion of the Margaret Hamilton story and women programmers
  - Connection to preservation efforts and Software Heritage
  - Guided exercises for students to practice code analysis techniques

## Margaret Hamilton & Apollo 11 Case Study

### Tasks
- [ ] Develop the Margaret Hamilton case
- [ ] Reconstruct the code of the Apollo 11
- [ ] Focus on the BURN_BABY_BURN--MASTER_IGNITION_ROUTINE
- [ ] Check for excessive use of "let's explore" in the text and replace with varied transitions
- [ ] Rewrite image legends for consistency and clarity across all figures

### Reference: BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc

**Source:** https://github.com/chrislgarry/Apollo-11/blob/master/Luminary099/BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc

**Key Context:**
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

**Historical Note:** The routine's name was inspired by disc jockey Magnificent Montague's phrase from the 1965 Los Angeles riots era, demonstrating how cultural moments influenced even the most technical code of the Apollo program.

### Potential Links
- [Humor as an Important Ingredient in Software Development (KTH)](https://www.kth.se/en/eecs/nyheter/humor-en-viktig-ingrediens-i-mjukvaruutveckling-1.1351788)

### Rosetta Code: Hello World/Text

**URL:** https://rosettacode.org/wiki/Hello_world/Text

**Purpose:** A comprehensive collection of "Hello World!" programs written in 300+ programming languages, organized chronologically from early mainframe languages (Assembly, COBOL, FORTRAN) through modern languages.

**Why It's Valuable for Code as Heritage:**

1. **Historical Timeline of Programming Languages**: The repository provides vivid examples of how programming practices have evolved across different eras:
   - 1950s-60s: Assembly, early FORTRAN, COBOL (verbose, hardware-constrained)
   - 1970s-80s: C, Pascal, BASIC (emergence of structured programming)
   - 1990s onwards: Python, Java, JavaScript (higher abstractions, readability focus)

2. **Cultural and Design Philosophy Markers**: By comparing "Hello World" implementations across languages, students can observe:
   - How language design reflects different philosophical approaches (e.g., Python's emphasis on readability vs. C's minimalism)
   - The influence of specific communities and time periods on language design
   - How programming languages themselves are cultural artifacts

3. **Pedagogical Value for Code as Communication**: Rosetta Code embodies the principle from Abelson & Sussman that "Programs must be written for people to read"—the same Hello World program looks vastly different depending on the language's design choices.

4. **Esoteric Languages Documentation**: The archive includes implementations in esoteric languages (Befunge, INTERCAL, Brainfuck), connecting to the section on esoteric programming languages as cultural expression.

**Suggested Integration Points:**
- Section 1.a (Understanding Source Code): Use Rosetta Code to illustrate how programming languages encode different assumptions about what code should communicate
- Section 2.a (External Criticism): Compare implementations across decades to identify chronological markers
- Section 2.b (Internal Criticism): Use language-specific implementations to identify cultural markers in naming conventions and code structure
- Potential exercise: Students select 3-4 languages from different eras and analyze how their Hello World implementations reflect the values and constraints of their historical moment

**Context:** A KTH research project by Deepika Tiwari, Benoit Baudry, and Martin Monperrus studied humor in software development. Their key finding: "What surprised us most when we started looking for humour in software is that it has always been there. Even in the Apollo mission code, we found jokes, which was funny."

The research examined cultural expressions in code, discovering everything from The Big Lebowski dialogues to Harry Potter references and song lyrics in software projects. The paper "With Great Humor Comes Great Developer Engagement" was presented at an International Conference on Software Engineering.

**Key Insight:** "Humour doesn't detract from the serious side of developing high-quality software." This directly relates to the BURN_BABY_BURN routine—a prime example of how cultural humor was embedded in critical Apollo program code.

---

## FORTRAN Historical Sources for Main Text

**Software Preservation Archive:** https://softwarepreservation.computerhistory.org/FORTRAN/

**Purpose:** When mentioning FORTRAN in the code-as-heritage lesson, this Computer History Museum archive provides rigorous historical sources and primary documents.

⚠️ **IMPORTANT ACCESSIBILITY NOTE:** The Software Heritage Exercise (Section 3.a in code-as-heritage.md) references a French-language source (Schafer 2017, Bulletin 1024) that is not accessible to English-speaking students. This section needs to be rethought to:
- Find equivalent English-language resources about Software Heritage's founding vision
- Consider adding English summaries or translations of key points from the French source
- Ensure all primary sources for student exercises are available in English or have English alternatives

**Why This Archive Matters for Your Research**

**Parallel Development Context:**
- FORTRAN released April 1957 (first high-level language, IBM 704)
- Apollo AGC development accelerated 1961-1969
- FORTRAN represents one extreme: high-level abstraction, compiler optimization, developer productivity
- AGC assembly language represents the opposite: bare-metal control, mission-critical reliability, absolute timing precision
- Understanding both illuminates the philosophical choices embedded in code

**Archive Contents Relevant to Teaching:**
- Original IBM 704 FORTRAN II compiler source code (3 volumes, 4-8K drum versions)
- John Backus's original 1954 proposal and 1957 formal specifications
- Interviews and biographies of FORTRAN developers
- Contemporary user stories and adoption histories
- Historical memos showing real design decisions and frustrations

### Recommended Citations for Main Lesson

1. **Language Design Philosophy:**
   - J.W. Backus et al. "The FORTRAN Automatic Coding System." Proceedings Western Joint Computer Conference, 1957.
   - John W. Backus. "The history of FORTRAN I, II and III." Proceedings First ACM SIGPLAN Conference on History of Programming Languages, 1978.
   - These show how FORTRAN prioritized mathematical expressivity while AGC prioritized mission control.

2. **Software Preservation Methodology:**
   - The archive documents how FORTRAN itself has been preserved: from handwritten documentation to microfilm to digital transcription to online access
   - Parallels the archival challenges with Apollo source code and justifies why preservation of code-as-heritage is necessary

3. **Developer Culture:**
   - Mark Halpern. "On the Heels of the Pioneers - A Memoir of the Not-quite-earliest Days of Programming." Annals of the History of Computing, 1991.
   - Shows how FORTRAN developers worked in similar cultural and institutional contexts as Apollo developers

### Key Distinction for Contrast
The FORTRAN archive helps position Apollo code not as an anomaly but as a deliberate choice. While FORTRAN optimized for efficiency and ease-of-use, AGC developers optimized for absolute reliability under extreme constraints—making the cultural expressions (like "BURN, BABY, BURN") all the more significant: they represent humanity persisting within machine language.
