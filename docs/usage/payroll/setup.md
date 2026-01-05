---
sidebar_position: 1
title: Setup
description: A setup for payroll maintenance
slug: /usage/payroll/setup
tags: ["Setup","Maintain Wages","Maintain Frequency","Maintain Contribution","Maintain Allowance","Deduction","Maintain Overtime","OT","Maintain Claim","Maintain Commission","Maintain Payment Method"]
---

## Maintain Wages

:::info Features

- Allows setting different contributions for Bonus, Director Fee, Pay Leave, and Unpaid Leave.
- Maintain Employee & Employer EPF Rates.
- Maintain working hours and days per month.
- Enables Overtime Calculation based on Maintain Employee settings. It will calculate OT based on the wages amount in Maintain Employee.

:::

- Setting up Maintain Wages helps you categorize the type of wages an employee receives.
- This affects the types of contributions required (EPF/SOCSO/PCB, etc.).
- This is especially useful if you have different types of workers such as permanent workers, contract workers, foreign workers, etc.

1. Navigate to **Payroll** > **Maintenance** > **Maintain Wages**.

    ![maintain-wages](../../../static/img/usage/payroll/setup/maintain-wages/maintain-wages.png)

2. Click **New** to create a new wages type.

    ![new](../../../static/img/usage/payroll/setup/maintain-wages/new.png)

3. Enter the information and check the required contributions.

    ![fill-in-1](../../../static/img/usage/payroll/setup/maintain-wages/fill-in-1.png)
    ![fill-in-2](../../../static/img/usage/payroll/setup/maintain-wages/fill-in-2.png)

### Common wages setup

| Local Permanent Workers                                                                        | Foreign Workers                                                                |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| ![local-permanent](../../../static/img/usage/payroll/setup/maintain-wages/local-permanent.png) | ![foreign](../../../static/img/usage/payroll/setup/maintain-wages/foreign.png) |

## Maintain Frequency

1. Navigate to **Payroll** > **Maintenance** > **Maintain Frequency**.

    ![maintain-frequency](../../../static/img/usage/payroll/setup/maintain-frequency/maintain-frequency.png)

2. Click **New** to preset your contribution.

    ![new](../../../static/img/usage/payroll/setup/maintain-frequency/new.png)

3. Go to **Human Resource** > **Maintain Employee**, select the employee, go to the **Payroll Info** tab, and set the Frequency according to the Maintenance Frequency.

    ![set-freq-1](../../../static/img/usage/payroll/setup/maintain-frequency/set-freq-1.png)

4. After saving, you can check the allowance the employee has. In this example, the employee Nicole has a Fixed Allowance of RM 230.

    ![set-freq-2](../../../static/img/usage/payroll/setup/maintain-frequency/set-freq-2.png)

5. Next, go to **Payroll** > **New Payroll** > **Frequency**.

    ![frequency](../../../static/img/usage/payroll/setup/maintain-frequency/frequency.png)

    1. Select the Frequency you set in Maintenance Frequency (e.g., Half).

    2. The Employee(s) set with this Frequency type in Maintain Employee will show in this column.

    3. Check the Sequence you want to process.

    4. Click **PROCESS**.

6. The following result will be shown in the **HALF MONTH FREQUENCY PAYROLL**.

    ![result-1](../../../static/img/usage/payroll/setup/maintain-frequency/result-1.png)

7. When it is time to do month end, click on **Payroll**, look for **New Payroll**, and click on **Final Month End** to process.

    ![result-2](../../../static/img/usage/payroll/setup/maintain-frequency/result-2.png)

8. Select the employee (e.g., Nicole) for whom you processed the Frequency. The following is an example result of an employee with processed Frequency.

    - Wages - [2800 (Basic) – 1400 (Frequency) = 1400 ]
    - Allowance - [ 230 (Fixed) – 115 (Frequency) = 115 ]

    ![final-result](../../../static/img/usage/payroll/setup/maintain-frequency/final-result.png)

## Maintain Contribution

:::info
Learn how to set the Employee/Employer EPF rate, OT calculation, and Tax calculation following this guide.
:::

- Setting up Maintain Contribution helps you categorize the type of contribution an employee receives.
- This affects the types of contributions required (EPF/SOCSO/PCB, etc.).
- This is especially useful if you have different types of workers such as permanent workers, contract workers, foreign workers, etc.

1. Navigate to **Payroll** > **Maintenance** > **Maintain Contribution**.

    ![navigate](../../../static/img/usage/payroll/setup/maintain-contribution/navigate.png)

2. Click **New** to create a new contribution.

    ![new](../../../static/img/usage/payroll/setup/maintain-contribution/new.png)

3. Enter the information and check the required contributions.

![key-in-1](../../../static/img/usage/payroll/setup/maintain-contribution/key-in-1.png)
![key-in-2](../../../static/img/usage/payroll/setup/maintain-contribution/key-in-2.png)

### Common contribution setup

| Local Permanent Workers                                                                               | Foreign Workers                                                                       |
| ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| ![local-permanent](../../../static/img/usage/payroll/setup/maintain-contribution/local-permanent.png) | ![foreign](../../../static/img/usage/payroll/setup/maintain-contribution/foreign.png) |

### Explanation of terms in Maintain Contribution panel

![explanation-1](../../../static/img/usage/payroll/setup/maintain-contribution/explanation-1.png)

![explanation-2](../../../static/img/usage/payroll/setup/maintain-contribution/explanation-2.png)

![explanation-3](../../../static/img/usage/payroll/setup/maintain-contribution/explanation-3.png)

## Maintain Allowance

:::info Features

- Setting up Maintain Allowance helps you categorize the type of allowance that employees are entitled to.
- This affects the types of contributions required (EPF/SOCSO/PCB, etc.).
- This is especially useful if you have different types of allowances such as Petrol, Handphone, or Meal Allowance based on different company entitlements.

:::

1. Navigate to **Payroll** > **Maintenance** > **Maintain Allowance**.

    ![navigate](../../../static/img/usage/payroll/setup/maintain-allowance/navigate.png)

2. Click **New** to create a new allowance.

    ![new](../../../static/img/usage/payroll/setup/maintain-allowance/new.png)

3. Enter the required information in Maintain Allowance.

    ![insert](../../../static/img/usage/payroll/setup/maintain-allowance/insert.png)

    1. Enter the **Code** of the Allowance you want to generate.
    2. Enter the **Description** of the allowance.
    3. Enter the fixed amount for the allowance. For example, if the Handphone allowance is a fixed RM 300 for every employee, enter RM 300. If there is no fixed amount, leave it blank.
    4. If the allowance is tax-exempt, enter the tax-exempt code.
    5. Check or uncheck the contribution for the allowance.

4. After creating the Allowance master file, you can add the fixed allowance for employees who receive it monthly.

    ![add-fixed-allowance](../../../static/img/usage/payroll/setup/maintain-allowance/add-fixed-allowance.png)

5. Alternatively, you can insert the allowance after processing the month end.

    ![process-month-end-add-allowance](../../../static/img/usage/payroll/setup/maintain-allowance/process-month-end-add-allowance.png)

    1. Click on "**Overtime**".
    2. Click the ➕ icon to add the employee, then fill in the overtime.

6. The Allowance feature works similarly to the Deduction feature; allowances are not compulsory and depend on company policy.

## Maintain Deduction

:::info Features

Maintain Deduction is used to configure employee payroll deductions, such as personal loan deductions, company advance deductions, lateness deductions, and restaurant deductions.

Deductions can be fixed amounts or percentages; once configured, they are automatically deducted from payroll.

Deductions may affect net pay, tax calculations, and the inclusion or exclusion of contributions such as EPF/SOCSO. These settings should be based on company policies and regulations.

:::

1. Navigate to **Payroll** > **Maintenance** > **Maintain Deduction**.

    ![navigate](../../../static/img/usage/payroll/setup/maintain-deduction/navigate.png)

2. Click **New** to create a new deduction.

    ![new](../../../static/img/usage/payroll/setup/maintain-deduction/new.png)

3. Enter the required information in Maintain Deduction.

    ![insert](../../../static/img/usage/payroll/setup/maintain-deduction/insert.png)

    1. Enter the **Code** of the Deduction you want to generate.
    2. Enter the **Description** of the deduction.
    3. Enter the fixed amount for the deduction. For example, if a Loan deduction is a fixed RM 100 for every employee, enter RM 100. If there is no fixed amount, leave it blank.
    4. Select the deduction type (General / Zakat / Tabung Haji / PTPTN).
    5. Check or uncheck the contribution for the deduction.

4. After creating the Deduction master file, you can add the fixed deduction for employees who have this deduction monthly.

    ![add-fixed-deduction](../../../static/img/usage/payroll/setup/maintain-deduction/add-fixed-deduction.png)

5. Alternatively, you can insert the deduction after processing the month end.

    ![process-month-end-add-deduction](../../../static/img/usage/payroll/setup/maintain-deduction/process-month-end-add-deduction.png)

    1. Click on "**Deduction**".
    2. Click the ➕ icon to add the employee, then fill in the deduction.

6. The Deduction feature works similarly to the Allowance feature; deductions are not compulsory and depend on company policy.

## Maintain Overtime

:::info Features

- Setting up Maintain Overtime helps you categorize the type of overtime offered by the company.
- This affects the types of contributions required (EPF/SOCSO/PCB, etc.).
- This setting impacts overtime calculation.

:::

### Processing Overtime After Month End

1. Click **Payroll** > **Maintenance** > **Maintain Overtime**.

    ![after-maintain-overtime](../../../static/img/usage/payroll/setup/maintain-overtime/after-maintain-overtime.png)

2. In the list, you can find some default overtime settings. Click **New** to create a custom one.

    ![after-new](../../../static/img/usage/payroll/setup/maintain-overtime/after-new.png)

3. Enter the Overtime details as follows:

    ![after-enter-details](../../../static/img/usage/payroll/setup/maintain-overtime/after-enter-details.png)

    - Enter the **Code** and **Description** of the overtime you want to generate.
    - Enter the **Rate** of the overtime (e.g., 1.5, 2.0, or 3.0 times the hourly rate).
    - **Unit Type** sets the overtime calculation to hourly or daily.
    - Set the overtime contributions (EPF, SOCSO, PCB, EIS, etc.).

4. When processing payroll at month end, navigate to **Payroll** > **New Payroll**.

    ![after-navigate-new-payroll](../../../static/img/usage/payroll/setup/maintain-overtime/after-navigate-new-payroll.png)

5. Click **Final**, then click **Process**.

    ![after-click-process](../../../static/img/usage/payroll/setup/maintain-overtime/after-click-process.png)

6. Click on any employee.

    ![after-click-employee](../../../static/img/usage/payroll/setup/maintain-overtime/after-click-employee.png)

7. Click on "**Overtime**".

    ![after-click-overtime](../../../static/img/usage/payroll/setup/maintain-overtime/after-click-overtime.png)

8. Click the ➕ icon to add the required information.

    ![after-click-plus](../../../static/img/usage/payroll/setup/maintain-overtime/after-click-plus.png)

9. Click **Code** to select the overtime type.

    ![after-select-code](../../../static/img/usage/payroll/setup/maintain-overtime/after-select-code.png)

10. Enter the work unit as overtime hours. For example, if Lee Hong Wai worked 2 hours of overtime, enter 2.

    ![after-key-overtime-hour](../../../static/img/usage/payroll/setup/maintain-overtime/after-key-overtime-hour.png)

11. Alternatively, click the button beside Trans Date and check the **Work Unit As Time** column.

    ![after-tick-column](../../../static/img/usage/payroll/setup/maintain-overtime/after-tick-column.png)

12. Once the column is visible, you may enter the overtime minutes as well (e.g., 2 hours and 09 mins).
    ![after-key-overtime-minutes](../../../static/img/usage/payroll/setup/maintain-overtime/after-key-overtime-minutes.png)

### Processing Overtime Before Month End

1. Click **Payroll** > **Open Pending Payroll**.

    ![before-open-pending](../../../static/img/usage/payroll/setup/maintain-overtime/before-open-pending.png)

2. Double-click **Overtime**.

    ![before-open](../../../static/img/usage/payroll/setup/maintain-overtime/before-open.png)

3. Click the **Append** icon.

    ![before-append-1](../../../static/img/usage/payroll/setup/maintain-overtime/before-append-1.png)

    ![before-append-2](../../../static/img/usage/payroll/setup/maintain-overtime/before-append-2.png)

4. Select the employee.

    ![before-select-employee](../../../static/img/usage/payroll/setup/maintain-overtime/before-select-employee.png)

5. Select the **Overtime Code**.

    ![before-select-code](../../../static/img/usage/payroll/setup/maintain-overtime/before-select-code.png)

6. Check to enable **Work Unit As Time**.

    ![before-enable-work-unit-as-time](../../../static/img/usage/payroll/setup/maintain-overtime/before-enable-work-unit-as-time.png)

7. Enter the time. For example, if Lee Chong Wai worked 2 hours and 30 minutes, enter it as shown below.

    ![before-enter-time](../../../static/img/usage/payroll/setup/maintain-overtime/before-enter-time.png)

8. Repeat these steps for other overtime records and save when finished.

    ![before-repeat](../../../static/img/usage/payroll/setup/maintain-overtime/before-repeat.png)

9. During month end processing:

    ![before-month-end-1](../../../static/img/usage/payroll/setup/maintain-overtime/before-month-end-1.png)

    ![before-month-end-2](../../../static/img/usage/payroll/setup/maintain-overtime/before-month-end-2.png)

10. Double-click the employee's name or code.

    ![before-click-employee](../../../static/img/usage/payroll/setup/maintain-overtime/before-click-employee.png)

11. Click the blue **Overtime** text.

    ![before-click-overtime](../../../static/img/usage/payroll/setup/maintain-overtime/before-click-overtime.png)

12. The overtime records entered in Pending Payroll will be displayed.

    ![before-overtime-records](../../../static/img/usage/payroll/setup/maintain-overtime/before-overtime-records.png)

### Importing Overtime from Excel to SQL Payroll

1. Prepare a table in Microsoft Excel as shown below:

    ![import-excel](../../../static/img/usage/payroll/setup/maintain-overtime/import-excel.png)

    :::tip

    - **Date**: Trans Date
    - **Employee**: Code of Employee
    - **OT**: Overtime Code created in Maintain Overtime
    - **Unit**: Work Unit (e.g., 2.50 = 2.5 hours)
      :::

2. After creating the table, go to **File**.

    ![import-go-to-file](../../../static/img/usage/payroll/setup/maintain-overtime/import-go-to-file.png)

3. Click **Save As**.

    ![import-save-as](../../../static/img/usage/payroll/setup/maintain-overtime/import-save-as.png)

4. Select **CSV (Comma delimited)** as the file type.

    ![import-select-csv](../../../static/img/usage/payroll/setup/maintain-overtime/import-select-csv.png)

5. Click **Save**.

    ![import-save](../../../static/img/usage/payroll/setup/maintain-overtime/import-save.png)

6. Go to **SQL Payroll** > **Payroll** > **Open Pending Payroll**.

    ![import-open-pending-payroll](../../../static/img/usage/payroll/setup/maintain-overtime/import-open-pending-payroll.png)

7. Double-click **Overtime**.

    ![import-click-overtime](../../../static/img/usage/payroll/setup/maintain-overtime/import-click-overtime.png)

8. Click the **Import Data** icon.

    ![import-click-data](../../../static/img/usage/payroll/setup/maintain-overtime/import-click-data.png)

9. Click the **...** (browse) button to select your data source.

    ![import-click-dots-button](../../../static/img/usage/payroll/setup/maintain-overtime/import-click-dots-button.png)

10. Select the CSV file to import.

    ![import-select-csv-file](../../../static/img/usage/payroll/setup/maintain-overtime/import-select-csv-file.png)

11. Click **Next**.

    ![import-next](../../../static/img/usage/payroll/setup/maintain-overtime/import-next.png)

12. Set **Import from row** to 1, select **Comma** as the separator, and select **"** as the text delimiter.

    ![import-import](../../../static/img/usage/payroll/setup/maintain-overtime/import-import.png)

13. Map the fields for every column.

    ![import-select-field-1](../../../static/img/usage/payroll/setup/maintain-overtime/import-select-field-1.png)

14. Ensure you have mapped all fields: Date, Employee, Code, and WorkUnit.

    ![import-select-field-2](../../../static/img/usage/payroll/setup/maintain-overtime/import-select-field-2.png)

15. Change **Import from row** to **2** and click **Finish**.

    ![import-finish](../../../static/img/usage/payroll/setup/maintain-overtime/import-finish.png)

16. Click **Close** after the data import is complete.

    ![import-close](../../../static/img/usage/payroll/setup/maintain-overtime/import-close.png)

17. Click the **Save** icon.

    ![import-last-save](../../../static/img/usage/payroll/setup/maintain-overtime/import-last-save.png)

## Maintain Claim

:::info Feature

- Maintain Claim is used to define the types of claims available to employees, as well as set default amounts and limits.
- For example, for travel claims, accommodation expenses, and communication expenses, you can set monthly or per-claim limits, set fixed amounts, or leave them blank for employees to fill in.
- This can impact the reimbursement process, monthly reimbursement review, and payroll calculations.

:::

1. Navigate to **Payroll** > **Maintenance** > **Maintain Claim**.

    ![navigate](../../../static/img/usage/payroll/setup/maintain-claim/navigate.png)

2. Click **New** to create a new claim.

    ![new](../../../static/img/usage/payroll/setup/maintain-claim/new.png)

3. Enter the required information in Maintain Claim.

    ![insert](../../../static/img/usage/payroll/setup/maintain-claim/insert.png)

    1. Enter the **Code** of the Claim you want to generate.
    2. Enter the **Description** of the claim.
    3. Enter the **Yearly Limit** for the claim. For example, if the limit is RM 2000 for every employee, enter RM 2000. If there is no limit, leave it blank or click **Set as Unlimited**.
    4. Enter the **Monthly Limit** for the claim. For example, if the limit is RM 200 for every employee, enter RM 200. If there is no limit, leave it blank or click **Set as Unlimited**.

4. After creating the Claim master file, you can add fixed Yearly and Monthly Limits for employees who have this claim.

    ![add-fixed-claim-limit](../../../static/img/usage/payroll/setup/maintain-claim/add-fixed-claim.png)

5. Alternatively, you can insert the claim after processing the month end.

    ![process-month-end-add-claim](../../../static/img/usage/payroll/setup/maintain-claim/process-month-end-add-claim.png)

    1. Click on "**Claim**".
    2. Click the ➕ icon to add the employee, then fill in the claim.

## Maintain Commission

1. Set the commission for the employee.

    - Navigate to **Payroll** > **Maintenance** > **Maintain Commission**.
    - Click **New** to create a new commission rate.

    ![maintain-commision](../../../static/img/usage/payroll/setup/maintain-commission/maintain-commission.png)

2. Open Pending Payroll for Commission.

    - Go to **Payroll** > **Open Pending Payroll** > **Commission**.
    - Enter the employee and amount.

    ![pending-payroll](../../../static/img/usage/payroll/setup/maintain-commission/pending-payroll.png)

3. Process Month End.

    1. Method 1: Final Payroll Process

        - Navigate to **Payroll** > **New Payroll** > **Process**.

        ![process-month-end-1](../../../static/img/usage/payroll/setup/maintain-commission/process-month-end-1.png)

    2. Method 2: Process Adhoc

        - Check EPF, PCB, and Monthly Fixed Allowance/Pending Payroll.

        ![process-month-end-2](../../../static/img/usage/payroll/setup/maintain-commission/process-month-end-2.png)

    3. Check **Commission**.

        ![tick-comm](../../../static/img/usage/payroll/setup/maintain-commission/tick-comm.png)

4. Double-click the employee who received the commission.

    ![check-employee](../../../static/img/usage/payroll/setup/maintain-commission/check-employee.png)

5. Check the Commission column.

    ![result](../../../static/img/usage/payroll/setup/maintain-commission/result.png)

## Maintain Payment Method

- Maintain Payment Method helps you categorize how you want to pay your employees.
- This is useful when you have different types of banks (MBB, HLB, etc.) and payment methods (Cash, Cheque, Transfer).
- Here, you can also set **auto rounding** so that all payouts are rounded to the nearest 5 cents.

  - e.g., Employee total pay = RM1234.**56**
  - After auto rounding, it will become RM1234.**55**

1. Navigate to the Maintain Payment Method panel.

    ![navigate](../../../static/img/usage/payroll/setup/maintain-payment-method/navigate.png)

2. Click **New** to create a new payment method.

    ![new](../../../static/img/usage/payroll/setup/maintain-payment-method/new.png)

3. Enter the required information and click **Save**.

    ![key-in-1](../../../static/img/usage/payroll/setup/maintain-payment-method/key-in-1.png)

    ![key-in-2](../../../static/img/usage/payroll/setup/maintain-payment-method/key-in-2.png)

### Explanation of Auto Rounding

#### Without Auto Rounding

![5](../../../static/img/usage/payroll/setup/maintain-payment-method/5.png)

- After month end, **no adjustment** will be shown.
- However, adjustments can be manually changed by clicking the up/down arrow beside it.

![6](../../../static/img/usage/payroll/setup/maintain-payment-method/6.png)

#### With Auto Rounding

- After month end, there will be an **auto adjustment** to the nearest 5 cents.

![7](../../../static/img/usage/payroll/setup/maintain-payment-method/7.png)
