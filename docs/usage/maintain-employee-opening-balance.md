---
title: Maintain Employee Opening Balance
description: A guide to maintain employee's opening balance
slug: /usage/maintain-employee-opening-balance
tags: ["SQL Payroll", "Employee", "Opening Balance"]
---

## Introduction

- Maintain employee’s opening balance is done when the respective employee enter the company in a month **later than January**.
- The previous PCB amount is **needed to key in so that the system can correctly calculate** the PCB amount that’s needed to pay every month.

## Setup

1. Navigate to the **Open Payroll**

   ![navigate](../../static/img/usage/maintain-employee-opening-balance/navigate.png)

2. Double click the year in Open Payroll

   ![open-payroll](../../static/img/usage/maintain-employee-opening-balance/open-payroll.png)

3. Double click the transaction under ‘Opening’

   ![open-txn](../../static/img/usage/maintain-employee-opening-balance/open-txn.png)

4. Select the employee by double clicking on the name

   ![select-employee](../../static/img/usage/maintain-employee-opening-balance/select-employee.png)

5. Key in all the employee’s opening balance information

   ![key-in-employee-details](../../static/img/usage/maintain-employee-opening-balance/key-in-employee-details.png)

## Mapping of SQL 'opening' to EA form

![mapping](../../static/img/usage/maintain-employee-opening-balance/mapping.png)

## Special note for additional EPF and additional PCB

- Additional EPF and additional PCB are used when additional remuneration (bonus, commission, paid leave) is given.
- In the EA form, normal EPF and additional EPF is group into one.
- However, SQL recommend users to split the amount for a more detail input.

![notes](../../static/img/usage/maintain-employee-opening-balance/notes.png)
