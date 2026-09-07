---
icon: circle-check
description: >-
  Review a machine's evaluations on the Results page, adjust the criteria from
  real submissions, and approve the grades your students see.
---

# Review, Adjust & Approve Results

The **Results** page is where you check the machine's work before it becomes a grade. You can see the whole class at once, drill into any single submission, correct anything you'd have graded differently, and then approve — which is what releases the final result to the student.

Open a machine's **⋮** menu and choose **Results**.

{% hint style="info" %}
Results is available to anyone who can manage the machine — its owner, and instructors in its class. It's no longer enabled per institution.
{% endhint %}

## See the whole class

The Results page opens on a **Heatmap**: one row per student, one column per rubric part, so you can read the class by part rather than one submission at a time. A part where most of the class scored low is usually a problem with the criterion or the assignment — not with thirty students.

* **Heatmap / Overview** — switch between the grid and an **Overview** with the score distribution.
* **Scope** — choose which submissions to read: the class, or a particular [bulk import](bulk-grading-assist.md) set.
* **Display** — show each cell as **Score**, **Percent**, or **Score / Total**.
* Select a part's header to sort by that part, lowest scorers first.

Selecting a part's cell expands a drill-down in place, so you can read that part's detail — and edit its summary — without leaving the class view.

If the page is empty, the machine has nothing to show results for yet. A machine that isn't part of a class has no student submissions to grade: add it to a class so students can submit to it, or [import submissions](bulk-grading-assist.md) from the machine menu.

### Final submissions awaiting review

When submissions are graded but not yet approved, the Heatmap shows a **N awaiting review** count. Those students are seeing a *pending* state until you approve, so this count is a queue to work through, not a statistic.

## Review one submission

Select a student's name to open their submission in a three-pane workspace:

* **Submission** — their original work.
* **Evaluation** — the rubric: each part with its score and written summary, and (when you expand a part) the criterion-by-criterion evaluation with the machine's reasoning.
* **Adjust** — a chat for correcting this evaluation.

Selecting a criterion's locate control scrolls the Submission pane to the exact spot in the student's work that the criterion refers to, so you can check the machine's reasoning against the evidence instead of taking it on faith.

{% hint style="info" %}
A chip in the Evaluation pane header tells you whether the criterion-level detail you're reading — **Detail visible to students** or **Detail hidden from students** — actually reaches the student, so you know where your review effort lands. See [What Students See](what-students-see.md).
{% endhint %}

## Adjust the machine from real submissions

**Adjust** and the [Modify panel](modifying-a-feedback-machine.md) both change the underlying machine, and both change how it grades from then on. The difference isn't permanence — it's context. Modify works from your description alone. Adjust works from the evidence: you pull specific submissions and evaluations into the conversation, so the AI can reason about the actual differences between real pieces of student work.

That's what makes a nuanced correction possible. You can say:

> Alice should be scoring higher for concept mastery and Joel should be scoring lower — they were told to do X in our lecture.

and the machine examines what Alice and Joel actually wrote, works out what distinguishes them, and updates the criteria to reflect your intent.

### How a change lands

{% stepper %}
{% step %}
### Point the AI at the evidence

Select the **wand** icon on any part or question to inject it into the Adjust chat as a reference. Add as many as you need — several criteria, or the same criterion across several students — so the AI is reasoning about specific evaluations rather than a general description.
{% endstep %}

{% step %}
### Describe the change

Explain what should be different and why, in plain language. Context the machine can't infer — what you told the class in lecture, how you weigh a trade-off — is exactly what's worth saying.
{% endstep %}

{% step %}
### Review the preview

The machine proposes updated evaluations and shows them to you before anything is committed. Compare the proposed result against the current one.
{% endstep %}

{% step %}
### Accept, and it re-grades the class

Accepting commits the change to the machine and re-evaluates the affected criteria across every submission in the set — not just the ones you referenced. Criteria the change didn't touch are left alone. You can revert a committed change from its history.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
**Criteria apply to the whole class.** A Feedback Machine has one set of criteria, so an adjustment changes grading for everyone. You cannot currently hold one student to different criteria than another — and you wouldn't want to: the point of adjusting from real submissions is to make the *shared* criteria express your intent more precisely.
{% endhint %}

### Edit the words students will read

Two pieces of the evaluation are written prose you can rewrite directly:

* **Key takeaways** — the lessons the student should carry forward, shown with their final results. Select **Edit**, and your version is what students see. It's attributed to you in the student's view.
* **Part summaries** — the short paragraph under each rubric part that justifies its score. Edit any of them the same way.

Your edits are yours: they survive re-evaluation, an applied Adjust change, and a revert — the machine never overwrites them. The edited text is also what leaves the system, so it's what appears in the [detailed CSV and Canvas feedback exports](bulk-grading-assist.md) and in the results sent back to a linked EXAMIND assessment.

{% hint style="success" %}
**Part summaries are the reviewable-sized justification.** Reading every criterion row for every student doesn't scale; reading one summary per part does. That's why summaries reach students even when the detailed breakdown is turned off — the grade stays defensible without publishing all of the reasoning.
{% endhint %}

## Approve

Approving is the act that makes a result final.

{% stepper %}
{% step %}
### Approve a submission

In the review workspace, select **Approve**. The button then reads **Approved**; select it again to un-approve.
{% endstep %}

{% step %}
### Or approve in bulk

From the Heatmap, select the students you want — then **Approve** (or **Unapprove**) the whole selection at once.
{% endstep %}

{% step %}
### The student's view flips

An approved result carries **Reviewed and approved by** your name and the date, so students see a human decision rather than a machine output. If the machine's feedback access is **Until approved**, the formative feedback on that submission gives way to the final results.
{% endstep %}
{% endstepper %}

Un-approving reverts the student's view immediately, so a mistaken approval is not permanent.

{% hint style="warning" %}
Approving does **not** reveal results if the machine's Summative Evaluation View access is set to **Never** — in that case approval is for your records and your LMS. See [What Students See](what-students-see.md).
{% endhint %}

## How much reviewing is enough?

That depends on how well the machine already matches your judgment, and it changes over time. There are two established workflows:

<table data-view="cards"><thead><tr><th></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td><strong>Human-in-the-loop</strong></td><td>Review every submission and add your own comments. Use it to align a new machine, and where a personal touch matters.</td><td><a href="human-in-the-loop.md">human-in-the-loop.md</a></td></tr><tr><td><strong>Human-on-the-loop</strong></td><td>Spot-check and look for class-wide patterns. Use it once a machine has proven itself aligned.</td><td><a href="human-on-the-loop.md">human-on-the-loop.md</a></td></tr></tbody></table>

## Grading a whole class from a batch of files

If your students' work isn't in Feedback Machines yet — you have a folder of files, or a Canvas submissions download — start with [Bulk Grading Assist](bulk-grading-assist.md) to create the submissions, then come back here to review and approve them.
