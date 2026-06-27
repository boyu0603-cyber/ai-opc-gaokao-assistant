# Data Governance

## Privacy Principles

The AI OPC Gaokao Assistant should follow privacy-first design because student application planning can involve sensitive educational, family, and personal preference information.

Core principles:

- Collect only information needed for planning.
- Avoid storing unnecessary personal details.
- Separate public portfolio materials from private operational materials.
- Require human review before outputs are used in consultation.
- Make uncertainty and source limitations visible.

## Sensitive Data Handling

Sensitive data may include:

- Student identity.
- Parent or family contact information.
- Scores, ranks, and application records.
- Private chat history.
- Consultation notes.
- Payment or commercial service information.
- Account credentials or system access details.

These materials must not be included in the public repository.

## Public Data vs Private Data

Public data may include official policy pages, public institution descriptions, public major information, and other approved references. Even public information should be checked for recency and source reliability.

Private data includes student profiles, family constraints, internal notes, private prompts, commercial materials, and any personally identifiable information. Private data should remain outside public documentation and should be handled only under a clear consent and access-control process.

## Source Provenance

Source provenance matters because Gaokao-related information can change by year, province, and institution.

A future prototype should track:

- Source name.
- Publication or access date.
- Relevant region or policy scope.
- Whether the information is official, public, advisor-curated, or user-provided.
- Whether the source needs manual verification.

## Human Review Requirement

AI-generated outputs should be treated as drafts. A human advisor should review:

- Factual grounding.
- Preference alignment.
- Risk language.
- Missing caveats.
- Source provenance.
- Whether the output is appropriate for family discussion.

## Data Minimization

The system should ask for the minimum information needed to support the planning stage. For example, early exploration may not need full identity information. A more advanced workflow may use anonymized profile IDs and separate personal identity from planning fields.

## Public-safe Repository Boundary

This repository is designed for admissions and portfolio review. It only contains:

- Public-safe project explanation.
- Architecture and workflow documentation.
- Synthetic sample output.
- Data governance principles.
- Evaluation and roadmap materials.

## What Is Intentionally Excluded

The repository intentionally excludes:

- Real student data.
- Parent or customer information.
- Private consultation records.
- Chat logs.
- API keys, tokens, passwords, credentials, and `.env` files.
- Private prompts.
- Internal scoring rules.
- Commercial pricing or service materials.
- Production backend or deployment code.

This boundary keeps the portfolio useful for review while reducing privacy and operational risk.
