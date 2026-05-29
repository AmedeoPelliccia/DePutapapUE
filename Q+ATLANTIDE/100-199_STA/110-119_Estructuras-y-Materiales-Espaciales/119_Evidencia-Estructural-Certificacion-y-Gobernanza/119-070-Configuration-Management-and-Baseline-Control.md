---
document_id: QATL-ATLAS-1000-STA-110-119-01-119-070
title: "STA 110-119 · 119-070 — Configuration Management and Baseline Control"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
architecture_code: STA
subsection: "119"
subsubject: "070"
subsubject_title: "Configuration Management and Baseline Control"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY]
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · 119-070 — Configuration Management and Baseline Control

## 1. Purpose

Defines the **configuration management (CM)** and **baseline control** framework for the Q+ATLANTIDE STA structural product: functional / allocated / product baselines, ICDs, Engineering Change Notices (ECN), Engineering Change Proposals (ECP), Change Control Board (CCB) and as-designed / as-built / as-maintained reconciliation per ECSS-M-ST-40C[^ecssmSt40] and ISO 10007[^iso10007].

## 2. Scope

- Covers the *Configuration Management and Baseline Control* subsubject (`070`) of subsection `119`.
- Concepts in scope:
  - **Baselines** — Functional (FBL @ SRR), Allocated (ABL @ PDR), Product (PBL @ CDR + delta @ QR), each frozen and identifier-locked.
  - **Configuration items (CIs)** — defined hierarchy CSCI / HWCI / interface CIs with unique `QATL-CI-<NNNN>` identifiers.
  - **Interface Control Documents (ICDs)** — mechanical, electrical, data, fluid, thermal ICDs version-controlled; bilateral sign-off.
  - **Change processes** — ECP for proposed change, impact analysis (cost/schedule/MoS/V&V impact), CCB decision (Approve / Reject / Defer), ECN for approved change, EO (Engineering Order) for shop.
  - **CCB authority** — chaired by Q-STRUCTURES with Q-SPACE, Q-INDUSTRY, Q-DATAGOV and ORB-PMO voting; Authority observer for certification-impacting changes.
  - **As-built / as-designed reconciliation** — every flight item delivered with as-built record referencing baseline + applied ECNs + NCRs/Waivers.
  - **Tooling** — DMS-based CM database with link to PLM/CAD vault; SHA-256 hashes for drawing immutability.
  - **Interfaces** — feeds 119-080 (in-service configuration), 119-090 (governance audit trail).

## 3. Diagram

```mermaid
flowchart LR
    FBL["Functional Baseline<br/>@ SRR"]
    FBL --> ABL["Allocated Baseline<br/>@ PDR"]
    ABL --> PBL["Product Baseline<br/>@ CDR / QR"]
    PBL --> CCB["CCB<br/>(ECP → ECN)"]
    CCB --> PBL2["Updated PBL"]
    PBL2 --> ASB["As-Built Record<br/>(per FM)"]
    ASB --> SVC["119-080 In-Service"]
    style PBL fill:#1f3a93,color:#fff
    style CCB fill:#2c82c9,color:#fff
```

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` |
| Subsection | `119` — Evidencia Estructural, Certificación y Gobernanza |
| Subsubject | `070` — Configuration Management and Baseline Control |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Governance class | `baseline`[^gov] |
| Document | `119-070-Configuration-Management-and-Baseline-Control.md` |
| Parent subsection | [`README.md`](./README.md) · [`119-000-General.md`](./119-000-General.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row.
[^gov]: **Governance class** — `baseline`.
[^ecssmSt40]: **ECSS-M-ST-40C** — Configuration and Information Management.
[^iso10007]: **ISO 10007:2017** — Configuration Management Guidelines.
