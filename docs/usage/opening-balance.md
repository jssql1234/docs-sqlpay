---
title: Opening Balance
description: A guide to maintain opening balance of employees
slug: /usage/opening-balance
tags: ["SQL Payroll", "Opening Balance"]
---

## Introduction

Maintain employee’s opening balance is done when the respective employee enter the company in a month **later than January**.

The previous PCB amount is **needed to key in so that the system can correctly calculate** the PCB amount that’s needed to pay every month.

## Setup

1. Navigate to **Payroll** > **Open Payroll**

   ![navigate](../../static/img/usage/opening-balance/navigate.png)

2. Double click on the payroll year to open it

   ![open](../../static/img/usage/opening-balance/open.png)

3. Double click on the transaction section under "**Opening**"

   ![open-transaction](../../static/img/usage/opening-balance/open-transaction.png)

4. Select the employee by double clicking on its name

   ![select-employee](../../static/img/usage/opening-balance/select-employee.png)

5. Key in all the employee’s opening balance information

   ![fill-in-employee-details](../../static/img/usage/opening-balance/fill-in-employee-details.png)

   :::info

   For the General part can enter information accordign to the EA form
   For others part Employee need to know whether they have any of it in previous employment
   :::

## Mapping of SQL "opening" to EA form

![mapping](../../static/img/usage/opening-balance/mapping.png)

## Special note for additional EPF and PCB

- Additional EPF and additional PCB are used when additional remuneration (bonus, commission, paid leave) is given.
- In the EA form, normal EPF and additional EPF is group into one.
- However, SQL recommend users to split the amount for a more detail input.

![additional-epf-pcb](../../static/img/usage/opening-balance/additional-epf-pcb.png)
