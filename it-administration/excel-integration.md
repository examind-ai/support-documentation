---
description: >-
  This page explains how to centrally grant students access to use EXAMIND's
  Excel Add-in as part of their assessments.
icon: file-excel
---

# Excel Integration

## Deployment Strategy Overview

Deploy the EXAMIND Add-in directly from AppSource using Microsoft 365 Centralized Deployment to student groups enrolled in courses requiring the add-in. This approach creates an "Admin Managed" tab in Excel, making the add-in automatically available without requiring student installation.

## Deployment Steps

1. Access Microsoft 365 Admin Center
   1. Navigate to Settings > Integrated apps
   2. Search for "EXAMIND" in AppSource
2. Configure Group-Based Deployment
   1. Select the EXAMIND add-in
   2. Choose "Assign to groups"
   3. Select appropriate student groups for courses using EXAMIND
   4. Set deployment as "Required" for automatic installation

## Group Management

**Target appropriate groups** such as:

* Course-specific groups (most precise)
* Program or department groups (broader coverage)

{% hint style="success" %}
**Recommendation:** Set up dynamic groups that automatically update based on course enrollment. This ensures students gain access when they enroll and lose access when they drop, reducing administrative overhead and maintaining precise targeting.
{% endhint %}

## Student Access

After deployment, students find the add-in in Excel under: **Home > Add-ins > More Add-ins > Admin Managed tab**
