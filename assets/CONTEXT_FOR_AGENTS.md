# SHARED CONTEXT — MEPG Integrated Planning & Scheduling Guideline Rev 4 Project

**Read this file completely before doing anything.** It is the single source of truth
assembled by the orchestrator from direct reading of all source documents. Every fact
below was verified against the source text (not inferred). Trust these facts; do not
re-derive them. If you believe a fact is wrong, flag it — do not silently change it.

Doc under revision: **`ID-G-BU-GG0-PRO-GN-00-0053` — MEPG Integrated Planning & Scheduling Guideline**, Rev 3 → Rev 4.
Owner org: **514018 – Asset Management Corridor**, Medco E&P Grissik Ltd (MEPG).

---

## 1. File inventory (all readable — real text, no OCR needed)

All paths relative to repo root `/home/user/tes/` unless absolute.

| File | What it is |
|---|---|
| `assets/source_text/v12.txt` | **Rev 3 (OLD)** guideline, full text. The current issued baseline (22 Nov 2024). |
| `assets/source_text/v14.txt` | **Rev 4 (NEW) working draft**, tracked-changes **accepted**. This is the accurate current draft state. |
| `assets/source_text/ibp_gn3005.txt` | Corporate **IBP Guideline GN-3005** Rev 1 (text). |
| `assets/source_text/gn3007.txt` | **Corridor Ops Procedure GN-3007** Rev 0 (text). |
| `assets/source_text/adp.txt` | **ADP Guideline GL-002** (text). |
| `assets/source_text/fdp.txt` | **FDP Guideline GL-001** (text). |
| `assets/Fig1_Integrated_Planning_Concept.png` | Guideline Figure 1 — legacy-style concept diagram (says "5 year", "Input to LRP"; no explicit 12M). |
| `assets/Fig2_Horizon_Overview.png` | Guideline Figure 2 — **high-quality navy/blue multi-horizon overview** embodying the full Rev 4 framework. Reuse this directly. |
| `assets/working/skeleton_deck.pptx` | The user's **existing working deck skeleton** (9 slides, branded, placeholder text). Agent B builds INTO this. |
| `assets/working/Integrated_Planning_Process.xlsx` | Working workbook (tabs incl. Document Skeleton, Comparison Table). |
| `assets/working/v14_accepted.docx` | Rev 4 draft with tracked changes accepted (source for the .txt above). |
| `/root/.claude/uploads/827909a4-51d6-546d-af4a-609c18b510cc/` | Original uploads incl. handover.md, claude.md, the real PDFs, and the V14 working docx (with unaccepted tracked changes). |

---

## 2. The core story — WHY Rev 4 exists (verified)

**Chronology (the spine of the "why now"):**

```
22 Nov 2024  Corridor P&S Guideline Rev 3 issued (v12)
Jan 2025     Corporate IBP Guideline GN-3005 Rev 1 signed  (~2 months after Rev 3)
Jan 2026     Corridor Ops Procedure GN-3007 Rev 0 issued (IFU)  (~14 months after Rev 3)
Jul 2026     Rev 4 rebuild in progress
```

- **Rev 3 predates and does not reference GN-3005 or GN-3007 anywhere** (verified by grep of v12 text). It was issued *before* the two documents it now must align to existed. This is the cleanest justification for Rev 4 — it is not misalignment through neglect.
- GN-3005 signed Jan 2025 by, among others, Tri Laksono (SVP Corridor Asset, 14 Jan 2025). Rev 1. Title: "Integrated Business Planning Guideline – E&P".
- GN-3007 Rev 0, IFU January 2026. Title: "Integrated Corridor Operation Planning Procedure (12-Month, 90-Day, 30-Day, and 7-Day Planning Framework)". Information Owner: OPAA Corridor.

---

## 3. What changed: Rev 3 → Rev 4 (verified)

### 3.1 Planning horizons (the biggest change)
- **Rev 3 horizons:** BU Life / ADP · 10-Year / LTP · 24-Month / Tactical · **30/90-Day** · detailed operational. **No 12-Month, no 7-Day.**
- **Rev 4 horizons (full system):** FDP → ADP → LTP (Outer-Years + 24-Month) → **12-Month (12M)** → 90-Day (90D) → 30-Day (30D) → **7-Day / Plan Control (7D)**.
- Net-new to the guideline: **12M** (early screening / rolling 12-month operational outlook) and **7D** (weekly execution control).
- Detail, readiness, and planning certainty increase toward execution.

### 3.2 Stage-gate governance (net-new)
- **Gate 1 = 90D** (prioritized planning candidates; not execution commitment).
- **Gate 2 = 30D** (execution commitment; plan declared **Frozen**).
- **Gate 3 = 7D** (authorizes weekly field execution within the frozen window).
- Consistent with GN-3007's 90D Forum-Gate 1, 30D Forum-Gate 2, 7D Forum-Gate 3.

### 3.3 Table 1 — Plan Approval & Administration (Rev 4, verbatim structure)
| Planning Horizon | Coverage | Plan Ownership | Approval Authority | Focal Point | Planning Admin |
|---|---|---|---|---|---|
| FDP | Field technical planning | SM Subsurface | **Sr. VP Asset** | per FDP guideline | per FDP guideline |
| ADP | Block/Asset development | Sr. VP Asset | **CEO/COO** | per ADP guideline | per ADP guideline |
| LTP (Outer Years) | 10-yr+ outlook | Asset Management | CEO/COO + Sr. VP Asset | Asset Management | E&P Planning |
| LTP (24-Month) | Major asset activities | Asset Management | CEO/COO + Sr. VP Asset | Asset Management | E&P Planning |
| 12M | Operationally impacting activities | OIM/OM + owners | **VP Operations** | P&S Team (OPAA) | Integrated Planner |
| 90D | Prioritized candidates | OIM/OM + Superintendent | **VP Operations (Gate 1)** | P&S Team (OPAA) | Functional/Asset Planner |
| 30D | Execution commitment | OIM/OM + Superintendent | **OIM/OM (Gate 2)** | P&S Team (OPAA) | Functional/Asset Planner |
| 7D / Plan Control | Weekly field execution | Superintendent/SPV | **Superintendent (Gate 3)** | Functional Planner | Activity/Functional Planner |

### 3.4 Governance forums / cadence (Rev 4 Table 2)
- FDP/ADP: annual cycle · LTP: bi-annual cycle · **12M: quarterly** · **90D: monthly (Gate 1)** · **30D: monthly (Gate 2 / Frozen)** · **7D: weekly (Gate 3)**.

### 3.5 "Managing the Plans" — expanded spine (mostly net-new depth)
Gate Review Criteria · Managing Constraints (PMI 6 constraints; QRA/CBR contingency) · Risk Assessment (integrated at 30/90D) · Conflict Resolution & Prioritization (HSE, asset integrity, production loss, human factors, opportunity cost…) · **Opportunity Identification (NEW)** · Change Control / **Break-in** for the frozen 30D plan · Plan Administration (documentation, data management, version control / source of truth).

### 3.6 Roles (clarified)
CEO/COO · SVP · **VP Operations (new emphasis for operational horizons)** · Asset Management · E&P Planning · **OPAA = Operations Planning and Activities Assurance** (coordinates 12M/90D/30D — *not* "P&S Team") · Plan Owners · Managers · Installation Manager/Superintendent · Responsible Person/Job Owner.

### 3.7 Performance & Continuous Improvement
- KPIs redefined: **Schedule Attainment** (with Schedule Shift Factor SF), **SPI** (Schedule Performance Indicator), **Plan Break-in**, **Plan Deletion**. Secondary: plan utilization, plan stability, work efficiency, disturbance/delay.
- AAR, Planning Compliance, Peer Review, Business Performance Review, Benchmarking, feedback loops across horizons.

### 3.8 Concept / Strategy
- New **Table 1 (Objectives)**: 11 integrated-planning objectives, each with Expected Behaviour (how) + Organizational Value (why) — HSE, value, decision-making, cost/resource efficiency, planning performance, production, cross-functional comms, common framework, role alignment, execution readiness, minimize NPT.
- Scope expanded to explicitly cover FDP, ADP, LTP (24M + outer years), and 12M/90D/30D/7D short-term planning.
- Explicit cross-references now added: **GN-3005** (LTP/IBP), **GN-3007** (operational horizons), **GL-001 FDP**, **GL-002 ADP**, **MPEP** (projects), **AACE RP 37R-06** (schedule levels).

---

## 4. Open items — DO NOT resolve; present as "requires stakeholder confirmation"

| # | Item | Conflict (both readings) | Confirm with |
|---|---|---|---|
| 1 | **ADP approval authority** | GL-002 **Scope** text says *"must be approved by Medco EP President Director"*; GL-002 **summary table** says Approval = *Medco EP CEO*; Rev 4 Table 1 uses *CEO/COO*. | Mas Fikri / Mas Robert |
| 2 | **FDP approval authority** | GL-001 **Scope** text says *"must be approved by Senior Manager Subsurface"*; GL-001 **summary table** says Approval = *Sr VP Asset*; Rev 4 Table 1 uses *Sr. VP Asset*. | Mas Fikri / Mas Robert |
| 3 | **90D/30D approval body** | GN-3007 uses OLT/OIM/OM chain; legacy Rev 3 Table 1 said *Field Manager*. Rev 4 adopted OIM/OM + VP Ops. | Kang Oi |
| 4 | **Legacy "Field Manager" language** may still appear in some Rev 4 body text (e.g., change-control section references "Field Manager (FM)") — conflicts with GN-3007 OIM/OM authority. | Kang Oi / Mas Fikri |
| 5 | **GN-3007 vs GN-3008** — the source procedure's cover reads `GN-00-3007` with a 4-horizon title, but its running header reads `GN-00-3008` with a 3-horizon title that drops 12-Month. A real defect **in the source**, not ours. | Kang Oi |
| 6 | Appendix C (activity inclusion) may lack a 12M column despite 12M being a formal horizon. | Mas Fikri |
| 7 | Corporate PIC for GN-3005 — Robert Cahyadi is the named preparer (strong lead) but not confirmed as ongoing contact. **A prior session invented "Mbak Alice" with zero basis — that name is void; never use it.** | Ridho |

---

## 5. Terminology — get these exactly right
- **OPAA** = Operations Planning and Activities Assurance (**not** "P&S Team").
- **GPT** = Gas Processing Tools (**not** an AI tool) — used for Short-Term Production Forecasting (STPF).
- **LTP** (Long-Term Plan), **not** LRP/LRP.
- **PMI PMBOK six constraints**: Scope, Schedule, Budget, Quality, Resources, Risk.
- **AACE RP 37R-06** — schedule levels (L1–L5), confirmed current.
- **Frozen** = the committed 30D plan after Gate 2.
- **Break-in** = controlled addition/change to the frozen 30D plan.

---

## 6. Rules for all agents
1. **Verify, don't assume.** Cite a document + section for every substantive claim.
2. **Minimal change.** Preserve valid Rev 3 content; change only where new/inconsistent/missing.
3. **Flag, don't silently resolve** conflicts (see §4).
4. **Never invent** names, hex codes, benefits, or facts. If unknown, say "unknown".
5. **Formal English** for all document/slide content; auditable rationale for every change.
6. Do **not** overwrite another agent's output file. Reference, don't recreate.

## 7. Environment note
LibreOffice `--convert-to pdf` is currently **failing in this environment** ("source file could not be loaded"), so pptx/docx→image rendering for visual QA may be unavailable. python-pptx, markitdown[pptx], openpyxl, pdftotext, and Pillow all work.
