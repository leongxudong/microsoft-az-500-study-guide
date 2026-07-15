# Four-Week AZ-500 Study Plan

This accelerated plan assumes prior Azure fundamentals and 8–10 focused hours per week. Extend it if Azure administration is new to you.

## Before Week 1

- Read the official study guide and confirm the exam retirement deadline.
- Create a personal Azure sandbox and configure a budget alert.
- Prepare a lab journal with columns for objective, design, implementation, validation, failure, and lesson learned.
- Take Microsoft's free practice assessment as a baseline, if available.

## Week 1 — Identity and Governance

Study:

- Azure RBAC and Microsoft Entra roles.
- PIM, MFA, Conditional Access, emergency access, and access reviews.
- App registrations, enterprise applications, OAuth consent, service principals, and managed identities.
- Azure Policy, initiatives, exemptions, remediation, and resource locks.

Practice:

- Complete [Lab 01](../labs/01-identity-and-access.md).
- Explain the difference between control-plane and data-plane access.
- Build a least-privilege role matrix for administrator, application, and auditor personas.

Checkpoint: You can implement privileged access without permanently assigning broad roles.

## Week 2 — Network Security

Study:

- NSGs, ASGs, UDRs, peering, VPN, Virtual WAN, and Network Watcher.
- Service endpoints, private endpoints, Private Link, and private DNS.
- Azure Firewall, WAF, Application Gateway, Front Door, TLS, and DDoS Protection.

Practice:

- Complete [Lab 02](../labs/02-network-security.md).
- Draw packet flows for allowed and denied traffic.
- Troubleshoot a deliberately broken NSG or DNS configuration.

Checkpoint: You can select private versus public access patterns and prove effective traffic flow.

## Week 3 — Compute, Storage, Databases, and Keys

Study:

- Bastion, JIT access, disk encryption, AKS security, ACR access, and API Management.
- Storage RBAC, SAS, keys, firewalls, soft delete, versioning, immutability, and encryption.
- Azure SQL Entra authentication, auditing, masking, TDE, and Always Encrypted.
- Key Vault RBAC, firewalls, private endpoints, rotation, backup, and recovery.

Practice:

- Complete [Lab 03](../labs/03-compute-storage-databases.md).
- Compare platform-managed keys, customer-managed keys, and application-level encryption.

Checkpoint: You can protect data throughout access, storage, recovery, and key lifecycles.

## Week 4 — Defender for Cloud, Sentinel, and Review

Study:

- Secure Score, recommendations, regulatory standards, Defender plans, vulnerability management, and DevOps security.
- Defender for Cloud alerts, workflow automation, Azure Monitor data collection, Sentinel connectors, analytics, and automation.

Practice:

- Complete [Lab 04](../labs/04-defender-and-sentinel.md).
- Work through every [scenario](../practice/scenarios.md).
- Retake the official practice assessment and review every uncertain answer using Microsoft Learn.

Checkpoint: You can connect posture, threat protection, monitoring, incident handling, and automation into one operating model.

## Final 48 Hours

- Stop adding new topics.
- Review decision points, not isolated portal steps.
- Confirm exam time, identity documents, testing rules, and accommodations.
- Use the [readiness checklist](../checklists/exam-readiness.md).

