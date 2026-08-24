---
description: >-
  An open-response assessment where students write in the essay room and you
  grade it yourself.
---

# Essay Assessments

An **Essay** assessment is a single open-response question. The student writes their answer in the **essay room** — a simple in-browser editor — and you grade it yourself, or link a [Feedback Machine](../../feedback-machines/get-started.md) to auto-grade it against your criteria. An optional [AI assistant](#the-ai-assistant) can help the student *while they write*; it doesn't grade their work.

## The essay room

The essay room is a straightforward writing editor with the basics:

* **Basic formatting** — bold, italic, underline, and text alignment, plus undo/redo. It's intentionally simple: there are no lists, headings, links, or images.
* **A live word count** against the limit you set; it turns red if the student goes over.
* **Time remaining**, with the student's work **auto-saved** as they go.

## The AI assistant

Alongside the editor, students can chat with an **AI assistant** as they work — to think through ideas, get unstuck, or ask questions about the task. It supports the *process* of writing; **it does not grade the work**. It's on by default, and you stay in control of it:

* **Shape its role** with an **AI system message** — for example, a brainstorming partner, a Socratic tutor that asks questions instead of giving answers, or a subject-matter expert.
* **Turn it off** with **Hide Chat** if you'd rather students work without it.
* **Review the conversations** — a student's chats are saved with their submission, so you can see how they used the assistant when you grade.

## Create an essay assessment

When you build an assessment and choose the **Essay** type, you can configure:

{% stepper %}
{% step %}
### Points & word limit

Set the **points** the essay is worth and the **maximum word count** (default 100).
{% endstep %}

{% step %}
### Instructions

Enter the **instructions** shown to the student in the essay room.
{% endstep %}

{% step %}
### AI assistant (optional)

Leave the assistant on and shape it with an **AI system message** (and choose the **AI model**), or turn it off with **Hide Chat**.
{% endstep %}

{% step %}
### Feedback Machine (optional)

To auto-grade the essay, select **Link Feedback Machine** in the builder's **Feedback Machine** section and pick, copy, or create the machine that will evaluate it against your criteria. Once linked, a status shows whether setup is **complete** or still needs finishing. You build the machine's rubric and instructions in the [Feedback Machines](../../feedback-machines/build-a-feedback-machine.md) section.
{% endstep %}
{% endstepper %}

## Grading

You grade essays yourself, with optional Feedback Machine auto-grading:

* Assign **points** and write an **overall comment**.
* Add **inline annotations** on specific parts of the student's writing.
* Leave **comments on the AI chat**, where the assistant was used.
* If a **Feedback Machine** is linked, it auto-grades the essay against your criteria; a manual grade you enter always takes precedence. Once feedback is ready, a **See Feedback** button opens the detailed, criteria-aligned feedback in Feedback Machines — for you, and for students during their [self review](../../grade/self-review.md) window.

{% hint style="info" %}
Prefer to grade manually but still want AI help? You can copy a student's essay into a standalone [Feedback Machine](../../feedback-machines/get-started.md) and run it there, without linking it to the assessment.
{% endhint %}
