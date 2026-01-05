---
sidebar_position: 2
title: Guide
description: Guide
slug: /usage/human-resource/guide
tags: ["HR", "Bulk Email","Employee Login","Print Letter","Increment Letter","MyKad Reader","Recurring Zakat","Loan"]
---

## Bulk Email With Password

:::note

- This feature is not applicable for **Export to Email Client** or **Export to PDF**.
- If there are multiple records (e.g., 10 records) in one PDF to be emailed to a single recipient, the system cannot generate a password as it cannot determine which password to apply.

:::

### Prerequisites

:::info
To use this feature, the user's computer must be configured with a Windows email client.
:::

### Setup

1. Navigate to **Human Resource** > **Maintain Employee**.

2. Enter the PDF password and the email address.

   ![des-maintain-employee-1](../../../static/img/usage/human-resource/hr-function-images/maintain-employee-1.png)

3. Next, go to **Payroll** > **Print Payslip**. Select the Month End Payslip, click **Apply**, and then **Preview**.

4. Click the 🔽 arrow beside the Excel export icon and select **Export to Email Client (Batch)**.

   ![des-export-to-email-client-batch](../../../static/img/usage/human-resource/hr-function-images/export-to-email-client-batch.png)

   :::tip
   For testing purposes, you can activate the module by going to **File** > **Customize Payroll Module** and checking **Batch Email**.
   :::

   ![des-batch-email](../../../static/img/usage/human-resource/hr-function-images/batch-email.png)

   :::warning Error
   If you haven't configured your Windows email client, you will see the error message below. Ensure your email client is configured before proceeding.
   :::

   ![des-error](../../../static/img/usage/human-resource/hr-function-images/error.png)

### Steps to Use IC as PDF Password

1. Navigate to **Human Resource** > **Maintain Employee**.

2. Click on one employee record, hold the `Shift` key on your keyboard, and click the last record to highlight all employees.

3. Click the 🔽 arrow beside **More** and select **Batch Edit**.

4. In the columns section, click **Field Chooser** and select **Name2** and **New IC**.

5. Save the structure, then copy the **New IC** values and paste them into the **Name2** column.

![des-ic-as-pdf-password-1](../../../static/img/usage/human-resource/hr-function-images/ic-as-pdf-password-1.png)

![des-ic-as-pdf-password-2](../../../static/img/usage/human-resource/hr-function-images/ic-as-pdf-password-2.png)

![des-ic-as-pdf-password-3](../../../static/img/usage/human-resource/hr-function-images/ic-as-pdf-password-3.png)

![des-ic-as-pdf-password-4](../../../static/img/usage/human-resource/hr-function-images/ic-as-pdf-password-4.png)

## Employee Login

:::info
This guide explains how to configure and create an account for the employee in SQL Payroll which allows employees to view their details.
:::

1. In SQL Payroll, navigate to **Human Resource** > **Maintain Employee**.

2. Click **Change Password**.

   ![des-change-password](../../../static/img/usage/human-resource/hr-function-images/change-password.png)

3. Enter a new password for the employee.

   ![des-enter-password](../../../static/img/usage/human-resource/hr-function-images/enter-password.png)

4. Next, instruct the employee to open SQL Payroll and log in using the **Employee Code** and **Password** configured previously. That's it! 🥳

   ![des-login](../../../static/img/usage/human-resource/hr-function-images/login.png)

5. Below is an example of the employee view:

   ![des-employee-view](../../../static/img/usage/human-resource/hr-function-images/employee-view.png)

## Print Letter

:::info
This guide explains how to print Appointment, Confirmation, and Increment letters.
:::

1. Navigate to the **Maintain Employee** panel.

   ![des-v](../../../static/img/usage/human-resource/hr-function-images/navigate.png)

2. Select an employee.

   ![des-select-employee](../../../static/img/usage/human-resource/hr-function-images/select-employee.png)

3. Click **Preview Reports**.

   ![des-preview-report](../../../static/img/usage/human-resource/hr-function-images/preview-report.png)

4. Double-click the desired report to select it.

   ![des-select-report](../../../static/img/usage/human-resource/hr-function-images/select-report.png)

5. Below is an example of an appointment letter:

   ![des-letter-example](../../../static/img/usage/human-resource/hr-function-images/letter-example.png)

### Increment Letter

:::note
For the increment letter, ensure that an increment is recorded in **History** for the report to generate correctly.
:::

1. Navigate to **Human Resource** > **Maintain Employee**.

   ![des-navigate-1](../../../static/img/usage/human-resource/hr-function-images/navigate-1.png)

2. Alternatively, click **Maintain Employee** on the homepage.

   ![des-navigate-2](../../../static/img/usage/human-resource/hr-function-images/navigate-2.png)

3. Open the employee details and click the **History** tab.

   ![des-inc-letter-select-employee](../../../static/img/usage/human-resource/hr-function-images/inc-letter-select-employee.png)

4. Click **Preview Reports**.

   ![des-inc-letter-click-preview](../../../static/img/usage/human-resource/hr-function-images/inc-letter-click-preview.png)

5. Select the report you wish to print.

   ![des-inc-letter-select-report](../../../static/img/usage/human-resource/hr-function-images/inc-letter-select-report.png)

#### Increment Letter Setup in History

![des-increment-letter-setup](../../../static/img/usage/human-resource/hr-function-images/increment-letter-setup.png)

## Maintain Employee with MyKad Reader

1. Connect your Smart Card Reader to your computer.

2. The reader's light will turn red when successfully connected.

   ![des-reader](../../../static/img/usage/human-resource/hr-function-images/reader.png)

3. Insert the MyKad into the reader.

4. The reader's light will turn blue when the MyKad is successfully read.

   ![des-plug-in-mykad](../../../static/img/usage/human-resource/hr-function-images/plug-in-mykad.png)

5. In SQL Payroll, open a **New Employee** profile and click **Read MyKad**.

   ![des-read-mykad](../../../static/img/usage/human-resource/hr-function-images/read-mykad.png)

6. Select **Reader Devices** and click **Read Card**.

   ![des-read-card](../../../static/img/usage/human-resource/hr-function-images/read-card.png)

7. Click **Read MyKad**.

   ![des-read-mykad-physical](../../../static/img/usage/human-resource/hr-function-images/read-mykad-physical.png)

8. The system will automatically fill in the MyKad details:

   - **(NAME, ADDRESS, ID Number, D.O.B, GENDER)**

   ![des-result](../../../static/img/usage/human-resource/hr-function-images/result.png)

## Recurring Zakat

1. Go to **Maintain Employee**.

   ![des-maintain-employee-button](../../../static/img/usage/human-resource/hr-function-images/maintain-employee-button.png)

2. Select the respective employee and go to the **Deduction** tab.

   ![des-deduction](../../../static/img/usage/human-resource/hr-function-images/deduction.png)

3. Enter a deduction and check the **Zakat** box. Note that other contribution checkboxes will be automatically unchecked.

   ![des-check-zakat](../../../static/img/usage/human-resource/hr-function-images/check-zakat.png)

4. Enter the **Rate** and set the contribution period in the **Date From** and **Date To** columns.

   ![des-key-in-rate](../../../static/img/usage/human-resource/hr-function-images/key-in-rate.png)

5. Save and process the month-end payroll. The amount will appear in **Gross Zakat**.

   ![des-result-1](../../../static/img/usage/human-resource/hr-function-images/result-1.png)

   ![des-result-2](../../../static/img/usage/human-resource/hr-function-images/result-2.png)

## Loan

:::note NOTE:
This is a **Paid Module**
:::

This module is for companies that provide loans to employees, which are repaid through salary deductions with interest.

## Maintain Loan

This section allows users to set up loans for selected employees.

Assume the following scenario:

| Field Name                  | Properties        |
|-----------------------------|-------------------|
| Employee Code               | 0010              |
| Loan Amount                 | 50,000            |
| Loan Interest               | 2,000             |
| Number of Repayment (Months)| 60                |
| First Repayment Date        | 01 Mar 2013       |

### Loan Amount & Interest Amount

1. Click **New** and enter the details as follows:

   ![des-maintain-loan-step-1](../../../static/img/usage/human-resource/hr-function-images/maintain-loan-step-1.jpg)

2. Click the **Schedule | Generate...** button.

   ![des-maintain-loan-step-2](../../../static/img/usage/human-resource/hr-function-images/maintain-loan-step-2.jpg)

3. Click **OK** to confirm.

4. Click **Save**.

### Auto Repayment

1. Process payroll as usual (refer to [New Payroll](../payroll/guide.md#create-payroll)).

2. In the selected employee's paysheet, click **Loan**.

   ![des-auto-repayment-step-1](../../../static/img/usage/human-resource/hr-function-images/auto-repayment-step-1.jpg)

### Advanced Repayments

1. In the **Transaction** tab:

   ![des-advanced-repayment-step-1](../../../static/img/usage/human-resource/hr-function-images/advanced-repayment-step-1.jpg)

## Print Loan Repayment History

This generates/prints the Ledger/History of loans given by the company for selected or all employees.

![des-loan-repayment-history-step-1](../../../static/img/usage/human-resource/hr-function-images/loan-repayment-history-step-1.jpg)
