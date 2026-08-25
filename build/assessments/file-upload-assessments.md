---
description: >-
  An assessment where students upload completed work as PDF or Word files — you
  grade it yourself, or have a Feedback Machine auto-grade it.
---

# File Upload Assessments

A **File Upload** assessment is a drop box for work students complete **outside EXAMIND**. The student attaches one or more files — **PDF or Word (`.docx`)** — and submits. You grade the work yourself, or link a [Feedback Machine](../../feedback-machines/get-started.md) to auto-grade the uploaded files against your criteria.

Use it when the deliverable is a finished document — a report, a problem set, a case write-up, a presentation exported to PDF — rather than something answered inside the EXAMIND question interface.

## How it works for students

The student opens the assessment, reads your instructions, and uploads their files by clicking or dragging them onto the drop zone. They can attach multiple files if you allow it, and submit when ready. Because the work happens outside EXAMIND:

* **There's no time limit.** File Upload assessments are governed by the [availability window](../../deliver/schedule.md) — students work up to the due date. See [Schedule](../../deliver/schedule.md).
* **There's no waiting room.** When nothing gates entry, the student lands directly on the upload page instead of a start dialog.

{% hint style="info" %}
Submitting with **no file attached scores zero**. EXAMIND warns the student ("**No File Attached** — Submitting now will score zero.") but still lets them submit, so an empty submission is a deliberate choice, not an accident.
{% endhint %}

## Create a File Upload assessment

Choose the **File Upload** type when you create the assessment (it's available when you start from **+ Add Assessment** without preselecting questions). Then configure:

{% stepper %}
{% step %}
### Points

Set the **points** the assessment is worth (default 25).
{% endstep %}

{% step %}
### Max Files

Set **Max Files** to cap how many files a student can attach. Leave it blank for no limit.
{% endstep %}

{% step %}
### Max Size per File

Set **Max Size per File (MB)** to cap the size of each individual file. This is a per-file limit, not a total for the submission. Leave it blank for no limit.
{% endstep %}

{% step %}
### Allowed File Types

Under **Allowed File Types**, choose which formats students can upload — **PDF (.pdf)**, **Word (.docx)**, or both. At least one must stay selected.
{% endstep %}

{% step %}
### Feedback Machine (optional)

Link a **Feedback Machine** to auto-grade the uploaded files against your criteria. See [Grading](#grading) below.
{% endstep %}

{% step %}
### Instructions

Enter the **instructions** shown to the student — what to complete, and which files to attach.
{% endstep %}
{% endstepper %}

## Grading

File Upload assessments are **graded by you**, with optional Feedback Machine auto-grading:

* Assign **points** and write an **overall comment**.
* If a **Feedback Machine** is linked, it auto-grades the student's uploaded files (PDF and Word documents) against your criteria. A manual grade you enter always takes precedence.
* When you review a submission, each attached file appears as a card under **Submitted Files** — open or **Download** it to read the student's work.

{% hint style="info" %}
Feedback Machines grades **PDF and Word documents only**, which is why those are the file types the builder offers. See [Feedback Machines](../../feedback-machines/get-started.md) for what it evaluates and how to build one.
{% endhint %}
