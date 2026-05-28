---
document_id: QATL-ATLAS-1000-STA-110-119-01-117-010
title: "STA 110-119 · 117-010 — Soft-Goods Materials and Restraint Layer"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
architecture_code: STA
subsection: "117"
subsubject: "010"
subsubject_title: "Soft-Goods Materials and Restraint Layer"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-MECHANICS, Q-DATAGOV, Q-HORIZON, Q-INDUSTRY]
governance_class: baseline
version: 1.0.0
status: active
language: en
---

# STA 110-119 · 117-010 — Soft-Goods Materials and Restraint Layer

## 1. Purpose

Defines the **soft-goods restraint architecture** for Q+ATLANTIDE inflatable / expandable habitable modules: Vectran, Kevlar and Nextel webbings carrying primary pressure load, allowables per CMH-17[^cmh17] Vol. 1 and conditioning per ASTM F3208[^astmf3208], strap-and-cord topology, and stitch / loop joint qualification per ECSS-E-ST-32-01C[^ecsseSt3201].

## 2. Scope

- Covers the *Soft-Goods Materials and Restraint Layer* subsubject (`010`) of subsection `117`.
- Inherits Q-Division authority from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Concepts in scope:
  - **Restraint architecture** — woven Vectran / Kevlar webbing carrying hoop and meridional pressure loads; safety factor ≥ 4.0 on ultimate per NASA-STD-5012[^nasastd5012] human-rated pressure vessel guidance.
  - **Material allowables** — A- and B-basis per CMH-17[^cmh17] from coupon population ≥ 30; creep-rupture derating at 50 % UTS for 30 years on-orbit.
  - **Conditioning and aging** — humidity, thermal-vacuum, and UV pre-conditioning per ASTM F3208[^astmf3208]; AO erosion testing for LEO missions.
  - **Joint qualification** — bar-tack and box-stitch joints qualified by pull-test ≥ 90 % web strength; loops sized to avoid stress concentration > 1.3.
  - **Lot traceability** — yarn lot, weaving lot, stitching lot, and inspector ID recorded per ECSS-Q-ST-70-15C[^ecssqst7015].
  - **Interfaces** — feeds 117-020 (bladder load path) and 117-060 (hard-soft interface clamp ring).

## 3. Diagram

```mermaid
flowchart LR
    YARN["Vectran / Kevlar Yarn\n(lot-traced)"]
    YARN --> WEAVE["Webbing Weave\n(CMH-17 allowables)"]
    WEAVE --> JOINT["Stitched Joints\n(bar-tack · box-stitch)"]
    JOINT --> SHELL["Restraint Shell\n(hoop + meridional)"]
    SHELL --> LP["Primary Load Path"]
    style LP fill:#1f3a93,color:#fff
    style YARN fill:#2c82c9,color:#fff
```

## 4. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` |
| Subsection | `117` — Estructuras Inflables, Expandibles y Habitables |
| Subsubject | `010` — Soft-Goods Materials and Restraint Layer |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Governance class | `baseline`[^gov] |
| Document | `117-010-Soft-Goods-Materials-and-Restraint-Layer.md` |
| Parent subsection | [`README.md`](./README.md) · [`117-000-General.md`](./117-000-General.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row.
[^gov]: **Governance class** — `baseline`.
[^ecsseSt3201]: **ECSS-E-ST-32-01C** — Space Engineering: Structural General Requirements.
[^ecsseSt3301]: **ECSS-E-ST-33-01C** — Space Engineering: Mechanisms.
[^ecsseSt31]: **ECSS-E-ST-31C** — Space Engineering: Thermal Control General Requirements.
[^ecssqst7015]: **ECSS-Q-ST-70-15C** — Space product assurance: Non-destructive testing.
[^nasastd3001]: **NASA-STD-3001 Vol. 1 & 2** — Space Flight Human-System Standard.
[^nasastd5012]: **NASA-STD-5012** — Strength and Life Assessment Requirements.
[^nasahdbk6003]: **NASA-HDBK-6003** — MMOD design reference.
[^astmf3208]: **ASTM F3208** — Standard Practice for Conditioning and Testing of Soft Goods.
[^cmh17]: **CMH-17** — Composite Materials Handbook.
[^iso9001]: **ISO 9001:2015** — Quality Management Systems.
