---
sidebar_position: 1
id: online-mobile-approval
title: Online Mobile Approval
description: A guide to carry out online mobile approval
slug: /online-mobile-approval
tags: ["SQL Payroll", "Online Mobile Approval"]
---

# Online Mobile Approval

**<ins>How to Start Mobile Approval</ins>**

**Step 1 : Tools > Maintain User**

![1](/img/payroll/online-mobile-approval/1.png)

**Step 2 : Double click the user that can setting for Approval > Edit**

![2](/img/payroll/online-mobile-approval/2.png)  
![3](/img/payroll/online-mobile-approval/3.png)

**Step 3 : Setting The Detail For Approval Person (ONLY GMAIL CAN LOGIN TO APPROVE OR REJECT)**

1. Mobile number - To which whatsapp number to get notification for approval only  
2. Email - To which email address to get notification for approval only  
3. Open ID (Google) - Gmail for approve or reject  

:::info[note]
If received notification email and approve email is GMail, just setting at 3. OPEN ID (Google), 2.Email
column blank
:::

![4](/img/payroll/online-mobile-approval/4.png)

For Example :  
**<ins>Senario 1 : Use Same Gmail to Received Notification and Give Approval</ins>**

Your Gmail address is : XXXXXX@gmail.com

1. Open ID (Google) : XXXXXX@gmail.com
2. Email : Left as blank

   ![5](/img/payroll/online-mobile-approval/5.png)

**<ins>Senario 2 : Use Different email to received notification and give approval</ins>**

To Give Approval Gmail Address is : XXXXXX@gmail.com  
To Received notification Address is : XXXXXX@estream.com

1. Open ID (Google) : Put your gmail address XXXXXX@gmail.com
2. Email : XXXXXX@estream.com

   ![6](/img/payroll/online-mobile-approval/6.png)

**Step 4 : Setting SMTP** 
:::info[note]
- This Setting is for user who want to **use Email to send Notification**
- If use whatsapp to send approval can skip this step
:::

Make Sure you had create App Password  
- If you’re using Gmail , you can <a href='https://support.google.com/accounts/answer/185833?hl=en' target='blank'>CLICK HERE</a> follow the step to create your App Password
- After get App Password you can go back to your SQL Payroll

![7](/img/payroll/online-mobile-approval/7.png)

1. Click on Email Setting
2. Your Email SMTP Host
3. Your Email SMTP Port
4. Your Email SMTP Connection Security
5. Your Email Address
6. Your Apps Password
7. Your Email Sender Name
8. Afte done setting click Save

**<ins>How it works?</ins>** 

For example : If we set Maintain Acceptable Transaction Date date from 01/03/2023  
Step 1 : Process Year 2023 February month end  
Step 2 : when click process > will prompt dialog box to override > click ***Online Approval***

![8](/img/payroll/online-mobile-approval/8.png)

Step 1 : Tick the ID that you choose to get approval  
Step 2 : You can choose to send by Whatsapp , Send by Email or Send by Whatsapp & Email

![9](/img/payroll/online-mobile-approval/9.png) 

Step 3 : You will received a message at whatsapp or email send by system

**<ins>Senario 1 : Send By Whatsapp</ins>**

You will received a message > Click that link  
![10](/img/payroll/online-mobile-approval/10.png) 

**<ins>Senario 2 : Send By Email</ins>**

You will received an email > Click ***‘CLICK HERE FOR MORE ACTIONS’***  
![11](/img/payroll/online-mobile-approval/11.png) 

Step 4 : Login **Gmail Address** that you setting in maintain user **Open ID (Google)**

:::info[note]
- This Step is for those send by **whatsapp** and **not use Gmail** to received notification
- Those use **Gmail Address** to received notification and approve can jump to **Step 6** 
:::

![12](/img/payroll/online-mobile-approval/12.png) 

Step 5 : Enter your **Gmail Password** 

![13](/img/payroll/online-mobile-approval/13.png)

Step 6 : After Login **Gmail** you will see this window

![14](/img/payroll/online-mobile-approval/14.png)

Step 7 : You can click on ***Doc Detail*** and ***ScreenShot*** to see the detail

1. Doc Detail : To show User Name
2. ScreenShot : To see the process screen
3. Reply : You can left a message and click Approve or Reject

![15](/img/payroll/online-mobile-approval/15.png)

:::info[note]
After Approve or Reject you can go back SQL Payroll, you will see below screen
:::

**<ins>Scenario 1 : Approve Override</ins>** 

A. Message : Approve Message  
B. If approve you will see the green tick  
C. You can click OK system will auto save that transaction

![16](/img/payroll/online-mobile-approval/16.png)

**<ins>Senario 2 : Reject Override</ins>** 

A. Message : Reject Message   
B. If Reject you will see the crossed  
C. If Reject you cant Click OK only can Click Cancel

![17](/img/payroll/online-mobile-approval/17.png)

After Click Cancel System will Prompt back to this dialog box

![18](/img/payroll/online-mobile-approval/18.png)

**<ins>These ALL can use Online Approval for user which :</ins>**

|Module|Access Right|
|------|------------|
|Logon Screen|<ul><li>No access right to change password</li></ul>|
|ALL module|<ul><li>ALL Module with execute but have no access right for pront / preview or export</li></ul><ul><li>Unable to Grid Export</li></ul>|
|Payroll|<ul><li>Process/ Delete Month End Outside Acceptable Transaction Date</li><li>Have right for Open Pending Payroll but without access right for execute or process right for pending Allowance, Overtime etc</li><li>Payroll Report -Payroll &#124; print report &#124; have execute right without process report</li></ul>|
|View|<ul><li>Not allowed to view Payroll or Leave Dashboard</li></ul>|