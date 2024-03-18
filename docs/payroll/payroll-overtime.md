---
sidebar_position: 20
id: payroll-overtime
title: Process Payroll with Overtime
description: A guide to process payroll with overtime
slug: /payroll/payroll-overtime
tags: ["SQL Payroll", "Overtime"]
---

## Process Overtime After Month End

1. Click on payroll > Maintenance > Maintain Overtime

    ![1](/img/payroll/payroll-overtime/1.png)

2. Click on New

    ![2](/img/payroll/payroll-overtime/2.png)

3. Enter the code and description, key in the overtime rate, and select the unit type for hourly, and tick or untick those contribution, save after all done

    ![3](/img/payroll/payroll-overtime/3.png)

    ![4](/img/payroll/payroll-overtime/4.png)

4. Repeat the same steps for other overtime type.

    ![5](/img/payroll/payroll-overtime/5.png)

5. After that, when we need to process the payroll at the month end,

    ![6](/img/payroll/payroll-overtime/6.png)

6. Click process.

    ![7](/img/payroll/payroll-overtime/7.png)

7. **DOUBLE CLICK** on one of the employee

    ![8](/img/payroll/payroll-overtime/8.png)

8. Click on the blue **OVERTIME** word

    ![9](/img/payroll/payroll-overtime/9.png)

9. The details of the overtime info will de displayed at the bottom of the application

    ![10](/img/payroll/payroll-overtime/10.png)

    ![11](/img/payroll/payroll-overtime/11.png)

    - Trans Date = the date of overtime
    - Post Date = the date of process or the posting date

    ![12](/img/payroll/payroll-overtime/12.png)

10. Select the code that you created,

    ![13](/img/payroll/payroll-overtime/13.png)

11. Enter the work unit as overtime hour, for example that day Lee Chong Wai overtime for 2 hours, enter 2 into the **Work Unit** column

    ![14](/img/payroll/payroll-overtime/14.png)

12. Or, you also can click on the button beside Trans Date, and tick the column name Work Unit As Time,

    ![15](/img/payroll/payroll-overtime/15.png)

13. After call out the column of Work Unit As Time, you may key in the overtime in minutes

    ![16](/img/payroll/payroll-overtime/16.png)

14. You may click on the append for second column, and repeat the same steps

    ![17](/img/payroll/payroll-overtime/17.png)

15. Click on save, you may repeat the same steps for the other employees

    ![18](/img/payroll/payroll-overtime/18.png)

## Process Overtime Before Month End

1. Click on payroll, open pending payroll.

    ![19](/img/payroll/payroll-overtime/19.png)

2. Double Click on **Overtime**

    ![20](/img/payroll/payroll-overtime/20.png)

3. Click on Append icon

    ![21](/img/payroll/payroll-overtime/21.png)

    ![22](/img/payroll/payroll-overtime/22.png)

4. Select employee

    ![23](/img/payroll/payroll-overtime/23.png)

5. Select **Overtime Code**

    ![24](/img/payroll/payroll-overtime/24.png)

6. Tick and enable the **Work Unit As Time**

    ![25](/img/payroll/payroll-overtime/25.png)

7. Enter the time in the work unit as time, for example Lee Chong Wai worked overtime for 2hours and 30minutes, key in as shown below.

    ![26](/img/payroll/payroll-overtime/26.png)

8. Repeat the same steps as shown above for the other overtime records and save after all done

    ![27](/img/payroll/payroll-overtime/27.png)

9. During month end,

    ![28](/img/payroll/payroll-overtime/28.png)

    ![29](/img/payroll/payroll-overtime/29.png)

10. Double click on the employee’s name or code,

    ![30](/img/payroll/payroll-overtime/30.png)

11. Click on the blue **Overtime** words

    ![31](/img/payroll/payroll-overtime/31.png)

12. The overtime records entered in pending payroll will be shown.

    ![32](/img/payroll/payroll-overtime/32.png)

## Import Excel Overtime Format into SQL Payroll

1. Prepare a table in Microsoft Excel as shown in the image below.

    ![33](/img/payroll/payroll-overtime/33.png)

    - Date = Trans Date
    - Employee = Code of Employee
    - OT = Code of Overtime that created in Maintain Overtime
    - Unit = Work Unit (count 2.50 = 150 minutes/2 and a half hours)

2. After done the table, go to file,

    ![34](/img/payroll/payroll-overtime/34.png)

3. Click on Save as,

    ![35](/img/payroll/payroll-overtime/35.png)

4. Select CSV file type,

    ![36](/img/payroll/payroll-overtime/36.png)

5. Click Save

    ![37](/img/payroll/payroll-overtime/37.png)

6. Go to SQL Payroll > Payroll > Open Pending Payment...

    ![38](/img/payroll/payroll-overtime/38.png)

7. Double click on the Overtime

    ![39](/img/payroll/payroll-overtime/39.png)

8. Click on the Import Data icon

    ![40](/img/payroll/payroll-overtime/40.png)

9. Click on the … (3 dots button) to select your data source,

    ![41](/img/payroll/payroll-overtime/41.png)

10. Select the csv file to import

    ![42](/img/payroll/payroll-overtime/42.png)

11. Click on the Next button

    ![43](/img/payroll/payroll-overtime/43.png)

12. Import from row 1, select Comma, select * for the text delimiter

    ![44](/img/payroll/payroll-overtime/44.png)

13. Select the field for every column

    ![45](/img/payroll/payroll-overtime/45.png)

14. Make sure you have select all the fields for the date, employee, code & workunit.

    ![46](/img/payroll/payroll-overtime/46.png)

15. Change the Import from row to **2** and click the finish button

    ![47](/img/payroll/payroll-overtime/47.png)

16. Click on the Close button after done importing the data

    ![48](/img/payroll/payroll-overtime/48.png)

17. Click on the Save icon

    ![49](/img/payroll/payroll-overtime/49.png)
