---
description: >-
  This page explains how to deploy EXAMIND's Excel Add-in to students using
  Microsoft 365 Centralized Deployment for seamless assessment integration.
icon: file-excel
---

# Excel Integration

## Deployment Strategy Overview

Deploy the EXAMIND Add-in directly from AppSource using [Microsoft 365 Centralized Deployment](https://learn.microsoft.com/en-us/microsoft-365/admin/manage/centralized-deployment-of-add-ins?view=o365-worldwide) to student groups enrolled in courses requiring the add-in. This approach creates an "Admin Managed" tab in Excel, making the add-in automatically available without requiring student installation.

## [Deployment Steps](https://learn.microsoft.com/en-us/microsoft-365/admin/manage/manage-deployment-of-add-ins?view=o365-worldwide)

1. Access Microsoft 365 Admin Center
   1. Navigate to Settings > Integrated apps
   2. Search for "EXAMIND" in AppSource
2. Configure Group-Based Deployment
   1. Select the EXAMIND add-in
   2. Assign the add-in to "Specific users / groups"
   3. Select appropriate student groups for courses using EXAMIND
   4. Set deployment method to "Fixed (Default)" for automatic installation

## Group Management

**Target appropriate groups** such as:

* Course-specific groups (most precise)
* Program or department groups (broader coverage)

{% hint style="success" %}
**Recommendation:** Set up dynamic groups that automatically update based on course enrollment. This ensures students gain access when they enroll and lose access when they drop, reducing administrative overhead and maintaining precise targeting.
{% endhint %}

## Student Access

After deployment, students find the add-in in Excel under: **Home > Add-ins > More Add-ins > Admin Managed tab**
