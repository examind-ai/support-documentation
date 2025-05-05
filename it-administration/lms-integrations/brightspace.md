---
description: This article shows you how to install EXAMIND using LTI in Brightspace.
---

# Brightspace

## Step 1: Send info to EXAMIND

In order for EXAMIND's iframe to load within your Brightspace instance, EXAMIND must white-list your Brightspace domain by adding it to its _content-security-policy_ HTTP header. Please send us your production Brightspace Instance URL (example: https://devcop.brightspace.com).

Information can be emailed to [**support@examind.io**](mailto:support@examind.io).

## Step 2: Register LTI Tool

From the **Admin Tools** menu, click **Manage Extensibility**:

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

From the **LTI Advantage** tab, click **Register Tool**:

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

Choose **Dynamic**, and add one of the following **Tool initiation registration endpoints**:

* For US data center users: https://lti.examind.io/register
* For Canadian data center users: https://lti-ca.examind.io/register

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

Click **Register** and a new tab will open.

{% hint style="info" %}
When registering a tool in Brightspace, a new tab will open and perform several redirects before remaining blank - this is a known issue that doesn't affect proper tool registration. Despite the blank page, your tool will be correctly registered in the system; simply close this tab and return to the `Register a Tool` page to continue.
{% endhint %}

From the **Admin Tools** menu, click **Manage Extensibility**:

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

From the **LTI Advantage** tab, click **All**, filter, find, and click **EXAMIND**:

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

Enable **EXAMIND**:

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

Ensure that the following 3 extensions are enabled:

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

Add the following **Substitution Parameters**:

| Name                                                      | Value                                 |
| --------------------------------------------------------- | ------------------------------------- |
| brightspace\_context\_id\_history                         | $Context.id.history                   |
| brightspace\_course\_offering\_label                      | $CourseOffering.label                 |
| brightspace\_course\_offering\_source\_id                 | $CourseOffering.sourcedId             |
| brightspace\_course\_offering\_title                      | $CourseOffering.title                 |
| brightspace\_course\_section\_dept                        | $CourseSection.dept                   |
| brightspace\_course\_section\_label                       | $CourseSection.label                  |
| brightspace\_course\_section\_source\_id                  | $CourseSection.sourcedId              |
| brightspace\_course\_section\_time\_frame\_begin          | $CourseSection.timeFrame.begin        |
| brightspace\_course\_section\_time\_frame\_end            | $CourseSection.timeFrame.end          |
| brightspace\_course\_section\_title                       | $CourseSection.title                  |
| brightspace\_person\_source\_id                           | $Person.sourcedId                     |
| brightspace\_resource\_link\_available\_end\_date\_time   | $ResourceLink.available.endDateTime   |
| brightspace\_resource\_link\_available\_start\_date\_time | $ResourceLink.available.startDateTime |
| brightspace\_resource\_link\_id\_history                  | $ResourceLink.id.history              |
| brightspace\_resource\_link\_submission\_end\_date\_time  | $ResourceLink.submission.endDateTime  |
| brightspace\_resource\_link\_title                        | $ResourceLink.title                   |
| brightspace\_user\_id                                     | $User.id                              |
| brightspace\_user\_username                               | $User.username                        |

It should look like this:

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

**Save** you changes without closing, as we will need to configure deployments next.

## Step 3: Add Deployment

From the **EXAMIND** LTI Tool page, click **View Deployments**:

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

Click **New Deployment**:

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

Select the **EXAMIND** tool and give it a name:

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

Ensure the the following extensions are enabled:

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

Enable the following **Security Settings**:

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

Enable the following **Configuration Settings**:

<figure><img src="../../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

Click Add Org Units and in the popup, select which organizations or courses should have access to EXAMIND:

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

Create Deployment.

## Step 3: Add Link

From the deployment page, click **View Links**:

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Click **New Link**:

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

Name the new link and set the URL to one of the following

* For US data center users: https://lti.examind.io/
* For Canadian data center users: https://lti-ca.examind.io/

For **Type**, select **Deep Linking Quicklink:**

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

Click **Save and Close**.

## Step 4: Assessment Deeplink

Refer to [Assessment Deeplink](../../get-started/lms-integrated/assessment-deeplink/#brightspace) for instructions on how to link a Brightspace activity to an EXAMIND assessment.
