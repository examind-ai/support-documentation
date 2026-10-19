---
description: >-
  How EXAMIND keeps your course roster in sync with your LMS — when a sync runs,
  and where section information comes from.
icon: people-group
coverY: 0
---

# Roster Sync

EXAMIND keeps your course roster in step with your LMS automatically. There is nothing to schedule and no button to press: the sync rides along with the launches your course is already doing.

## When a sync runs

A sync is queued when someone launches an **EXAMIND assessment** from your LMS course, and only if it has been more than **24 hours** since that course last synced.

Launches that aren't tied to an assessment — a course-navigation link, or the deep-link screen where you place an assessment — don't queue one. Students always arrive through an assessment, so a course in use stays current on its own.

## Section information

In **Canvas**, a sync brings section names in with the roster, so sections are filled in for the students the launched assessment is assigned to.

Other LMSs don't pass section names to the sync. There, sections arrive one member at a time: each student or instructor who launches into the course brings their own section with them, where the LMS is configured to pass it during the LTI handshake. Canvas fills its gaps the same way — a student the launched assessment wasn't assigned to gets their section on their own next launch.

{% hint style="info" %}
A sync never clears section information it couldn't read. A member whose sections the LMS didn't supply keeps whatever was recorded before.
{% endhint %}
