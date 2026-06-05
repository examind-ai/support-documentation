---
description: >-
  An AI-powered scenario where students interact with an AI and, optionally,
  reflect on it — and can be auto-graded by a Feedback Machine.
---

# Simulation Assessments

A **Simulation** assessment is an AI-powered, conversational scenario. The student works through an interactive exchange with an AI. It can also be **auto-graded** by a [Feedback Machine](../../feedback-machines/overview.md) (see below).

## How a simulation works

A simulation has up to two steps for the student:

1. **Interact** — the student has a conversation with the AI based on the scenario you set up.
2. **Reflect** *(optional)* — the student writes a reflection or response based on instructions you provide.

## Create a simulation assessment

When you build an assessment and choose the **Simulation** type, you can configure:

{% stepper %}
{% step %}
### Points & auto-grading

Set the **points** the simulation is worth. To auto-grade it, a **Feedback Machine** evaluates the student's work against a rubric. You build the Feedback Machine yourself (see the [Feedback Machines](../../feedback-machines/build-a-feedback-machine.md) section).

{% hint style="info" %}
**Linking is handled by EXAMIND for now.** You can set up and configure both the Simulation and the Feedback Machine on your own, but connecting the two currently requires us to set it up. Just [contact us](mailto:support@examind.io) and we'll link them.
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

* If a **Feedback Machine** is linked (see above), it auto-grades the interaction against its rubric.
* You can assign **points** and add an **overall comment**.
