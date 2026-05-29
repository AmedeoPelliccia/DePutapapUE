---
document_id: QATL-ATLAS-1000-STA-110-119-01-115-000-GENERAL
title: "STA 110-119 · 115-000 — General"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
architecture_code: STA
subsection: "115"
subsection_title: "Fabricación, Ensamblaje e Integración Estructural"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY]
governance_class: baseline
version: 1.0.0
status: active
language: en
subsubject: "000"
subsubject_title: "General"
---

# STA 110-119 · 115-000 — General

## 1. Purpose

Overview entry-point for the *Fabricación, Ensamblaje e Integración Estructural* subsection within the `110-119` code range (Section `01` — *Estructuras y Materiales Espaciales*) of the **STA** architecture band (*Space Technology Architecture*, master range `100–199`).

This subsubject (`000 Overview`) introduces the STA 110-119.115 slice and links it to the controlled Q+ATLANTIDE baseline[^baseline]. It establishes the structural manufacturing framework governing manufacturing process control, composite and metallic fabrication, assembly tooling, structural integration and interface management, NDI and quality control, cleanliness and contamination control, and manufacturing qualification and acceptance for Q+ATLANTIDE space missions. This subsection is designated **structural manufacturing critical**.

## 2. Scope

- Covers the *Fabricación, Ensamblaje e Integración Estructural* slice of parent code range `110-119`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Populated subsubject set (`010`–`090`) indexed in [`README.md`](./README.md).
- Concepts in scope:
  - **Structural Manufacturing Processes and Controls** (`010`) — manufacturing process register, process specification control, first-article inspection (FAI), non-conformance/MRB flow per ECSS-E-ST-32-01C[^ecsse3201] and NASA-STD-6016[^nasastd6016].
  - **Composite and Advanced Material Fabrication** (`020`) — lay-up, autoclave and OOA cure, RTM, fibre placement, process qualification per CMH-17[^cmh17].
  - **Metallic Structural Fabrication and Welding** (`030`) — machining, forming, FSW, EBW, TIG weld process qualification per ECSS-Q-ST-70-39C[^ecssq7039].
  - **Assembly Tooling and Fixture Design** (`040`) — assembly jigs, CMM tooling certification, tooling accuracy classes, maintenance programme.
  - **Structural Integration and Interface Management** (`050`) — assembly sequence, ICD management, fit-check, torque control, hazardous operations, assembly records.
  - **Non-Destructive Inspection and Quality Control** (`060`) — UT, RT/CT, PT, ET methods; NDI plan from fracture control plan; FCI protocol per NASA-STD-5009[^nasastd5009].
  - **Cleanliness, Contamination Control and Handling** (`070`) — ISO 14644-1 classes, TMC limits, cleaning procedures, packaging and transport per ECSS-Q-ST-70-01C[^ecssq7001].
  - **Manufacturing Qualification and Acceptance Programme** (`080`) — qualification witness coupons, ATA, FAQT, ADP content, MRR gate.
  - **Traceability, Evidence and Lifecycle Governance** (`090`) — manufacturing evidence package, DRB/MRB authority, PDR/CDR/MRR/Acceptance review gates.

## 3. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `115` — Fabricación, Ensamblaje e Integración Estructural |
| Subsubject | `000` — Overview |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/115_Fabricacion-Ensamblaje-e-Integracion-Estructural/` |
| Document | `115-000-General.md` (this file) |
| Parent subsection | [`README.md`](./README.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row.
[^gov]: **Governance class** — `baseline` denotes documents under controlled change management.
[^ecsse3201]: **ECSS-E-ST-32-01C** — Space Engineering: Structural General Requirements.
[^nasastd6016]: **NASA-STD-6016** — Standard Materials and Processes Requirements for Spacecraft.
[^cmh17]: **CMH-17** — Composite Materials Handbook.
[^ecssq7039]: **ECSS-Q-ST-70-39C** — Welding of Metallic Materials for Flight Hardware.
[^nasastd5009]: **NASA-STD-5009** — NDE Requirements for Fracture-Critical Metallic Components.
[^ecssq7001]: **ECSS-Q-ST-70-01C** — Cleanliness and Contamination Control.
