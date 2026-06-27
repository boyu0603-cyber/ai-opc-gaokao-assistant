# Workflow

## Workflow Objective

The workflow of the AI-OPC Gaokao Assistant is designed to help students and families move from unclear goals to a structured, reviewable application plan.

The workflow does not assume that an AI model can replace human judgment. Instead, it uses AI to organize information, ask better questions, explain trade-offs, and support iterative planning.

## Stage 1: Initial Intake

The process begins by collecting the student's basic planning context.

Typical public-safe intake categories include:

- Academic background.
- Province or regional context.
- Subject direction.
- Target majors or career interests.
- Preferred cities or regions.
- Institution preferences.
- Family expectations.
- Risk tolerance.

At this stage, the system should avoid making recommendations too early. The goal is to understand the decision context.

## Stage 2: Profile Structuring

The assistant converts the intake information into a structured profile.

This step helps identify:

- Hard constraints.
- Soft preferences.
- Missing information.
- Conflicting priorities.
- Assumptions that need confirmation.

For example, a student may prefer a specific city but also prioritize a major that is stronger elsewhere. The workflow should surface this conflict before generating a final plan.

## Stage 3: Clarification

If the profile is incomplete, the assistant asks targeted follow-up questions.

Good clarification questions are specific and decision-relevant. They should help determine:

- Whether location or major fit matters more.
- Whether the family prefers lower risk or higher upside.
- Whether employment outlook, academic interest, or school reputation is the top priority.
- Whether certain schools, regions, or majors should be excluded.

This stage reduces the chance of producing confident but poorly matched recommendations.

## Stage 4: Context Support

The workflow then brings in relevant reference information from approved sources or curated materials.

The purpose is to support reasoning with context such as:

- Institution characteristics.
- Major descriptions.
- Policy considerations.
- Historical application references.
- Career and study-path considerations.

The assistant should clearly distinguish retrieved or referenced information from AI-generated interpretation.

## Stage 5: Candidate Plan Generation

The system generates candidate application options based on the structured profile and context.

At a public-safe level, options may be grouped by risk posture:

- Conservative options.
- Balanced options.
- Ambitious options.

This document does not disclose internal scoring formulas, private weighting rules, or proprietary recommendation parameters.

## Stage 6: Explanation

Each candidate plan should be accompanied by a clear explanation.

Useful explanations include:

- Why the option may fit the student's goals.
- What trade-offs are involved.
- Which assumptions the plan depends on.
- What information should be verified.
- How the option compares with alternatives.

The explanation layer is especially important because families need to understand the reasoning before trusting or revising a plan.

## Stage 7: Human Review

The workflow expects human review before any final decision.

Users or advisors should be able to:

- Correct profile information.
- Reject unsuitable options.
- Reorder priorities.
- Add new constraints.
- Ask for alternative strategies.

Human review is treated as a system feature rather than an exception.

## Stage 8: Iteration and Final Summary

After review, the assistant updates the plan and produces a revised summary.

A useful final summary should include:

- Student profile assumptions.
- Main preferences and constraints.
- Candidate plan categories.
- Key trade-offs.
- Open questions.
- Suggested next actions.

Because Gaokao application planning changes as new information appears, the workflow is designed to support multiple iterations.

## Workflow Principles

The project follows several workflow principles:

- Ask clarifying questions before generating major recommendations.
- Keep user preferences structured and revisable.
- Make assumptions visible.
- Separate factual context from AI reasoning.
- Keep humans responsible for final decisions.
- Avoid exposing sensitive implementation details in public materials.

## Current Status

The current public version documents the workflow as a portfolio case. It does not include private user sessions, personal information, internal prompts, production code, or sensitive data.

## Next Steps

Future workflow improvements may include:

- A structured intake form with privacy controls.
- A review dashboard for advisors.
- Provenance tracking for supporting information.
- A recommendation quality rubric.
- User feedback collection for iterative improvement.
