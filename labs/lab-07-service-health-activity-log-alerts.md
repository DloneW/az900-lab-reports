# Lab 07: Monitor Azure with Service Health and Activity Log Alerts

**Course:** AZ-900T00-A: Introduction to Cloud Infrastructure [Cloud Slice Provided]
**Environment:** Microsoft Learn Hosted Cloud Slice (Azure)
**Required:** Yes
**Status:** ✅ Complete
**Duration:** Expected 1 hour

---

## Objective

Configure Azure Monitor to send proactive notifications for service health incidents and resource activity, using action groups and alert rules.

## Core Concepts Covered

- Creating an **Azure Monitor Action Group** to define who gets notified and how
- Subscribing an email recipient to an action group
- Understanding **Activity Log alerts** vs. **Service Health alerts**
- Triggering and validating a **test alert** to confirm delivery end-to-end
- Reviewing alert metadata: tracking ID, incident type, impacted services/regions, communication status

## Evidence of Completion

Two confirmation emails were received from Microsoft Azure, verifying the action group and alert pipeline were correctly configured:

**1. Action Group Confirmation**
- Notification: *"You've been added to an Azure Monitor action group"*
- Action group name: `ag-gp-ops-email`
- Resource group: `rg-gp-monitoring-alerts`
- Subscription ID: `DFA2C547-25DE-4C7D-93CC-D76ED15A69D4`

**2. Test Alert Delivery Confirmation**
- Notification: *"Delivery Confirmation: This is a sample service health alert from Azure Monitor Action Groups"*
- Triggered rule: `test-ServiceHealthAlertRule`
- Tracking ID: `TEST-TTT`
- Type: Incident
- Latest status: Active — July 25, 2026, 13:45 UTC
- Impacted service(s): Virtual Machines
- Impacted region(s): US West, US East

Both confirmations demonstrate the full alert path working correctly: action group → alert rule trigger → notification delivery.

## Relevance

Alerting and monitoring are foundational to detection — an environment with no service health or activity log alerts configured has no early warning system for outages or suspicious changes. This lab is directly applicable to setting up baseline monitoring during a security hygiene audit or as part of ongoing managed detection work.

## Skills Demonstrated

- Azure Monitor action group configuration
- Activity Log and Service Health alert setup
- End-to-end alert delivery validation

---
*Part of the [AZ-900T00-A Lab Reports](../README.md) series.*
