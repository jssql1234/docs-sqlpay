---
title: ETMS
description: A full guide on ETMS (Time Management System)
slug: /hrms/etms
tags: ["SQL Payroll", "HRMS", "Cloud", "ETMS", "User Guide", "SQL Drive"]
---

## Introduction

Time Management System (ETMS) is a feature which allows employers to monitor employees performance and greatly reducing hazzle in employees reward such as overtime (OT).

## Prerequisites

Before proceed with the guide below, you will need to have SQL Drive setup. Find out how to setup in the [enable SQL Drive guide](enable-sql-drive)

## 1 General Setup

### 1.1 Maintain Location

1. In SQL Payroll, navigate to **Human Resource** > **Maintain Branch**

2. Click on **Edit**

   ![edit-branch](../../../static/img/integration/hrms/etms/edit-branch.png)

3. Click on **Map**

   ![click-map](../../../static/img/integration/hrms/etms/click-map.png)

4. Key in the **Company Address**, click **Search** and lastly click **Confirm**

   ![company-map-search](../../../static/img/integration/hrms/etms/company-map-search.png)

5. Fill in the **Radius** you wish to control (in meter), and click **Save**

   :::info
   if you leave the field empty, default value of **60m** will be used
   :::

   ![configure-radius](../../../static/img/integration/hrms/etms/configure-radius.png)

   You can also create new branch if more than one branch

### 1.2 Maintain Public Holiday

1. Navigate to **Leave** > **Maintain Public Holiday** to configure the public holiday of the year

2. Click on **Edit**

   ![edit-holiday-calendar](../../../static/img/integration/hrms/etms/edit-holiday-calendar.png)

3. In the tabbed view, click on **P**, select the **date of public holiday** and click **Save**

   ![select-public-holiday](../../../static/img/integration/hrms/etms/select-public-holiday.png)

### 1.3 Maintain Employee

1. Navigate to **Human Resource** > **Maintain Employee**

2. Click to highlight the employee you wish to change it's settings, and click **Edit**

   ![edit-employee](../../../static/img/integration/hrms/etms/edit-employee.png)

3. Go to **Personal** tab, key in employee email address

   ![edit-email](../../../static/img/integration/hrms/etms/edit-email.png)

4. Next, go to the **Grouping** tab and select Branch

5. Select **Public Holiday Calendar**

6. Select **Work OT**

7. Click **Save**

   :::note
   Tick on Traveller if the employee is Traveller (Eg. Sales Person / Delivery Person / Doctor)
   :::

   ![edit-employee-grouping](../../../static/img/integration/hrms/etms/edit-employee-grouping.png)

:::tip
In ETMS, we have the **Attendance Reward** feature. If the worker works for more than _2 hours_ of OT per day (OT >= 2 hours), default meal allowance is provided. (This default settings apply to employees who have **attendance allowance only**)
:::

## 2 Time Attendance

### 2.1 Maintain Work Session

1. Navigate to **Time Attendance** > **Maintain Work Session**

2. Click on **Edit**

   ![workstation](../../../static/img/integration/hrms/etms/workstation.png)

3. Key in time for **Work Start** (09:00 AM) and time for **Work End** (06:00 PM)

   :::info
   **Late In Buffer (min)**: How many minute(s) allow can be late

   **Early Out Buffer (min)**: How many minute(s) allow can be leave early
   :::

   ![edit-workstation](../../../static/img/integration/hrms/etms/edit-workstation.png)

4. Key in **Break Time**

   ![breaktime](../../../static/img/integration/hrms/etms/breaktime.png)

   |           | Start    | End      | Description  |
   | --------- | -------- | -------- | ------------ |
   | 1st Break | 10:00 AM | 10:15 AM | Coffee Break |
   | 2nd Break | 12:00 PM | 01:00 PM | Lunch Break  |
   | 3rd Break | 04:00 PM | 04:30 PM | Tea Break    |

5. Select **Rules**

   ![work-session-rules](../../../static/img/integration/hrms/etms/work-session-rules.png)

   :::info
   **Clock In / Clock Out**: whether user need to clock in / clock out

   **GPS Monitoring (Work Hour)**: User need to turn on location every time they Clock In / Clock Out

   **Site Photo**: User must take photo during Clock In / Clock Out (Doesn't allow photo from album)
   :::

6. Leave Rules

   ![leave-rules](../../../static/img/integration/hrms/etms/leave-rules.png)

   ![leave-rules-table](../../../static/img/integration/hrms/etms/leave-rules-table.png)

   :::tip
   For Traveller employee, once apply the **Leave Rule**, **NO NEED** fill in the **Break Time**
   :::

7. Click on **Save** once you have done with all settings

   ![save-work-session](../../../static/img/integration/hrms/etms/save-work-session.png)

### 2.2 Maintain Work OT

1. Navigate to **Time Attendance** > **Maintain Work OT**

2. Select a Work OT rule, and click **Edit**

   ![work-ot](../../../static/img/integration/hrms/etms/work-ot.png)

3. Key in **Day Type**, **OT Period**, **Work Session**, **OT Rule**

   ![edit-work-ot](../../../static/img/integration/hrms/etms/edit-work-ot.png)

4. Select **OT Rule** (Refer to [OT rules](#221-ot-rules) for more details)

5. Click on **OK** once done setting

6. Click on **Save** once done all setting

   ![save-work-ot](../../../static/img/integration/hrms/etms/save-work-ot.png)

#### 2.2.1 OT Rules

:::note Example
**Rest day** = Saturday with rate 1.5

**Rest day (Special Rate)** = Sunday with rate 2.0
:::

1. Table below explains the OT rules
   | Day Type | OT Period | Description |
   | --------------------------- | ----------- | ----------------------------------------- |
   | Work Day | Before Work | Before 9:00 AM |
   | Work Day | After Work | After 6:00 PM |
   | Work Day | Break Time | 12:00 PM – 01:00 PM |
   | **Rest Day** | All Day | Entire day for Rest Day |
   | Public Holiday | All Day | Entire day for Public Holiday |
   | **Rest Day (Special Rate)** | All Day | Entire day for Rest Day with Special Rate |

2. There are two types of OT rules:

   - Clock Time
   - Tier

3. Example of **Clock Time**

   ![clock-time](../../../static/img/integration/hrms/etms/clock-time.png)

   | Field              | Description                                               |
   | ------------------ | --------------------------------------------------------- |
   | **Min OT**         | Allow to claim OT at least 15 minutes                     |
   | **Max OT**         | Allow to OT up to 180 minutes (3 Hours)                   |
   | **Allow AdHoc OT** | Between 6:00 PM – 7:00 PM (Allow to start OT immediately) |

   ![clock-time-period](../../../static/img/integration/hrms/etms/clock-time-period.png)

   | Period | OT Start |  OT  | Description                                  |
   | :----: | :------: | :--: | -------------------------------------------- |
   |   1    | 07:00 PM | HW15 | 07:00 PM - 08:00 PM, OT rate is 1.5          |
   |   2    | 08:00 PM | HW20 | Starting at 08:00 PM onwards, OT rate is 2.0 |

   :::info Example
   If OT start after 08:30PM, OT rate is 2.0 and can claim OT up to 3 Hours (until 11:30 PM)
   :::

4. Example of **Tier**

   ![tier](../../../static/img/integration/hrms/etms/tier.png)

   | Field              | Description                                               |
   | ------------------ | --------------------------------------------------------- |
   | **OT Start**       | Time allow to start OT                                    |
   | **Min OT**         | Allow to claim OT at least 15 minutes                     |
   | **Allow AdHoc OT** | Between 6:00 PM – 7:00 PM (Allow to start OT immediately) |

   ![tier-period](../../../static/img/integration/hrms/etms/tier-period.png)

   | Tier | Max OT |  OT  | Description                                                            |
   | :--: | :----: | :--: | ---------------------------------------------------------------------- |
   |  1   |   30   | HW15 | OT up to 30 minutes, OT rate is 1.5 (Eg. 07:00 PM – 07:30 PM)          |
   |  2   |   30   | HW20 | The next OT up to 30 minutes, OT rate is 2.0 (Eg. 07:30 PM – 08:00 PM) |
   |  3   |   60   | HW30 | Finish Tier 1 & Tier 2, OT rate is 3.0 (Eg. 08:00 PM – 09:00 PM)       |

### 2.3 Maintain Calendar

1. Wizard Calendar

   1. Navigate to **Time Attendance** > **Maintain Calendar**

   2. **Select** the employees you wish to apply the wizard calendar and click on the **Wizard** button

      ![wizard-calendar](../../../static/img/integration/hrms/etms/wizard-calendar.png)

   3. Click on **Rest Day**. In the **Make every** dropdown, select every _day_ you wish to specify as **Rest Day or Rest Day (Special Rate)**

   4. Click on **Next**

      ![wizard-calendar-next](../../../static/img/integration/hrms/etms/wizard-calendar-next.png)

   5. Select **Session** and select **Schedule**

   :::warning
   You will not be able to set a past date
   :::

   ![select-schedule](../../../static/img/integration/hrms/etms/select-schedule.png)

   | Schedule         | Description                                       |
   | ---------------- | ------------------------------------------------- |
   | By Months        | Assign on every month, in every week and each day |
   | By Days of Month | Assign on every month and each days of month      |
   | By Weeks         | Assign on week of year and each days of month     |
   | Custom           | Assign date by date                               |

2. View Calendar

   1. Navigate to **Time Attendance** > **Maintain Calendar**

   2. Click on **View Schedule**, it should show all the **calendar and day type**

      ![view-calendar](../../../static/img/integration/hrms/etms/view-calendar.png)

3. Copy Calendar from Employee

   1. Navigate to **Time Attendance** > **Maintain Calendar**

   2. **Tick** employee you wish to replicate calendar, and click on the dropdown 🔽 besides the **Wizard** button, select **Copy From**

      ![copy-calendar](../../../static/img/integration/hrms/etms/copy-calendar.png)

   3. Specify the **Date Range**, select **Copy From** which employee and finally press **OK**

      ![copy-calendar-confirm](../../../static/img/integration/hrms/etms/copy-calendar-confirm.png)

4. Clear Calendar

   :::note
   Not able to clear past date with work session (Rest day will still clear)
   :::

   1. Navigate to **Time Attendance** > **Maintain Calendar**

   2. **Select** the employees you wish to clear all calendar and click on the dropdown 🔽 besides the **Wizard** button, select **Clear All**

      ![clear-calendar](../../../static/img/integration/hrms/etms/clear-calendar.png)

   3. Select the **date range** to clear all calendar and press **OK**

      ![clear-calendar-confirm](../../../static/img/integration/hrms/etms/clear-calendar-confirm.png)

   4. Click on **View Schedule** to view the changes, all the **Rest Day** will be cleared

      ![clear-calendar-result](../../../static/img/integration/hrms/etms/clear-calendar-result.png)

### 2.4 Maintain Traveller Location

1. Wizard Traveller Location

   :::info
   Repeat the guide if Traveller Clock In / Clock Out in more than one location on different day
   :::

   1. Navigate to **Time Attendance** > **Maintain Traveller Location**

   2. **Select** employee you want to do wizard location and click on the **Wizard** button

      ![traveller-location](../../../static/img/integration/hrms/etms/traveller-location.png)

   3. Select the option

      ![traveller-location-option](../../../static/img/integration/hrms/etms/traveller-location-option.png)

      | Schedule         | Description                                       |
      | ---------------- | ------------------------------------------------- |
      | By Months        | Assign on every month, in every week and each day |
      | By Days of Month | Assign on every month and each days of month      |
      | By Weeks         | Assign on week of year and each days of month     |
      | Custom           | Assign date by date                               |

   4. Select Months, Weeks, and Days, click on the ➕ button and select **Map**

      ![traveller-location-setup](../../../static/img/integration/hrms/etms/traveller-location-setup.png)

   5. Select your desired **GPS Type**. There are two **GPS Type**:

      - **Branch**: This type is specifically for enabling Clock In / Clock out for travellers

      ![branch](../../../static/img/integration/hrms/etms/branch.png)

      - **Custom**: For custom, key in the **Address**, click **Search** to look for the location and lastly press the **Confirm** button

      ![custom](../../../static/img/integration/hrms/etms/custom.png)

   6. After that, click **Process** to set the rule

      ![traveller-location-process](../../../static/img/integration/hrms/etms/traveller-location-process.png)

   7. You can add multiple locations if your employee is allowed to Clock In / Clock out in different places

      ![traveller-location-multiple](../../../static/img/integration/hrms/etms/traveller-location-multiple.png)

2. View Traveller Location

   1. Navigate to **Time Attendance** > **Maintain Traveller Location**

   2. Click on **View Location** to show all the **Location to Clock In / Clock Out**

   ![traveller](../../../static/img/integration/hrms/etms/traveller.png)

3. Copy Location from Traveller Employee

   1. Navigate to **Time Attendance** > **Maintain Traveller Employee**

   2. **Select** the employees you wish to replicate the location and click on the dropdown 🔽 besides the **Wizard** button, select **Copy From**

      ![traveller-location-copy](../../../static/img/integration/hrms/etms/traveller-location-copy.png)

   3. Specify the **Date Range** and select which employee to copy from, and press **OK**

      ![traveller-location-copy-confirm](../../../static/img/integration/hrms/etms/traveller-location-copy-confirm.png)

4. Clear Location

   :::info
   Take note you will not be able to clear location past date
   :::

   1. Navigate to **Time Attendance** > **Maintain Calendar**

   2. **Select** the employees you wish to clear all the location and click on the dropdown 🔽 besides the **Wizard** button, select **Clear All**

      ![traveller-location-clear](../../../static/img/integration/hrms/etms/traveller-location-clear.png)

   3. Specify the **date range** to clear all calendar and press **OK**

      ![traveller-location-clear-confirm](../../../static/img/integration/hrms/etms/traveller-location-clear-confirm.png)

   4. To see the updates, click on **View Location** and you will be able to see all the **Location** records have been clear

      ![traveller-location-clear-result](../../../static/img/integration/hrms/etms/traveller-location-clear-result.png)

## 3 Cloud (Time Attendance)

### 3.1 Sync Cloud

1. Sync

   1. Navigate to **Cloud ☁️** > **Sync Cloud**

   2. Press **Sync All**

   3. Next, go to **Time Attendance** tabbed view

      ![sync-cloud](../../../static/img/integration/hrms/etms/sync-cloud.png)

   4. Check the bottom left tray, the status should shows **Sync Complete**

      ![sync-cloud-completed](../../../static/img/integration/hrms/etms/sync-cloud-completed.png)

2. Log

   1. Navigate to **Cloud** > **Sync Cloud**

   2. Next, go to **Time Attendance** in the tabbed view

   3. In the **Log** tab, you will see history of employee clock in / clock out status

      ![time-attendance-log](../../../static/img/integration/hrms/etms/time-attendance-log.png)

3. OT

   1. Navigate to **Cloud** > **Sync Cloud**

   2. Next, go to **Time Attendance**, the **OT** tab, and click on the **Action** dropdown

      ![ot](../../../static/img/integration/hrms/etms/ot.png)

   3. The table below explains different action you can modify for the employee OT:

      | Actions    | Description                         |
      | ---------- | ----------------------------------- |
      | Unassigned | Not yet allocated any action        |
      | Overtime   | This working period is assign to OT |
      | Cancelled  | Cancelled for this working session  |

   4. When set the action to **Overtime**, it might be highlighted as Green 🟢 or Red 🔴

   5. If it appears as Green 🟢, it will be posted to _Pending OT_

      ![green-case](../../../static/img/integration/hrms/etms/green-case.png)

   6. If it appears as Red 🔴, it **WILL NOT** be posted to pending OT, and action will be automatically switched to "Unassigned" due to **missing OT code**

      ![red-case](../../../static/img/integration/hrms/etms/red-case.png)

   7. To resolve the Red 🔴 case, choose OT Code by right clicking on the record, and select **Edit**

   8. Choose the **OT Code** for the employee and click **Save**

      ![select-ot-code](../../../static/img/integration/hrms/etms/select-ot-code.png)

   9. Besides, you can also see logs of employee who had OT by clicking on **Show Log**

      ![show-log-1](../../../static/img/integration/hrms/etms/show-log-1.png)

      ![show-log-2](../../../static/img/integration/hrms/etms/show-log-2.png)

4. Leave

   1. Navigate to **Cloud** > **Sync Cloud**

   2. Select **Leave** in the tabbed view

   3. In the **Leave** tab, you can configure the **Action** and **Leave Type**. There are a variety of actions + leave combinations to control the leave, refer to table below:

      ![leave](../../../static/img/integration/hrms/etms/leave.png)

      | Actions      | Leave Type | Description                                       |
      | ------------ | ---------- | ------------------------------------------------- |
      | Unassigned   | -          | Not yet allocated any actions                     |
      | Leave        | AL, MC     | Will be deducted as Annual Leave or Medical Leave |
      | Unpaid Leave | UL         | Will be deducted as Unpaid Leave                  |
      | Cancelled    | -          | Cancelled for this Leave                          |

### 3.2 Time Attendance Log

:::info NOTE
Only will prompt out for employee who did not Clock Out, HR need assign Clock Out Time manually.
:::

1. Enter **Clock Out** time

2. Tick if **IsOT** (optional)

3. Enter **Break Time** (optional)

   ![tms-log-config](../../../static/img/integration/hrms/etms/tms-log-config.png)

4. **Save**

   ![tms-log-config-save](../../../static/img/integration/hrms/etms/tms-log-config-save.png)

### 3.3 Attendance Reward

:::info
By default, meal allowance is set to RM20, you can refer service consultant to change the settings
:::

1. Navigate to **Time Attendance** > **Print Time Attendance Summary**

2. Make sure to **TICK ALL** under **Clock Status**

   ![attendance-reward](../../../static/img/integration/hrms/etms/attendance-reward.png)

3. **Apply** and click on **Attendance Reward**

   ![attendance-reward-apply](../../../static/img/integration/hrms/etms/attendance-reward-apply.png)

4. Press on **Save**

   ![attendance-reward-save](../../../static/img/integration/hrms/etms/attendance-reward-save.png)

5. After save, the reward will appear under open pending payroll (you can navigate to **Payroll** > **Open Pending Payroll** > **Allowance** to view it)

   ![attendance-reward-result](../../../static/img/integration/hrms/etms/attendance-reward-result.png)

## 4 Application SQL HRMS

### 4.1 Installation For iPhone User

:::note
Minimum IOS version: **IOS 14 and above**
:::

1. Click on App Store

   ![app-store](../../../static/img/integration/hrms/etms/app-store.png)

2. Click on **Search** (bottom right hand side)

   ![app-store-home](../../../static/img/integration/hrms/etms/app-store-home.png)

3. Key in “**SQL HRMS**” in search bar

   ![app-store-search](../../../static/img/integration/hrms/etms/app-store-search.png)

4. Click on **GET**

   ![app-store-hrms](../../../static/img/integration/hrms/etms/app-store-hrms.png)

5. Done

### 4.2 Installation for Android User

:::note

- Minimum android version: **Android 8.1 and above**

- Huawei phones were banned from using Google services in 2019. Therefore, since SQL HRMS utilizes Google technology, certain models of Huawei phones may not be able to enjoy our app

:::

1. Click on App Store

   ![playstore](../../../static/img/integration/hrms/etms/playstore.png)

2. Key in “**SQL HRMS**” in search bar | Enter

3. Click on **Install**

   ![playstore-hrms](../../../static/img/integration/hrms/etms/playstore-hrms.png)

### 4.3 Login to the Application

1. Open the mobile application, key in your registered email and click **Next**

   ![hrms-login](../../../static/img/integration/hrms/etms/hrms-login.png)

2. You will receive OTP in your email, go to your mailbox to grab the code

   :::info
   If you didn't receive the mail, kindly check the spam box. The OTP email might have been falsely classfied as spam by mail classifier. If not in spam box, click **Resend** to receive a new OTP mail
   :::

3. **Enter the OTP Code** and click **Verify**

   ![hrms-verify](../../../static/img/integration/hrms/etms/hrms-verify.png)

### 4.4 Location Setup For iPhone User

1. Turn on Location Services

   1. Click on **Setting**

      ![ios-settings](../../../static/img/integration/hrms/etms/ios-settings.png)

   2. Click on **Privacy & Security**

      ![ios-security](../../../static/img/integration/hrms/etms/ios-security.png)

   3. Click on **Location Services**

      ![ios-location-service](../../../static/img/integration/hrms/etms/ios-location-service.png)

   4. Turn on **Location Services** (Make sure is green color)

      ![ios-location-service-on](../../../static/img/integration/hrms/etms/ios-location-service-on.png)

   5. Scroll down and choose **SQL HRMS**

      ![ios-location-allow-hrms](../../../static/img/integration/hrms/etms/ios-location-allow-hrms.png)

   6. Choose **Always** & **Precise Location** make sure is **ON**

      ![ios-location-precise](../../../static/img/integration/hrms/etms/ios-location-precise.png)

### 4.5 Location Setup for Android User

1. Turn on Location Services

   1. Click on Setting

      ![android-settings](../../../static/img/integration/hrms/etms/android-settings.png)

   2. Click on **Location**

      ![android-location](../../../static/img/integration/hrms/etms/android-location.png)

   3. Turn on **Use Location**

      ![android-use-location](../../../static/img/integration/hrms/etms/android-use-location.png)

   4. Click on **SQL HRMS**

      ![android-allow-hrms](../../../static/img/integration/hrms/etms/android-allow-hrms.png)

   5. Choose **Allow all the time** & **Precise Location** make sure is **ON**

      | 1. Allow all the time                                                                  | 2. On the Precise Location                                                           |
      | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
      | ![android-location-all-time](../../../static/img/integration/hrms/etms/android-location-all-time.png) | ![android-precise-location](../../../static/img/integration/hrms/etms/android-precise-location.png) |

## 4.6 Clock In

1. Click **Clock In**

   ![clock-in](../../../static/img/integration/hrms/etms/clock-in.png)

2. When you have reach your work location, you should see the status changed to **Location matched**. Take a photo by clicking on **Take Photo** and press **Clock In**

   ![take-photo](../../../static/img/integration/hrms/etms/take-photo.png)

3. From the screen, you can check your current location by clicking on **View Work Location**

4. If the location does not match, the app will show a message **Please Clock In At XXX (Location set)**

### 4.7 Clock Out

1. Click **Clock Out**

   ![clock-out](../../../static/img/integration/hrms/etms/clock-out.png)

2. Whe you are in your work location, you shoul see the status is **Location Matched**. Take a photo by clicking on  **Take Photo** and press **Clock Out**

3. Click **Claim OT** when you did OT. Key In Total OT Break Time when you OT, system will deduct the break time when calculate OT

   ![claim-ot](../../../static/img/integration/hrms/etms/claim-ot.png)

### 4.8 Attendance Log

1. View the duration of work for this period working days

   ![attendance-log](../../../static/img/integration/hrms/etms/attendance-log.png)

2. Click **Location Updates** to view time and location of clock in & clock out

   ![clocking-details](../../../static/img/integration/hrms/etms/clocking-details.png)

### 4.9 Team Attendance

![team-attendance](../../../static/img/integration/hrms/etms/team-attendance.png)

1. Status will show all staff attendance status

   - View All to view status in detail

   - Attendance Log to view employee clock in & clock out status

2. Click each Status can view details of that status

   ![team-attendance-status-details-1](../../../static/img/integration/hrms/etms/team-attendance-status-details-1.png)

   ![team-attendance-status-details-2](../../../static/img/integration/hrms/etms/team-attendance-status-details-2.png)

3. Summary of all status (Employee name will be show)

   ![team-attendance-summary](../../../static/img/integration/hrms/etms/team-attendance-summary.png)

### 4.10 OT Entitlement

:::info
Can view the OT Entitlement set by company
:::

![ot-entitlement](../../../static/img/integration/hrms/etms/ot-entitlement.png)

### 4.11 My Calendar

1. View Work Session using Calendar
2. View Working Location for each day

![my-calendar](../../../static/img/integration/hrms/etms/my-calendar.png)
