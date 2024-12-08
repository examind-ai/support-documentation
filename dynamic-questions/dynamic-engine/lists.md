---
description: This article will teach you about the List blocks in our Dynamic Engine.
---

# Lists

## The List Blocks

There are twelve kinds of _list_ blocks you can use in the Dynamic Engine. This article focuses on the top three blocks that you will use:

1. Create List With
2. Make List From Text
3. In List Get

### List: Create List With

The **create list with** block assigns a list of values to your variable. This allows you to group items together while also maintaining their independence from one another.&#x20;

For example, this sets the value of the variable named "List of Colors" to "Red,Blue,Green,Yellow".  The colors are separated by a comma when stored in the Dynamic Engine.

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-04%20at%209-29-34%20AM-png.png?width=575&#x26;height=146&#x26;name=Screen%20Shot%202024-06-04%20at%209-29-34%20AM-png.png" alt="" height="146" width="575"><figcaption></figcaption></figure>

### List: Make List From Text

The **make list from text** block does the same thing as the **create list with** block. It works great when you have a really large list that you want to add to the dynamic engine because it saves time by not having to drag and drop blocks. \
\
For example, this sets the value of the variable named "List of Colors" to "Red,Blue,Green,Yellow" (same as above).

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-04%20at%209-32-41%20AM-png.png?width=688&#x26;height=49&#x26;name=Screen%20Shot%202024-06-04%20at%209-32-41%20AM-png.png" alt="" height="49" width="688"><figcaption></figcaption></figure>

The colors are separated by a comma when stored in the Dynamic Engine. The most common delimiter that people use with computers is a comma. We blew our intern's mind when we showed them that .csv files from excel stands for **C**omma **S**eparated **V**alues 🤯\
\
Note that there are no spaces when using the delimiter, unless you specify the delimiter to have a space.

### List: In List Get

The **in list get** block lets you pull a value out of the list. This is useful when you want to pull a random value from a list. For example, this sets the value of the variable named "Random Color" to either "Red", "Blue", "Green" or "Yellow".

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-04%20at%209-35-47%20AM-png.png?width=575&#x26;height=58&#x26;name=Screen%20Shot%202024-06-04%20at%209-35-47%20AM-png.png" alt="" height="58" width="575"><figcaption></figcaption></figure>

The way this works is we first want to create a list. In this case, the list is called "List of Colors". Then, we want to create a new variable called "Random Color" that uses the **in list get** block from, and specify that we want a random value from the list.\
\
The options for the **get** dropdown do the following:

* **Get** - gets a value from the list, leaving the list unchanged
* **Get and Remove** - gets a value from the list, removes it and updates the list
* **Remove** - removes a value from the list and updates the list

For example, the following blocks could result in the variable "Random Color" being "Green" and the list becoming "Red,Blue,Yellow".

<figure><img src="https://instructor-help.examind.io/hs-fs/hubfs/Screen%20Shot%202024-06-04%20at%209-37-34%20AM-png.png?width=1388&#x26;height=114&#x26;name=Screen%20Shot%202024-06-04%20at%209-37-34%20AM-png.png" alt="" height="114" width="1388"><figcaption></figcaption></figure>

The options for the **#** dropdown do the following:

* **#** - gets a value from a specific position in the list (e.g., the 2nd value would be "Blue")
* **# from end** - gets a value from a specific position in the list, counting from the end
* **First** - gets the first value in the list
* **Last** - gets the last value in the list
* **Random** - gets a random value in the list

***

## Example Question

Consider the following Multiple Choice question in EXAMIND.

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-05 at 5.41.35 PM.png" alt=""><figcaption></figcaption></figure>

The goal of this question is to add a custom list of long-term assets can current assets.

Here is what the Dynamic Engine would look like:

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-05 at 5.44.59 PM.png" alt=""><figcaption></figcaption></figure>

In this example, we use the **create list with** block to generate a list of values and the **in list get** block to assign a random value to the variable Long-term-Asset". Then, we use the **get and remove** feature to pull values for Current Asset 1 and Current Asset 2.

Here is what the sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../.gitbook/assets/Screenshot 2024-12-05 at 5.41.53 PM.png" alt=""><figcaption></figcaption></figure>
