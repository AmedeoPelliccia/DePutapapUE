---
document_id: QATL-ATLAS-1000-STA-110-119-01-115-README
title: "STA 110-119 · 01.115 — Fabricación, Ensamblaje e Integración Estructural (Subsection Index)"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
parent_baseline_doc: ../../../../organization/Q+ATLANTIDE.md
parent_architecture_doc: ../../README.md
parent_section_doc: ../README.md
architecture_code: STA
architecture_name: "Space Technology Architecture"
master_range: "100–199"
code_range: "110-119"
section: "01"
section_title: "Estructuras y Materiales Espaciales"
subsection: "115"
subsection_title: "Fabricación, Ensamblaje e Integración Estructural"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-MANUFACTURING, Q-DATAGOV, Q-INDUSTRY, Q-QA]
orb_function_support: [ORB-PMO, ORB-FIN]
linked_nodes:
  - "110_Estructuras-Orbitales"
  - "111_Materiales-Espaciales"
  - "112_Proteccion-Termica-y-Radiacion"
  - "113_Mecanismos-Espaciales-y-Desplegables"
  - "114_Cargas-Mecanicas-Vibracion-y-Choque"
safety_boundary: "structural manufacturing critical; requires controlled manufacturing process documentation, composite and weld process qualification, NDI coverage per fracture control plan, contamination control compliance, and full manufacturing traceability to DRB/MRB authority"
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · Section 01 · Subsection 115 — Fabricación, Ensamblaje e Integración Estructural

## 1. Purpose

Subsection-level index for *Fabricación, Ensamblaje e Integración Estructural* (`115`) within STA `110-119` — *Estructuras y Materiales Espaciales*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001]. It is designated **structural manufacturing critical**: all subsubjects require controlled manufacturing process documentation, composite and weld process qualification, NDI coverage per fracture control plan, contamination control compliance, and full manufacturing traceability to DRB/MRB authority.

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `115`; subsubjects `091`–`099` remain reserved.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Linked nodes: `110_Estructuras-Orbitales`, `111_Materiales-Espaciales`, `112_Proteccion-Termica-y-Radiacion`, `113_Mecanismos-Espaciales-y-Desplegables`, `114_Cargas-Mecanicas-Vibracion-y-Choque`.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`115-000-General.md`](./115-000-General.md) | active |
| 010 | Structural Manufacturing Processes and Controls | [`115-010-Structural-Manufacturing-Processes-and-Controls.md`](./115-010-Structural-Manufacturing-Processes-and-Controls.md) | active |
| 020 | Composite and Advanced Material Fabrication | [`115-020-Composite-and-Advanced-Material-Fabrication.md`](./115-020-Composite-and-Advanced-Material-Fabrication.md) | active |
| 030 | Metallic Structural Fabrication and Welding | [`115-030-Metallic-Structural-Fabrication-and-Welding.md`](./115-030-Metallic-Structural-Fabrication-and-Welding.md) | active |
| 040 | Assembly Tooling and Fixture Design | [`115-040-Assembly-Tooling-and-Fixture-Design.md`](./115-040-Assembly-Tooling-and-Fixture-Design.md) | active |
| 050 | Structural Integration and Interface Management | [`115-050-Structural-Integration-and-Interface-Management.md`](./115-050-Structural-Integration-and-Interface-Management.md) | active |
| 060 | Non-Destructive Inspection and Quality Control | [`115-060-Non-Destructive-Inspection-and-Quality-Control.md`](./115-060-Non-Destructive-Inspection-and-Quality-Control.md) | active |
| 070 | Cleanliness Contamination Control and Handling | [`115-070-Cleanliness-Contamination-Control-and-Handling.md`](./115-070-Cleanliness-Contamination-Control-and-Handling.md) | active |
| 080 | Manufacturing Qualification and Acceptance Programme | [`115-080-Manufacturing-Qualification-and-Acceptance-Programme.md`](./115-080-Manufacturing-Qualification-and-Acceptance-Programme.md) | active |
| 090 | Traceability Evidence and Lifecycle Governance | [`115-090-Traceability-Evidence-and-Lifecycle-Governance.md`](./115-090-Traceability-Evidence-and-Lifecycle-Governance.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `115` — Fabricación, Ensamblaje e Integración Estructural |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-MANUFACTURING, Q-DATAGOV, Q-INDUSTRY, Q-QA |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Safety boundary | structural manufacturing critical |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/115_Fabricacion-Ensamblaje-e-Integracion-Estructural/` |
| Document | `README.md` (this file) |
| Parent section | [`../README.md`](../README.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## Governance

Governed by [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md)[^baseline]. All subsubjects inherit `architecture_code = STA`, `primary_q_division = Q-SPACE`, `support_q_divisions = [Q-STRUCTURES, Q-MANUFACTURING, Q-DATAGOV, Q-INDUSTRY, Q-QA]`, and `governance_class = baseline`. Extensions under `091`–`099` shall preserve those header fields, declare the `safety_boundary`, and reuse the footnote set.

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).
[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.
[^n001]: **Note N-001** — Q+ATLANTIDE is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
