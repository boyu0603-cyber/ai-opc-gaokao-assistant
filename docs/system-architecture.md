# System Architecture

## Architecture Goal

The AI-OPC Gaokao Assistant is designed as a decision-support system, not an autonomous decision-maker. The architecture aims to combine structured data capture, controlled AI reasoning, knowledge support, and human review.

The main design priorities are:

- Explainability.
- Privacy protection.
- Modular components.
- Iterative planning.
- Clear separation between factual context and AI-generated reasoning.

## High-Level Architecture

```text
User / Advisor
     |
     v
Intake Interface
     |
     v
Profile Normalization Layer
     |
     +--------------------+
     |                    |
     v                    v
Knowledge Support     Preference & Constraint Model
     |                    |
     +---------+----------+
               |
               v
AI-Assisted Planning Layer
               |
               v
Explanation & Review Layer
               |
               v
Planning Summary / Iteration Loop
```

## Component Overview

### 1. Intake Interface

The intake interface collects user-provided information such as academic background, location context, subject direction, major interests, geographic preferences, family expectations, and risk tolerance.

The public documentation does not include real user profiles, private forms, chat logs, or personal data.

### 2. Profile Normalization Layer

This layer converts unstructured or semi-structured input into a consistent planning profile.

Example responsibilities:

- Standardizing preference categories.
- Identifying missing fields.
- Separating hard constraints from soft preferences.
- Preparing a structured context for downstream reasoning.

This layer helps reduce ambiguity before AI-generated recommendations are produced.

### 3. Knowledge Support

The knowledge support component is responsible for grounding planning discussions in approved reference material. In a production-oriented design, this could include public policy information, school and major descriptions, historical admission references, and advisor-approved materials.

Important design principles:

- Retrieved information should be traceable.
- Outdated or uncertain information should be flagged.
- AI-generated reasoning should not be confused with verified facts.
- Sensitive or unauthorized data should not be used.

### 4. Preference & Constraint Model

This component represents the student's decision conditions in a structured way.

Potential categories include:

- Academic profile.
- Province or region context.
- Major and career interests.
- Institution preferences.
- Geographic preferences.
- Family constraints.
- Risk tolerance.

This public document does not disclose proprietary scoring rules or recommendation parameters.

### 5. AI-Assisted Planning Layer

The planning layer uses AI to support reasoning and explanation. It may help compare candidate options, summarize trade-offs, and generate planning narratives.

The AI is positioned as a workflow assistant. It should not independently make final decisions or present uncertain outputs as guaranteed outcomes.

Public-safe AI tasks include:

- Clarifying ambiguous input.
- Summarizing option trade-offs.
- Explaining why a plan may be conservative, balanced, or ambitious.
- Producing readable planning summaries.
- Suggesting additional questions for human review.

### 6. Explanation & Review Layer

This layer turns internal planning output into user-facing explanations.

A strong explanation should include:

- Key assumptions.
- Main recommendation logic.
- Areas of uncertainty.
- Trade-offs among choices.
- Questions requiring human judgment.

Human review is part of the architecture, especially because Gaokao application planning is high-impact and context-dependent.

### 7. Planning Summary and Iteration Loop

The final output is not a one-time answer. The system is designed to support iteration as users update preferences, add constraints, or reconsider trade-offs.

The loop encourages the user or advisor to:

- Validate assumptions.
- Correct missing or inaccurate fields.
- Re-rank priorities.
- Compare alternative plans.
- Generate a revised planning summary.

## Enterprise AI Relevance

Although the project is education-focused, the architecture is relevant to enterprise AI systems because it follows patterns common in decision-support products:

- Structured intake before model reasoning.
- Human-in-the-loop review.
- Retrieval-assisted context.
- Explainable output generation.
- Modular pipeline design.
- Privacy and compliance boundaries.
- Audit-friendly documentation.

The same design logic can be applied to domains such as customer advisory, employee support, compliance triage, financial planning support, and internal knowledge management.

## Public-Safe Boundaries

This architecture document intentionally excludes:

- API credentials.
- Private environment settings.
- Internal prompts.
- User conversation logs.
- Real student data.
- Proprietary scoring formulas.
- Production deployment details that could expose private systems.

The goal is to communicate the system design clearly while keeping implementation-sensitive information private.
