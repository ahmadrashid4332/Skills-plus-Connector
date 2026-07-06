# Skills Plus Connector — Project Overview

This repository contains the complete development lifecycle of an AI-powered career assistant skill (Autonomous Career Agent / ATS Career Coach), from creation through to portability verification and audit documentation.

## Folder Structure

| Folder | Purpose |
|---|---|
| **task 1 create skill** | Contains the core **ATS Career Coach skill** (`ats-career-coach.skill`) — the AI system prompt that auto-triggers on resume upload. Performs Phase 1 (Resume Audit: formatting, grammar, impact fixes). Includes a screenshot proving the auto-trigger behavior. |
| **task 2 connect-APP** | Defines the full **3-phase agent workflow** — Resume Audit → Indeed Job Search (via Indeed Connector) → Resume Tailoring. Contains the detailed system instructions and 6 screenshots showing the skill's configuration and the API/connector setup. |
| **task 3 skill + connector** | Demonstrates the **end-to-end execution** — live resume upload triggering the auto-audit, interactive preference gathering, live Indeed job search with data fetching, and ATS-friendly resume tailoring. 6 screenshots document the full flow. |
| **task 4 portable handoff** | Validates **portability** by transferring the skill prompt to a second account. Confirms 100% success — the skill auto-triggered and executed identically in the new environment, proving it's not account-locked. 3 screenshots as proof. |
| **task 5 audit report** | A separate **safety assessment report** for a "Canvas-Design" AI skill. Evaluates what the skill does, what system/data it accesses, and concludes it is safe and trustworthy — included as an example of AI skill auditing methodology. |
| **project-overview** | This folder — an index of the repository's structure and the purpose of each task folder. |

Each folder builds on the previous one: **create the skill → connect it to a live data source (Indeed) → execute the full workflow → verify portability across accounts → document an audit report example.**
