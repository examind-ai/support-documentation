---
description: This article shows you how to use the Text blocks in our Dynamic Engine.
---

# Text

## The Text Blocks

There are twelve kinds of _text_ blocks you can use in the Dynamic Engine. This article focuses on the five most common blocks you will use:

1. Basic
2. Create Text With
3. Append Text
4. Set Letter Case
5. Random Text

### Text: Basic

The **basic** block assigns a text value to a variable of your choosing. For example, this sets the value of the variable named "first name" to the text "John".

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-03 at 7-27-47 PM-png.png" alt=""><figcaption></figcaption></figure>

Examples of pieces of text are:

* "John"
* "thing #1"
* "March 12, 2010"
* "Who framed Roger Rabbit?"

Text can contain letters (which may be lower-case or upper-case), numbers, punctuation marks, other symbols, and blank spaces between words. The conventional term for all of these different types of text is "characters".

{% hint style="info" %}
Note that nothing between two quotation marks represents empty text, and looks like this "".
{% endhint %}

### Text: Create Text With

The **create text with** block combines different blocks to create a combined string of text. For example, this sets the value of the variable named "full name" to the text "John Doe".

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-03 at 7-29-18 PM-png.png" alt=""><figcaption></figcaption></figure>

Notice how the two **basic** text blocks that are being combined are "John" and " Doe". You also have the option to add more or less blocks by pressing the "+" or the "-".

{% hint style="info" %}
Be mindful of spaces in text blocks. There is an intentional space added in the " Doe" text to create "John Doe".
{% endhint %}

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-03 at 7-30-03 PM-png.png" alt=""><figcaption></figcaption></figure>

### Text: Append Text

The **append text** block adds values to the end of a variable. For example, this sets the value of the variable named "first name" to "John" and then adds the text "Doe" to the end. The end result is that the variable named "first name" will now show "John Doe".

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-03 at 7-31-32 PM-png.png" alt=""><figcaption></figcaption></figure>

### Text: Letter Case

The **set letter case** block formats your values. For example, this sets the value of the variable named "full name" to "John Doe".

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-03 at 7-34-39 PM-png.png" alt=""><figcaption></figcaption></figure>

There are 3 options when you select the dropdown:

1. UPPER CASE
2. lower case
3. Title Case

### Text: Random Text

The **random** block selects from pre-populated datasets. For example, this sets the value of the variable named "first name" to a random female first name, such as "Anna".

<figure><img src="../../../../.gitbook/assets/Screen Shot 2024-06-03 at 7-35-39 PM-png.png" alt=""><figcaption></figcaption></figure>

Datasets can be select by clicking the dropdown menu next to the word "random". The current datasets available are the following:

* **City** - 89,500+ fake cities
* **Company** - 18,000+ fake companies
* **Country** - 244 real countries
* **First Name** - 3,000+ ethnically diverse names
* **First Name (Female)** - 450+ ethnically diverse female names
* **First Name (Male)** - 400+ ethnically diverse male names
* **Industry** - 148 real industries
* **Last Name** - 450+ ethnically diverse last names
* **Month** - 12 months
* **Weekday** - 7 days of the week

***

## Example Question

Consider the following multiple-choice question.

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-05 at 4.55.36 PM.png" alt=""><figcaption></figcaption></figure>

The goal of this question is to create independent variables that don't affect the answer outcome. These variables enable EXAMIND to identify the source of leaked content (if this question appears online). This works because each student is served a unique permutation of the question.\
\
Here is what the Dynamic Engine would look like:

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-05 at 4.55.19 PM.png" alt=""><figcaption></figcaption></figure>

Here is what a sample question would look like (values highlighted in blue for convenience):

<figure><img src="../../../../.gitbook/assets/Screenshot 2024-12-05 at 4.56.55 PM.png" alt=""><figcaption></figcaption></figure>
