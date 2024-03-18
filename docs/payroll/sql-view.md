---
sidebar_position: 23
id: sql-view
title: SQL View
description: A guide of setting user view on certain records and data
slug: /payroll/sql-view
tags: ["SQL Payroll", "View"]
---

SQL view module is to lock certain user to view from all employees, in other word only allow handling a group of employee.

## Steps & Instructions

In this sample, the goal is allowing KL User to view/ edit only the employee in KL branch.

1. Tools | DIY | Maintain DIY

    1. Go to **View Template** tab

    2. Right Click **Employee** > Select **New View Template**

        ![1](/img/payroll/sql-view/1.png)

    3. Press New

    4. Enter description, enter condition and save

        ![2](/img/payroll/sql-view/2.png)

    5. Right click the new created view template > select **User View**

        ![3](/img/payroll/sql-view/3.png)

    6. Assign user view to this group of employee

        ![4](/img/payroll/sql-view/4.png)

    7. Logon as KL User.

2. Result:

   - Before:

        ![5](/img/payroll/sql-view/5.png)

   - After:

        ![6](/img/payroll/sql-view/6.png)

:::info[note]
If you haven’t register, you may try by turn on SQL View module under :
File | Customize SQL Payroll Module.
:::
