---
id: 1
title: Create Project Constitution
stage: constitution
date: 2025-12-31
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: master
user: unknown
command: /sp.constitution You are acting as a senior software architect using an Agentic Dev Stack.

Create a CONSTITUTION.md file for a project titled:
"Phase I: In-Memory Todo Console Application"

The constitution must define the governing principles, rules, and constraints of the project.

Project requirements:
- Console-based todo application
- Python 3.13+
- UV for environment management
- Claude Code for all implementation
- Spec-Kit Plus for specification-driven development
- In-memory task storage only (no persistence)

Mandatory rules to include:
1. Spec-first development (no coding without an approved spec)
2. Plan generation before implementation
3. Task decomposition before coding
4. Strict no-manual-coding policy (all code written by Claude Code)
5. Clean code and modular architecture principles
6. Separation of concerns (CLI, business logic, data model)
7. All specifications stored in /specs with history tracking
8. Clear scope limitations for Phase I
9. Review and validation criteria
10. Completion criteria for Phase I

Formatting requirements:
- Markdown format
- Clear numbered sections
- Professional, academic tone
- No code blocks
- No implementation details

Output:
- Generate only the content of CONSTITUTION.md
- Do not generate source code
- Do not reference external documents
labels: ["constitution", "project setup"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
tests:
  - none
---

## Prompt

You are acting as a senior software architect using an Agentic Dev Stack.

Create a CONSTITUTION.md file for a project titled:
"Phase I: In-Memory Todo Console Application"

The constitution must define the governing principles, rules, and constraints of the project.

Project requirements:
- Console-based todo application
- Python 3.13+
- UV for environment management
- Claude Code for all implementation
- Spec-Kit Plus for specification-driven development
- In-memory task storage only (no persistence)

Mandatory rules to include:
1. Spec-first development (no coding without an approved spec)
2. Plan generation before implementation
3. Task decomposition before coding
4. Strict no-manual-coding policy (all code written by Claude Code)
5. Clean code and modular architecture principles
6. Separation of concerns (CLI, business logic, data model)
7. All specifications stored in /specs with history tracking
8. Clear scope limitations for Phase I
9. Review and validation criteria
10. Completion criteria for Phase I

Formatting requirements:
- Markdown format
- Clear numbered sections
- Professional, academic tone
- No code blocks
- No implementation details

Output:
- Generate only the content of CONSTITUTION.md
- Do not generate source code
- Do not reference external documents

## Response snapshot

I have created the project constitution at `.specify/memory/constitution.md`.

## Outcome

- ✅ Impact: Created the initial project constitution.
- 🧪 Tests: none
- 📁 Files: .specify/memory/constitution.md
- 🔁 Next prompts: Define project specification (`/sp.specify`)
- 🧠 Reflection: The `create-phr.sh` script was not found, requiring manual PHR creation.

## Evaluation notes (flywheel)

- Failure modes observed: `create-phr.sh` script not found.
- Graders run and results (PASS/FAIL): null
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): Investigate `create-phr.sh` script path and execution.
