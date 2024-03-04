---
sidebar_position: 3
id: batch-email
title: Batch Email - Email Client Batch & SMTP Batch
description: A guide to do batch email
slug: /batch-email
tags: ["SQL Payroll", "Batch", "Email"]
---

# Batch Email - Email Client Batch & SMTP Batch
## How to Batch Email Payslip?

:::info[note]
Make sure you had done setting the template in Maintain Employee.
:::

### <ins>How to Setting in Maintain Employee</ins>

You can <a href="https://wiki.sql.com.my/wiki/Fast_Report_-_E-Mail_Client_(Batch)_%26_E-Mail_(Native)#Version_1.2021.196.166_.26_above" target="blank">CLICK HERE</a> to go Batch Email Link

**Step 1 : Click on 3.2.2 Version 1.2021.196.166 & above**

![1](/img/payroll/batch-email/1.png)

**Step 2 : Scroll down until see this Sample E-Mail Template (Version 1.2021.196.166 & above) > Click on Expand**

![2](/img/payroll/batch-email/2.png)

**Step 3 : Copy all**

![3](/img/payroll/batch-email/3.png)

**Step 4 : Open your SQL Payroll System** 

**Step 5: Human Resource > Maintain Employee > Click New**

![4](/img/payroll/batch-email/4.png)

**Step 6 : Click ![22](/img/payroll/batch-email/22.png) Beside More**

![5](/img/payroll/batch-email/5.png)

**Step 7 : Click on Paste Employee**

![6](/img/payroll/batch-email/6.png)

After Paste Employee you will see Employee Code as **EMAIL** and the PDF Password Setting at **Note**

![7](/img/payroll/batch-email/7.png)

### <ins>How to setting PDF Password</ins>

**<ins>Scenario 1 : Setting Empoyee Name 2 as password</ins>**  
*Available in Version 1.2021.2066.174 & above

Step 1 : At Note Tab :   
- [UseName2] Put 1= Enable  
- [GlobalPassword] and [PrivatePassword] make sure is empty

![8](/img/payroll/batch-email/8.png)

Step 2 : Under Employee profile set the password at **Name 2**  
For Example : ***testing*** is the PDF Password

![9](/img/payroll/batch-email/9.png)

**<ins>Scenario 2 :  Setting Global PDF Password by UseName and ICPass</ins>**

**_UseNameICPass** - This setting is to use Employee Name and IC set as PDF password

1. [UseName2] set 0 = Disable, [PrivatePassword] is empty
2. The first character of Employee Name (In Uppercase)
3. Second character is @
4. The subsequent 6 characters is the last 6 digits of NRIC or Passport Number

For example :  
&emsp;Name : LEE CHONG WEI  
&emsp;NRIC : 961212-01-4321

**The password is : L@014321**

![10](/img/payroll/batch-email/10.png)

**<ins>Scenario 3 : Setting Global PDF Password</ins>**

**Global PDF Password** - Set **All Employees** with the same Password 

1. **[UseName2] set as 0 = Disable** and **[PrivatePassword]** is empty
2. Under **[Global Password]** set the PDF Password 

For example as below : The PDF Password is ***‘BatchEmail’***

![11](/img/payroll/batch-email/11.png)

**<ins>Scenario 4 : Setting Private/ Individual Password</ins>**

Private Password - Each Employees got their own PDF Password 

:::info[note]
Must set for all Employees
:::

1. [UseName2] set 0 = Disable , [GlobalPassword] is empty  
    Format : EmployeeCode=Password

    For Example as below :  
    &emsp;001=LEE (‘LEE’ is the PDF Password)  
    &emsp;002=KOO (‘KOO’ is the PDF Password)

    ![12](/img/payroll/batch-email/12.png)

### <ins>How to send Payslip by Batch Email</ins>

**<ins>Method 1 : How to send payslip by Export to E-Mail Client (Batch)</ins>**

:::info[note]
Make sure your pc had install window email (Ex : Outlook or Thunderbird)
:::

Step 1 : Go to Payroll> Print Pay Slip ... 

![13](/img/payroll/batch-email/13.png)

Step 2 : Filter your process you wish to batch email > Apply

![14](/img/payroll/batch-email/14.png)

Step 3 : Click ![22](/img/payroll/batch-email/22.png) Beside Printer icon 

Step 4 : Click on Export to E-Mail Client (Batch)

![15](/img/payroll/batch-email/15.png)

Step 5 : Select your payslip format > OK

![16](/img/payroll/batch-email/16.png)

After click ok will prompt window and show has been sent to recipient email, mean success send out

![17](/img/payroll/batch-email/17.png)

**<ins>Method 2 : How to send payslip by Export to E-Mail SMTP (Batch)</ins>**

:::info[note]
 Make Sure you had create App Password
- If you’re using Gmail , you can <a href="https://support.google.com/accounts/answer/185833?hl=en" target="blank">CLICK HERE</a> to create your App Password
:::

Step 1 : Go to File

Step 2 : Company Profile

![18](/img/payroll/batch-email/18.png)

Step 3 : Select Email Setting

Step 4 : Fill in your email detail  
**Password : Is your App Password

![19](/img/payroll/batch-email/19.png)

Step 5 : Payroll > Print Pay Slip..

![20](/img/payroll/batch-email/20.png)

Step 7 : Filter your process you wish to batch email > Apply

![21](/img/payroll/batch-email/21.png)

Step 8 : Click ![22](/img/payroll/batch-email/22.png) Beside Printer icon

Step 9 : Click on Export to E-Mail SMTP (Batch)

![23](/img/payroll/batch-email/23.png)

Step 10 : Select your payslip format > OK

![24](/img/payroll/batch-email/24.png)

After click ok will prompt window and show has been sent to recipient email, mean success send out

![25](/img/payroll/batch-email/25.png)