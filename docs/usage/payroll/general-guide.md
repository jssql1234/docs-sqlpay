---
sidebar_position: 2
title: General Guide
description: A guide to maintain payroll
slug: /usage/payroll/general
tags: ["SQL Payroll", "Payroll", "Month End", "Pending Payroll"]
---

## Create Payroll

### Final Process

Enable to process the Month Pay Salary and Final Pay Salary.

1. Click into **Payroll** and look for **New Payroll**.

   :::tip
   Certain company their payroll cut off date will not in the month end, some of the company will according to the 26th of the month, so you can preset your own company payroll cut off date through the "..." button.
   :::

   ![month-end](../../../static/img/usage/payroll/general/create.png)

2. Click on the **Process** option.

### Frequency Process

To process mid month salary payroll. The salary payout is based on average % of the Fixed Salary.

Not the last Pay of the Month.

![pay-frequency](../../../static/img/usage/payroll/general/jj1_pay_frequency.png)

### Ad Hoc Process

To process Mid Month Ad Hoc Payroll

![pay-adhoc](../../../static/img/usage/payroll/general/jj2_pay_adHoc.png)

![pay-adhoc-bonusallow](../../../static/img/usage/payroll/general/jj3_pay_adHoc_bonusallow.png)

Default this option
- All(PCB,Socso,EPF) Contribution for Fixed Transaction will be 0
- Value will be 0 (Zero) & user need to self enter a value for All/Selected Employee

![pay-adhoc-monthlyFA](../../../static/img/usage/payroll/general/jj4_pay_adhoc_montlyFA.png)

In this option allow the user to self control the Contribution (default 100%) for Fixed Transaction.

In other word if (eg Bonus with PCB (A) only just set Contribution to 0%)

## Open Payroll

:::info
Once you have created the payroll and you wish to view whatever you have did, then you can make some amendment.
:::

1. Navigate to **Payroll** > **Open Payroll**. Alternatively, access it from the home page by clicking **Open Payroll**

   ![open-navigate](../../../static/img/usage/payroll/general/open-navigate.png)

2. Select employee, double click your employee name to check on its individual’s amount

   ![open-select-employee](../../../static/img/usage/payroll/general/open-select-employee.png)

   :::info
   You can process 2 month end in the same day also. Initially, you can choose to tick those first batch employees.

   While processing the 2nd batch, you can tick the 2nd batch of users.

   Example:

   **BATCH 1**

   ![batch-1-payroll](../../../static/img/usage/payroll/general/batch-1-payroll.png)

   ![batch-1-employees](../../../static/img/usage/payroll/general/batch-1-employees.png)

   **BATCH 2**

   ![batch-2-payroll](../../../static/img/usage/payroll/general/batch-2-payroll.png)

   ![batch-2-employees](../../../static/img/usage/payroll/general/batch-2-employees.png)
   :::

## Open Pending Payroll

:::tip
Before you process the month end, you can use open pending payroll to key-in all others add hoc info like extra allowance, overtime, claim etc.
:::

- This is for the user to prepare the transaction (eg Overtime, Deduction) before Processing the Payroll...
- Available Pending Type Transactions

<table>
  <tr>
    <td>Wages</td><td>Allowance</td><td>Tax Deduction</td><td>Overtime</td>
  </tr>
  <tr>
    <td>Deduction</td><td>Advance Paid</td><td>Claims</td><td>Loan</td>
  </tr>
  <tr>
    <td>CP38</td><td>Advance Deduct</td><td>Bonus</td><td>Paid Leave</td>
  </tr>
  <tr>
    <td>Director Fees</td><td>Unpaid Leave</td><td>Tax Benefit</td><td>Commission</td>
  </tr>
</table>

- After all the Pending had enter user may go either below step to for next step except Pending Advance Paid
    - New Payroll | Final Process
    - New_Payroll | Ad Hoc Process
- For Pending Advance Paid must use New_Payroll | Ad Hoc Process then only can use New Payroll | Final Process

### Steps

1. Go to **Payroll** > **Open Pending Payroll**.

    ![navigate](../../../static/img/usage/payroll/general/navigate.png)

2. Double Click on the info that you want to input, eg: Overtime.

    ![pending-click-overtime](../../../static/img/usage/payroll/general/pending-click-overtime.png)

3. Insert the overtime info accordingly

    1. Press on the ➕ button to add new overtime.

        ![pending-add-new-overtime](../../../static/img/usage/payroll/general/pending-add-new-overtime.png)

    2. Insert the info accordingly like employee, overtime code, work unit etc

        ![pending-insert-info](../../../static/img/usage/payroll/general/pending-insert-info.png)

    3. Once update accordingly then save.

        ![pending-overtime-save](../../../static/img/usage/payroll/general/pending-overtime-save.png)

4. Once finish the update you may process the month end and observe the result.

    ![pending-result](../../../static/img/usage/payroll/general/pending-result.png)

### Pending YYYY

- YYYY represents the Year (e.g. if in 2013 will show as Pending 2013).
- To show the pending in Monthly (with & without Transactions).

![open-pending-payroll-02](../../../static/img/usage/payroll/general/jj5_Payroll_OpenPendingPayroll02.png)

### Pending Navigator

Show which Pending Type had transactions in the day view.

![open-pending-payroll-04](../../../static/img/usage/payroll/general/jj6_Payroll_OpenPendingPayroll04.png)

### Show all Pending Payroll

To show the pending in Yearly (with Transactions).

![open-pending-payroll-03](../../../static/img/usage/payroll/general/jj7_Payroll_OpenPendingPayroll03.png)

## Pending Transactions Types

1. Just click the + button on top of the Screen (The Green + and Money icon) to Insert record(s).

2. After done just Click the Blue Diskette icon on top of the Screen to save the record.

### Pending Wages

This is useful for employees to be paid by the number of days they work (i.e. users can add the day when the selected employee comes to work).

![pending-wages](../../../static/img/usage/payroll/general/jj8_Payroll_OpenPendingPayroll_Wages.png)

### Pending Overtime

![pending-overtime](../../../static/img/usage/payroll/general/jj9_Payroll_OpenPendingPayroll_Overtime.png)

### Pending Paid Leave

![pending-paid-leave](../../../static/img/usage/payroll/general/jj10_Payroll.OpenPendingPayroll_PaidLeave.png)

### Pending Unpaid Leave

![pending-unpaid-leave](../../../static/img/usage/payroll/general/jj11_Payroll.OpenPendingPayroll_UnpaidLeave.png)

### Pending Claim

![pending-claim](../../../static/img/usage/payroll/general/jj12_Payroll.OpenPendingPayroll_Claim.png)

### Pending CP38

This is generally towards settlement of outstanding taxes.

![pending-cp38-01](../../../static/img/usage/payroll/general/jj13_Payroll.OpenPendingPayroll_CP3801.png)

![pending-cp38-02](../../../static/img/usage/payroll/general/jj14_Payroll.OpenPendingPayroll_CP3802.png)

### Pending Allowance

![pending-allowance](../../../static/img/usage/payroll/general/jj15_Payroll.OpenPendingPayroll_Allowance.png)

### Pending Deduction & Pending Commission

Below Example information is applicable for

- Pending Deduction
- Pending Commission

![pending-deduction-commission](../../../static/img/usage/payroll/general/jj16_Payroll.OpenPendingPayroll_Deduction.png)

### Pending Bonus & Pending Director Fees
Below Example information is applicable for

- Pending Bonus
- Pending Director Fees

![pending-bonus-director-fees](../../../static/img/usage/payroll/general/jj17_Payroll.OpenPendingPayroll_Bonus.png)

### Pending Advance Paid, Pending Advance Deduct & Pending Loan

Below Example information is applicable for

- Pending Advance Paid
- Pending Advance Deduct (Only View because it derive from Advance Paid after Ad Hoc Process)
- Pending Commission

![pending-advance-paid-advance-deduct-commission](../../../static/img/usage/payroll/general/jj18_Payroll.OpenPendingPayroll_AdvancePaid.png)

### Pending Tax Benefit & Pending Tax Deduction

Below Example information is applicable for

- Pending Tax Benefit
- Pending Tax Deduction

![pending-tax-benefit-tax-deduction](../../../static/img/usage/payroll/general/jj19_Payroll.OpenPendingPayroll_TaxDeduct.png)
