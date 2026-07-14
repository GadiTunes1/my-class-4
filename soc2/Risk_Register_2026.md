---
id: 1b273467-f3e9-544f-aa17-62c4fb878f77
---

# Risk Register — 2026

| Field | Value |
|---|---|
| Assessment period | 2026 |
| Date performed | 2026-06-17 |
| Facilitated by | <CISO / Risk Owner> |
| Participants | <control owners present at walkthrough> |
| Reviewed & approved by | <Management> — Date: __________ |

> **How to use:** One row per risk. Score = Likelihood × Impact (1–5 each). Fill the residual columns after considering existing controls. **Every remediation item and any "Accept" decision needs the management approval columns completed.** The example rows below are starters — replace/expand for your environment.

## Scoring key
**Likelihood:** 1 Rare · 2 Unlikely · 3 Possible · 4 Likely · 5 Almost certain
**Impact:** 1 Negligible · 2 Minor · 3 Moderate · 4 Major · 5 Severe
**Rating:** 1–4 Low · 5–9 Medium · 10–15 High · 16–25 Critical

## Risk register

| ID | Risk source | Risk / threat description | Affected asset / objective | Owner | L | I | Inherent score | Existing controls | Residual rating | Treatment | Remediation item & target date | Mgmt approved (Y/N) | Approver / date |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R-01 | External — security | Phishing leads to credential compromise of employee account | Customer data, prod systems | Security | 4 | 4 | 16 (Critical) | MFA, email filtering, awareness training | Medium | Mitigate | Roll out phishing-resistant MFA (FIDO2) — Q3 2026 | | |
| R-02 | External — security | Exploitation of unpatched vulnerability in internet-facing service | Production environment | Eng / SRE | 3 | 5 | 15 (High) | Monthly patching, vuln scanning | Medium | Mitigate | Reduce patch SLA to 14 days for critical CVEs — Q3 2026 | | |
| R-03 | Internal operations | Loss of key person / single point of knowledge | Service continuity | Eng Mgmt | 3 | 4 | 12 (High) | Some documentation | Medium | Mitigate | Cross-train + runbooks for critical systems — Q4 2026 | | |
| R-04 | External — third party | Critical vendor (cloud/SaaS) outage or breach | Availability, customer data | Security | 3 | 4 | 12 (High) | Vendor SOC 2 review, DR plan | Medium | Mitigate | Annual vendor risk review + DR test — Q4 2026 | | |
| R-05 | Business commitments | New regulatory/contractual commitment not met | Compliance, customer commitments | Legal / Sec | 2 | 4 | 8 (Medium) | Compliance tracking | Low | Mitigate | Map new commitments to controls — Q3 2026 | | |
| R-06 | Internal operations | Insider misuse or excessive access (over-privilege) | Confidential data | Security | 2 | 4 | 8 (Medium) | RBAC, access reviews | Low | Mitigate | Quarterly least-privilege access review — ongoing | | |
| R-07 | Internal operations | Data loss / inadequate backup or recovery | Availability, integrity | SRE | 2 | 5 | 10 (High) | Automated backups | Low | Mitigate | Document + test restore quarterly — Q3 2026 | | |
| R-08 | Business objectives | Insecure changes from rapid feature delivery | Production security | Eng | 3 | 3 | 9 (Medium) | Code review, CI checks | Low | Mitigate | Add security gate to CI/CD — Q4 2026 | | |

## Remediation tracking (management-approved actions)

| Item | From risk | Owner | Target date | Status | Approved by / date | Closed date |
|---|---|---|---|---|---|---|
| FIDO2 MFA rollout | R-01 | Security | Q3 2026 | Open | | |
| Critical-CVE patch SLA | R-02 | SRE | Q3 2026 | Open | | |
| Cross-training & runbooks | R-03 | Eng Mgmt | Q4 2026 | Open | | |

---

### Management sign-off
By signing, management confirms it has reviewed this risk assessment and **approves the remediation plans** recorded above.

| Name | Title | Signature | Date |
|---|---|---|---|
| | CEO / Management | | |
| | CISO / Risk Owner | | |
