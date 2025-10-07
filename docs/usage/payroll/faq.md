---
title: FAQ
description: A faq for payroll
slug: /usage/payroll/faq
tags: ["SQL Payroll", "FAQ"]
---

## How to solve when missing code and employee name columns in the month payroll screen?

**Issue:**

![issue-1](../../../static/img/usage/payroll/faq/issue_1.png)

**Solution:**

![solution-1](../../../static/img/usage/payroll/faq/solution_1.png)

## Error message dataset "CalendarInfo" does not exist when batch email using customize payslip format

**Issue:**

Error message prompt when try to **Export to E-Mail Client (Batch)** using **customize payslip format**.

![issue-2](../../../static/img/usage/payroll/faq/issue_2.png)

**Solution:**

At payslip report designer,

    Change the [\<Profile."RegisterNo"\>] to [\<Profile."BRN"\>]

    ![solution-2a](../../../static/img/usage/payroll/faq/solution_2a.png)

After correction, it will be look like the screenshot below.

    ![solution-2b](../../../static/img/usage/payroll/faq/solution_2b.png)

## Where to define the company leave policy?

**Solution:**

1. Preset the leave policy at **Leave | Maintain Leave Group...**

## Why date format not display correctly in some payroll report?

**Issue:**

What is the faster solution to show the date format correctly?

![issue-4](../../../static/img/usage/payroll/faq/issue_4.png)

Government Reports | Print Income Tax PCB 2 (II)

**Solution:**

1. Go to Control Panel.
2. Search for Region in Control Panel. 3. Click on Additional Settings...

![solution-4a](../../../static/img/usage/payroll/faq/solution_4a.png)

4. Click to Date tab.
5. Change the Short Date Format to DD/MM/YYYY

![solution-4b](../../../static/img/usage/payroll/faq/solution_4b.png)

6. Date format has display correctly now.

![solution-4c](../../../static/img/usage/payroll/faq/solution_4c.png)
