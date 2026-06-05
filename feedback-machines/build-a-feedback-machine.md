---
icon: wrench
description: >-
  Create a Feedback Machine in four steps — from assignment instructions to a
  published machine students can use.
---

# Build a Feedback Machine

Building a Feedback Machine is a four-step process: describe the assignment, set up a rubric, let the system generate the evaluation, then configure and publish. The builder walks you through each step in order.

{% stepper %}
{% step %}
### Assignment Instructions

Paste or type your assignment instructions. Feedback Machines reads them to understand the work being evaluated — the kind of submission expected (text, `.docx`, or `.pdf`), whether writing quality matters, and whether it's a group assignment.
{% endstep %}

{% step %}
### Rubric

Give your Feedback Machine a grading rubric. You have two options:

* **Import a Rubric** — paste an existing rubric in any format, and the system structures it for you.
* **Create a Rubric** — let Feedback Machines generate one. Use the optional **Rubric Preferences** field to direct it: the scoring system you want, point values, the criteria to emphasize, or the number of categories. Then select **Generate Rubric**.

A rubric is made of **Parts** (the criteria) and, within each part, **Levels** (performance tiers) with **point values**.
{% endstep %}

{% step %}
### Review and Modify Machine

Feedback Machines analyzes your assignment and rubric and generates the **evaluation questions** it will use to assess submissions — each with its own **performance levels** and points. This is the machine's grading logic, expressed as questions the AI can answer about each submission.

The machine review page shows the generated parts, questions, and performance levels. From here you can:

* **[Modify the machine](modifying-a-feedback-machine.md)** — change questions, adjust points, add instructor notes, and more, just by asking in plain language.
* **Resolve [content dependencies](content-dependencies.md)** — provide any external material a question refers to (like a case study or template) so the AI can evaluate it accurately.
* **Understand [how scoring works](how-scoring-works.md)** — so the points reflect how you grade.

You can refine anything here, before or after publishing.
{% endstep %}

{% step %}
### Configure & Publish

Name your machine and set how it behaves for students:

* **Points** — show or hide scores from students.
* **Rubric view** — show or hide the per-criterion rubric summary to students.
* **Machine details** — show how the machine evaluates always, only after a first submission, or never.
* **Sharing** — keep the machine **personal** (just you) or share it with a **class**.
* **Submission type** — text, `.docx`, or `.pdf`, and how many files a submission may include.

Publish when you're ready, and the machine becomes available for use.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**No rubric yet? You don't need one.** Use **Create a Rubric** with **Rubric Preferences** — describe the qualities that matter for your learning outcomes and Feedback Machines drafts a complete, criteria-based rubric you can review and adjust.
{% endhint %}

## Next step

[Deliver to Students →](deliver.md)
