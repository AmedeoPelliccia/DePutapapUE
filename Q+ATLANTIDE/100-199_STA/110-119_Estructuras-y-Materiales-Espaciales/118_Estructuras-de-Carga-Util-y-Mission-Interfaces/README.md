---
document_id: QATL-ATLAS-1000-STA-110-119-01-118-README
title: "STA 110-119 · 01.118 — Estructuras de Carga Útil y Mission Interfaces (Subsection Index)"
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
subsection: "118"
subsection_title: "Estructuras de Carga Útil y Mission Interfaces"
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
  - "117_Estructuras-Inflables-Expandibles-y-Habitables"
safety_boundary: "mission-critical payload-to-bus interface; requires controlled envelope and coordinate frame, qualified separation system with low-shock release, redundant umbilical disconnects, alignment and pointing stability budgets, and full mission-readiness evidence"
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · Section 01 · Subsection 118 — Estructuras de Carga Útil y Mission Interfaces

## 1. Purpose

Subsection-level index for *Estructuras de Carga Útil y Mission Interfaces* (`118`) within STA `110-119` — *Estructuras y Materiales Espaciales*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001]. It is designated **mission-critical payload-to-bus interface**: all subsubjects require controlled mechanical envelope and coordinate frames, qualified separation systems with low-shock release, redundant umbilical disconnects, alignment / pointing stability budgets, and full mission-readiness evidence.

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `118`; subsubjects `091`–`099` remain reserved.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Linked nodes: `110_Estructuras-Orbitales`, `111_Materiales-Espaciales`, `112_Proteccion-Termica-y-Radiacion`, `113_Mecanismos-Espaciales-y-Desplegables`, `114_Cargas-Mecanicas-Vibracion-y-Choque`, `115_Fabricacion-Ensamblaje-e-Integracion-Estructural`, `116_Inspeccion-NDT-y-Salud-Estructural`, `117_Estructuras-Inflables-Expandibles-y-Habitables`.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`118-000-General.md`](./118-000-General.md) | active |
| 010 | Payload Mechanical Envelope and Coordinate System | [`118-010-Payload-Mechanical-Envelope-and-Coordinate-System.md`](./118-010-Payload-Mechanical-Envelope-and-Coordinate-System.md) | active |
| 020 | Payload-to-Bus Mechanical Interface and Separation System | [`118-020-Payload-to-Bus-Mechanical-Interface-and-Separation-System.md`](./118-020-Payload-to-Bus-Mechanical-Interface-and-Separation-System.md) | active |
| 030 | Payload Electrical Data and Fluid Umbilicals | [`118-030-Payload-Electrical-Data-and-Fluid-Umbilicals.md`](./118-030-Payload-Electrical-Data-and-Fluid-Umbilicals.md) | active |
| 040 | Mission-Adapter and Dispenser Architecture | [`118-040-Mission-Adapter-and-Dispenser-Architecture.md`](./118-040-Mission-Adapter-and-Dispenser-Architecture.md) | active |
| 050 | Secondary-Payload and Rideshare Accommodation | [`118-050-Secondary-Payload-and-Rideshare-Accommodation.md`](./118-050-Secondary-Payload-and-Rideshare-Accommodation.md) | active |
| 060 | Pointing Stability and Alignment Interfaces | [`118-060-Pointing-Stability-and-Alignment-Interfaces.md`](./118-060-Pointing-Stability-and-Alignment-Interfaces.md) | active |
| 070 | Payload Thermal and Contamination Interfaces | [`118-070-Payload-Thermal-and-Contamination-Interfaces.md`](./118-070-Payload-Thermal-and-Contamination-Interfaces.md) | active |
| 080 | Verification Acceptance and Mission Readiness | [`118-080-Verification-Acceptance-and-Mission-Readiness.md`](./118-080-Verification-Acceptance-and-Mission-Readiness.md) | active |
| 090 | Traceability Evidence and Lifecycle Governance | [`118-090-Traceability-Evidence-and-Lifecycle-Governance.md`](./118-090-Traceability-Evidence-and-Lifecycle-Governance.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `118` — Estructuras de Carga Útil y Mission Interfaces |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Safety boundary | mission-critical payload-to-bus interface |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/118_Estructuras-de-Carga-Util-y-Mission-Interfaces/` |
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
