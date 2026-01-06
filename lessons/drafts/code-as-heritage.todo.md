# Todo List - Code as Heritage (v2)

## Corrections

### Text Clarifications Needed

- [ ] **Section 2.a, "The Inheritance of Source Criticism"** - Reword the following sentence as it overstates the accessibility claim:
  
  **Current (lines ~197-199):** "Understanding what code does benefits from basic familiarity with programming concepts—not expertise, but enough literacy to recognize structures, follow logic, and understand why certain choices were made."
  
  **Issue:** This sentence minimizes the actual expertise required. Recognizing structures, following logic, and understanding technical choices *does* require substantive programming knowledge—more than "basic familiarity."
  
  **Suggested revision:** Clarify the level of expertise actually needed, or more accurately describe what can be understood without programming experience versus what requires deeper technical knowledge.

- [ ] **Section 2.a, "The Entanglement Problem"** - **DRAFT: Needs more theoretical depth:**
  
  **Current status:** This section remains a draft. While it now includes references to Fickers 2012 and Kirschenbaum 2008 and introduces the "layered reading" approach, it requires substantial reworking.
  
  **Needs expansion on:**
  - The epistemological implications: How does this challenge traditional source criticism methods?
  - More specific examples of how metadata embedding creates interpretive challenges
  - Theoretical frameworks from digital humanities/digital history scholarship to contextualize the problem
  - How this "entanglement" might actually provide advantages for historical analysis
  - Clearer connection between the theoretical framing and the practical exercises that follow

- [ ] **Section 2.b, "Programming Languages as Historical Markers" - Exercise using Rosetta Code** - Enhance with concrete examples and better pedagogical guidance:
  
  **Current issue (lines ~255-265):** The exercise asks students to "compare implementations across three eras" but provides only generic prompting ("What differences do you notice?") without sufficient scaffolding or concrete examples to guide analysis.
  
  **Needs improvement:**
  - Provide 2-3 actual code examples from Rosetta Code (complete "Hello World" programs in languages from different eras)
  - Include specific analytical questions that walk students through what to look for (verbosity levels, syntax structure, commenting patterns, memory constraints reflected in code)
  - Add expected observations/insights so instructors and students can calibrate their analysis
  - Consider providing side-by-side comparison format to make differences more visible
  - Clarify what students should conclude about how historical context shaped language design

- [ ] **Section 2.c, "The Journey of the Apollo Code"** - **DRAFT: Needs further development**
  
  **Current status:** This section has initial content in v2 (lines 320-510) but remains a draft requiring rethinking and refinement.
  
  **Current elements (need review/expansion):**
  - Narrative of how Apollo code was nearly lost and recovered
  - Close reading of specific code excerpts using the "layered reading" approach
  - Analysis of naming conventions (BURN_BABY_BURN), comments, and cultural context
  - Discussion of the Margaret Hamilton story and women programmers
  - Connection to preservation efforts and Software Heritage
  - Multiple guided analysis tasks for students
  
  **Still needed:**
  - Deeper integration of analytical methods from 2.a and 2.b
  - More rigorous scholarly framing
  - Review of pedagogical scaffolding in exercises
  - Possible restructuring of the narrative flow

## Margaret Hamilton & Apollo 11 Case Study

### Tasks - **DRAFT: Needs rethinking from current version**

**Current status:** Initial content exists in Section 2.c but the Margaret Hamilton case study requires substantial rethinking and development.

- [ ] **Rethink the Margaret Hamilton case** - Current version in "The Human Context" subsection needs:
  - Deeper engagement with gender dynamics in computing history
  - Better integration with the code analysis (not just a separate subsection)
  - More primary sources and scholarly framing
  - Clearer pedagogical purpose

- [ ] **Refine the Apollo 11 code reconstruction narrative** - Current version needs:
  - Stronger connection to preservation/heritagization themes
  - More nuanced discussion of what was lost vs. recovered
  - Better scaffolding for student analysis

- [ ] **Strengthen BURN_BABY_BURN analysis** - Current version needs:
  - Deeper cultural/historical context
  - Clearer analytical framework application
  - More rigorous exercise design

- [ ] Check for excessive use of "let's explore" in the text and replace with varied transitions
- [ ] Rewrite image legends for consistency and clarity across all figures

### Reference: BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc ✅ INTEGRATED

**Status:** This reference material has been integrated into Section 2.c of v2. The full code header is now included in the lesson with guided analysis tasks.

**Source:** https://github.com/chrislgarry/Apollo-11/blob/master/Luminary099/BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc

**Historical Note:** The routine's name was inspired by disc jockey Magnificent Montague's phrase from the 1965 Los Angeles riots era, demonstrating how cultural moments influenced even the most technical code of the Apollo program. *(Now discussed in v2 under "Humor in Mission-Critical Code")*

### Potential Links ✅ INTEGRATED
- [Humor as an Important Ingredient in Software Development (KTH)](https://www.kth.se/en/eecs/nyheter/humor-en-viktig-ingrediens-i-mjukvaruutveckling-1.1351788) - **Cited in v2 Section 2.c**

### Rosetta Code: Hello World/Text - STILL NEEDS ENHANCEMENT

**URL:** https://rosettacode.org/wiki/Hello_world/Text

**Status:** Referenced in v2 Section 2.b but the exercise still lacks concrete code examples and detailed pedagogical scaffolding.

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

4. **Esoteric Languages Documentation**: The archive includes implementations in esoteric languages (Befunge, INTERCAL, Brainfuck), connecting to the section on esoteric programming languages as cultural expression. *(Section 2.d now covers esoteric languages)*

**TODO for Rosetta Code exercise:**
- [ ] Add 2-3 actual code examples (FORTRAN, C, Python side-by-side)
- [ ] Include specific analytical questions (verbosity, syntax, memory constraints)
- [ ] Add expected observations for instructors
- [ ] Consider side-by-side comparison format

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

---

## Accessibility Issues

### French-Language Source in Section 3.a ⚠️ PARTIALLY ADDRESSED

**Status in v2:** The lesson now includes an inline note acknowledging the issue:
> *[Note: The Schafer 2017 source below is in French. This exercise will be revised to include English-language alternatives.]*

**Still TODO:**
- [ ] Find equivalent English-language resources about Software Heritage's founding vision
- [ ] Add English summaries or translations of key points from the French source
- [ ] Ensure all primary sources for student exercises are available in English or have English alternatives

---

## Summary of Remaining Tasks

### High Priority - Major Drafts Requiring Rework
- [ ] **Add clear learning goals for each of the 3 main sections:**
  - [ ] Section 1 (Understanding Digital Heritage Recognition) - Define specific learning outcomes
  - [ ] Section 2 (Learning to Read Code as Cultural Text) - Define specific learning outcomes
  - [ ] Section 3 (Preserving Code: Initiatives and Infrastructures) - Define specific learning outcomes
- [ ] **Section 2.a theoretical depth** - Needs substantial theoretical scaffolding, not just sentence fixes
- [ ] **Section 2.c Apollo case study** - Draft needs further development and refinement
- [ ] **Margaret Hamilton case study** - Needs rethinking from current version
- [ ] Reword Section 2.a sentence about expertise/accessibility
- [ ] Enhance Rosetta Code exercise with concrete examples
- [ ] Resolve French-language source accessibility issue
- [ ] **Section 3 Reading/viewing suggestions** - Currently missing; Section 3 has no reading suggestions section unlike Sections 1 and 2

### Medium Priority  
- [x] Check for excessive "let's explore" phrasing ✅ Completed - replaced with measured academic language
- [ ] Review image legends for consistency
- [ ] Review pedagogical scaffolding across all exercises

### Completed/Integrated in v2 ✅
- [x] KTH humor research integrated (cited in Section 2.c)
- [x] Section 2.d on esoteric languages added
- [x] Comprehensive reading/viewing suggestions added
- [x] Section 3 preservation initiatives expanded
- [x] BURN_BABY_BURN code header included (but analysis needs refinement)
- [x] Check for excessive "let's explore" phrasing - replaced with academic tone
