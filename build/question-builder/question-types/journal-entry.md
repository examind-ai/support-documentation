---
description: This article shows you how to build a Journal Entry question in EXAMIND
---

# Journal Entry

## Overview

A Journal Entry Question asks students to record accounting transactions in a general ledger format. The student is required to specify which accounts are debited, which are credited, and the corresponding amounts.

### Why Use It

This question type is effective for developing practical bookkeeping skills and reinforce their understanding of fundamental accounting principles. They encourage learners to think critically about how transactions affect the accounting equation (Assets = Liabilities + Equity) and ensure that they understand the rationale behind debits and credits.

* Encourages application of theoretical accounting principles to realistic scenarios.
* Reinforces accuracy, attention to detail, and logical reasoning in financial record-keeping.
* Prepares students for more advanced topics and professional accounting tasks.

{% hint style="info" %}
EXAMIND provides full autograding with partial credit on Journal Entry questions.
{% endhint %}

### Use Cases

* **Introductory Accounting:** Practice classifying transactions into the correct accounts.
* **Intermediate/Advanced Accounting:** Apply accrued and deferred adjustments, recognize revenue/expenses, or record complex financial events.
* **Exam or Homework Assignments:** Assess students’ mastery of the double-entry accounting system.

## Create and Configure

{% stepper %}
{% step %}
### Write Your Question Stem

<figure><img src="../../../.gitbook/assets/d3e1b67c-ee57-433d-9b69-2c05eca1ff98.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Add Matching Block

<figure><img src="../../../.gitbook/assets/eb38e90f-ce77-493f-93c8-c5762d362a2e.gif" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Add Accounts, Debits and Credits

<figure><img src="../../../.gitbook/assets/904ab03c-1e45-4654-83b3-82a6ab4c6df7.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Add Line Items

Use the + and x symbols to add more correct and incorrect alternatives. EXAMIND will only show one correct choice at a time.

<figure><img src="../../../.gitbook/assets/38c90294-1a35-4bfd-b096-1fedb5a16907.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Add Distractors

<figure><img src="../../../.gitbook/assets/7e56676f-dc6f-431c-96b5-f29dfa9ca109.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The list of accounts is presented alphabetically in a dropdown menu to students
{% endhint %}
{% endstep %}

{% step %}
### Configure Settings

{% hint style="info" %}
Remember to click **Update** to save your settings
{% endhint %}

<figure><img src="../../../.gitbook/assets/d04f72ce-533c-4c82-b317-658b010888dc.png" alt=""><figcaption></figcaption></figure>

**Points:** The default total point value for this question in an assessment

**Error Tolerance (%)**: Enter the specified percentage of error tolerance that you will allow the auto grader to accept.

**No Entry Required Correct**: Check this box if "No Entry Required" is the correct answer. You will need to provide at least two distractor accounts if this box is checked.

**No Entry Required Distractor**: By default the "No Entry Required" will appear as a distractor. If you accidentally deleted it, simply check the "No Entry Required Distractor" checkbox and it will reappear.


{% endstep %}

{% step %}
### Review and Test Autograder

The review tab provides a real-time autograder to help you see how points are awarded.

<figure><img src="../../../.gitbook/assets/8a5d97c0-1976-442c-b10c-3031f7d3ff81.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
We encourage you to review how points and error tolerance are treated with the autograder
{% endhint %}
{% endstep %}
{% endstepper %}

## Autograder Behavior

This autograder is the culmination of 25+ accounting professors and a AAA board member collectively agreeing on an objective approach to grading journal entry questions.

Each line item in this question type is based on a 3 points system:

* 1 point for the correct account
* 1 point for the correct debit/credit
* 1 point for the correct amount

{% hint style="info" %}
Partial points are only awarded if the student enters the correct account
{% endhint %}

### Examples

If the incorrect account is chosen, the student will receive a 0 out of 3 points for that given line item.

If the student enters the correct account and amount but wrong debit/credit, the student would receive 2 out of 3 points for that line item.

If the student enters the correct account but wrong amount and wrong position the student will receive 1 out of 3 points.

The total number of points (6) will be distributed across each line item. For example, if there are three line items worth a total of 6 points each line item will be worth a total of 6 points divided by 3 line items or 2 points each.

## Instructor Tips

### Ensuring Academic Integrity

* **Variations in Transactions:** Change the details or amounts for different student attempts.
* **Dynamic Questions:** Use a combination of independent and dependent variables.
* **Unique Scenarios:** Use a diverse set of transactions from multiple chapters or unit topics.
* **Limited Time Windows:** Give students a set amount of time to complete the question.

### Common Issues

* Students may reverse the debit and credit sides. Provide guidelines and reminders: “Debits on the left, Credits on the right.”
* Confusing Expense vs. Asset Accounts: Clarify which accounts represent assets acquired (e.g., supplies) versus expenses (e.g., when supplies are used).

### Best Practices

* Start with simple transactions and progress to more complex adjustments as the course advances.
* Encourage students to write down the accounting equation and think through the impact of each transaction before deciding on debits and credits.
