# Rev 3 → Rev 4 Revision Notes

**Document:** `ID-G-BU-GG0-PRO-GN-00-0053` — MEPG Integrated Planning & Scheduling Guideline
**Owner org:** 514018 – Asset Management Corridor, Medco E&P Grissik Ltd (MEPG)
**Comparison basis:** Rev 3 (Issued for Use, 22 Nov 2024 — source `v12.txt`) vs Rev 4 working draft (tracked changes accepted — source `v14.txt`)
**Prepared by:** Agent A — Revision Review & Change Log
**Status of source:** The Rev 4 source is a *working draft*. It contains author placeholders (some in Indonesian), duplicated section blocks, and a stale Table of Contents. These are flagged throughout as drafting artefacts requiring closure before issue.

---

## Executive Summary

Rev 4 is a structural rebuild driven principally by two corporate documents that did not exist when Rev 3 was issued: the corporate **IBP Guideline GN-3005 Rev 1** (signed Jan 2025, ~2 months after Rev 3) and the **Corridor Ops Procedure GN-3007 Rev 0** (IFU Jan 2026, ~14 months after Rev 3). Rev 3 pre-dates and does not reference either document; Rev 4 aligns the BU guideline to both, and adds explicit cross-references to the FDP (GL-001) and ADP (GL-002) guidelines. The change is therefore forced alignment to a changed corporate framework, not correction of neglect.

**Biggest structural changes**
- The planning-horizon model is rebuilt from a 5-tier legacy set (BU Life/ADP · 10-Year/LTP · 24-Month · 30/90-Day · Plan Control) into a full 8-tier system: **FDP → ADP → LTP (Outer-Years + 24-Month) → 12M → 90D → 30D → 7D**. Net-new horizons are **12-Month (12M)** and **7-Day (7D)**; **FDP** is newly named as an explicit upstream input.
- Rev 3 Section 2 ("Planning System") is split and expanded into three parts in Rev 4: **Philosophy & Principles**, a new major section **Planning System & Horizon** (horizon breakdown, activity-based planning processes, work-process flow, tools & references), and **Roles, Approvals & Governance**.
- The body is renumbered/retitled, but the **Table of Contents was not updated** and still shows the Rev 3 1–9 skeleton — a conflict between ToC and body (see Open Items).

**Biggest governance improvements**
- Net-new **stage-gate governance**: Gate 1 = 90D (planning candidates, not commitment), Gate 2 = 30D (execution commitment, plan declared **Frozen**), Gate 3 = 7D (weekly execution authorisation) — consistent with GN-3007's 90D/30D/7D Forum-Gate model.
- **Table 1 (Plan Approval & Administration)** rebuilt to eight horizons with explicit **Approval Authority** column, introducing **VP Operations** for 12M/90D and **OIM/OM** and **Superintendent** for 30D/7D, replacing Rev 3's "Field Manager / Managers".
- New **Table 2 (Meeting Cadence)** codifying forum cadence: FDP/ADP annual, LTP bi-annual, 12M quarterly, 90D monthly (Gate 1), 30D monthly (Gate 2/Frozen), 7D weekly (Gate 3).

**Biggest planning improvements**
- New **Section 1.1 Table 1 (Objectives)**: the 11 Rev 3 prose objectives are recast as a structured table pairing each objective with an **Expected Behaviour (how)** and **Organizational Value (why)**.
- **Scope** widened and re-expressed around the new horizons, adding **FDP** and **outer-years LTP**, and explicitly deferring function-specific execution to the respective procedures.
- New **Activity-Based Planning Processes** sub-section (Maintenance, Project, Shutdown, Early Operations) and a common six-stage **Work Process/Flow**.
- New **Tools, System & References** section (IBP module in BPM, SAP, ARIS, MCRS, SharePoint, WDDP, MPEP, GPT for STPF) and explicit **AACE RP 37R-06** schedule-level mapping re-based onto the new horizons.

**Biggest operational improvements**
- New **OPAA (Operations Planning and Activities Assurance)** role replaces the Rev 3 "Planning Group / P&S Steering Committee" as the coordinator of 12M/90D/30D.
- Expanded "Managing the Plans" spine with placeholder frameworks for **Opportunity Identification**, **Escalation Path**, **Break-in management** for the Frozen 30D plan, **Version Control / Source of Truth**, and **Reporting Cadence & Ownership** — all net-new intent, though several remain unwritten placeholders in the draft.

---

## Section-by-Section Change Log

Categories: Added · Updated · Removed · Restructured · Clarification · Governance Update

### 1. Introduction

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 1.1 Concept and Objectives of Integrated Planning (from Rev 3 §1.1) |
| **Old (Rev 3)** | Purpose paragraph followed by an 11-item *prose* bullet list of objectives; closing paragraph on consistency across functions. |
| **New (Rev 4)** | Same purpose paragraph, but the 11 objectives are recast as **Table 1 – Integrated Planning Objectives, Expected Behaviours, and Organizational Value**, each objective paired with "Expected Behaviour (how)" and "Organizational Value (why)". Adds a monitoring statement tying objectives to the KPI section. |
| **Reason** | Clarity and traceability; aligns objectives to measurable behaviour/value consistent with the IBP performance-management intent (GN-3005). |
| **Reference** | Rev 4 §1.1, Table 1; GN-3005 Rev 1. |
| **Category** | Restructured / Clarification |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 1.2 Scope (from Rev 3 §1.2) |
| **Old (Rev 3)** | Scope listed: BU Life/ADP, 10-Year/LTP, Medium/Tactical/24-Month, Short-Term/Operational 30-90 Day, and detailed operational-level planning. |
| **New (Rev 4)** | Scope re-expressed around: **ADP; FDP; LTP (24-month + outer-years); Short-term planning (12M, 90D, 30D, 7D)**. Adds statement that function-specific execution remains governed by respective procedures while aligning to this guideline. |
| **Reason** | Alignment to the new horizon system and to GN-3005 (LTP/IBP), GN-3007 (operational horizons), GL-001 FDP, GL-002 ADP; introduces 12M and 7D and the FDP as explicit scope items. |
| **Reference** | Rev 4 §1.2; GN-3005; GN-3007; GL-001; GL-002. |
| **Category** | Updated / Added |

### 2. Philosophy & Principles (Rev 3 "Planning System", §2)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Section 2 retitled **"Philosophy & Principles"** (Rev 3 title was "Planning System"). |
| **Old (Rev 3)** | §2 "Planning System" contained 2.1 Philosophy, 2.2 Strategy, 2.3 Work Process, 2.4 Plan Ownership & Approval, 2.5 Roles. |
| **New (Rev 4)** | Retitled and narrowed to philosophy and principles only. The work process, ownership/approval, and roles content is relocated to the new Sections 3 and 4 (see Restructure note below). |
| **Reason** | Separation of principles from the (now expanded) planning-system mechanics; clearer document architecture. |
| **Reference** | Rev 4 §2 heading vs Rev 3 §2. |
| **Category** | Restructured |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 2.1 Integrated Planning Philosophy |
| **Old (Rev 3)** | Brief statement of cross-functional planning across operational/tactical/strategic horizons producing resourced, prioritized, approved plans. |
| **New (Rev 4)** | Rewritten and expanded: activities integrated and prioritized on **risk, business value, readiness, and available resources**; common framework identifying constraints, opportunities, and ownership early; continuous improvement of planning and execution performance. |
| **Reason** | Clarity; introduces the risk/value/readiness prioritisation basis used later in gating. |
| **Reference** | Rev 4 §2.1. |
| **Category** | Updated / Clarification |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 2.2 Integrated Planning Strategy |
| **Old (Rev 3)** | Principles: Organization; Planning Goals & Objective; Integrated P&S; Planning Integration; Planning tools/visualization/comms; Continuous Improvement; Planning Process (with sub-bullets). |
| **New (Rev 4)** | Same principle set, relabelled and reworded ("Organization and Ownership", "Goal Alignment", "Integration Across Planning Horizon", "Structured Planning Process") and elevated to mandatory ("shall") language; adds a "Formal approval of the integrated plan" step. |
| **Reason** | Clarity and consistency of obligation language; minimal substantive change. |
| **Reference** | Rev 4 §2.2. |
| **Category** | Updated / Clarification |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 2.3 Function-Specific Practices (from Rev 3 §2.2 tail) |
| **Old (Rev 3)** | Function-specific tailored practices (Operations/Shutdown, Projects/Portfolio & OA, Well Ops/WDDP, Commercial) were embedded within §2.2 Strategy. |
| **New (Rev 4)** | Promoted to a distinct sub-section "Function-Specific Practices" with named practices (Shutdown Planning, Portfolio Management & Operability Execution, Operability Assurance, Procurement Planning, WDDP, Sales Agreement Alignment, Market Alignment); wording aligned to "shall" and to MPEP where applicable. |
| **Reason** | Clarity; keeps function-specific execution subordinate to the integrated framework and each function's own procedures. |
| **Reference** | Rev 4 §2.3; MPEP (MPEP-PM-GUI-03, MPEP-PD-GUI-01). |
| **Category** | Restructured / Clarification |

### 3. Planning System & Horizon (NEW major section)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Section 3 **"Planning System & Horizon"** — new; absorbs and greatly expands Rev 3 §2.3 "Integrated Planning Work Process". |
| **Old (Rev 3)** | §2.3 summarised five horizons in prose: BU Life/ADP, 10-Year/LTP, 24-Month, 30/90-Day, Plan Control (7-D for field ops). |
| **New (Rev 4)** | New standalone section stating detail/readiness/certainty increase toward execution and that horizons are interdependent. Contains the **Horizon Breakdown** (below), Activity-Based Planning Processes, Work Process/Flow, and Tools/References. |
| **Reason** | The horizon model is the central change of Rev 4; it warrants a dedicated section aligned to GN-3005 (LTP/IBP) and GN-3007 (12M/90D/30D/7D). |
| **Reference** | Rev 4 §3; GN-3005; GN-3007. |
| **Category** | Added / Restructured |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 3.1 Horizon Breakdown |
| **Old (Rev 3)** | Five horizons; **no 12-Month and no 7-Day** as formal named horizons; "Plan Control" described a 7-D field-ops process generically. FDP not named. |
| **New (Rev 4)** | Eight explicit horizons each with definition, inputs/outputs and gating: **FDP** (field technical basis; per GL-001), **ADP** (per GL-002), **LTP** (per GN-3005; split into **24-Month Planning Period** and **Outer-Years Period**), **12M** (rolling operational outlook / early screening), **90D** (Gate 1 candidates, not commitment), **30D** (Gate 2, **Frozen**), **7D** (Gate 3, weekly execution). |
| **Reason** | Net-new 12M and 7D; explicit FDP/ADP/LTP references; introduces stage gates — direct alignment to GN-3007 (operational) and GN-3005 (LTP). |
| **Reference** | Rev 4 §3.1; GN-3007; GN-3005; GL-001 (`GL-001/06.2021/MEDC/RESV-TA`); GL-002 (`GL-002/06.2021/MEDC/RESV-TA`); GN-3005 (`ID-G-BU-GG0-GUI-GN-00-3005`). |
| **Category** | Added / Governance Update |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 3.x Activity-Based Planning Processes (new) |
| **Old (Rev 3)** | Maintenance, Shutdown, Project, and Early-Operations planning were mentioned in scattered prose within §2.3. |
| **New (Rev 4)** | Consolidated sub-section defining Maintenance Planning, Project Planning (per MPEP), Shutdown Planning, and Early Operations Planning (per OA/MPEP-PD-GUI-01) as activity-based processes that feed the horizons (12M/90D/30D/7D) rather than being separate horizons. |
| **Reason** | Clarity on how function work integrates into the horizon system without duplicating function governance. |
| **Reference** | Rev 4 §3; MPEP-PM-GUI-03; MPEP-PD-GUI-01. |
| **Category** | Added / Clarification |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 3.x Work Process/Flow (new) |
| **Old (Rev 3)** | No explicit common process-stage model; work process was described narratively and via Figure 2. |
| **New (Rev 4)** | Defines six common process stages for every horizon: Initiation & Input; Integration & Review; Decision & Approval; Plan Hand-Off & Progression; Performance Monitoring & Control; Feedback & Adjustment. References **Figure 2 – Multi-Horizon Planning Work Process (Horizon Overview)** as showing focus, forum/cadence, chair, and approval authority per horizon. |
| **Reason** | Standardises the planning cycle across horizons; supports the iterative feedback intent. |
| **Reference** | Rev 4 §3; Figure 2 (`assets/Fig2_Horizon_Overview.png`). |
| **Category** | Added |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 3.x Tools, System & References (new) |
| **Old (Rev 3)** | No consolidated tools/systems section. |
| **New (Rev 4)** | Lists IBP module in Medco BPM, SAP, ARIS, MCRS, SharePoint, WDDP, MPEP, and **Production Forecasting Tools / Gas Processing Tools (GPT)** for STPF. |
| **Reason** | Alignment to actual practice and to IBP/BPM implementation (GN-3005). Note: GPT = Gas Processing Tools (production forecasting), not an AI tool. |
| **Reference** | Rev 4 §3; GN-3005. |
| **Category** | Added |

### 4. Roles, Approvals & Governance (Rev 3 §2.4–2.5)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 4.1 Plan Ownership and Approval — **Table 1 (Plan Approval and Administration)** (from Rev 3 §2.4) |
| **Old (Rev 3)** | Table 1 columns: Planning Horizons / Coverage / **Overall Plan Approval** / Planning Process Focal Point / Planning Administrator. Five rows: BU Life (COO), 10 Year (COO), 24-Month (SVP), 30/90 Day (**Field Manager/Managers**; Operations Planning & Scheduling; Functional/Asset Planner), Plan Control (**Field Managers/supervisors**; Functional Planner). |
| **New (Rev 4)** | Table 1 columns: Planning Horizon / Coverage / **Plan Ownership** / **Approval Authority** / Planning Focal Point / Planning Admin. Eight rows: FDP (SM Subsurface → Sr. VP Asset), ADP (Sr. VP Asset → CEO/COO), LTP Outer Years (Asset Mgmt → CEO/COO + Sr. VP Asset), LTP 24-Month (same), 12M (OIM/OM + owners → **VP Operations**; P&S Team; Integrated Planner), 90D (OIM/OM + Superintendent → **VP Operations, Gate 1**), 30D (→ **OIM/OM, Gate 2**), 7D (Superintendent/SPV → **Superintendent, Gate 3**). |
| **Reason** | Alignment to GN-3007 approval chain (OIM/OM, VP Ops, Superintendent) and to GL-001/GL-002; adds explicit ownership vs approval separation and stage gates; retires "Field Manager" as approver at the operational horizons. |
| **Reference** | Rev 4 §4.1 Table 1; GN-3007; GL-001; GL-002. |
| **Category** | Governance Update / Updated |
| **Conflict flag (Open Items §4)** | (1) ADP approval — Rev 4 uses "CEO/COO"; GL-002 scope text says "President Director", GL-002 summary table says "CEO". (2) FDP approval — Rev 4 and GL-002 summary say "Sr. VP Asset"; GL-001 scope text says "Senior Manager Subsurface". (3) 90D/30D body — GN-3007 uses OLT/OIM/OM chain; legacy Rev 3 said Field Manager. Confirm with Mas Fikri / Mas Robert / Kang Oi. Do not resolve. |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | 4.x Roles and Responsibilities (from Rev 3 §2.5) |
| **Old (Rev 3)** | Roles: COO; SVP; Asset Management; Plan Owners; Managers; Installation Manager/Superintendent; Other Dept/Team Leaders; Responsible Person/Job Owner; **Planning Group**; **P&S Steering Committee**. |
| **New (Rev 4)** | Roles: **CEO & COO**; SVP; **VP Operations (new)**; Asset Management; **E&P Planning (new)**; **OPAA – Operations Planning and Activities Assurance (new; coordinates 12M/90D/30D)**; Plan Owners; Managers; Installation Manager/Superintendent; Other Dept/Team Leaders; Responsible Person/Job Owner (expanded). The Rev 3 **"Planning Group"** and **"P&S Steering Committee"** role blocks are not carried in the Rev 4 roles list (Steering Committee is still referenced in the Continuous Improvement section). |
| **Reason** | Alignment to GN-3007 (VP Ops / OPAA / OIM-OM) and GN-3005 (E&P Planning / IBP); OPAA replaces the generic "P&S Team/Group" as operational coordinator. |
| **Reference** | Rev 4 §4 Roles; GN-3007; GN-3005. |
| **Category** | Governance Update / Added / Updated |
| **Terminology note** | OPAA = Operations Planning and Activities Assurance (not "P&S Team"). Table 1 still labels the 12M/90D/30D focal point "P&S Team" — minor inconsistency with the OPAA naming in the roles text. |

### Governance Model (Rev 3 §3)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Governance Model + Meeting Term of Reference (from Rev 3 §3 / §3.1) |
| **Old (Rev 3)** | Brief feedback-loop statement; §3.1 pointed TORs to Appendix A and Appendix B. No cadence table. |
| **New (Rev 4)** | Retains the feedback-loop statement and TOR pointer, and **adds Table 2 – Overview of Integrated Planning Meeting Cadence** (labelled "Table X" in the draft): FDP/ADP annual, LTP outer-years/24-month bi-annual, 12M quarterly, 90D monthly (Gate 1), 30D monthly (Gate 2/Frozen), 7D weekly (Gate 3), with key participants, main inputs, expected outputs. States the 12M/90D/30D/7D sequence is consistent with GN-3007. |
| **Reason** | Codifies forum cadence and gate outputs per GN-3007. |
| **Reference** | Rev 4 Governance Model, Table 2; GN-3007 (`ID-G-BU-GG0-PRO-GN-00-3007`). |
| **Category** | Added / Governance Update |
| **Draft flag** | Cadence table is titled "Table X" (placeholder number) and ADP row is blank — requires finalisation. |

### Criteria of Activities Inclusion into Plan (Rev 3 §4)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Criteria of Activities Inclusion into Plan (from Rev 3 §4) |
| **Old (Rev 3)** | Short section referencing Appendix C and mapping horizons to AACE RP 37R-06: 10-Year = L1; 24-Month = breakdown of L1; 30/90D = L3; Plan Control = L4/5. |
| **New (Rev 4)** | Adds an **Inclusion Criteria Matrix** narrative (Activity Type, Planning Horizon, Inclusion Criteria, Schedule Visualization Granularity; meaning of "ALL"/thresholds; criteria as minimum visibility). **Schedule Levels (AACE)** re-mapped to the new horizons: LTP = L1; 24-Month; 12M (higher operational visibility / early screening); 90D (first level of detailed operational screening); 30D (execution commitment / readiness validation); 7D (weekly execution / work-package control). |
| **Reason** | Alignment to the new horizon set; clarity on inclusion logic. AACE RP 37R-06 confirmed current. |
| **Reference** | Rev 4 Inclusion Criteria & Schedule Levels; AACE RP 37R-06; Appendix C. |
| **Category** | Updated / Clarification |
| **Conflict flag (Open Item §4.6)** | **Appendix C (Planning Activity Inclusion Criteria) was NOT updated** — its matrix columns remain 7-day/30-day/90-Day/24 Month/10-Year/BU Life, with **no 12M column** and still "10-Year" (not "LTP"). Inconsistent with the new §3.1 horizons and the AACE re-mapping. Confirm with Mas Fikri. |

### Managing the Plans (Rev 3 §5)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Managing the Plans — introductory framing (from Rev 3 §5) |
| **Old (Rev 3)** | Section opened directly with 5.1 Acceptance/Input Criteria. |
| **New (Rev 4)** | Adds a framing paragraph: management requires consistent develop/review/update/control processes; detail, certainty, readiness, and control increase from strategic toward execution. |
| **Reason** | Clarity; ties the section to the horizon-progression principle. |
| **Reference** | Rev 4 "Managing the Plans" intro. |
| **Category** | Clarification |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Acceptance/Input Criteria + 12M content (Rev 3 §5.1–5.2) |
| **Old (Rev 3)** | §5.1 Acceptance/Input Criteria referencing Appendix D; §5.2 "30/90 Day Plan" describing the 30-day frozen window and required activity detail. |
| **New (Rev 4)** | §5.1 retained, now explicitly ties acceptance to Appendix C inclusion criteria. Adds a substantial new **"12 Month Plan (12M)"** sub-section (rolling operational outlook, transition between LTP and operational planning, list of activity attributes required for 12M inclusion, progression rule to 90D that is not execution commitment). The Rev 3 30-day frozen content is retained beneath it. |
| **Reason** | Introduces the 12M horizon into the managing-the-plans mechanics; alignment to GN-3007. |
| **Reference** | Rev 4 Managing the Plans / 12M; GN-3007. |
| **Category** | Added / Updated |
| **Draft flag** | The heading "12 Month Plan (12M)" appears **twice**; the second instance is immediately followed by the legacy 30-day frozen paragraph — an evident mislabel/duplication to be corrected (should be a "30 Day Plan (30D)" heading). |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Gate Review Criteria; Managing Constraints; Risk Assessment (Rev 3 §5.3–5.5) |
| **Old (Rev 3)** | Present as §5.3 Gate Review Criteria (90D/30D gate requirements), §5.4 Managing Constraints (static/dynamic; permitting, POB, logistics, contractors, materials, work pack, O&M), §5.5 Risk Assessment (strategic/tactical/operational; QRA/CBR; contingency). |
| **New (Rev 4)** | Carried over substantially **unchanged** in content (minimal-change). Gate criteria, constraint categories, and risk-assessment horizons retained verbatim. |
| **Reason** | Valid Rev 3 content preserved under the minimal-change philosophy. |
| **Reference** | Rev 4 Managing the Plans (Gate Review / Constraints / Risk). |
| **Category** | Updated (carried over) |
| **Note** | Constraint text still refers to "30/90-Day Plan" and "OIM or Field Manager", not yet re-expressed in the new horizon/authority terms — residual legacy language (Open Item §4.4). |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Conflict Resolution and Plan Prioritization (from Rev 3 §5.6) — with new sub-sections |
| **Old (Rev 3)** | §5.6 prioritisation objectives and criteria for strategic/tactical/operational horizons. |
| **New (Rev 4)** | Core content retained, plus **three net-new sub-sections**: **Escalation Path** (new), **Opportunity Identification** (new — types of opportunity by cost/time/scope/quality; assessment methods such as OPZBB/process improvement/kaizen; steps to integrate opportunities into the plan and decision-making framework), and **Output/Deliverables per Horizon** (new — a per-horizon deliverables table: output, format, owner, cadence). |
| **Reason** | Expands the "Managing the Plans" spine to add opportunity capture and structured escalation, consistent with the value-capture objective and IBP intent. |
| **Reference** | Rev 4 Conflict Resolution & Prioritization sub-sections. |
| **Category** | Added |
| **Draft flag** | Escalation Path, Opportunity Identification, and Output/Deliverables per Horizon are **unwritten placeholders** (author notes, partly in Indonesian: "Bahas mengenai…", "New, bahas apa itu opportunity…", "[NEW] A deliverables table per horizon"). Intent captured; drafting incomplete. |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Administering the Plan (from Rev 3 §5.7) |
| **Old (Rev 3)** | Documentation; Data & Information Management; Plan Communication & Visualization. |
| **New (Rev 4)** | Same three topics retained, plus a new **"Version Control Rule & Source of Truth"** sub-heading. |
| **Reason** | Adds explicit single-source-of-truth / version-control governance for planning data. |
| **Reference** | Rev 4 Administering the Plan. |
| **Category** | Added |
| **Draft flag** | The Version Control sub-section body currently repeats the Plan Communication paragraph (placeholder text) — content to be written. |

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Change Control for Operational Planning Horizon (from Rev 3 §5.8) — with Break-in |
| **Old (Rev 3)** | §5.8 change control for the frozen 30-day plan; changes escalated to OIM with final approval at discretion of the **Field Manager (FM)**; references Appendix F. |
| **New (Rev 4)** | Legacy change-control text retained, plus a new **Break-in Management** intent block: establish a planner-side break-in process; standardise the readiness checklist handed from project planner to operations planner; standardise the full break-in process across operations and non-operations sources. |
| **Reason** | Formalises controlled additions/changes ("Break-in") to the Frozen 30D plan post-Gate 2, consistent with GN-3007. |
| **Reference** | Rev 4 Change Control; GN-3007; Appendix F. |
| **Category** | Added / Governance Update |
| **Conflict flag (Open Item §4.4)** | Change-control body still names **"Field Manager (FM)"** as approver — conflicts with the GN-3007 OIM/OM authority adopted in Table 1. Confirm with Kang Oi / Mas Fikri. |
| **Draft flag** | Break-in items are marked "[NEW]"/"[DECIDE]" placeholders (confirm whether a break-in template already exists — Kang Oi). Drafting incomplete. |

### Assessing Performance (Rev 3 §6)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Assessing Performance — AAR, Planning Compliance, Peer Review, Business Performance Review, KPI, Benchmarking (from Rev 3 §6.1–6.6) |
| **Old (Rev 3)** | §6.1–6.6 with KPIs: 6.5.1 Schedule Attainment (with SF), 6.5.2 SPI, 6.5.3 Plan Break-in, 6.5.4 Plan Deletion; benchmarking strategy. |
| **New (Rev 4)** | Content carried over substantially **unchanged** (Schedule Attainment + Schedule Shift Factor, SPI, Plan Break-in, Plan Deletion equations all retained verbatim). Adds a new **"Reporting Cadence & Ownership"** intent (a reporting matrix: metric, owner, cadence, forum). |
| **Reason** | Preserve valid Rev 3 KPI framework (minimal change); add reporting governance. |
| **Reference** | Rev 4 Assessing Performance / KPI. |
| **Category** | Updated (carried over) / Added |
| **Draft flag** | "Reporting Cadence & Ownership" and benchmarking scope note are placeholders ("SPECIFY SCOPE, PEERS…", "Create reporting matrix…"). |

### Planning Process Review / Continuous Improvement (Rev 3 §7)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Continuous Improvement (from Rev 3 §7.1–7.2) |
| **Old (Rev 3)** | §7 Continuous Improvement (Steering Committee accountability) and §7.2 Reviews and Assessments (Table 2 P&S system reviews). |
| **New (Rev 4)** | Reorganised under "Continuous Improvement" with new sub-headings **Program Structure**, **Review Cadence**, **Ownership Model**; retains Steering Committee reference and the Reviews & Assessments table. |
| **Reason** | Structural clarity. |
| **Reference** | Rev 4 Continuous Improvement. |
| **Category** | Restructured |
| **Draft flag** | Review Cadence and Ownership Model bodies currently duplicate placeholder text; the Reviews & Assessments table (Table 2) reappears further down. Section is duplicated in the draft (see Structural flags). |

### 8–9. Operating Cost Management & Future State (Rev 3 §8–9)

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Alignment with Operating Cost Management (§8) and Future State – Dynamic Plan Management (§9) |
| **Old (Rev 3)** | §8 cost-management alignment; §9 dynamic plan-management vision. |
| **New (Rev 4)** | Carried over **unchanged** in substance. |
| **Reason** | Valid Rev 3 content preserved. |
| **Reference** | Rev 4 §8, §9. |
| **Category** | Updated (carried over) |
| **Structural flag** | These two sections, plus Future State and Continuous Improvement, appear **duplicated** in the draft (a full second copy of "Planning Process Review and Adjustment", "Alignment with Operating Cost Management", and "Future State" follows the first). A drafting artefact to be de-duplicated before issue. |

### Appendices A–G

| Field | Detail |
|---|---|
| **Section (Rev 4)** | Appendices A – BU Life Planning; B – Meeting TOR; C – Planning Activity Inclusion Criteria; D – Data Input Attribute; E – Prioritization Matrix; F – Activity Change Request Process; G – Conducting After Action Review |
| **Old (Rev 3)** | Same seven appendices (A–G). |
| **New (Rev 4)** | Carried over **unchanged**. Appendix A (BU Life Planning), C (inclusion matrix), D (Data Input Attribute), E, F (change request / PCR), and G (AAR) are identical to Rev 3. |
| **Reason** | Minimal change; appendices not yet re-aligned to the new horizon system. |
| **Reference** | Rev 4 Appendices A–G. |
| **Category** | Updated (carried over) |
| **Conflict flags** | (a) Appendix C lacks a 12M column and still says "10-Year"/"BU Life" (Open Item §4.6). (b) Appendix F PCR process still names the **Field Manager** as PCR approver (Open Item §4.4). (c) Appendix D "Data Input Attribute" still keyed to Operational/Tactical/Strategic, not the eight new horizons. Confirm with Mas Fikri / Kang Oi. |

---

## Structural & Draft-Status Flags (require closure before Rev 4 issue)

These are not Rev-3-vs-Rev-4 content changes but conditions of the working draft that the reviewer must note:

1. **Stale Table of Contents.** The ToC still lists the Rev 3 1–9 skeleton ("2 Planning System", "3 Governance Model" …) and does not reflect the restructured body ("Philosophy & Principles", "Planning System & Horizon", "Roles, Approvals & Governance"). ToC and section numbering must be regenerated.
2. **Duplicated section blocks.** "Continuous Improvement / Planning Process Review", "Alignment with Operating Cost Management", and "Future State – Dynamic Plan Management" each appear twice; the "12 Month Plan (12M)" heading appears twice (second is mislabelled 30D content). De-duplicate.
3. **Unwritten placeholders (author notes, some in Indonesian).** Escalation Path; Opportunity Identification; Output/Deliverables per Horizon; Version Control Rule & Source of Truth; Break-in Management; Reporting Cadence & Ownership; benchmarking scope. Intent is captured but body text is not written.
4. **Placeholder table identifiers.** Cadence table labelled "Table X"; ADP cadence row blank; the objectives-monitoring cross-reference points to "Section x.x".
5. **Residual legacy terminology.** "Field Manager (FM)", "30/90-Day Plan", "P&S Team", "Planning Group", "P&S Steering Committee" persist in body/appendix text that elsewhere adopts OIM/OM, VP Ops, OPAA, and the 8-horizon model.

## Open Items carried from Context §4 (flag only — do NOT resolve)

- **#1 ADP approval authority** — GL-002 scope ("President Director") vs GL-002 table ("CEO") vs Rev 4 Table 1 ("CEO/COO"). Confirm: Mas Fikri / Mas Robert.
- **#2 FDP approval authority** — GL-001 scope ("Senior Manager Subsurface") vs GL-001 table ("Sr VP Asset") vs Rev 4 Table 1 ("Sr. VP Asset"). Confirm: Mas Fikri / Mas Robert.
- **#3 90D/30D approval body** — GN-3007 OLT/OIM/OM chain vs legacy Rev 3 "Field Manager"; Rev 4 adopted OIM/OM + VP Ops. Confirm: Kang Oi.
- **#4 Residual "Field Manager" language** in Rev 4 change-control and Appendix F — conflicts with GN-3007 OIM/OM authority. Confirm: Kang Oi / Mas Fikri.
- **#5 GN-3007 vs GN-3008 source defect** — source procedure cover reads `GN-00-3007` (4-horizon title) but running header reads `GN-00-3008` (3-horizon title dropping 12M). A defect in the source, not in this guideline. Confirm: Kang Oi.
- **#6 Appendix C lacks a 12M column** despite 12M being a formal horizon. Confirm: Mas Fikri.
- **#7 Corporate PIC for GN-3005** — Robert Cahyadi named preparer; ongoing contact unconfirmed. ("Mbak Alice" is void — never use.) Confirm: Ridho.

---

## Draft Rev 4 Revision Sheet Entry

*(Written in the style/format of the existing Rev 2 and Rev 3 entries in the Revision Sheet block. For paste into the "REVISION / DATE / DESCRIPTION OF CHANGE" table.)*

**REVISION 4 — [Issue date to be confirmed]**

Update the planning horizon framework to align with corporate Integrated Business Planning Guideline – E&P (GN-3005) and the Integrated Corridor Operation Planning Procedure (GN-3007), introducing the full FDP → ADP → LTP (Outer-Years + 24-Month) → 12-Month → 90-Day → 30-Day → 7-Day horizon system.

- Update Section 1.1 – Recast the Integrated Planning objectives into Table 1 (Objectives, Expected Behaviours, and Organizational Value).
- Update Section 1.2 (Scope) – Realign scope to ADP, FDP, LTP (24-month and outer-years), and short-term planning (12M, 90D, 30D, 7D).
- Update Section 2 – Retitle "Planning System" to "Philosophy & Principles"; realign the planning strategy principles and promote Function-Specific Practices to a distinct sub-section.
- Add new Section 3 (Planning System & Horizon) – Add the Horizon Breakdown (FDP, ADP, LTP, 12M, 90D, 30D, 7D), Activity-Based Planning Processes (Maintenance, Project, Shutdown, Early Operations), the common six-stage Work Process/Flow, and Tools, System & References.
- Add new 12-Month (12M) and 7-Day (7D) planning horizons; add the FDP as an explicit upstream planning input.
- Update Section 2.4/Table 1 (Plan Approval and Administration) – Rebuild to eight horizons with a distinct Plan Ownership and Approval Authority; introduce VP Operations, OIM/OM, and Superintendent authorities and the Gate 1 (90D) / Gate 2 (30D, Frozen) / Gate 3 (7D) stage gates; align with GN-3007.
- Update Section 2.5 (Roles and Responsibilities) – Add Vice President of Operations, E&P Planning, and OPAA (Operations Planning and Activities Assurance); align CEO/COO and SVP roles; retire the standalone Planning Group role block.
- Update Section 3 (Governance Model) – Add Table 2 (Overview of Integrated Planning Meeting Cadence) defining forum cadence and gate outputs per horizon (FDP/ADP annual, LTP bi-annual, 12M quarterly, 90D/30D monthly, 7D weekly), aligned with GN-3007.
- Update Section 4 (Criteria of Activities Inclusion) – Add the Inclusion Criteria Matrix narrative and re-map the AACE RP 37R-06 schedule levels onto the new horizons.
- Update Section 5 (Managing the Plans) – Add an introductory framing on progressive detail/readiness/control and a new 12-Month (12M) acceptance sub-section.
- Add new sub-sections under Section 5.6 – Escalation Path, Opportunity Identification, and Output/Deliverables per Horizon.
- Update Section 5.7 (Administering the Plan) – Add Version Control Rule & Source of Truth.
- Update Section 5.8 (Change Control) – Add Break-in Management for the Frozen 30-Day Plan.
- Update Section 6 (Assessing Performance) – Retain the KPI set (Schedule Attainment/SF, SPI, Plan Break-in, Plan Deletion); add Reporting Cadence & Ownership.
- Update Section 7 – Reorganise Continuous Improvement into Program Structure, Review Cadence, and Ownership Model.
- Update Section 3.1 (Meeting Term of Reference) and references to Figure 2 (Multi-Horizon Planning Work Process / Horizon Overview).
- Add cross-references to GN-3005 (LTP/IBP), GN-3007 (operational horizons), GL-001 (FDP), GL-002 (ADP), MPEP, and AACE RP 37R-06.
- Sections 8 and 9 and Appendices A–G – Carried forward from Rev 3 with no substantive change (pending re-alignment of Appendix C inclusion matrix to include a 12M column and of Appendix F to the OIM/OM approval authority).
- General formatting and typo corrections; regenerate Table of Contents and section numbering; remove duplicated section blocks and complete outstanding placeholder content.

---

*Note: This revision sheet entry documents the intended Rev 4 changes as observed in the accepted working draft. Several items (approval authorities for FDP/ADP and 90D/30D; residual "Field Manager" references; Appendix C 12M column) remain open and require stakeholder confirmation before issue — see Open Items above. They are flagged, not resolved.*
