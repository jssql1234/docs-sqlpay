---
title: Why show error message dataset "CalendarInfo" does not exist when batch email using customize payslip format?
description: A guide to solve error message dataset "CalendarInfo" does not exist when batch email using customize payslip format
slug: /faq/error-calendarinfo
tags: ["SQL Payroll", "FAQ", "Error"]
---

## Issue

Error message prompt when try to **Export to E-Mail Client (Batch)** using **customize payslip format**.

![1](../../static/img/faq/error-calendarinfo/yc1-error.jpg)

## Solution

At payslip report designer, change the **[\<Profile."RegisterNo">]** to **[\<Profile."BRN">]**

![2](../../static/img/faq/error-calendarinfo/yc2-error.jpg)

**After correction**, it will be look like the screenshot below.

![3](../../static/img/faq/error-calendarinfo/yc3-error.jpg)