---
icon: calculator
description: How a Feedback Machine turns performance levels into a score.
---

# How Scoring Works

A Feedback Machine scoring capabilities are generally more flexible than most rubrics. It can support:

* Traditional point-based rubrics
* Check-style criteria that give feedback without changing the score
* Penalty-style rubrics with negative points
* Parts with minimum score floors

The combination of these capabilities allows Feedback Machines to be aligned with your preferred grading approach, even when a traditional rubric might not. 

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

If you modify questions or point values, the machine may **rebalance** points so a part's values stay consistent. When it does, it lets you know in the [Modify panel](modifying-a-feedback-machine.md). For example, if you have an assignment worth 50 points, and you increase the point value of one criterion from 10 to 15, the machine will automatically adjust the point values of the other criteria to maintain the total of 50 points. If you ever want to avoid this behavior, just clarify that you want to change the total points for the whole assignment or part.

