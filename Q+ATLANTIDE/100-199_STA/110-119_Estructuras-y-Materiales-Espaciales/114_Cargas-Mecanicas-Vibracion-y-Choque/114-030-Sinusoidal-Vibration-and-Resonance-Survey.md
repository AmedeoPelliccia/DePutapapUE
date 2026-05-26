---
document_id: QATL-ATLAS-1000-STA-110-119-01-114-030-SINUSOIDAL-VIBRATION-AND-RESONANCE-SURVEY
title: "STA 110-119 · 114-030 — Sinusoidal Vibration and Resonance Survey"
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
subsubject: "030"
subsubject_title: "Sinusoidal Vibration and Resonance Survey"
---
# STA 110-119 · 114-030 — Sinusoidal Vibration and Resonance Survey

## 1. Purpose

Defines the **sinusoidal vibration test specification and resonance survey requirements** for Q+ATLANTIDE STA-band spacecraft and payloads, covering primary structure frequency requirements, sine-sweep levels, and modal survey assessment per ECSS-E-ST-32-11C[^ecsse3211] and NASA-HDBK-7005[^nasahdbk7005].

## 2. Scope

- Covers the *Sinusoidal Vibration and Resonance Survey* subsubject (`030`) of subsection `114`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Concepts in scope:
  - **Primary structure frequency requirements** — fundamental frequency ≥ 35 Hz lateral and ≥ 50 Hz axial at primary spacecraft-to-launcher interface to avoid coupling with launcher modes; stiffness design rules.
  - **Sine-sweep test specification** — frequency range 5–100 Hz, sweep rate ≤ 4 oct/min, qualification levels defined per launcher ICD; notching philosophy and notch justification requirements.
  - **Structural notching** — force/acceleration-limited notching permitted at structural resonances; notch documentation in test plan with analytical basis.
  - **Resonance survey (RS)** — low-level sinusoidal sweep (0.1–0.25 g) to identify resonant frequencies and damping ratios; comparison to pre-test FEM predictions.
  - **Modal survey assessment** — test-FEM correlation per ECSS-E-ST-32-11C[^ecsse3211]: MAC ≥ 0.9 for primary modes, frequency correlation within ±5 %, cross-orthogonality check.
  - **Damping values** — structural damping ζ = 0.02 (2%) for analysis; measured damping ratios documented in test report.

## 3. Diagram — Sinusoidal Vibration and Modal Survey Flow

```mermaid
flowchart TB
    SPEC["Sine-Sweep Specification<br/>(5–100 Hz · ≤ 4 oct/min · launcher ICD)"]
    SPEC --> NOTCH["Notching Review<br/>(force/accel-limited · analytical basis)"]
    NOTCH --> TEST["Sine-Sweep Test<br/>(qualification / acceptance levels)"]
    TEST --> RS["Resonance Survey<br/>(0.1–0.25 g · freq + damping identification)"]
    RS --> CORR["FEM Correlation<br/>(MAC ≥ 0.9 · Δf ≤ 5 % · cross-orthogonality)"]
    CORR --> MSA["Modal Survey Assessment Report<br/>(ECSS-E-ST-32-11C)"]
    SPEC --> FREQ["Primary Freq. Req.<br/>(≥ 35 Hz lateral · ≥ 50 Hz axial)"]
    style TEST fill:#1f3a93,color:#fff
    style MSA fill:#2c82c9,color:#fff
```

## Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `114` — Cargas Mecánicas, Vibración y Choque |
| Subsubject | `030` — Sinusoidal Vibration and Resonance Survey |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/114_Cargas-Mecanicas-Vibracion-y-Choque/` |
| Document | `114-030-Sinusoidal-Vibration-and-Resonance-Survey.md` (this file) |
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