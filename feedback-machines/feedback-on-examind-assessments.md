---
icon: route
description: >-
  How students get Feedback Machine feedback on an EXAMIND Essay, Simulation,
  or File Upload assessment — linking the machine from your assessment, then
  the two checks that decide what students see and when.
---

# Feedback on EXAMIND Assessments

When a Feedback Machine grades an EXAMIND assessment, the detailed feedback lives in Feedback Machines, and students reach it from their **self review** of the attempt. Setting it up is one step in the EXAMIND Platform, followed by two checks — one in the machine, one in EXAMIND — that together decide what students see and when.

{% stepper %}
{% step %}
### Start from your assessment in the EXAMIND Platform

Open the Essay, Simulation, or File Upload assessment in the EXAMIND Platform and click **Link Feedback Machine**. You can pick a machine you already have, copy one, or create a new one — if this is your first time, you'll create it here. The first link in a course also asks which Feedback Machines class the course should use; see [The class behind a linked course](get-started.md#the-class-behind-a-linked-course).

Creating or copying a machine takes you into Feedback Machines to build it: your assignment instructions, your criteria, and the settings that control what students see. [Build a Feedback Machine](build-a-feedback-machine.md) walks through that. Back on the assessment, a status shows whether the machine's setup is **complete** or still needs finishing. Submissions made before setup is complete are held and graded once it is.
{% endstep %}

{% step %}
### Check what students will see in the machine

In the machine's **Configure & Publish** step, decide whether students get improvement feedback, final results after you approve, or both. Those settings are described in [What Students See](what-students-see.md). Two of them apply only to submissions arriving from EXAMIND:

* **Treat EXAMIND submissions as** — **Summative** keeps the machine from offering improvement suggestions on work already submitted for a grade.
* **Send grades to EXAMIND** — new machines hold the score until you approve the submission. The feedback itself doesn't wait: **See Feedback** opens as soon as the submission is evaluated.
{% endstep %}

{% step %}
### Open the Self Review window in EXAMIND

Students reach the feedback through the **See Feedback** button on their self review, and the self review only opens during an availability window you set. On the assessment's **Self Review** page, click **+ ADD AVAILABILITY** and set the dates — for everyone, or for particular sections or students. See [Self Review](../grade/self-review.md).

This is the step most often missed. Linking the machine doesn't open the review: until a window is open, students see a greyed-out **Review** button with the note "Disabled by your instructor", and there is no other route to the feedback from EXAMIND. The machine's settings in step 2 only take effect once this window exists.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
A window that opens before the assessment closes lets early finishers see their feedback while classmates are still working. Set the window to start after the assessment's last availability date unless that's what you want.
{% endhint %}

## What the student does

1. Opens the assessment where they launched it — the Canvas assignment, or the course's **Done** tab when signed in to EXAMIND directly.
2. Clicks **Review** on the completed attempt.
3. Clicks **See Feedback** in the review's header. Feedback Machines opens with their submission and shows whichever view the machine's settings allow: improvement feedback, final results, or a note that the work is awaiting review.

The machine's feedback usually appears within half an hour of the submission. Until then, the review shows the submission and your own grading, with no **See Feedback** button.

## If a student can't see their feedback

Check in this order:

1. **Is a Self Review window open for that student?** Look at the assessment's **Self Review** page. A window set for one section or student replaces the everyone-window for them, so check the window that applies to the student who's asking.
2. **Has the machine evaluated the submission?** Open the submission in Feedback Machines. If it isn't there, confirm the assessment still shows the machine as linked with setup **complete**, and that the attempt was submitted. A duplicated question doesn't keep its link.
3. **What does the machine let students see?** In [What Students See](what-students-see.md), a student access setting of **Never** on both views hides everything, and **After review & approval** shows results only once you approve. A student who reaches Feedback Machines and sees "awaiting review" is seeing exactly that setting.

{% hint style="info" %}
You can always open **See Feedback** yourself, from the instructor's view of the submission, whether or not a window is open. Only the student's access depends on the window.
{% endhint %}
