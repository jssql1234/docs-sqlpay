---
sidebar_position: 5
id: etms-user-guide
title: ETMS (Time Management System)
description: A full guide on ETMS
slug: /cloud/SQL_Payroll_eTMS_Guide_Edited-2.0
tags: ["SQL Payroll", "Cloud", "ETMS", "User Guide"]
---

## 1 General Setup

### 1.1 Maintain Cloud Drive

1. **File** | **Company Profile** | **Cloud**

2. Turn **ON** drive

   ![1](/img/cloud/etms-user-guide/1.png)

3. Click on **Log in**

   ![2](/img/cloud/etms-user-guide/2.png)

4. Click on **Log in with Google**

   ![3](/img/cloud/etms-user-guide/3.png)

5. Enter **Email Address** | **Next**

   :::note

   Email address can register with our consultant.

   :::

   ![4](/img/cloud/etms-user-guide/4.png)

6. Enter **password** | **Next**

   ![5](/img/cloud/etms-user-guide/5.png)

7. Click on **Grant access**

   ![6](/img/cloud/etms-user-guide/6.png)

8. Click on Save

   :::note

   Make sure Drive is turn **ON**

   :::

   ![7](/img/cloud/etms-user-guide/7.png)

### 1.2 Maintain Location

1. **Human Resource** | **Maintain Branch**

2. Click on **Edit**

   ![8](/img/cloud/etms-user-guide/8.png)

3. Click on **Map**

   ![9](/img/cloud/etms-user-guide/9.png)

4. Enter **company Address** | **Search** | **Confirm**

   ![10](/img/cloud/etms-user-guide/10.png)

5. Key in **Radius** | **Save**

   :::note

   By default, radius (meter) is 60, able to increase or reduce radius

   :::

   ![11](/img/cloud/etms-user-guide/11.png)

   You can also create new branch if more than one branch

### 1.3 Maintain Public Holiday

1. **Leave** | **Maintain Public Holiday**

   To set the public holiday of the year

2. Click on **Edit**

3. Click on **P** | **Select date of the public holiday** | **Save**

   ![12](/img/cloud/etms-user-guide/12.png)

### 1.4 Maintain Employee

1. **Human Resource** | **Maintain Employee**

2. Double click employee that you want to do setting | **Edit**

   ![13](/img/cloud/etms-user-guide/13.png)

3. Go to **Personal** tab | Key in employee email address

   ![14](/img/cloud/etms-user-guide/14.png)

4. Go to **Grouping** tab | Select Branch

5. Select **Public Holiday Calendar**

6. Select **Work OT**

7. **Save**

   **Attendance Reward**: Work OT >= 2 hours per day, meal allowance is given (Refer 3.3 to get more info)

   :::note

   Just apply for employee who have attendance allowance

   :::

   ![15](/img/cloud/etms-user-guide/15.png)

   :::note

   Tick on Traveler if the employee is traveler (Eg. Sales Person / Delivery Person / Doctor)

   :::

## 2 Time Attendance

### 2.1 Maintain Work Session

1. **Time Attendance** | **Maintain Work Session**

2. Click on **Edit**

   ![16](/img/cloud/etms-user-guide/16.png)

3. Key in time for **Work Start** (09:00 AM) and time for **Work End** (06:00 PM)

   **Late In Buffer (min)** = How many minute(s) allow can be late

   **Early Out Buffer (min)** = How many minute(s) allow can be leave early

   ![17](/img/cloud/etms-user-guide/17.png)

4. Key in **Break Time**

   ![18](/img/cloud/etms-user-guide/18.png)

   |        | Start | End |   Description    |
   |--------|-------|-----|------------------|
   |  1st Break   |  10:00 AM |  10:15 AM    |  Coffee Break     |
   |  2nd Break   |  12:00 PM |   01:00 PM   |   Lunch Break     |
   |3rd Break  | 04:00 PM  | 04:30 PM  | Tea Break    |

5. Select **Rules**

   ![19](/img/cloud/etms-user-guide/19.png)

   - Clock In / Clock Out – User need to Clock In / Clock Out

   - GPS Monitoring (Work Hour) - User need to turn on location every time they Clock In / Clock Out.

   - GPS monitoring is for background tracking after Clock In

   - Site Photo - must take photo before Clock In / Clock Out

   :::note

   Not allow to upload photo from album

   :::

6. Leave Rules

   ![20](/img/cloud/etms-user-guide/20.png)

   ![20a](/img/cloud/etms-user-guide/20a.png)

   :::note

   Just apply for Traveler employee

   Once **apply Leave Rule**, **NO NEED** fill in **Break Time**

   :::

7. Click on **Save** once done all setting

   ![21](/img/cloud/etms-user-guide/21.png)

### 2.2 Maintain Work OT

1. **Time Attendance** | **Maintain Work OT**

2. Select Work OT | **Edit**

   ![22](/img/cloud/etms-user-guide/22.png)

3. Key in **Data Type** | **OT Period** | **Work Session** | **OT Rule**

   ![23](/img/cloud/etms-user-guide/23.png)

   OT Rule – Refer step 4

   | Day Type                | OT Period | Description                  |
   |-------------------------|-----------|------------------------------|
   | Work Day          | Before Work    | Before 9:00 AM               |
   | Work Day           | After Work     | After 6:00 PM                |
   | Work Day      | Break Time         | 12:00 PM – 01:00 PM          |
   | **Rest Day**                | All Day         | Entire day for Rest Day      |
   | Public Holiday          | All Day         | Entire day for Public Holiday|
   | **Rest Day (Special Rate)** | All Day         | Entire day for Rest Day with Special Rate |

   :::note Example

   **Rest day** = Saturday with rate 1.5

   **Rest day (Special Rate)** = Sunday with rate 2.0

   :::

4. Select **OT Rule**

   1. Type 1 : Clock Time

      ![24](/img/cloud/etms-user-guide/24.png)

      **Min OT** - Allow to claim OT at least 15 minutes

      **Max OT** - Allow to OT up to 180 minutes (3 Hours)

      **Allow AdHoc OT** - Between 6:00 PM – 7:00 PM (Allow to start OT immediately)

      ![25](/img/cloud/etms-user-guide/25.png)

      | Period | OT Start | OT   | Description                             |
      |:------:|:------:|:------:|--------------------------------------|
      | 1      | 07:00 PM | HW15 | 07:00 PM - 08:00 PM, OT rate is 1.5  |
      | 2      | 08:00 PM | HW20 | Starting at 08:00 PM onwards, OT rate is 2.0 |

      :::info Example

      If OT start after 08:30PM, OT rate is 2.0 and can claim OT up to 3 Hours (until 11:30 PM)

      :::

   2. Type 2: Tier

      ![26](/img/cloud/etms-user-guide/26.png)

      **OT Start** - Time allow to start OT

      **Min OT** - Allow to claim OT at least 15 minutes

      **Allow AdHoc OT** - Between 6:00 PM – 7:00 PM (Allow to start OT immediately)

      ![27](/img/cloud/etms-user-guide/27.png)

      | Tier | Max OT | OT | Description                                           |
      |:----:|:------:|:----:|----------------------------------------------------|
      |   1  |   30   | HW15  |OT up to 30 minutes, OT rate is 1.5 (Eg. 07:00 PM – 07:30 PM) |
      |   2  |   30   | HW20  |The next OT up to 30 minutes, OT rate is 2.0 (Eg. 07:30 PM – 08:00 PM) |
      |   3  |   60   | HW30  |Finish Tier 1 & Tier 2, OT rate is 3.0 (Eg. 08:00 PM – 09:00 PM) |

5. Click on **OK** once done setting

6. Click on **Save** once done all setting

   ![28](/img/cloud/etms-user-guide/28.png)

### 2.3 Maintain Calendar

1. Wizard Calendar

   1. **Time Attendance** | **Maintain Calendar**

   2. **Tick** employee want to wizard calendar | **Wizard**

      ![29](/img/cloud/etms-user-guide/29.png)

   3. Click on **Rest Day** | Tick every **which day** as **Rest Day or Rest Day (Special Rate)**

   4. Click on **Next**

      ![30](/img/cloud/etms-user-guide/30.png)

   5. Select **Session** and select **Schedule**

      ![31](/img/cloud/etms-user-guide/31.png)

      | Schedule | Description |
      |---------|------------|
      | By Months | Assign on every month, in every week and each day |
      | By Days of Month | Assign on every month and each days of month |
      | By Weeks | Assign on week of year and each days of month |
      | Custom | Assign date by date |

      :::note
      Not able to set past date
      :::

2. View Calendar

   1. **Time Attendance** | **Maintain Calendar**

   2. Click on **View Schedule** | Show all the **calendar and day type**

      ![32](/img/cloud/etms-user-guide/32.png)

3. Copy Calendar from Employee

   1. **Time Attendance** | **Maintain Calendar**

   2. **Tick** employee want to replicate calendar | ↓ | **Copy From**

      ![33](/img/cloud/etms-user-guide/33.png)

   3. Select the **Date Range** | Select **Copy From** which employee | **OK**

      ![34](/img/cloud/etms-user-guide/34.png)

4. Clear Calendar

   1. **Time Attendance** | **Maintain Calendar**

   2. **Tick** employee want to clear all calendar | ↓ | **Clear All**

      ![35](/img/cloud/etms-user-guide/35.png)

   3. Select the **date range** to clear all calendar | **OK**

      ![36](/img/cloud/etms-user-guide/36.png)

   4. Click on **View Schedule** | All the **Rest Day** have been clear

      ![37](/img/cloud/etms-user-guide/37.png)

      :::note

      Not able to clear past date with work session (Rest day will still clear)

      :::

### 2.4 Maintain Traveler Location

1. Wizard Traveler Location

   1. **Time Attendance** | **Maintain Traveler Location**

   2. **Tick** employee want to wizard location | **Wizard**

      ![38](/img/cloud/etms-user-guide/38.png)

   3. Select the option

      ![39](/img/cloud/etms-user-guide/39.png)

      | Schedule | Description   |
      |--------|-------|
      |By Months  | Assign on every month, in every week and each day |
      |By Days of Month | Assign on every month and each days of month |
      |By Weeks | Assign on week of year and each days of month |
      |Custom  | Assign date by date |

   4. Select Months, Weeks, and Days | **+** | **Map**

      ![40](/img/cloud/etms-user-guide/40.png)

   5. Select **GPS Type** | **Branch** (Select Branch to Clock In/ Clock Out for traveler) | **Confirm**

      1. GPS Type 1: Branch (Just select branch that have created earlier)

         ![41](/img/cloud/etms-user-guide/41.png)

      2. GPS Type 2: **Custom** | Key in new **Address** | **Search** | **Confirm**

         ![42](/img/cloud/etms-user-guide/42.png)

   6. Done choose **Coordinate** | **Process**

      ![43](/img/cloud/etms-user-guide/43.png)

      :::note

      Click on **+** if the Traveler employee can *Clock In / Clock Out* either one location

      :::

      ![44](/img/cloud/etms-user-guide/44.png)

      Repeat Step 1 if traveler Clock In / Clock Out more than one location in different day

2. View Traveler Location

   1. **Time Attendance** | **Maintain Traveler Location**

   2. Click on **View Location** | Show all the **Location to Clock In / Clock Out**

   ![45](/img/cloud/etms-user-guide/45.png)

3. Copy Location from Traveler Employee

   1. **Time Attendance** | **Maintain Traveler Employee**

   2. **Tick** employee want to replicate location | ↓ | **Copy From**

      ![46](/img/cloud/etms-user-guide/46.png)

   3. Select the **Date Range** | Select **Copy From** which employee | **OK**

      ![47](/img/cloud/etms-user-guide/47.png)

4. Clear Location

   1. **Time Attendance** | **Maintain Calendar**

   2. **Tick** employee want to clear all location | ↓ | **Clear All**

      ![48](/img/cloud/etms-user-guide/48.png)

   3. Select the **date range** to clear all calendar | **OK**

      ![49](/img/cloud/etms-user-guide/49.png)

   4. Click on **View Location** | All the **Location** have been clear

      ![50](/img/cloud/etms-user-guide/50.png)

      :::note

      Not able to clear location past date

      :::

## 3 Cloud (Time Attendance)

### 3.1 Sync Cloud

1. Steps to Sync

   1. **Cloud** | **Sync Cloud**

   2. **Sync All**

   3. **Time Attendance**

      ![51](/img/cloud/etms-user-guide/51.png)

   4. **Sync Complete**

      ![52](/img/cloud/etms-user-guide/52.png)

2. Log

   1. **Cloud** | **Sync Cloud**

   2. **Time Attendance**

   3. **Log**

      ![53](/img/cloud/etms-user-guide/53.png)

      To show employee Clock Status

3. OT

   1. **Cloud** | **Sync Cloud**

   2. **Time Attendance** | **OT** | **Action**

      ![54](/img/cloud/etms-user-guide/54.png)

      | Actions | Description |
      |---------|-------------|
      | Unassigned | Not yet allocated any action |
      | Overtime  | This working period is assign to OT |
      | Cancelled | Cancelled for this working session |

      Once assign action to Overtime and appear highlighted green, it will be posted to Pending OT

      ![55](/img/cloud/etms-user-guide/55.png)

      ![56](/img/cloud/etms-user-guide/56.png)

      :::info NOTE

      Highlighted **PINK**: WILL NOT be posted to Pending OT, and action will be changed to “Unassigned” (missing OT code)

      :::

      To choose OT Code, **Right Click** on highlighted Pink | **Edit**

      Choose **OT Code** | **Save**

      ![57](/img/cloud/etms-user-guide/57.png)

   3. **Show Log**

      To Show Log for employee who OT

      ![58](/img/cloud/etms-user-guide/58.png)

4. Leave

   1. **Cloud** | **Sync Cloud**

   2. **Leave**

   3. **Actions**

   4. **Leave Type**

      ![59](/img/cloud/etms-user-guide/59.png)

      | Actions | Leave Type | Description |
      |---------|------------|-------------|
      | Unassigned   | -   | Not yet allocated any actions  |
      | Leave  | AL, MC |  Will be deducted as Annual Leave or Medical Leave |
      |Unpaid Leave | UL | Will be deducted as Unpaid Leave |
      |Cancelled | - | Cancelled for this Leave |

### 3.2 Time Attendance Log

:::info NOTE

Only will prompt out for employee who did not Clock Out, HR need assign Clock Out Time manually.

:::

1. Enter **Clock Out** time

2. Tick if **IsOT** (optional)

3. Enter **Break Time** (optional)

   ![60](/img/cloud/etms-user-guide/60.png)

4. **Save**

   ![61](/img/cloud/etms-user-guide/61.png)

### 3.3 Attendance Reward

1. **Time Attendance** | **Print Time Attendance Summary**

2. Make sure **TICK ALL** under **Clock Status**

   ![62](/img/cloud/etms-user-guide/62.png)

3. **Apply**

4. **Attendance Reward**

   ![63](/img/cloud/etms-user-guide/63.png)

5. **Save**

   ![64](/img/cloud/etms-user-guide/64.png)

6. After save, the reward will appear under open pending payroll

   **Payroll** | **Open Pending Payroll** | **Allowance**

   ![65](/img/cloud/etms-user-guide/65.png)

   :::info

   By default, meal allowance is RM20, can refer consultant to change amount

   :::

## 4 Application SQL HRMS

### 4.1 Installation For iPhone User

1. Click on App Store

   ![66](/img/cloud/etms-user-guide/66.png)

2. Click on **Search** (bottom right hand side)

   ![67](/img/cloud/etms-user-guide/67.png)

3. Key in “**SQL HRMS**” in search bar

   ![68](/img/cloud/etms-user-guide/68.png)

4. Click on **GET**

   ![69](/img/cloud/etms-user-guide/69.png)

5. Done

:::note

Minimum IOS version: **IOS 14 and above**

:::

### 4.2 Installation for Android User

1. Click on App Store

   ![70](/img/cloud/etms-user-guide/70.png)

2. Key in “**SQL HRMS**” in search bar | Enter

3. Click on **Install**

   ![71](/img/cloud/etms-user-guide/71.png)

4. Done

   :::note

   - Minimum android version: **Android 8.1 and above**

   - Huawei phones were banned from using Google services in 2019. Therefore, since SQL HRMS utilizes Google technology, certain models of Huawei phones may not be able to enjoy our app

   :::

### 4.3 Login Application with Email

![72](/img/cloud/etms-user-guide/72.png)

1. **Login Application with Email** | **Next**

2. Check Email will receive OTP for login SQL HRMS

   :::note

   If no received can check on SPAM mail

   :::

   ![73](/img/cloud/etms-user-guide/73.png)

3. **Enter OTP Code** after received email | Click **Verify**

:::note

If no receive email, click **Resend** to request resend OTP to your email

:::

### 4.4 Location Setup For iPhone User

1. Turn on Location Services

   1. Click on **Setting**

      ![74](/img/cloud/etms-user-guide/74.png)

   2. Click on **Privacy & Security**

      ![75](/img/cloud/etms-user-guide/75.png)

   3. Click on **Location Services**

      ![76](/img/cloud/etms-user-guide/76.png)

   4. Turn on **Location Services** (Make sure is green color)

      ![77](/img/cloud/etms-user-guide/77.png)

   5. Scroll down and choose **SQL HRMS**

      ![78](/img/cloud/etms-user-guide/78.png)

   6. Choose **Always** & **Precise Location** make sure is **ON**

      ![79](/img/cloud/etms-user-guide/79.png)

   7. Done

### 4.5 Location Setup for Android User

1. Turn on Location Services

   1. Click on Setting

      ![80](/img/cloud/etms-user-guide/80.png)

   2. Click on **Location**

      ![81](/img/cloud/etms-user-guide/81.png)

   3. Turn on **Use Location**

      ![82](/img/cloud/etms-user-guide/82.png)

   4. Click on **SQL HRMS**

      ![83](/img/cloud/etms-user-guide/83.png)

   5. Choose **Allow all the time** & **Precise Location** make sure is **ON**

      ![84](/img/cloud/etms-user-guide/84.png)

   6. Done

## 4.6 Clock In

![85](/img/cloud/etms-user-guide/85.png)

1. Click **Clock In**

   ![86](/img/cloud/etms-user-guide/86.png)

2. **Location matched** when you are in work location | **Take Photo** | Clock In

   - **View Location** can check current location

   - When location not match, will show message **Please Clock In At XXX (Location set)**

### 4.7 Clock Out

1. **Click Clock Out**

   ![87](/img/cloud/etms-user-guide/87.png)

   ![88](/img/cloud/etms-user-guide/88.png)

2. **Location Matched** | **Take Photo** | **Clock Out**

   - Click **Claim OT** when you did OT

   (Key In Total OT Break Time when you OT, system will deduct the break time when calculate OT)

### 4.8 Attendance Log

![89](/img/cloud/etms-user-guide/89.png)

1. View the duration of work for this period working days

   ![90](/img/cloud/etms-user-guide/90.png)

2. Click **Location Updates** to view time and location of clock in & clock out

3. **Details of clock in & clock out**

4. **View photo of clock in & clock out**

### 4.9 Team Attendance

   ![91](/img/cloud/etms-user-guide/91.png)

1. Status will show all staff attendance status

   - View All to view status in detail

   - Attendance Log to view employee clock in & clock out status

   ![92](/img/cloud/etms-user-guide/92.png)

2. Click each Status can view details of that status

   ![93](/img/cloud/etms-user-guide/93.png)

3. Summary of all status (Employee name will be show)

### 4.10 OT Entitlement

![94](/img/cloud/etms-user-guide/94.png)

:::info

Can view the OT Entitlement set by company

:::

### 4.11 My Calendar

![95](/img/cloud/etms-user-guide/95.png)

- View Work Session using Calendar

- View Working Location for each day
