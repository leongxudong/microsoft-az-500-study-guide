# Microsoft AZ-500 Study Guide and Hands-On Labs

Community learning materials for **Exam AZ-500: Microsoft Azure Security Technologies** and the **Microsoft Certified: Azure Security Engineer Associate** role.

> [!IMPORTANT]
> Microsoft will retire AZ-500 and the Azure Security Engineer Associate certification on **31 August 2026 at 11:59 PM Central Time**. Microsoft identifies **SC-500: Implementing End-to-End Security Controls for Cloud and AI Workloads** as the successor course and certification path. This repository was last checked against Microsoft Learn on **15 July 2026**.

Use this repository if you are already preparing for AZ-500 before retirement, or if you want practical Azure security engineering foundations that transfer to SC-500.

## What You Will Learn

- Secure Azure identity, access, applications, and managed identities.
- Design and implement private and public network controls.
- Protect compute, storage, databases, secrets, keys, and backups.
- Use Azure Policy, Microsoft Defender for Cloud, and Microsoft Sentinel.
- Explain security decisions using risk, compliance, and operational trade-offs.

## Exam Domains

| Domain | Weight |
|---|---:|
| Secure identity and access | 15–20% |
| Secure networking | 20–25% |
| Secure compute, storage, and databases | 20–25% |
| Secure Azure using Microsoft Defender for Cloud and Microsoft Sentinel | 30–35% |

The percentages and objective groupings above reflect Microsoft's skills measured as of 22 January 2026. Always check the [official AZ-500 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-500) before scheduling an exam.

## Repository Map

```text
microsoft-az-500-study-guide/
├── README.md
├── docs/
│   ├── objective-map.md
│   └── four-week-study-plan.md
├── labs/
│   ├── 01-identity-and-access.md
│   ├── 02-network-security.md
│   ├── 03-compute-storage-databases.md
│   └── 04-defender-and-sentinel.md
├── practice/
│   └── scenarios.md
├── checklists/
│   └── exam-readiness.md
└── resources/
    └── official-links.md
```

## Recommended Study Method

1. Read the [objective map](docs/objective-map.md) and score each skill from 0 to 3.
2. Follow the [four-week study plan](docs/four-week-study-plan.md).
3. Complete each lab in a personal sandbox subscription.
4. Record evidence: configuration, validation result, rollback step, and lesson learned.
5. Work through the [architecture scenarios](practice/scenarios.md) without memorising product names alone.
6. Use the [readiness checklist](checklists/exam-readiness.md) before booking.

## Lab Safety and Cost Control

- Use a personal lab tenant or authorised sandbox only.
- Never test in an employer or client environment without written approval.
- Set budgets and cost alerts before deploying resources.
- Prefer the smallest eligible resource sizes and remove resources after each lab.
- Do not commit tenant IDs, subscription IDs, secrets, tokens, logs, or screenshots containing personal data.

## AZ-500 to SC-500 Transition

The enduring skills are identity, Key Vault, policy, network security, workload protection, posture management, and monitoring. SC-500 adds stronger emphasis on end-to-end controls for cloud and AI workloads. Learners starting after the AZ-500 retirement window should use this repository for foundational labs, then map them to the [official SC-500 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-500).

## Integrity Notice

These are original learning notes and lab prompts. They do not contain leaked questions, exam dumps, proprietary courseware, or confidential material. Microsoft Learn remains the authoritative source for certification requirements and product behaviour.

