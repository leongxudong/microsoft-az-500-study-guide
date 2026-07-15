# AZ-500 Objective Map

Use this map to turn the official objectives into demonstrable skills. Rate yourself:

- **0 — Unfamiliar:** cannot explain the concept.
- **1 — Aware:** can describe the purpose.
- **2 — Guided:** can implement with documentation.
- **3 — Independent:** can choose, implement, validate, and troubleshoot the control.

## 1. Secure Identity and Access — 15–20%

| Capability | Evidence to Produce | Score |
|---|---|---:|
| Azure and Entra role assignments | Least-privilege role matrix and test result | 0–3 |
| Custom roles | Custom role definition with justified actions and scope | 0–3 |
| Privileged Identity Management | Eligible assignment, approval, MFA, and activation evidence | 0–3 |
| MFA and Conditional Access | Policy design, exclusions, report-only test, and rollback | 0–3 |
| App registrations and enterprise apps | Permission inventory and consent-risk review | 0–3 |
| Service principals and managed identities | Workload identity design with no embedded secrets | 0–3 |

Decision questions:

- When should you use an Azure role instead of a Microsoft Entra role?
- Which emergency-access accounts must be excluded, and how will you monitor them?
- When is a managed identity preferable to a service principal with a secret?

## 2. Secure Networking — 20–25%

| Capability | Evidence to Produce | Score |
|---|---|---:|
| NSGs, ASGs, UDRs, and peering | Traffic-flow diagram and effective-rule validation | 0–3 |
| VPN, Virtual WAN, and ExpressRoute security | Connectivity option comparison and encryption decision | 0–3 |
| Service endpoints, private endpoints, and Private Link | PaaS access design with DNS notes | 0–3 |
| Azure Firewall and firewall policy | Rule collection design and logging validation | 0–3 |
| Application Gateway, Front Door, and WAF | Layer 7 protection decision record | 0–3 |
| DDoS Protection and Network Watcher | Trigger criteria and troubleshooting evidence | 0–3 |

Decision questions:

- Which traffic must remain private, and where will DNS resolution occur?
- When should controls be applied at subnet, workload, perimeter, or application layer?
- How will you prove that a rule works and does not break required traffic?

## 3. Secure Compute, Storage, and Databases — 20–25%

| Capability | Evidence to Produce | Score |
|---|---|---:|
| Bastion and just-in-time VM access | Remote-access design with exposed-port comparison | 0–3 |
| AKS, ACI, ACA, and ACR security | Identity, network isolation, and image-access checklist | 0–3 |
| Disk and host encryption | Encryption choice and key-responsibility notes | 0–3 |
| Storage access and threat protection | RBAC/SAS/key comparison and recovery test | 0–3 |
| Soft delete, versioning, immutability, and backup | Destructive-test recovery evidence | 0–3 |
| Azure SQL security | Entra authentication, auditing, masking, TDE, and Always Encrypted decision | 0–3 |

## 4. Defender for Cloud and Sentinel — 30–35%

| Capability | Evidence to Produce | Score |
|---|---|---:|
| Azure Policy and initiatives | Assignment, compliance result, exemption, and remediation | 0–3 |
| Key Vault | RBAC, network rules, rotation, backup, and recovery evidence | 0–3 |
| Defender for Cloud posture management | Secure Score improvement with risk justification | 0–3 |
| Regulatory compliance | Standard mapping and evidence-gap analysis | 0–3 |
| Hybrid and multicloud connectors | Responsibility and data-flow diagram | 0–3 |
| Workload protection | Defender plan selection based on protected assets | 0–3 |
| Sentinel connectors and analytics | Data connector, analytic rule, incident, and test result | 0–3 |
| Automation | Workflow trigger, approval boundary, and rollback | 0–3 |

## Completion Standard

Do not treat a configuration screenshot as proof by itself. For each skill, capture:

1. Requirement and threat addressed.
2. Chosen control and rejected alternatives.
3. Implementation steps.
4. Positive and negative tests.
5. Monitoring and evidence source.
6. Rollback and cost-cleanup steps.

