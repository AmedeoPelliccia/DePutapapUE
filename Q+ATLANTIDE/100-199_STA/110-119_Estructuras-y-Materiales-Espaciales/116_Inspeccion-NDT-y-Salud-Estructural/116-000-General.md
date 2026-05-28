---
document_id: QATL-ATLAS-1000-STA-110-119-01-116-000-GENERAL
title: "STA 110-119 · 116-000 — General"
register: ATLAS-1000
parent_baseline: Q+ATLANTIDE
architecture_code: STA
subsection: "116"
subsection_title: "Inspección NDT y Salud Estructural"
primary_q_division: Q-SPACE
support_q_divisions: [Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY]
governance_class: baseline
version: 1.0.0
status: active
language: en
subsubject: "000"
subsubject_title: "General"
---

# STA 110-119 · 116-000 — General

## 1. Purpose

Overview entry-point for the *Inspección NDT y Salud Estructural* subsection within the `110-119` code range (Section `01` — *Estructuras y Materiales Espaciales*) of the **STA** architecture band (*Space Technology Architecture*, master range `100–199`).

This subsubject (`000 Overview`) introduces the STA 110-119.116 slice and links it to the controlled Q+ATLANTIDE baseline[^baseline]. It establishes the non-destructive testing (NDT) and structural health monitoring (SHM) framework governing method selection and qualification, ultrasonic/phased-array, radiographic/CT, surface/electromagnetic, composite/bonded-joint NDI, SHM architecture and sensors, diagnostics/prognostics, and damage-tolerance integration for Q+ATLANTIDE space missions. This subsection is designated **fracture-critical inspection and SHM**.

## 2. Scope

- Covers the *Inspección NDT y Salud Estructural* slice of parent code range `110-119`.
- Inherits Q-Division authority and ORB support from the parent row in [`../../README.md` §3](../../README.md#3-architecture-table)[^archtable].
- Populated subsubject set (`010`–`090`) indexed in [`README.md`](./README.md).
- Concepts in scope:
  - **NDT Methods Selection and Qualification** (`010`) — method matrix per material/flaw/geometry; POD curves per MIL-HDBK-1823[^milhdbk1823]; personnel certification per EN 4179[^en4179] / NAS 410 / ISO 9712[^iso9712].
  - **Ultrasonic and Phased-Array Inspection** (`020`) — pulse-echo, through-transmission, PAUT, TFM/FMC; reference standards; calibration per ASTM E2491[^astme2491].
  - **Radiographic and Computed-Tomography Inspection** (`030`) — film/digital RT, micro-CT; IQI sensitivity per ASTM E1742[^astme1742] / E2698; voxel resolution and reconstruction QA.
  - **Surface and Electromagnetic NDT Methods** (`040`) — dye-penetrant (PT) per ASTM E1417[^astme1417], magnetic particle (MT) per ASTM E1444[^astme1444], eddy-current (ET) per ASTM E309/E2884.
  - **Composite and Bonded-Joint NDI** (`050`) — through-transmission UT, pulse-echo UT, infrared thermography, shearography, tap-test; disbond/delamination detection per CMH-17[^cmh17] Vol. 3.
  - **Structural Health Monitoring Architecture** (`060`) — onboard SHM topology, zone segmentation, link to vehicle health bus; ARP6461[^arp6461] guideline use.
  - **SHM Sensors and Data Acquisition** (`070`) — FBG optical strain, PZT/AE patches, MEMS accelerometers, comparative-vacuum monitoring; DAQ sampling and synchronisation budgets.
  - **Diagnostics, Prognostics and Damage-Tolerance Integration** (`080`) — feature extraction, anomaly classification, RUL estimation; integration with fracture-control plan (→ `114-060`) and inspection intervals.
  - **Traceability, Evidence and Lifecycle Governance** (`090`) — NDT/SHM evidence package, DRB/MRB authority, PDR/CDR/QTR/MRR review gates.

## 3. Footprint

| Metric | Value |
|---|---|
| Architecture | `STA` — Space Technology Architecture |
| Master range | `100–199` |
| Code range | `110-119` |
| Section | `01` — Estructuras y Materiales Espaciales |
| Subsection | `116` — Inspección NDT y Salud Estructural |
| Subsubject | `000` — Overview |
| Primary Q-Division | Q-SPACE[^qdiv] |
| Support Q-Divisions | Q-STRUCTURES, Q-DATAGOV, Q-HORIZON, Q-HPC, Q-INDUSTRY |
| ORB support | ORB-PMO, ORB-FIN |
| Governance class | `baseline`[^gov] |
| Folder path | `Q+ATLANTIDE/100-199_STA/110-119_Estructuras-y-Materiales-Espaciales/116_Inspeccion-NDT-y-Salud-Estructural/` |
| Document | `116-000-General.md` (this file) |
| Parent subsection | [`README.md`](./README.md) |
| Parent architecture | [`../../README.md`](../../README.md) |
| Parent baseline | [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md) |

## References & Citations

[^baseline]: **Q+ATLANTIDE controlled baseline (v1.0.0)** — [`organization/Q+ATLANTIDE.md`](../../../../organization/Q+ATLANTIDE.md).
[^archtable]: **STA §3 Architecture Table** — [`../../README.md` §3](../../README.md#3-architecture-table).
[^qdiv]: **Q-Division authority** — Q-Divisions provide technical authority over an architecture row.
[^gov]: **Governance class** — `baseline` denotes documents under controlled change management.
[^milhdbk1823]: **MIL-HDBK-1823A** — Nondestructive Evaluation System Reliability Assessment (POD).
[^en4179]: **EN 4179 / NAS 410** — Qualification and Approval of Personnel for Non-Destructive Testing.
[^iso9712]: **ISO 9712** — NDT: Qualification and Certification of NDT Personnel.
[^astme2491]: **ASTM E2491** — Standard Guide for Evaluating Performance Characteristics of Phased-Array UT Instruments.
[^astme1742]: **ASTM E1742 / E2698** — Standard Practice for Radiographic Examination / Digital Radiographic Examination.
[^astme1417]: **ASTM E1417** — Standard Practice for Liquid Penetrant Testing.
[^astme1444]: **ASTM E1444** — Standard Practice for Magnetic Particle Testing.
[^cmh17]: **CMH-17** — Composite Materials Handbook.
[^arp6461]: **SAE ARP6461** — Guidelines for Implementation of Structural Health Monitoring on Fixed-Wing Aircraft.
