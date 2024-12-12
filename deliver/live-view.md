---
icon: server
description: This article shows you how to control logistics during a live assessment.
---

# Live View

## **What Is Live View?**

Live View is a feature within EXAMIND that gives instructors visibility into what his happening during an assessment in real time. Within Live View you can also force submit a student's assessment, add additional time, or re-open a student's previously submitted exam.

### Accessing Live View

1. Click Assessments in the left menu
2. Select the desired assessment
3. Select **Live View** in the left menu

### **Tab Views**

There are threes sections in Live View.

{% tabs %}
{% tab title="NOT STARTED" %}
This tab shows which student have not started their assessment.

#### Status Icons

<img src="../.gitbook/assets/Screenshot 2024-12-09 at 2.19.18 PM (1).png" alt="" data-size="line"> - The student has not arrived for their assessment

<img src="../.gitbook/assets/Screenshot 2024-12-09 at 2.22.13 PM.png" alt="" data-size="line"> - The student has arrived to the waiting room for this assessment
{% endtab %}

{% tab title="IN PROGRESS" %}
This tab shows which student have started, but not submitted their assessment.

#### Status Icons

<img src="../.gitbook/assets/Screenshot 2024-12-09 at 2.40.31 PM.png" alt="" data-size="line"> - The student is online and in the assessment

<img src="../.gitbook/assets/Screenshot 2024-12-09 at 2.42.55 PM.png" alt="" data-size="line"> - The student is either offline or has left the assessment

{% hint style="info" %}
Live connection is accurate for \~95-99% of users. The remaining 1-5% may have settings or configurations on their machines that prevent live connection status from being monitored reliably.
{% endhint %}

#### On Hover

The following diagnostic information is available while hovering on the status icon:

* Browser
* Computer Type
* IP Address
* Location

{% hint style="info" %}
Instructors can also use this information to identify usual behavior
{% endhint %}
{% endtab %}

{% tab title="SUBMITTED" %}
This tab shows which student submissions have been completed.

#### Status Icons

<img src="../.gitbook/assets/Screenshot 2024-12-09 at 2.49.07 PM.png" alt="" data-size="line"> - The student submission has been finalized and they no longer have access

#### On Hover

Diagnostic information from each attempt is saved and available while hovering on the status icon:

* Browser
* Computer Type
* IP Address
* Location

{% hint style="info" %}
Instructors can also use this information to identify usual behavior
{% endhint %}
{% endtab %}
{% endtabs %}

## Live Control

There are two ways to access live view controls:

1. Click on the student name
2. Select multiple students and click Bulk Actions

### Pause/Unpause

Pausing an assessment will:

* Conceal the assessment from the student
* Stop the student's countdown timer
* Save and lock the student's progress

Unpausing an assessment will:

* Allow a student to continue where they left off
* Automatically extend the availability window

{% hint style="info" %}
Pausing is very effective during a fire drill. Simply select all students by clicking the checkbox in the table header, select pause and click save.
{% endhint %}

### Add Time

Adding time to an assessment will:

* Be recorded as extra time
* Extend the availability window automatically

### Force Submit

Forcing a submission will:

* End the countdown timer
* Save and submit the student's progress
* Notify the student

### Reopen Attempt

After an assessment has been submitted, it can be reopened in the Submitted tab of the live view. You can specify the time limit for the reopened attempt and the due date. The timer will begin when the student enters their assessment.

EXAMIND records each **Take** of an attempt in the Live View. Reopening an attempt creates a subsequent take, as seen below.

<figure><img src="../.gitbook/assets/Group 47.png" alt=""><figcaption></figcaption></figure>

### Bulk Actions

You can perform any of the above actions in bulk by selecting the checkboxes and clicking Bulk Actions.

