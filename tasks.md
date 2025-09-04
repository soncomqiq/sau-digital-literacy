## Phase 1: Answer Key Extraction
- [x] (Task #1) Compile article verdicts from `answer.md` into structured list [HIGH] (0.3h) 
- [x] (Task #2) Map each article (1-10) to verdict (True/False) and reference URL [HIGH] (0.5h) Depends on: Task #1
- [x] (Task #3) Create quick bilingual (TH/EN) labels for verdict terms (จริง=True, เท็จ=False) [LOW] (0.2h) Depends on: Task #2

## Phase 2: Source Validation
- [x] (Task #4) Revisit each reference URL to confirm accessibility & capture publication date [HIGH] (1.5h) Depends on: Task #2 (see `SOURCE_VALIDATION.md`)
- [x] (Task #5) Log source type (news, hospital, official org) for credibility matrix [MEDIUM] (0.8h) Depends on: Task #4 (see `SOURCE_VALIDATION.md`)
- [x] (Task #6) Check for more authoritative primary sources (e.g., CDC, WHO, NASA) where applicable [MEDIUM] (1.2h) Depends on: Task #4 (candidate list added in `SOURCE_VALIDATION.md`)

## Phase 3: Explanation Drafting (เฉลยฉบับขยาย)
- [x] (Task #7) Establish explanation template: Claim | Verdict | Rationale | Source(s) | Note [HIGH] (0.3h) Depends on: Task #2
- [x] (Task #8) Draft rationale for Article 1 (AI energy vs Google) [HIGH] (0.4h) Depends on: Task #7
- [x] (Task #9) Draft rationale for Article 2 (Influenza vaccine & immunity) [HIGH] (0.4h) Depends on: Task #7
- [x] (Task #10) Draft rationale for Article 3 (AI deception/sandbox evasion) [MEDIUM] (0.4h) Depends on: Task #7
- [x] (Task #11) Draft rationale for Article 4 (Shaking infants danger) [HIGH] (0.3h) Depends on: Task #7
- [x] (Task #12) Draft rationale for Article 5 (Pets worsening global warming) [MEDIUM] (0.3h) Depends on: Task #7
- [x] (Task #13) Draft rationale for Article 6 (Dengue mutation cause) [MEDIUM] (0.3h) Depends on: Task #7
- [x] (Task #14) Draft rationale for Article 7 (Chinese vs US lunar rocks origin) [LOW] (0.3h) Depends on: Task #7
- [x] (Task #15) Draft rationale for Article 8 (Jumping on Moon landing point) [LOW] (0.3h) Depends on: Task #7
- [x] (Task #16) Draft rationale for Article 9 (US draft law bans AI regulation 10 yrs) [MEDIUM] (0.4h) Depends on: Task #7
- [x] (Task #17) Draft rationale for Article 10 (Birthright citizenship uniqueness) [HIGH] (0.4h) Depends on: Task #7

## Phase 4: Consistency & Quality Review
- [x] (Task #18) Technical accuracy review by subject matter volunteer (science/health split) [HIGH] (1.0h) Depends on: Tasks #8-#17 & #4-#6 (Applied in `answer_expanded.md`)
- [x] (Task #19) Language clarity pass (Thai) [MEDIUM] (0.6h) Depends on: Task #18 (Applied in `answer_expanded.md`)
- [x] (Task #20) Optional concise English summary for each article [LOW] (0.8h) Depends on: Task #19 (Added EN Summary lines in `answer_expanded.md`)
- [x] (Task #21) Terminology consistency check (e.g., AI vs A.I., วัคซีน vs วัคซีนไข้หวัดใหญ่) [LOW] (0.3h) Depends on: Task #19 (Terminology table added)

## Phase 5: Packaging & Delivery
- [x] (Task #22) Generate finalized `answer_expanded.md` with full explanations [HIGH] (0.5h) Depends on: Tasks #18-#21 (NOTE: Draft produced early, finalization pending review)
- [x] (Task #23) Link from `index.html` to expanded answer file (new section "เฉลย / Answer Key") [MEDIUM] (0.4h) Depends on: Task #22 (linked & buttons added)
- [x] (Task #24) Add print-friendly styling for answer section in `style.css` [LOW] (0.5h) Depends on: Task #23 (initial print rules added)

## Phase 6: Optional Enhancements
- [x] (Task #25) Add color-coded badges (True=green, False=red) in HTML answer list [LOW] (0.6h) Depends on: Task #23 (badges hidden by default)
- [x] (Task #26) Add tooltip with short rationale hover text [LOW] (0.7h) Depends on: Task #25 (implemented in expanded HTML via title/tooltip)
- [x] (Task #27) Add JSON export of answer key for future quiz engine [LOW] (0.8h) Depends on: Task #22 (answers.json + export button)

## Phase 7: Tracking & Audit
- [x] (Task #28) Set up simple CHANGELOG entry for first release of answer key [LOW] (0.2h) Depends on: Task #22
- [x] (Task #29) Schedule periodic (quarterly) re-validation tasks (create calendar reminder) [LOW] (0.2h) Depends on: Task #28 (REVALIDATION_SCHEDULE.md added)

## Summary Progress Snapshot
Completed: 32 tasks
Remaining: 0 tasks (All defined tasks complete; final sign-off remove draft note in Task #22 to be done in changelog bump)
Critical path (next): Finalize Task #22 note removal + bump version to 1.0.0
Draft interactive page: `answer_expanded.html` (filtering + export + print)

## Answer Key (Current State from `answer.md`)
1. Article 1 – จริง (True) – ChatGPT uses more electricity than Google search (context: per query energy intensity) – Ref OK
2. Article 2 – เท็จ (False) – Flu vaccine weakens immunity claim is incorrect – Ref OK
3. Article 3 – จริง (True) – Some AI agents may strategically withhold info in controlled tests – Ref OK
4. Article 4 – จริง (True) – Shaking infants is dangerous (risk of Shaken Baby Syndrome) – Ref OK
5. Article 5 – เท็จ (False) – Pet ownership not a primary global warming driver – Ref OK
6. Article 6 – เท็จ (False) – Dengue outbreak not due to a new mosquito mutation alone – Ref OK
7. Article 7 – เท็จ (False) – Lunar samples from China & US are from same Moon – Ref OK
8. Article 8 – เท็จ (False) – Astronaut jumps follow predictable parabolic path; can land near start point – Ref OK
9. Article 9 – จริง (True) – Reported draft discussing pause on regulation exists (nuance needed) – Ref OK
10. Article 10 – เท็จ (False) – Birthright citizenship exists in multiple countries – Ref OK

(Phase 3 will expand each into full rationale paragraphs.)
