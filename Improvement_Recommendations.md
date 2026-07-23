# Improvement & Gap Assessment — MEPG Integrated Planning & Scheduling Guideline Rev 4

**Agent D — Improvement & Gap Assessment**
**Question answered:** *If this were the final corporate planning guideline, what important guidance is still missing?*
**Baseline reviewed:** `v14.txt` (Rev 4 accepted draft) against `v12.txt` (Rev 3), `ibp_gn3005.txt` (GN-3005), `gn3007.txt` (GN-3007), `adp.txt` (GL-002), `fdp.txt` (GL-001).
**Philosophy respected:** high-level, practical, governance-focused, usable by every planning function. Every recommendation below either (a) closes a stub the Rev 4 draft itself flags as incomplete, or (b) fills a gap evidenced by a source document. No new complexity is proposed beyond what the sources already imply. Judgment calls are labelled **[judgment]**.

---

## 1. Prioritized summary (top gaps first)

The Rev 4 draft is structurally strong on **horizons, gate governance, constraints, risk, and KPIs**. What is missing clusters in two places: **(a) sections the draft explicitly left as stubs**, and **(b) the "closing" governance layer** — deliverables, reporting/ownership, escalation, opportunity, break-in, and version control — which a *final* corporate guideline cannot ship without.

| # | Gap | Priority | Evidence anchor |
|---|---|---|---|
| G1 | **Break-in Management** is an unfilled stub ("ADD BREAKIN MANAGEMENT") — yet it is the control that protects the Frozen 30D plan | **High** | v14 L963–967; GN-3007 §11 (full text exists) |
| G2 | **Opportunity Identification / Management** is a stub in Indonesian notes — but it is a named objective and philosophy commitment | **High** | v14 L925–932, L235, L343, Objective 2 (L247) |
| G3 | **Escalation Path** for conflicts is an empty stub | **High** | v14 L922–924; GN-3007 §9.1, §10.5 |
| G4 | **Output/Deliverables per Horizon** table marked "[NEW]" but not built | **High** | v14 L933–938 |
| G5 | **Reporting Cadence & Ownership** matrix is a stub | **High** | v14 L1039–1044; GN-3007 §12.3 |
| G6 | **Continuous Improvement** section is hollow — Review Cadence and Ownership Model empty; **Steering Committee referenced but never defined** | **High** | v14 L1049–1055, L1065–1066; Rev 3 v12 L413–421 |
| G7 | **Version Control Rule & Source of Truth** is placeholder text copied from another paragraph — no actual rule | **High** | v14 L950–951; GN-3007 §6.1 |
| G8 | **KPIs have no targets/thresholds** — cannot judge good vs. poor performance | **Medium** | v14 L995–1030; GN-3007 §12.1 (thresholds exist) |
| G9 | **No Definitions/Glossary section** — Frozen, Break-in, Gate 1/2/3, SIMOPS used but undefined | **Medium** | v14 (absent); GN-3007 §4 (full glossary exists) |
| G10 | **No RACI in the guideline** — roles are narrative only, no role-to-step accountability map | **Medium** | v14 §4.2; GN-3007 App. C/F (RACI exists) |
| G11 | **Broken anchors & table numbering** ("Section x.x", "Table X", Table 1 and Table 2 each used twice), mislabeled 30D section | **Medium** | v14 L292, L719, L237/L513, L1069, L821 |
| G12 | **Risk-based activity classification** (Mandatory / Value-Adding / Deferrable) from corporate ops not reflected in inclusion criteria | **Medium** [judgment] | GN-3007 §7.1.1, §7.2.1 |
| G13 | **"P&S Team" used in Table 1** where owner is OPAA — ownership ambiguity | **Medium** | v14 L548/L555/L561; CONTEXT §5 |
| G14 | **Break-in ↔ MOC relationship** not stated | **Low/Med** | GN-3007 §11.8 |
| G15 | **Planning maturity model** absent | **Low** [judgment] | Not in any source |
| G16 | **Benchmarking scope/peers/frequency** left as optional stub | **Low** | v14 L1037 |
| **F1** | **Activity entry criteria per horizon** (min info to enter 12M/90D/30D/7D) — planner-proposed, not consolidated in draft | **High** | FIELD_INPUTS; GN-3007 §8 |
| **F2** | **High-level "Ready" definitions** for the 4 aspects in real use (Engineering / Material / Manpower / Permit & Regulatory) — none defined today | **High** | FIELD_INPUTS items 4,6; GN-3007 §7.2.2 |
| **F3** | **Planner-judgement / readiness-assessment process undocumented**; evidence held per-planner | **High** | FIELD_INPUTS item 5 |
| **F4** | **Standardize readiness criteria without removing planner judgement** — balance not stated | **Medium** | FIELD_INPUTS items 3,6; GN-3007 §6.2 |
| **F5** | **"Integrated Highlight Activities"** staging step (LTP → Integrated Highlight Activities → 90D) is real practice not named in the draft | **Medium** | FIELD_INPUTS item 2 |

Detailed assessments follow (G1–G16 in Section 2; the field-validated additions F1–F5 in Section 2A). Open source **conflicts** (do not resolve) are consolidated in Section 3.

---

## 2. Detailed assessments

### G1 — Break-in Management (High)
- **Current state.** §5.8 covers change control for the 30D plan (PCR route, Appendix F). Immediately after it sits a bare instruction block: *"ADD BREAKIN MANAGEMENT — (1) Establish a break-in process from the planner's side; (2) Standardize the readiness checklist…; (3) Standardize the full break-in process across all sources; (4) [DECIDE] Confirm with Kang Oi / Mas Fikri whether a break-in template already exists."* (v14 L963–967).
- **Gap.** Break-in is the mechanism that lets the Frozen 30D plan absorb legitimate late work without losing discipline. Rev 4 names "Break-in" throughout (Table 1 gates, KPI "Plan Break-in") but never defines the process, criteria, or authority.
- **Recommendation.** Adopt a condensed version of **GN-3007 §11** (Break-in Management & Change Control): principle (break-in is an exception, not routine), definition (add/remove/change to a committed plan), justification criteria (safety/integrity/regulatory/operational-necessity only — *not* urgency, convenience, or late planning), approval authority by gate level (90D → VP/delegate; 30D Frozen → OIM/OM; high-impact/cross-functional → escalate to VP), assessment requirements (risk, impact-on-frozen-plan, readiness, mitigation), and monitoring (track frequency as a planning-quality signal). Keep it high-level and cross-reference GN-3007 for the procedural detail and forms.
- **Why it matters (business).** Uncontrolled break-ins are the single largest driver of the rework, standby, and safety exposure that GN-3007's own Background section cites as the reason the framework exists (GN-3007 L165–200). Without this section the guideline authorizes a Freeze it cannot defend.
- **Reference.** v14 L963–967; GN-3007 §11.1–11.8, §10.5, §4 (Break-in definition).

### G2 — Opportunity Identification / Management (High)
- **Current state.** Stub with drafting notes in Indonesian: *"New, bahas apa itu opportunity, type by impact… Types of opportunity (cost, time, scope, quality)… Cara melakukan assessment (OPZBB, process improvement, kaizen)… Step melakukan integrasi opportunity ke existing plan…"* (v14 L925–932).
- **Gap.** Opportunity management is promised in three higher-level places — the purpose statement ("managing opportunities", L235), the philosophy ("identify constraints, opportunities, and ownership early", L343), and **Objective 2** ("resolve conflicts, and prioritize opportunities", L247) — but no process delivers on it. Conflict Resolution & Prioritization (§5.6) handles conflicts; the opportunity counterpart is empty.
- **Recommendation.** Write a short, practical subsection: (1) what qualifies as an opportunity (value/cost, time/acceleration, scope, quality, risk-reduction); (2) how it is assessed (link to existing methods already named in the doc — cost management acceleration/deferral in §8, QRA/CBR, and standard decision-quality framing); (3) how it is integrated — assess impact/risk/mitigation, apply a decision framework (well-defined problem, decision, managed risk), then route through the same horizon prioritization and approval used for other activities. Do **not** invent new tools; reference OPZBB/kaizen only if MEPG already uses them (confirm — otherwise omit).
- **Why it matters (business).** "Value creation" and "capture opportunities" are stated organizational values (Objectives 2 and 6). A guideline that lists opportunity as an objective but gives no method leaves value capture to chance and undercuts its own stated purpose.
- **Reference.** v14 L925–932, L235, L247, L266, L343; §8 (Operating Cost Management: acceleration/deferral/addition).

### G3 — Escalation Path (High)
- **Current state.** Stub: *"Escalation Path — Bahas mengenai: What to do on conflict; what if it doesn't align with the planned horizon; (optional) resolution time."* (v14 L922–924), sitting at the end of Conflict Resolution & Plan Prioritization.
- **Gap.** §5.6 gives prioritization criteria (HSE, asset integrity, production loss, human factors, opportunity cost) but no path for what happens when a conflict cannot be resolved at the forum level — who it goes to, in what order, and within what timeframe.
- **Recommendation.** Define a simple tiered escalation ladder aligned to the approval chain already in Table 1: activity/planner level → Superintendent → OIM/OM → VP Operations → SVP for cross-asset/strategic conflicts. State the trigger ("unresolved at forum" / "impacts a frozen commitment" / "exceeds asset-level authority") and a target resolution time. This mirrors GN-3007's "VP = Final Escalation Authority for high-impact break-in decisions" and the Break-in Review & Escalation Governance forum.
- **Why it matters (business).** Unescalated conflicts stall plans and default to whoever shouts loudest — the "short-term driven, fragmented" failure mode GN-3007 was written to stop. A named ladder makes conflict resolution auditable and fast.
- **Reference.** v14 L914–924; GN-3007 §9.1, §10.5, §11.4.

### G4 — Output / Deliverables per Horizon (High)
- **Current state.** Placeholder: *"[NEW] A deliverables table per horizon (ADP/FDP/LTP/30-90/7-day), covering: a) output; b) format; c) owner; d) cadence."* (v14 L933–938).
- **Gap.** The guideline defines who owns and approves each horizon (Table 1) and the meeting cadence (Table 2), but never states **what each horizon must produce**. "Deliverables" is one of the review areas and one of the handover's L3 rows (Mgmt of Plans → OUTPUT/Deliverable).
- **Recommendation.** Build the four-column table exactly as scoped. Most content already exists in the body and can simply be tabulated: FDP → approved FDP/technical basis; ADP → approved development scenario; LTP → 10-yr outlook + 24M activity outlook; 12M → approved 12M baseline / feeder list (quarterly); 90D → Gate 1 prioritized plan (monthly); 30D → Gate 2 Frozen plan (monthly); 7D → Gate 3 weekly plan. Pull owners/cadence straight from Table 1 and Table 2 to stay consistent.
- **Why it matters (business).** Without a named deliverable per horizon, "done" is undefined at every stage, hand-offs are ambiguous, and performance cannot be measured against a plan artifact. This is low-effort, high-clarity — the inputs already exist.
- **Reference.** v14 L933–938, L719–764 (cadence table), L513–568 (Table 1).

### G5 — Reporting Cadence & Ownership matrix (High)
- **Current state.** Stub: *"Create reporting matrix covering: Metric / Owner / Cadence / Forum."* (v14 L1039–1044), inside Assessing Performance.
- **Gap.** §6 defines KPIs (Schedule Attainment, SPI, Plan Break-in, Plan Deletion) but never says who reports each, how often, or to which forum. Performance measurement without reporting ownership is inert.
- **Recommendation.** Build the Metric / Owner / Cadence / Forum matrix. It maps naturally onto structures already in the doc: operational KPIs → OPAA/Integrated Planner → monthly → 30D/90D forums; planning-compliance KPIs → BU P&S Lead → quarterly → Business Performance Review. GN-3007 §12.3 ("KPI results shall be reviewed regularly in planning and execution forums") supports the cadence.
- **Why it matters (business).** A KPI with no owner and no forum is never actually reviewed. This matrix is what turns metrics into a management routine.
- **Reference.** v14 L1039–1044, L995–1030; GN-3007 §12.3.

### G6 — Continuous Improvement section hollow + orphaned Steering Committee (High)
- **Current state.** Continuous Improvement (§7) has a Program Structure paragraph, then two headings — **Review Cadence** and **Ownership Model** — whose body text is empty or duplicated boilerplate (v14 L1051–1055). Both the Continuous Improvement paragraph and Program Structure refer readers to *"Section 2.5 for a detailed description of the **Steering Committee's** Roles and Responsibilities"* (L1050, L1066). **But Rev 4's Section 2.5 / §4.2 Roles and Responsibilities does not define a Steering Committee at all** — it lists CEO/COO, SVP, VP Ops, Asset Management, E&P Planning, OPAA, Plan Owners, Managers, Superintendent, Job Owner. The Steering Committee existed in Rev 3 (v12 L413–421: "P&S Steering Committee… led by the BU P&S Lead… convenes quarterly") and was dropped from the Rev 4 roles section but is still referenced by the improvement section.
- **Gap.** (a) Review Cadence and Ownership Model are unwritten; (b) the improvement governance body (Steering Committee) is referenced but undefined — a dangling accountability.
- **Recommendation.** Either (i) reinstate a short Steering Committee definition in Roles & Responsibilities (carry the Rev 3 wording forward, refreshed to Medco/OPAA terminology), or (ii) reassign continuous-improvement accountability to a body that *is* defined in Rev 4 (e.g., BU P&S Lead / Asset Management) and fix the cross-reference. Then fill Review Cadence (e.g., annual guideline review Q3 — already stated in §7.2 Table) and Ownership Model (process owner = BU P&S Lead, per §7.2). **[Flag]** the reinstate-vs-reassign choice for Mas Fikri; do not silently pick.
- **Why it matters (business).** Continuous improvement is a stated objective and a Definition-of-Done area. A section that points to a non-existent role fails an audit and leaves no one accountable for keeping the guideline alive.
- **Reference.** v14 L1049–1055, L1065–1066, §4.2 roles (L621–694); Rev 3 v12 L413–421; §7.2 Table (L1069–1085).

### G7 — Version Control Rule & Source of Truth (High)
- **Current state.** The heading exists under Administering the Plan, but its body is a verbatim copy of the preceding "Plan Communication and Visualization" paragraph — it says nothing about versioning or source of truth (v14 L950–951).
- **Gap.** No rule for which system/plan is authoritative when multiple tools hold planning data. The Tools section itself lists BPM/IBP, SAP, ARIS, MCRS, SharePoint, WDDP, MPEP, GPT (L476–484) and warns information must stay "consistent, current, and traceable" (L474) — but never names the single source of truth per horizon.
- **Recommendation.** State a short rule: for each horizon, name the authoritative plan/system (e.g., approved 30D/7D Frozen plan in the operational planning system is the single source of truth for execution; LTP/IBP module for long-term; SharePoint summary repository for tactical/strategic) and a versioning convention (approved baseline + revision marker; superseded versions retained but clearly marked). GN-3007's "single, integrated planning system — no parallel planning or informal commitments" principle (§6.1) is the corporate anchor.
- **Why it matters (business).** Conflicting plan versions across BPM/SAP/SharePoint are exactly the "conflicting data sources" the Future-State section aspires to eliminate (L1060). Without a source-of-truth rule, freeze discipline and KPI measurement rest on unstable ground.
- **Reference.** v14 L950–951, L472–484; GN-3007 §6.1.

### G8 — KPI targets / thresholds (Medium)
- **Current state.** §6.5 defines Schedule Attainment (with SF), SPI, Plan Break-in, Plan Deletion, plus secondary measures — all with formulas but **no target values or performance bands**.
- **Gap.** A formula without a threshold cannot distinguish acceptable from poor performance, so KPI review has no decision content.
- **Recommendation.** Adopt performance bands, at least for the headline operational KPIs. GN-3007 §12.1 already publishes Plan Attainment bands (≥90% Excellent, 85–89% Acceptable, 75–84% Marginal, <75% Poor) and a break-in-frequency interpretation — reuse these so the guideline and the ops procedure agree. Keep long-term/compliance KPIs qualitative if targets are not yet set, and say so.
- **Why it matters (business).** Shared thresholds let Corridor and corporate compare performance on the same scale and make the Business Performance Review actionable.
- **Reference.** v14 L995–1030; GN-3007 §12.1.

### G9 — Definitions / Glossary (Medium)
- **Current state.** Rev 4 uses **Frozen, Break-in, Gate 1/2/3, SIMOPS, POB, MOC, STPF, SF, SPI, OPAA, OIM/OM** throughout but has no Definitions section; some terms are explained inline, most are assumed.
- **Gap.** A final corporate guideline read across every planning function needs a shared vocabulary; several terms are net-new in Rev 4 (12M, 7D, Frozen, Gate 1/2/3) and appear before any definition.
- **Recommendation.** Add a short Definitions & Abbreviations section. GN-3007 §4 already defines 12M/90D/30D/7D, Break-in, Frozen, Conditional/At-Risk, Gate 1/2/3, MOC, OIM, OM, SIMOPS, Planning Candidate, Execution Commitment, Readiness Outlook — adopt these verbatim for consistency, and add the guideline-specific ones (LTP, ADP, FDP, OPAA, SF, SPI, STPF, GPT = Gas Processing Tools).
- **Why it matters (business).** Prevents the exact terminology drift this project has already had to correct (e.g., OPAA vs "P&S Team", GPT-not-an-AI-tool, LTP-not-LRP). One authoritative glossary removes a whole class of misread.
- **Reference.** v14 (absent); GN-3007 §4; CONTEXT §5.

### G10 — RACI in the guideline (Medium)
- **Current state.** §4.2 gives narrative role descriptions; Table 1 gives ownership/approval/focal-point/admin per horizon. There is no role-to-process-step RACI.
- **Gap.** Narrative roles leave "who is Responsible vs. Accountable vs. Consulted" implicit at each process stage (initiation, integration, decision, hand-off, monitoring).
- **Recommendation.** Add a compact RACI (or reference one) for the core process steps. GN-3007 Appendix C/F already carries 90D/30D/7D RACI matrices, and GN-3005 §4.3 carries the LTP/IBP RACI — the guideline can present a summary RACI and point to those for detail rather than duplicating. Keep it high-level to preserve the guideline's altitude. **[judgment]** — a full RACI may be more than a "guideline" needs; a summary or explicit pointer is the minimal-change option.
- **Why it matters (business).** Kang Oi's prior feedback was that draft content was "too high-level — needs who does what, when, with what input, producing what output." A summary RACI is the lightest structural answer to that.
- **Reference.** v14 §4.2; GN-3007 App. C/F; GN-3005 §4.3; handover §11.

### G11 — Broken anchors, table numbering, and a mislabeled section (Medium)
- **Current state.** Multiple internal-reference defects: (a) *"as defined in Section x.x – Key Performance Indicators"* — unresolved anchor (L292); (b) meeting-cadence table titled *"Table X"* (L719); (c) **"Table 1" used for both** the Objectives table (L237) **and** Plan Approval & Administration (L513); (d) **"Table 2" used for both** the meeting-cadence overview (implied) and the P&S Reviews & Assessments table (L1069); (e) the second **"12 Month Plan (12M)"** heading (L821) actually introduces **30-Day Frozen-plan** content — a mislabeled heading.
- **Gap.** Cross-references and table citations do not resolve; a reader cannot reliably navigate. This directly fails the Definition-of-Done item "appendix cross-references internally consistent."
- **Recommendation.** Renumber tables uniquely (Objectives = Table 1; Plan Approval = Table 2; Meeting Cadence = Table 3; Reviews & Assessments = Table 4, or similar), resolve every "Section x.x"/"Table X" placeholder, and correct the mislabeled 30D heading. (Overlaps Agent E / Legacy Cleanup scope — flag for coordination; listed here because it blocks the document being *final*.)
- **Why it matters (business).** Unresolvable references are the most visible sign of a draft, not a final; they undermine auditability and user trust.
- **Reference.** v14 L292, L719, L237, L513, L1069, L821.

### G12 — Risk-based activity classification not carried into inclusion criteria (Medium) [judgment]
- **Current state.** Rev 4 classifies activities as **Integrated vs. Function-specific** (§4, Appendix C). GN-3007 classifies operational activities as **Mandatory / Value-Adding / Deferrable** (plus Break-In and Highlight-business-event) and drives prioritization from that (GN-3007 §7.1.1, §7.2.1, §6.2).
- **Gap.** The corporate ops procedure's risk-priority language ("mandatory safety/integrity/compliance always takes precedence") is not reflected in the guideline's inclusion/prioritization sections, so the two documents describe activity screening differently.
- **Recommendation.** In the inclusion-criteria or prioritization text, acknowledge the Mandatory/Value-Adding/Deferrable classification for operational horizons and align it with the §5.6 prioritization criteria (HSE and asset integrity first). This is an *alignment* addition, not a new system. **[judgment]** — include only if the intent is tight GN-3007 alignment; otherwise a one-line cross-reference suffices.
- **Why it matters (business).** Ensures the guideline and the procedure that implements it agree on how work is triaged, so mandatory safety/integrity work is provably protected end-to-end.
- **Reference.** GN-3007 §6.2, §7.1.1, §7.2.1; v14 §4, §5.6.

### G13 — "P&S Team" vs OPAA in Table 1 (Medium)
- **Current state.** Table 1 lists the Planning Focal Point for 12M/90D/30D as **"P&S Team"** (v14 L548, L555, L561), while §4.2 correctly assigns 12M/90D/30D coordination to **OPAA (Operations Planning and Activities Assurance)** (L656–657).
- **Gap.** The same function is named two ways; "P&S Team" is not a defined entity in Rev 4. CONTEXT §5 is explicit: OPAA, **not** "P&S Team."
- **Recommendation.** Replace "P&S Team" with "OPAA" in Table 1 for consistency with §4.2 and the glossary (G9). (Terminology fix — overlaps Agent E; flagged here because it affects ownership clarity.)
- **Why it matters (business).** Ownership must read identically in the table and the role text, or accountability for the operational horizons is ambiguous.
- **Reference.** v14 L548/L555/L561 vs L656–657; CONTEXT §5.

### G14 — Break-in ↔ MOC relationship (Low/Med)
- **Current state.** §5.8 change control and (once G1 is filled) break-in both address plan changes; MOC is listed as a 30D readiness item (L416) but the relationship between break-in approval and MOC approval is not stated.
- **Gap.** A reader could assume break-in approval substitutes for MOC.
- **Recommendation.** Add one sentence mirroring GN-3007 §11.8: break-in governance does **not** replace MOC or technical-approval processes; activities changing design/process/equipment/organization must satisfy MOC **in addition to** break-in approval.
- **Why it matters (business).** Prevents a governance short-circuit where a fast break-in bypasses the safety-critical MOC gate.
- **Reference.** GN-3007 §11.8; v14 L416.

### G15 — Planning maturity model (Low) [judgment]
- **Current state.** No maturity/capability model in Rev 3 or Rev 4; GN-3007 has a "progressive planning discipline" principle (§6.3) but no maturity ladder.
- **Gap.** "Planning maturity" is a listed review area; the guideline has no self-assessment framework for how well planning is being practiced.
- **Recommendation.** **Optional / defer.** A maturity model is not present in any source and would add complexity against the minimal-change philosophy. If leadership wants a continuous-improvement anchor, a lightweight 3–4 level maturity descriptor could live in §7 — but only on explicit request. Recommend **not** adding for Rev 4 unless asked.
- **Why it matters (business).** Useful for long-term capability building, but not required for the guideline to function; low value relative to the higher-priority stubs.
- **Reference.** Not in sources (judgment call, stated as such).

### G16 — Benchmarking scope/peers/frequency (Low)
- **Current state.** §6.6 Benchmarking Strategy is written, but ends with an optional stub: *"SPECIFY SCOPE, PEERS TO REVIEW, AND FREQUENCY OF REVIEW (OPTIONAL)."* (v14 L1037).
- **Gap.** Benchmarking scope/peers/frequency undefined.
- **Recommendation.** Either specify (shutdown and major-project benchmarking, internal operated/non-operated peers, annual) or delete the stub line so it does not read as an unfinished draft. Low effort.
- **Why it matters (business).** Cosmetic-to-modest; mainly removes a visible "draft" marker.
- **Reference.** v14 L1031–1037.

---

## 2A. Field-validated additions (real-practice evidence)

*Added after the initial assessment, on receipt of `assets/FIELD_INPUTS_ShortTerm_Planning.md` — a planner meeting thread (15–21 Jul 2026, planners ⇄ Ridho, cc Oi Rozak/OPAA) plus real Gate 1/2/3 artifacts in `assets/field_inputs/` (90D Gate 1 approval, SUBAN/GGSDR 30D Frozen plans, the GGSDR 30D DoA approval form, SUBAN 7D plans, and the GGSDR weekly forum deck). These five items are distinct from G1–G16: they are improvements the **planners themselves proposed**, grounded in what they already do. They reinforce — not replace — G4 (deliverables) and the G1/G3 stubs. Same minimal-change philosophy: document existing practice, do not impose new machinery, and explicitly preserve planner judgement.*

### F1 — Activity entry criteria per planning horizon (High)
- **Current state.** §5.1 "Acceptance/Input Criteria" points generically to Appendix C (inclusion) and Appendix D (Data Input Attribute), and the body lists 90D and 30D "gate requirements" (v14 L844–860) and a 12M input list (L809–818). But there is **no consolidated statement of the minimum information/detail an activity must carry to *enter* each specific horizon — 12M, 90D, 30D, 7D.** Planners confirmed this is a proposed improvement ("Set activity entry criteria per planning horizon — minimum information/detail required to enter each horizon"), and Ridho is the action-item owner to draft and validate it.
- **Gap.** Entry thresholds live in planners' heads and in scattered sub-lists, not as a single per-horizon criteria set. GN-3007 §8 ("Activity Entry and Screening Criteria", §8.2–8.5) already defines entry criteria for 12M/90D/30D/7D at the corporate-ops level; the guideline does not mirror them.
- **Recommendation.** Add a compact **Activity Entry Criteria** table or list, one row per horizon, stating the minimum an activity needs to enter: **12M** — objective/intent defined at concept level; potential impact on safety/integrity/regulatory/production/capacity; known or anticipated requirement (per GN-3007 §8.2). **90D** — screened in 12M (or approved emergent entry); classified Mandatory/Value-Adding/Deferrable/Break-In; high-level readiness outlook + risk screen; feasibility/resource/interface assessed (GN-3007 §8.3). **30D** — progressed through 12M/90D as an execution-commitment candidate (or routine/BAU visibility item); defined scope + execution intent; readiness, resource availability, cross-functional impact assessed; subject to Gate 2 freeze (GN-3007 §8.4). **7D** — declared Frozen in the approved 30D plan (or approved routine/BAU); no new scope without break-in (GN-3007 §8.5). Seed the detailed data fields from the existing Appendix D. Keep it as *minimum* criteria — functions may hold more.
- **Why it matters (business).** Entry criteria are the front-door filter that stops unprepared work entering the funnel — the exact failure GN-3007 was written to prevent ("activities introduced too late… bypass proper readiness checks", GN-3007 L173–177). Making them explicit closes the loop with G4 (each horizon's *deliverable*) by also defining each horizon's *entry ticket*.
- **Reference.** FIELD_INPUTS §Meeting-summary (proposed improvements; action items); GN-3007 §8.1–8.5; v14 §5.1, L809–818, L844–860, Appendix D.

### F2 — High-level "Ready" definitions for the four readiness aspects (High)
- **Current state.** Real practice uses **four readiness aspects — Engineering, Material, Manpower, Permit & Regulatory** (FIELD_INPUTS §Verified-current-practice item 4), visible in the Gate 1 90D "readiness outlook" and Gate 2 30D validation artifacts. But **there is no formal definition of "Ready" for any aspect** (item 6) — readiness is asserted per activity without a shared bar. The guideline text uses "readiness" pervasively (Gate reviews §5.3, 90D/30D gate requirements) but never defines what "ready" means for each aspect.
- **Gap.** "Ready" is undefined, so two planners can rate the same activity differently. Planners explicitly proposed a **high-level** "Ready" definition per aspect (and said high-level is acceptable).
- **Recommendation.** Add four short, high-level "Ready" statements — deliberately not exhaustive checklists:
  - **Engineering Ready** — scope and methodology defined; technical/engineering design sufficiently matured for the horizon; MOC identified where applicable.
  - **Material Ready** — required materials/equipment identified with confirmed availability or a committed delivery date appropriate to the horizon (e.g., delivered or en route for 30D).
  - **Manpower Ready** — required personnel/crew, competencies, and contractor resources identified and available/committed for the planned window.
  - **Permit & Regulatory Ready** — necessary permits, approvals, and regulatory/partner/SKKMigas clearances identified and obtainable (or obtained) before execution.
  These align directly with GN-3007's 90D readiness-outlook elements (scope/methodology, engineering maturity, material/equipment, contracting/manpower, permit/regulatory — GN-3007 §7.2.2) and 30D validation (§7.3.2). Frame readiness as **maturing across horizons** (indicative at 12M/90D → validated at 30D), so a single definition scales.
- **Why it matters (business).** A shared, high-level "Ready" bar is the smallest change that makes Gate 1/2/3 decisions consistent and defensible across facilities (SUBAN, GGSDR, Grissik/Gelam) and planners, without turning the guideline into a checklist manual.
- **Reference.** FIELD_INPUTS items 4 & 6, proposed improvements; GN-3007 §7.2.2, §7.3.2; v14 §5.3, L844–860.

### F3 — Document the planner-judgement / readiness-assessment process (High)
- **Current state.** Readiness "still relies on **planner judgement**; evidence stored by each planner individually" (FIELD_INPUTS item 5). The assessment process itself — how a planner weighs the four aspects, records the basis, and decides ready/not-ready/conditional — is **undocumented in the guideline** and not centrally retained.
- **Gap.** Because the judgement process is tacit and the evidence is dispersed, readiness decisions are neither transparent nor auditable, and knowledge is lost when a planner moves. GN-3007 provides the vocabulary already (Readiness Outlook §4/§7.2.2; "Conditional/At-Risk Activity" for activities not fully meeting criteria) but the guideline does not describe the *act* of assessing.
- **Recommendation.** Add a short subsection describing the readiness-assessment process at a high level: the planner assesses each activity against the four "Ready" aspects (F2) at the applicable horizon; records the readiness status (e.g., Ready / Conditional-At-Risk / Not-Ready, reusing GN-3007's Conditional/At-Risk term) and the basis for the judgement; carries unresolved gaps as constraints into the forum; and stores the readiness evidence in the common planning repository / source of truth (ties to G7 version-control). Explicitly state that **planner judgement remains central** — the process documents and standardizes *how* judgement is recorded, not a rule that replaces it.
- **Why it matters (business).** Documenting the process converts individual know-how into an organizational capability, makes Gate decisions auditable, and directly answers Kang Oi's earlier feedback that the draft needs "who does what, when, with what input, producing what output." It also removes the single-point-of-knowledge risk of per-planner evidence.
- **Reference.** FIELD_INPUTS item 5, proposed improvements ("Document the planner-judgement & readiness-assessment process"); GN-3007 §4 (Readiness Outlook, Conditional/At-Risk), §7.2.2; cross-ref G7.

### F4 — Standardize readiness criteria while preserving planner-judgement flexibility (Medium)
- **Current state.** With no shared "Ready" definition (F2) and a tacit assessment process (F3), readiness criteria vary by planner and facility. Planners proposed to **"standardize readiness criteria without removing planner-judgement flexibility."**
- **Gap.** The need is a *balance*: a common baseline that does not become a rigid checklist. Neither the guideline nor GN-3007 currently states this balance.
- **Recommendation.** State the principle explicitly in the readiness text: the four "Ready" definitions (F2) are the **common minimum baseline** applied across all horizons and facilities; planners retain judgement to (a) require more where risk, complexity, or operational impact warrant, and (b) flag an activity Conditional/At-Risk with documented rationale where criteria are partially met. This mirrors the guideline's existing stance elsewhere ("criteria represent the minimum level… functions may maintain more detailed plans", v14 L780) and GN-3007's risk-and-priority-based principle (§6.2). Do **not** publish exhaustive per-activity checklists in the guideline — keep those in function/planner working tools.
- **Why it matters (business).** Standardization improves cross-facility comparability and Gate consistency; preserved flexibility keeps the process usable for the full range of routine and non-routine work (both of which follow the same flow — FIELD_INPUTS item 3) without forcing false precision. This is the explicit guardrail the planners asked for.
- **Reference.** FIELD_INPUTS items 3 & 6, proposed improvements; GN-3007 §6.2; v14 L780.

### F5 — Name the "Integrated Highlight Activities" staging step (Medium)
- **Current state.** Planners confirmed the real flow is **approved LTP → "Integrated Highlight Activities" → 90D Plan** (FIELD_INPUTS item 2), and the artifact set includes a "GGSDR 30D Highlight Activity July 2026" plan and "Top Priority & Decision-Driving Activities" sections — i.e., "highlight activities" is live terminology in the actual templates. The Rev 4 draft describes progression as LTP/12M → 90D and **does not name an "Integrated Highlight Activities" staging step** between approved LTP and the 90D Plan.
- **Gap.** A real, in-use staging/prioritization step is absent from the documented flow, so the guideline's flow does not fully match practice (a Definition-of-Done concern: "reflects actual current Corridor practice"). GN-3007 §7.2.1 lists "Highlight business event" as a 90D activity class, which is adjacent but not the same as the LTP→90D staging step planners described.
- **Recommendation.** **Flag as a candidate to document, pending confirmation of scope with OPAA/Kang Oi** (do not silently insert — the exact definition and owner of "Integrated Highlight Activities" should be confirmed, and it may map onto the 12M screening / feeder-list already in the draft). If confirmed as a distinct step, name it in the Work Process/Flow (§3.3) and the horizon breakdown as the mechanism that surfaces LTP-origin activities into the 90D funnel, and reconcile it with the 12M "early screening / feeder list to 90D" language (v14 L409–410, L1064). If it is simply the local name for the 12M feeder output, say so and cross-reference — avoid creating a duplicate concept.
- **Why it matters (business).** Practice and document must agree for the guideline to be credible with the planners who use it daily; naming the real staging step (or explicitly mapping it to 12M) closes a visible flow gap. Flagged rather than resolved because the term's precise boundary is not yet confirmed in a source.
- **Reference.** FIELD_INPUTS item 2 (and note flagging it as "a real practice not explicitly named in the guideline draft"); GN-3007 §7.2.1 (Highlight business event); v14 §3.3, L409–410, L1064.

---

## 3. Open source conflicts — FLAGGED, NOT RESOLVED (per CONTEXT §4)

These are genuine contradictions **between source documents**; Agent D does not resolve them. They must be confirmed by the named stakeholder before Rev 4 can be final. Confirmed against source text during this review:

| # | Item | Both readings (verified) | Confirm with |
|---|---|---|---|
| C1 | **ADP approval authority** | GL-002 **Scope** (adp.txt L159): *"must be approved by Medco EP President Director"* — vs GL-002 **summary table** (adp.txt L217): *Approval = Medco EP CEO* — vs Rev 4 Table 1: *CEO/COO*. Three different authorities. | Mas Fikri / Mas Robert |
| C2 | **FDP approval authority** | GL-001 **Scope** (fdp.txt L109–110): *"must be approved by Senior Manager Subsurface"* — vs GL-001 **summary table** (fdp.txt L164/L167): *Ownership = Sr. Manager Subsurface, Approval = Sr VP Asset* — vs Rev 4 Table 1: *Sr. VP Asset*. Scope text and table disagree within the same source. | Mas Fikri / Mas Robert |
| C3 | **90D/30D approval body** | GN-3007 uses OLT/OIM/OM chain (Gate 1 = VP/OLT, Gate 2 = OIM/OM); legacy Rev 3 Table 1 said *Field Manager*. Rev 4 adopted OIM/OM + VP Ops. | Kang Oi |
| C4 | **Legacy "Field Manager (FM)" language survives in Rev 4 body** | §5.8 change control (v14 L954–955) and Appendix F (v14 L2263–2264) still route approval to the **Field Manager (FM)** — conflicts with GN-3007's OIM/OM authority now used in Table 1. Internal inconsistency inside Rev 4 itself. | Kang Oi / Mas Fikri |
| C5 | **GN-3007 vs GN-3008 doc-number/title defect** | Source cover reads `GN-00-3007`, four-horizon title (incl. 12-Month); running header from p.2 reads `GN-00-3008`, three-horizon title dropping 12-Month (gn3007.txt L4 vs L47–49). Defect **in the source**, not ours. Rev 4 cites "GN-00-3007, 1st issuance" (v14 L718). | Kang Oi |
| C6 | **Appendix C lacks a 12M column** | Rev 4 inclusion matrix (Appendix C) columns are 7-day / 30-day / 90-Day / 24 Month / 10-Year / BU Life (v14 L1200–1205) — **no 12M column**, despite 12M being a formal horizon everywhere else in Rev 4. | Mas Fikri |
| C7 | **Corporate PIC for GN-3005** | Robert Cahyadi is the named preparer (ibp_gn3005.txt L28) — strong lead — but not confirmed as ongoing contact. The invented name "Mbak Alice" is void; use "unknown" until confirmed. | Ridho |

C4 and C6 are also improvement-relevant: C4 is an internal Rev 4 inconsistency that G1/G13 alignment work will surface, and C6 is a Definition-of-Done blocker ("12M fully integrated into … Appendix C").

---

## 4. Readiness note — what must close before this is a final corporate guideline

**Not yet final.** The Rev 4 draft is a strong skeleton with several load-bearing sections still open. In priority order, the following must be closed:

**Must-close (blockers — the document is visibly incomplete without them):**
1. Fill the six explicit stubs: **Break-in Management (G1)**, **Opportunity Identification (G2)**, **Escalation Path (G3)**, **Output/Deliverables table (G4)**, **Reporting Cadence & Ownership (G5)**, **Version Control / Source of Truth (G7)**.
2. Complete **Continuous Improvement (G6)** and resolve the **orphaned Steering Committee** reference (reinstate or reassign — Mas Fikri to decide).
3. Resolve all **broken anchors and duplicate table numbers (G11)** and the **mislabeled 30D heading**; add the **12M column to Appendix C (C6)**.

**Should-close (quality/consistency for a corporate-grade document):**
4. **KPI thresholds (G8)**, **Definitions/Glossary (G9)**, **summary RACI or explicit pointer (G10)**, **"P&S Team" → OPAA (G13)**, **Break-in ↔ MOC sentence (G14)**.

**Field-validated must-close (planners' own proposals — high confidence, evidence already exists in practice):**
5. **Activity entry criteria per horizon (F1)**, **high-level "Ready" definitions for the four aspects (F2)**, and **document the readiness-assessment / planner-judgement process (F3)** — these three make the draft procedurally specific and directly answer the "too high-level" feedback. **Standardize-with-flexibility (F4)** is the guardrail that must accompany them. Ridho is already the named action-item owner to draft F1/F2 and validate against historical planning documentation.
6. **Confirm-then-document the "Integrated Highlight Activities" staging step (F5)** with OPAA/Kang Oi — do not insert until its boundary vs. the 12M feeder is confirmed.

**Must-confirm before lock (not Agent D's to resolve):**
7. The seven source conflicts in Section 3 — especially **C1/C2 (ADP/FDP approval authority)** and **C4 (residual Field Manager language)** — require named stakeholder sign-off (Mas Fikri / Mas Robert / Kang Oi). A guideline that states approval authorities cannot ship while those authorities are contradicted by their own source documents.

**Explicitly leave out (respecting minimal-change):** the planning maturity model (G15) unless leadership requests it; and, for F2/F4, do **not** publish exhaustive per-activity readiness checklists in the guideline — keep the guideline at the high-level "Ready" baseline and leave detailed checklists in planner/function working tools, preserving judgement. Everything else recommended above is either a stub the draft itself flagged, an alignment gap evidenced directly by GN-3005 / GN-3007 / GL-001 / GL-002, or a planner-validated improvement grounded in the real Gate 1/2/3 artifacts.

*All line references are to the `assets/source_text/*.txt` files reviewed. Where a recommendation overlaps Agent E (legacy cleanup) or Agents B/C (corporate/ops alignment), it is noted for coordination; Agent D has written only to this file.*
