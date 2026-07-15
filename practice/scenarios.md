# AZ-500 Practice Scenarios

These are original decision exercises, not replicas of certification questions. Write your answer before opening Microsoft documentation.

## Scenario 1 — Permanent Privilege

Administrators have permanent Owner access at subscription scope. The organisation needs emergency access but wants routine administration to be time-bound.

Address:

- Role and scope changes.
- PIM configuration.
- Conditional Access and MFA.
- Emergency-access exclusions and monitoring.
- Evidence that privileged access is reviewed.

## Scenario 2 — Application Secret Sprawl

An Azure-hosted application stores a client secret in a configuration file and accesses several Key Vault secrets it does not need.

Address:

- Managed identity.
- Key Vault RBAC or access model.
- Network restrictions.
- Secret rotation and audit evidence.
- Migration and rollback.

## Scenario 3 — Public Storage Exposure

A storage account containing sensitive test data is reachable from the internet. Developers need access from one application subnet and an approved administrative path.

Address:

- Public access settings.
- Private endpoint and DNS.
- Authentication and authorisation.
- Data protection and recovery.
- Validation from allowed and denied locations.

## Scenario 4 — Internet-Facing Application

A public web application needs TLS, WAF protection, resilient global routing, and private access to its backend.

Compare:

- Front Door and Application Gateway.
- WAF placement.
- Private Link or private endpoints.
- DDoS protection.
- Logging and incident evidence.

## Scenario 5 — Secure Score Without Context

Management asks the team to maximise Secure Score immediately, but several recommendations would disrupt legacy workloads.

Address:

- Risk prioritisation.
- Compensating controls.
- Policy exemptions.
- Remediation ownership and deadlines.
- Reporting residual risk rather than presenting the score alone.

## Scenario 6 — Cloud Alert Automation

Defender for Cloud generates repeated alerts for suspicious activity on test servers. The team wants automation but cannot risk disabling business services.

Address:

- Alert validation and tuning.
- Sentinel ingestion and incident grouping.
- Non-destructive enrichment.
- Approval boundaries for containment.
- Closure evidence and lessons learned.

## Self-Review Rubric

A strong response includes requirement, threat, control choice, rejected alternative, dependency, validation, monitoring, rollback, and residual risk.

