---
description: This article shows you how to install EXAMIND using LTI in Brightspace.
---

# Brightspace

## Step 1: Install LTI Tool

Follow the steps in D2L's [Tool Registration, Deployment, and Links](https://community.d2l.com/brightspace/kb/articles/23662-tool-registration-deployment-and-links) page to install EXAMIND as an LTI Tool into Brightspace.

Note the following settings that are specific to EXAMIND:

{% tabs %}
{% tab title="Step 3" %}
**Instructions for Step 3**

Choose Dynamic For Dynamic Registration URL, use one of the following:

* For US data center users: https://lti.examind.io/register
* For Canadian data center users: https://lti-ca.examind.io/register
{% endtab %}

{% tab title="Step 4" %}
**Instructions for Step 4**

Select both **Send Institution Role** and **Send Context Role**
{% endtab %}

{% tab title="Step 5" %}
**Instructions for Step 5**

Select the following:

* $CourseOffering.title
* $CourseSection.label
* $CourseSection.sourcedId
* $CourseSection.title
* $CourseSection.timeFrame.begin
* $CourseSection.timeFrame.end
* $Person.email.primary
* $Person.name.family
* $Person.name.full
* $Person.name.given
* $Person.sourcedId
* $ResourceLink.available.startDateTime
* $ResourceLink.available.endDateTime
* $ResourceLink.description
* $ResourceLink.submission.endDateTime
* $ResourceLink.title
* $User.id
* $User.username
{% endtab %}

{% tab title="Step 6" %}
**Instructions for Step 6**

Leave blank
{% endtab %}
{% endtabs %}

## Step 2: Link Assessment

Go to a course in Brightspace, then select **Existing Activities**, then **EXAMIND** (or a different name selected during **LTI Tool Installation**):

<figure><img src="../../.gitbook/assets/image-png-1.webp" alt=""><figcaption></figcaption></figure>

If this is your first time adding an assessment into this Brightspace course, you'll be asked to select an EXAMIND course to link this course to.

Either select an existing course in EXAMIND or create a new one:

<figure><img src="../../.gitbook/assets/image-png-2 (1).webp" alt=""><figcaption></figcaption></figure>

If you've already linked an EXAMIND course, you'll be asked to select an assessment in EXAMIND. Either select an existing assessment or create a new one:

<figure><img src="../../.gitbook/assets/image-png-3.webp" alt=""><figcaption></figcaption></figure>

If you select the New Assessment option, by default it will be named **LTI Assessment**. Rename it in Brightspace:

<figure><img src="../../.gitbook/assets/image-png-4.webp" alt=""><figcaption></figcaption></figure>

Open the activity, click Edit, and rename it in EXAMIND:

<figure><img src="../../.gitbook/assets/image-png-Apr-26-2024-05-09-05-6994-AM.webp" alt=""><figcaption></figcaption></figure>

EXAMIND's assessment is now available as an activity in Brightspace.
