# Lab 02 — Private PaaS Access and Layered Network Security

## Goal

Build a network path that permits authorised application traffic to a platform service while blocking unnecessary public exposure.

## Scenario

An internal workload must access an Azure Storage account. Administrative access must use a controlled path. The design must support troubleshooting and audit evidence.

## Tasks

1. Create a virtual network with separate workload and management subnets.
2. Apply NSGs that permit only documented flows.
3. Deploy a Storage account with public network access disabled.
4. Create a private endpoint and configure private DNS resolution.
5. Use Network Watcher or effective security rules to validate traffic decisions.
6. Compare Azure Bastion, JIT VM access, VPN, and public IP administration; document the chosen pattern.
7. Draft when Azure Firewall, Application Gateway/WAF, Front Door, or DDoS Protection would be required at larger scale.

## Validation

- Resolve the service name to its private address from the intended network.
- Confirm authorised private access succeeds.
- Confirm access from an unauthorised path fails.
- Capture effective NSG rules and the relevant flow diagram.

## Failure Injection

- Break private DNS intentionally and diagnose the result.
- Add a conflicting NSG rule, inspect priority evaluation, and remediate it.

## Design Questions

- Why choose a private endpoint instead of a service endpoint?
- Where should TLS terminate?
- Which logs prove whether a failure is caused by DNS, routing, NSG, firewall, identity, or the service itself?

## Cleanup

Delete all billable networking resources, especially gateways, firewalls, public IPs, and DDoS plans.

