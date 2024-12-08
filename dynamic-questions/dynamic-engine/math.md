---
description: This article will teach you about the Math blocks in our Dynamic Engine.
---

# Math

## The Math Blocks

There are thirteen kinds of _math_ blocks you can use in the Dynamic Engine. This article focuses on the top six blocks that you will use:

1. Specific Number
2. Random Number
3. Random Fraction
4. Basic Equation
5. Sum of List
6. Round

### Math: Specific Number

The **specific** **number** block lets you specify a specific number. For example, the following blocks set the variable "number" to "100".

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-03%20at%205-31-06%20PM-png.png?width=123&#x26;height=76&#x26;name=Screen%20Shot%202024-06-03%20at%205-31-06%20PM-png.png" alt="" height="76" width="123"><figcaption></figcaption></figure>

### Math: Random Number

The **random number** block randomly generates a number between two numbers with specified increments. For example, the following blocks set the variable "number" to a random number between "0" and "100", in increments of "10".

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-03%20at%205-31-53%20PM-png.png?width=640&#x26;height=82&#x26;name=Screen%20Shot%202024-06-03%20at%205-31-53%20PM-png.png" alt="" height="82" width="640"><figcaption></figcaption></figure>

For further clarity, the above example would create a random number that could be 0, 10, 20... up to 100.

### Math: Basic Equation

The **basic equation** block lets you specify mathematical operations with specific numbers or variables. For example, the following blocks first set the variable "number" to a random number between 0 and 100, in increments of 10, and then using a **basic equation** block adds the number "1" to a new variable "new number".

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-03%20at%205-40-41%20PM-png.png?width=679&#x26;height=108&#x26;name=Screen%20Shot%202024-06-03%20at%205-40-41%20PM-png.png" alt="" height="108" width="679"><figcaption></figcaption></figure>

There are five mathematical operators within the dropdown menu of **basic equation** block:

* **x** multiplied by
* **÷** divided by
* **+** add to
* **-** subtract from
* **^** to the power of

You can nest multiple basic equation blocks inside of each other, creating a whole world of possibilities. For example, the following two basic equation blocks were combined to 1) double the variable "number" and 2) take it to the power of a 3.

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-03%20at%205-49-53%20PM-png.png?width=600&#x26;height=128&#x26;name=Screen%20Shot%202024-06-03%20at%205-49-53%20PM-png.png" alt="" height="128" width="600"><figcaption></figcaption></figure>

### Math: Sum of List

The **sum of list** block adds all the values in a list. It must be combined with a **list** block in order to work. For example, the following blocks set the variable "number" to 10, by adding the **specific number** blocks 2, 3 and 5 together.

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-03%20at%205-45-30%20PM-png.png?width=684&#x26;height=133&#x26;name=Screen%20Shot%202024-06-03%20at%205-45-30%20PM-png.png" alt="" height="133" width="684"><figcaption></figcaption></figure>

There are eight operators within the dropdown menu of this block:

* **sum:** add all values in a list together
* **min:** finds and returns the minimum value in a list
* **max:** finds and returns the maximum value in a list
* **average:** calculates the simple average value of a list
* **median:** finds and returns the median value in a list
* **modes:** finds and returns the mode(s) in a list
* **standard deviation:** calculates the standard deviation of a list
* **random item:** finds and returns a random value from a list

### Math: Round

The **round** block rounds a value to the nearest whole number. For example, the following blocks set the variable "number" to the value "3", by rounding 3.14159 down to 3.

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-03%20at%205-46-23%20PM-png.png?width=688&#x26;height=101&#x26;name=Screen%20Shot%202024-06-03%20at%205-46-23%20PM-png.png" alt="" height="101" width="688"><figcaption></figcaption></figure>

There are three operators within the dropdown menu of this block:

* **round:** rounds to the nearest whole number
* **round up:** rounds up to the nearest whole number
* **round down:** rounds down to the nearest whole number

{% hint style="info" %}
If you want to round to a specific number of decimal places, you'll need to multiply by 10, round, then divide by 10.
{% endhint %}

***

## Example Question

Consider the following Multiple Choice question in EXAMIND:

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-05 at 4.42.41 PM.png" alt=""><figcaption></figcaption></figure>

The goal of this question is to change the data for each student.\
\
Here is what the Dynamic Engine would look like:

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-05 at 4.46.25 PM.png" alt=""><figcaption></figcaption></figure>

What's happening here is that the Dynamic Engine is generating 3 random numbers within specified limits, it then creates three answer options, two of which are functional distractors with those random numbers.\
\
Here is what the sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-05 at 4.47.43 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
EXAMIND's dynamic engine will never allow two choices to be identical for answer choices in an exam question
{% endhint %}
