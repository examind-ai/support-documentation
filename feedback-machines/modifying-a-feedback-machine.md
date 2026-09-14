---
icon: pen-to-square
description: >-
  Refine your machine by asking the AI to change questions, points, notes, and
  more — in plain language.
---

# Modifying a Feedback Machine

You can refine a Feedback Machine at any time — before or after students use it — from the machine review page. Changes apply to **future** submissions; work that's already been evaluated isn't re-graded.

## The Modify panel

On the machine review page, the **Modify Feedback Machine** panel sits on the right. You can minimize it to a button in the corner and reopen it whenever you need it.

It works as a chat: type what you'd like to change in plain language in the **"Enter desired changes"** box and send it. The AI applies the change to your machine and replies explaining what it did. If it has to rebalance point values to keep a part's points consistent, it tells you.

## What you can change

Just ask. The AI can:

* **Add, remove, or edit** evaluation questions, parts, and performance levels.
* **Change point values** for a question, a part, or the whole machine.
* **Make bulk changes** across parts — for example, "reduce every part's maximum by 10 points."
* **Set a points floor** on a part, so a student can't score below a minimum for that group of questions.
* **Add instructor notes** to a question to clarify how it should be evaluated — an edge case or interpretation, for instance. *Notes are hidden from students.*
* **Merge** overlapping questions, or **split** a question that covers more than one criterion into separate ones.
* **Manage [content dependencies](content-dependencies.md)** — add one the system didn't detect (e.g., "this question depends on the case study"), or remove one.

{% hint style="info" %}
**Instructor notes are the best way to align the AI with your judgment.** If the machine misreads an edge case, add a note explaining how you'd grade it — for example, "Accept this if the student discusses X, even if they don't explicitly mention Y."
{% endhint %}

## Audit the machine for overlapping levels

Grading varies when two performance levels could both fit the same piece of work. **Audit MECE** on the machine review page checks every evaluation question for that problem — whether its levels are mutually exclusive (no work fits two) and collectively exhaustive (no work fits none).

Questions with a finding get a warning icon, and a banner tells you how many there are. Select an icon to see the question as it stands beside the suggested version — the wording, the levels and their points, and the question's instructor note — along with an explanation of the problem found. Accept the suggestion or dismiss it, one at a time or all at once.

Guidance meant for the grader stays in the instructor note rather than being folded into the question students read. Where a note and the levels disagree about how to judge something, the audit treats the note as your more specific intent and brings the levels in line with it — and says so in its explanation, so you can go the other way instead.

{% hint style="warning" %}
Audit MECE is a **beta** feature. Read each suggestion before accepting it.
{% endhint %}

## Restore a previous version

Every change is captured in the panel's chat history. To undo, click **restore this version** on an earlier AI message — the machine reverts to that point, and you can keep modifying from there.
