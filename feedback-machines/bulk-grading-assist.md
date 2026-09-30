---
icon: layer-group
description: >-
  Grade a whole class at once — upload a batch of submissions, let the machine
  evaluate them, and export the results.
---

# Bulk Grading Assist

Bulk Grading Assist lets you grade a whole class's work at once. You upload a batch of student submissions, the Feedback Machine evaluates each one against your criteria, and you review and export the scores and feedback.

{% hint style="info" %}
**Bulk Import** and **Bulk Export** are available to anyone who can manage the machine — its owner, and instructors in its class. They're no longer enabled per institution or class. If you don't see them on a machine, check that you're an instructor in the class it's shared with, or [contact us](mailto:support@examind.io).
{% endhint %}

## Grade a batch

{% stepper %}
{% step %}
### Start a bulk import

From your Feedback Machine's menu, select **Bulk Import**. Upload a **`.zip` containing your students' `.docx` and/or `.pdf` files** — each file becomes its own submission (only `.docx` and `.pdf` files are processed). A single import accepts up to **1 GiB** of files (with individual files up to 30 MB). Then select **Start Bulk Import**, and keep the browser tab open until all submissions are created.

{% hint style="info" %}
In Canvas, an assignment's **Download Submissions** option gives you a zip of student files you can upload directly. Feedback Machines recognizes the Canvas filename format and groups multiple files from the same student.
{% endhint %}
{% endstep %}

{% step %}
### Let it evaluate

Feedback Machines creates a submission for each file and evaluates it against your criteria. Evaluations run in the background — **up to 200 at a time** — so large batches process steadily without you waiting on each one; when the system isn't busy, a full class of around 1,000 submissions can finish in as little as an hour. You'll see live progress for each submission; any that fail are retried automatically, and you can retry remaining errors yourself.
{% endstep %}

{% step %}
### Review results

The import lists every submission with its score and status. Open any one to read its full feedback and criteria breakdown — including anything hidden from students. To read the batch by rubric part rather than one submission at a time, and to approve the grades, use the machine's [Results page](review-adjust-and-approve.md).
{% endstep %}

{% step %}
### Export

Open the export page with the import's **Export Results** button, or from the machine's menu under **Bulk Export** — both lead to the same page. It opens on your most recent import whenever that import is newer than any student submission. The **export scope** dropdown at the top sets which submissions are included: every submission, students only, each student's latest or highest-scoring submission, or one specific import listed under **By Import**. The page shows how many submissions the current scope will export.

Two exports are available for any scope:

* **Export Evaluations (CSV)** — one row per submission with its score, each rubric part's score and summary, the overall feedback summaries, and separate **First Name** and **Last Name** columns alongside each submitter's email. Use it for your own records and analysis. Canvas can't import it into the gradebook: it doesn't carry the Canvas student IDs and SIS columns that Canvas matches on.
* **Export Submissions (ZIP)** — the original student files.

Two more appear only when the scope is a Canvas import:

* **Export Scores for Canvas Gradebook** — in Canvas, export your gradebook (**Actions**, then **Export**) and upload that CSV here. Feedback Machines adds a score column and gives you a file that imports straight back in (**Actions**, then **Import**). The upload is needed because Canvas requires the SIS columns from your export, which Feedback Machines doesn't store. Skip the upload and you get a simple CSV of Canvas student ID and score to merge yourself.
* **Export Feedback for Canvas SpeedGrader** — a zip with one feedback PDF per submission (strengths, areas for development, suggestions for next time, and the rubric breakdown with part summaries), each named after the student's original file so you can attach it as a comment on their submission in SpeedGrader.

{% hint style="info" %}
Don't see the Canvas options? Check the scope dropdown — they're offered only while a Canvas import is selected under **By Import**.
{% endhint %}
{% endstep %}
{% endstepper %}

## Refine and re-evaluate

Bulk grading is iterative. As you review the results, you'll often spot evaluations you'd have graded differently — that's expected, and bringing the machine into agreement with your judgment is the core of the workflow. A few rounds is normal.

The place to do it is the machine's [Results page](review-adjust-and-approve.md). There you can read the whole batch by rubric part, pull the submissions you disagree with straight into the **Adjust** chat, preview the corrected evaluations, and apply the change across every submission at once — then approve. See [Review, Adjust & Approve Results](review-adjust-and-approve.md).

{% hint style="info" %}
You can also select **Re-evaluate All** from the import to re-run every submission against the current machine — useful after editing the machine directly in the [Modify panel](modifying-a-feedback-machine.md). Your original import and its results are preserved either way, so you can compare before and after.
{% endhint %}
