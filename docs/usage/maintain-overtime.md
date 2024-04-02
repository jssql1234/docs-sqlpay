---
title: Maintain Overtime
description: A guide to process payroll with overtime
slug: /usage/maintain-overtime
tags: ["SQL Payroll", "Overtime"]
---

## Introduction

:::info Features

- Setting up maintain overtime helps you to categorize the type of overtime that company have.
- This would affect the types of contribution that they need to provide (EPF/SOCSO/PCB & etc)
- This setting will bring impact of the calculation of overtime.

:::

## Process Overtime After Month End

1. Click on **Payroll** > **Maintenance** > **Maintain Overtime**

   ![after-maintain-overtime](../../static/img/usage/maintain-overtime/after-maintain-overtime.png)

2. In the list, you can find some default overtime settings. Click on **New** to generate a custom one

   ![after-new](../../static/img/usage/maintain-overtime/after-new.png)

3. Key-in Overtime details as below

   ![after-enter-details](../../static/img/usage/maintain-overtime/after-enter-details.png)

   - Insert the **Code** and **Description** of the overtime that you want to generate.
   - Insert the **Rate** of the overtime, eg : the overtime rate is 1.5 as per overtime amount or double, triple of the overtime amount.
   - **Unit Type** is to set the overtime calculation by hourly or by daily.
     -Set the contribution of overtime with EPF, SOCSO, PCB, EIS etc.

4. After that, when we need to process the payroll at the month end. Navigate to **Payroll** > **New Payroll**

   ![after-navigate-new-payroll](../../static/img/usage/maintain-overtime/after-navigate-new-payroll.png)

5. Click **Final**, and click on **Process**

   ![after-click-process](../../static/img/usage/maintain-overtime/after-click-process.png)

6. Click on any employee

   ![after-click-employee](../../static/img/usage/maintain-overtime/after-click-employee.png)

7. Click on the "**Overtime**"

   ![after-click-overtime](../../static/img/usage/maintain-overtime/after-click-overtime.png)

8. Click on the ➕ to add the info you want

   ![after-click-plus](../../static/img/usage/maintain-overtime/after-click-plus.png)

9. Click on the "**Code**" to choose the overtime type

   ![after-select-code](../../static/img/usage/maintain-overtime/after-select-code.png)

10. Key in the work unit as overtime hour, for example if Lee hong Wai overtime for 2 hours on that particular day, just key in numbering as 2 will do

    ![after-key-overtime-hour](../../static/img/usage/maintain-overtime/after-key-overtime-hour.png)

11. Alternatively, you can click on the button beside Trans Date, and tick the column name Work Unit As Time

    ![after-tick-column](../../static/img/usage/maintain-overtime/after-tick-column.png)

12. After call out the column of Work Unit As Time, you may key in he overtime minutes also (eg: 2 hours and 09 mins)
    ![after-key-overtime-minutes](../../static/img/usage/maintain-overtime/after-key-overtime-minutes.png)

## Process Overtime Before Month End

1. Click on payroll, open pending payroll.

   ![before-open-pending](../../static/img/usage/maintain-overtime/before-open-pending.png)

2. Double Click on **Overtime**

   ![before-open](../../static/img/usage/maintain-overtime/before-open.png)

3. Click on Append icon

   ![before-append-1](../../static/img/usage/maintain-overtime/before-append-1.png)

   ![before-append-2](../../static/img/usage/maintain-overtime/before-append-2.png)

4. Select employee

   ![before-select-employee](../../static/img/usage/maintain-overtime/before-select-employee.png)

5. Select **Overtime Code**

   ![before-select-code](../../static/img/usage/maintain-overtime/before-select-code.png)

6. Tick and enable the **Work Unit As Time**

   ![before-enable-work-unit-as-time](../../static/img/usage/maintain-overtime/before-enable-work-unit-as-time.png)

7. Enter the time in the work unit as time, for example Lee Chong Wai worked overtime for 2hours and 30minutes, key in as shown below

   ![before-enter-time](../../static/img/usage/maintain-overtime/before-enter-time.png)

8. Repeat the same steps as shown above for the other overtime records and save after all done

   ![before-repeat](../../static/img/usage/maintain-overtime/before-repeat.png)

9. During month end,

   ![before-month-end-1](../../static/img/usage/maintain-overtime/before-month-end-1.png)

   ![before-month-end-2](../../static/img/usage/maintain-overtime/before-month-end-2.png)

10. Double click on the employee’s name or code

    ![before-click-employee](../../static/img/usage/maintain-overtime/before-click-employee.png)

11. Click on the blue **Overtime** words

    ![before-click-overtime](../../static/img/usage/maintain-overtime/before-click-overtime.png)

12. The overtime records entered in pending payroll will be shown

    ![before-overtime-records](../../static/img/usage/maintain-overtime/before-overtime-records.png)

## Import Excel Overtime Format into SQL Payroll

1. Prepare a table in Microsoft Excel as shown in the image below

   ![import-excel](../../static/img/usage/maintain-overtime/import-excel.png)

   :::tip

   - **Date**: Trans Date
   - **Employee**: Code of Employee
   - **OT**: Code of Overtime that created in Maintain Overtime
   - **Unit**: Work Unit (count 2.50 = 150 minutes/2 and a half hours)
   :::

2. After done the table, go to file

   ![import-go-to-file](../../static/img/usage/maintain-overtime/import-go-to-file.png)

3. Click on Save as

   ![import-save-as](../../static/img/usage/maintain-overtime/import-save-as.png)

4. Select CSV file type

   ![import-select-csv](../../static/img/usage/maintain-overtime/import-select-csv.png)

5. Click Save

   ![import-save](../../static/img/usage/maintain-overtime/import-save.png)

6. Go to SQL Payroll > Payroll > Open Pending Payroll...

   ![import-open-pending-payroll](../../static/img/usage/maintain-overtime/import-open-pending-payroll.png)

7. Double click on the Overtime

   ![import-click-overtime](../../static/img/usage/maintain-overtime/import-click-overtime.png)

8. Click on the Import Data icon

   ![import-click-data](../../static/img/usage/maintain-overtime/import-click-data.png)

9. Click on the … (3 dots button) to select your data source,

   ![import-click-dots-button](../../static/img/usage/maintain-overtime/import-click-dots-button.png)

10. Select the csv file to import

    ![import-select-csv-file](../../static/img/usage/maintain-overtime/import-select-csv-file.png)

11. Click on the Next button

    ![import-next](../../static/img/usage/maintain-overtime/import-next.png)

12. Import from row 1, select Comma, select " for the text delimiter

    ![import-import](../../static/img/usage/maintain-overtime/import-import.png)

13. Select the field for every column

    ![import-select-field-1](../../static/img/usage/maintain-overtime/import-select-field-1.png)

14. Make sure you have select all the fields for the date, employee, code & workunit.

    ![import-select-field-2](../../static/img/usage/maintain-overtime/import-select-field-2.png)

15. Change the Import from row to **2** and click the finish button

    ![import-finish](../../static/img/usage/maintain-overtime/import-finish.png)

16. Click on the Close button after done importing the data

    ![import-close](../../static/img/usage/maintain-overtime/import-close.png)

17. Click on the Save icon

    ![import-last-save](../../static/img/usage/maintain-overtime/import-last-save.png)
