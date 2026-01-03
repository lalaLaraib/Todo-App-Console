# Phase I: In-Memory Todo Console Application - Project Constitution

This constitution defines the governing principles, rules, and constraints for the "Phase I: In-Memory Todo Console Application" project.

## 1. Project Overview

**Title:** Phase I: In-Memory Todo Console Application
**Description:** A console-based application for managing todo tasks, focusing on core functionality and in-memory storage.
**Phase:** I (In-Memory Storage)

## 2. Project Requirements

*   **Application Type:** Console-based Todo Application
*   **Language:** Python 3.13+
*   **Environment Management:** UV
*   **Implementation Tool:** Claude Code
*   **Development Methodology:** Spec-Kit Plus for Specification-Driven Development (SDD)
*   **Data Storage:** In-memory task storage ONLY (no persistence to disk or database in Phase I)

## 3. Governing Principles and Rules

1.  **Spec-First Development:** No coding shall commence without a clearly defined and approved specification (`spec.md`).
2.  **Plan Generation Before Implementation:** A detailed implementation plan (`plan.md`) must be generated and approved before any coding begins.
3.  **Task Decomposition Before Coding:** All implementation tasks (`tasks.md`) must be decomposed into granular, testable units before writing any code.
4.  **Strict No-Manual-Coding Policy:** All code for the project will be written and managed exclusively by Claude Code. Manual code modifications by human developers are strictly prohibited.
5.  **Clean Code and Modular Architecture:** Adherence to clean code principles, including readability, maintainability, and a modular architecture, is mandatory.
6.  **Separation of Concerns:** The application architecture must clearly separate concerns:
    *   **CLI Layer:** Handles user interaction and command parsing.
    *   **Business Logic Layer:** Contains core todo task management functionality.
    *   **Data Model Layer:** Defines the structure of todo tasks (in-memory).
7.  **Specification Storage and History:** All project specifications, plans, and tasks shall be stored under the `/specs` directory, with proper version control to track history.
8.  **Clear Scope Limitations for Phase I:** This phase is strictly limited to in-memory storage. Any features requiring persistence, external integrations, or advanced UI beyond the console are explicitly out of scope for Phase I.
9.  **Review and Validation Criteria:** All generated specifications, plans, and code will undergo rigorous review and validation to ensure correctness, adherence to principles, and fulfillment of requirements.
10. **Completion Criteria for Phase I:** Phase I is considered complete when all specified core todo functionalities (add, view, mark complete, delete) are implemented, tested, and demonstrably working as a console application with in-memory storage, and all associated documentation (spec, plan, tasks, PHRs) is finalized.

## 4. Constraints

*   **Technology Stack:** Limited to Python 3.13+, UV, Claude Code, Spec-Kit Plus.
*   **Storage:** In-memory only.
*   **Interaction:** Command-line interface only.

## 5. Review and Approval

This constitution will serve as the foundational document for all project decisions and will be reviewed and approved by the project architect. Any deviations or amendments must follow a formal change management process.
