---
icon: layer-group
description: >-
  Grade a whole class at once — upload a batch of submissions, let the machine
  evaluate them, and export the results.
---

# Bulk Grading Assist

Bulk Grading Assist lets you grade a whole class's work at once. You upload a batch of student submissions, the Feedback Machine evaluates each one against your rubric, and you review and export the scores and feedback — instead of collecting drafts one at a time.

{% hint style="info" %}
Bulk Grading Assist is enabled per plan and class. If you don't see **Bulk Import** on your machine, [contact us](mailto:support@examind.io).
{% endhint %}

## Grade a batch

{% stepper %}
{% step %}
### Start a bulk import

From your machine, open **Bulk Imports** and select **Start Bulk Import**. Upload a **`.zip` file containing your students' `.docx` and/or `.pdf` submissions** — other file types in the zip are ignored.

{% hint style="info" %}
In Canvas, an assignment's **Download Submissions** option gives you a zip of student files you can upload directly. Feedback Machines recognizes the Canvas filename format and groups multiple files from the same student.
{% endhint %}
{% endstep %}

{% step %}
### Let it evaluate

Feedback Machines creates a submission for each file and evaluates it against your rubric. You'll see live progress for each submission; any that fail are retried automatically, and you can retry remaining errors yourself.
{% endstep %}

{% step %}
### Review results

The import lists every submission with its score and status. Open any one to read its full feedback and rubric breakdown — the same view a student would see.
{% endstep %}

{% step %}
### Export

Select **Export Results** to download:

* **Canvas gradebook** — scores as a CSV you can import into Canvas.
* **Feedback files** — a zip of per-student feedback.
* **Submissions** — a zip of the original student files.

You can export all students, or only each student's highest-scoring submission.
{% endstep %}
{% endstepper %}

## Re-evaluate after changes

If you update the machine's rubric or criteria, use **Re-evaluate All** to re-run every submission against the current version. The original import and its results are preserved.
