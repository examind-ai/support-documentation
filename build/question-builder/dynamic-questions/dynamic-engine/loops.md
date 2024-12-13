---
description: This article will teach you about the Loops blocks in our Dynamic Engine.
---

# Loops

## Intro to Loops

A loop is a sequence of blocks which is specified once but which may be executed several times in succession. These structures are called loops since the blocks inside the loop (the _body_ of the loop) is repeated multiple times, reminiscent of a rope containing loops. Each pass through the loop is called an iteration.

{% hint style="info" %}
For more information on Loops, read this [Wikipedia page](https://en.wikipedia.org/wiki/Control_flow#Loops).
{% endhint %}

## The Loops Blocks

There are four kinds of _loops_ blocks you can use in the Dynamic Engine, as well as a special _loop termination_ block that allows you to terminate (aka short circuit) a loop if a certain condition is met. The four _loops_ blocks are:

1. Repeat N Times
2. Repeat While/Until
3. Count With
4. For Each in List

The loop termination block is: Break Out or Continue With Next Iteration

### Loop: Repeat N times

The simplest repeat block runs the code in its body the specified number of times. For example, the following block will log "Hello!" ten times.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 1.42.33 PM.png" alt=""><figcaption></figcaption></figure>

### Loop: Repeat

The options for the **repeat** dropdown do the following:

* **While** - repeats _while_ the condition is _true_
* **Until** - repeats _until_ the condition is _true_

#### **Repeat While:**

The _Repeat While_ block repeats its body while some condition is _true_.  To determine whether a condition is _true_ or _false_, [_Logic Blocks_](logic.md) need to be used. In the following example, the _Repeat While_ block is used to assign 3 random numbers between 1 and 100 to a variable named _sorted list_, but continue doing that until those random numbers are sorted in ascending order.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 1.45.02 PM.png" alt=""><figcaption></figcaption></figure>

In the example above, it's uncertain how many times the body will be executed. It may execute once or hundreds of times, depending on when the while condition becomes _true_.\
\
The condition used in the above example is a little complicated, so it warrants further explanation. The first part of the condition, _not sorted list_, is required to enter the loop at least once when the _sorted list_ variable is not defined. The second part of the condition reads like this: _while sorted list is not ascending_. The first part and the second part are joined together with an _or_ condition, which results in the overall condition being _true_ if either of those conditional parts are _true_.

{% hint style="info" %}
For more information on Logic Blocks, see the [Logic Blocks Page](logic.md).
{% endhint %}

#### **Repeat Until:**

The _Repeat Until_ block is very similar to the _Repeat While_ block, except the condition is reversed. _Repeat While_ loops repeat their bodies _while_ some condition is true, while _Repeat Until_ loops repeat their bodies _until_ some condition is true. The following blocks are equivalent to the previous example because the loop continues until the sorted list variable is sorted in ascending order.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 1.51.32 PM.png" alt=""><figcaption></figcaption></figure>

### Loop: Count With

The _Count With_ block advances a variable from the first value to the second value by the increment amount (third value), running the body once for each value. For example, the following _Count With_ block assigns the value _0_ to the variable _i_ in the first loop, then assigns the value _2_ to the variable _i_ in the second loop, and so on. This block will log all even numbers from 0 to 10 in ascending order.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 1.54.15 PM.png" alt=""><figcaption></figcaption></figure>

Similarly, loops can go in reverse order. The following example will log all even numbers of 0 to 10 in descending order.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 1.54.27 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note that _Count With_ is called a [For Loop](https://en.wikipedia.org/wiki/For_loop) in most programming languages
{% endhint %}

### Loop: For Each in List

The _For Each in List_ block is similar to the _Count With_ block, except instead of giving the loop variable values in a numeric sequence, it uses the values from a list in turn. The following _For Each_ block logs each _color_ in the _colors_ list: "red", "green", "blue".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 1.58.29 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
For more information on For Each, read this [Wikipedia Page](https://en.wikipedia.org/wiki/Foreach)
{% endhint %}

### Loop: Break Out or Continue With Next Iteration

The _Break Out or Continue With Next Iteration_ blocks differ from other loops blocks, as they are loop termination blocks. They are meant to be used in conjunction with the other loops blocks.

#### **Break Out Block:**

The _Break Out_ block provides an [early exit from a loop](https://en.wikipedia.org/wiki/Control_flow#Early_exit_from_loops). The following example logs "red" on the first iteration and breaks out of the loop on the second iteration when the loop variable is equal to "green". The third item in the list is never reached.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 2.00.08 PM.png" alt=""><figcaption></figcaption></figure>

#### **Continue With Next Iteration Block:**

The _Continue With Next Iteration_ block causes the remaining code in the body to be skipped and for the next iteration of the loop to begin. The following example logs "red" on the first iteration of the loop. On the second iteration, the _Continue With Next Iteration_ block is run, skipping the logging of "green". On the final iteration, "blue" is logged.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 2.01.07 PM (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note that _Continue With Next Iteration_ is called [continue](https://en.wikipedia.org/wiki/Control_flow#Continuation_with_next_iteration) in most programming languages
{% endhint %}

***

## Example Question

Consider the following Fill-in-the-blank question in EXAMIND:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 2.52.08 PM.png" alt=""><figcaption></figcaption></figure>

The goal of this question is to create a simple question that doesn't have negative net income. Using a loop will ensure that the random numbers will only generate a positive net income.\
\
Here is what the Dynamic Engine would look like:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 2.52.23 PM.png" alt=""><figcaption></figcaption></figure>

Loops are very handy when you want to add some control to the randomized scenarios. In this case, no student will ever receive a question where net income is not above $0.

Here is what a sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 2.52.34 PM.png" alt=""><figcaption></figcaption></figure>
