---
document_id: QATL-ATLAS-1000-STA-120-129-02-127-README
title: "STA 120-129 · 02.127 — Gestión de Propelente y Reabastecimiento en Órbita (Subsection Index)"
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
subsection: "127"
subsection_title: "Gestión de Propelente y Reabastecimiento en Órbita"
primary_q_division: Q-SPACE
support_q_divisions: [Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON]
orb_function_support: [ORB-PMO, ORB-LEG]
safety_boundary: "fluid-transfer and contamination critical; requires microgravity-fluid controls, interface compatibility, leak containment and operational assurance gates"
governance_class: baseline
version: 1.0.0
status: active
language: en
no_aaa_rule: true
---

# STA 120-129 · Section 02 · Subsection 127 — Gestión de Propelente y Reabastecimiento en Órbita

## 1. Purpose

Subsection-level index for *Propellant Management and In-Orbit Refueling* (`127`) within STA `120-129` — *Propulsión Espacial Tradicional y Avanzada*.

This subsection is part of the **ATLAS-1000** register, a subpart of the controlled **Q+ATLANTIDE** baseline[^baseline][^n001].

## 2. Scope

- Populates the subsubject namespace `000`–`090` of subsection `127`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable] and the section index in [`../README.md`](../README.md).
- Safety boundary: **fluid-transfer and contamination critical; requires microgravity-fluid controls, interface compatibility, leak containment and operational assurance gates**.

## 3. Subsubject Index

| NNN | Title | Document | Status |
|---:|---|---|---|
| 000 | General | [`127-000-General.md`](./127-000-General.md) | active |
| 010 | Propellant Management and In-Orbit Refueling Controlled Definition | [`127-010-Propellant-Management-and-In-Orbit-Refueling-Controlled-Definition.md`](./127-010-Propellant-Management-and-In-Orbit-Refueling-Controlled-Definition.md) | active |
| 020 | Propellant Storage Types and Selection Criteria | [`127-020-Propellant-Storage-Types-and-Selection-Criteria.md`](./127-020-Propellant-Storage-Types-and-Selection-Criteria.md) | active |
| 030 | Cryogenic Storage and Boil Off Management | [`127-030-Cryogenic-Storage-and-Boil-Off-Management.md`](./127-030-Cryogenic-Storage-and-Boil-Off-Management.md) | active |
| 040 | Propellant Gauging and Microgravity Fluid Behavior | [`127-040-Propellant-Gauging-and-Microgravity-Fluid-Behavior.md`](./127-040-Propellant-Gauging-and-Microgravity-Fluid-Behavior.md) | active |
| 050 | Fluid Transfer Couplings and Interfaces | [`127-050-Fluid-Transfer-Couplings-and-Interfaces.md`](./127-050-Fluid-Transfer-Couplings-and-Interfaces.md) | active |
| 060 | On Orbit Refueling and Depot Interface Boundaries | [`127-060-On-Orbit-Refueling-and-Depot-Interface-Boundaries.md`](./127-060-On-Orbit-Refueling-and-Depot-Interface-Boundaries.md) | active |
| 070 | ISRU Derived Propellant Interface Boundaries | [`127-070-ISRU-Derived-Propellant-Interface-Boundaries.md`](./127-070-ISRU-Derived-Propellant-Interface-Boundaries.md) | active |
| 080 | Contamination Compatibility and Operational Limits | [`127-080-Contamination-Compatibility-and-Operational-Limits.md`](./127-080-Contamination-Compatibility-and-Operational-Limits.md) | active |
| 090 | Safety and Assurance Boundaries | [`127-090-Safety-and-Assurance-Boundaries.md`](./127-090-Safety-and-Assurance-Boundaries.md) | active |

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `120-129` |
| Section | `02` — Propulsión Espacial Tradicional y Avanzada |
| Subsection | `127` — Gestión de Propelente y Reabastecimiento en Órbita |
| Subsubject namespace | `000`–`090` (10 active); higher reserved |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-GREENTECH, Q-STRUCTURES, Q-DATAGOV, Q-HPC, Q-HORIZON |
| ORB support | ORB-PMO, ORB-LEG |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/120-129_Propulsion-Espacial-Tradicional-y-Avanzada/127_Gestion-de-Propelente-y-Reabastecimiento-en-Orbita/` |
| Document | `README.md` (this file) |

## 5. References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).

[^archtable]: **§3 — Architecture Table (parent)** — [`../../README.md` §3](../../README.md#3-architecture-table).

[^qdiv]: **Q-Division authority** — [`organization/Q-Divisions/`](../../../../organization/Q-Divisions/).

[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.

[^n001]: **Note N-001** — Q+ATLANTIDE (with its ATLAS-1000 register subpart) is a taxonomy and traceability ecosystem, not an organization chart. See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).
