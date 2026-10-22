# PROVINCIAL GOVERNMENT RESEARCH MASTER  
## Papua New Guinea Provincial Administration Intelligence and Performance System (PAIPS)

**Handover reference:** PNG-PGAPS-RESEARCH-001  
**Prepared for:** Independent verification and product-strategy review  
**Research date:** 23 October 2026  
**Status:** Research and opportunity discovery only — no product design, architecture, code, procurement commitment, or pilot-partner selection has been made.

---

## SECTION 1: EXECUTIVE SUMMARY

### Core finding

The research finds **partial but credible evidence of an unmet need** for better consolidated, timely, and verifiable operational reporting within Papua New Guinea’s provincial administrations. The strongest documented problems are late or missing financial and acquittal reports, weak monitoring of provincial and district service-improvement funding, unreliable financial records, and limited feedback on provincial performance reports. These problems are documented by the Auditor-General, the PNG Parliamentary Public Accounts Committee, the Asian Development Bank, the United Nations Development Programme, and the Lowy Institute. [7][8][11][13][14][15][31]

However, the evidence does **not** establish that every provincial administration lacks all performance-reporting capability, nor that a new stand-alone platform is automatically the right response. PNG already has important national systems and institutional mandates: the Integrated Financial Management System (IFMS) for financial administration, DPLGA’s Section 114 and Section 119 reporting responsibilities, provincial corporate-plan and annual-performance-report processes, and the Digital Government Act 2022 framework. [16][17][21][24][25][28]

### Strongest evidence of an unmet need

1. **Late mandatory financial reporting is persistent.** The Auditor-General and parliamentary inquiry evidence show repeated delays, incomplete financial statements, weak records, and audit backlogs affecting provincial and local-level governments. More recent reporting in 2026 indicates that non-submission of financial statements remains a material concern. [11][12][13][14]

2. **Service Improvement Program reporting has been weak.** The Auditor-General found late acquittal reports, mismatches between reported and disbursed amounts, and ineffective monitoring of Provincial, District, and Local-Level Service Improvement Program funds. [15]

3. **Provincial performance reports have historically not been consistently submitted or analysed.** The ADB reported that provinces were expected to submit annual performance reports but often did not, and that submitted reports were rarely analysed or followed by feedback. [31]

4. **Financial systems have expanded but do not by themselves solve operational performance management.** IFMS is now reported as deployed across provinces, districts, health authorities, and local-level governments, but it is primarily a financial-management system rather than a departmental work-plan, service-delivery, project-milestone, and management-action platform. [16][17][22][23]

### Most important existing systems

| System / process | Owner | Relevance to PAIPS |
|---|---|---|
| Integrated Financial Management System (IFMS) | Department of Finance | Operational financial accounting, budgeting, payments, and reporting platform; now reported as rolled out across provinces and districts. PAIPS should integrate with or consume authorised IFMS-derived data rather than duplicate it. [16][17][22][23] |
| Section 114 and Section 119 reporting | DPLGA with provincial governments | Existing statutory reporting channels for provincial financial affairs and governance/performance matters. [21][31] |
| Provincial corporate plans and annual performance reports | Provincial administrations, with DPLGA coordination | Existing planning and performance-reporting process; PAIPS could improve timeliness, evidence capture, and consolidation. [24][25][31] |
| DPLGA performance-monitoring mandate | DPLGA | DPLGA states that it is developing and institutionalising provincial performance-reporting systems and monitoring performance across provinces, districts, cities, LLGs, and special-purpose authorities. [21] |
| Digital Government Act 2022 and Digital Government Plan 2023–2027 | DICT | Establishes the legal and policy environment for digital government, data standards, cybersecurity, and shared digital infrastructure. Any PAIPS proposal must align with these requirements. [1][4][6][18][28] |
| Public Service Performance Management System (PMS) | Department of Personnel Management | A performance-management initiative for agency heads and public servants; earlier rollout experienced awareness, data, connectivity, staffing, funding, and legal-settlement constraints. [40][41] |

### Major confirmed or probable gaps

- **Proven:** delayed financial statements, weak accounting records, late acquittals, and audit backlogs. [7][8][11][12][13][14][15]
- **Probable:** fragmented departmental reporting, manual consolidation, limited management visibility below department-head level, and inconsistent follow-up on corrective actions. These are strongly suggested by the reporting failures and by DPLGA’s stated intention to build stronger reporting systems, but they require provincial-level validation. [21][24][25][31]
- **Unresolved:** the actual availability of computers, mobile devices, connectivity, ICT support, and digital skills in each provincial administration; the current state of each province’s reporting workflow; and whether administrators would use and fund a new system. [29][40]

### Feasibility assessment

A narrow, integration-first PAIPS is **feasible to investigate further**, but a broad new “whole-of-province intelligence platform” is not yet justified. The most defensible approach is **Option B/D combined**: build a narrowly scoped departmental reporting and management-action layer that consumes authorised financial data from IFMS where possible, supports offline-capable data entry, and complements—not replaces—Section 119, corporate-plan, and IFMS reporting. [16][17][18][21][31]

### Recommended next step

Proceed to **structured stakeholder research and a limited, conditional pilot definition** with one willing provincial administration. Do not begin software development until the pilot partner confirms its reporting workflows, data availability, connectivity, authorised users, and willingness to provide a named business owner. The pilot should test only reporting compliance, work-plan/activity status, evidence attachment, supervisor verification, management actions, and an authorised dashboard—not a full provincial ERP or analytics platform.

---

## SECTION 2: RESEARCH SCOPE AND METHODOLOGY

### Scope

The research examined whether provincial administrations in PNG have a documented need for an integrated system to collect, verify, consolidate, and present departmental performance and operational information across an authorised management hierarchy.

It covered:

- PNG provincial-government institutional structures and reporting obligations.
- Documented administrative, financial, monitoring, and service-delivery problems.
- Existing government systems and reporting processes.
- Dashboard, hierarchy, data-collection, and indicator considerations.
- Security, privacy, governance, technical, financial, adoption, and commercial feasibility.
- Comparable international lessons at a high level.

### Source-selection criteria

Priority was given to:

1. PNG government sources, including DPLGA, Department of Finance, DICT, Auditor-General, Department of Personnel Management, and Prime Minister and National Executive Council communications.
2. Multilateral and development-partner sources, including ADB, World Bank, and UNDP.
3. Independent research and credible policy analysis, including the Lowy Institute.
4. Government-linked reporting and credible news only where it reports statements or developments not available in primary documents.

Vendor marketing, unverified social-media claims, and unsupported estimates were not treated as evidence of need or implementation success.

### Research limitations

This is a **desk-based public-source review**. No provincial administrators, departmental heads, ICT officers, finance officers, or frontline officers were interviewed. Therefore, the report can establish institutional mandates and nationally documented problems, but it cannot verify current workflows, system usage, user demand, or province-specific readiness.

Key unavailable evidence includes:

- Current IFMS usage depth and data quality by province.
- Whether IFMS exposes usable APIs or reporting extracts for a provincial dashboard.
- Current Section 119 report submission rates and quality.
- Province-by-province connectivity, device availability, and ICT staffing.
- Current DPLGA performance-reporting system status and data model.
- Active government procurement opportunities, budgets, and supplier arrangements for provincial performance systems.
- Formal legal advice on data residency, records retention, procurement, and privacy obligations.

These limitations are carried into Section 16.

---

## SECTION 3: PNG PROVINCIAL GOVERNMENT STRUCTURE

### National coordination institutions

**Department of Provincial and Local-Level Government Affairs (DPLGA)** is the central institution most directly relevant to PAIPS. Its published structure includes an Executive Wing responsible for a management reporting framework capturing performance, expenditure, and outcomes, and for facilitating Section 114 financial-affairs and Section 119 governance-affairs reporting under the Organic Law on Provincial and Local-Level Government Affairs. Its Corporate Support Services Wing is responsible for institutional performance monitoring, evaluation, and reporting, and for developing provincial performance-reporting systems. [21]

DPLGA’s earlier corporate plans also describe its role as secretariat to the Provincial and Local-Level Services Monitoring Authority (PLLSMA), with responsibilities for minimum standards, capacity development, performance monitoring, Section 119 report analysis, and reporting to the Minister. [24][25]

**Department of Finance** owns IFMS, the government’s integrated financial-management system. The Department states that IFMS environments were configured for provincial and local-level governments, district development authorities, and provincial health authorities; it later reported rollout to provincial and district finance offices, with subsequent expansion to remaining provincial and local-level entities. [16]

**Department of Information and Communications Technology (DICT)** administers the Digital Government Act 2022 and leads the Digital Government Plan 2023–2027. DICT coordinates digital projects across national, provincial, and district levels and requires ICT project designs to align with the Digital Government Plan, Government Technology Stack, and ICT policies. [1][6][28]

**Department of Personnel Management (DPM)** is responsible for public-service employment, payroll, and performance-management policy. In 2026, the Prime Minister announced a Public Service Payroll Office and a reform direction linking individual KPIs to key result areas, MTDPs, and Vision 2050, with intended extension of ICT-enabled performance and payroll tools to provincial administrations. This is a policy direction and reform agenda, not evidence that a province-wide digital performance system is already operating. [36][38]

**Office of the Auditor-General (OAG)** is the legislated auditor for government units, including provinces and local-level governments. Its reports are the principal independent evidence source on provincial financial-management and reporting weaknesses. [9][13][14]

### Provincial administrations

A provincial administration typically supports an elected provincial government and implements functions across departments such as finance and treasury, planning, works, health, education, administration, and community services. The precise departmental structure varies by province, so PAIPS must not impose a fixed hierarchy without local validation.

The proposed hierarchy—Provincial Administrator, departmental heads, divisional managers, unit supervisors, and officers—is broadly plausible as a management model, but it should be treated as configurable rather than universal. Evidence from DPLGA and provincial corporate plans shows that planning and reporting are expected to cascade from corporate plans to divisional annual activity plans and individual work plans, with quarterly review. [24][25][30][35][37]

### Who monitors provincial performance?

- **Provincial administrators and departmental heads** are responsible for internal management, departmental plans, work plans, and operational reporting.
- **DPLGA** coordinates and analyses provincial governance and performance reporting, particularly Section 119 reports, and has a stated mandate to develop provincial performance-reporting systems. [21][25][31]
- **Department of Finance and Treasury** oversee financial reporting, budget execution, and public financial management.
- **OAG** provides independent audit assurance. [9][13][14]
- **National Planning and Monitoring** has historically identified sector performance indicators and expected provinces to report progress through annual performance reports. [31]

### Reporting obligations

The evidence identifies several reporting channels:

- Annual provincial performance reports to national government, historically linked to DPLGA and the Minister for Inter-Governmental Relations. [31]
- Section 114 financial-affairs reports and Section 119 governance-affairs reports under the Organic Law on Provincial and Local-Level Government Affairs. [21]
- Annual financial statements and monthly bank reconciliations for provincial, district, and LLG accounts. [7]
- Service Improvement Program acquittal reports for PSIP, DSIP, and LLGSIP funding. [15]
- Corporate-plan, annual activity-plan, quarterly, and annual performance reporting within provincial administrations and national departments. [24][25][30][35][37]

---

## SECTION 4: DOCUMENTED ADMINISTRATIVE PROBLEMS

### Evidence table

| # | Identified problem | Affected institution | Evidence | Direct source | Publication date / period | Current relevance | Operational consequence | Potential digital response | Confidence |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Provincial and LLG financial statements have contained material errors, uncertainties, and inadequate records, preventing reliable audit opinions. | Provincial governments, LLGs, OAG | Parliamentary Public Accounts Committee inquiry findings; OAG reports. | [11] | Inquiry covers 2005–2007; report published later. | Historical but structurally relevant; later OAG reporting indicates continuing non-submission and quality problems. [12] | Audit delay, weak financial oversight, difficulty tracing public money. | Standardised financial-data submission, exception flags, document/evidence attachment, status tracking. | High for historical finding; high that reporting weakness persists in some entities. |
| 2 | Severe delays in submission of provincial and district annual financial statements and monthly bank reconciliations. | Provincial governments, district and LLG administrations, Department of Finance | UNDP PCaB project documentation reported most provinces were three to four years late with AFS and 25–40 months late with bank reconciliations. | [7] | Project documentation endorsed 2016; describes preceding-period conditions. | Historical baseline; the problem was severe enough to motivate an electronic M&E tool. | Delayed budget releases and impaired service delivery. | Submission tracking, deadline alerts, completeness checks, reconciliation-status dashboard. | High for the documented period; current status requires verification. |
| 3 | Late acquittal reports and mismatches for PSIP, DSIP, and LLGSIP funds. | Provincial administrations, District Development Authorities, LLGs, Department of Rural Development / Finance | Auditor-General found late acquittals, figure mismatches, capacity and resource constraints, and ineffective monitoring. | [15] | Audit covers 2013–2016. | Highly relevant to reporting-compliance and funds-acquittal workflow. | Delayed monitoring, weak accountability, delays in subsequent funding and inspections. | Acquittal workflow, evidence upload, supervisor certification, overdue alerts, variance reporting. | High for the audited period; current recurrence requires confirmation. |
| 4 | Provincial annual performance reports were often not submitted, and submitted reports were rarely analysed or followed by feedback. | Provincial administrations, DPLGA | ADB Provincial Performance Improvement Initiative evaluation. | [31] | Initiative began 2004; publication reflects programme experience. | Important historical evidence; DPLGA’s current mandate suggests the issue remains institutionally recognised. [21] | Weak accountability, limited learning, no corrective-action loop. | Structured report submission, automated completeness checks, review workflow, feedback/action register. | Medium-high; historical but consistent with DPLGA’s ongoing reform mandate. |
| 5 | Weak financial management and delayed audits in provincial and local-level governments. | Provincial governments, LLGs, OAG | Auditor-General Part 3 reports identify inaccurate statements, inexperienced personnel, weak records, and audit delays. | [13][14] | 2010 and 2014 audit reporting. | Historical, but Lowy Institute’s 2024 analysis cites the 2017 provincial audit and continuing non-compliance concerns. [8] | Delayed oversight, weak control environment, reduced public accountability. | Financial-report status dashboard and integration with IFMS-derived reporting; not a replacement for IFMS. | High for historical findings; current extent unresolved. |
| 6 | Non-submission of financial statements remains a current concern. | Public bodies including provincial entities, OAG | 2026 reporting quotes the Auditor-General stating that many entities, including provincial entities, have not submitted financial statements for audit, with some delays of seven to eight years. | [12] | Published 21 October 2026. | Current and highly relevant. | Audits cannot commence; oversight of provincial funds is delayed. | Mandatory submission register, escalation workflow, evidence and sign-off trail. | Medium-high; news report of Auditor-General remarks, not the underlying OAG report. |
| 7 | Performance-management rollout has faced connectivity, staffing, awareness, data, and funding constraints. | DPM, provincial administrations, public agencies | DPM newsletter reports PMS rollout issues including connectivity problems, unavailable dedicated data-entry staff, funding constraints, and confusion over KRAs/KPIs. | [40] | Newsletter period not precisely dated; refers to pre-2018 conditions and the then-recent Supreme Court decision. | Relevant as evidence that digital performance systems face adoption barriers in PNG. | Low adoption, incomplete data, unreliable performance assessment. | Offline-first design, training, business-owner model, simple forms, phased rollout. | Medium; dated source, but barriers remain plausible and require validation. |
| 8 | IFMS rollout was previously constrained by communication infrastructure in provinces. | Department of Finance, provinces | Auditor-General review of IFMS stated provincial rollout was not included in the earlier project because required communication infrastructure was unproven or absent. | [29] | Audit report covers the earlier IFMS project period. | Historical; IFMS has since been expanded substantially. [16][17][22] | Connectivity and support remain material deployment risks. | Offline-capable collection and synchronisation; dependency mapping before deployment. | High historically; current infrastructure status varies and is unresolved. |
| 9 | Public-sector management has been input-focused rather than results-focused. | PNG public sector broadly, including sub-national administration | World Bank public-expenditure and service-delivery review found services are managed and monitored mainly on staff and money inputs, diverting attention from results. | [3] | Older World Bank report. | Conceptually relevant; not sufficient alone to prove a current provincial dashboard need. | Weak results orientation and limited output-based accountability. | Output and milestone tracking, evidence-based reporting, management review. | Medium; older source, used as context rather than proof of current conditions. |

### Verified versus hypothesised problems

**Verified or strongly documented:**

- Late or missing financial statements and reconciliations. [7][11][12][13][14]
- Late or inconsistent SIP acquittals. [15]
- Audit delays and weak record-keeping. [8][11][13][14]
- Historical weakness in provincial performance-report submission and feedback. [31]
- Adoption barriers for prior digital performance-management initiatives. [40]

**Probable but not yet province-verified:**

- Manual consolidation of departmental reports.
- Repeated data entry between spreadsheets, emails, and formal reports.
- Limited visibility of activity, project, and service-delivery status below department-head level.
- Weak tracking of management decisions and corrective actions.
- Inconsistent indicator definitions across departments.

**Unverified hypotheses:**

- That all provincial administrators want a dashboard.
- That officers will reliably submit digital reports.
- That provinces have sufficient devices, connectivity, and ICT support.
- That a new platform would improve outcomes more than strengthening existing reporting and IFMS use.

---

## SECTION 5: EXISTING GOVERNMENT SYSTEMS

### System comparison

| Existing system | Owner | Main function | Implementation status | Provincial coverage | Capabilities | Verified gaps | Relationship to PAIPS |
|---|---|---|---|---|---|---|---|
| Integrated Financial Management System (IFMS) | Department of Finance | Government accounting, budgeting, payments, procurement-related financial processes, and financial reporting. | Operational; reported as fully functional for 37 national departments, 11 statutory authorities, 19 provincial governments and their DDAs/LLGs, and 13 PHAs in a 2024 DICT presentation; later government communications describe full provincial connectivity and a 2025 cloud migration. [17][22][23] | Reported nationwide, including provinces and districts; NCDC and Bougainville were excluded from the earlier rollout scope. [16] | Financial transactions, budget and expenditure data, financial reporting; real-time online accounting and financial data are identified in the Digital Government Plan. [4] | Not designed as a departmental work-plan, field-service, project-milestone, or management-action system; public evidence does not establish province-level dashboard usability or API access. | Primary integration candidate for budget execution, expenditure, and financial-reporting indicators. |
| Section 114 / Section 119 reporting | DPLGA and provincial governments | Statutory reporting on provincial financial affairs and governance/performance matters. | Institutional process; DPLGA identifies it as an ongoing function. [21] | All provincial governments subject to the relevant Organic Law provisions. | Formal compliance and governance reporting. | Public evidence does not show a modern consolidated digital workflow or timely analytics layer. | PAIPS should support preparation, evidence capture, approval, and status tracking—not replace statutory reporting. |
| Provincial corporate plans and annual performance reports | Provincial administrations; DPLGA coordination | Set provincial objectives, annual activity plans, work plans, and performance reports. | Established administrative process. [24][25][31] | Province-specific; historically uneven submission and analysis. [31] | Planning, target setting, quarterly review, annual performance reporting. | Manual compilation, variable timeliness, limited feedback loop. | Core workflow that PAIPS could digitise and strengthen. |
| DPLGA provincial performance-reporting systems | DPLGA | Monitor and report provincial, district, city, LLG, and special-purpose-authority performance. | DPLGA states this is an institutional objective/current function; deployment maturity is not publicly established. [21] | Unknown. | Intended performance monitoring and reporting. | Implementation status, data model, user base, and dashboard capability unknown. | Potential existing platform to improve or integrate with, rather than duplicate. |
| Public Service Performance Management System (PMS) | Department of Personnel Management | Performance management for agency heads and public servants, including KRAs and KPIs. | Previously rolled out to a small number of agencies; later reported as affected by legal and implementation constraints. [40][41] | Limited historical coverage; East New Britain Provincial Administration was among early users. [40] | KRA/KPI definition, appraisal and performance assessment. | Connectivity, staffing, funding, awareness, and data-quality constraints were documented. [40] | Potential future HR/performance integration, but not a substitute for operational departmental reporting. |
| SIP acquittal monitoring | Department of Finance / Department of Rural Development / provincial and district administrations | Track acquittal of PSIP, DSIP, and LLGSIP funds. | Process exists; Auditor-General found monitoring and reporting largely ineffective in the audited period. [15] | Provinces, districts, and LLGs. | Acquittal submission and compliance checking. | Late submissions, mismatches, limited monitoring capacity. | Strong candidate for a narrow PAIPS module: acquittal status, evidence, certification, and overdue alerts. |
| Government data standards and digital-government infrastructure | DICT | Data governance, security, interoperability, digital identity, shared infrastructure, and cyber-risk management. | Policy/standards framework and implementation programme; Digital Government Plan approved by NEC. [1][4][6][18][28] | Applies across national, provincial, and local-level agencies. [18] | Standards for data management, security, access control, encryption, privileged access, and data protection. | Operational maturity and agency compliance vary; not a performance-management system. | Mandatory compliance and integration environment for PAIPS. |

### Alternative assessment

| Option | Assessment | Evidence-based judgement |
|---|---|---|
| **A. Develop a new integrated platform** | Could address operational reporting gaps but carries duplication, adoption, cost, security, and maintenance risk. | Not recommended as the first move. The evidence supports a narrow system, not a broad new platform. [16][17][21][31] |
| **B. Integrate existing systems into a common dashboard** | Best aligned with the existence of IFMS, DPLGA reporting, and digital-government standards. | Strongest strategic direction, but requires verified API/extract access and data-governance approval. [4][16][17][18] |
| **C. Improve an existing government platform** | Potentially ideal if DPLGA’s performance-reporting system or IFMS reporting can be extended. | Must be investigated before building anything new; current public evidence is insufficient to confirm technical feasibility. [16][21] |
| **D. Develop a narrower departmental reporting or data-collection solution** | Most practical near-term option if integration is not immediately possible. | Recommended as the pilot scope: activity status, reporting compliance, evidence, verification, and management actions. [15][31][40] |
| **E. Do not proceed** | Not supported because documented reporting and monitoring weaknesses are substantial. | Not recommended, provided the concept is narrowed and conditional on stakeholder validation. [7][12][15][31] |

---

## SECTION 6: GAP ANALYSIS

### Proven gaps

1. **Financial reporting timeliness and quality.** Multiple authoritative sources document late, incomplete, or unreliable financial statements and reconciliations. [7][11][12][13][14]

2. **Acquittal and grant-monitoring weakness.** The Auditor-General found late acquittals, mismatches, and ineffective monitoring for SIP funds. [15]

3. **Oversight feedback loop.** Provincial performance reports were historically not consistently submitted, analysed, or followed by feedback. [31]

4. **Audit and oversight delay.** OAG reports and recent commentary identify audit backlogs and delayed oversight. [12][13][14]

### Probable gaps

1. **No verified common operational dashboard.** IFMS covers financial management, while DPLGA’s performance-reporting mandate is institutional rather than demonstrably a deployed province-wide dashboard. [16][17][21]

2. **Department-level operational visibility.** Corporate-plan frameworks expect quarterly divisional and individual performance review, but public evidence does not establish that provincial administrations have a reliable digital mechanism for this. [24][25][30][35][37]

3. **Frontline data capture.** DPM’s earlier PMS rollout identified connectivity, staffing, and data-entry constraints, suggesting that any new collection model must be simple and offline-tolerant. [40]

4. **Management-action tracking.** The evidence shows reporting and monitoring weaknesses, but does not directly measure whether corrective actions are tracked to closure. This remains a probable, not proven, gap.

### Unresolved gaps

- Whether provincial administrators regard reporting delay as a priority relative to staffing, funding, transport, and service-delivery constraints.
- Whether DPLGA already has a functioning digital reporting platform that could be extended.
- Whether IFMS can provide timely, authorised, province- and department-level data through supported interfaces.
- Whether provinces have enough devices, connectivity, and trained users for routine digital submission.
- Whether a dashboard would change decisions or merely create another reporting burden.

---

## SECTION 7: STAKEHOLDER ANALYSIS

| Stakeholder | Responsibilities / interest | Information needs | Potential benefit | Likely concerns | Role in pilot |
|---|---|---|---|---|---|
| Provincial Administrator | Overall administration, service delivery, coordination, accountability. | Consolidated departmental status, overdue reports, budget execution, project issues, corrective actions. | Earlier visibility and fewer manual briefings. | Additional reporting burden; data reliability; political sensitivity. | Executive sponsor and primary dashboard user. |
| Provincial departmental heads | Departmental plans, staff, budget, service delivery. | Departmental work-plan progress, staff/activity status, financial exceptions, outstanding actions. | Better departmental oversight and evidence-based reporting. | Data-entry workload; performance scrutiny. | Department-level configuration and verification. |
| Divisional managers | Delivery of divisional activities and supervision. | Unit activity status, deadlines, issues, evidence. | Clearer task and exception management. | Duplicate reporting; limited connectivity. | Primary approvers of frontline submissions. |
| Unit supervisors / officers | Operational delivery and record-keeping. | Simple task reporting, evidence capture, status updates. | Less manual paperwork; clearer accountability. | Connectivity, device access, digital skills, fear of misuse. | Data-entry and evidence-capture users. |
| Planning and monitoring officers | Corporate plans, MTDP alignment, M&E. | Indicator data, plan-versus-actual status, reporting compliance. | Better analysis and fewer spreadsheet consolidations. | Indicator quality and data definitions. | Indicator owner and pilot evaluator. |
| Finance and treasury officers | Budget, expenditure, reconciliations, financial statements. | Financial deadlines, reconciliation status, acquittals, IFMS data. | Improved deadline tracking and audit readiness. | Integration risk; control of financial data. | Data steward and IFMS integration counterpart. |
| ICT officers | Systems, connectivity, support, security. | User accounts, support incidents, integration requirements. | Structured support model. | Under-resourcing, security, maintenance burden. | Technical owner and deployment support. |
| DPLGA | Provincial performance monitoring, Section 114/119 reporting, PLLSMA support. | Standardised provincial performance and governance data. | Better national visibility and analysis. | Duplication of mandate; inconsistent provincial data. | Potential national sponsor or standards owner. |
| Department of Finance | IFMS, PFM, financial reporting. | Financial reporting compliance and expenditure data. | Better sub-national financial oversight. | Security, integration control, system ownership. | Mandatory integration partner for financial data. |
| DICT | Digital-government standards, cybersecurity, shared infrastructure. | Compliance with standards, secure architecture, interoperability. | Alignment with national digital transformation. | Unapproved shadow systems; security risk. | Standards and security approver. |
| OAG | Independent audit and assurance. | Reliable records, evidence, audit trail. | Better auditability and faster assurance. | Poor data quality; incomplete records. | Indirect beneficiary; requirements source. |
| Development partners | Public-sector reform, service delivery, PFM. | Measurable outcomes, sustainability, accountability. | Potential co-funding or technical assistance. | Sustainability and ownership risk. | Potential funder or technical partner, subject to formal engagement. |

---

## SECTION 8: PROPOSED PRODUCT CAPABILITIES

### Evidence-based requirements

These capabilities respond directly to documented problems:

1. **Reporting-deadline and submission register** — track financial statements, reconciliations, acquittals, Section 119 reports, and departmental reports; identify overdue items and responsible officers. This responds to documented late-reporting problems. [7][12][15][31]

2. **Evidence attachment and verification** — allow officers to attach documents, photographs, references, or supporting records; require supervisor review before an item is treated as verified. This responds to weak records and mismatched acquittal figures. [11][13][15]

3. **Work-plan and activity status** — record approved activities, responsible officer, due date, status, and completion evidence. This aligns with existing corporate-plan and annual-activity-plan practice. [24][25][30][35][37]

4. **Management-action register** — record decisions, corrective actions, owner, due date, status, and closure evidence. This addresses the weak feedback and follow-up loop identified in provincial performance reporting. [31]

5. **Hierarchical authorised views** — provincial administrator sees a provincial summary and authorised departmental detail; department heads see their departments; managers see their units; officers see and submit only relevant information. This is consistent with the management model proposed in the handover, but must be configured to each province’s actual structure.

6. **Offline-capable submission** — allow basic forms and evidence to be captured offline and synchronised later. This responds to documented connectivity and infrastructure constraints. [29][40]

7. **Audit trail** — record who created, edited, approved, or changed a submission and when. This supports auditability and reduces disputes about reported figures. [11][13]

### Proposed but not yet validated features

These should not be treated as requirements until stakeholder research confirms demand:

- Automated performance scores.
- Predictive analytics or AI-generated assessments.
- Full HR, payroll, procurement, asset, or health-information modules.
- Public-facing dashboards.
- Cross-province benchmarking.
- Automated integration with all national systems.
- Mobile-native applications.

### Dashboard model

A minimum dashboard should distinguish:

- **Verified results:** approved by an authorised supervisor and supported by evidence.
- **Self-reported status:** submitted but not yet verified.
- **Overdue or missing data:** no submission or incomplete reporting.
- **Financial indicators:** sourced from authorised IFMS or finance-office reporting, not manually re-entered.
- **Management actions:** open, overdue, and closed corrective actions.

The system should avoid a single simplistic “province performance score.” Complex departmental performance can be misrepresented by composite scores, especially where data quality, staffing, and service conditions differ. The evidence instead supports transparent status, timeliness, completeness, evidence coverage, and exception lists. [3][31][40]

---

## SECTION 9: PERFORMANCE INDICATORS

### Officially grounded indicators

The following are grounded in existing reporting obligations or documented government processes. Exact definitions must be agreed with DPLGA, Finance, and the pilot province.

| Indicator | What it measures | Why it matters | Likely source | Frequency | Status |
|---|---|---|---|---|---|
| Financial statement submission status | Whether required financial statements were submitted by deadline. | Late statements delay audit and oversight. [7][12][13] | Finance office / OAG / IFMS-derived status. | Monthly or annual, by requirement. | Officially grounded. |
| Bank reconciliation status | Whether required reconciliations are complete and current. | Weak reconciliations undermine financial control. [7][11] | Finance office / IFMS-derived status. | Monthly. | Officially grounded. |
| SIP acquittal submission rate | Percentage of required PSIP/DSIP/LLGSIP acquittals submitted on time. | Late acquittals impair monitoring and funding. [15] | Finance / implementing department. | Per funding cycle. | Officially grounded. |
| Acquittal variance | Difference between disbursed and acquitted/reported amounts. | Mismatches indicate weak control or reporting. [15] | Finance / acquittal records. | Per acquittal. | Officially grounded. |
| Section 119 report status | Whether governance/performance reports were submitted and accepted. | Existing statutory performance-reporting channel. [21][31] | DPLGA / provincial administration. | Annual or as required. | Officially grounded. |
| Annual activity plan completion | Percentage of approved activities completed or progressing as planned. | Links corporate plans to delivery. [24][25][35][37] | Departmental work plans. | Monthly or quarterly. | Existing process; digital measurement would be new. |
| Report timeliness | Percentage of departmental reports submitted by deadline. | Measures reporting discipline. [7][15][31] | PAIPS submission records. | Monthly. | PAIPS-proposed operational measure. |
| Evidence coverage | Percentage of completed activities with required evidence attached. | Distinguishes assertion from verifiable performance. [11][13][15] | PAIPS evidence attachments. | Monthly or quarterly. | PAIPS-proposed data-quality measure. |
| Outstanding management actions | Number and age of open corrective actions. | Makes follow-up visible. [31] | PAIPS action register. | Weekly or monthly. | PAIPS-proposed management measure. |
| Overdue decisions | Decisions awaiting action beyond an agreed threshold. | Supports accountability. | PAIPS action register. | Weekly or monthly. | PAIPS-proposed management measure. |

### Indicators requiring caution

- **Budget execution percentage:** useful, but must be sourced from authorised financial systems and interpreted with commitment controls, timing, and procurement realities.
- **Service-delivery output indicators:** should come from sector systems or agreed departmental definitions; PAIPS should not invent national service indicators.
- **Staffing indicators:** require DPM, provincial HR, and privacy-authority clearance; should be aggregate and authorised only.
- **Composite performance scores:** not recommended initially because they can conceal data-quality and contextual differences. [3][31][40]

---

## SECTION 10: COMPARABLE INTERNATIONAL SYSTEMS

Publicly verifiable, directly comparable government deployments in Pacific countries are limited in the available research. The following lessons are therefore drawn cautiously from PNG’s own systems and broader public-sector management practice.

### PNG-specific lessons

1. **IFMS demonstrates that central platforms can be extended to provinces, but implementation is not the same as routine use.** IFMS moved from national agencies to provincial finance offices and later to wider provincial and local-level deployment, with government communications describing full provincial connectivity and a cloud migration in 2025. [16][17][22][23]

2. **Digital performance systems need dedicated data-entry capacity.** DPM’s PMS rollout encountered unavailable staff to enter data, confusion over KRAs/KPIs, connectivity problems, and funding constraints. [40]

3. **Reporting obligations alone do not ensure compliance.** The SIP audit found that provinces and districts did not always feel obliged to meet reporting timetables, and that weak enforcement contributed to poor compliance. [15]

4. **Feedback matters.** The ADB found that provincial performance reports were rarely analysed and seldom received feedback, weakening the value of reporting. [31]

### International design lessons

For a dispersed, lower-connectivity public administration, the relevant lessons are:

- Start with a small number of mandatory, high-value reports.
- Use role-based access and approval workflows.
- Make evidence capture mandatory for completion claims.
- Support offline capture and later synchronisation.
- Integrate financial data rather than re-entering it.
- Track overdue items and corrective actions visibly.
- Avoid vanity dashboards and unexplained composite scores.
- Assign a named business owner, data steward, and ICT support function in each participating administration.

These are implementation lessons, not claims that a particular foreign system should be copied.

---

## SECTION 11: SECURITY, GOVERNANCE AND LEGAL CONSIDERATIONS

### Applicable framework

The **Digital Government Act 2022** applies to public bodies and establishes the basis for digital government, electronic data management, digital transformation officers, cybersecurity arrangements, a Government Private Network, and a central electronic data repository. [28]

The **Digital Government Plan 2023–2027** is required under the Act and sets out a path for digital services, resilient cyber environments, and digital-service standards. [1][4]

DICT’s **Government Data Standards, Specifications and Guidelines 2025** state that all public bodies must comply with the instrument, manage electronic data under Part IV of the Digital Government Act, apply appropriate security measures including access controls, encryption, and firewalls, and protect personal and sensitive data. The standards also specify data minimisation, data-protection officers, encryption, multi-factor authentication for privileged access, penetration testing, and secure backups stored in PNG. [18]

### Mandatory versus recommended safeguards

**Likely mandatory or standards-driven:**

- Compliance with the Digital Government Act 2022 and DICT data standards. [18][28]
- Access controls, encryption, and protection against unauthorised access or disclosure. [18]
- Data minimisation and lawful processing of personal data. [18]
- Appointment of a data-protection officer where required by the standards. [18]
- Secure privileged access, including MFA. [18]
- Secure backups, including backups stored in PNG under the cited standards. [18]
- Alignment with the Government Technology Stack and ICT policies. [6]

**Recommended operational safeguards:**

- Role-based access tied to verified organisational position.
- Separate technical-administrator access from business-data access.
- Approval workflow before data enters official management reporting.
- Immutable or tamper-evident audit logs.
- Version control for approved reports.
- Data-quality checks and exception queues.
- Tested disaster-recovery procedures.
- Formal data-sharing agreements before IFMS or other system integration.

### Unresolved legal and governance questions

- Whether a provincial performance platform must be hosted in the Government Private Network or an approved government cloud environment.
- Which agency is the lawful data custodian for cross-departmental provincial performance data.
- Whether IFMS data can be shared with a third-party dashboard and under what data-sharing agreement.
- Whether personal data, including staff performance or disciplinary information, may be included.
- How long submitted evidence and reports must be retained under public-records requirements.
- Whether procurement must follow a particular ICT procurement pathway or DICT approval process.
- Whether the platform requires a security assessment before production deployment.

These require formal confirmation from DICT, Department of Finance, DPLGA, the Provincial Attorney-General or legal adviser, and qualified PNG legal counsel.

---

## SECTION 12: TECHNICAL AND FINANCIAL FEASIBILITY

### Implementation approaches

| Approach | Advantages | Risks | Assessment |
|---|---|---|---|
| Centralised web platform | Common data model, easier national reporting, consistent controls. | Connectivity dependency, duplication of IFMS/DPLGA functions, higher hosting and maintenance cost. | Suitable only after integration and governance are confirmed. |
| Modular platform integrated with existing systems | Avoids duplicate financial data; aligns with national architecture. | Integration complexity; requires API/extract access and data-sharing approval. | Preferred strategic direction. |
| Offline-capable web application | Works with intermittent connectivity; supports field and remote offices. | Synchronisation conflicts, device management, support burden. | Necessary for frontline data capture. |
| Hybrid reporting layer plus shared dashboard | Lowest duplication; uses IFMS for finance and PAIPS for operational reporting. | Depends on data quality and system access. | Recommended pilot approach. |

### Technical considerations

- **Connectivity:** cannot be assumed. Earlier IFMS rollout explicitly identified unproven or absent provincial communication infrastructure, and DPM identified connectivity problems during PMS rollout. [29][40]
- **Offline-first reporting:** should be treated as a core requirement for frontline and remote use, not an optional feature.
- **Data migration:** should be minimal in a pilot; start with current-period work plans and reporting obligations rather than historical back-capture.
- **Integration:** IFMS is the most important potential integration, but no public evidence was found confirming a documented public API or approved extract mechanism for provincial dashboards. This is a critical pre-pilot question. [16][17]
- **Support:** each province needs a named administrator, departmental data stewards, and ICT support arrangements.
- **Scalability:** a pilot should use configurable departments, roles, and forms rather than hard-coded province-specific workflows.

### Financial feasibility

No reliable public cost estimate for a PNG provincial performance platform was identified. Therefore, no development budget, licence cost, or operating cost is asserted.

Cost drivers that must be estimated during pilot definition include:

- Government-approved hosting or Government Private Network services.
- Integration with IFMS or authorised finance reporting.
- Offline-capable application development and maintenance.
- Security testing, audit logging, backup, and recovery.
- Training, change management, and provincial ICT support.
- Connectivity and devices where government offices lack them.
- Multi-year support, not only initial build cost.

Open-source software may reduce licence costs, but it does not remove hosting, security, integration, support, training, or compliance costs. Free public cloud services should not be assumed suitable for sensitive government records.

---

## SECTION 13: ADOPTION AND COMMERCIAL FEASIBILITY

### Public value

The public-value case is credible where the system reduces late reporting, improves evidence quality, makes overdue actions visible, and strengthens accountability for provincial funds and service-delivery commitments. The documented problems in financial reporting, SIP acquittals, and provincial performance feedback provide a practical basis for this case. [7][12][15][31]

### Commercial viability

The commercial opportunity is **credible but unproven**.

Potential buyers include:

- Individual provincial administrations.
- DPLGA, if it seeks a national provincial performance-reporting capability.
- Department of Finance, if the solution complements IFMS reporting and PFM oversight.
- DICT, if delivered as part of a broader digital-government programme.
- Development partners funding public-sector reform, PFM, or service-delivery programmes.

However, no current tender, contract, budget line, or confirmed government demand for this specific product was identified in the available public evidence. The existence of an administrative problem does not by itself establish a procurement opportunity.

### Adoption barriers

- Competing priorities and limited provincial budgets.
- Connectivity and device constraints. [29][40]
- Limited ICT and data-entry capacity. [40]
- Resistance to additional reporting.
- Data-quality concerns and possible misreporting.
- Overlap with DPLGA, Finance, DPM, and sector-agency mandates.
- Procurement, security, and data-governance approvals.
- Sustainability after donor-funded implementation.

### Most viable delivery model

The most viable route is a **government-sponsored, province-led pilot**, followed by a decision on whether DPLGA or another central agency should adopt it as a standard capability. A vendor-led multi-province rollout without a national sponsor would face high adoption and procurement risk.

---

## SECTION 14: PILOT RECOMMENDATION

### Proposed scope

A limited pilot should test whether a narrow reporting and management-action layer improves timeliness, completeness, and visibility of departmental performance.

**Included capabilities:**

1. Departmental work-plan and activity register.
2. Monthly or fortnightly activity-status submissions.
3. Evidence attachment for completed activities.
4. Supervisor verification and rejection/correction workflow.
5. Overdue report and action alerts.
6. Departmental and provincial dashboards.
7. Management-action register.
8. Optional read-only financial-status indicators, only if authorised IFMS or finance-office data can be supplied.

**Excluded from pilot:**

- Payroll, HR case management, procurement, asset management, health records, or citizen-facing services.
- Replacement of IFMS.
- Replacement of statutory Section 114/119 reporting.
- AI-based scoring or automated performance judgements.
- Multi-province rollout before pilot evaluation.

### Likely participants

No province should be named as a confirmed pilot partner. The appropriate participants are:

- One provincial administration that volunteers and has an engaged provincial administrator.
- Its planning, finance, ICT, and at least two operational departments.
- DPLGA as observer or potential standards owner.
- Department of Finance for any IFMS-related data access.
- DICT for standards, security, hosting, and interoperability clearance.

### Evidence needed before implementation

- Written interest from the provincial administrator.
- Named business owner and departmental champions.
- Current reporting templates, calendars, and examples.
- List of departments, divisions, units, and authorised users.
- Confirmation of devices, connectivity, and support capacity.
- Agreement on 8–12 initial indicators.
- Data-sharing and security approval for any IFMS-derived data.
- DICT alignment confirmation.
- A baseline measurement of current reporting timeliness and completeness.

### Success measures

- Reduction in late departmental reports relative to baseline.
- Increase in complete submissions.
- Percentage of completed activities with acceptable evidence.
- Percentage of overdue actions closed within agreed time.
- User adoption among intended officers and supervisors.
- Administrator-reported usefulness in management meetings.
- No material security, privacy, or data-integrity incident.

### Conditions that should prevent a pilot

Do not proceed if:

- No provincial administration provides written interest and a business owner.
- DPLGA or Finance identifies an existing system that should be extended instead.
- DICT cannot confirm an acceptable hosting, security, and interoperability pathway.
- The province cannot identify users, devices, or connectivity arrangements.
- The pilot would require duplicate entry of IFMS financial data.
- There is no baseline against which improvement can be measured.

---

## SECTION 15: FINAL RECOMMENDATION

**Recommendation: Conduct further targeted stakeholder research, then pursue a narrow integration-first pilot.**

The evidence supports further development of the concept, but not immediate construction of a broad PAIPS platform.

The defensible path is:

1. Confirm with DPLGA whether its stated provincial performance-reporting initiative is an operational system, a planned system, or a reporting process requiring digitisation. [21]
2. Confirm with Department of Finance whether authorised IFMS data or reports can support a provincial dashboard without duplicate data entry. [16][17]
3. Confirm with DICT the required hosting, security, interoperability, identity, and data-governance pathway. [1][6][18][28]
4. Secure one willing provincial administration and establish a baseline.
5. Pilot only reporting compliance, activity status, evidence, verification, and management actions.
6. Evaluate against timeliness, completeness, evidence coverage, adoption, and action-closure measures.

This approach follows **Option B/D**: integrate where possible; otherwise build only the narrow operational-reporting layer that existing systems do not demonstrably provide.

---

## SECTION 16: UNRESOLVED QUESTIONS

1. Does DPLGA already operate a provincial performance-reporting system, and can it be extended?
2. Can IFMS provide authorised, timely, department- or province-level data through a supported interface?
3. What are current Section 119 report submission rates, quality levels, and feedback practices?
4. Which provinces have reliable connectivity, devices, ICT staff, and trained users?
5. What reporting workflows do provincial administrators and departmental heads actually use today?
6. Would officers and supervisors use a digital reporting tool routinely?
7. Which indicators do DPLGA, Finance, and provincial administrations formally recognise?
8. What are the legal requirements for hosting, records retention, data residency, and cross-system data sharing?
9. Is there an active government budget, procurement pathway, or development-partner programme that could fund a pilot?
10. Would a pilot improve decisions and accountability, or simply add another reporting channel?

---

## SECTION 17: SOURCE REGISTER

| Source | Institution | Date / period | Relevant sections | URL | Significance |
|---|---|---|---|---|---|
| Digital Government Plans | Department of ICT, PNG | Current page; Plan covers 2023–2027 | 3, 5, 11, 12 | https://www.ict.gov.pg/digital-government-plans/ | Confirms Digital Government Plan 2023–2027 and its basis under the Digital Government Act. [1] |
| Digital Government Plan 2023–2027 | DICT, PNG | 2023–2027 | 3, 5, 11, 12 | https://www.ict.gov.pg/Digital%20Govt%20Plan%202023-2027/Digital%20Government%20Plan%202023-2027%20-%20Final%20Version.pdf | Identifies IFMS/eFinance, M&E framework, digital-service standards, and DICT sponsorship. [4] |
| Digital Transformation | DICT, PNG | Current page | 3, 5, 11 | https://www.ict.gov.pg/digital-government/ | Confirms DICT coordination across national, provincial, and district levels and ICT project-alignment requirements. [6] |
| Government Data Standards, Specifications and Guidelines 2025 | DICT, PNG | 2025; compliance dates stated in document | 11, 12 | https://www.ict.gov.pg/Digital%20Standards/Government%20Data%20Standards,%20Guidelines%20and%20Specification%20%5B3rd%20draft%5D.pdf | Key source for data governance, security, privacy, encryption, MFA, and PNG-hosted backups. [18] |
| Integrated Financial Management System | Department of Finance, PNG | Project page; historical rollout narrative | 3, 5, 12 | https://www.finance.gov.pg/projects/ifms/ | Documents IFMS purpose and provincial/district rollout history. [16] |
| IFMS training and implementation presentation | Department of Finance / DICT | October 2024 | 5, 12 | https://www.ict.gov.pg/wp-content/uploads/2024/10/13.1-DoF-IFMS-ppp-DICT-Presentation-Oct-2024.pptx | Reports IFMS implementation across national departments, provincial governments, DDAs, LLGs, and PHAs. [17] |
| Chief Secretary speech on TechnologyOne contract | Prime Minister and National Executive Council | 21 October 2026 | 5, 12 | https://www.pmnec.gov.pg/speech-by-the-chief-secretary-to-the-government-on-the-signing-of-the-contract-between-the-state-and-technologyone/ | Describes IFMS as fully realised across provinces and announces a K26 million three-year support/upgrade agreement. [22] |
| Prime Minister statement to Parliament | Prime Minister and National Executive Council | 19 October 2026 | 5, 12 | https://www.pmnec.gov.pg/statement-to-the-national-parliament-by-prime-minister-hon-james-marape-gcl-mp/ | States IFMS cloud migration was completed in May 2025. [23] |
| Wings and Divisions | DPLGA, PNG | Page updated 8 March 2026 | 3, 5, 7, 8 | https://www.dplga.gov.pg/wings-and-divisions/ | Confirms DPLGA reporting-framework, Section 114/119, and provincial performance-reporting responsibilities. [21] |
| DPLGA Corporate Plan 2014–2017 | DPLGA, PNG | 2014–2017 | 3, 5, 8, 9 | https://www.dplga.gov.pg/wp-content/uploads/2022/06/DPLGA_CP2014-2017.pdf | Documents minimum standards, performance monitoring, quarterly review, and reporting to CACC. [24] |
| DPLGA Corporate Plan 2018–2022 | DPLGA, PNG | 2018–2022 | 3, 5, 8, 9 | https://www.dplga.gov.pg/wp-content/uploads/2022/06/DPLGA_CP2018-2022.pdf | Documents corporate performance management, Section 119 coordination, and provincial/LLG monitoring. [25] |
| Provincial Performance Improvement Initiative | Asian Development Bank | Programme began 2004; publication reflects programme experience | 4, 5, 6, 8, 10 | https://www.adb.org/sites/default/files/publication/29197/provincial-performance-improvement-initiative.pdf | Documents weak provincial performance-report submission, limited analysis/feedback, and DPLGA monitoring developments. [31] |
| PCaB II-B Project Document | UNDP | Endorsed 2016; describes preceding reporting conditions | 4, 5, 6 | https://info.undp.org/docs/pdc/Documents/PNG/PCAB%20II-B%20Project%20Document%20FINAL%20endorsed%20by%20SC%20on%209%20Dec%202016.docx | Documents severe delays in provincial/district financial statements and bank reconciliations, plus an electronic M&E response. [7] |
| Part 3 Report of the Auditor-General 2014 | Office of the Auditor-General, PNG | 2014 audit reporting | 4, 5, 11 | https://ago.gov.pg/wp-content/uploads/2020/04/Part-3-2014-FOR-PRINTING.pdf | Documents provincial financial-management weaknesses and audit delays. [13] |
| Part 3 Report of the Auditor-General 2010 | Office of the Auditor-General, PNG | 2010 audit reporting | 4, 5, 11 | https://ago.gov.pg/wp-content/uploads/2020/04/Part_III_2010-1.pdf | Documents inaccurate statements, weak competency, record weaknesses, and audit backlogs. [14] |
| SIP Report 2013–2016 | Office of the Auditor-General, PNG | Audit covers 2013–2016 | 4, 5, 6, 8, 9 | https://ago.gov.pg/wp-content/uploads/2021/07/SIP-Report-2013-2016.pdf | Documents late acquittals, mismatches, weak monitoring, and capacity constraints. [15] |
| Review of the IFMS Project | Office of the Auditor-General, PNG | Earlier IFMS project period | 4, 5, 12 | https://ago.gov.pg/wp-content/uploads/2020/04/Report_No5_IFMS.pdf | Documents earlier provincial connectivity and rollout constraints. [29] |
| Papua New Guinea’s fiscal decentralisation: A way forward | Lowy Institute | 3 March 2024 | 4, 6 | https://www.lowyinstitute.org/publications/papua-new-guinea-s-fiscal-decentralisation-way-forward | Summarises provincial audit, reporting non-compliance, and financial-management concerns. [8] |
| Non-submission of financial statements a concern | The PNG Bulletin, reporting Auditor-General remarks | 21 October 2026 | 4, 6 | https://thepngbulletin.com/news/finance/non-submission-of-financial-statements-a-concern/ | Current indication that financial-statement non-submission remains a concern; secondary source requiring OAG-report verification. [12] |
| Parliamentary committee report on provincial accounts | National Parliament of PNG | Covers 2005–2007 audit period | 4, 5 | http://downloads.pngiportal.org.s3.amazonaws.com/documents/PAC2009k.pdf | Historical evidence of unreliable provincial financial statements and audit delays. [11] |
| Promoting Good Governance in the Public Service | Public Services Commission, PNG | Corporate Plan 2014–2018 | 3, 8, 9 | https://www.psc.gov.pg/wp-content/uploads/2022/07/PSC-CORPORATE-PLAN-2014-2018.pdf | Shows tiered monitoring and reporting model linking individual and organisational accountability. [30] |
| Second Quarter Newsletter | Department of Personnel Management, PNG | Pre-2018 period | 4, 5, 10, 12 | https://www.dpm.gov.pg/wp-content/uploads/2019/07/Second-Quarter-Newsletter.pdf | Documents PMS rollout barriers: connectivity, staffing, funding, KRA/KPI confusion, and legal interruption. [40] |
| PM Marape launches Public Service Payroll Office | Prime Minister and National Executive Council | 16 October 2026 | 3, 5, 13 | https://www.pmnec.gov.pg/pm-marape-launches-public-service-payroll-office-calls-for-digital-id-ict-and-kpi-driven-reform/ | Current policy direction on digital ID, ICT/AI tools, KPI-driven performance management, and provincial rollout. [38] |
| Papua New Guinea — Digital Economy | U.S. International Trade Administration | 18 September 2024 | 11 | https://www.trade.gov/country-commercial-guides/papua-new-guinea-digital-economy | Notes data-protection framework limitations, cybersecurity strategy, and the 2021 Finance Department IFMS cyber incident. [19] |
| Overview of PNG Digital Government Act 2022 | PLN | 3 August 2022 | 11 | https://www.pln.com.pg/single-post/overview-of-papua-new-guineas-digital-government-act-2022/ | Summarises the Act’s scope, DICT role, digital transformation officers, cyber centre, and data repository. [28] |
| Papua New Guinea Delivering Public Services | World Bank | Older report | 4, 8, 9 | https://documents1.worldbank.org/curated/en/203621468775145061/pdf/multi-page.pdf | Contextual evidence on input-based management and weak results orientation. [3] |

---

## SECTION 18: RESEARCH AUDIT SUMMARY

### Completed

- Institutional mapping of DPLGA, Finance, DICT, DPM, OAG, and provincial reporting responsibilities.
- Identification of documented financial-reporting, acquittal, audit, and performance-feedback problems.
- Mapping of IFMS, Section 114/119 reporting, corporate planning, PMS, SIP acquittal monitoring, and digital-government standards.
- Initial gap analysis and evaluation of five implementation options.
- Initial stakeholder, indicator, security, feasibility, adoption, and pilot analysis.

### Partially completed

- Province-level workflow and readiness assessment: requires interviews and document requests.
- Current IFMS integration capability: requires technical and governance confirmation.
- Current DPLGA reporting-system status: requires direct enquiry.
- International comparable-system review: limited by availability of verifiable Pacific-government deployment evidence.
- Commercial opportunity assessment: no active tender, budget, or confirmed buyer was identified.

### Important unavailable sources

- Current OAG annual report and provincial audit status.
- Current DPLGA Section 119 submission database or annual report.
- IFMS technical documentation, API specification, or authorised reporting extracts.
- Provincial corporate plans, annual reports, and ICT inventories.
- DICT approval procedures for government-hosted applications.
- Current procurement opportunities and contract registers.

### Claims requiring verification

- That provincial reporting delays persist uniformly across all provinces.
- That DPLGA’s performance-reporting system is not already adequate.
- That IFMS can supply dashboard-ready data.
- That provinces have sufficient connectivity and devices.
- That administrators and departmental heads want an additional digital reporting tool.
- That the 2026 news report on financial-statement non-submission accurately reflects the underlying OAG findings.

### Current facts versus historical evidence

- **Current:** DPLGA’s stated reporting mandate, DICT’s digital-government framework, IFMS’s reported national rollout and cloud migration, and the 2026 policy emphasis on KPI-driven public-service reform. [1][6][17][21][22][23][38]
- **Historical but still material:** provincial financial-statement failures, SIP acquittal delays, audit backlogs, weak performance-report feedback, and earlier PMS adoption barriers. [7][11][13][14][15][31][40]

### Key assumptions

- Provincial administrations have heterogeneous structures and capabilities.
- Financial data should come from IFMS or authorised finance reporting, not be re-entered.
- A pilot must be offline-tolerant and role-based.
- Statutory reporting remains the authoritative compliance channel.
- No province has agreed to participate.

### Recommended next research actions

1. Request current DPLGA Section 119 reporting guidance, submission statistics, and system documentation.
2. Request IFMS integration, reporting, API, and data-access information from Department of Finance.
3. Request DICT confirmation of hosting, security, identity, interoperability, and procurement requirements.
4. Identify two or three provincial administrations for confidential workflow interviews.
5. Collect current provincial reporting templates, calendars, and examples of late or incomplete reports.
6. Establish a reporting baseline before any pilot is approved.

---

# REQUIRED FINAL ASSESSMENT

| # | Question | Answer | Evidence and reasoning |
|---|---|---|---|
| 1 | Is the administrative problem documented? | **Yes, partially** | Late financial statements, weak records, late SIP acquittals, audit delays, and weak provincial performance-report feedback are documented by OAG, Parliament, ADB, UNDP, and Lowy Institute. [7][8][11][13][14][15][31] |
| 2 | Is the problem relevant to provincial administrations in PNG? | **Yes** | The evidence concerns provincial governments, district administrations, LLGs, provincial finance offices, and DPLGA’s provincial monitoring mandate. [7][15][21][31] |
| 3 | Do relevant government systems already exist? | **Yes** | IFMS, Section 114/119 reporting, corporate-plan/annual-performance reporting, SIP acquittal processes, PMS, and DICT digital-government frameworks already exist. [16][17][21][24][25][28][40] |
| 4 | Is a significant capability gap demonstrated? | **Partially** | Financial and acquittal reporting gaps are well documented. A gap in integrated departmental operational reporting is probable but not yet demonstrated at province level. [15][16][21][31] |
| 5 | Would a new integrated dashboard add measurable value? | **Unresolved / potentially yes if narrow** | Value is plausible for reporting compliance, evidence, and action tracking, but must be demonstrated against a baseline. A broad dashboard is not yet justified. [15][31][40] |
| 6 | Is integration preferable to developing a new system? | **Yes, as the default** | IFMS should remain the financial system of record; DPLGA reporting should remain the statutory channel. Any new component should integrate with or extend these systems. [16][17][21] |
| 7 | Is a pilot justified? | **Yes, conditionally** | A narrow pilot is justified only with a willing province, named owner, baseline data, DICT/Finance/DPLGA engagement, and no duplication of IFMS. [15][18][21][31] |
| 8 | Is there a credible route to government adoption? | **Partially** | DPLGA, Finance, and DICT have relevant mandates, and national policy supports digital public-service reform. But no confirmed sponsor, budget, procurement route, or user commitment was found. [1][6][17][21][38] |
| 9 | Is the commercial opportunity credible? | **Partially** | Public value is credible; commercial viability is unproven because no active demand signal, tender, budget, or confirmed buyer was identified. |
| 10 | What should happen next? | **Conduct targeted stakeholder research; prepare a conditional pilot** | Confirm DPLGA/Finance/DICT positions, secure one willing province, establish a baseline, and scope only a narrow reporting-and-action pilot. |

---

## COMPLETION SUMMARY FOR CHATGPT REVIEW

1. **Strongest evidence of an unmet need:** documented late or missing provincial financial statements and reconciliations, late SIP acquittals, audit backlogs, and historically weak submission, analysis, and feedback of provincial performance reports. [7][12][13][14][15][31]

2. **Most important existing systems:** IFMS; DPLGA Section 114/119 reporting; provincial corporate plans and annual performance reports; DPLGA performance-monitoring mandate; DPM performance-management processes; and DICT’s Digital Government Act, Plan, and data standards. [1][4][16][17][21][24][25][28][40]

3. **Most significant remaining gaps:** integrated departmental operational reporting, frontline data capture, evidence-based verification, management-action follow-up, and timely authorised visibility for administrators—subject to provincial validation. [21][24][25][31][40]

4. **Recommended product or integration approach:** pursue **Option B/D**—an integration-first, narrowly scoped departmental reporting, evidence-verification, and management-action layer; integrate with IFMS where authorised; do not replace IFMS or statutory reporting. [16][17][21][31]

5. **Main unanswered questions:** current DPLGA system status; IFMS integration/access; current provincial reporting workflows and submission rates; connectivity/device readiness; legal hosting and data-sharing requirements; and confirmed government demand or funding.

6. **Five most important sources:**  
   - ADB, *Provincial Performance Improvement Initiative* [31]  
   - OAG, *SIP Report 2013–2016* [15]  
   - UNDP, *PCaB II-B Project Document* [7]  
   - DPLGA, *Wings and Divisions* and corporate plans [21][24][25]  
   - Department of Finance / DICT, IFMS implementation materials and Digital Government Plan [4][16][17]

**Research status:** complete for independent verification and review. No application code, database schema, technology-stack decision, GitHub modification, or pilot-partner commitment has been made.
