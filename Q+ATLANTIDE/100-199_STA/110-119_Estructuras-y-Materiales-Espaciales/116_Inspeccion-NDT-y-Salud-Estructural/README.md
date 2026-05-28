---
document_id: QATL-ATLAS-1000-STA-110-119-01-116-README
title: "STA 110-119 · 01.116 — Inspección NDT y Salud Estructural (Subsection Index)"
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
subsection: "116"
subsection_title: "Inspección NDT y Salud Estructural"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-QA, Q-DATAGOV, Q-SENSORS, Q-MANUFACTURING]
orb_function_support: [ORB-PMO, ORB-FIN]
linked_nodes:
  - "111_Materiales-Espaciales"
  - "113_Mecanismos-Espaciales-y-Desplegables"
  - "114_Cargas-Mecanicas-Vibracion-y-Choque"
  - "115_Fabricacion-Ensamblaje-e-Integracion-Estructural"
safety_boundary: "fracture-critical inspection and structural health monitoring; requires qualified NDI procedures and personnel, validated SHM architecture, traceable damage-tolerance evidence, and full traceability to fracture-control authority"
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · Section 01 · Subsection 116 — Inspección NDT y Salud Estructural

## 1. Purpose

Subsection-level index for *Inspección NDT y Salud Estructural* (`116`) within STA `110-119` — *Estructuras y Materiales Espaciales*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001]. It is designated **fracture-critical inspection and structural health monitoring**: all subsubjects require qualified NDI procedures and personnel, validated SHM architecture, traceable damage-tolerance evidence, and full traceability to fracture-control authority.

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `116`; subsubjects `091`–`099` remain reserved.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Linked nodes: `111_Materiales-Espaciales`, `113_Mecanismos-Espaciales-y-Desplegables`, `114_Cargas-Mecanicas-Vibracion-y-Choque`, `115_Fabricacion-Ensamblaje-e-Integracion-Estructural`.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`116-000-General.md`](./116-000-General.md) | active |
| 010 | NDT Methods Selection and Qualification | [`116-010-NDT-Methods-Selection-and-Qualification.md`](./116-010-NDT-Methods-Selection-and-Qualification.md) | active |
| 020 | Ultrasonic and Phased-Array Inspection | [`116-020-Ultrasonic-and-Phased-Array-Inspection.md`](./116-020-Ultrasonic-and-Phased-Array-Inspection.md) | active |
| 030 | Radiographic and Computed-Tomography Inspection | [`116-030-Radiographic-and-Computed-Tomography-Inspection.md`](./116-030-Radiographic-and-Computed-Tomography-Inspection.md) | active |
| 040 | Surface and Electromagnetic NDT Methods | [`116-040-Surface-and-Electromagnetic-NDT-Methods.md`](./116-040-Surface-and-Electromagnetic-NDT-Methods.md) | active |
| 050 | Composite and Bonded-Joint NDI | [`116-050-Composite-and-Bonded-Joint-NDI.md`](./116-050-Composite-and-Bonded-Joint-NDI.md) | active |
| 060 | Structural Health Monitoring Architecture | [`116-060-Structural-Health-Monitoring-Architecture.md`](./116-060-Structural-Health-Monitoring-Architecture.md) | active |
| 070 | SHM Sensors and Data Acquisition | [`116-070-SHM-Sensors-and-Data-Acquisition.md`](./116-070-SHM-Sensors-and-Data-Acquisition.md) | active |
| 080 | Diagnostics Prognostics and Damage-Tolerance Integration | [`116-080-Diagnostics-Prognostics-and-Damage-Tolerance-Integration.md`](./116-080-Diagnostics-Prognostics-and-Damage-Tolerance-Integration.md) | active |
| 090 | Traceability Evidence and Lifecycle Governance | [`116-090-Traceability-Evidence-and-Lifecycle-Governance.md`](./116-090-Traceability-Evidence-and-Lifecycle-Governance.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `116` — Inspección NDT y Salud Estructural |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-QA, Q-DATAGOV, Q-SENSORS, Q-MANUFACTURING |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Safety boundary | fracture-critical inspection and SHM |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/116_Inspeccion-NDT-y-Salud-Estructural/` |
| Document | `README.md` (this file) |
| Parent section | [`../README.md`](../README.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## Governance

Governed by [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md)[^baseline]. All subsubjects inherit `architecture_code = STA`, `primary_q_division = Q-SPACE`, `support_q_divisions = [Q-STRUCTURES, Q-QA, Q-DATAGOV, Q-SENSORS, Q-MANUFACTURING]`, and `governance_class = baseline`. Extensions under `091`–`099` shall preserve those header fields, declare the `safety_boundary`, and reuse the footnote set.

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).
[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.
[^n001]: **Note N-001** — Q+ATLANTIDE is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
