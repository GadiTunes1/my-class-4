---
id: 930e35c0-2687-5108-8f4e-53bdc2b1b7a5
---

# Risk Assessment Policy & Procedure

| Field | Value |
|---|---|
| Document owner | <CISO / Head of Security> |
| Approved by | <CEO / Management> |
| Version | 1.0 |
| Effective date | 2026-06-17 |
| Last reviewed | 2026-06-17 |
| Next review (annual) | 2027-06-17 |
| Classification | Internal |

> **SOC 2 mapping:** Trust Services Criteria **CC3.1, CC3.2, CC3.3, CC3.4** and **CC9.1** (COSO Principles 6–9). This document is the *process* the auditor walks through. The companion **Risk Register** is the *output* the auditor reviews.

---

## 1. Purpose

This policy establishes how <Company> identifies, evaluates, and treats risks that threaten the achievement of its business objectives, commitments, and service requirements — including threats to the security, availability, and confidentiality of its systems. It ensures risk is **formally assessed**, **documented**, **maintained**, and that **all remediation activities are approved by management**.

## 2. Scope

Applies to all systems, data, personnel, vendors, and processes that support <Company>'s services and business objectives, covering risks from:

- **Changes to business objectives, commitments, and requirements** (new products, contracts, regulatory/compliance commitments).
- **Internal operations** (people, process, technology, organizational change).
- **External factors** (threat landscape, vendors/third parties, legal/regulatory, economic, environmental).

## 3. Roles & Responsibilities

| Role | Responsibility |
|---|---|
| **Management / Executive sponsor** | Owns the risk program; **approves the risk assessment and all remediation plans**; accepts residual risk. |
| **Risk owner (CISO / Security lead)** | Facilitates the assessment, maintains the Risk Register, drives the cadence. |
| **Control / process owners** | Provide input on threats and controls for their area; execute remediation. |
| **All employees** | Report new or emerging risks to the risk owner. |

## 4. Risk Assessment Process

### 4.1 Cadence (when it runs)
- **Annually** at minimum (full assessment).
- **Ad hoc / triggered** whenever a significant change occurs: new product or major feature, new system or vendor, major org change, new regulatory or contractual commitment, a security incident, or a material change in the threat landscape.

### 4.2 Step 1 — Risk Identification *(this is the "walkthrough" the auditor observes)*
Identify threats and risks across the four sources in scope (business objectives/commitments, internal operations, external factors, and **threats to system security**). Inputs used:

- Asset & data inventory and data-flow diagrams.
- Prior Risk Register and open remediation items.
- Threat intelligence, known vulnerability sources, and the security incident log.
- Vendor/third-party list and their risk tier.
- Changes since last assessment (new commitments, systems, regulations).
- Stakeholder interviews / brainstorming workshop with control owners.

Each identified risk is recorded in the Risk Register with a description, the threat, the affected asset/objective, and the risk owner.

### 4.3 Step 2 — Risk Evaluation (analysis & scoring)
For each risk, rate **Likelihood** and **Impact** on a 1–5 scale. Inherent **Risk Score = Likelihood × Impact** (1–25), mapped to a rating:

| Score | Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–15 | High |
| 16–25 | Critical |

**Likelihood (1–5):** 1 Rare · 2 Unlikely · 3 Possible · 4 Likely · 5 Almost certain.
**Impact (1–5):** 1 Negligible · 2 Minor · 3 Moderate · 4 Major · 5 Severe (to operations, finances, reputation, compliance, or customer commitments).

### 4.4 Step 3 — Risk Treatment / Response
Select a response and consider existing controls to derive **residual risk**:

- **Mitigate** — implement/strengthen controls (default for High/Critical).
- **Transfer** — insurance, contractual terms.
- **Avoid** — stop the activity.
- **Accept** — formally accepted by management (required for any residual Medium+).

Each treatment becomes a **remediation item** with an owner and target date. **Management must approve every remediation plan and any decision to accept risk** (see §5).

### 4.5 Step 4 — Documentation & Approval
The completed assessment is recorded in the **Risk Register**, reviewed with management, and **signed off by management**. The signed register and meeting record are retained as evidence.

### 4.6 Step 5 — Monitoring & Maintenance
The risk owner tracks remediation to closure, updates the register as status changes, and reports open High/Critical risks to management at least quarterly. The register is a living document maintained between annual cycles.

## 5. Management Approval (control requirement)
- The annual (and each triggered) risk assessment is **formally reviewed and approved by management**, evidenced by signature/date or documented meeting minutes.
- **No remediation activity proceeds, and no residual risk is accepted, without management approval.** Approvals are recorded in the Risk Register's approval columns.

## 6. Evidence Retained (what the auditor will ask for)
1. This **policy/procedure** document (the documented process).
2. The completed **Risk Register** for the period.
3. **Walkthrough** notes / agenda from the risk identification session.
4. **Management approval** record (signatures or meeting minutes) of the assessment and remediation plans.
5. Tracking of remediation items to closure.

## 7. Review
This policy is reviewed and re-approved at least annually, or upon significant change.

---

### Approval

| Name | Title | Signature | Date |
|---|---|---|---|
| | CEO / Management | | |
| | CISO / Risk Owner | | |
