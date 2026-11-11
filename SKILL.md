---
name: responsible-vibe-coding
description: Apply The Vibe-Code of Ethics to build, modify, review, test, or prepare educational software for release with AI coding agents. Use when users request responsible or ethical vibe coding, student-facing learning apps, classroom prototypes, or security and maintainability review of educator-built tools. Cover pedagogy, privacy, security, accessibility, dignity, human oversight, evidence, and maintenance; distinguish a prototype from school approval.
---
# Responsible Vibe Coding

Created by Barbara Anna Zielonka, based on *The Vibe-Code of Ethics*.

Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See `LICENSE.md` for scope and attribution.

Use this operational adaptation of Barbara Anna Zielonka’s *The Vibe-Code of Ethics*. Read `references/framework.md` when interpreting its principles; use `references/review.md` for the evidence record and release checks. Treat the source as a professional framework, not a security certificate or current legal authority. Version: 0.1.1, adapted 2026-11-11.

## 1. Establish purpose and proportionate scope
- State the learning objective, audience and age range, learning activity, and how the teacher stays in control. Explain the benefit compared with a non-digital alternative.
- Infer reversible prototype choices and label assumptions; ask only for missing decisions that change learning suitability, sensitive processing or release authority. Continue useful independent work.
- Use fictional data throughout development. Never request real student records, assignments containing identifiers, disability details, credentials or confidential school documents for testing.
- Classify practical risk by actual processing and consequences, not appearance: lower for static practice without saved answers; moderate for accounts or saved progress; higher for student-input AI, records or tracking; very high for consequential educational decisions. This is not a legal taxonomy. Reclassify when features change.

## 2. Choose the smallest responsible architecture
- Prefer no accounts, analytics, persistent answers or live AI when the objective does not need them. Separate AI-assisted development from AI operating inside the finished app.
- Map every data flow: input → processing → storage → external recipient → retention/deletion. Include hosting logs and identifiers even without login. Do not claim “no data collection” from frontend inspection alone.
- Document dependencies, external scripts/fonts, integrations, permissions, recurring costs and failure paths. Prefer simple, readable modules and minimal dependencies; pin and review needed packages and preserve lockfiles.
- For accounts, databases or external AI, examine real configurations, server authorisation, provider policies and deletion arrangements. Keep unresolved issues explicit. Seek appropriate specialist/school review before student deployment; proceed with a fictional-data prototype where feasible.

## 3. Build learning, dignity and accessibility into behavior
- Require retrieval, explanation or application; offer scaffolding, hints, revision and learner choice. Make feedback specific and kind. Avoid timers, public rankings, shaming, unsupported ability labels or manipulative engagement.
- Keep formative practice distinct from grading. Accept reasonable answer variants or explain matching limits and offer a way to discuss alternatives with a teacher. Do not automate consequential grades, progression or opportunities.
- Use semantic controls, programmatic labels, keyboard operation, visible focus, adequate contrast, text resizing, responsive layouts, understandable error states, and reduced-motion support where animation exists. Do not rely on colour, audio or pointer gestures alone. Target WCAG 2.2 AA without claiming conformance from an automated scan.
- Check examples for stereotypes, cultural assumptions and exclusion. Offer an equivalent non-digital route. State content provenance and human-review status honestly.

## 4. Implement security and maintainability
- Never embed credentials in browser code, screenshots, logs, fixtures or repositories. Use server-side secret storage when needed; if exposed, remove and rotate through authorised processes.
- Treat user text, uploads, retrieved content and model output as untrusted data. Render plain text safely; avoid unsafe HTML insertion, executable strings and dynamic code execution. Validate type, size and content at each trust boundary, including the server when present.
- Enforce authentication and record-level authorisation on the server; test cross-user reads, writes and deletes. Hidden UI is not access control. A prompt is not a security boundary.
- Limit AI tools and permissions; prevent untrusted content from authorising actions. Add abuse/cost limits, failure handling, inappropriate-output reporting and human review for consequential operations.
- Keep content separate from logic where practical. Use clear names, small functions, explicit state, useful comments and reproducible run/test instructions. Test important behavior and failure modes, not implementation trivia.
- Check content/code licences and attribution. Do not invent licensing permission for a supplied framework; keep publication licensing an explicit author decision.

## 5. Verify and record evidence
- Review source and configuration, then execute applicable functional, adversarial-input, accessibility and responsive checks. Test retry/reset, empty and long inputs, special characters, valid alternatives, repeated actions, and storage/network behavior where relevant.
- Inspect dependencies and secret exposure; test authorisation and injection if those boundaries exist. Use current authoritative documentation for changing security or legal claims. Never fabricate passing tests or imply a scan proves safety.
- Read `references/review.md` and write a concise project record mapping the framework's gates A–G to evidence. Use PASS, FAIL, NOT TESTED or NOT APPLICABLE with a reason. Separate observed results from design intent.
- Include pedagogical review, diverse fictional scenarios, and remaining real-user/screen-reader checks. Automated checks do not replace human review.

## 6. Release and hand over in stages
- Distinguish: fictional-data prototype → technical review → teacher review → authorised supervised pilot → deployment → ongoing review. A private adult preview is not school approval.
- Respect the user's release boundary. Prepare a reviewable result and tests before seeking any still-required publication decision. Do not publish publicly when the user wants to test first.
- For student use, record the relevant school authority's approval, privacy review, maintainer and unresolved issues. Never claim GDPR compliance, certification or school approval without established evidence. Verify current jurisdiction-specific obligations with authoritative sources and responsible specialists.
- Provide purpose, age range, version/date, data/AI notice, limitations, report route, maintenance owner/status, and handover instructions. Explain them plainly to non-programmers.
- Include failure and retirement plans: switch to an offline activity; disable affected functionality; preserve necessary evidence without spreading personal data; contact responsible school/IT/privacy staff; let the responsible organisation assess reporting obligations; fix and review before restart. Describe export/deletion and safe shutdown where data exists.
- Finish with what was built, tests actually run, remaining gates, and the next small action for the user. Never present this skill as enforcement, a substitute for technical review, or a guarantee that another agent will follow it.
