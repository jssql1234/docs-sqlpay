---
sidebar_position: 3
---

# Manager
:::info[Note]

These feature is only available to **manager**.  

:::

## Gift Creation
:::info[Note]
After a manager creates a gift, users receive a notification about the new gift.
:::
To add a new gift, managers can go to **More icon> Add Gift**.

![gift](../../../../static/img/integration/vision/gift/gotoAddGift.png)

### 1. Gift Redemption Details

![gift](../../../../static/img/integration/vision/gift/addGiftStep1.png)

| Properties                   | Description                                                                        | Note     |
|:-----------------------------|:-----------------------------------------------------------------------------------|:--------:|
| **1.0 Name** | The name of the gift.                                                                               | Required |
| **1.1 Description** | A detailed description of the gift.                                                          | Required |
| **1.2 Terms & Conditions** | To specify the rules, requirements, guidelines, and limitations that the user must agree to in order to redeem the gift.                                                                                                               | Required |
| **1.3 Redemption Validity Start Date** | The first date when the gift can be redeemed.                            | Required |
| **1.4 Redemption Validity End Date** | The last date when the gift can be redeemed.                                | Required |
| **1.5 Clear** | Clears all content on the current page.                                                            |    -     |
| **1.6 Next** |  Navigates to the previous page.                                                             |    -     |

### 2. Gift Redeemption Criteria 

![gift](../../../../static/img/integration/vision/gift/addGiftStep2.png)

| Properties                   | Description                                                                        | Note     |
|:-----------------------------|:-----------------------------------------------------------------------------------|:--------:|
| **2.0 Redeem Coins** | To specify the amount of coins required to redeem the gift.                                | Required |
| **2.1 Category** | To select a category to classify the gift, such as Uncategorised, Food & Beverages, Shopping, Service, Entertainment, Digital Goods, or Travel Accommodation.                                                                                            | Required |
| **2.2 Available Quantity** | To specify the total number of units of the gift that are available for redemption.             | Required |
| **2.3 Max Allowable Redemption Per Employee** | To specify the maximum number of times a user can redeem the gift.| Required |
| **2.4 Attactment** | To upload an image associated with the gift, such as a product photo or promotional graphic, through the mobile's camera or gallery.                                                | - |
| **2.5 Clear** | Clears all content on the current page.                                                            |    -     |
| **2.6 Back** | Navigates to the previous page.                                                                    |    -     |
| **2.7 Create** |  To submit and create the new gift entry after filling in all required details.                   |    -     |


## Gift Update


### 1. Choose Gift

To update a gift, the manager can go to **More icon > Manage Gift** and select the gift want to be update.
|![gift](../../../../static/img/integration/vision/gift/gotoManageGift.png)|![gift](../../../../static/img/integration/vision/gift/chooseEditGift.png)                 |
|:------------------------------------|:-----------------------------------------------------|

### 2. Update Gift Details
In step 2 of edit mode, the user can update the gift's status using the **"Set as Active"** field.

:::info[Note]

The **Active** status can only be set if the Redemption Validity End Date is **on or after** the the current date.

:::

|![gift](../../../../static/img/integration/vision/gift/editGiftStep1.png)|![gift](../../../../static/img/integration/vision/gift/editGiftStep2.png)                   |
|:------------------------------------|:-----------------------------------------------------|

## Gift Issue 

### 1. Choose Gift Issuance Request

The gift can only be issued after the user has redeemed it. To issue a gift, the manager can go to **More icon > Manage Redemption** and select a gift issuance request.

|![gift](../../../../static/img/integration/vision/gift/gotoManageRedemption.png)|![gift](../../../../static/img/integration/vision/gift/chooseIssueGift.png)          |
|:------------------------------------|:-----------------------------------------------------|

### 2. Confirm Issuance
After clicking **Issue**, select **Confirm** to complete issuing the gift.
|![gift](../../../../static/img/integration/vision/gift/issueConfirmation.png)|![gift](../../../../static/img/integration/vision/gift/doneIssuedGift.png)              |
|:------------------------------------|:-----------------------------------------------------|

### 3. Check Issuance

To check completed issuances, **toggle on Issued Gift**s to display the latest issued gift.

|![gift](../../../../static/img/integration/vision/gift/gotoIssuedPage.png)|![gift](../../../../static/img/integration/vision/gift/checkIssuance.png)                  |
|:------------------------------------|:-----------------------------------------------------|


## Manage Gift

### 1. Gift Status 

|Active Gifts|Inactive Gifts |
|:--------------------------------|:---------------------------------|
|![gift](../../../../static/img/integration/vision/gift/activeGift.png)|![gift](../../../../static/img/integration/vision/gift/inactiveGift.png)|

|Propertise|Description|
|:--------------------------------|:--------------------------------|
|**1.0 Inactive Gifts Switch - Toggle Off**|Displays all active gifts.|
|**1.1 Deactivate**|Deactivate all currently selected active gifts|
|**1.2 Inactive Gifts Switch - Toggle On**|Displays all inactive gifts.|
|**1.3 Active**|Activate all currently selected inactive gifts|

### 2. Expired Gift

The activation will **fail** if the gift has expired. To activate the gift, the manager must [**update**](#2-update-gift-details) its **Redemption Validity End Date**.

|![gift](../../../../static/img/integration/vision/gift/expiredGift.png)|![gift](../../../../static/img/integration/vision/gift/activationFailed.png)                  |
|:------------------------------------|:-----------------------------------------------------|




