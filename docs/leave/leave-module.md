---
sidebar_position: 4
id: leave-module
title: Leave Module
description: A guide leave module for SQL Payroll
slug: /leave/leave-module
tags: ["SQL Payroll", "Leave","Leave Application","Leave Module"]
---


:::info
Before assigning leave group to your employee, you need to make sure that you have leave type and leave group maintained beforehand. **“Leave Type”** simply means the nature of the leave, while **“Leave Group”** is the grouping method of employee according to their leave entitlement.
:::

## Maintain Leave Type

1. Firstly, point to “Leave” tab and select “Maintain Leave Type”

    ![1](/img/leave/leave-module/1.png)

2. Click on **“New”** button on the upper right corner to create new leave type

    ![2](/img/leave/leave-module/2.png)

3. Assign code for your leave type.

    :::tip eg: MaL for Maternity Leave:

    - Tick on the relevant pay entitlement;
    - And “Save”.
    :::

    ![3](/img/leave/leave-module/3.png)

4. You have your new leave type created.

    ![4](/img/leave/leave-module/4.png)

## Maintain Leave Group

1. Firstly, point to **“Leave”** tab and select **“Maintain Leave Group”**

    ![5](/img/leave/leave-module/5.png)

2. Click on **“New”** button on the upper right corner to create new leave group.

    ![6](/img/leave/leave-module/6.png)

3. Assign code for your new leave group.

    eg: FW for “Foreign Worker”;
    - Click on the “+” button to select the entitled leave type for this particular leave group.

    ![7](/img/leave/leave-module/7.png)

4. Taking **“Annual Leave (AL)”** as an example.

    - By default, the calculation for “Annual Leave” is as such:

    |Year of Service (Years) |Day of Leave Entitled (Days) |
    |------------------------|-----------------------------|
    |1 to 2                  |          8                  |
    |3 to 4                  |         12                  |
    |  >4                    |         16                  |

    If your company’s annual leave policy follows this default setting, you can point to the **“Entitle”** tab and select **“Annual Leave Entitlement Policy”**. With that, the calculation will follow the default setting.

    ![8](/img/leave/leave-module/8.png)

    Click **“Save”**.

5. If your company does not follow the default annual leave setting, you can always customise your own calculation by calling out the **“Entitle (Table)”** column.

    ![9](/img/leave/leave-module/9.png)

     Point to “…” button under **“Entitle (Table)”** tab.

    ![10](/img/leave/leave-module/10.png)

6. Click on the “+” button to call out the row bar for you to key in the **“Year From”**, **“Year To”** and **“Days”**.

    ![11](/img/leave/leave-module/11.png)

7. For example, your company complies to the calculation as below.

    |Year of Service (Years) | Day of Leave Entitled (Days) |
    |------------------------|------------------------------|
    |1 to 2                  |      8                       |
    |3 to 5                  |      12                      |
    |>5                      |      18                      |

    Thus, you need to key in the table as such:

    |Year From |Year To |Days  |
    |----------|--------|------|
    |1         | 2      | 8    |
    |3         | 5      | 12   |
    |1         | 99     | 18   |

    ![12](/img/leave/leave-module/12.png)

    Click **“OK”** then you will come to this. The new calculation will be clearly stated out in the **“Entitle (Table)”** column. Then, click **“Save”**

    ![13](/img/leave/leave-module/13.png)

## Employee Leave Group Assignment

1. Firstly, point to **“Human Resource”** tab and select **“Maintain Employee”**

    ![14](/img/leave/leave-module/14.png)

2. Select relevant employee. eg: Nicole. Click “Edit”

    ![15](/img/leave/leave-module/15.png)

3. Click on **“Grouping”** tab, and you will see **“Leave Group”** at the last panel.

    ![16](/img/leave/leave-module/16.png)

4. Assign relevant leave group.

    eg: Foreign Worker (FW)

    Then, Click **“Save"**

    ![17](/img/leave/leave-module/17.png)
    ![18](/img/leave/leave-module/18.png)

## Leave Application

1. First, point to **“Leave”** and click on **“Leave Application”**

    ![19](/img/leave/leave-module/19.png)

2. Select the year. eg: Year 2015

    ![20](/img/leave/leave-module/20.png)

3. Point to the name of employee and click into it. eg: Lee Chong Wai

    ![21](/img/leave/leave-module/21.png)

4. Click on the “+” button. A row will appear in the display box where you can select the date, type of leave and number of day as how your employee applied. Click “Save once the application is done.

    ![22](/img/leave/leave-module/22.png)
    ![23](/img/leave/leave-module/23.png)

5. If your employee applies for half day leave or leave calculated in hours, call out “Day As Time” column. 1 working day has 8 working hours.

    ![24](/img/leave/leave-module/24.png)

6. Select the duration of the leave. eg: 3 hours. Then system will automatically calculate the number of day as 0.38 day.

    ![25](/img/leave/leave-module/25.png)

## Leave Entitlement Processor

1. Leave entitlement process can be done once a year. First, point to “Leave” and click on “Leave Entitlement Processor”.

    ![26](/img/leave/leave-module/26.png)

2. Select the Transaction Posting Year. eg: 2015. And click “Process”

    ![27](/img/leave/leave-module/27.png)

3. You will see a table clearly stating the number of leave each and every employee entitled in the year 2015.

    ![28](/img/leave/leave-module/28.png)

4. System allows you to edit the number of day. Click **“Save”** when the setting is done.

    ![29](/img/leave/leave-module/29.png)
