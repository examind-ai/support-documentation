---
icon: calculator
description: How a Feedback Machine turns performance levels into a score.
---

# How Scoring Works

A Feedback Machine scores work the way a rubric does — it judges each criterion, then adds the results up.

## The structure

* A machine is organized into **parts** — groups of related criteria.
* Each part has one or more **questions** — the individual things being evaluated.
* Each question has **performance levels** (from lowest to highest), and each level is worth a number of **points**.

## How a score is calculated

1. For each **question**, the AI selects the one performance level that best matches the submission, and awards that level's points.
2. Each **part's** score is the sum of its questions' points.
3. The **overall score** is the sum of the part scores. The maximum possible is the sum of the parts' maximums.

### Points floor

A part can have a **points floor** — a minimum it won't drop below. If the questions in that part sum to less than the floor, the student receives the floor instead.

### Deductions and check-style levels

* A level can be worth **negative points**, which acts as a deduction — useful for penalty-style rubrics.
* A level can be worth **zero points** — useful for check-style criteria that give feedback without changing the score.

### After you change points

If you modify questions or point values, the machine may **rebalance** points so a part's values stay consistent. When it does, it lets you know in the [Modify panel](modifying-a-feedback-machine.md).

## Example

| Part | Question | Earned |
| --- | --- | --- |
| **Content** (20 pts) | Clarity of argument (max 10) | 10 |
| | Use of evidence (max 10) | 5 |
| | **Part score** | **15** |
| **Writing** (10 pts) | Mechanics (max 10) | 10 |
| | **Part score** | **10** |
| **Analysis** (10 pts, 5-pt floor) | Depth of analysis (max 10) | 0 → floor |
| | **Part score** | **5** |

**Overall: 15 + 10 + 5 = 30 out of 40.** The Analysis part summed to 0, but its 5-point floor applied.
