---
id: bulk-email
title: Bulk Email with Password
description: A guide to payroll bulk email module for SQL Payroll
slug: /usage/human-resource/bulk-email
tags: ["SQL Payroll", "Bulk Email"]
---

:::note

- Not applicable for Export Email Client or Export to PDF
- For Email Client, 10 records in one PDF, email to 1 recipient, system unable to generate password due to not sure which password should get

:::

## Prerequisites

:::info
In order to use this, user’s computer must configure with window email first
:::

## Setup

1. Navigate to **Human Resource** > **Maintain Employee**

2. Key in the PDF password and enter the email address

   ![maintain-employee](../../../static/img/usage/human-resource/payroll-bulk-email/maintain-employee.png)

3. Next, go to **Payroll** > **Print Payslip**. Choose the month End Payslip, Apply and Preview

4. Click on the 🔽 beside the excel export, click on **Export to Email Client (Batch)**

   ![export-to-email-client-batch](../../../static/img/usage/human-resource/payroll-bulk-email/export-to-email-client-batch.png)

   :::tip
   For Testing purpose, you may activate the module at File > Customize Payroll Module and ticked **Batch Email**
   :::

   ![batch-email](../../../static/img/usage/human-resource/payroll-bulk-email/batch-email.png)

   :::warning Error
   If you haven't configure your window email, you will see an error message as below. Make sure yo have configure your window email before doing these steps.
   :::

   ![error](../../../static/img/usage/human-resource/payroll-bulk-email/error.png)

## Simple Steps To use IC as PDF Password

1. Navigate to **Human Resource** > **Maintain Employee**

2. Click on one employee record, hold the `Shift` key in the keyboard and click on the last record to highlight all

3. Click on 🔽 button beside More, select Batch Edit

4. From the columns, click on field Chooser and select **Name2**, **New IC**

5. Save the structure, copy and paste the New IC value to Name2 column

![5](../../../static/img/usage/human-resource/payroll-bulk-email/5.png)

![6](../../../static/img/usage/human-resource/payroll-bulk-email/6.png)

![7](../../../static/img/usage/human-resource/payroll-bulk-email/7.png)

![8](../../../static/img/usage/human-resource/payroll-bulk-email/8.png)
