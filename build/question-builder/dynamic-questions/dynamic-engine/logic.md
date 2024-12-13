---
description: This article will teach you about the Logic blocks in our Dynamic Engine.
---

# Logic

## Intro to Boolean Logic

Boolean logic is a simple mathematical system that has two values:

* _true_
* _false_

This is a useful concept because it helps you to build conditional logic into your questions by looking for _true_ statements. For example, **if** the weather outside is currently raining, **then** it would be wise to bring an umbrella.

{% hint style="info" %}
For more information on Boolean Logic, read this [Wikipedia page](https://en.wikipedia.org/wiki/Boolean_algebra).
{% endhint %}



## The Logic Blocks

There are eight kinds of _logic_ blocks you can use in the Dynamic Engine. This article focuses on the top three blocks that you will use:

1. If Do
2. If Do Else
3. Comparison

### Logic: If Do

The **if do** block builds boolean logic into your question.

For example, the following blocks first set the variable "number" to a random whole number between 1 and 10. If the random number comes out as "5", then the variable "statement" will be "The random number is 5".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.09.04 PM.png" alt=""><figcaption></figcaption></figure>

There are a few things to note when you are using the **if do** block:

* The **if** part of the block requires you to specify what you want the engine to check for.
* The **do** part of the block will only happen when the **if** statement is _true_. It will not happen if the statement is **false**.
* You have a lot of freedom to make your question follow any logic. We recommend starting out small and then building from there.

#### Working with "Else If"

You can easily add more logic to the **if do** block by clicking "+". These new options will show up as **else if** and can be removed by clicking "-".

The **else if** option allows you to add more logic to the same **if do** block. This follows a principle called "order of operations", which means that the Dynamic Engine will move on if the logic is _false_ until it finds a statement which is _true._&#x20;

For example, the following **if do** checks to see if the number is "5", and if it is not "5", then the **else if** will check to see if the number is "6". If the number is not "6", then it simple won't do anything to the variable named "statement".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.11.26 PM.png" alt=""><figcaption></figcaption></figure>

You can add as many **else if** statements as you like,  but we recommend starting out simple before making things too complex.

### Logic: If Do Else

The **if do else** block is similar to the **if do** block, but forces the dynamic engine to do something if your logic comes out as _false._

For example, the following blocks first set the variable "number" to a random number between 1 and 10. If the random number comes out as "5", then the variable "statement" will be "The random number is 5". If the random number comes out as anything else, then the variable "statement" will be "The random number is **not** 5".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.12.35 PM.png" alt=""><figcaption></figcaption></figure>

As with the **if do** block, you can click "+" to add more **else if** logic to your block.

### Logic: Comparison

The **comparison** block looks like this:

<div data-full-width="false"><figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.17.27 PM.png" alt=""><figcaption></figcaption></figure></div>

Each **comparison** block compares two inputs and returns _true_ or _false,_ depending on how the inputs compare with each other.

There are six comparison operators within the dropdown menu of this block:

* **=** equal to
* **≠** not equal to
* **<** less than
* **≤** less than or equal to
* **>** greater than
* **≥** greater than or equal to

For example, if we look closely at the blocks you can see that the **comparison** block is highlighted in yellow. As described in the other sections above, this **comparison block** is comparing the variable "number" (which generates a random number) to the specific number "5".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.18.46 PM.png" alt=""><figcaption></figcaption></figure>

***

## Example Question

Consider the following Multiple Choice question in EXAMIND:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.30.13 PM.png" alt=""><figcaption></figcaption></figure>

The goal with this question is to use logic to change the question for each student.\
\
Here is what the Dynamic Engine would look like:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.27.24 PM.png" alt=""><figcaption></figcaption></figure>

What's happening here is that the logic is now altering the answer choices presented to students. The dynamic engine is checking to see if the random number is less than "0". If it is not, then it's check to see if it is greater than "0". It lastly checks to see if the random number is equal to "0". \
\
Here is what a sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 12.30.23 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
_Logic_ blocks are a very powerful way to increase the integrity of your questions. What we find is that students who are collaborating with each other in real time often miss the subtlety of questions that use _logic_ blocks. This results in the belief that they have the same question and can copy answers off each other.
{% endhint %}

