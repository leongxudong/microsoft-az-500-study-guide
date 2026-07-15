# Lab 03 — Protect Compute and Data Services

## Goal

Apply layered controls to compute, storage, database, encryption, and recovery paths.

## Scenario

A small application handles sensitive records. Administrators need controlled access, data must be recoverable after accidental deletion, and database activity must be auditable.

## Tasks

1. Select a low-cost compute option and document why it fits the scenario.
2. Remove direct administrative exposure; use Bastion, JIT, or another approved controlled-access pattern.
3. Enable appropriate disk or platform encryption and document key ownership.
4. Configure Storage access using Entra ID/RBAC where possible; compare SAS and account keys.
5. Enable soft delete, versioning, and an appropriate backup or immutability control.
6. Configure Azure SQL Entra authentication and auditing in a sandbox database.
7. Compare TDE, Always Encrypted, dynamic data masking, and application-level encryption.
8. Store one application secret in Key Vault and document rotation and recovery.

## Validation

- Demonstrate least-privilege access to storage and database resources.
- Delete and recover a non-sensitive test object.
- Verify that database audit events are produced.
- Confirm secret access works only for the intended identity.

## Decision Record

For each control, record the threat addressed, service dependency, residual risk, operational owner, evidence source, and recovery method.

## Cleanup

Remove databases, compute, storage, vaults, backups, and monitoring destinations created for the lab.

