# Todo List - Code as Heritage (v2)

## General Issues (Lesson-wide)

- [ ] Check for excessive use of "let's explore" in the text and replace with varied transitions
- [ ] Rewrite image legends for consistency and clarity across all figures
- [ ] Review pedagogical scaffolding across all exercises

---

## Section 1: Understanding Digital Heritage Recognition

**Status:** ✅ COMPLETE

- [x] Learning objectives added
- [x] All subsections (1.a, 1.b, 1.c) developed with content and exercises
- [x] Reading/viewing suggestions added
- [x] Figure captions and credits complete

*Section 1 is ready for publication.*

---

## Section 2: Learning to Read Code as Cultural Text

**Status:** 🚧 Multiple drafts requiring rework

- [x] Learning objectives added

### Section 2.a: Source Criticism in the Digital Age

- [ ] **Rethink how source criticism is introduced** - The current approach has methodological problems:

  **The contradiction:** The lesson introduces the traditional external/internal criticism distinction ("The Inheritance of Source Criticism" subsection), then immediately claims this distinction "becomes complicated" and "collapses" in born-digital sources ("The Entanglement Problem" subsection). This is pedagogically confusing—why introduce a framework only to say it doesn't work?
  
  **The replacement problem:** The "layered reading" approach (four layers: technical object, textual artifact, historical trace, archival construction) was AI-generated as a replacement for external/internal criticism. It has no established theoretical basis in:
  - Digital humanities scholarship
  - Critical code studies (Marino 2020 is cited but doesn't use this framework)
  - Digital history/historiography
  - Science and technology studies
  
  **Questions to resolve:**
  1. Should we keep external/internal criticism at all? If yes, show how it *adapts* for digital sources rather than claiming it "collapses." If no, don't introduce it as the starting point.
  2. What should replace the "layered reading" framework?
     - Option A: Ground it theoretically—find actual scholarship that supports this approach
     - Option B: Replace with an established framework from critical code studies
     - Option C: Remove the explicit framework and teach analytical *questions* without claiming a coherent "method"
     - Option D: Acknowledge this is a *proposed* approach, not established methodology
  3. What do existing critical code studies scholars (Marino, Montfort, Berry, Hayles) actually propose as analytical methods?

- [ ] **Remove all references to "layered method/layered reading"** - Locations:
  - Section 2.a "The Layered Reading Approach" subsection
  - Section 2.b GW-BASIC exercise ("Apply the layered reading approach")
  - Section 2.c Apollo case study references
  - Conclusion references to "layered reading approach"

- [ ] **Reword accessibility claim** - Current text overstates what can be understood without programming expertise:
  
  > "Understanding what code does benefits from basic familiarity with programming concepts—not expertise, but enough literacy to recognize structures, follow logic, and understand why certain choices were made."
  
  **Issue:** Recognizing structures, following logic, and understanding technical choices *does* require substantive programming knowledge—more than "basic familiarity."

- [ ] **"The Entanglement Problem" needs theoretical depth** - Current draft needs:
  - Epistemological implications: How does this challenge traditional source criticism?
  - More specific examples of metadata embedding challenges
  - Theoretical frameworks from digital humanities/digital history scholarship
  - How "entanglement" might provide advantages for historical analysis
  - Clearer connection to practical exercises that follow

### Section 2.b: Programming Languages as Historical Markers

- [ ] **Enhance Rosetta Code exercise** - Current version lacks concrete examples and pedagogical scaffolding:
  - Add 2-3 actual code examples (FORTRAN, C, Python side-by-side)
  - Include specific analytical questions (verbosity, syntax, memory constraints)
  - Add expected observations for instructors
  - Consider side-by-side comparison format
  - Clarify what students should conclude about historical context shaping language design

**Resource:** [Rosetta Code Hello World](https://rosettacode.org/wiki/Hello_world/Text) - 300+ programming languages, organized chronologically

### Section 2.c: The Journey of the Apollo Code

**Status:** Draft requiring further development

- [ ] **Rethink the Margaret Hamilton case** - Current "The Human Context" subsection needs:
  - Deeper engagement with gender dynamics in computing history
  - Better integration with code analysis (not just a separate subsection)
  - More primary sources and scholarly framing
  - Clearer pedagogical purpose

- [ ] **Refine the Apollo 11 code reconstruction narrative** - Needs:
  - Stronger connection to preservation/heritagization themes
  - More nuanced discussion of what was lost vs. recovered
  - Better scaffolding for student analysis

- [ ] **Strengthen BURN_BABY_BURN analysis** - Needs:
  - Deeper cultural/historical context
  - Clearer analytical framework application
  - More rigorous exercise design

**Reference integrated:** [BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc](https://github.com/chrislgarry/Apollo-11/blob/master/Luminary099/BURN_BABY_BURN--MASTER_IGNITION_ROUTINE.agc) ✅

**KTH humor research integrated:** [Humor in Software Development](https://www.kth.se/en/eecs/nyheter/humor-en-viktig-ingrediens-i-mjukvaruutveckling-1.1351788) ✅

### Section 2.d: Esoteric Languages

**Status:** ✅ Added in v2

---

## Section 3: Preserving Code: Initiatives and Infrastructures

**Status:** 🚧 Needs accessibility fix and reading suggestions

- [x] Learning objectives added
- [x] Preservation initiatives expanded

- [ ] **French-language source accessibility issue** - Section 3.a references Schafer 2017 (Bulletin 1024) which is not accessible to English-speaking students:
  - Find equivalent English-language resources about Software Heritage's founding vision
  - Add English summaries or translations of key points
  - Ensure all primary sources for student exercises are available in English
  
  *Current status:* Inline note acknowledges the issue but doesn't resolve it.

- [ ] **Add Reading/viewing suggestions** - Section 3 has no reading suggestions section unlike Sections 1 and 2

---

## Conclusion

**Status:** ⚠️ UNREVIEWED AI DRAFT

- [ ] **Full review and revision required:**
  - Human review for accuracy and appropriateness
  - Verification that it accurately reflects lesson content
  - Revision for tone and style consistency
  - Possible restructuring based on final lesson content

---

## Additional Resources (for integration)

### FORTRAN Historical Sources

**Archive:** https://softwarepreservation.computerhistory.org/FORTRAN/

**Recommended citations:**
- J.W. Backus et al. "The FORTRAN Automatic Coding System." Proceedings Western Joint Computer Conference, 1957.
- John W. Backus. "The history of FORTRAN I, II and III." Proceedings First ACM SIGPLAN Conference on History of Programming Languages, 1978.
- Mark Halpern. "On the Heels of the Pioneers." Annals of the History of Computing, 1991.

**Why it matters:** FORTRAN (high-level abstraction) vs. AGC assembly (bare-metal control) illuminates philosophical choices embedded in code.

---

## Summary of Remaining Tasks

### High Priority
- [ ] Rethink source criticism methodology (Section 2.a)
- [ ] Remove all "layered reading" references
- [ ] Review and revise Conclusion (AI draft)
- [ ] Resolve French-language source accessibility (Section 3.a)
- [ ] Add Section 3 Reading/viewing suggestions

### Medium Priority
- [ ] Enhance Rosetta Code exercise with concrete examples (Section 2.b)
- [ ] Develop Margaret Hamilton case study (Section 2.c)
- [ ] Strengthen BURN_BABY_BURN analysis (Section 2.c)
- [ ] Reword accessibility claim (Section 2.a)

### Lower Priority
- [ ] Review image legends for consistency
- [ ] Check for excessive "let's explore" phrasing
- [ ] Review pedagogical scaffolding across all exercises

### Completed ✅
- [x] Learning objectives added to all three sections
- [x] KTH humor research integrated (Section 2.c)
- [x] Section 2.d on esoteric languages added
- [x] Reading/viewing suggestions added (Sections 1 and 2)
- [x] Section 3 preservation initiatives expanded
- [x] BURN_BABY_BURN code header included
- [x] Replaced excessive "let's explore" phrasing
- [x] **Section 1: Understanding Digital Heritage Recognition - COMPLETE**
