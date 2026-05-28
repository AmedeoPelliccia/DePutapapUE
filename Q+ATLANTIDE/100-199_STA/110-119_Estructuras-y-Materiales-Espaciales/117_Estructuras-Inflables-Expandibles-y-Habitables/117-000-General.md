---
document_id: QATL-ATLAS-1000-STA-110-119-01-117-000-GENERAL
title: "STA 110-119 · 117-000 — General"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
architecture_code: STA
subsection: "117"
subsection_title: "Estructuras Inflables, Expandibles y Habitables"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY]
governance_class: baseline
version: 1.0.0
status: active
language: en
subsubject: "000"
subsubject_title: "General"
---

# STA 110-119 · 117-000 — General

## 1. Purpose

Overview entry-point for the *Estructuras Inflables, Expandibles y Habitables* subsection within the `110-119` code range (Section `01` — *Estructuras y Materiales Espaciales*) of the **STA** architecture band (*Space Technology Architecture*, master range `100–199`).

This subsubject (`000 Overview`) introduces the STA 110-119.117 slice and links it to the controlled Q+ATLANTIDE baseline[^baseline]. It establishes the inflatable / expandable / habitable structures framework governing soft-goods materials and restraint layers, bladder pressure containment, MMOD and thermal multi-layer protection, packing/deployment/inflation, post-deployment rigidization, hard-soft interfaces, habitability integration, qualification and human-rating for Q+ATLANTIDE space missions. This subsection is designated **habitable pressure-vessel critical**.

## 2. Scope

- Covers the *Estructuras Inflables, Expandibles y Habitables* slice of parent code range `110-119`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Populated subsubject set (`010`–`090`) indexed in [`README.md`](./README.md).
- Concepts in scope:
  - **Soft-Goods Materials and Restraint Layer** (`010`) — Vectran, Kevlar, Nextel webbing and weaves; allowables per CMH-17[^cmh17] and ASTM F3208[^astmf3208]; strap-and-cord architecture carrying primary pressure load.
  - **Bladder Pressure-Containment and Leak Control** (`020`) — multi-layer urethane / EVOH / Nomex bladder; leak rate ≤ 1 × 10⁻³ scc/s; helium leak test per ASTM E499 and ECSS-Q-ST-70-15C[^ecssqst7015].
  - **MMOD and Thermal Multi-Layer Protection** (`030`) — Nextel + Kevlar + foam spacer Whipple-type stack per NASA-HDBK-6003[^nasahdbk6003]; MLI per ECSS-E-ST-31C[^ecsseSt31]; AO and UV barrier.
  - **Packing Deployment and Inflation Subsystem** (`040`) — stowage volume fraction, controlled inflation pressure ramp, redundant inflation gas tanks, deployment kinematics per ECSS-E-ST-33-01C[^ecsseSt3301].
  - **Rigidization and Post-Deployment Stiffness** (`050`) — pressure-stabilized vs UV-cure resin vs thermoset / sub-Tg shape-memory architectures; modal stiffness validation post-deployment.
  - **Hard-Soft Interface and Penetration Management** (`060`) — metallic bulkhead-to-soft-goods clamp rings, hatch / window / utility feedthrough seals, fatigue management at the interface ring.
  - **Habitability ECLSS Acoustic and Human-Factors Integration** (`070`) — internal outfitting, acoustic treatment ≤ NC-50, ECLSS interfaces, human-factors per NASA-STD-3001 Vol. 2[^nasastd3001].
  - **Qualification Acceptance and Human-Rating Programme** (`080`) — burst, creep-rupture, MMOD impact, vacuum-thermal-cycling, deployment qualification per ECSS-E-ST-32-01C[^ecsseSt3201] and NASA-STD-5012[^nasastd5012]; human-rating per NASA-STD-3001 Vol. 1.
  - **Traceability, Evidence and Lifecycle Governance** (`090`) — soft-goods lot traceability, burst-test evidence, DRB/MRB authority, PDR/CDR/QTR/MRR review gates.

## 3. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `117` — Estructuras Inflables, Expandibles y Habitables |
| Subsubject | `000` — Overview |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/117_Estructuras-Inflables-Expandibles-y-Habitables/` |
| Document | `117-000-General.md` (this file) |
| Parent subsection | [`README.md`](./README.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row.
[^gov]: **Governance class** — `baseline` denotes documents under controlled change management.
[^ecsseSt3201]: **ECSS-E-ST-32-01C** — Space Engineering: Structural General Requirements.
[^ecsseSt3301]: **ECSS-E-ST-33-01C** — Space Engineering: Mechanisms.
[^ecsseSt31]: **ECSS-E-ST-31C** — Space Engineering: Thermal Control General Requirements.
[^ecssqst7015]: **ECSS-Q-ST-70-15C** — Space product assurance: Non-destructive testing.
[^nasastd3001]: **NASA-STD-3001 Vol. 1 & 2** — Space Flight Human-System Standard.
[^nasastd5012]: **NASA-STD-5012** — Strength and Life Assessment Requirements for Liquid-Fueled Space Propulsion System Engines and applicable structural elements.
[^nasahdbk6003]: **NASA-HDBK-6003** — Application of Data Matrix Identification Symbols / MMOD design reference.
[^astmf3208]: **ASTM F3208** — Standard Practice for Conditioning and Testing of Soft Goods.
[^cmh17]: **CMH-17** — Composite Materials Handbook.
