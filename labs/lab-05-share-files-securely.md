# Lab 05: Share Files Securely

**Course:** AZ-900T00-A: Introduction to Cloud Infrastructure [Cloud Slice Provided]
**Environment:** Microsoft Learn Hosted Cloud Slice (Azure)
**Required:** Yes
**Status:** ✅ Complete
**Duration:** Expected 1 hour

---

## Objective

Configure secure file sharing in Azure, using controlled access mechanisms rather than public exposure, to distribute files safely to intended recipients.

## Core Concepts Covered

- Provisioning Azure Storage for file sharing (Blob/File Share)
- Generating and scoping **Shared Access Signatures (SAS)** — time-limited, permission-scoped access tokens
- Setting expiration windows and permission levels (read-only, read/write) on shared access
- Avoiding public/anonymous exposure of sensitive files
- Reviewing access logs for shared resources

## Relevance

Secure file sharing is directly relevant to security hygiene audits — improperly scoped or non-expiring SAS tokens, and publicly accessible storage, are recurring findings in cloud misconfiguration assessments. This lab reinforces the "principle of least exposure" applied to data sharing.

## Skills Demonstrated

- Azure Storage secure sharing configuration
- SAS token generation and scoping
- Data exposure risk awareness

---
*Part of the [AZ-900T00-A Lab Reports](../README.md) series.*
