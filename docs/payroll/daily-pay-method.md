---
sidebar_position: 7
id: daily-pay-method
title: Daily Pay Method
description: A guide to process CP38
slug: /daily-pay-method
tags: ["SQL Payroll", "Daily Pay"]
---

# Daily Pay Method

For example,  
&emsp;Pay rate per day = RM16.00  
&emsp;Normal working hour = 8 hours

**<ins>DEFINE THE CONTRIBUTION SETTING</ins>**  
[Path: Payroll | Maintenance |Maintain Contribution…]

1. Create new contribution, let said the contribution code is “DAILY.”
2. Define the following items:-
    1. Working Day Per Month = 1
    2. Working Hour Per Day = 8

    ![1](/img/payroll/daily-pay-method/1.png)

**<ins>INPUT THE DAILY RATE IN MAINTAIN EMPLOYEE</ins>**  
[Path: Human Resource | Maintain Employee…]

1. Input the daily rate (RM16.00 per day) in the Wages field.
2. Set the contribution to “DAILY”.

![2](/img/payroll/daily-pay-method/2.png)

**<ins>OPEN PENDING PAYROLL – WAGES</ins>**  
[Path: Payroll  Open Pending Payroll…]

1. Go to Wages Pending.
2. Key-in the daily working records for an employee.
    1. Work unit = 1 day
    2. Rate = RM16.00 per day

    ![3](/img/payroll/daily-pay-method/3.png)

**<ins>OPEN PENDING PAYROLL – OVERTIME</ins>**  
[Path: Payroll | Open Pending Payroll…]

1. Go to Overtime Pending.
2. Key-in the daily working records for an employee.
    1. Code = HW15 (OT Hourly Rate)
    2. Work Unit = No.of hours (OT)
    3. Rate = 1.5 rate per hour (OT)

    ![4](/img/payroll/daily-pay-method/4.png)

**<ins>FINAL PAYROLL PROCESS</ins>**  
[Path: Payroll | New Payroll…]

1. Click on Final followed by Process button.
    ![5](/img/payroll/daily-pay-method/5.png)

**<ins>CHECK TO THE WAGES RECORDS</ins>**

1. Click on the Wages to retrieve the detailed wages records. 
2. You will see the records are posted from wages pending for the month.
    ![6](/img/payroll/daily-pay-method/6.png)

**<ins>CHECK TO THE OVERTIME RECORDS</ins>**

1. Click on the Overtime to retrieve the detailed wages records. 
2. You will see the records are posted from Overtime pending for the month.
    1. Working Day Per Month = 1 (from Maintain Contribution)
    2. Working Hour Per Day = 8 (from Maintain Contribution)
    3. Wages = RM16.00 (from Maintain Employee)

Based on the above information,  
&emsp;&emsp;Daily Pay Rate = RM16.00 / 1 day = RM16.00 per day  
&emsp;&emsp;Hourly Pay Rate = RM16.00 / 8 hrs = RM2.00 per hour

Therefore, the overtime calculation is
|Code|Work Unit|Rate|Pay Rate|OT Pay Rate|Amount|
|:--:| :-----: |:--:|:------:|:---------:|:----:|
|HW15|4hrs|1.5|2.00|RM2.00 x 1.5 = RM3.00|RM3.00 x 4 hrs = RM12.00|
|HW15|4hrs|1.5|2.00|RM2.00 x 1.5 = RM3.00|RM3.00 x 3 hrs = RM9.00|

![7](/img/payroll/daily-pay-method/7.png)