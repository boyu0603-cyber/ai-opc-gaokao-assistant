# Project Overview

## Problem

The Chinese Gaokao application process requires students and families to make complex decisions under pressure. A strong application plan may need to balance score range, province-level admission rules, school reputation, major fit, employment outlook, family preferences, geographic constraints, and risk tolerance.

Many families approach the process through fragmented information sources, informal advice, and manual comparison. This creates several recurring issues:

- Important constraints are discovered too late.
- School and major choices are compared inconsistently.
- Recommendations are difficult to explain or audit.
- Students may receive generic suggestions that do not reflect their actual priorities.
- Families often struggle to revise plans when assumptions change.

The AI-OPC Gaokao Assistant explores how an AI-assisted workflow can support this decision process in a more structured, explainable, and iterative way.

## Context

This project is framed as a graduate application portfolio case study. It is intended to demonstrate applied AI system thinking rather than expose private implementation assets.

The core context is not simply "using AI for education." The more important design challenge is building an advisory workflow for a high-stakes, domain-specific decision. In that setting, the system must handle ambiguity, incomplete information, changing policies, and different stakeholder priorities.

The project connects naturally to enterprise AI themes:

- Intake automation.
- Knowledge-assisted reasoning.
- Workflow orchestration.
- Explainable recommendation support.
- Human review and decision accountability.
- Privacy-conscious documentation and data handling.

## My Role

My role centered on turning a broad advisory idea into a structured AI system concept.

Key contributions included:

- Defining the user journey from initial consultation to revised planning output.
- Translating unstructured family goals into structured decision variables.
- Designing AI-assisted modules for clarification, comparison, explanation, and iteration.
- Establishing public-safe documentation boundaries for portfolio sharing.
- Positioning the project as an example of AI-assisted system and workflow design.

The project demonstrates my interest in building practical AI systems that fit real decision processes, rather than treating generative AI as a standalone chat interface.

## System Design

The system is designed around modular responsibilities:

- **User-facing intake:** Captures student background, preferences, and constraints.
- **Profile normalization:** Converts raw responses into structured planning attributes.
- **Knowledge support:** Connects recommendations to approved reference information.
- **Planning engine:** Produces candidate application strategies and trade-off summaries.
- **Explanation layer:** Communicates assumptions, uncertainty, and rationale.
- **Review loop:** Allows users or advisors to refine priorities and update results.

The design goal is to make AI outputs reviewable. The assistant should help organize and reason about the decision, while the final judgment remains with human users.

## AI Components

The AI-assisted components are designed to support specific tasks:

- Extracting structured fields from natural-language input.
- Detecting missing or conflicting information.
- Generating follow-up questions.
- Summarizing relevant school, major, and application context.
- Explaining trade-offs among candidate plans.
- Producing user-friendly planning summaries.

The public version does not disclose internal prompts, private ranking logic, scoring formulas, or proprietary parameter values.

## Workflow

The project workflow can be summarized as:

1. Collect initial student and family information.
2. Convert the information into structured planning variables.
3. Clarify missing or inconsistent preferences.
4. Retrieve or reference relevant application context.
5. Generate candidate options under different risk levels.
6. Explain trade-offs in plain language.
7. Review feedback and revise the plan.
8. Produce a final planning summary for discussion.

This workflow is designed to be iterative because Gaokao application planning rarely happens in one pass.

## Current Status

The current public repository is documentation-only. It presents the design rationale, architecture, workflow, and learning outcomes without exposing private source code, credentials, personal user information, or sensitive datasets.

The project is suitable for portfolio review because it demonstrates:

- Domain problem analysis.
- AI-assisted workflow design.
- Modular architecture thinking.
- Responsible documentation practice.
- Awareness of privacy and deployment constraints.

## Lessons Learned

Several lessons emerged from the project:

- Domain-specific AI systems require structured workflows around the model.
- For advisory systems, the ability to explain reasoning is essential.
- User input quality strongly affects recommendation quality.
- Missing information should trigger clarification rather than confident guessing.
- Public documentation must clearly separate system design from private implementation.

## Next Steps

Potential next steps include:

- Developing a formal evaluation rubric for recommendation usefulness.
- Adding clearer data provenance and citation support.
- Creating a privacy-first student profile schema.
- Improving feedback loops for advisors and families.
- Exploring a deployable prototype with strict access control and audit logs.
