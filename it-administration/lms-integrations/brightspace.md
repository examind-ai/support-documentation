---
description: This article shows you how to install EXAMIND using LTI in Brightspace.
---

# Brightspace

## Step 1: Install LTI Tool

Follow the steps in D2L's [Tool Registration, Deployment, and Links](https://community.d2l.com/brightspace/kb/articles/23662-tool-registration-deployment-and-links) page to install EXAMIND as an LTI Tool into Brightspace.

Note the following settings that are specific to EXAMIND **inside of D2L**:

{% tabs %}
{% tab title="D2L Step 3" %}
**Instructions for Step 3**

Choose Dynamic.

For Dynamic Registration URL, use one of the following:

* For US data center users: https://lti.examind.io/register
* For Canadian data center users: https://lti-ca.examind.io/register

After clicking `Register`, you will be greeted with a blank page. This is a known issue. Attempting to register again will result in a 500 error due to duplicate registration.

Return to Brightspace and find the `EXAMIND` tool:

* From the `Admin Tools` menu, click `Manage Extensibility`
* From the `LTI Advantage` tab, select the `All` filter and search for `EXAMIND`
* Open the `EXAMIND` tool and continue to `Step 4` of (https://community.d2l.com/brightspace/kb/articles/23662-tool-registration-deployment-and-links) at 
{% endtab %}

{% tab title="D2L Step 4" %}
**Instructions for Step 4**

Select **Send Institution Role**
{% endtab %}

{% tab title="D2L Step 5" %}
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

{% tab title="D2L Step 6" %}
**Instructions for Step 6 (Custom Parameters)**

Leave blank
{% endtab %}
{% endtabs %}

## Step 2: Assessment Deeplink

Refer to [Assessment Deeplink](../../get-started/lms-integrated/assessment-deeplink/#brightspace) for instructions on how to link a Brightspace activity to an EXAMIND assessment.
