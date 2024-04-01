---
title: Payroll Overtime
description: A guide to process payroll with overtime
slug: /usage/payroll-overtime
tags: ["SQL Payroll", "Overtime"]
---

## Process Overtime After Month End

1. Click on payroll > Maintenance > Maintain Overtime

    ![after-maintain-overtime](../../static/img/usage/payroll-overtime/after-maintain-overtime.png)

2. Click on New

    ![after-new](../../static/img/usage/payroll-overtime/after-new.png)

3. Enter the code and description, key in the overtime rate, and select the unit type for hourly, and tick or untick those contribution, save after all done

    ![after-enter-details-1](../../static/img/usage/payroll-overtime/after-enter-details-1.png)

    ![after-enter-details-2](../../static/img/usage/payroll-overtime/after-enter-details-2.png)

4. Repeat the same steps for other overtime type

    ![after-repeat-overtime](../../static/img/usage/payroll-overtime/after-repeat-overtime.png)

5. After that, when we need to process the payroll at the month end

    ![after-process-1](../../static/img/usage/payroll-overtime/after-process-1.png)

6. Click process.

    ![after-process-2](../../static/img/usage/payroll-overtime/after-process-2.png)

7. **DOUBLE CLICK** on one of the employee

    ![after-select-employee](../../static/img/usage/payroll-overtime/after-select-employee.png)

8. Click on the blue **OVERTIME** word

    ![after-click-overtime](../../static/img/usage/payroll-overtime/after-click-overtime.png)

9. The details of the overtime info will de displayed at the bottom of the application

    ![after-overtime-details-1](../../static/img/usage/payroll-overtime/after-overtime-details-1.png)

    ![after-overtime-details-2](../../static/img/usage/payroll-overtime/after-overtime-details-2.png)

    - Trans Date = the date of overtime
    - Post Date = the date of process or the posting date

    ![after-overtime-details-3](../../static/img/usage/payroll-overtime/after-overtime-details-3.png)

10. Select the code that you created

    ![after-select-code](../../static/img/usage/payroll-overtime/after-select-code.png)

11. Enter the work unit as overtime hour, for example that day Lee Chong Wai overtime for 2 hours, enter 2 into the **Work Unit** column

    ![after-enter-overtime](../../static/img/usage/payroll-overtime/after-enter-overtime.png)

12. Or, you also can click on the button beside Trans Date, and tick the column name Work Unit As Time

    ![after-tick-column](../../static/img/usage/payroll-overtime/after-tick-column.png)

13. After call out the column of Work Unit As Time, you may key in the overtime in minutes

    ![after-key-overtime-minutes](../../static/img/usage/payroll-overtime/after-key-overtime-minutes.png)

14. You may click on the append for second column, and repeat the same steps

    ![after-repeat](../../static/img/usage/payroll-overtime/after-repeat.png)

15. Click on save, you may repeat the same steps for the other employees

    ![after-save](../../static/img/usage/payroll-overtime/after-save.png)

## Process Overtime Before Month End

1. Click on payroll, open pending payroll.

    ![before-open-pending](../../static/img/usage/payroll-overtime/before-open-pending.png)

2. Double Click on **Overtime**

    ![before-open](../../static/img/usage/payroll-overtime/before-open.png)

3. Click on Append icon

    ![before-append-1](../../static/img/usage/payroll-overtime/before-append-1.png)

    ![before-append-2](../../static/img/usage/payroll-overtime/before-append-2.png)

4. Select employee

    ![before-select-employee](../../static/img/usage/payroll-overtime/before-select-employee.png)

5. Select **Overtime Code**

    ![before-select-code](../../static/img/usage/payroll-overtime/before-select-code.png)

6. Tick and enable the **Work Unit As Time**

    ![before-enable-work-unit-as-time](../../static/img/usage/payroll-overtime/before-enable-work-unit-as-time.png)

7. Enter the time in the work unit as time, for example Lee Chong Wai worked overtime for 2hours and 30minutes, key in as shown below

    ![before-enter-time](../../static/img/usage/payroll-overtime/before-enter-time.png)

8. Repeat the same steps as shown above for the other overtime records and save after all done

    ![before-repeat](../../static/img/usage/payroll-overtime/before-repeat.png)

9. During month end,

    ![before-month-end-1](../../static/img/usage/payroll-overtime/before-month-end-1.png)

    ![before-month-end-2](../../static/img/usage/payroll-overtime/before-month-end-2.png)

10. Double click on the employee’s name or code

    ![before-click-employee](../../static/img/usage/payroll-overtime/before-click-employee.png)

11. Click on the blue **Overtime** words

    ![before-click-overtime](../../static/img/usage/payroll-overtime/before-click-overtime.png)

12. The overtime records entered in pending payroll will be shown

    ![before-overtime-records](../../static/img/usage/payroll-overtime/before-overtime-records.png)

## Import Excel Overtime Format into SQL Payroll

1. Prepare a table in Microsoft Excel as shown in the image below

    ![import-excel](../../static/img/usage/payroll-overtime/import-excel.png)

    - Date = Trans Date
    - Employee = Code of Employee
    - OT = Code of Overtime that created in Maintain Overtime
    - Unit = Work Unit (count 2.50 = 150 minutes/2 and a half hours)

2. After done the table, go to file

    ![import-go-to-file](../../static/img/usage/payroll-overtime/import-go-to-file.png)

3. Click on Save as

    ![import-save-as](../../static/img/usage/payroll-overtime/import-save-as.png)

4. Select CSV file type

    ![import-select-csv](../../static/img/usage/payroll-overtime/import-select-csv.png)

5. Click Save

    ![import-save](../../static/img/usage/payroll-overtime/import-save.png)

6. Go to SQL Payroll > Payroll > Open Pending Payment...

    ![import-open-pending-payment](../../static/img/usage/payroll-overtime/import-open-pending-payment.png)

7. Double click on the Overtime

    ![import-click-overtime](../../static/img/usage/payroll-overtime/import-click-overtime.png)

8. Click on the Import Data icon

    ![import-click-data](../../static/img/usage/payroll-overtime/import-click-data.png)

9. Click on the … (3 dots button) to select your data source,

    ![import-click-dots-button](../../static/img/usage/payroll-overtime/import-click-dots-button.png)

10. Select the csv file to import

    ![import-select-csv-file](../../static/img/usage/payroll-overtime/import-select-csv-file.png)

11. Click on the Next button

    ![import-next](../../static/img/usage/payroll-overtime/import-next.png)

12. Import from row 1, select Comma, select * for the text delimiter

    ![import-import](../../static/img/usage/payroll-overtime/import-import.png)

13. Select the field for every column

    ![import-select-field-1](../../static/img/usage/payroll-overtime/import-select-field-1.png)

14. Make sure you have select all the fields for the date, employee, code & workunit.

    ![import-select-field-2](../../static/img/usage/payroll-overtime/import-select-field-2.png)

15. Change the Import from row to **2** and click the finish button

    ![import-finish](../../static/img/usage/payroll-overtime/import-finish.png)

16. Click on the Close button after done importing the data

    ![import-close](../../static/img/usage/payroll-overtime/import-close.png)

17. Click on the Save icon

    ![import-last-save](../../static/img/usage/payroll-overtime/import-last-save.png)
