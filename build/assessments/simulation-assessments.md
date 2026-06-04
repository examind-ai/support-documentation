---
description: >-
  An AI-powered scenario where students interact with an AI and, optionally,
  reflect on it — and can be auto-graded by a Feedback Machine.
---

# Simulation Assessments

A **Simulation** assessment is an AI-powered, conversational scenario. The student works through an interactive exchange with an AI. You can optionally link a [Feedback Machine](../../feedback-machines/overview.md) to **auto-grade** the interaction against a rubric.

## How a simulation works

A simulation has up to two steps for the student:

1. **Interact** — the student has a conversation with the AI based on the scenario you set up.
2. **Reflect** *(optional)* — the student writes a reflection or response based on instructions you provide.

## Create a simulation assessment

When you build an assessment and choose the **Simulation** type, you can configure:

{% stepper %}
{% step %}
### Points & auto-grading

Set the **points** the simulation is worth. To auto-grade it, optionally link a **Feedback Machine** that will evaluate the student's work against a rubric. (Build one first in the [Feedback Machines](../../feedback-machines/build-a-feedback-machine.md) section.)
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

* If you link a **Feedback Machine**, it auto-grades the interaction against its rubric.
* You can assign **points** and add an **overall comment**.
