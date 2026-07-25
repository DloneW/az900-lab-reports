# Lab 01: Deploy a Static Website with Azure Blob Storage

**Course:** AZ-900T00-A: Introduction to Cloud Infrastructure [Cloud Slice Provided]
**Environment:** Microsoft Learn Hosted Cloud Slice (Azure)
**Required:** Yes
**Status:** ✅ Complete
**Started:** Friday, July 24, 2026 — 4:18 PM (WAT)
**Ended:** Friday, July 24, 2026 — 5:05 PM (WAT)
**Duration:** ~47 minutes (Expected: 1 hour)

---

## Objective

Provision an Azure Storage account and enable static website hosting directly from Blob Storage, without needing a dedicated web server.

## Core Concepts Covered

- Creating and configuring an Azure Storage account
- Enabling the **Static Website** feature on Blob Storage
- Understanding the `$web` container and its role in serving static content
- Uploading `index.html` / `error.html` assets to blob storage
- Retrieving and validating the primary web endpoint
- Cost and scalability implications of serving static content directly from storage vs. a compute-based web server

## Relevance

Blob-hosted static sites are a common low-cost pattern for portfolios, documentation sites, and landing pages. From a security-analyst lens, this lab is also useful for understanding a common **attack surface**: publicly exposed storage endpoints are frequently misconfigured (e.g., left with anonymous read access at the container level, or exposing sensitive files unintentionally) — a pattern relevant to external recon and exposure assessments.

## Skills Demonstrated

- Azure Storage account provisioning and configuration
- Static website hosting architecture
- Cloud resource lifecycle awareness

---
*Part of the [AZ-900T00-A Lab Reports](../README.md) series.*
