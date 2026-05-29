---
document_id: QATL-ATLAS-1000-STA-110-119-01-114-080-LOADS-QUALIFICATION-AND-ACCEPTANCE-TEST-PROGRAMME
title: "STA 110-119 · 114-080 — Loads Qualification and Acceptance Test Programme"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
parent_baseline_doc: ../../../../organization/Q+ATLANTIDE.md
parent_architecture_doc: ../../README.md
parent_section_doc: ../README.md
parent_subsection_doc: ./README.md
architecture_code: STA
architecture_name: "Space Technology Architecture"
master_range: "100–199"
code_range: "110-119"
section: "01"
section_title: "Estructuras y Materiales Espaciales"
subsection: "114"
subsection_title: "Cargas Mecánicas, Vibración y Choque"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY]
orb_function_support: [ORB-PMO, ORB-FIN]
governance_class: baseline
version: 1.0.0
status: active
language: en
subsubject: "080"
subsubject_title: "Loads Qualification and Acceptance Test Programme"
---
# STA 110-119 · 114-080 — Loads Qualification and Acceptance Test Programme

## 1. Purpose

Defines the **structural loads qualification and acceptance test programme** for Q+ATLANTIDE STA-band spacecraft structures, covering test scope, qualification and acceptance levels, test sequence, evidence package, and heritage credit rules per ECSS-E-ST-32-01C[^ecsse3201] and NASA-HDBK-7005[^nasahdbk7005].

## 2. Scope

- Covers the *Loads Qualification and Acceptance Test Programme* subsubject (`080`) of subsection `114`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Concepts in scope:
  - **Qualification test levels** — qualification = limit load × ultimate FoS (static/quasi-static); +6 dB (×2) over predicted flight level for acoustic and random vibration; +3 dB over predicted SRS for shock.
  - **Acceptance test levels** — acceptance = limit load × yield FoS (static); +3 dB over predicted flight level (acoustic/random); flight-level + 3 dB (shock); every flight unit tested.
  - **Test sequence** — modal survey → sine vibration (low-level) → random vibration → acoustic → shock → sine vibration (post-shock survey); thermal-vacuum structural test for distortion-sensitive items.
  - **Static proof load test** — proof pressure + structural static proof load where applicable; load introduction accuracy ±3 % of specified load.
  - **Evidence package** — qualification test report (QTR), acceptance data package (ADP), structural analysis report (SA-report), modal survey report, fracture control plan closure, and anomaly/NCR disposition.
  - **Heritage credit** — similarity assessment methodology; delta-qualification scope for design changes affecting mass, stiffness, or load path; traceability to original QTR.

## 3. Diagram — Test Programme Flow

```mermaid
flowchart TB
    REQ["Structural Requirements<br/>(ECSS-E-ST-32-01C · NASA-HDBK-7005)"]
    REQ --> QLVL["Qualification Levels<br/>(static: UL · vib: +6 dB · shock: +3 dB)"]
    REQ --> ALVL["Acceptance Levels<br/>(static: YL · vib: +3 dB · shock: FL+3dB)"]
    QLVL --> SEQ["Test Sequence<br/>(modal → sine → random → acoustic → shock → survey)"]
    ALVL --> SEQ
    SEQ --> QTR["Qualification Test Report (QTR)"]
    SEQ --> ADP["Acceptance Data Package (ADP)"]
    QTR & ADP --> EP["Evidence Package<br/>(SA-report · FCP closure · NCR)"]
    EP --> HER["Heritage Credit Assessment"]
    EP --> LG["Lifecycle Governance<br/>(→ 114-090)"]
    style SEQ fill:#1f3a93,color:#fff
    style EP fill:#2c82c9,color:#fff
```

## Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `114` — Cargas Mecánicas, Vibración y Choque |
| Subsubject | `080` — Loads Qualification and Acceptance Test Programme |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/114_Cargas-Mecanicas-Vibracion-y-Choque/` |
| Document | `114-080-Loads-Qualification-and-Acceptance-Test-Programme.md` (this file) |
| Parent subsection | [`README.md`](./README.md) · [`114-000-General.md`](./114-000-General.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md). Defines the controlled `000-999` architecture-band taxonomy and the ATLAS-1000 register subpart.

[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table). Authoritative source for the `110-119` row.

[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row (Q+ATLANTIDE Note N-002). See [`organization/Q+ATLANTIDE.md` §4](../../../../organization/Q+ATLANTIDE.md#4-notes).

[^gov]: **Governance class** — `baseline` denotes documents under controlled change management within the Q+ATLANTIDE baseline.

[^ecsse3201]: **ECSS-E-ST-32-01C — Space Engineering: Structural General Requirements** — European standard defining structural general requirements for space systems, covering load cases, safety factors, and structural analysis.

[^ecsse3210]: **ECSS-E-ST-32-10C Rev.1 — Space Engineering: Structural Factors of Safety for Spaceflight Hardware** — European standard defining factors of safety for structural design and test.

[^ecsse3211]: **ECSS-E-ST-32-11C — Space Engineering: Modal Survey Assessment** — European standard for structural dynamic model verification through modal survey testing.

[^nasastd5002]: **NASA-STD-5002 — Loads Analyses of Spacecraft and Payloads** — NASA standard defining loads analysis process for launch, ascent, on-orbit, and re-entry mission phases.

[^nasahdbk7005]: **NASA-HDBK-7005 — Dynamic Environmental Criteria** — NASA handbook providing dynamic environmental criteria (sinusoidal, random, acoustic, shock) for spacecraft qualification.

[^nasastd5019]: **NASA-STD-5019A — Fracture Control Requirements for Spaceflight Hardware** — NASA standard defining fracture control programme requirements for pressurised and unpressurised structures.

[^iso9283]: **ISO 9283:1998 — Manipulating Industrial Robots: Performance Criteria** — Applicable to robotic structural and dynamic characterisation.

### Applicable industry standards

- ECSS-E-ST-32-01C — Space Engineering: Structural General Requirements[^ecsse3201]
- ECSS-E-ST-32-10C Rev.1 — Structural Factors of Safety for Spaceflight Hardware[^ecsse3210]
- ECSS-E-ST-32-11C — Modal Survey Assessment[^ecsse3211]
- NASA-STD-5002 — Loads Analyses of Spacecraft and Payloads[^nasastd5002]
- NASA-HDBK-7005 — Dynamic Environmental Criteria[^nasahdbk7005]
- NASA-STD-5019A — Fracture Control Requirements for Spaceflight Hardware[^nasastd5019]