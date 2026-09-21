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

## The evaluation standard

Whenever a piece of work sits on the boundary between two performance levels, choosing one of them is a judgment call. The **evaluation standard** decides which of the two it earns:

* **Strict** — boundary work earns the lower level.
* **Generous** — boundary work earns the higher level, unless a required element of that level is clearly missing.

An [instructor note](modifying-a-feedback-machine.md) on a question takes precedence over both. Where your note says how to judge something, that's what the machine follows.

The effect is modest: in our testing, Generous raised total scores by roughly 1 to 7 percent — more on criteria that call for judgment, less on concrete ones — with no loss of consistency.

### Setting it

The **Evaluation Standard** card in the machine's **Configure & Publish** step has two switches:

| Switch | What it does |
| --- | --- |
| **Default standard** | Strict or Generous, applied to every submission the machine evaluates. |
| **Final submissions** | Applies the Generous standard to submissions designated **summative**, leaving drafts on the default. It's unavailable when the default is already Generous, which covers everything. |

**Summative** here is the designation a submission carries, not your approval of it: it's what the machine's **Treat EXAMIND submissions as** setting stamps on work arriving from a linked EXAMIND assessment — see [What Students See](what-students-see.md#submissions-that-come-from-examind). Approving a submission doesn't change the standard it was evaluated under.

New machines start on the recommended pairing: **Strict** as the default with **Generous** for final submissions. Drafts get the push to keep improving, while the grade of record resolves a close call in the student's favor. Machines created before the setting existed evaluate everything to the Strict standard until you change them.

Changing the standard applies to evaluations from then on; work that's already been graded isn't re-evaluated.

