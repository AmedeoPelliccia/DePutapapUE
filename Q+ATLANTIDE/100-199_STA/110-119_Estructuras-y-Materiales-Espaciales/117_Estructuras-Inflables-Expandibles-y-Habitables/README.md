---
document_id: QATL-ATLAS-1000-STA-110-119-01-117-README
title: "STA 110-119 · 01.117 — Estructuras Inflables, Expandibles y Habitables (Subsection Index)"
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
subsection: "117"
subsection_title: "Estructuras Inflables, Expandibles y Habitables"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY]
orb_function_support: [ORB-PMO, ORB-FIN]
linked_nodes:
  - "110_Estructuras-Orbitales"
  - "111_Materiales-Espaciales"
  - "112_Proteccion-Termica-y-Radiacion"
  - "113_Mecanismos-Espaciales-y-Desplegables"
  - "114_Cargas-Mecanicas-Vibracion-y-Choque"
  - "115_Fabricacion-Ensamblaje-e-Integracion-Estructural"
  - "116_Inspeccion-NDT-y-Salud-Estructural"
safety_boundary: "habitable pressure-vessel critical; requires qualified soft-goods materials, demonstrated leak-before-burst margin, MMOD protection, controlled deployment kinematics, and full traceability for human-rated certification"
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · Section 01 · Subsection 117 — Estructuras Inflables, Expandibles y Habitables

## 1. Purpose

Subsection-level index for *Estructuras Inflables, Expandibles y Habitables* (`117`) within STA `110-119` — *Estructuras y Materiales Espaciales*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001]. It is designated **habitable pressure-vessel critical**: all subsubjects require qualified soft-goods materials, demonstrated leak-before-burst margin, MMOD protection, controlled deployment kinematics, and full traceability for human-rated certification.

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `117`; subsubjects `091`–`099` remain reserved.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Linked nodes: `110_Estructuras-Orbitales`, `111_Materiales-Espaciales`, `112_Proteccion-Termica-y-Radiacion`, `113_Mecanismos-Espaciales-y-Desplegables`, `114_Cargas-Mecanicas-Vibracion-y-Choque`, `115_Fabricacion-Ensamblaje-e-Integracion-Estructural`, `116_Inspeccion-NDT-y-Salud-Estructural`.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`117-000-General.md`](./117-000-General.md) | active |
| 010 | Soft-Goods Materials and Restraint Layer | [`117-010-Soft-Goods-Materials-and-Restraint-Layer.md`](./117-010-Soft-Goods-Materials-and-Restraint-Layer.md) | active |
| 020 | Bladder Pressure-Containment and Leak Control | [`117-020-Bladder-Pressure-Containment-and-Leak-Control.md`](./117-020-Bladder-Pressure-Containment-and-Leak-Control.md) | active |
| 030 | MMOD and Thermal Multi-Layer Protection | [`117-030-MMOD-and-Thermal-Multi-Layer-Protection.md`](./117-030-MMOD-and-Thermal-Multi-Layer-Protection.md) | active |
| 040 | Packing Deployment and Inflation Subsystem | [`117-040-Packing-Deployment-and-Inflation-Subsystem.md`](./117-040-Packing-Deployment-and-Inflation-Subsystem.md) | active |
| 050 | Rigidization and Post-Deployment Stiffness | [`117-050-Rigidization-and-Post-Deployment-Stiffness.md`](./117-050-Rigidization-and-Post-Deployment-Stiffness.md) | active |
| 060 | Hard-Soft Interface and Penetration Management | [`117-060-Hard-Soft-Interface-and-Penetration-Management.md`](./117-060-Hard-Soft-Interface-and-Penetration-Management.md) | active |
| 070 | Habitability ECLSS Acoustic and Human-Factors Integration | [`117-070-Habitability-ECLSS-Acoustic-and-Human-Factors-Integration.md`](./117-070-Habitability-ECLSS-Acoustic-and-Human-Factors-Integration.md) | active |
| 080 | Qualification Acceptance and Human-Rating Programme | [`117-080-Qualification-Acceptance-and-Human-Rating-Programme.md`](./117-080-Qualification-Acceptance-and-Human-Rating-Programme.md) | active |
| 090 | Traceability Evidence and Lifecycle Governance | [`117-090-Traceability-Evidence-and-Lifecycle-Governance.md`](./117-090-Traceability-Evidence-and-Lifecycle-Governance.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `117` — Estructuras Inflables, Expandibles y Habitables |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Safety boundary | habitable pressure-vessel critical |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/117_Estructuras-Inflables-Expandibles-y-Habitables/` |
| Document | `README.md` (this file) |
| Parent section | [`../README.md`](../README.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## Governance

Governed by [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md)[^baseline]. All subsubjects inherit `architecture_code = STA`, `primary_q_division = Q-SPACE`, `support_q_divisions = [Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY]`, and `governance_class = baseline`. Extensions under `091`–`099` shall preserve those header fields, declare the `safety_boundary`, and reuse the footnote set.

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).
[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.
[^n001]: **Note N-001** — Q+ATLANTIDE is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
