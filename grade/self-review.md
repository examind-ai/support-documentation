---
icon: book
description: This article shows you how to let students review a submitted assessment, and what they see when they do.
---

# Self Review

Let students revisit a submitted attempt. You decide when the review is open; what students see inside it depends on the assessment type.

## Accessing Self Review

1. Click Assessments in the left menu
2. Click the desired assessment
3. Click **Self Review** in the left menu

## Availability Windows

Click **+ ADD AVAILABILITY** and enter the availability window for self review with start and end dates. The availability window can be set for everyone, by student, or by section.

{% hint style="info" %}
Click the **+ New** tab to add additional availability windows.&#x20;
{% endhint %}

{% hint style="warning" %}
A window that opens before the assessment closes lets early finishers see their results while others are still working. EXAMIND warns you when that is the case; open the review after the assessment's last availability date.
{% endhint %}

Practice assessments have no availability windows: students can review a practice attempt any time the practice itself is available.

## What Students See

### Exams and quizzes

Students see each question with their own answer and whether it was correct. Two **Review Settings** on each availability window control what else they see:

1. **Answer Key** shows the correct answer.
2. **Answer Explanation** shows the explanation for the correct answer, pulled from the Explanation field in the question builder.

{% hint style="info" %}
Toggle the settings to preview how students see each question type in their review.
{% endhint %}

The review shows the total score. Whether the score also appears on the student's list of completed attempts, before they open the review, is set by **Result Visibility** under the assessment's **Settings**; with it off, the list reads "Hidden".

### Practice

Practice needs no setup. Students always see their score and the answer key; explanations are not shown.

### Essays, simulations, and file uploads

These types have no review settings. Students see their submitted work together with your grading:

* **Essay**: the essay with your inline comments, a **Grading** tab with the points awarded and your overall comment, the AI chat history if the essay used the assistant, and a PDF download of the submission.
* **Simulation**: the full conversation with your comments on it, your overall comment, and a PDF download.
* **File upload**: the submitted files and a **Grading** tab with the points awarded and your overall comment.

If a [Feedback Machine](../feedback-machines/get-started.md) is linked to the assessment, a **See Feedback** button appears in the review's header once the machine's feedback is ready. It opens the student's detailed feedback in Feedback Machines; what they see there is [controlled in the machine](../feedback-machines/what-students-see.md). (A simulation question inside a quiz gets the same button beside the question.)

## How Students Get There

Students reach their review from the same place they launched the assessment.

**From Canvas or another LMS:**

1. Open the assignment in the LMS. The EXAMIND assessment page loads with two tables: **Available Attempts** and **Completed Attempts**.
2. In **Completed Attempts**, click **Review** on the attempt. The review opens in a new browser tab.

**Signed in to EXAMIND directly:** open the course, select the **Done** tab, and click **Review** in the **Available for Review** table.

The **Review** button is greyed out while the attempt is outside its availability window, with the tooltip "Disabled by your instructor". Adding a window enables it; ending one disables it again.

{% hint style="info" %}
For exams and quizzes, the grade posted to Canvas also carries a link: in Canvas Grades, the submission details show a **Review Results** button that opens the same review. Essay, simulation, and file upload assessments post a PDF of the results instead, so students reach those reviews through the assignment.
{% endhint %}
