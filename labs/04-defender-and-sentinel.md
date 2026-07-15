# Lab 04 — Posture, Detection, and Automation

## Goal

Connect governance, posture management, workload protection, monitoring, incident creation, and controlled automation.

## Scenario

A security team needs a repeatable view of cloud risk, evidence of compliance, and an incident workflow for high-confidence findings.

## Tasks

1. Review Defender for Cloud recommendations and Secure Score in a sandbox subscription.
2. Select one recommendation that is safe and affordable to remediate; record the before-and-after evidence.
3. Assign a relevant Azure Policy or initiative and review compliance state.
4. Document when an exemption is justified and what approval/evidence it requires.
5. Review Defender plans and enable only those required for the lab.
6. Connect an authorised data source to Microsoft Sentinel, if a workspace is available.
7. Create a simple analytic rule using lab-generated benign activity.
8. Define an automation workflow that enriches or routes an incident without destructive action.

## Validation

- Show the policy assignment, compliance result, and remediation task.
- Show the Defender recommendation or alert and its affected resource.
- Show the Sentinel incident or expected analytic-rule result.
- Explain false-positive handling, ownership, escalation, and closure evidence.

## Safety Boundary

Do not auto-isolate, delete, disable, or block production resources. Use approval gates for actions with operational impact.

## Cleanup

Disable paid plans that were enabled only for the lab and delete temporary workspaces, connectors, rules, playbooks, and resources.

