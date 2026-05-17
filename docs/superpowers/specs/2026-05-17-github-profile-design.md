# GitHub Profile README Design

Date: 2026-05-17
Target repository: `Restodecoca/Restodecoca`
Primary language: English

## Goal

Create and publish a GitHub profile README that presents Gabriel Silva Rodrigues as an AI/ML researcher and software engineer with strong practical engineering output. The profile should feel professional, technical, and current without becoming visually noisy.

## Audience

The README should serve a balanced audience:

- Technical recruiters and hiring teams looking for AI/ML, LLM/RAG, data, backend, and full-stack engineering experience.
- Research collaborators or academic readers interested in UNIFESSPA, AKCIT-CEIA, UFG, and applied AI work.
- Developers evaluating public projects, side projects, and open-source activity.

## Positioning

Use the primary positioning: `AI/ML Researcher & Software Engineer`.

The intro should connect three parts of Gabriel's profile:

- Systems student at UNIFESSPA, currently in the 7th semester.
- Researcher at AKCIT-CEIA through UFG.
- Builder of practical AI/ML systems and side projects using Python, TypeScript, Java, SQL, and Docker.

The tone should be confident and direct. It should avoid sounding generic, inflated, or purely academic.

## Content Architecture

The README will use these sections in order:

1. Hero intro: name, headline, one concise paragraph, and contact badges.
2. `What I work on`: bullets for AI/ML, LLM/RAG, data systems, full-stack products, and backend systems.
3. `Research & Engineering Focus`: short explanation of applied research, model experimentation, retrieval systems, datasets, dashboards, and production-minded software.
4. `Tech Stack`: grouped by domain rather than a long unstructured badge wall.
5. `Selected directions`: representative project areas, including non-sensitive institutional work and public side projects.
6. `GitHub snapshot`: moderate stats cards that support the profile without dominating it.
7. `Contact`: GitHub, LinkedIn, and public email.

## Visual Style

Use a clean professional style with technical density:

- Minimal but useful badges.
- Clear section headings.
- No excessive animations.
- No large decorative banners unless the user requests one later.
- GitHub stats may be included, but should not be the main proof of quality.

## Public Information Rules

The README may mention:

- UNIFESSPA.
- AKCIT-CEIA.
- UFG.
- Broad project themes and non-sensitive project names.
- Public GitHub repositories.
- Non-sensitive private/institutional work at a high level.

The README must avoid:

- Sensitive project details.
- Private client data.
- Internal credentials, URLs, datasets, or operational specifics.
- Claims that cannot be supported by the user's provided context or visible work.

## Contact Links

Use:

- GitHub: `https://github.com/Restodecoca`
- LinkedIn: `https://www.linkedin.com/in/gabriel-s-r/`
- Email: `mailto:gabriel.00001156@Hotmail.com`

## Implementation Notes

The implementation should create the special public GitHub profile repository `Restodecoca/Restodecoca` if it does not exist, add a root `README.md`, commit it, and push it.

The repository can keep this spec under `docs/superpowers/specs/` without affecting the rendered profile because GitHub uses the root README for the profile page.

## Verification

Before considering the work complete, verify:

- The repository exists and is public.
- The root `README.md` renders correctly as Markdown.
- GitHub, LinkedIn, and email links work.
- The profile page at `https://github.com/Restodecoca` shows the new README.
- The text reflects AI/ML research, software engineering, UNIFESSPA, AKCIT-CEIA/UFG, and side projects without exposing sensitive information.

## Self-Review

- No placeholders remain.
- Scope is focused on a single GitHub profile README.
- The design uses the approved `Research Engineer` direction.
- The visual style matches the approved clean professional plus technical dense blend.
- Confidentiality constraints are explicit.
