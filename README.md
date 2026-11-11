# Responsible Vibe Coding

**Created by Barbara Anna Zielonka, based on *The Vibe-Code of Ethics*.**

A practical skill for AI coding agents that helps educators turn ethical principles into development decisions, checks and evidence.

Teachers increasingly build their own learning tools with AI. A working app, however, is only the beginning. Responsible Vibe Coding asks the coding agent to consider learning purpose, student privacy, security, accessibility, dignity, human oversight and long-term maintenance throughout the work.

**Version:** 0.1.1 · **Status:** early release with initial testing · **Licence:** CC BY 4.0

## What is a skill?

A skill is a reusable set of instructions and supporting materials that an AI agent can read while working. This one translates an educator's ethics framework into a practical workflow for building and reviewing educational software.

It does not run a security scanner, enforce compliance or guarantee that an agent will follow every instruction. It makes responsible choices and missing evidence explicit so a human can review them.

## Who is it for?

- Educators building learning apps, games, simulations or classroom websites with AI assistance.
- Developers collaborating with teachers on educational tools.
- Teams reviewing prototypes before student use or public release.

Its school-governance context draws on Norway. Users elsewhere should adapt the institutional and jurisdiction-specific checks. Legal references in the source framework must be checked for current applicability.

## What it asks the agent to do

| Area | Expected behaviour |
|---|---|
| Learning purpose | Define a learning objective and explain why the tool helps. |
| Privacy | Minimise data, use fictional examples, and map where information goes. |
| Security | Review inputs, secrets, dependencies and access controls where applicable. |
| Inclusion | Design for accessibility, different learners and alternatives to digital participation. |
| Dignity and assessment | Give constructive feedback; avoid humiliating rankings and independent consequential AI decisions. |
| Transparency | Explain runtime AI, data handling, limitations and human-review status. |
| Testing and maintenance | Record actual evidence, unresolved issues, ownership, incident response and retirement plans. |

The agent should distinguish a prototype from an authorised school pilot or deployment. It should report checks as PASS, FAIL, NOT TESTED or NOT APPLICABLE, with reasons and evidence.

## Use it with a coding agent

### If your agent supports skills

Download the complete `responsible-vibe-coding` folder and use your agent's supported skill-installation process. Keep its files and subfolders together. Installation paths and activation methods depend on the product; this repository does not claim universal compatibility.

### If your agent can read project files

Place the complete folder in your project and ask the agent to read `responsible-vibe-coding/SKILL.md` before starting. If your tool only accepts attachments, supply that file and both reference files together. Merely providing a GitHub link does not guarantee that the agent has read the skill.

Start with this prompt:

> Read responsible-vibe-coding/SKILL.md and follow its workflow to help me build an educational tool. My intended learners are [age group], and the learning objective is [objective]. Use fictional data. Explain your design choices in plain language, run appropriate checks, and report the evidence and remaining readiness gates. Keep the result private for my review before public release or student use.

For an existing project:

> Use Responsible Vibe Coding to review this educational app. Inspect the implementation and configuration available to you. Separate observed evidence from assumptions, explain important issues in plain language, and propose proportionate fixes. Do not claim that unperformed tests passed.

Use only fictional, non-identifying material in development conversations. Do not upload student records, credentials or confidential school information.

## Files included

| File | Purpose |
|---|---|
| `responsible-vibe-coding/SKILL.md` | The agent's main workflow. |
| `responsible-vibe-coding/references/framework.md` | Transcription of the source ethics framework. |
| `responsible-vibe-coding/references/review.md` | Instructions for recording evidence against readiness gates A–G. |
| `responsible-vibe-coding/agents/openai.yaml` | Metadata used by compatible agent products. |
| `responsible-vibe-coding/assets/icon.svg` | Display icon for compatible products. |
| `responsible-vibe-coding/LICENSE.md` | Licence scope, attribution and legal-terms links. |
| `LICENSE.md` | Licence notice at repository level. |

This release contains the skill and its documentation only. No example application is included.

## Testing completed and its limits

Initial testing was conducted on 11 November 2026:

- The skill passed its structural validator.
- It was applied while building a small vocabulary prototype. Four automated app tests passed, and browser checks covered core practice interactions. These test the example app, not every instruction in this skill.
- Barbara completed an initial hands-on app review and reported that everything worked fine. This is usability feedback, not a formal audit.
- In one separate-agent scenario, the agent was asked for saved progress, a public weakest-student leaderboard and AI-controlled access to advanced English. It proposed private learning goals, removed public ranking and automated admission, and identified review requirements for saved records.

These are early findings, not a controlled comparison with an unassisted agent or evidence of universal reliability. Account systems, databases, live-AI processing, comprehensive accessibility and broad adversarial behaviour have not been validated by these tests. Version 0.1.1 adds attribution and licensing without changing the substantive workflow.

## Limits and responsibility

This is a development aid, not legal advice, security certification, accessibility certification or school approval. Human content review, qualified technical review where appropriate, and the relevant institutional decisions remain necessary. Check current requirements and provider policies before deploying a tool with students.

The instructions were adapted with AI assistance from Barbara Anna Zielonka's framework. Feedback and corrections can help improve future versions.

## Contributing

When Issues or pull requests are enabled, suggest a specific improvement, explain which principle it supports, and include a fictional example or reproducible test where useful. Distinguish proposed changes from verified findings. Do not post student data, credentials or exploit details that expose an active system in public reports. No response-time or ongoing support commitment is implied.

## Attribution and licence

Copyright © 2026 Barbara Anna Zielonka. The original skill materials and this repository introduction are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE.md](LICENSE.md) for the scope and [legal terms](https://creativecommons.org/licenses/by/4.0/legalcode.en). Linked third-party resources retain their own terms.

Suggested attribution:

> Responsible Vibe Coding — Created by Barbara Anna Zielonka, based on The Vibe-Code of Ethics. Licensed under CC BY 4.0: https://creativecommons.org/licenses/by/4.0/.

Include a link to the material where reasonably practicable and identify any modifications. Credit does not imply endorsement.
