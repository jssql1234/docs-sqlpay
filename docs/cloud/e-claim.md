---
sidebar_position: 1
id: e-claim
title: E Claim
description: A guide to explain the e claim functionality
slug: /cloud/e-claim
tags: ["SQL Payroll", "Cloud", "E Claim"]
---

## Introduction

Employee can now submit a claim on SQL HRMS mobile app and then synchronize the claim application back to SQL Payroll.

:::note

Please contact your SQL service agent to register for SQL Drive before setup.

:::

## Steps & Instruction

### 1. Create Claim Code (Admin)

1. Login to SQL Payroll | **Payroll** | **Maintenance** | **Maintain Claim**

   ![1](/img/cloud/e-claim/1.png)

2. Create **New** | e.g. Petrol | **Save**

   ![2](/img/cloud/e-claim/2.png)

:::note

Optional: Yearly Limit & Monthly Limit

Set to a specific amount to limit employee total claim amount.

:::

### 2. Enable SQL Drive (Admin)

:::note

Please contact your SQL service agent to register for SQL Drive or you won't able to login successfully.

:::

1. **File** | **Company Profile**

   Go to the last tab (Cloud Icon), then turn on Drive as shown below

   ![3](/img/cloud/e-claim/3.png)

2. You will be prompted a new window (shown below) to login and Grant Access to your SQL Drive account. Just follow the instruction on screen and login with the Gmail account registered with your SQL service agent.

   ![4](/img/cloud/e-claim/4.png)

3. Once you granted access, the popup window should closed by itself. Click on **Save**.

   ![5](/img/cloud/e-claim/5.png)

### 3. Setup employee access to SQL HRMS mobile app (Admin)

1. In SQL Payroll | Maintain Employee | Employee profile | Make sure key in employee Email address.

   ![6](/img/cloud/e-claim/6.png)

2. After that, go to **Cloud** | **Sync Cloud**.

   ![7](/img/cloud/e-claim/7.png)

3. Click on **Sync Now**.

   ![8](/img/cloud/e-claim/8.png)

4. Wait the the sync status to show "**Sync completed**"

   ![9](/img/cloud/e-claim/9.png)

### 4. SQL HRMS mobile app (Employee)

1. Download the app

   1. Go to Play Store (Android), App Store (iOS), and search for **SQL HRMS** by **eStream Software** .

      ![10](/img/cloud/e-claim/10.png)

   2. Open the app, and proceed to login with the email address registered in Maintain Employee (refer to Step 3)

   3. During login process, employee will need to enter the OTP (One Time Password) sent to the registered email for verification purpose.

2. Submit Claim (Employee)

   | 1. Go to **Employee View**  | 2. Swipe Left to show Claim section  |
   |----|----|
   | ![11a](/img/cloud/e-claim/11a.png)  | ![11b](/img/cloud/e-claim/11b.png)  |
   | 3. Enter Claim Details and Upload Attachments | 4. Submit the claim |
   | ![11c](/img/cloud/e-claim/11c.png) | ![11d](/img/cloud/e-claim/11d.png) |

:::info

For more info, may refer to the video [Youtube](https://www.youtube.com/watch?v=h1nJzSHkjDQ)

:::

### 5. Sync Claim Application to SQL Payroll (Admin)

- To approve/reject claim application

- If reject, system will NOT calculate the claim amount when processing payroll

- If approve, system will calculate the claim amount when processing payroll

1. Login to SQL Payroll | **Cloud** | **Sync Cloud**

   ![12](/img/cloud/e-claim/12.png)

2. Go to **Pending Claim**, then click **Sync All**.

   ![13](/img/cloud/e-claim/13.png)

3. Once synced successfully, you will a listing of pending claim to be approved or rejected.

4. Double click on any of the claim listing to expand its attachments.

5. Click on the Attachment column to view attachments directly.

   ![14](/img/cloud/e-claim/14.png)

---

1. Reject Claim

   1. Click **Reject**

      ![15](/img/cloud/e-claim/15.png)

      :::info

      The row turning red indicates that it has been successfully **rejected**. The system will **not** include the claim amounts during payroll processing.

      :::

   2. Click Sync Now again, system will then sync the status with SQL HRMS app so employee can see the latest status.

2. Approve Claim

   1. Click Approve

      ![16](/img/cloud/e-claim/16.png)

      :::note

      The row turning blue indicates that it has been successfully **approved**.

      :::

   2. Click Sync Now again, system will then sync the status with SQL HRMS app so employee can see the latest status.

   3. Now go to **Payroll** | **New Payroll** | Click *Process*

      ![17](/img/cloud/e-claim/17.png)

   4. You will be prompted with the pending claim that will be included, click **OK** to proceed.

      ![18](/img/cloud/e-claim/18.png)

   5. Double click on the employee on left sidebar to check payroll details. Can see that claim amount is included in the month end payroll.

      ![19](/img/cloud/e-claim/19.png)

   6. Done

## FAQ

**What if the claim amount exceeded monthly/yearly limit and you still want to approve it?**

System do not force you to reject the claim, however you will be given two reminder if you chose to proceed and approve the claim (shown below).

1. Example: **Petrol Claim**

   Monthly limit: **RM250**

   Employee Claim Amount: **RM200**

   ![20](/img/cloud/e-claim/20.png)

   :::note

   You can reject the claim at this window if you do not wish to proceed.

   :::

2. Click approve, system will calculate the extra amount which exceeded limit. (**First reminder**)

   ![21](/img/cloud/e-claim/21.png)

3. Click Sync Now.

4. Go to **Payroll** | *New Payroll* | Click *Process* | Click *OK*

   ![22](/img/cloud/e-claim/22.png)

5. System will prompt a new window "Claims Exceed Limit" (**Second reminder**)

   ![23](/img/cloud/e-claim/23.png)

6. Click OK to approve and proceed with the claim.

   ![24](/img/cloud/e-claim/24.png)

If you do not wish to reject the claim, untick it and Click **OK**

   ![25](/img/cloud/e-claim/25.png)
