---
description: This article shows you how to post grades to your LMS.
icon: memo-circle-check
---

# Post Grades

Send assessment grades from EXAMIND back to the linked assignment in your LMS gradebook.

## Accessing EXAMIND LTI Page

1. Navigate to the assessment in your LMS that is linked to EXAMIND
2. Click on **EXAMIND** assessment to load EXAMIND LTI page

## Exams, Quizzes, and Practices

### Post Grades

1. Click **Post Grades**
2. Choose between `New submissions only` and `All submissions`
3. Verify grades have been imported into your LMS

## Essays and Simulations

### Send Results

* Click **Send Results**
* Choose between `New submissions only` and `All submissions`
* Verify grades have been imported into your LMS

When sending essay and simulation results to Canvas, the system automatically uploads a PDF containing the student's complete results to SpeedGrader alongside the numerical grade.

{% hint style="warning" %}
**All submissions:** Updates all grades in the LMS for this assessment. This will override any manual adjustments made directly in the LMS with the grades stored in EXAMIND.

**New submissions only:** Sends grades only for students whose results have not yet been posted to the LMS, preserving any existing grades and manual adjustments.
{% endhint %}

{% hint style="info" %}
The score posted to the LMS is determined by the **Score to Keep** setting on the assessment. See [Schedule](../../deliver/schedule.md).
{% endhint %}

{% hint style="info" %}
In order to post grades to Canvas, the following conditions must be met:

* Course must have started
* Course cannot have ended
* Course must to be published (even if posting grades for `Test Student`)
* If posting grades using the `All submissions` option, each grade post counts as an attempt in Canvas, so ensure sufficient attempts are allowed in the Canvas assignment
{% endhint %}

## Automatically Post Grades

By default, EXAMIND keeps grades in EXAMIND until you post them yourself using the steps above, so that any adjustments you make directly in your LMS are never overwritten without your say-so. If you would rather not post grades by hand, you can have EXAMIND keep the LMS gradebook up to date for you.

In the assessment's **Settings**, under **LMS Integration**, turn on **Auto-post grades to LMS**. Once enabled, EXAMIND automatically sends grades for newly submitted attempts to the linked LMS gradebook, so you no longer need to click **Post Grades** after each round of submissions.

{% hint style="info" %}
* **Auto-post grades to LMS** is off until you turn it on, and you can enable it as soon as the assessment is set up. Grades begin posting automatically once the assessment has been opened from your LMS at least once (the launch that links it to its gradebook column); any submissions from before that point are sent automatically as soon as the link is in place.
* Auto-posting sends **new submissions only**, so grades you have already adjusted in the LMS are preserved.
* The score sent follows the assessment's **Score to Keep** setting, the same as a manual post.
{% endhint %}
