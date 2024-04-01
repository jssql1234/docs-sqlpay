---
title: E Leave
description: A brief guide on the E Leave feature
slug: /hrms/e-leave
tags: ["SQL Payroll", "Cloud", "E Leave", "Sync", "Multi Level Approval"]
---

## Introduction

E Leave is a feature in SQL HRMS which greatly simplifies the process of managing employees leave applications

:::info
E Leave is utilizing email as the channel for notifying managers/employees. In order to make it work, there are some simple setup need to be done. If you have a **custom company email address**, you can create additional user for E Leave and configure following the steps below. Whereby for users who doesn't have a custom company email address, you can utilize **Google Email (Gmail)** or **Microsoft Outlook** in the setup, they are free. 🤩
:::

## Generate App Password

:::note
Skip to [**Setup**](#setup) if you are using custom company email address. This guide is applicable to **Google Email (Gmail)** and **Microsoft Outlook** only.
:::

### Google Email (Gmail)

1. Visit [Google account](https://accounts.google.com/) and login into your gmail

2. From the sidebar, click on **Security** tab

   ![google-security](../../../static/img/integration/hrms/e-leave/google-security.png)

3. Turn on **2-Step Verification** (Skip this step if you have turned it on)

   1. Click on **2-Step verification**

      ![2fa](../../../static/img/integration/hrms/e-leave/2fa.png)

   2. Press on **GET STARTED**

      ![2fa-get-started](../../../static/img/integration/hrms/e-leave/2fa-get-started.png)

   3. Enter your **Gmail Password**

   4. Press **Continue**

   5. Press **Sent**

   6. Enter **Gmail code**

4. After enabling **2-Step Verification**, we will be able to generate the **App Password**

   :::warning
   If you don't see this option, it might be due to the following issues:

   - 2-Step Verification is not set up for your account
   - 2-Step Verification is only set up for security keys
   - Your account is through work, school, or other organization
   - You turned on Advanced Protection

   :::

5. Click on **App Passwords** section

6. Enter your gmail password to continue

7. Next, Select **Mail** as the app and **Windows Computer** as the device. Click **Generate** to create an app password

   ![generate-google-app-password](../../../static/img/integration/hrms/e-leave/generate-google-app-password.png)

8. Copy and note down the **App password**, you will need to fill it in the _password_ field following the [Setup](#setup) guide

   ![google-app-password](../../../static/img/integration/hrms/e-leave/google-app-password.png)

### Microsoft Outlook

1. Visit [Microsoft account](https://account.live.com/proofs/Manage?mkt=en-us) and login into your email

2. Navigate to **Security** tab, and enable **Two-step verification**

   ![microsoft-2fa](../../../static/img/integration/hrms/e-leave/microsoft-2fa.png)

3. Next, find the **App passwords** section, and click "**Create a new app password**"

   ![microsoft-create-app-password](../../../static/img/integration/hrms/e-leave/microsoft-create-app-password.png)

4. Copy and note down the **App password**, you will need to fill it in the _password_ field following the [Setup](#setup) guide

   ![microsoft-app-password](../../../static/img/integration/hrms/e-leave/microsoft-app-password.png)

## Setup

1. In SQL Payroll, go to **File** > **Company Profile**

2. Under the **General** tab, enter the company email (this will be the recipient email in the E Leave notification)

   ![enter-company-email](../../../static/img/integration/hrms/e-leave/enter-company-email.png)

3. Next, navigate to the **Email Settings** tab, fill in the details

4. Click **Send Test Email** to test the functionaliy of the config and save

   | Fields      | Description                                                                 | Google Email (Gmail) | Microsoft Outlook    | Custom               |
   | ----------- | --------------------------------------------------------------------------- | -------------------- | -------------------- | -------------------- |
   | SMTP Host   | Email SMTP Host                                                             | `smtp.gmail.com`     | `smtp.office365.com` | user defined host    |
   | Port        | Email SMTP Port                                                             | 587                  | 587                  | user defined port    |
   | User        | User email which used in generating the app password OR custom user created | gmail                | microsoft email      | custom user          |
   | Password    | The 16-character app password OR custom user password                       | -                    | -                    | custom user password |
   | Sender Name | Name of the email sender for notification                                   | -                    | -                    | -                    |

   ![smtp-setup](../../../static/img/integration/hrms/e-leave/smtp-setup.png)

   :::tip
   Upon successful, the email address configured in the **User** field should receive an email
   :::

   ![successful-smtp-setup](../../../static/img/integration/hrms/e-leave/successful-smtp-setup.png)

5. To preserve the settings, navigate to **Cloud ☁️** Icon on the menu bar > **Sync Cloud...**

   ![sync-cloud](../../../static/img/integration/hrms/e-leave/sync-cloud.png)

6. Under the tabview, select the **Leave App** tab and click on the **Sync Now** button

   ![sync-now](../../../static/img/integration/hrms/e-leave/sync-now.png)

   :::info
   Repeat step 5 and 6 for every changes to the configuration, this is to ensure configuration are synchronized to cloud
   :::

## Sync EA or Payslip to E Leave

1. Navigate to **Cloud ☁️** Icon > **Sync Cloud**

   ![ea-sync-cloud](../../../static/img/integration/hrms/e-leave/ea-sync-cloud.png)

2. From the tabbed view, select **Payroll**
3. Tick **Include Employee Payroll Info**
4. Tick **Upload Payslip** and specify the **year and month** of payslip
5. Choose the **report format** for _Payslip_
6. Tick **Include EA Form Info**
7. Tick **Upload EA Form** and specify the **year**
8. Choose the **report format** for _EA Form_
9. Lastly, click on the **Sync Now** button

   ![sync-ea](../../../static/img/integration/hrms/e-leave/sync-ea.png)

10. Wait until the status bar (located at the bottom) show as **Sync completed**.

    ![sync-complete](../../../static/img/integration/hrms/e-leave/sync-complete.png)

11. That's all! You can now login into **SQL HRMS** to see the documents

    ![employee-view](../../../static/img/integration/hrms/e-leave/employee-view.png)

### View Payslip from SQL HRMS

1. First, go to **Employee View**

2. Click **View Payslip**, you will be able to view your payslip info for the month

   ![view-payslip](../../../static/img/integration/hrms/e-leave/view-payslip.png)

### Download Payslip from SQL HRMS

1. We do provides ability to download the payslip. In the **Employee View**, click on the **Monthly Payroll**

   ![download-payslip](../../../static/img/integration/hrms/e-leave/download-payslip.png)

2. Select the month that you wish

   ![download-payslip-select-month](../../../static/img/integration/hrms/e-leave/download-payslip-select-month.png)

3. There will be a payslip icon on the top right, click on it

   ![download-payslip-download](../../../static/img/integration/hrms/e-leave/download-payslip-download.png)

### Download EA Form from SQL HRMS

1. Besides payslip, employee can download EA Form directly from the app too. In the **Employee View**, clic on the **EA Form**

   ![download-eaform](../../../static/img/integration/hrms/e-leave/download-eaform.png)

2. Select the year of EA Form you wish to download

   ![download-eaform-select-year](../../../static/img/integration/hrms/e-leave/download-eaform-select-year.png)

3. Click on **Download** icon on the top right, this will initialize a download to your phone 🥳

   ![download-eaform-download](../../../static/img/integration/hrms/e-leave/download-eaform-download.png)

## Multi Level Approval

:::info
This feature allows multiple managers in managing the leave application of your employees (e.g. a leave application will require more than 1 manager to approve)
:::

### Feature Setup

1. In SQL Payroll, go to **File** > **Company Profile** > **E Leave**

2. In the tabbed view, navigate to **E HRMS**, tick **Multi-Level Approval**

   ![enable-multilevel-approval](../../../static/img/integration/hrms/e-leave/enable-multilevel-approval.png)

3. Next, go to **Maintain Employee**, assign the **manager role** to the employee. This employee will act as a manager for the leave application

   ![assign-manager](../../../static/img/integration/hrms/e-leave/assign-manager.png)

4. The table below illustrates the action one manager can do given different privileges:

   ![privilege-table](../../../static/img/integration/hrms/e-leave/privilege-table.png)

### Example of SQL HRMS behaviors

The table below show some example of screens given different privileges & circumstances (observe the button options **circled**):

| Can Review only                                        | Can Approve only                                                              | Review + Approve                                                                         |
| ------------------------------------------------------ | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| only allow to **Verify** ([Example](#can-review-only)) | If **not yet verified**, unable to approve ([Example](#can-approve-directly)) | Allow to **approve directly** (without review)([Example](#verified-can-approve--reject)) |
| -                                                      | Once **verified**, can approve / reject ([Example](#can-approve-directly))    | Allow to **undo approve** leave application ([Example](#unapproved))                     |
| -                                                      | -                                                                             | Allow to **undo rejected** leave application ([Example](#unrejected))                    |

### Leave Status in SQL Payroll

In the **Sync Cloud** window, there total of **4 types of status**:

- `Request`: **pending for verification**
- `Pending`: verified, **pending review by Manager**
- `Approved`: approved leave applications
- `Rejected`: rejeted leave applications

![e-leave-status](../../../static/img/integration/hrms/e-leave/e-leave-status.png)

## Appendix

### Can Review only

![apdx-can-review-only](../../../static/img/integration/hrms/e-leave/apdx-can-review-only.png)

### Can Approve directly

![apdx-can-approve-directly](../../../static/img/integration/hrms/e-leave/apdx-can-approve-directly.png)

### Verified, can Approve / Reject

![apdx-verified-approve-reject](../../../static/img/integration/hrms/e-leave/apdx-verified-approve-reject.png)

### Unapproved

![apdx-unapproved](../../../static/img/integration/hrms/e-leave/apdx-unapproved.png)

### Unrejected

![apdx-unrejected](../../../static/img/integration/hrms/e-leave/apdx-unrejected.png)

### Permission Table

![apdx-permission-table](../../../static/img/integration/hrms/e-leave/apdx-permission-table.png)

### The flow of Can Review only permission

![apdx-can-review-flow](../../../static/img/integration/hrms/e-leave/apdx-can-review-flow.png)

### The flow of Can Approve only permission

![apdx-can-approve-flow](../../../static/img/integration/hrms/e-leave/apdx-can-approve-flow.png)

### The flow of Review + Approve

![apdx-review-approve-flow](../../../static/img/integration/hrms/e-leave/apdx-review-approve-flow.png)
