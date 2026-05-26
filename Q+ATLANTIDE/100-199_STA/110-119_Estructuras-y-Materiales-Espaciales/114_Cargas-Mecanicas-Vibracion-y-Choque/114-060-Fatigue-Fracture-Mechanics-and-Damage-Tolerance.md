---
document_id: QATL-ATLAS-1000-STA-110-119-01-114-060-FATIGUE-FRACTURE-MECHANICS-AND-DAMAGE-TOLERANCE
title: "STA 110-119 · 114-060 — Fatigue Fracture Mechanics and Damage Tolerance"
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
subsubject: "060"
subsubject_title: "Fatigue Fracture Mechanics and Damage Tolerance"
---
# STA 110-119 · 114-060 — Fatigue Fracture Mechanics and Damage Tolerance

## 1. Purpose

Defines the **fatigue, fracture mechanics, and damage tolerance requirements** for Q+ATLANTIDE STA-band spacecraft structures, covering fatigue life analysis, fracture control programme, and damage-tolerance assessment per NASA-STD-5019A[^nasastd5019] and ECSS-E-ST-32-01C[^ecsse3201].

## 2. Scope

- Covers the *Fatigue, Fracture Mechanics and Damage Tolerance* subsubject (`060`) of subsection `114`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Concepts in scope:
  - **Fatigue life analysis** — stress-life (S-N) and strain-life (ε-N) methods; fatigue scatter factor ≥ 4× on life; mission life mission spectrum definition including ground handling, launch, and on-orbit thermal cycling.
  - **Fracture control programme** — classification of fracture-critical items (FCI), fracture control plan (FCP), fracture mechanics analysis using linear-elastic fracture mechanics (LEFM), initial flaw size per NDE capability.
  - **Damage tolerance assessment** — slow-crack-growth methodology; crack growth analysis with Paris-law model; minimum detectable crack size; inspection interval derivation.
  - **Material allowables** — A-basis and B-basis allowables per MMPDS/CMH-17; knockdown factors for environment (temperature, humidity, radiation) and manufacturing variability.
  - **Welded and bonded joints** — weld quality categories per AWS D1.1 / ECSS-Q-ST-70-39C; bonded joint cohesive zone model (CZM) analysis; NDI inspection at weld and bond lines.
  - **Pressure vessel fracture control** — proof test factor for fracture control; hydroproof/pneumoproof cycle requirements; leak-before-burst (LBB) design philosophy.

## 3. Diagram — Fatigue and Fracture Control Flow

```mermaid
flowchart TB
    SPEC["Mission Load Spectrum<br/>(ground · launch · on-orbit · thermal cycling)"]
    SPEC --> FAT["Fatigue Life Analysis<br/>(S-N · ε-N · scatter factor ≥ 4×)"]
    SPEC --> FCL["Fracture-Critical Item List<br/>(FCI classification)"]
    FCL --> LEFM["LEFM Analysis<br/>(Paris law · initial flaw · NDE limit)"]
    LEFM --> DTA["Damage Tolerance Assessment<br/>(crack growth · inspection interval)"]
    FAT & DTA --> ALLOW["Material Allowables<br/>(A-basis · B-basis · knockdowns)"]
    ALLOW --> FCP["Fracture Control Plan<br/>(NASA-STD-5019A)"]
    FCP --> EP["Evidence Package<br/>(→ 114-080)"]
    style FCL fill:#1f3a93,color:#fff
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
| Subsubject | `060` — Fatigue Fracture Mechanics and Damage Tolerance |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/114_Cargas-Mecanicas-Vibracion-y-Choque/` |
| Document | `114-060-Fatigue-Fracture-Mechanics-and-Damage-Tolerance.md` (this file) |
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