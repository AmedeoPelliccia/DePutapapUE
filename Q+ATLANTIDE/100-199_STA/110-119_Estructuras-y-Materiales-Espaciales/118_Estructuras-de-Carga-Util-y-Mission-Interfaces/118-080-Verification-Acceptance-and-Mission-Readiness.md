---
document_id: QATL-ATLAS-1000-STA-110-119-01-118-080
title: "STA 110-119 · 118-080 — Verification Acceptance and Mission Readiness"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
architecture_code: STA
subsection: "118"
subsubject: "080"
subsubject_title: "Verification Acceptance and Mission Readiness"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY]
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · 118-080 — Verification Acceptance and Mission Readiness

## 1. Purpose

Defines the **verification, acceptance and mission-readiness** programme for Q+ATLANTIDE payload-to-bus and payload-to-launcher interfaces: fit-check, modal survey, sine and random vibration, separation-shock, EMC and end-to-end mission-readiness reviews per ECSS-E-ST-10-03C[^ecsseSt1003] and GSFC-STD-7000 (GEVS)[^gevs].

## 2. Scope

- Covers the *Verification Acceptance and Mission Readiness* subsubject (`080`) of subsection `118`.
- Concepts in scope:
  - **Fit-check** — physical and dimensional verification with mass simulator and flight ring; bolt-up torque map and shim record archived.
  - **Modal survey** — sine-burst or low-level random characterisation; first axial / lateral modes match analysis ≤ 5 % per ECSS-E-ST-32-11C[^ecsseSt3211].
  - **Sine / random / acoustic vibration** — per launcher User's Guide envelope and GEVS qualification factors (typ. +3 dB above acceptance, ≥ 60 s/axis).
  - **Separation-shock** — pyro/NEA firing at flight ring with SRS measured at interface and at instrument plane; verified ≤ allowable per 118-020.
  - **EMC / EMI** — radiated and conducted emissions per MIL-STD-461G[^mil461] CE102 / RE102 envelopes harmonised with payload bus.
  - **End-to-end mission readiness** — Flight Readiness Review (FRR), Launch Readiness Review (LRR), Mission Readiness Review (MRR) with all evidence packages closed; risk register reviewed.
  - **Acceptance certificate** — signed by Q-STRUCTURES, Q-SPACE and ORB-PMO, archived in DMS prior to ship.
  - **Interfaces** — feeds 118-090 (evidence package).

## 3. Diagram

```mermaid
flowchart LR
    FIT["Fit-Check"]
    FIT --> MODAL["Modal Survey<br/>(≤ 5 % vs FEM)"]
    MODAL --> VIB["Sine / Random / Acoustic"]
    VIB --> SHOCK["Separation-Shock Test"]
    SHOCK --> EMC["EMC / EMI"]
    EMC --> FRR["FRR · LRR · MRR"]
    FRR --> CERT["Acceptance Certificate"]
    style CERT fill:#1f3a93,color:#fff
    style FRR fill:#2c82c9,color:#fff
```

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` |
| Subsection | `118` — Estructuras de Carga Útil y Mission Interfaces |
| Subsubject | `080` — Verification Acceptance and Mission Readiness |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Governance class | `baseline`[^gov] |
| Document | `118-080-Verification-Acceptance-and-Mission-Readiness.md` |
| Parent subsection | [`README.md`](./README.md) · [`118-000-General.md`](./118-000-General.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row.
[^gov]: **Governance class** — `baseline`.
[^ecsseSt1003]: **ECSS-E-ST-10-03C** — Space Engineering: Testing.
[^ecsseSt3211]: **ECSS-E-ST-32-11C** — Modal Survey Assessment.
[^gevs]: **GSFC-STD-7000 (GEVS)** — General Environmental Verification Standard.
[^mil461]: **MIL-STD-461G** — Requirements for the Control of Electromagnetic Interference Characteristics.
