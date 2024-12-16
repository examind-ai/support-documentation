---
description: This article shows you how to use the Variable blocks in our Dynamic Engine.
---

# Variables

## What Is a Variable?

The term _variable_ is the same term used in mathematics or computer science. It is a named value that can be changed - aka it "varies".

## The Variable Blocks

There are three kinds of variable blocks that you can use:

1. Set
2. Get
3. Change

### Variable: Set

The **set** block assigns a value to a variable, creating the variable if it doesn't already exist. For example, this sets the value of the variable named "age" to the number "18".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.22.46 PM.png" alt=""><figcaption></figcaption></figure>

### Variable: Get

The **get** block provides the value of a variable. Continuing from the previous example, it would _get_ the number "18".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.23.08 PM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Without a corresponding **set** block, the engine does not know what you want to do with the number "18". Think of it like a floating puzzle piece that needs to be connected to something. Without a connection, it's just floating around the office looking for a fresh cup of coffee (like our hipster UX designer).
{% endhint %}

### Variable: Change

The **change** block adds a number to a variable. Continuing from the previous example, this would add the number "1" to the number "18".

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.25.32 PM.png" alt=""><figcaption></figcaption></figure>

The **change** block broken down into a calculation would look like this:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.24.40 PM.png" alt=""><figcaption></figcaption></figure>

This is the equivalent of saying **set** the variable age to it's previous number (ie. 18) plus the number 1. So think of **change** like a shortcut.

### Variable: Menu

Click on the variable's dropdown symbol (light blue triangle) to get the following menu:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.27.14 PM.png" alt=""><figcaption></figcaption></figure>

The menu provides the following options:

* **Existing variables**: The names of all existing variables defined in the program. In this example, we only have one variable (age).&#x20;
* **Rename variable...:** Change the name of the selected variable. Selecting this option opens a prompt to enter a new name.
* **Delete the 'selected' variable:** Deletes all blocks that reference this variable wherever it appears in the program.

***

## Example Question

Consider the following multiple-choice question. The goal of this question is to add randomness to the "too young" and "too old" distractors.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.32.50 PM.png" alt=""><figcaption></figcaption></figure>

Here is what the Dynamic Engine would look like:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.33.40 PM.png" alt=""><figcaption></figcaption></figure>

Age is being **set** to make the correct answer "18" and the other answer options set to _Math_ blocks that randomly choose numbers in a range.

Here is what a sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-06 at 4.34.46 PM.png" alt=""><figcaption></figcaption></figure>
