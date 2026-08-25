---
description: >-
  An AI-powered scenario where students interact with an AI and, optionally,
  reflect on it — and can be auto-graded by a Feedback Machine.
---

# Simulation Assessments

A **Simulation** assessment is an AI-powered, conversational scenario. The student works through an interactive exchange with an AI. It can also be **auto-graded** by a [Feedback Machine](../../feedback-machines/get-started.md) (see below).

## How a simulation works

A simulation has up to two steps for the student:

1. **Interact** — the student has a conversation with the AI based on the scenario you set up.
2. **Reflect** *(optional)* — the student writes a reflection or response based on instructions you provide.

## Create a simulation assessment

When you build an assessment and choose the **Simulation** type, you can configure:

{% stepper %}
{% step %}
### Points & auto-grading

Set the **points** the simulation is worth. To auto-grade it, link a **Feedback Machine** that evaluates the student's work against your criteria.

In the builder's **Feedback Machine** section, select **Link Feedback Machine** and pick, copy, or create the machine that will grade this simulation. Once it's linked, a status shows whether setup is **complete** or still needs finishing, and you can jump back into the machine anytime with **Open in Feedback Machines** / **Continue setup**. You build the machine's rubric and instructions in the [Feedback Machines](../../feedback-machines/build-a-feedback-machine.md) section.

{% hint style="info" %}
If a student submits before you've finished setting up the linked machine, EXAMIND **holds** their submission and grades it automatically once setup is complete — nothing is lost. If Feedback Machines isn't enabled for your institution yet, the control will prompt you to [contact us](mailto:support@examind.io).
{% endhint %}
{% endstep %}

{% step %}
### Instructions

Enter the **instructions** that set up the scenario for the student.
{% endstep %}

{% step %}
### The conversation (optional)

By default the student converses with an AI. You can shape it with an **AI system message** and **AI model**, or turn the chat off entirely with **Disable Chat**.
{% endstep %}

{% step %}
### Reflection step (optional)

Add **comment instructions** to give the student a second, written reflection step after the interaction.
{% endstep %}
{% endstepper %}

## Grading

A simulation combines optional AI auto-grading with your own judgment:

* If a **Feedback Machine** is linked (see above), it auto-grades the interaction against its criteria.
* You can assign **points** and add an **overall comment**.
* Once a linked machine has produced feedback, a **See Feedback** button appears on the review — for you, and for students during their [self review](../../grade/self-review.md) window — opening the detailed, criteria-aligned feedback in Feedback Machines.
