---
sidebar_position: 2
id: e-claim-user-guide
title: E Leave & E Claim Setup User Guide
description: A guide to setup E Leave and E Claim
slug: /cloud/e-leave-&-e-claim-setup-user-guide
tags: ["SQL Payroll", "Cloud", "E Claim", "E Claim", "User Guide"]
---

## 1. Get Started

### 1.1 E Leave Setup

Purpose: Allow user to receive email notification when using SQL ELeaveBefore entering the SMTP settings, you might need to create an app password using company email address. This app password will be used for authentication when sending email using external program. If user do not have a company address, user can choose to get the app password using a Gmail or a Microsoft account. The tutorial of getting an app password using
Google/Microsoft SMTP server in under **Appendix 1**.

1. Open SQL Payroll

2. **File** | **Company Profile**

3. Under ‘**General**’ tab, enter the email user used to generate app password
   ![1](/img/cloud/user-guide/1.png)

4. Under ‘**Email Settings**’ tab, fill in the details and press the ‘**Send Test Email**’ at right bottom

   **Field Description:**

   **Host** :

   For Gmail user : smtp.gmail.com

   For Microsoft account user : smtp.office365.com

   **Port No** : 587

   **User** : Email used to generate the app password

   **Password** : The 16-character password generated in the email setup

   **Sender Name** : Name of the sender

      ![2](/img/cloud/user-guide/2.png)

   :::note

   Upon successful, an email will be received under the email address used to generate the app password

   :::

5. (Sync to Cloud)**: **Cloud** Icon on the menu bar | ‘**Sync Cloud...**’ | Open ‘**Leave App**’ tab | click on ‘**Sync Now**’ button

   ![3a](/img/cloud/user-guide/3a.png)

   ![3b](/img/cloud/user-guide/3b.png)

   :::note

   Note: User need to sync to cloud EVERYTIME after any changes changes made.

   :::

### 1.2 E Claim Share Setup

Purpose: To allow user to view the attached images or documents attached with the claim submission when using SQL E Leave mobile application

1. Open Payroll

2. **File** | **Company Profile**

3. Go to ‘**General**’ tab and click on the ‘**+**’ button

   ![4](/img/cloud/user-guide/4.png)

4. (Sync to Cloud)**: **Cloud** Icon on the menu bar | ‘**Sync Cloud...**’ | Open ‘**PendingClaim**’ tab | click on ‘**Sync Now**’ button

   ![5a](/img/cloud/user-guide/3a.png)

   ![5b](/img/cloud/user-guide/5.png)

   :::note

   User need to sync to cloud EVERYTIME after any changes changes made.

   :::

5. Login with user’s Gmail address

6. Open a web browser and go to [here](https://drive.sql.com.my)

7. Login with your Gmail address and user can view all the attached images and documents

## 2. Login Page

1. Enter user company email address

   ![6](/img/cloud/user-guide/6.png)

2. Wait to receive an email that include an One-Time Password (OTP)

   ![7](/img/cloud/user-guide/7.png)

3. Enter the OTP

   ![8](/img/cloud/user-guide/8.png)

4. Ready to use the application after verification

## 3. Main Page

The Main Page display the company that the employee is enrolled in.

![9](/img/cloud/user-guide/9.png)

### 3.1 Header Section

![10](/img/cloud/user-guide/10.png)

### 3.2 Content Section

1. This button allows user to view selected company details

2. This button directs user to the employee dashboard which will be discussed under section 3.0

3. This button allows user to view the list of manager in the company

## 4. Employee Dashboard (Leave Info)

![11](/img/cloud/user-guide/11.png)

![12](/img/cloud/user-guide/12.png)

### 4.1 Back Button

This button allows you to back to the Main Page

### 4.2 View Profile

1. User can view their profile in the company payroll system based on the groupings in

   - [General, Grouping, Family, Payroll Info]

   - Note: User are **not allowed** to **edit** or **modify** the details from the mobile application

   ![13](/img/cloud/user-guide/13.png)

### 4.3 Leave Info

User can view the summary of his leave from the employee dashboard and he can view the details of his leave upon clicking on the leave info dashboard.

- User can view the approved, rejected and pending leave details from this page

![14](/img/cloud/user-guide/14.png)

- Filter button (**Section 1**) : This menu allows user to filter the leave details

![15](/img/cloud/user-guide/15.png)

- Sort button (**Section 1**) : This menu allows user to sort the leave details

![16](/img/cloud/user-guide/16.png)

### 4.4 Take Leave

This button allows user to create a new leave application after filling in the details and submit the application by clicking the ‘SUBMIT’ button

- User can choose set the date time, leave type and add on description when applying the leave

![17](/img/cloud/user-guide/17.png)

### 4.5 Leave Balance

This button allows user to view his leave balance details by year and filter menu on right top allows user to filter the details based on date and department

![18](/img/cloud/user-guide/18.png)

### 4.6 Leave details

Users are allowed to view the past and upcoming leaves applied

### 4.7 Payroll Info

Users can view the latest processed payroll info

### 4.8 Monthly Payroll

Users are allowed to view the net amount of salary obtained for each month

### 4.9 EA Form

Users are allowed to view his EA Form

## 5. Employee Dashboard (Claim Info)

![19](/img/cloud/user-guide/19.png)

### 5.1 Claim Info

User can view all the approved, pending and rejected claim when clicked on the claim info dashboard

![20](/img/cloud/user-guide/20.png)

- Filter button (**Section 1**) : User can filter the leave details by date, expenses type and the claim status

![21](/img/cloud/user-guide/21.png)

- Sort button (**Section 1**) : User are allowed to sort the leave details

![22](/img/cloud/user-guide/22.png)

### 5.2 Submit Claim

User are allowed to create a new claim submission by clicking the ‘**Submit claim**’ button

- User are allowed to upload images and attach it to the claim submission as reference

![23](/img/cloud/user-guide/23.png)

:::note

Users are required to setup E Claim Share in SQL Payroll in order to allow their employee to upload images/documents

:::

### 5.3 Expenses

User can view the details of expenses used by month and by year

![24](/img/cloud/user-guide/24.png)

### 5.4 Claim Application

User can view the summary and total amount of the claim in the form of pie chart

### Appendix 1

**Gmail Setup:**

1. Login into Google account

2. Turn on two- step verification

   ![25](/img/cloud/user-guide/25.png)

3. Setup ‘App passwords’

   ![26](/img/cloud/user-guide/26.png)

4. Choose ‘**Select App**’ to choose the app user are using and ‘**Select device**’ to choose the device you are using and click the ‘**Generate**’ button on right bottom

   ![27](/img/cloud/user-guide/27.png)

5. A 16-character password will be generated and follow the instructions under the ‘**How to use it**’ section in the image below

   ![28](/img/cloud/user-guide/28.png)

**Microsoft Account Setup:**

1. Login to user Microsoft account

2. Direct to ‘**Security**’ tab and turn on the ‘**Two-step verification**’

   ![29](/img/cloud/user-guide/29.png)

3. A 16-character password is generated
