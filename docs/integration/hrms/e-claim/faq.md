---
sidebar_position: 4
title: FAQ
description: E-Claim Frequently Asked Questions
slug: /integration/hrms/e-claim/faq
tags: ["SQL HRMS", "E-Claim", "Troubleshooting FAQ"]
---
## Approvals & Audit Trail

### Why does the change log show “ADMIN” instead of the manager’s name?

When a claim is approved or rejected directly in **SQL Payroll** (rather than in HRMS), the audit log records the action under **ADMIN**. Approvals completed within HRMS display the actual manager’s name.

---

## E-Invoice Claim Workflow

### What is an E-Invoice Claim?

This submission type requires an attachment containing a **valid e-invoice QR code**. SQL HRMS scans the file, validates the QR code, and auto-populates the invoice details in the claim form.

### Why do I see “No QR detected” after attaching an e-invoice?

Common reasons include:

- No QR code present in the attachment.
- QR code is too small or low quality to be read.
- The e-invoice itself is invalid.

Upload a clear, valid e-invoice and attach it again.

### Why is the Supplier Name or E-Invoice No truncated in `Ref 1` / `Ref 2`?

Each reference field supports up to **80 characters**. Values longer than that are automatically shortened to fit the limit.
