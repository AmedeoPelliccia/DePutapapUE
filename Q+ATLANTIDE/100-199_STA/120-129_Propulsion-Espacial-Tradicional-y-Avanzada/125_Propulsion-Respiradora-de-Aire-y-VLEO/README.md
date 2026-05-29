---
document_id: QATL-ATLAS-1000-STA-120-129-02-125-README
title: "STA 120-129 · 02.125 — Propulsión Respiradora de Aire y VLEO (Subsection Index)"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
parent_baseline_doc: ../../../../organization/Q+ATLANTIDE.md
parent_architecture_doc: ../../README.md
parent_section_doc: ../README.md
architecture_code: STA
architecture_name: "Space Technology Architecture"
master_range: "100–199"
code_range: "120-129"
section: "02"
section_title: "Propulsión Espacial Tradicional y Avanzada"
subsection: "125"
subsection_title: "Propulsión Respiradora de Aire y VLEO"
primary_q_division: Q-SPACE
support_q_divisions: [Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON]
orb_function_support: [ORB-PMO, ORB-LEG]
safety_boundary: "VLEO drag-compensation critical; requires intake-contamination control, power-thermal closure, duty-cycle discipline and verified lifetime margins"
governance_class: baseline
version: 1.0.0
status: active
language: en
no_aaa_rule: true
---

# STA 120-129 · Section 02 · Subsection 125 — Propulsión Respiradora de Aire y VLEO

## 1. Purpose

Subsection-level index for *Air-Breathing and VLEO Propulsion* (`125`) within STA `120-129` — *Propulsión Espacial Tradicional y Avanzada*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001].

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `125`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable] and the section index in [`../README.md`](../README.md).
- Safety boundary: **VLEO drag-compensation critical; requires intake-contamination control, power-thermal closure, duty-cycle discipline and verified lifetime margins**.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`125-000-General.md`](./125-000-General.md) | active |
| 010 | Air-Breathing and VLEO Propulsion Controlled Definition | [`125-010-Air-Breathing-and-VLEO-Propulsion-Controlled-Definition.md`](./125-010-Air-Breathing-and-VLEO-Propulsion-Controlled-Definition.md) | active |
| 020 | VLEO Atmospheric Environment and Selection Criteria | [`125-020-VLEO-Atmospheric-Environment-and-Selection-Criteria.md`](./125-020-VLEO-Atmospheric-Environment-and-Selection-Criteria.md) | active |
| 030 | Atmosphere Breathing Electric Propulsion ABEP | [`125-030-Atmosphere-Breathing-Electric-Propulsion-ABEP.md`](./125-030-Atmosphere-Breathing-Electric-Propulsion-ABEP.md) | active |
| 040 | Intake and Collector Design | [`125-040-Intake-and-Collector-Design.md`](./125-040-Intake-and-Collector-Design.md) | active |
| 050 | Ionization and Acceleration Stages | [`125-050-Ionization-and-Acceleration-Stages.md`](./125-050-Ionization-and-Acceleration-Stages.md) | active |
| 060 | Power and Thermal Interfaces | [`125-060-Power-and-Thermal-Interfaces.md`](./125-060-Power-and-Thermal-Interfaces.md) | active |
| 070 | Drag Compensation and Orbit Maintenance | [`125-070-Drag-Compensation-and-Orbit-Maintenance.md`](./125-070-Drag-Compensation-and-Orbit-Maintenance.md) | active |
| 080 | Performance Duty Cycle and Lifetime Metrics | [`125-080-Performance-Duty-Cycle-and-Lifetime-Metrics.md`](./125-080-Performance-Duty-Cycle-and-Lifetime-Metrics.md) | active |
| 090 | Testing and Assurance Boundaries | [`125-090-Testing-and-Assurance-Boundaries.md`](./125-090-Testing-and-Assurance-Boundaries.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `120-129` |
| Section | `02` — Propulsión Espacial Tradicional y Avanzada |
| Subsection | `125` — Propulsión Respiradora de Aire y VLEO |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON |
| ORB support | ORB-PMO, ORB-LEG |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/120-129_Propulsion-Espacial-Tradicional-y-Avanzada/125_Propulsion-Respiradora-de-Aire-y-VLEO/` |
| Document | `README.md` (this file) |

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).

[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).

[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).

[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.

[^n001]: **Note N-001** — Q+ATLANTIDE (with its ATLAS-1000 register subpart) is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
