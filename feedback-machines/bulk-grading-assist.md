---
icon: layer-group
description: >-
  Grade a whole class at once — upload a batch of submissions, let the machine
  evaluate them, and export the results.
---

# Bulk Grading Assist

Bulk Grading Assist lets you grade a whole class's work at once. You upload a batch of student submissions, the Feedback Machine evaluates each one against your criteria, and you review and export the scores and feedback.

{% hint style="info" %}
Bulk Grading Assist is enabled per institution and class. If you don't see **Bulk Import** on your machine, [contact us](mailto:support@examind.io).
{% endhint %}

## Grade a batch

{% stepper %}
{% step %}
### Start a bulk import

From your Feedback Machine's menu, select **Bulk Import**. Upload a **`.zip` containing your students' `.docx` and/or `.pdf` files** — each file becomes its own submission (only `.docx` and `.pdf` files are processed). Then select **Start Bulk Import**, and keep the browser tab open until all submissions are created.

{% hint style="info" %}
In Canvas, an assignment's **Download Submissions** option gives you a zip of student files you can upload directly. Feedback Machines recognizes the Canvas filename format and groups multiple files from the same student.
{% endhint %}
{% endstep %}

{% step %}
### Let it evaluate

Feedback Machines creates a submission for each file and evaluates it against your criteria. You'll see live progress for each submission; any that fail are retried automatically, and you can retry remaining errors yourself.
{% endstep %}

{% step %}
### Review results

The import lists every submission with its score and status. Open any one to read its full feedback and criteria breakdown — the same view a student would see.
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

## Refine and re-evaluate

Bulk grading is iterative. As you review the results, you'll often spot evaluations you'd have graded differently — that's expected, and it's easy to correct:

1. **Spot a discrepancy.** While reviewing the grading results, note any evaluation you don't agree with.
2. **Explain it to the machine.** Open the [Modify panel](modifying-a-feedback-machine.md) and describe the discrepancy — for example, adjust a question, change point values, or add an instructor note clarifying how that case should be handled.
3. **Re-evaluate.** Come back to the import and select **Re-evaluate All** to re-run every submission against the updated machine.

Your original import and its results are preserved, so you can compare before and after.

{% hint style="info" %}
This review → refine → re-evaluate loop is the core of bulk grading. A few rounds is normal — it's how you bring the machine into agreement with your judgment.
{% endhint %}
