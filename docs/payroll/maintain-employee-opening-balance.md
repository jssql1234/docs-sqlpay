---
sidebar_position: 14
id: maintain-employee-opening-balance
title: Maintain Employee's Opening Balance
description: A guide to maintain employee's opening balance
slug: /maintain-employee-opening-balance
tags: ["SQL Payroll", "Employee", "Opening Balance"]
---

# Maintain Employee's Opening Balance
Maintain employee’s opening balance is done when the respective employee enter the company in a month **later than January**.

The previous PCB amount is **needed to key in so that the system can correctly calculate** the PCB amount that’s needed to pay every month.

:::info[note]
CN translation: 1 月后进公司的员工都要打 ‘opening’, 这样系统才能真确地算出员工的 PCB
:::

## Step 1: Navigate yourself to the open payroll

![1](/img/payroll/maintain-employee-opening-balance/1.png)

## Step 2: Double click the year in open payroll

![2](/img/payroll/maintain-employee-opening-balance/2.png)

## Step 3: Double click the transaction under ‘Opening’

![3](/img/payroll/maintain-employee-opening-balance/3.png)

## Step 4: Select the employee by double clicking on its name

![4](/img/payroll/maintain-employee-opening-balance/4.png)

## Step 5: Key in all the employee’s opening balance information 

![5](/img/payroll/maintain-employee-opening-balance/5.png)

## Mapping of SQL ‘opening’ to EA form (SQL ‘Opening’与 EA form 的对比)

![6](/img/payroll/maintain-employee-opening-balance/6.png)

## Special note for additional EPF and additional PCB

- Additional EPF and additional PCB are used when additional remuneration (bonus, commission, paid leave) is given. 
- In the EA form, normal EPF and additional EPF is group into one. 
- However, SQL recommend users to split the amount for a more detail input.  

额外收入（如: 花红，佣金，带薪休假）都会分类在 Additional EPF 和 additional PCB 
虽然在 EA form 里，普通 EPF 和 additional EPF 是组合起来了，但是，SQL 建议各位用户把普通 EPF 和 additional EPF 分出来比较好。

![7](/img/payroll/maintain-employee-opening-balance/7.png)