# GitHub Profile README Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create and publish the `Restodecoca/Restodecoca` GitHub profile README.

**Architecture:** This is a documentation-only repository. The root `README.md` is the rendered GitHub profile, while design and planning documents live under `docs/superpowers/` and do not affect profile rendering.

**Tech Stack:** Markdown, Git, GitHub CLI, GitHub profile README conventions, Shields.io badges, GitHub stats cards.

---

## File Structure

- Create: `README.md`
  - Responsibility: Render the public GitHub profile content.
- Already exists: `docs/superpowers/specs/2026-05-17-github-profile-design.md`
  - Responsibility: Record the approved design and constraints.
- Create: `docs/superpowers/plans/2026-05-17-github-profile.md`
  - Responsibility: Track this implementation plan.

## Tasks

### Task 1: Create Root Profile README

**Files:**
- Create: `README.md`
- Modify: none
- Test: `git diff --check -- README.md`

- [ ] **Step 1: Create the README content**

Add this exact content to `README.md`:

```markdown
<h1 align="center">Gabriel Silva Rodrigues</h1>

<p align="center">
  <strong>AI/ML Researcher & Software Engineer</strong><br />
  Building applied AI systems, data-driven tools, and full-stack side projects.
</p>

<p align="center">
  <a href="https://github.com/Restodecoca"><img src="https://img.shields.io/badge/GitHub-Restodecoca-181717?style=flat&logo=github" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/gabriel-s-r/"><img src="https://img.shields.io/badge/LinkedIn-gabriel--s--r-0A66C2?style=flat&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:gabriel.00001156@Hotmail.com"><img src="https://img.shields.io/badge/Email-gabriel.00001156%40Hotmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I am a Systems student at **UNIFESSPA**, currently in the 7th semester, and a researcher at **AKCIT-CEIA** through **UFG**. My work sits between applied AI research and software engineering: I experiment with models, build retrieval and data workflows, and turn ideas into usable systems.

Most of my day-to-day work is around **AI/ML**, **LLMs/RAG**, datasets, dashboards, backend services, and automation. I also keep side projects in **TypeScript** and **Java**, because I like building things end-to-end instead of stopping at notebooks or prototypes.

## What I Work On

- **AI/ML systems:** experiments, model evaluation, data preparation, fine-tuning workflows, and practical ML applications.
- **LLMs and retrieval:** RAG pipelines, embeddings, document understanding, agents, and applied generative AI.
- **Data-heavy applications:** dashboards, SQL workflows, analysis pipelines, and tools that make data easier to inspect and use.
- **Software engineering:** APIs, backend services, full-stack projects, Dockerized environments, and maintainable project structure.
- **Research to product:** transforming research questions into reproducible experiments and useful software artifacts.

## Research & Engineering Focus

I am especially interested in applied AI that can survive contact with real-world data: noisy documents, incomplete datasets, domain constraints, and users who need reliable outputs. My current focus is on combining research discipline with engineering execution, especially in projects involving machine learning, LLMs, retrieval systems, and information extraction.

## Tech Stack

| Area | Tools and topics |
| --- | --- |
| AI / ML | Python, machine learning, model evaluation, fine-tuning, notebooks, data preprocessing |
| LLMs / RAG | Retrieval-augmented generation, embeddings, vector search, agents, prompt engineering |
| Data | SQL, PLSQL, data analysis, dashboards, reporting, structured datasets |
| Backend | Java, Python services, APIs, integrations, automation |
| Web / Side Projects | TypeScript, JavaScript, full-stack applications, UI-driven tools |
| Infrastructure | Docker, Git, reproducible environments, local development workflows |

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git" />
</p>

## Selected Directions

- Applied AI research at **AKCIT-CEIA / UFG**.
- Systems and academic work at **UNIFESSPA**.
- LLM/RAG experiments for document understanding, search, and structured generation.
- Dashboards and data workflows for analysis-heavy contexts.
- TypeScript and Java side projects focused on learning, shipping, and improving engineering range.

## GitHub Snapshot

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Restodecoca&show_icons=true&hide_title=true&hide_rank=false&theme=github_dark&include_all_commits=true" alt="Gabriel's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Restodecoca&layout=compact&theme=github_dark&hide_title=true" alt="Top languages" />
</p>

## Contact

- GitHub: [@Restodecoca](https://github.com/Restodecoca)
- LinkedIn: [gabriel-s-r](https://www.linkedin.com/in/gabriel-s-r/)
- Email: [gabriel.00001156@Hotmail.com](mailto:gabriel.00001156@Hotmail.com)
```

- [ ] **Step 2: Run local whitespace validation**

Run:

```powershell
git diff --check -- README.md
```

Expected output: no output and exit code `0`.

- [ ] **Step 3: Inspect README diff**

Run:

```powershell
git diff -- README.md
```

Expected output: a diff showing only the new `README.md` content from Step 1.

- [ ] **Step 4: Commit the README**

Run:

```powershell
git status --short
git add README.md
git commit -m "Add GitHub profile README"
```

Expected output: `README.md` is committed with message `Add GitHub profile README`.

### Task 2: Commit the Implementation Plan

**Files:**
- Create: `docs/superpowers/plans/2026-05-17-github-profile.md`
- Test: `git diff --check -- docs/superpowers/plans/2026-05-17-github-profile.md`

- [ ] **Step 1: Validate plan formatting**

Run:

```powershell
git diff --check -- docs/superpowers/plans/2026-05-17-github-profile.md
```

Expected output: no output and exit code `0`.

- [ ] **Step 2: Commit the plan file**

Run:

```powershell
git status --short
git add docs/superpowers/plans/2026-05-17-github-profile.md
git commit -m "Add GitHub profile implementation plan"
```

Expected output: the plan file is committed with message `Add GitHub profile implementation plan`.

### Task 3: Create Public GitHub Profile Repository

**Files:**
- Modify: local git remote configuration through `gh repo create`
- Test: `gh repo view Restodecoca/Restodecoca --json isPrivate,url,defaultBranchRef`

- [ ] **Step 1: Confirm the repository does not exist yet**

Run:

```powershell
gh repo view Restodecoca/Restodecoca --json url
```

Expected output: GitHub CLI reports that the repository cannot be resolved.

- [ ] **Step 2: Create the public profile repository and push current branch**

Run from `C:\Users\Gabriel Silva\Desktop\Restodecoca`:

```powershell
gh repo create Restodecoca/Restodecoca --public --source . --remote origin --push
```

Expected output: GitHub CLI creates `https://github.com/Restodecoca/Restodecoca`, adds `origin`, and pushes the local commits.

- [ ] **Step 3: Verify repository visibility and default branch**

Run:

```powershell
gh repo view Restodecoca/Restodecoca --json isPrivate,url,defaultBranchRef --jq '{url:.url,isPrivate:.isPrivate,defaultBranch:.defaultBranchRef.name}'
```

Expected output:

```json
{"defaultBranch":"master","isPrivate":false,"url":"https://github.com/Restodecoca/Restodecoca"}
```

### Task 4: Verify Published Profile

**Files:**
- Modify: none
- Test: GitHub API and public profile page checks

- [ ] **Step 1: Verify GitHub can read the root README**

Run:

```powershell
gh api repos/Restodecoca/Restodecoca/readme --jq .name
```

Expected output:

```text
README.md
```

- [ ] **Step 2: Verify the public profile page responds**

Run:

```powershell
(Invoke-WebRequest -UseBasicParsing -Uri "https://github.com/Restodecoca").StatusCode
```

Expected output:

```text
200
```

- [ ] **Step 3: Verify the pushed file contains the key positioning**

Run:

```powershell
gh api repos/Restodecoca/Restodecoca/contents/README.md --jq .content
```

Expected output: base64 content is returned for `README.md`. Decode is not required for this check because Step 1 confirms the root README exists and Step 2 confirms the profile page responds.

- [ ] **Step 4: Final status check**

Run:

```powershell
git status --short
git log --oneline -5
```

Expected output: `git status --short` has no output, and `git log --oneline -5` shows the README, plan, and spec commits.

## Self-Review

- Spec coverage: the plan creates the root README, preserves the approved research engineer positioning, includes contact links, uses clean technical formatting, creates the public profile repo, and verifies publication.
- Placeholder scan: the plan contains concrete paths, commands, commit messages, and README content.
- Consistency check: all paths use the local repository `C:\Users\Gabriel Silva\Desktop\Restodecoca`, and all GitHub references use `Restodecoca/Restodecoca`.
