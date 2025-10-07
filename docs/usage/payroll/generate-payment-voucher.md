---
title: Generate Payment Voucher / Journal Entry
description: A guide to generate payment voucher / journal entry
slug: /usage/payroll/generate-payment-voucher
tags: ["SQL Payroll", "Payroll", "Payment Voucher", "Journal Entry"]
---

## Introduction

:::success[note]
This is **Additional Module** (Payroll Accounting (SQL Payroll))
:::

1. To generate the monthly payroll data converted into double entry and get post into SQL Account.

2. It is available in **SQL Payroll version 129** and above.

3. It is available to import payroll data in **SQL Account version 745** and above.

![1](../../../static/img/usage/payroll/generate-payment-voucher/export_import_as_PV_JE.jpg)

## Overview of the Process Flow

![2](../../../static/img/usage/payroll/generate-payment-voucher/overview_process_flow.jpg)

## Configure Payroll Accounting (1 time setup)

Go to **Menu : Payroll | Generate Payment Voucher / Journal Entry...**

1. At Generate Payment Voucher / Journal Entry, click on **Configure Payroll Accounting.**

![3](../../../static/img/usage/payroll/generate-payment-voucher/insert_process_and_date.jpg)

2. Overview of the Configure Payroll Accounting settings screen.

![4](../../../static/img/usage/payroll/generate-payment-voucher/configure_payroll_accounting.jpg)

### Step 1: Save GL Account to File (SQL Account)

1. Login the SQL Account database.

2. Go to **File | Import | (SQL Payroll) Import Payment Voucher / Journal Entry | Save GL Account File**

![5](../../../static/img/usage/payroll/generate-payment-voucher/navigate_import_payment_voucher.png)

![6](../../../static/img/usage/payroll/generate-payment-voucher/save_gl_account_to_file.png)

3. Save SQL Account file to Desktop.

![7](../../../static/img/usage/payroll/generate-payment-voucher/save_gl_to_file.jpg)

### Step 2: SQL Account GL Code

1. Click on **Load From File**.

![8](../../../static/img/usage/payroll/generate-payment-voucher/load_from_sql_account.jpg)

2. Select a **SQL Account file (*.txt)** and click **Open**.

![9](../../../static/img/usage/payroll/generate-payment-voucher/load_sql_account_file.jpg)

3. After the SQL Account GL Code has loaded, the company name will be display and last saved date and time.

![10](../../../static/img/usage/payroll/generate-payment-voucher/display_company_name_and_last_saved_date_and_time.jpg)

4. Click Remove File button if you wish to load the new chart of account.

### Step 3: GL Account Mapping

1. After load the chart of accounts (in step 2), you are able to lookup and **map the GL Account code** to wages, allowance, overtime, bonus, etc accordingly.

![11](../../../static/img/usage/payroll/generate-payment-voucher/gl_account_mapping.jpg)

2. Example of the account mapping:

![12](../../../static/img/usage/payroll/generate-payment-voucher/account_mapping_table.png)

### Step 4: Posting Method

1. Generate posting entry by **Payment Voucher** or by **Journal Entry**.

2. Group by **Employee** (available in payment voucher), **Branch, Department, HR group, or Category**.

3. Tick to **With Project Code** to post the entry with project code.

4. OPTIONAL: Generate Journal Entry for Employer EPF, SOCSO Accrual **(by default is untick)**. For some company might charge the Employer EPF and SOCSO accrual in next month.

![13](../../../static/img/usage/payroll/generate-payment-voucher/posting_method.jpg)

## Generate Payment Voucher / Journal Entry

To generate the Payment Voucher or Journal Entry from SQL Payroll. Click on **Generate**.

![14](../../../static/img/usage/payroll/generate-payment-voucher/generate_PV_JE.jpg)

## Import Payment Voucher / Journal Entry

1. Login the SQL Account database.

2. Go to **File | Import | (SQL Payroll) Import Payment Voucher / Journal Entry...**

3. Click on **Select File** from the Payment Voucher/Journal Entry (payroll data) generate from SQL Payroll.

![15](../../../static/img/usage/payroll/generate-payment-voucher/import_PV_JE.jpg)

4. Click on **Execute**.

![16](../../../static/img/usage/payroll/generate-payment-voucher/import_PV_JE_successful.jpg)