---
icon: route
description: >-
  How students get Feedback Machine feedback on an EXAMIND Essay, Simulation,
  or File Upload assessment — the three things you set up, and what to check
  when a student can't see it.
---

# Feedback on EXAMIND Assessments

When a Feedback Machine grades an EXAMIND assessment, the detailed feedback lives in Feedback Machines, and students reach it from their **self review** of the attempt. Three things have to be in place before a student can see it:

1. A **Feedback Machine** with student access configured.
2. The machine **linked** to the assessment.
3. A **Self Review availability window** on the assessment.

The third one is the one most often missed. Linking a machine does not open the review: until you add a window, students see a greyed-out **Review** button and never reach **See Feedback**, however the machine is configured.

{% stepper %}
{% step %}
### Build the machine and decide what students see

[Build a Feedback Machine](build-a-feedback-machine.md) from your assignment instructions and criteria, then set its student-facing views in the **Configure & Publish** step — whether students get improvement feedback, final results after you approve, or both. Those settings are described in [What Students See](what-students-see.md).

Two settings there apply only to EXAMIND submissions and are worth deciding up front:

* **Treat EXAMIND submissions as** — **Summative** keeps the machine from offering improvement suggestions on work already submitted for a grade.
* **Send grades to EXAMIND** — new machines hold the score until you approve the submission. The feedback itself doesn't wait: **See Feedback** opens as soon as the submission is evaluated.
{% endstep %}

{% step %}
### Link the machine from the assessment builder

Open the assessment in the builder and select **Link Feedback Machine** in its **Feedback Machine** section. The step is the same for [Essay](../build/assessments/essay-assessments.md), [Simulation](../build/assessments/simulation-assessments.md), and [File Upload](../build/assessments/file-upload-assessments.md) assessments. The first link in a course also asks which Feedback Machines class the course should use — see [The class behind a linked course](get-started.md#the-class-behind-a-linked-course).

Once linked, a status shows whether the machine's setup is **complete**. Submissions made before setup is complete are held and graded once it is.
{% endstep %}

{% step %}
### Open a Self Review window

In the assessment's **Self Review** page, click **+ ADD AVAILABILITY** and set the dates during which students may open their review — for everyone, or for particular sections or students. See [Self Review](../grade/self-review.md).

This is what releases the feedback. Inside the window, the **Review** button on the student's completed attempt is enabled and the review's header shows **See Feedback** once the machine has evaluated the submission. Outside it, the button is greyed out with the note "Disabled by your instructor", and there is no other route to the feedback from EXAMIND.
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
