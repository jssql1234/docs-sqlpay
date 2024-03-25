---
sidebar_position: 4
id: multi-level-approval
title: E Leave - Multi-Level Approval
description: A guide to setup multi level approval for E Leave
slug: /cloud/ELeave-Multi-levelApproval
tags: ["SQL Payroll", "Cloud", "E Leave", "Multi Level Approval"]
---

## Introduction

With turn on Multi-Level Approval, the leave which applied by staff required more than 1 manager to approve.

## SQL Payroll

1. **File** -> **Company Profile** -> **E Leave**

   Ticked if want to have Multi-Level approval for the leave

   ![1](../../static/img/cloud/multi-level/1.png)

2. **Maintain Employee** -> **Manager Tab**

   ![2](../../static/img/cloud/multi-level/2.png)

   ![2a](../../static/img/cloud/multi-level/2a.png)

## ELeave Apps

1. **Manager can Review only**

   - Allows to Verify the leave by **Can Review Manager**

      ![3](../../static/img/cloud/multi-level/3.png)

2. **Manager can Approve only**

   1. Unable to approve if haven’t verify(review) by manager

      ![4](../../static/img/cloud/multi-level/4.png)

   2. Once done Verify by Can Review Manager, allows to approve / reject the leave

      ![5](../../static/img/cloud/multi-level/5.png)

3. **Manager allows Review and Approve**

   1. Allow to approve without verify.

      ![6](../../static/img/cloud/multi-level/6.png)

   2. Allow to unapproved the leave

      ![7](../../static/img/cloud/multi-level/7.png)

   3. Allow to Unrejected the leave

      ![8](../../static/img/cloud/multi-level/8.png)

## In SQL Payroll

1. **Sync Cloud**

   1. Request = Leave is pending for Verify

      ![9](../../static/img/cloud/multi-level/9.png)

   2. Pending = Leave have done Verify by **Can review Manager**

      ![10](../../static/img/cloud/multi-level/10.png)

## Appendix

   ![11](../../static/img/cloud/multi-level/11.png)

   ![12](../../static/img/cloud/multi-level/12.png)

   ![13](../../static/img/cloud/multi-level/13.png)

   ![14](../../static/img/cloud/multi-level/14.png)
