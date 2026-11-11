# Evidence and release record

For each project, record version/date, audience, learning objective, practical risk and why, lifecycle stage, responsible owner (or unassigned), and whether AI runs in the product.

## Evidence gates
| Gate | Required evidence |
|---|---|
| A — Pedagogy | Objective, retrieval/application, constructive feedback, age suitability, teacher review, non-digital alternative |
| B — Privacy | Actual data flow including hosting; minimisation; storage/retention/deletion; provider review and school privacy decisions where applicable |
| C — Security | Code/configuration review; secrets/dependencies; input handling; real authorisation and misuse tests if applicable; incident response |
| D — AI responsibility | Development vs runtime AI; content checks; limitations; tool permissions/injection/cost controls if applicable; human decisions |
| E — Inclusion | Keyboard/focus, contrast, labels, zoom/mobile, assistive-technology/user tests, diverse examples and alternatives |
| F — Assessment and rights | Formative-only limits; reasonable variants; no profiling/rankings; feedback challenge/report route; human oversight |
| G — Deployment and maintenance | Executed tests; documentation; relevant approval; maintainer; updates/costs; fallback, incident and retirement plan; licences |

For every gate, mark individual checks PASS / FAIL / NOT TESTED / NOT APPLICABLE, attach the command, observation or artifact and a reason, and record unresolved actions. Do not give an overall “approved” verdict when a required check is missing. A local-only prototype may be ready for adult testing while remaining unapproved for school use.

## Minimum handover
- Explain how to run it and repeat meaningful tests without assuming coding knowledge.
- Describe editable content and how to recover from mistakes.
- State exactly where entered information goes and when it disappears; distinguish app behavior from host/platform logging.
- Name third-party assets and licences or state that permission is unresolved.
- Provide a reporting route suitable for the prototype; never invent a contact address.
- Assign maintenance, school approval, licensing and release decisions to real people, or mark them unassigned.
- Re-review after data/AI/account changes and before any student pilot; schedule ongoing review only when requested.

## Attribution and licence
Created by Barbara Anna Zielonka, based on *The Vibe-Code of Ethics*. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); see `../LICENSE.md`.
