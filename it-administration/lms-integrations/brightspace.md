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
**Instructions for Step 6 (Custom Parameters)**

Leave blank
{% endtab %}
{% endtabs %}

***

## Step 2: Assessment Deeplink

Refer to [Assessment Deeplink](../../get-started/lms-integrated/assessment-deeplink/#brightspace) for instructions on how to link a Brightspace activity to an EXAMIND assessment.
