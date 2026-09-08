---
icon: chart-simple
description: >-
  Spot-check a proven machine and read the class for patterns, instead of
  reviewing every submission individually.
---

# Human-on-the-loop

In a human-on-the-loop workflow you don't read every evaluation. You watch the class as a whole, spot-check a sample, and intervene where a pattern tells you something is off.

The unit of attention shifts from the student to the **criterion**. One student scoring low on a criterion is a student; most of the class scoring low on that criterion is usually the criterion, the assignment, or something that didn't land in the lecture.

## When to use it

Use it when the machine has earned it:

* **After a semester of [human-in-the-loop](human-in-the-loop.md) review** on the same assignment, where your corrections have already tightened the criteria.
* **When the machine has demonstrated aligned grading at scale** — your spot-checks keep agreeing with it.
* **When nothing material has changed** about the assignment, the rubric, or the course content.

If any of those isn't true, go back to [human-in-the-loop](human-in-the-loop.md) for a cycle. A machine that hasn't been aligned to your judgment hasn't earned this workflow.

## The workflow

{% stepper %}
{% step %}
### Read the class by criterion

Open the **Heatmap** on the [Results page](review-adjust-and-approve.md) — students down, rubric parts across. Scan the columns, not the rows. Select a part's header to sort by it and bring the lowest scorers together.

What you're looking for is a criterion that's out of step: graded too strictly, too leniently, or in a way that doesn't match what you meant by it.
{% endstep %}

{% step %}
### Expand a criterion to see how it was scored

Expand a part in place to see how its scores were derived across the whole class, without opening students one at a time. This is usually enough to tell a genuinely hard criterion from a misaligned one.
{% endstep %}

{% step %}
### Spot-check a sample

Open a handful of submissions across the score range — a strong one, a weak one, something in the middle. If your judgment keeps agreeing with the machine's, the pattern you're seeing is real. If it doesn't, you've found a misalignment.
{% endstep %}

{% step %}
### Adjust from several students at once

Use the wand controls (🪄) to pull evaluations from several students into the Adjust chat at once — hover a part's heading for its wand button, or use the **Adjust** button at the end of a question row — then describe what should be different. Giving the AI several students together lets it work out where the line between them actually falls.

Review the preview, accept, and the change re-grades the affected criteria across the class. See [Adjust the machine from real submissions](review-adjust-and-approve.md#adjust-the-machine-from-real-submissions).
{% endstep %}

{% step %}
### Approve in bulk

Select the students whose results you're releasing and approve them together from the Heatmap.
{% endstep %}
{% endstepper %}

## The trade-off

**What you gain:** accurate, consistent grading across the class, and a very large amount of your time back. Time that can go into giving students more practice opportunities — which is where the learning gain actually comes from.

**What you give up:** the personal touch. Nobody receives a comment written by you about their specific work. For some students in some courses that's a real loss, and worth weighing.

{% hint style="info" %}
The two workflows mix. A common pattern is on-the-loop for the class, dropping into [human-in-the-loop](human-in-the-loop.md) review for the students at the extremes — the struggling and the borderline — where an instructor's comment is worth the most.
{% endhint %}
