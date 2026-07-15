# Lab 01 — Identity, Privilege, and Workload Access

## Goal

Implement least-privilege human and workload access, then validate that intended access succeeds and unintended access fails.

## Scenario

A cloud operations team needs time-bound administrative access. An application must read one secret without storing credentials. Emergency access must remain possible without becoming a routine bypass.

## Tasks

1. Create a resource group containing a Key Vault and a low-cost test resource.
2. Define three personas: reader, resource operator, and privileged administrator.
3. Assign the smallest suitable built-in roles at the narrowest practical scope.
4. If licensing permits, configure the administrator as PIM-eligible with MFA, justification, limited duration, and approval.
5. Create a managed identity for a test workload and grant only the required Key Vault data-plane permission.
6. Draft a Conditional Access policy for administrators in report-only mode.
7. Document emergency-access exclusions and monitoring controls.

## Validation

- Prove the reader cannot modify resources.
- Prove the operator cannot change role assignments.
- Prove the managed identity can access the intended secret and no others.
- Review sign-in or audit evidence for role activation and policy evaluation.

## Failure Injection

- Remove the managed identity assignment and confirm access fails.
- Add an overly broad role, identify the excess permissions, then remediate it.

## Evidence Template

| Item | Record |
|---|---|
| Requirement | |
| Role and scope | |
| Positive test | |
| Negative test | |
| Audit evidence | |
| Rollback | |

## Cleanup

Remove temporary assignments, secrets, identities, policies, and resources. Never publish tenant identifiers or secret values.

