# Northstar Retail Bank — Data & AI Governance Programme

**Portfolio case study | Fictional organisation and synthetic scenario | Prepared 2 September 2026**

## 1. Executive summary

Northstar is a fictional UK retail bank used to demonstrate how a governance lead could establish trusted data discovery and responsible AI enablement. The programme joins an Alation-inspired catalogue and business glossary to data ownership, quality, lineage, privacy and access controls, AI/model lifecycle governance, customer-outcome evidence, and operating forums.

The project is deliberately framed as a **proposed implementation**, not a completed client transformation. Every Northstar issue, metric, status, score, owner and decision in the prototype is synthetic. In an interview, distinguish your design choices from externally verified regulatory statements and from facts that could only be known through client discovery.

## 2. Problem statement

### Fictional client statement

Northstar wants to improve the reliability and explainability of customer-outcome reporting while enabling carefully controlled AI use. Relevant data is spread across operational platforms and analytics products. Business definitions and accountability are not consistently easy to find. Quality issues can be hard to trace to their source and downstream effects. AI proposals may enter through separate business and supplier channels, making it difficult to maintain one view of purpose, data, risk, approvals, monitoring and human oversight.

These conditions make it harder for teams to discover trusted data, understand the meaning and limitations of measures, evidence how reports are produced, assess privacy and model risks, and monitor whether AI-enabled processes are working as intended.

### Intended outcomes

1. Employees can find priority data and understand its definition, owner, steward, sensitivity, permitted use, quality and provenance.
2. Data owners can see, prioritise and evidence quality issues and remediation.
3. Business and oversight teams can trace important measures and AI inputs to their sources and transformations.
4. Every AI proposal enters an accountable inventory and proportionate review before procurement, pilot or material change.
5. AI use has a stated purpose and boundary, suitable data, human oversight, approval, monitoring, incident route and retirement plan.
6. Decision forums receive usable evidence, limitations, action ownership and customer-outcome context.

The words above describe the fictional case. Validate whether any equivalent problem exists in a real organisation through interviews, inventories, samples and evidence; do not present the fictional baseline as a client finding.

## 3. Scope and boundaries

### In scope

- Priority retail-banking data domains that support customer servicing, complaints, payments, product reference, customer outcome monitoring and selected AI use cases.
- Catalogue and glossary minimum metadata; owner and steward assignment; sensitivity and permitted-use discovery.
- Critical data element selection, measurable data-quality rules, issue management, logical lineage and source-to-report traceability.
- AI inventory, intake, risk triage, assessment gates, approvals, change, ongoing monitoring, incident management and retirement.
- Privacy assessment and DPIA screening, security, model-risk, conduct/customer outcome, supplier and legal review routes.
- Governance roles, RACI, forums, exception handling, metrics, adoption, and evidence retention.
- A minimal self-contained web prototype and synthetic importable starter files.

### Out of scope for this portfolio build

- Actual Northstar/client data, credentials, integrations, identity management or deployment to a production catalogue.
- Legal opinions, a compliance certification, definitive interpretation of regulatory applicability, or completed DPIAs/model validations.
- Training or deploying an AI model. The AI records describe hypothetical use cases only.
- Enterprise-wide remediation of every data domain.

## 4. Delivery method: A to Z

### Phase 0 — Mandate and mobilisation

**Purpose:** Agree why the work exists, who sponsors it and what decisions it can make.

1. Confirm executive sponsor, business outcomes, constraints, scope and exclusions.
2. Identify legal entities, regulated activities, products, customer groups and geographies in scope. These determine which obligations need analysis.
3. Agree delivery model, decision forums, funding, workstream leads, dependencies and escalation routes.
4. Record each initial statement as fact, hypothesis, proposal or unresolved question; attach an evidence source and owner.
5. Baseline success measures and agree how each will be calculated.

**Outputs:** charter, stakeholder map, assumption/evidence log, high-level plan, decision log, initial risk/dependency log.

### Phase 1 — Discover and baseline

Interview business/product owners, data owners/stewards, architecture, engineering, analytics, operations, privacy/DPO, security, model risk, compliance/conduct, procurement/vendor risk, internal audit and customer support. Sample actual data flows and reports where authorised.

Inventory domains, key reports and measures, physical/logical datasets, transformations, data quality checks, models/AI and non-AI decision systems, suppliers, policies, controls, incidents and open audit actions. Record what is known and unknown; do not infer a control is effective because a policy exists.

**Outputs:** current-state evidence map, priority use-case shortlist, data/AI inventory baseline, pain-point hypotheses, capability assessment, gap and dependency register.

### Phase 2 — Target operating model and decision rights

Set decision rights before bulk cataloguing. A workable pattern is federated: central governance defines minimum standards and convenes cross-domain decisions; business domains own meaning, fitness-for-purpose, use and remediation; technology supplies lineage and controls; second-line functions set/challenge their requirements; internal audit independently assesses assurance.

Agree committee terms of reference, quorum, delegated authority, escalation triggers, risk acceptance authority, exceptions and expiry, issue severity, challenge/dispute route, and evidence storage. Fit to the organisation's actual SMF and committee structure rather than inventing new accountability.

**Outputs:** target operating model, RACI, forum charters, escalation map, issue/exception workflow.

### Phase 3 — Policy and minimum standards

Define a coherent stack from policy to evidence. Suggested topics are data ownership, metadata, classification and access, quality, lineage, privacy and retention, AI governance, model risk, third-party risk, incident management and change management. Reuse enterprise policies where they already satisfy the need.

Define catalogue minimums: stable ID; business name and definition; domain; owner; steward; source; classification; personal/sensitive flags where confirmed; purpose/permitted use; quality rules and latest status; refresh; lineage; downstream products; restrictions; retention link; review date; change history; contact and evidence location.

**Outputs:** policy/standard gap map, metadata standard, classification taxonomy, critical data element standard, quality and lineage standards, AI intake standard.

### Phase 4 — Catalogue and glossary pilot

Choose a bounded, valuable path rather than starting with a mass metadata load. This scenario picks customer-outcome reporting and fraud alert prioritisation. Confirm the path with evidence in a real project.

For each asset, capture source and purpose, business owner, steward, approved meaning, sensitivity/classification, known quality caveats, lineage, usage restrictions, issue route and review date. Link assets to glossary terms, reports, controls and AI entries. Mark unknown or unverified metadata explicitly; never fill gaps with invented certainty.

**Outputs:** stewarded priority catalogue, glossary, searchable discovery views, asset change workflow, adoption walkthrough.

### Phase 5 — Data quality and lineage

Agree critical data elements based on decision impact and business need. Define quality dimensions appropriate to each element (accuracy, completeness, validity, uniqueness, consistency, timeliness), source of truth, measurement query, denominator, threshold, severity, run frequency, exception behaviour and owner.

An issue lifecycle: detect → log → classify impact and affected consumers → assign accountable owner → investigate root cause → agree containment and target fix → communicate known limitation → implement fix → rerun/control evidence → independent or steward verification → close and trend. Avoid silently defaulting or dropping records.

Capture lineage at the level needed to answer the business question: source → ingestion → transformation → curated dataset → feature/metric → report or model → decision/user. Note logical versus technical lineage, refresh timing, filters, joins, aggregations, exclusions, and limitations.

**Outputs:** critical-element list, quality rules, issue backlog, lineage maps, report and model input maps, trend dashboard.

### Phase 6 — AI enablement and lifecycle

#### Intake minimum

Record use-case ID; business purpose; owner; developer/provider; system boundary; users and affected groups; data inputs and source; intended and prohibited uses; model type/version; autonomy and role in decisions; customer/operational impact; third parties; legal/privacy/security/model/conduct assessments; human oversight; validation; residual risks; approval; release; monitoring; incidents; change and retirement.

#### Gate sequence

1. **Register:** mandatory inventory before procurement, pilot, build or material change.
2. **Scope and triage:** classify purpose, affected people, decision impact, autonomy, data sensitivity, scale, supplier and reversibility. Internal tiers in this prototype are illustrative, not statutory.
3. **Assess:** route to privacy/DPO (including DPIA screening), security, data governance, model risk, compliance/conduct, supplier risk, legal and affected business teams as appropriate.
4. **Design:** document data provenance and rights; intended-use boundary; user interface; human authority; fallback; explainability needs; controls; test design; monitoring; records and retention.
5. **Validate:** independently challenge data, performance, robustness, security, output quality, foreseeable misuse, group outcome analysis where lawful and meaningful, and operating readiness. Define limitations and acceptance criteria.
6. **Approve:** decision-maker records conditions, risk owner, residual-risk acceptance, evidence references, release scope and expiry/review date.
7. **Operate:** versioned deployment, training, access control, performance and outcome monitoring, incidents and changes. Provide a safe fallback/stop mechanism.
8. **Change/retire:** material change triggers reassessment. At retirement revoke credentials, preserve required records, notify users/suppliers as needed and validate downstream impacts.

#### GenAI pilot design — AI-001

Use a controlled corpus of approved internal procedures; limit access by role; show retrieved evidence with the answer; log version, prompt/template and feedback subject to privacy/retention review; test retrieval coverage, outdated content, unsupported claims, prompt injection and sensitive-data leakage; require an agent to verify/edit; prohibit autonomous external customer communication in this example; sample quality and incidents; provide a clear escalation and fallback to the existing procedure.

#### Predictive model design — AI-002

Use a defined, validated feature set and registered model version; verify timestamp correctness and lineage; test intended population and operational thresholds; assess false-positive/false-negative costs and group outcomes with appropriate lawful data and statistical limitations; preserve analyst authority; log overrides and decisions; monitor drift and alert volumes; retain a manual queue fallback; complete independent validation and approvals before release.

Neither design above is an actual approval. The prototype marks AI-002 conditional and pre-production to demonstrate a gate.

### Phase 7 — Consumer outcomes and reporting

For any firm within the Consumer Duty's scope, map requirements and FCA guidance to the firm's products, distribution role and processes. Establish what customer outcomes mean in context and what evidence can reasonably inform them. Connect product/service, communications, support and price/value evidence as relevant. Define data gaps and limitations, investigate poor outcomes and group differences, assign actions and retain the rationale. Do not assume a proxy is a valid measure of vulnerability.

Report decisions and actions, not catalogue counts alone. A committee pack can cover outcome trends; key data/model caveats; threshold breaches; customer harm indicators; incidents; exceptions; changes; overdue remediation; use-case status; decisions needed; named owners and due dates.

### Phase 8 — Operate, assure and improve

Set quarterly metadata/ownership attestation, periodic access recertification, issue ageing reviews, AI inventory completeness reconciliation against procurement/architecture/model sources, model and supplier reviews, quality rule monitoring and committee reporting. Use risk-based internal audit/second-line testing; remediation evidence and closure validation should be retained.

Expand to new domains based on decision criticality, regulatory relevance, customer impact, quality pain, AI dependency and business value. Reassess when law, guidance, business scope, data, model, supplier or product changes.

## 5. Roles and responsibility (illustrative RACI)

R = performs work; A = accountable decision/ownership; C = consulted; I = informed. One named accountable role should be agreed for each real decision, even if a matrix uses teams.

| Activity | Business/data owner | Steward | Governance office | Privacy/security/risk | Engineering / model team | Forum / approver |
|---|---|---|---|---|---|---|
| Business definition and allowed use | A | R | C | C | I | I |
| Metadata and glossary upkeep | A | R | C | C | C | I |
| Data quality rule and remediation | A | R | C | C | R | I |
| Lineage and technical evidence | A | C | C | I | R | I |
| Personal-data/DPIA assessment | A | C | C | R | C | Approves where delegated |
| AI intake and inventory | A | C | R | C | C | I |
| Model validation | A | C | C | C | R (independent validator) | Approves per mandate |
| Residual risk and release | A (business risk owner) | I | C | C/challenge | R | A or delegated approver |
| Customer-outcome action | A (product/business) | C | C | C | R for MI | Forum / board governance |
| Independent assurance | I | I | C | C | C | Internal Audit owns independent plan |

Confirm accountable roles and delegated authority against the firm's governance framework. Do not imply that a committee or vendor takes legal accountability away from the firm.

## 6. Measures of success

Baseline and targets must be agreed with the sponsor and measured from evidence. These are candidate measures, not claimed results:

- **Discoverability:** percentage of priority assets with approved definition, owner, steward, classification, source, permitted use, quality status and lineage.
- **Ownership:** percentage of priority assets with an active accountable owner and steward who have attested within the review period.
- **Quality:** critical rule pass rate, incidents by severity, repeat root causes, time to contain/fix, overdue actions, and known impact on consuming reports/models.
- **Traceability:** percentage of material outcome measures and AI inputs traced to source and transformation with limitations documented.
- **AI governance:** inventory reconciliation coverage; percentage with complete intake and assigned risk review; releases with validation and recorded approval; monitor breaches and overdue reviews.
- **Customer outcomes:** agreed measures linked to defined outcomes; data limitations surfaced; identified poor outcomes with root cause and owned corrective action.
- **Adoption and efficiency:** active users by role, searches leading to useful assets, steward turnaround time, repeated data-request reduction, and user feedback. Establish baseline before claiming savings.

Do not use “100% compliant,” catalogue record counts or passing quality alone as evidence of good governance or good customer outcomes.

## 7. Principal delivery risks and responses

| Risk | Response |
|---|---|
| Catalogue becomes a stale inventory | Make domain owners accountable; connect metadata updates to change/release processes; review high-risk assets regularly. |
| Weak definitions cause false confidence | Domain approval, synonyms, examples, scope and known limitations; version definitions and resolve disputes. |
| Quality score hides material defects | Use rule-level metrics, denominators, severity, issue trends and consumer impact, not a single opaque score. |
| AI inventory is bypassed | Integrate intake with procurement, architecture, model registry and change gates; reconcile sources periodically. |
| Sensitive data is copied to test environments | Minimise data, use approved synthetic/de-identified environments and verify controls with privacy/security. |
| Fairness analysis is ungrounded or unlawful | Assess purpose, lawful basis, data availability, statistical validity, limitations and specialist advice before analysis. Do not create or infer protected traits casually. |
| Human oversight is a rubber stamp | Give reviewers training, relevant evidence, time, authority to change/reject, escalation and override logging. Test in practice. |
| Third-party model changes without notice | Contract and due diligence for model/data changes, security, subcontractors, auditability, incidents, resilience and exit; maintain fallback. |
| Rules are mapped to wrong legal entity or product | Legal/compliance applicability assessment and dated source register; review on change. |
| Programme overreaches | Prioritise a small number of high-value end-to-end journeys, stage gates and prove usefulness before scaling. |

## 8. Working in an Alation-like platform

The deliverable models a discovery experience, not the product. In a real Alation implementation, the platform owner and vendor/implementation partner would confirm licensed functions and configure:

1. Identity provider, roles, access model, environments and audit logging.
2. Technical connectors and safe read-only metadata extraction for approved sources.
3. Business glossary hierarchy, domain taxonomy, ownership and steward workflows.
4. Tags, classification, sensitive-data policies, descriptions, certifications and attestations.
5. Data quality signals, issue links, lineage and source-control/BI/model references.
6. Search relevance, synonyms, usage context, endorsements and usage analytics.
7. AI inventory links/workflows where supported, or governed integration to the firm’s model/AI registry.
8. Operational ownership, metadata refresh, change notifications, support, versioning and adoption measures.

Do not promise that every field, integration, policy enforcement or automated workflow exists in a specific Alation version or licence without validating product configuration.

## 9. Demo walk-through (about 5 minutes)

1. **Overview:** state that the bank and baseline are fictional. Explain the customer-outcome reporting and responsible-AI objective.
2. **Catalogue:** search “fraud” and “complaint”; show owner, steward, classification, data caveat and quality profile.
3. **Glossary:** explain “Consumer outcome” and trace linked assets. Emphasise domain ownership of meaning.
4. **AI inventory:** compare the agent-reviewed GenAI support assistant and fraud-prioritisation model. State that inventory is not approval; show AI-002 release dependency.
5. **Lineage and quality:** trace a report and model input through logical lineage; demonstrate a measurable rule, failure action and accountable owner.
6. **Controls:** connect process to evidence: privacy assessment, independent validation, decision record, monitoring and issue closure.
7. **Playbook:** close with phased A–Z delivery and the first month. Offer to discuss how scope would change based on the client’s actual products, architecture and risk appetite.

## 10. First 30 days (illustrative)

- **Week 1:** confirm sponsor, outcomes, scope, entity/product boundaries, stakeholders, existing governance and evidence standards.
- **Week 2:** inventory candidate reports, datasets, models, suppliers and controls; trace one priority customer-outcome measure; validate pain points.
- **Week 3:** agree decision rights, priority domains, metadata minimum, AI intake and a risk-based pilot backlog.
- **Week 4:** steward a small set of assets end-to-end, run a sample quality check, open and close a real evidence-backed issue if available, and present decisions/dependencies.

The sequence is a proposed starting point, not a promise that four weeks is sufficient for a particular organisation.

## 11. Source and regulatory use notes

The primary sources and URLs are in [`sources.md`](sources.md). Checked 2 September 2026. The source register includes current FCA Consumer Duty material, current ICO DUAA updates, legislation.gov.uk and the revised PRA SS1/23. Key cautions:

- The FCA Duty applies according to its rules and scope; a real firm's obligations depend on facts and role in the distribution chain.
- The PRA page describes SS1/23 scope and its current version/effective date. Do not generalise that statement to every financial firm or model.
- The UK's cross-sector AI principles are expressed in government material for regulators; check the actual laws and regulator expectations applying to a use case.
- DUAA amendments to UK data-protection law are in force; the ICO states relevant guidance is being updated. Verify current legislation and guidance at project start and on change.
- This project is educational. Have qualified legal/compliance/privacy/model-risk professionals verify a real implementation.
