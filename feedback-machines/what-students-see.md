---
icon: eye
description: >-
  The two views a student can see — Feedback while they're drafting, Results
  once the grade is final — and the settings that control each.
---

# What Students See

A Feedback Machine shows a student two different things at two different moments, and you control each one separately:

* The **Feedback** view is for improving the next draft: strengths, areas for development, and specific suggestions in order of impact.
* The **Results** view is the grade of record: the final score, the key takeaways to carry forward, and the rubric parts with their scores.

Keeping these apart is what lets one machine serve both purposes — unlimited practice while the work is in progress, then a single authoritative result at the end.

{% hint style="info" %}
You always see everything, on every submission, regardless of these settings. They govern what **students** see. See [Review, Adjust & Approve Results](review-adjust-and-approve.md) for the reviewer's side.
{% endhint %}

## The settings

You set these in the machine's **Configure & Publish** step, and can change them anytime.

### Formative Feedback View

| Setting | Options |
| --- | --- |
| **Student access** | **Until approved** — feedback on every submission except one you've reviewed and approved, which shows only its final results. **Always** — feedback as soon as each submission is evaluated. **Never** — no feedback view. |
| **Show score estimates** | Off by default: students get feedback without numbers. On: estimated points and percentages appear with the feedback. |

### Summative Evaluation View

| Setting | Options |
| --- | --- |
| **Student access** | **After review & approval** — results appear once you approve. **Always** — results are available immediately after every submission. **Never** — students never see results here (you release grades in your LMS instead). |
| **Show detailed evaluation breakdown** | Off by default: students see each rubric part with its score and summary. On: they can also expand each part for the criterion-by-criterion evaluation and the reasoning behind each score. |

{% hint style="success" %}
**Turning details off doesn't hide the justification.** Even with the breakdown off, students still see every rubric part with its score *and* its written summary — enough to understand and trust the grade. What's hidden is the criterion-level reasoning underneath.
{% endhint %}

## Approval is the flip

For the common workflow — **Until approved** feedback plus **After review & approval** results — approval is the single moment that changes what a student sees:

1. **While drafting.** The student submits as often as they like and gets the Feedback view each time. No final score.
2. **You review and approve** their final submission (see [Review, Adjust & Approve Results](review-adjust-and-approve.md)).
3. **The student's view flips.** Feedback on that submission gives way to Results: the final score, key takeaways, and the rubric parts — with **Reviewed and approved by** *your name* and the date, so the grade reads as a human decision rather than a machine output.

Un-approving reverts the student's view immediately.

{% hint style="warning" %}
Approval never overrides **Never**. If the Summative Evaluation View's access is set to **Never**, approving a submission does not reveal results to the student — approval is for your records and your LMS. Approval decides *when* results appear, not *whether* they can.
{% endhint %}

## While a student is waiting

If a student has no Feedback view and no Results view yet — a final submission that's graded but not yet approved, for instance — they see a short message telling them their work is awaiting review, or that results will be released elsewhere. They never see an empty page or a partial score.

## Submissions that come from EXAMIND

When a machine is linked to an EXAMIND assessment ([Essay](../build/assessments/essay-assessments.md), [Simulation](../build/assessments/simulation-assessments.md), or [File Upload](../build/assessments/file-upload-assessments.md)), the Configure step adds one more control: **Treat EXAMIND submissions as**.

| Option | What it means |
| --- | --- |
| **Both** | Submissions from the linked assessment behave like any other submission (the default). |
| **Formative** | They get feedback only, and no final results — unless you approve one, which releases its results. |
| **Summative** | They are final submissions — no formative feedback; results appear per the access setting above. |

This matters because an EXAMIND assessment is usually a graded, one-shot submission, while the same machine may also be open for practice. **Summative** is how you keep a single machine from handing a student improvement suggestions on work they've already submitted for a grade.

{% hint style="info" %}
**Approving overrides a Formative designation.** Approving a formative-designated submission is a deliberate act that makes it summative and releases its results. What approval can't override is an access setting of **Never**.
{% endhint %}

{% hint style="info" %}
This setting appears only on machines linked to an EXAMIND assessment. Students reach this view through **See Feedback** on their EXAMIND [self review](../grade/self-review.md) — the detailed feedback and results live in Feedback Machines, not in EXAMIND.
{% endhint %}

## Backwards compatibility

These settings were introduced in September 2026, replacing the earlier **Points** and **Rubric view** switches.

Machines created before then continue to work exactly as they did. Their old choices map onto the new, more flexible settings automatically: feedback stays always-on, score estimates follow what Points was set to, and the results view follows Rubric view. Nothing changes for your students unless you change it yourself.

Machines created since start with the defaults above — feedback without numbers on every draft, and finality earned by review.
