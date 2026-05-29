---
document_id: QATL-ATLAS-1000-STA-120-129-02-128-README
title: "STA 120-129 · 02.128 — Integración de Propulsión e Interfaz GNC (Subsection Index)"
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
subsection: "128"
subsection_title: "Integración de Propulsión e Interfaz GNC"
primary_q_division: Q-SPACE
support_q_divisions: [Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON]
orb_function_support: [ORB-PMO, ORB-LEG]
safety_boundary: "mission-control loop critical; requires closed-loop stability evidence, contamination controls, structural-thermal compatibility and fault-managed mode transitions"
governance_class: baseline
version: 1.0.0
status: active
language: en
no_aaa_rule: true
---

# STA 120-129 · Section 02 · Subsection 128 — Integración de Propulsión e Interfaz GNC

## 1. Purpose

Subsection-level index for *Propulsion Integration and GNC Interface* (`128`) within STA `120-129` — *Propulsión Espacial Tradicional y Avanzada*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001].

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `128`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable] and the section index in [`../README.md`](../README.md).
- Safety boundary: **mission-control loop critical; requires closed-loop stability evidence, contamination controls, structural-thermal compatibility and fault-managed mode transitions**.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`128-000-General.md`](./128-000-General.md) | active |
| 010 | Propulsion Integration and GNC Interface Controlled Definition | [`128-010-Propulsion-Integration-and-GNC-Interface-Controlled-Definition.md`](./128-010-Propulsion-Integration-and-GNC-Interface-Controlled-Definition.md) | active |
| 020 | Delta V Budgeting and Mission Propulsion Sizing | [`128-020-Delta-V-Budgeting-and-Mission-Propulsion-Sizing.md`](./128-020-Delta-V-Budgeting-and-Mission-Propulsion-Sizing.md) | active |
| 030 | Thrust Vector Control and Pointing | [`128-030-Thrust-Vector-Control-and-Pointing.md`](./128-030-Thrust-Vector-Control-and-Pointing.md) | active |
| 040 | Propulsion GNC Closed Loop Coupling | [`128-040-Propulsion-GNC-Closed-Loop-Coupling.md`](./128-040-Propulsion-GNC-Closed-Loop-Coupling.md) | active |
| 050 | Plume Impingement and Contamination Interfaces | [`128-050-Plume-Impingement-and-Contamination-Interfaces.md`](./128-050-Plume-Impingement-and-Contamination-Interfaces.md) | active |
| 060 | Structural Thermal and Mechanical Integration | [`128-060-Structural-Thermal-and-Mechanical-Integration.md`](./128-060-Structural-Thermal-and-Mechanical-Integration.md) | active |
| 070 | Redundancy Fault Management and Mode Transitions | [`128-070-Redundancy-Fault-Management-and-Mode-Transitions.md`](./128-070-Redundancy-Fault-Management-and-Mode-Transitions.md) | active |
| 080 | Integration Verification and Performance Metrics | [`128-080-Integration-Verification-and-Performance-Metrics.md`](./128-080-Integration-Verification-and-Performance-Metrics.md) | active |
| 090 | Safety and Assurance Boundaries | [`128-090-Safety-and-Assurance-Boundaries.md`](./128-090-Safety-and-Assurance-Boundaries.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `120-129` |
| Section | `02` — Propulsión Espacial Tradicional y Avanzada |
| Subsection | `128` — Integración de Propulsión e Interfaz GNC |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON |
| ORB support | ORB-PMO, ORB-LEG |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/120-129_Propulsion-Espacial-Tradicional-y-Avanzada/128_Integracion-de-Propulsion-e-Interfaz-GNC/` |
| Document | `README.md` (this file) |

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).

[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).

[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).

[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.

[^n001]: **Note N-001** — Q+ATLANTIDE (with its ATLAS-1000 register subpart) is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
