# Medical Coding and Narrative Quality — EdVyro Pharmacovigilance Task 03

## Objective
This project demonstrates consistent normalization of product and adverse-event terms, traceable coding decisions, and concise chronological case narratives using only the supplied fictional/de-identified case facts.

## Task requirements addressed
1. Normalize product name, dose, route, indication, and event terms.
2. Map reported event terms to the most appropriate available coding terms.
3. Write neutral chronological narratives using only supplied facts.
4. Provide a quality-control checklist and one public repository as proof.

## Data handling rule
No missing clinical information has been invented. When dose, route, indication, or other details were not supplied, they are recorded as **Not reported** or **Unknown**, as appropriate.

## Coding approach
The event mapping uses the most direct normalized clinical concept supported by the supplied wording:
- Nausea → Nausea
- Loss of consciousness → Loss of consciousness
- Mild rash → Rash
- Appendicitis → Appendicitis

The word **mild** is treated as a descriptive qualifier and is not retained as a separate event concept. No unsupported diagnosis, causality, seriousness criterion, or treatment has been added.

> Note: This is an internship practice project using fictional/de-identified data. It is not a submission to a regulatory authority and does not reproduce any confidential patient information.

## Project files
- `Coding_Worksheet.md` — normalization and coding decisions
- `Case_Narratives.md` — chronological narratives for all four cases
- `Quality_Control_Checklist.md` — final consistency and quality checks
- `Case_Chronology.md` — case-by-case timeline view
- `supporting/narrative-source-cases.csv` — supplied source-case dataset recreated for this project

## Completion summary
All four supplied cases were reviewed. Product, event, onset, outcome, and seriousness information were preserved. Missing dose/route/indication information was not fabricated.
