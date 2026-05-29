---
document_id: QATL-ATLAS-1000-STA-120-129-02-126-README
title: "STA 120-129 · 02.126 — Micropropulsión y Control de Reacción (Subsection Index)"
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
subsection: "126"
subsection_title: "Micropropulsión y Control de Reacción"
primary_q_division: Q-SPACE
support_q_divisions: [Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON]
orb_function_support: [ORB-PMO, ORB-LEG]
safety_boundary: "precision-control critical; requires impulse-bit characterization, feed-system integrity, fault-tolerant actuation and lifetime-traceable calibration"
governance_class: baseline
version: 1.0.0
status: active
language: en
no_aaa_rule: true
---

# STA 120-129 · Section 02 · Subsection 126 — Micropropulsión y Control de Reacción

## 1. Purpose

Subsection-level index for *Micropropulsion and Reaction Control* (`126`) within STA `120-129` — *Propulsión Espacial Tradicional y Avanzada*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001].

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `126`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable] and the section index in [`../README.md`](../README.md).
- Safety boundary: **precision-control critical; requires impulse-bit characterization, feed-system integrity, fault-tolerant actuation and lifetime-traceable calibration**.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`126-000-General.md`](./126-000-General.md) | active |
| 010 | Micropropulsion and Reaction Control Controlled Definition | [`126-010-Micropropulsion-and-Reaction-Control-Controlled-Definition.md`](./126-010-Micropropulsion-and-Reaction-Control-Controlled-Definition.md) | active |
| 020 | Micropropulsion Families and Selection Criteria | [`126-020-Micropropulsion-Families-and-Selection-Criteria.md`](./126-020-Micropropulsion-Families-and-Selection-Criteria.md) | active |
| 030 | Cold Gas and Warm Gas Systems | [`126-030-Cold-Gas-and-Warm-Gas-Systems.md`](./126-030-Cold-Gas-and-Warm-Gas-Systems.md) | active |
| 040 | Monopropellant and Green Monopropellant Systems | [`126-040-Monopropellant-and-Green-Monopropellant-Systems.md`](./126-040-Monopropellant-and-Green-Monopropellant-Systems.md) | active |
| 050 | Micro Electric and Micro Chemical Thrusters | [`126-050-Micro-Electric-and-Micro-Chemical-Thrusters.md`](./126-050-Micro-Electric-and-Micro-Chemical-Thrusters.md) | active |
| 060 | Reaction Control Station Keeping and Attitude Functions | [`126-060-Reaction-Control-Station-Keeping-and-Attitude-Functions.md`](./126-060-Reaction-Control-Station-Keeping-and-Attitude-Functions.md) | active |
| 070 | Miniaturized Feed Storage and Integration | [`126-070-Miniaturized-Feed-Storage-and-Integration.md`](./126-070-Miniaturized-Feed-Storage-and-Integration.md) | active |
| 080 | Impulse Bit Resolution and Lifetime Metrics | [`126-080-Impulse-Bit-Resolution-and-Lifetime-Metrics.md`](./126-080-Impulse-Bit-Resolution-and-Lifetime-Metrics.md) | active |
| 090 | Safety and Assurance Boundaries | [`126-090-Safety-and-Assurance-Boundaries.md`](./126-090-Safety-and-Assurance-Boundaries.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `120-129` |
| Section | `02` — Propulsión Espacial Tradicional y Avanzada |
| Subsection | `126` — Micropropulsión y Control de Reacción |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON |
| ORB support | ORB-PMO, ORB-LEG |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/120-129_Propulsion-Espacial-Tradicional-y-Avanzada/126_Micropropulsion-y-Control-de-Reaccion/` |
| Document | `README.md` (this file) |

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).

[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).

[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).

[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.

[^n001]: **Note N-001** — Q+ATLANTIDE (with its ATLAS-1000 register subpart) is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
