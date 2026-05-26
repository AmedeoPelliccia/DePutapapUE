---
document_id: SMD-CONTROL-001-Status-and-Scope
title: "SMD-CONTROL-001 — Status and Scope"
path: governance/SMD-MODEL/00_CONTROL/SMD-CONTROL-001-Status-and-Scope.md
status: draft
version: "0.1.0"
owner: "Office of the CEO / Amedeo Pelliccia"
governance_domain: SMD-MODEL
classification: open-governance-baseline
standard_scope: governance
lifecycle_model: LC01-LC14
parent_document: governance/SMD-MODEL/00_CONTROL/README.md
linked_governance_rule: SMD-GOV-001
evidence_target: governance/SMD-MODEL/08_EVIDENCE_AND_MERIT/
---

# SMD-CONTROL-001 — Status and Scope

## 1. Purpose

This document defines the controlled status model, lifecycle relationships, and scope boundaries for artefacts governed by the `SMD-MODEL` baseline.

It establishes the operational taxonomy required to distinguish:
* Draft governance content.
* Approved governance constraints.
* Superseded historical records.
* Baseline governance artefacts.
* Downstream programme, technology, infrastructure, organizational, and neural-network implementation records.

The primary objective is to prevent ambiguity or systemic drift between the foundational **SMD governance baseline** and localized execution artefacts.

---

## 2. Document Status Architecture

Every controlled artefact within the `SMD-MODEL` domain shall declare its current operational state inside its frontmatter metadata.

The permitted configuration values are restricted to the following block:

```yaml
allowed_status_values:
  - draft
  - approved
  - superseded

```

### 2.1 Status Matrix

| Status | Meaning | Enforcement Weight | Repository Treatment |
| --- | --- | --- | --- |
| `draft` | The artefact is under development, validation, peer review, or democratic review. | None until approved. | May be edited through the normal controlled drafting process. |
| `approved` | The artefact has successfully passed the required review and approval process. | Binding framework rule. | Active component of the operational SMD-MODEL governance baseline. |
| `superseded` | The artefact has been replaced by a later, formally approved version. | None, except for audit trails. | Retained exclusively for historical traceability and change evidence. |

### 2.2 Status Rules

* A `draft` artefact shall not be treated as an enforceable governance constraint under any circumstances.
* An `approved` artefact shall be treated as strictly binding for all applicable downstream entities.
* A `superseded` artefact shall not be reused as a current authority unless explicitly cited for historical traceability or baseline regression audits.
* All document status transitions shall be controlled solely by the mechanisms defined in `SMD-CONTROL-004-Change-Control.md`.

---

## 3. Lifecycle Model Integration

Status transitions shall align chronologically with the canonical `LC01–LC14` lifecycle model.

| Lifecycle Phase Range | Governance Activity | Valid Status |
| --- | --- | --- |
| `LC01` – `LC02` | Concept definition, scope identification, and initial governance need. | `draft` |
| `LC03` – `LC05` | Architecture definition, rule drafting, and cross-axis mapping. | `draft` |
| `LC06` – `LC08` | Verification planning, peer review, impact assessment, and evidence preparation. | `draft` |
| `LC09` – `LC10` | Formal review, approval, democratic ratification, and baseline entry. | `draft` → `approved` |
| `LC11` – `LC12` | Operational use, monitoring, support, and active compliance application. | `approved` |
| `LC13` | Upgrade, modification, amendment, and controlled revision management. | `approved` or `draft` successor |
| `LC14` | Retirement, replacement, decommissioning, and archival closure. | `superseded` |

---

## 4. Scope Boundaries

The `SMD-MODEL` baseline controls the foundational governance logic, not the day-to-day execution records of downstream programmes.

### 4.1 Macro-Governance Mandates

The framework explicitly defines:

* The social-merito-democratic governance principles.
* The **OPTIN** operating architecture.
* The criteria for merit evidence and corporate accountability.
* The structural requirements for democratic review and recall.
* The minimum traceability obligations and schema parameters.
* The mandatory linkage layers between organizations, programmes, technologies, infrastructures, and neural-network systems.

### 4.2 Localized Management Exclusions

This baseline shall not replace localized programme management, technical engineering configuration management, human resource operations, or raw runtime telemetry repositories.

---

## 5. In-Scope Governance Baseline

The `SMD-MODEL` domain has baseline jurisdiction over the following structural blocks:

| Area | In-Scope Content |
| --- | --- |
| **`00_CONTROL`** | Document status, scope boundaries, vocabulary, applicability, and change-control rules. |
| **`01_PRINCIPLES`** | Dignity floor, fair access, evidence-based merit, democratic accountability, and regenerative value. |
| **`02_ARCHITECTURE`** | OPTIN foundational structure: Organizations, Programmes, Technologies, Infrastructures, and Neural Networks. |
| **`03_ORGANIZATIONS`** | Q-Divisions and Q-ORB governance roles, permissions, and domain constraints. |
| **`04_PROGRAMMES`** | Programme accountability matrices and validation requirements (excluding engineering execution). |
| **`05_TECHNOLOGIES`** | Technology governance models, baseline standards, and validation criteria. |
| **`06_INFRASTRUCTURES`** | Physical/digital asset accountability and audit verification linkages. |
| **`07_NEURAL_NETWORKS`** | Deterministic AI, synthetic data governance, neural bridging, QSN, and certification-aware AI rules. |
| **`08_EVIDENCE_AND_MERIT`** | Merit-evidence records, contribution measurement engines, and appeal/review logic. |
| **`09_GOVERNANCE_RULES`** | Binding governance rules, systemic capture restrictions, and anti-corruption controls. |
| **`10_TEMPLATES`** | Controlled templates and schemas ensuring consistent downstream implementation. |

---

## 6. Out-of-Scope Execution Records

The following items reside outside the direct `SMD-MODEL` baseline and shall be managed within independent downstream environments:

| Area | Out-of-Scope Content | Required Linkage |
| --- | --- | --- |
| **Programme Execution** | Engineering telemetry, design files, test datasets, and day-to-day project schedules. | Must link to explicit SMD accountability records when governance-relevant. |
| **HR Operations** | Day-to-day staffing, individual team allocations, payroll execution, and internal task tickets. | Must respect SMD baseline principles but remain inside separate HR systems. |
| **Software Execution** | Source code repositories, runtime logs, continuous integration (CI) traces, and NN inference outputs. | Must establish linkages to SMD if utilized as compliance, merit, or governance evidence. |
| **Financial Operations** | Individual ledger transactions, vendor invoices, expense records, and localized budget logs. | Must link back to Q-ORB / finance governance when required for accountability audits. |
| **Local Project Management** | Team task boards, agile sprint backlogs, and operational milestone assignments. | Must not override, alter, or dilute approved SMD governance rules. |

---

## 7. Applicability Boundaries

Approved `SMD-MODEL` mandates apply categorically across the five **OPTIN** axes:

| Axis | Applicability Rule |
| --- | --- |
| **O — Organizations** | Applies to all Q-Divisions, horizontal Q-ORB support functions, councils, review authorities, and administrative bodies. |
| **P — Programmes** | Applies strictly to multi-year programme lines such as `AMPEL360`, `GAIA-AIR`, `GAIA-SPACE`, `ROBBBO-T`, and all future core initiatives. |
| **T — Technologies** | Applies to core technology baselines, collaborative research stacks, controlled technical standards, and R&D validation models. |
| **I — Infrastructures** | Applies to industrial manufacturing plants, airports, vertiports, spaceports, maintenance hangars, FALs, and major logistics assets. |
| **N — Neural Networks** | Applies to deterministic AI pipelines, synthetic data governance nodes, neural-network bridging, QSN architectures, and certified safety models. |

---

## 8. Boundary Rule

```yaml
boundary_rule:
  id: SMD-CONTROL-001-BR-001
  title: "Governance Baseline vs Execution Record"
  rule: >
    SMD-MODEL defines the governance baseline and accountability obligations.
    Downstream programmes, technologies, infrastructures, organizations, and
    neural-network systems instantiate those obligations in their own controlled
    implementation branches.
  enforcement:
    - The SMD baseline shall not contain raw or uncontrolled programme execution data.
    - Localized programme branches shall not override or dilute approved SMD governance obligations.
    - Local execution records shall structurally link back to SMD governance rules when used as evidence.

```

---

## 9. Traceability

| Trace Target | Reference / Location |
| --- | --- |
| **Parent Document** | `governance/SMD-MODEL/00_CONTROL/README.md` |
| **Linked Governance Rule** | `SMD-GOV-001 — No Programme Without SMD Accountability` |
| **Lifecycle Model** | `LC01-LC14` |
| **Evidence Target** | `governance/SMD-MODEL/08_EVIDENCE_AND_MERIT/` |
| **Change-Control Authority** | `governance/SMD-MODEL/00_CONTROL/SMD-CONTROL-004-Change-Control.md` |
| **Applicability Authority** | `governance/SMD-MODEL/00_CONTROL/SMD-CONTROL-003-Applicability.md` |

---

## 10. Controlled Closure Statement

This document establishes the official status and scope boundaries for the `SMD-MODEL` baseline. No structural or operational asset shall be treated as part of the controlled baseline unless its status, scope, applicability, and change-control relationship are fully compliant with this document.

Any changes to status definitions, scope boundaries, or applicability logic must be processed through the formal authorization pipelines of `SMD-CONTROL-004-Change-Control.md`.

```

```
