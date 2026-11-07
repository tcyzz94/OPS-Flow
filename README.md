# Enterprise Full-Stack & AI-Native Engineering

> A public learning journey: building an enterprise-style application from the ground up, one chapter at a time.

## About this repository

This repository documents my effort to strengthen my software engineering fundamentals while learning how to design, build, test, deploy, and maintain modern full-stack applications with practical AI capabilities.

The goal is not simply to finish an app. It is to **understand the decisions behind it**: how features are designed, how systems fit together, why trade-offs matter, and what it takes to make software reliable in a real business environment.

I am approaching this as a hands-on portfolio project, with an emphasis on **enterprise operations workflows** and engineering practices relevant to senior full-stack roles.

**Project status:** 🚧 Learning and building in public. Features and architecture will evolve as chapters are completed.

## What I'm learning

| Area | Focus |
| --- | --- |
| Frontend engineering | React, TypeScript, responsive UI, accessibility, state management, and performance |
| Backend engineering | API design, validation, error handling, integrations, and service architecture |
| Data and persistence | Relational modelling, PostgreSQL, migrations, queries, and transactions |
| Security | Authentication, authorization, input validation, and secure development practices |
| Software quality | Unit and integration testing, debugging, code reviews, and maintainability |
| Delivery and operations | Docker, CI/CD, environment configuration, logging, and deployment |
| AI-native development | LLM integration, retrieval-augmented generation (RAG), tool use, evaluation, and safety |
| Engineering judgment | Requirements, architecture decisions, trade-offs, documentation, and retrospectives |

## The project

I am building an **enterprise operations application** that will grow incrementally. The aim is to model realistic business problems such as request submission, approvals, task tracking, notifications, document workflows, and knowledge retrieval.

AI features will be introduced only where they solve a meaningful problem—for example, helping users find relevant information from internal documents or assisting with routine operations—rather than adding AI for its own sake.

This is a **learning project**, not a production service. The eventual feature set and stack may change as I validate requirements and gain experience.

## Learning roadmap

The repository is organized into chapters. Each chapter includes implementation work, notes, and a review checkpoint.

| Chapter | Theme | Status |
| --- | --- | --- |
| 01 | Problem definition, requirements, and project setup | ⬜ Planned |
| 02 | Frontend foundations and accessible UI | ⬜ Planned |
| 03 | Backend services and REST APIs | ⬜ Planned |
| 04 | Database design and end-to-end workflows | ⬜ Planned |
| 05 | Authentication, authorization, and security | ⬜ Planned |
| 06 | Testing, observability, and deployment | ⬜ Planned |
| 07 | Practical AI features and integrations | ⬜ Planned |
| 08 | Hardening, documentation, and portfolio demo | ⬜ Planned |

*The chapter sequence is a working plan, not a claim that these features have been implemented.*

## How I learn and build

**Every implementation is written by hand.** I use AI tools, including Codex, at defined checkpoints to **review** my work—not to generate the solution for me.

My process for each chapter:

1. Understand the problem and define the expected behavior.
2. Design a small, testable solution and document key decisions.
3. Implement the code myself.
4. Write tests and verify the behavior.
5. Request a Codex review for correctness, security, readability, and maintainability.
6. Evaluate the feedback, make changes manually, and document what I learned.

The intention is to develop independent problem-solving ability, not just produce working code.

## What visitors can expect

As the project progresses, this repository will include:

- Source code with meaningful commit history.
- Chapter notes explaining concepts and trade-offs.
- Architecture diagrams and architecture decision records (ADRs), where useful.
- Tests and reproducible setup instructions.
- Review checkpoints, issues found, and improvements made.
- Screenshots or a live demo once there is something working to show.

## Technology choices

The initial direction is **React + TypeScript** for the frontend, a **TypeScript-based backend**, and **PostgreSQL** for relational data. I plan to use **Docker** and a CI/CD workflow as the project matures. AI features will be integrated through appropriate model APIs when their chapter begins.

Dependencies and architectural decisions will be documented as they are adopted, rather than treated as fixed from day one.

## Current milestone

**Week 1 — Define the problem and establish the foundation.**

The [product brief](Week%201/product%20brief.md) limits the first version to purchase-request approval, inventory tracking, and expiry warnings. Purchase order creation, invoice approval, and payment processing are excluded. These features remain planned. The Week 1 Day 01 review found that the brief still needs explicit role responsibilities and three use cases. **Next:** finish those items and resolve the brief's placeholders before moving to Day 02 workflow rules.

### Progress updates

- **2026-11-07 — Week 1: Day 01 brief reviewed against the workbook.** Problem framing and an out-of-scope list are present; role definitions and three explicit use cases remain incomplete. Chapter 01 remains planned pending implementation. **Next:** complete the Day 01 brief, then document workflow rules.

## Why this repository is public

I want this portfolio to show **how I think and improve as an engineer**, not just the final application. The code, decisions, mistakes, reviews, and iterations are all part of the learning record.

If you're reviewing this as an engineer or hiring manager, I hope the repository makes my approach to software design, implementation, and continuous learning easy to follow.

---

**Note:** This repository is an educational portfolio project. Any sample business data should be fictional or anonymized; no confidential employer information is intended to be included.
