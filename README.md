## Portfolio Note

This repository is a public-safe portfolio case prepared by QIAN Boyu (Bowie) for graduate study applications in AI, enterprise AI systems, and design-led AI innovation.

The purpose of this repository is not to publish production code, but to demonstrate my ability to frame a real-world decision problem, design a human-in-the-loop AI workflow, structure system architecture, and translate an early-stage AI product into a responsible and explainable portfolio artifact.

# ai-opc-gaokao-assistant[README.md](https://github.com/user-attachments/files/29405061/README.md)

Public-safe portfolio documentation for a personalized AI-assisted Chinese university application planning system.

> This repository intentionally contains documentation only. It does not include private datasets, user records, API credentials, conversation logs, proprietary prompts, or deployable production code.

## Project Summary

The AI-OPC Gaokao Assistant is an AI-assisted decision-support concept for students and families navigating the Chinese Gaokao university application process. The project explores how structured workflows, retrieval-assisted reasoning, and human-in-the-loop review can improve the clarity, consistency, and personalization of application planning.

The system is designed around a practical problem: Gaokao application decisions involve many variables, including exam score, province, subject track, institution level, major preference, career direction, admission risk, family constraints, and rapidly changing policy context. Families often struggle to organize this information into a reliable and explainable plan.

This portfolio version focuses on system design and workflow architecture rather than implementation details.

## Problem

Chinese university application planning is high-stakes, information-heavy, and time-sensitive. A useful assistant must do more than generate generic advice. It needs to:

- Convert incomplete student goals into structured planning inputs.
- Compare schools, majors, and admission possibilities in a transparent way.
- Separate factual information from model-generated reasoning.
- Provide explainable recommendations instead of black-box answers.
- Support iterative planning as families adjust priorities.

## Context

The project was developed as a public-safe portfolio artifact for graduate study applications, especially for programs focused on AI, data innovation, enterprise AI systems, and workflow automation.

It reflects a broader interest in building AI systems that combine:

- Domain-specific decision workflows.
- Human-centered interaction design.
- Responsible use of language models.
- Modular system architecture.
- Enterprise-style process orchestration.

## My Role

I worked on the product framing, system workflow, AI interaction design, and documentation structure. The core contribution was not only asking an AI model to answer questions, but designing a controlled decision-support process around the model.

My responsibilities included:

- Defining the user problem and decision journey.
- Structuring the planning workflow from intake to recommendation.
- Designing AI-assisted modules for information extraction, reasoning, explanation, and follow-up.
- Separating public-safe documentation from private implementation details.
- Translating a personal project into a graduate-level portfolio case study.

## System Design

At a high level, the system is organized into five layers:

1. User intake and preference capture.
2. Structured profile and constraint modeling.
3. Knowledge retrieval and policy context support.
4. AI-assisted planning and explanation generation.
5. Human review, iteration, and final plan refinement.

The design emphasizes traceability. Recommendations should be grounded in structured inputs and clearly labeled assumptions, rather than presented as final authority.

See [docs/system-architecture.md](docs/system-architecture.md) for the public-safe architecture overview.

## AI Components

The AI components are designed as assistants within a controlled workflow:

- **Profile structuring:** Converts user-provided background into normalized planning fields.
- **Preference clarification:** Identifies missing information and asks follow-up questions.
- **Retrieval-assisted context:** Supports school, major, policy, and application-related information lookup in a controlled manner.
- **Recommendation explanation:** Produces readable reasoning for different application options.
- **Risk communication:** Helps categorize choices into safer, balanced, and ambitious groups without exposing proprietary scoring parameters.

The portfolio documentation does not disclose private prompts, internal ranking rules, model credentials, or sensitive data.

## Workflow

The workflow follows a structured decision-support pattern:

1. Gather student profile and family priorities.
2. Normalize key planning variables.
3. Identify constraints and preference conflicts.
4. Retrieve relevant public or approved reference information.
5. Generate candidate planning options.
6. Explain trade-offs and assumptions.
7. Collect human feedback.
8. Refine the plan iteratively.

See [docs/workflow.md](docs/workflow.md) for the detailed workflow.

## Current Status

This repository is a public-safe portfolio version. It is suitable for sharing with admissions reviewers, academic mentors, and collaborators who need to understand the design thinking behind the project without accessing private code or data.

The current documentation includes:

- Project overview.
- System architecture.
- Workflow design.
- Lessons learned and next steps.

## Lessons Learned

This project reinforced several lessons about applied AI system design:

- A useful AI assistant needs workflow design, not just model access.
- In high-stakes decisions, explainability and scope control matter as much as output quality.
- Human-in-the-loop review should be treated as a core system feature.
- Public portfolio documentation must separate design contribution from sensitive implementation assets.
- Enterprise AI relevance comes from process integration, auditability, and reliability, not only model capability.

## Next Steps

Future development directions include:

- Building a more formal evaluation framework for recommendation quality.
- Designing a safer data governance model for student profile handling.
- Adding clearer provenance tracking for retrieved information.
- Improving multilingual documentation for international academic review.
- Exploring deployment patterns suitable for privacy-sensitive advisory systems.

## Public-Safe Scope

This repository does not contain:

- API keys, tokens, accounts, or `.env` files.
- Real user profiles, private chat logs, or personal data.
- Financial, payment, or transaction records.
- Proprietary recommendation parameters.
- Deployable private backend or production code.

The goal is to present the project as a system-design portfolio case for AI-assisted decision support.
