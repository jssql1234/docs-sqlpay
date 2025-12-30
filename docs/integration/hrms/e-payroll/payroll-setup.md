---
sidebar_position: 1
title: Payroll Setup
description: An E Payroll setup guide in SQL Payroll
---

## Maintain Announcement

1. Navigate to Human Resource > Maintain Announcement…, press "Create New"
2. Enter the Title and Remark (Remark is optional and visible in maintenance view only)
3. Select a Category and Date for the duration the Announcement will be visible to the employees
    ![maintain-announcement1](../../../../static/img/integration/hrms/e-payroll/maintain-announcement1.png)

4. Go to Edit Note, enter text on the note, close the form and save the changes
    ![maintain-announcement2](../../../../static/img/integration/hrms/e-payroll/maintain-announcement2.png)
5. Add Attachments

    - Maximum of 2 attachments are allowed
    - Attachment extensions that are allowed: .jpg, .jpeg, .png, .pdf

6. Save

## Sync Cloud

### SQL Payroll

1. In SQL Payroll, navigate to ☁️ > Sync Cloud… > Payroll.

  ![sync-cloud](../../../../static/img/integration/hrms/e-payroll/sync-cloud.png)

    - To sync payroll details and payslip

      - Check **_'Include Employee Payroll Info'_**
      - Select Year and Month
      - Check **_'Upload Payslip'_**
      - Select Report format

          | **Year** | **Month** | **Upload Payslip** | **Explanation**                                                                                                      |
          | :------- | :-------- | :----------------- | :------------------------------------------------------------------------------------------------------------------- |
          | 2025     | 2         | Checked            | **Payroll Details:** All details up till Feb 2025 will synced <br/> **Payslip:** Payslip for Feb 2025 will be synced |
          | 2025     | 2         | Unchecked          | **Payroll Details:** All details up till Feb 2025 will synced <br/> **Payslip:** No payslip will be synced           |

    - To Sync EA form (The Year and Month selected next to Payroll Info is for **Payroll Details** and **Payslip** only (it's not applicable to EA Form))
      - Check **_'Include EA Form Info'_**
      - Check **_'Upload Payslip'_**
      - Select Year and Report format

2. Click **_'Sync All'_**

:::warning
A warning message will be prompt when user wants to sync **Payslip** earlier than their last synced date

![sync-payslip](../../../../static/img/integration/hrms/e-payroll/sync-payslip.png)

Proceeding will cause **newer Payslip** to be deleted and user will have to resync each month individually again
:::

### Announcement

1. Navigate to ☁️ > Sync Cloud… > Sync All

:::info
Make sure to always **_'Sync Cloud'_** when new Announcement is added or if there are any changes to the existing Announcement to ensure both Payroll and SQL HRMS app are in sync with one another
:::
