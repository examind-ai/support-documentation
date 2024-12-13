---
description: This article will teach you about the Function blocks in our Dynamic Engine.
---

# Functions

## What is a Function?

The term _function_ is used to describe a set of reusable and self-contained "block of blocks" that accomplish a specific task.

A _function_ is a reusable, self-contained "block of blocks" designed to accomplish a specific task. They work great for blocks that you want to reuse many times over.

## The Function Blocks

There are two kinds of blocks that you can use:

1. to
2. to return

### Function: To

The **to** function in Blockly is a fundamental programming block used to group a set of code instructions or tasks into a reusable and organized function. Unlike the **to return** function, which returns a value after execution, the **to** function performs operations only and does not return a specific result. It is primarily used for its side effects, such as modifying variables or creating outputs within the program. The code encapsulated within a **to** function can be called and executed multiple times throughout the program, enhancing code reusability and efficiency.

You first have to **set** the function, and then you'll **get** the function to call it.

For example, let's say you like to randomize names in most of your questions. Sometimes you want to use a first name, sometimes a last name, and sometimes a full name. Instead of building this for every question, you can simply create a to function. Here is an example:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 3.45.39 PM.png" alt=""><figcaption></figcaption></figure>

Anything that you can do inside of the Dynamic Engine, you can put inside of a function. To call the function, all you have to do is use the **get** component of the function block. So all that work is now just a simple "Random Name" call and you're done:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 3.53.14 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Put your functions inside of [The Backpack](the-backpack.md) for easy retrieval across questions.
{% endhint %}

### Function: To Return

The **To Return** function in Blockly allows you to create reusable blocks of code that perform specific tasks and return a value. Utilizing the **to** block, you define the function's logic, specify any necessary inputs, and determine the output value that is returned when the function is called. This enables efficient code management and simplifies complex operations by encapsulating functionality within named functions, making it easier to implement consistent logic across different parts of your project.

Another way to think about the **To Return** function is a custom formula for a specific variable. For example, if we are always calculating straight-line depreciation, it is easier to have a function we can call up and just send the values.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.03.56 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
To keep things clean, right click a function and select "collapse block". This will give you more space to work.
{% endhint %}

To **get** the calculation to work, we simple attached the function to a variable and its values:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.04.46 PM.png" alt=""><figcaption></figcaption></figure>

***

## Example Question

Consider the following Fill-in-the-blank question in EXAMIND:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.17.36 PM.png" alt=""><figcaption></figcaption></figure>

Here is what the Dynamic Engine would look like:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.17.52 PM.png" alt=""><figcaption></figcaption></figure>

The **Random Name** and **Asset Purchase Data** functions would look like this:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.20.22 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Both the **set** and **get** part of a function needs to be in the Dynamic Engine to work properly
{% endhint %}

Here is what a sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.17.26 PM.png" alt=""><figcaption></figcaption></figure>
