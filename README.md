# Northstar: UK Data & AI Governance Lab

An interview-ready portfolio project for a Data & AI Governance Lead or Manager. It combines a browser-based, Alation-inspired metadata catalogue prototype with an end-to-end delivery guide and editable governance starter artefacts.

## Open the project

Open `index.html` in a current browser. It is a static application with no installation, server, login, external service, or live data dependency. Navigate the catalogue, glossary, AI inventory, controls, quality/lineage views, and playbook. Download or edit the CSVs in `data/`.

## What is real and what is illustrative

- Northstar Retail Bank, all assets, owners, systems, risks, tiers, scores, thresholds, forums, decisions and delivery statuses are **fictional scenario inputs**.
- CSV rows contain synthetic metadata only; there is no customer-level or production data.
- The scenario is inspired by common financial-services governance needs and public supervisory themes. It does not reproduce confidential client material or allege that a named institution has these problems.
- Regulatory mapping is a starting point for discussion. It is not legal advice, a compliance attestation, or proof that a particular rule applies to a real firm's entity, activities, or system.

## Contents

- `Project-Guide.md` — problem statement, scope, operating model, A–Z method, roles, deliverables, measures, risks, and source-informed design notes.
- `Interview-Story.md` — concise project walkthrough and likely interview questions.
- `sources.md` — primary UK sources checked on 2 September 2026, with notes on what each supports.
- `index.html` — functioning local catalogue prototype.
- `data/data_assets.csv` — synthetic catalogue starter records.
- `data/business_glossary.csv` — business terms and ownership.
- `data/ai_use_cases.csv` — AI intake and lifecycle register examples.
- `data/control_library.csv` — control objectives, ownership, evidence and cadence.
- `data/data_quality_rules.csv` — example rules, thresholds, severities and failure handling.

## Demonstration path

1. Start at Overview and explain the fictional problem and target outcome.
2. In Data catalogue, search for “complaint” or “fraud”; show owner, sensitivity, status and quality profile.
3. In Business glossary, show how “Consumer outcome” connects business language to data products.
4. In AI use cases, compare bounded GenAI support with fraud prioritisation and explain why inventory is not approval.
5. In Quality & lineage, trace a customer outcome metric and an AI input back to source; discuss failure handling.
6. In Policies & controls, show how governance becomes accountable activities with retained evidence.
7. In Project playbook, walk through intake-to-monitoring and describe the first month of mobilisation.

## Alation comparison

This prototype borrows the **enterprise data discovery** pattern associated with a data catalogue: searchable assets, business definitions, ownership, tags, quality signals, and lineage. It is a teaching model, not an Alation clone or integration. A real Alation implementation would configure connectors, identity and access, metadata extraction, stewardship workflows, policy controls and platform-specific features in the licensed environment.
