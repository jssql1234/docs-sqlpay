---
sidebar_position: 9
---

# Linking to SQL Account

## Introduction

SQL Vision are linked to SQL Account to get the amount of sales target achieved by employees.

## Requirement

- SQL Vision Sync
- SQL Account
- SQL Vision
- Internet Access

## Setup

1. **Run SQLVisionSync-Setup.exe**

2. Click **Next | Next | Next | Install**

3. Click **Finish**

## Connect SQL Account and SQL Vision with SQL Vision Sync 

![Sync Program](../../../static/img/integration/vision/account/text-connection.png)

1. Insert the SQL accounting DFC file into the corresponding field of SQL Vision Sync. You can find the SQL account DFC file in the path specified within the SQL Account Database of the SQL Accounting Software.
 
![Sync Program](../../../static/img/integration/vision/account/location-DCF-file.png)

2. Open the dropdown and select the database from the dropdown lsit. 

3. Insert the user name and password fields with the SQL Accounting Software user name and password. 

4. Click **Test Connection**.
:::info[Hint]

The SQL Accounting Software must be open and logged in during the connection process.

:::

5. Click **Next** to continue the following steps.


![Sync Program](../../../static/img/integration/vision/account/get-otp-and-token.png)

6. Insert the company ID. 
7. Click **Get OTP** .
8. Insert the OTP Get from the step 7 into the OTP field. 
9. Click **Get Token**.
10. Click **Next** to continue the following steps.

![Sync Program](../../../static/img/integration/vision/account/export-data.png)

11. Select the last export date 
12. Click **Export Data**.
13. Once the data is exported, the SQL Vision mobile app will sync and display the data retrieved from the SQL Accounting Software.

:::info[Parameter for SQL Vision Sync]

![Sync Program](../../../static/img/integration/vision/account/export-log-file.png)

:::

## Strategy

The **Strategy** is a formula that helps managers and the application categorize specific targets for each mission. This setup allows the application to accurately retrieve the target amounts associated with a mission from the SQL Account system.

:::tip Example Scenario

<!-- Suppose you’re managing a Sales Department and want to track quarterly targets for different product lines: -->
Suppose you’re managing a Sales Department and want to track Q1 sales targets:

<!-- 1. **Define a Strategy**  
   Create a strategy named **"Q1 Product Line A Sales"** to track sales targets for Product Line A for the first quarter. -->

1. **Assign Strategy to Mission**  
   For the mission **"Achieve Q1 Sales Target"**, assign the **"Invoice Based Strategy"** strategy.
   <!-- For the mission **"Achieve Q1 Sales Target for Product Line A"**, assign the **"Invoice Based Strategy"** strategy. -->

2. **Automated Target Tracking**  
   With this setup, the application will automatically retrieve and update the sales progress daily, based on employee achievements recorded in SQL Account. Managers can view this updated progress daily in SQL Vision. 
   <!-- With this setup, the application will automatically retrieve and update the sales progress for Product Line A daily, based on employee achievements recorded in SQL Account. Managers can view this updated progress daily in SQL Vision. -->

:::

### 1.0 Pre-defined Strategy

By default, SQL Vision automatically adds two pre-defined strategies to a newly created company, as shown in the image below:

![Predefined Strategy](../../../static/img/integration/vision/account/predefined-strategy.png)

If the system encounters an error and fails to create the pre-defined strategies, you can manually add them by navigating to the Company Configuration section. When this issue occurs, SQL Vision will display a dialog box prompting you to add the default strategies manually, as shown in the image below:

![Predefined Strategy-Add](../../../static/img/integration/vision/account/predefined-strategy-add.png)

### 1.1 Creating or Editing a Strategy

Coming Soon.

<!-- Managers can create or modify strategies by navigating to **Main Dashboard > Side Bar > Company Configuration**.

![Company Configuration](../../../static/img/integration/vision/main-dashboard/companyConfiguration.png)

#### 1. Add Strategy

To add a new strategy, follow these steps:

![Add Strategy](../../../static/img/integration/vision/account/strategy-add.png)

| Step                  | Description                                              | 
|:----------------------|:---------------------------------------------------------|
| **1. Add Icon**       | Click the add icon to create a new strategy.             | 
| **2. Text Field**     | Enter the name of your strategy.                         | 
| **3. Add Button**     | Click the add button to preview the new strategy.        |
| **4. Preview**        | View your strategy in the preview. Use the X to remove it if needed. |
| **5. Save Button**    | Save your new strategy.                                  |
| **6. Cancel Button**  | Cancel your creation.                                    |

#### 2. Edit Strategy

To edit an existing strategy, follow these steps:

![Edit Strategy](../../../static/img/integration/vision/account/strategy-edit.png)

| Step                  | Description                                                       | 
|:----------------------|:------------------------------------------------------------------|
| **1. Edit Icon**      | Click the edit icon to modify an existing strategy.               | 
| **2. Text Field**     | Change the name of the strategy as needed.                        | 
| **3. Edit Button**    | Click the edit button to preview your modifications.              |
| **4. Preview**        | View the strategy in the preview. Use the Edit Icon to re-edit if necessary. |
| **5. Save Button**    | Save your updated strategy.                                       |
| **6. Cancel Button**  | Cancel the modification.                                          | -->

