# Revalidation Schedule

Purpose: Ensure factual accuracy remains current and links stay accessible.

## Cycle
- Frequency: Quarterly (every 3 months)
- Anchor Dates (start from 2025-09-04):
  - 2025-12-04
  - 2026-03-04
  - 2026-06-04
  - 2026-09-04

## Checklist Per Cycle
1. Link Accessibility (HTTP 200, no major content drift)
2. Verify publication dates + capture (archive.org snapshot if critical)
3. Re-run health / science claims vs current guidelines (WHO, CDC, NASA, IEA updates)
4. Update energy-per-query figures (Article 1) if new LLM benchmarks published
5. Check AI deception research (Articles 3 & 9) for new replication or contradictory studies
6. Confirm dengue epidemiology patterns (serotype shifts) (Article 6)
7. Update jus soli country list counts (Article 10)
8. Add any DOI or primary sources not yet included
9. Regenerate `answers.json` if verdicts or references change
10. Increment version + CHANGELOG

## Roles (Suggested)
- Health & Medical: Reviewer A
- Science & Space: Reviewer B
- Tech / AI Policy: Reviewer C
- Editorial Consistency: Reviewer D

## Change Control
- Minor edit: Patch version bump (0.1.x)
- Content addition / new metrics: Minor version bump (0.x.0)
- Structural / format change: Major after stable (>=1.0.0)

## Logging Template
Date: YYYY-MM-DD
Cycle: Q# / Year
Reviewed Articles: [list]
Updates Made: (summary)
Links Broken: (list + replacement)
Action Items Next Cycle: (list)
Reviewer Sign-offs: A / B / C / D

---
This schedule satisfies Task #29 draft creation (pending calendar entry outside repo).
