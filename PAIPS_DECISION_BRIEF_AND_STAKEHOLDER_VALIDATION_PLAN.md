# PAIPS — Decision Brief and Stakeholder Validation Plan

**Project:** Papua New Guinea Provincial Administration Intelligence and Performance System (PAIPS)  
**Document reference:** PNG-PAIPS-DECISION-001  
**Prepared:** 23 October 2026  
**Status:** Pre-decision; desk research only  
**Related research:**  
- [Provincial Government Research Master](PROVINCIAL_GOVERNMENT_RESEARCH_MASTER.md)  
- [Provincial Government Existing Systems and Stakeholders](PROVINCIAL_GOVERNMENT_EXISTING_SYSTEMS_AND_STAKEHOLDERS.md)

---

## 1. Executive decision

### Current recommendation: NARROW AND VALIDATE — DO NOT BUILD YET

There is credible evidence that provincial performance reporting is an active government process and that reporting completeness, data availability, and verification can be difficult. However, the research does not establish that a new standalone software platform is needed, that existing systems cannot be improved, or that a government buyer or pilot partner is available.

PAIPS should therefore remain a **proposed concept**, not a confirmed product or approved government initiative.

The next activity should be stakeholder validation and existing-system investigation. No application development, database design, technology selection, or procurement claims should be made until the decision gates in this document are passed.

### Decision to make after validation

Choose one of five outcomes:

1. **Stop:** no sufficiently distinct problem, sponsor, or adoption route is established.
2. **Defer:** a problem exists, but timing, ownership, funding, or readiness is inadequate.
3. **Improve an existing system (preferred if feasible):** DPLGA or another authorised owner already has a platform that can be improved.
4. **Propose a narrow integration/workflow layer:** an independently validated gap remains, and the relevant agencies approve the approach.
5. **Consider a broader platform:** only if evidence demonstrates that narrower approaches cannot meet agreed requirements and government stakeholders request this option.

> **Important distinction:** the second research report calls “Option D” the integration-layer option, while its executive summary also uses “Option D” to mean conducting validation. To avoid ambiguity, this document names the immediate action **Stage 1: Validation** and reserves **Option D** for a potential integration layer.

---

## 2. What the research establishes

The following are findings reported by the two desk-research documents. They have not been independently verified through interviews or access to internal systems in this stage.

### Evidence-supported findings

- DPLGA has a formal role in provincial performance reporting and facilitates Annual Provincial Performance Reports (APPRs) and Section 114/119 reporting.
- DPLGA reported that 14 of 20 provinces had submitted their 2024 APPRs at the time described in its publication. This indicates incomplete submission at that point; it does not by itself explain why submissions were outstanding.
- Enga presented its 2023 and 2024 APPRs in 2025. Its published account described data availability and verification difficulties.
- Western Highlands presented its 2024 Section 119 report in 2025 and called for physical verification of reported projects and programmes.
- IFMS is the established government financial-management system for budgeting, accounting, payments, grants, expenditure and financial reporting.
- Department of Finance material identifies internet connectivity as an operational constraint for IFMS outside Port Moresby.
- DPLGA describes a digital-integration function with responsibilities related to digital platforms, data collection, performance monitoring and inter-governmental communication.

### What this evidence does NOT establish

- That DPLGA has no digital APPR or Section 119 platform.
- That provincial reporting is predominantly paper-based or spreadsheet-based.
- That IFMS has no suitable report exports, interfaces, APIs or authorised integration route.
- That provinces lack operational dashboards or internal reporting tools.
- That a dashboard would improve decision-making or reporting compliance.
- That a province would participate in a pilot.
- That government has approved PAIPS, allocated funding, or intends to procure it.

Absence of public documentation must be treated as **unknown**, not proof that a capability does not exist.

---

## 3. The problem hypothesis to test

### Primary hypothesis

Provincial administrations and DPLGA may benefit from improving the existing APPR/Section 119 workflow so that authorised officers can collect departmental inputs, attach supporting evidence, verify submissions, track deadlines, consolidate reports, and follow up agreed management actions with less repeated manual work.

### Hypotheses that require testing

1. Departmental inputs are difficult to collect consistently and on time.
2. Supporting evidence is difficult to locate, verify or audit.
3. Reporting status and overdue submissions are not visible to the right managers in time.
4. Corrective actions arising from reviews are not consistently tracked to closure.
5. Existing DPLGA or provincial tools cannot adequately address these problems.
6. A new digital workflow would be acceptable and usable in provincial connectivity conditions.

Do not present any of these hypotheses as established facts until validated with actual users and system owners.

---

## 4. Scope boundaries

### Potential scope, only if validated

A narrow reporting workflow could potentially cover:

- Departmental reporting submissions.
- Supporting documents and evidence references.
- Supervisor review and verification.
- Submission deadlines and status.
- Consolidation support for approved APPR/Section 119 reporting formats.
- Follow-up actions, owners, due dates and closure evidence.
- Role-based access and an audit trail.
- Offline-tolerant data capture if user research confirms the need.

### Explicitly out of scope for an initial proposal

PAIPS must not be positioned as a replacement for:

- IFMS financial transactions, accounting or budgeting.
- Statutory APPR, Section 114 or Section 119 reporting channels.
- Existing HR or employee-performance systems.
- Procurement systems.
- DPLGA, Finance or DICT systems already approved for these functions.

No IFMS integration should be promised before Department of Finance confirms an authorised technical and governance pathway.

---

## 5. Stakeholders to consult, in priority order

### Priority 1 — DPLGA

Request a briefing with:
- Secretary’s Office or delegated senior official.
- Corporate Planning and Performance Management Reporting Branch.
- Strategic Policy and Digital Integration Division / relevant digital-integration function.
- PLLSMA or the relevant monitoring function, if appropriate.

**Purpose:** establish the official reporting process, system status, ownership, templates, data definitions, existing digital initiatives and whether DPLGA is willing to explore improvement.

### Priority 2 — Department of Finance

Request a technical and business briefing with:
- Provincial and District Financial Management Division.
- Financial Management Improvement Program.
- IFMS project, ICT or system-support officials.

**Purpose:** establish IFMS's actual reporting capabilities, access permissions, export/interface options, data-sharing requirements and constraints. Do not request or exchange sensitive production data during initial discovery.

### Priority 3 — DICT

Ask the relevant digital-government, interoperability, cybersecurity, hosting and data-governance officials about:
- Digital Government Plan alignment.
- Government data standards and system registration or approval requirements.
- Hosting and data-residency expectations.
- Security assessment, identity/access management, backup and retention requirements.
- Interoperability standards and any government technology-stack constraints.

### Priority 4 — Provincial administrations

Potential interview targets from the desk research:
- Enga.
- Western Highlands.
- West New Britain.

These are **research targets only**, not confirmed pilot partners. Ask each administration to nominate the Provincial Administrator or delegate, planning/M&E staff, departmental heads, finance/treasury staff and ICT staff as relevant.

### Other stakeholders, if the first interviews indicate a need

- Department of National Planning and Monitoring.
- Department of Personnel Management, if overlap with employee-performance systems is identified.
- Department of Treasury, where budget reporting is relevant.
- National Procurement Commission or relevant procurement officials.
- Development partners, only after government ownership and needs are clearer.

---

## 6. Validation questions

### A. Questions for DPLGA

1. What is the current end-to-end APPR and Section 119 workflow, from departmental input to submission and parliamentary reporting?
2. What are the required templates, indicators, evidence standards, submission dates and validation rules?
3. Is there an internal or external digital platform supporting APPR or Section 114/119 reporting? If yes, what does it do, who uses it, and what gaps remain?
4. Are any new DPLGA digital reporting tools planned, being developed, piloted or procured?
5. How are incomplete submissions escalated and how is feedback returned to provinces?
6. How are reported project outcomes verified and how are corrective actions tracked?
7. Would DPLGA consider a process-improvement study or a narrowly scoped pilot? Who would be the business owner and approval authority?
8. What would make a proposed tool unacceptable or duplicative?

### B. Questions for Department of Finance / IFMS

1. Which provincial offices and user groups currently use IFMS, and for which functions?
2. What standard reports are available to authorised provincial managers?
3. Are exports, scheduled reports, APIs or other interfaces supported?
4. What permissions, approvals and technical constraints govern reuse of IFMS data?
5. Can an authorised workflow consume approved financial summaries without re-entering financial transactions?
6. What security, audit, hosting and support conditions apply?
7. What connectivity and operational constraints should a complementary tool accommodate?

### C. Questions for DICT

1. What policy, architecture, interoperability and cybersecurity approvals would a new government-facing reporting tool require?
2. Are there existing government platforms or shared services that should be reused?
3. What hosting, data-residency, identity, backup, retention and incident-response standards apply?
4. Is offline capture with later synchronisation permitted, and what controls would be required?
5. What is the appropriate process for technical review before any pilot?

### D. Questions for provincial users

1. Walk us through the last APPR/Section 119 reporting cycle, using actual artefacts where permission is granted.
2. Who supplies each section, in what format, and how is it consolidated?
3. Where do delays, rework, missing information or verification problems occur?
4. Which data is already held in IFMS or another system, and where is it stored?
5. How do managers see reporting status and follow up overdue tasks?
6. How are project progress and supporting evidence verified?
7. What devices, connectivity, staff skills and local ICT support are available?
8. What existing tools are used, and what would need to improve before staff would adopt another one?
9. Which two or three measurable outcomes would make an improvement worthwhile?
10. Would the administration consider a pilot if DPLGA and DICT approve it? Who could authorise participation?

---

## 7. Evidence to collect

Only collect material with permission and avoid sensitive or personal information unless there is an approved lawful basis and secure handling plan.

Request or inspect, where available:

- Current APPR and Section 119 templates.
- Current submission calendar and instructions.
- One completed, appropriately redacted report.
- Departmental input templates or registers.
- Evidence and verification guidelines.
- Report-review comments and feedback procedures.
- Existing system or platform descriptions.
- A sample reporting-status register with confidential information removed.
- Connectivity/device assessment for the candidate province.
- Written confirmation of system ownership and relevant approval pathways.

For each item, record: source, date, owner, version, access conditions, whether it is official, and which claim it supports. Do not upload confidential government records to public repositories.

---

## 8. Decision gates and go/no-go criteria

### Gate 1 — Existing-system clarity

**Pass only if:** DPLGA has explained the current process and confirmed whether an existing or planned digital tool covers the proposed workflow.

**If not passed:** continue discovery; do not design or code.

### Gate 2 — Validated user problem

**Pass only if:** at least one relevant government owner and several directly involved users describe a specific problem, supported by workflow evidence rather than general enthusiasm alone.

**If not passed:** narrow the hypothesis, defer or stop.

### Gate 3 — Distinct capability gap

**Pass only if:** the required capability is not already adequately provided by DPLGA, IFMS or another approved system, and stakeholders prefer an improvement or integration approach over duplicative entry.

**If existing systems can be improved:** recommend improving them instead.

### Gate 4 — Named sponsor and pilot owner

**Pass only if:** a government institution names a responsible business owner and provides written interest in the next stage. A conversation or informal positive comment is not formal approval.

**If not passed:** no pilot build.

### Gate 5 — Governance and technical pathway

**Pass only if:** DPLGA, Finance (for any IFMS-related data), and DICT (for applicable digital-government/security requirements) clarify the approval, data access, hosting and security route.

**If not passed:** do not connect to government systems or use real government data.

### Gate 6 — Measurable pilot and resourcing

**Pass only if:** the pilot has a baseline, limited scope, success measures, training/support arrangements, realistic costs, ownership, and a plan for maintenance or exit.

**If not passed:** defer the pilot.

### Decision rule

A pilot may be proposed only after Gates 1–5 pass. Development should begin only after the required written approvals and Gate 6 are satisfied. A production deployment requires a separate decision and security/governance approval.

---

## 9. Possible pilot measures

Agree these with the government owner before selecting targets. Do not invent target values before the baseline is measured.

- Percentage of required departmental submissions received by the agreed deadline.
- Time taken to consolidate an APPR/Section 119 report.
- Number of submissions returned for missing or inconsistent information.
- Percentage of claims with the required evidence attached or referenced.
- Time taken to resolve verification issues.
- Percentage of management actions closed by their due dates.
- User completion rate and time spent on reporting.
- Availability and successful synchronisation under actual connectivity conditions.
- Number of duplicate data-entry steps removed, without duplicating IFMS transactions.

A pilot should compare results against a documented baseline and use agreed definitions.

---

## 10. Solution options to keep open

| Option | Description | When to choose it |
|---|---|---|
| A. Keep current process | No new system; improve guidance, templates, training or reporting discipline. | If the problem is mainly procedural or low-cost changes are sufficient. |
| B. Improve an existing system | Extend DPLGA's or a province's existing approved tools. | If a suitable system exists and its owner supports improvement. |
| C. New standalone PAIPS | Build a separate platform. | Only if a distinct need is proven and reuse/integration cannot adequately address it. This is not currently recommended. |
| D. Narrow integration/workflow layer | Support the specific APPR/Section 119 workflow and approved data exchange without replacing systems of record. | If a gap is validated, owners approve it, and data access/security are feasible. |
| E. Shared multi-province platform | Common configurable service across multiple provinces. | Only after a successful, authorised pilot and a clear central owner, funding and support model. |

The selection must follow evidence and government direction, not a preselected technology or commercial preference.

---

## 11. Commercial and procurement position

At present, there is no verified PAIPS tender, confirmed buyer, allocated budget, approved vendor arrangement or pilot commitment in the desk-research record.

Therefore:
- Do not claim government endorsement, procurement readiness or guaranteed demand.
- Do not spend money or build a full product on the assumption that a government contract will follow.
- First establish the government problem owner, approved procurement route and potential funding source.
- If a pilot is supported, clarify procurement, intellectual property, support, data ownership, hosting, liability and exit arrangements before development.

Potential public value is not the same as proven commercial viability.

---

## 12. Immediate action plan

### Step 1 — Prepare a short official briefing request

Prepare a neutral request for an exploratory briefing with DPLGA. Ask to understand existing systems and process-improvement priorities; do not present PAIPS as a solution already selected.

### Step 2 — Prepare interview pack

Create:
- One-page project-neutral problem statement.
- Interview guide from Section 6.
- Evidence-request checklist from Section 7.
- Interview notes template with findings, evidence, contradictions and follow-up actions.

### Step 3 — Conduct DPLGA discovery first

Do not approach provinces with a request to adopt a new platform before DPLGA clarifies its current and planned systems. Once DPLGA advises, seek permission for appropriate provincial discussions.

### Step 4 — Conduct Finance and DICT discovery

Ask only about the relevant scope and approved pathways. No system access, credentials or real data should be requested at this stage.

### Step 5 — Interview provincial users

If access is granted, compare the actual workflows in selected provinces. Do not assume that three provinces have identical processes.

### Step 6 — Produce a validation findings report

Record:
- Confirmed findings and supporting evidence.
- Claims disproved or revised.
- Existing tools and owners.
- Validated pain points and affected users.
- Required approvals and data boundaries.
- Solution options and trade-offs.
- Recommendation: stop, defer, improve existing system, or propose a pilot.

### Step 7 — Return for a formal decision

ChatGPT should review the evidence and recommend a course of action. No software development should begin merely because interviews were completed; the decision gates must be satisfied.

---

## 13. Interview notes template

For each interview, record:

- Institution / province:
- Office and role (avoid unnecessary personal details):
- Date and method:
- Participants' authority to speak for the institution:
- Current workflow described:
- Systems and tools currently used:
- Specific problems described:
- Example or evidence supplied:
- Existing workaround:
- Consequence of the problem:
- Frequency / scale, if known:
- Proposed improvement from the user's perspective:
- Existing system or planned initiative that may overlap:
- Data sensitivity and access restrictions:
- Approvals required:
- Willingness to participate in further discovery (not equivalent to pilot approval):
- Unanswered questions:
- Follow-up owner and due date:
- Confidence rating and reason:

Separate direct observations, official documents, interview statements and our own interpretations.

---

## 14. Current decision record

| Item | Current status |
|---|---|
| Is provincial reporting an established process? | Yes, according to the desk research. |
| Is a reporting/verification problem plausible? | Yes; there is public evidence of incomplete submissions and verification difficulty. |
| Is a new standalone platform justified? | Not established. |
| Is DPLGA's digital APPR/Section 119 platform status known? | No; this is the highest-priority question. |
| Is IFMS integration capability known? | No; Department of Finance must clarify. |
| Is there a confirmed government sponsor? | No. |
| Is there a confirmed provincial pilot partner? | No. |
| Is there verified funding or procurement? | No. |
| Has software development been authorised? | No. |
| Next action | Stakeholder validation and existing-system investigation. |

## Final recommendation

**Proceed with validation, not development.** The project's immediate deliverable is evidence of the real workflow, the existing systems and their owners, a clearly bounded capability gap, and a credible government-led route forward. If that evidence does not emerge, PAIPS should be deferred or stopped rather than built speculatively.
