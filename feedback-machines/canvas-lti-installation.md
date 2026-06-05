---
icon: plug
description: >-
  One-time Canvas LTI installation of Feedback Machines, for institution IT /
  Canvas administrators.
---

# Canvas LTI Installation (IT)

This guide is for **institution IT or Canvas administrators**. It covers the one-time installation of the Feedback Machines LTI tool at the Canvas account level. Once it's installed, instructors can [enable Feedback Machines in their own courses](canvas-setup.md).

{% hint style="info" %}
Feedback Machines is a **separate product** from the EXAMIND Platform and has its **own** Canvas LTI integration. Installing one does not install the other.
{% endhint %}

## Install the LTI tool

{% stepper %}
{% step %}
### Create an LTI developer key

In Canvas, go to **Admin → Developer Keys** and select **+ LTI Key**.

* **Key Name:** `Feedback Machines`
* **Method:** `Enter URL`
* **JSON / Configuration URL:** `https://lti.feedbackmachines.com/lti/register/canvas`
{% endstep %}

{% step %}
### Set the placement

Edit the key and, under **Manual Entry**, set the placement to **Course Navigation**. Save.
{% endstep %}

{% step %}
### Turn the key ON

New developer keys default to **OFF**. Switch the Feedback Machines key state to **ON**.
{% endstep %}

{% step %}
### Install the app by Client ID

Copy the **Client ID** shown for the developer key. Then go to **Settings → Apps**, click **+ App**, choose **By Client ID** as the configuration type, paste the Client ID, and confirm the installation.
{% endstep %}

{% step %}
### Send your registration details to EXAMIND

So we can finish the integration on our side, email the following to [support@examind.io](mailto:support@examind.io):

* Your **production** Canvas instance URL
* Your **test** Canvas instance URL (if you have one)
* Whether your Canvas is **self-hosted** or on **Instructure Cloud**
* The **Client ID** generated above

We'll complete the platform registration and confirm when it's ready to test.
{% endstep %}
{% endstepper %}

## Next step

Once installation is confirmed, instructors can [enable Feedback Machines in their course and link a class](canvas-setup.md).
