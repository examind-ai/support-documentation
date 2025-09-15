---
description: >-
  This page explains how to allow an institutions' students to install and use
  EXAMIND's Excel Add-in as part of their assessments.
---

# Excel Integration

### Terminology

Microsoft AppSource is the official name for Microsoft's marketplace where Office add-ins are distributed. However, Microsoft's admin interfaces and documentation still frequently use the legacy term "Office Store." These terms refer to the same service and can be used interchangeably, but we will use "Microsoft AppSource" for consistency throughout this documentation.

### Grant Users Access to Microsoft AppSource

Follow the first 3 steps in  [this Microsoft documentation](https://learn.microsoft.com/en-us/microsoft-365/admin/manage/manage-addins-in-the-admin-center?view=o365-worldwide#manage-add-in-downloads-by-turning-onoff-appsource-across-all-apps-except-outlook) to grant users access to Microsoft AppSource. When configuring access permissions, you'll see the following 3 user groups:

* [x] Faculty, staff and other non-student users
* [x] Adult student
* [x] Non-adult student

{% hint style="danger" %}
Ensure that the appropriate student groups are enabled based on your institution's user base. Students who enroll in courses using EXAMIND's Add-in must have access to Microsoft AppSource. If your institution has students enrolling and unenrolling throughout the term, permission granting must be automated to prevent students from being locked out of their assessments, which could cause significant stress during exam periods.
{% endhint %}
