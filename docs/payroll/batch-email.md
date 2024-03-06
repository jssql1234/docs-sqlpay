---
sidebar_position: 3
id: batch-email
title: Batch Email - Email Client Batch & SMTP Batch
description: A guide to do batch email
slug: /payroll/batch-email
tags: ["SQL Payroll", "Batch Email"]
---

:::info[note]
Make sure you had done setting the template in Maintain Employee.
:::

## Setting in Maintain Employee

You can [CLICK HERE](https://wiki.sql.com.my/wiki/Fast_Report_-_E-Mail_Client_(Batch)_%26_E-Mail_(Native)#Version_1.2021.196.166_.26_above) to go Batch Email Link

1. Click on 3.2.2 Version 1.2021.196.166 & above

    ![1](/img/payroll/batch-email/1.png)

2. Scroll down until see this Sample E-Mail Template (Version 1.2021.196.166 & above) > Click on Expand

    ![2](/img/payroll/batch-email/2.png)

3. Copy all

    ![3](/img/payroll/batch-email/3.png)

4. Open your SQL Payroll System

5. Human Resource > Maintain Employee > Click New

    ![4](/img/payroll/batch-email/4.png)

6. Click ![22](/img/payroll/batch-email/22.png) Beside More

    ![5](/img/payroll/batch-email/5.png)

7. Click on Paste Employee**

    ![6](/img/payroll/batch-email/6.png)

8. After Paste Employee you will see Employee Code as **EMAIL** and the PDF Password Setting at **Note**

    ![7](/img/payroll/batch-email/7.png)

## Setting PDF Password

- **Scenario 1 : Setting Empoyee Name 2 as password**

    :::info[note]
    *Only available in Version 1.2021.2066.174 & above
    :::

  1. At Note Tab :

     1. [UseName2] Put 1= Enable

     2. [GlobalPassword] and [PrivatePassword] make sure is empty

        ![8](/img/payroll/batch-email/8.png)

  2. Under Employee profile set the password at **Name 2**

        >For Example : ***testing*** is the PDF Password

    ![9](/img/payroll/batch-email/9.png)

  - **Scenario 2 :  Setting Global PDF Password by UseName and ICPass**

    >**_UseNameICPass** - This setting is to use Employee Name and IC set as PDF password

    1. [UseName2] set 0 = Disable, [PrivatePassword] is empty

    2. The first character of Employee Name (In Uppercase)

    3. Second character is @

    4. The subsequent 6 characters is the last 6 digits of NRIC or Passport Number

    For example :
    >Name : LEE CHONG WEI
    >
    >NRIC : 961212-01-4321
    >
    >The password is : **L@014321**

    ![10](/img/payroll/batch-email/10.png)

  - **Scenario 3 : Setting Global PDF Password**

    >**Global PDF Password** - Set **All Employees** with the same Password

    1. **[UseName2] set as 0 = Disable** and **[PrivatePassword]** is empty

    2. Under **[Global Password]** set the PDF Password

    For example as below :
    >The PDF Password is ***‘BatchEmail’***

    ![11](/img/payroll/batch-email/11.png)

  - **Scenario 4 : Setting Private/ Individual Password**

    Private Password - Each Employees got their own PDF Password

    :::info[note]
    Must set for all Employees
    :::

    1. [UseName2] set 0 = Disable , [GlobalPassword] is empty

        >Format : EmployeeCode=Password

        For Example as below :
        >001=LEE (‘LEE’ is the PDF Password)
        >
        >002=KOO (‘KOO’ is the PDF Password)

    ![12](/img/payroll/batch-email/12.png)

## Send Payslip by Batch Email

- **Method 1 : How to send payslip by Export to E-Mail Client (Batch)**

    :::info[note]
    Make sure your pc had install window email (Ex : Outlook or Thunderbird)
    :::

1. Go to Payroll> Print Pay Slip ...

    ![13](/img/payroll/batch-email/13.png)

2. Filter your process you wish to batch email > Apply

    ![14](/img/payroll/batch-email/14.png)

3. Click ![22](/img/payroll/batch-email/22.png) Beside Printer icon

4. Click on Export to E-Mail Client (Batch)

    ![15](/img/payroll/batch-email/15.png)

5. Select your payslip format > OK

    ![16](/img/payroll/batch-email/16.png)

6. After click ok will prompt window and show has been sent to recipient email, mean success send out

    ![17](/img/payroll/batch-email/17.png)

- **Method 2 : How to send payslip by Export to E-Mail SMTP (Batch)**

    :::info[note]
        Make Sure you had create App Password

        - If you’re using Gmail , you can [CLICK HERE](https://support.google.com/accounts/answer/185833?hl=en) to create your App Password
    :::

  1. Go to File

  2. Company Profile

        ![18](/img/payroll/batch-email/18.png)

  3. Select Email Setting

  4. Fill in your email detail
        >**Password : Is your App Password

        ![19](/img/payroll/batch-email/19.png)

  5. Go to Payroll

  6. Click Print Pay Slip..

        ![20](/img/payroll/batch-email/20.png)

  7. Filter your process you wish to batch email > Apply

        ![21](/img/payroll/batch-email/21.png)

  8. Click ![22](/img/payroll/batch-email/22.png) Beside Printer icon

  9. Click on Export to E-Mail SMTP (Batch)

        ![23](/img/payroll/batch-email/23.png)

  10. Select your payslip format > OK

        ![24](/img/payroll/batch-email/24.png)

  11. After click ok will prompt window and show has been sent to recipient email, mean success send out

        ![25](/img/payroll/batch-email/25.png)
