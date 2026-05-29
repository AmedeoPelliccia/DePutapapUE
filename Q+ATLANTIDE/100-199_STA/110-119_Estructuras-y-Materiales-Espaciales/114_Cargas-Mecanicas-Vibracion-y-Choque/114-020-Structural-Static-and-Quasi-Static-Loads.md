---
document_id: QATL-ATLAS-1000-STA-110-119-01-114-020-STRUCTURAL-STATIC-AND-QUASI-STATIC-LOADS
title: "STA 110-119 · 114-020 — Structural Static and Quasi-Static Loads"
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
subsubject: "020"
subsubject_title: "Structural Static and Quasi-Static Loads"
---
# STA 110-119 · 114-020 — Structural Static and Quasi-Static Loads

## 1. Purpose

Defines the **structural static and quasi-static loads requirements** for Q+ATLANTIDE STA-band spacecraft structures, covering design load derivation, factors of safety, and structural analysis methodology per ECSS-E-ST-32-01C[^ecsse3201] and ECSS-E-ST-32-10C[^ecsse3210].

## 2. Scope

- Covers the *Structural Static and Quasi-Static Loads* subsubject (`020`) of subsection `114`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Concepts in scope:
  - **Limit load (LL)** — maximum load expected in service; equal to DLL from load-case register (→ `114-010`).
  - **Ultimate load (UL)** — LL × ultimate factor of safety (FoS); structure must sustain UL without rupture.
  - **Factors of safety (FoS)** — yield FoS = 1.25, ultimate FoS = 1.50 for metallic structures per ECSS-E-ST-32-10C[^ecsse3210]; higher factors for composites and bonded joints.
  - **Quasi-static load (QSL)** — quasi-static equivalent of dynamic load event; derivation from low-frequency (<100 Hz) dynamic analysis output with 3σ statistical factor.
  - **Structural margin of safety (MS)** — MS = (allowable / applied) / FoS − 1 ≥ 0 for all load paths; positive MS required at all structural joints.
  - **Structural analysis methods** — linear static FEM (MSC Nastran / Abaqus), hand calculations for simple members, test-validated allowables for composites; analysis report (SA-report) required for each load case.

## 3. Diagram — Static Loads and Margin Hierarchy

```mermaid
flowchart TB
    LC["Load-Case Register<br/>(→ 114-010)"]
    LC --> LL["Limit Load (LL)"]
    LL --> YL["Yield Load = LL × 1.25"]
    LL --> UL["Ultimate Load = LL × 1.50"]
    YL --> MSY["MS_yield = allow_yield / YL − 1 ≥ 0"]
    UL --> MSU["MS_ultimate = allow_ult / UL − 1 ≥ 0"]
    MSY & MSU --> SAR["Structural Analysis Report<br/>(SA-Report)"]
    SAR --> QUAL["Test Evidence<br/>(→ 114-080)"]
    style LL fill:#1f3a93,color:#fff
    style SAR fill:#2c82c9,color:#fff
```

## Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `114` — Cargas Mecánicas, Vibración y Choque |
| Subsubject | `020` — Structural Static and Quasi-Static Loads |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/114_Cargas-Mecanicas-Vibracion-y-Choque/` |
| Document | `114-020-Structural-Static-and-Quasi-Static-Loads.md` (this file) |
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