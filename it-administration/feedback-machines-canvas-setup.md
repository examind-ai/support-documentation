---
icon: plug
description: >-
  One-time Canvas LTI installation of Feedback Machines, for institution IT /
  Canvas administrators.
---

# Feedback Machines: Canvas LTI Installation

This guide is for **institution IT or Canvas administrators**. It covers the one-time installation of the Feedback Machines LTI tool at the Canvas account level. Once it's installed, instructors can [enable Feedback Machines in their own courses](../feedback-machines/using-canvas.md).

{% hint style="info" %}
Feedback Machines is a **separate product** from the EXAMIND Platform and has its **own** Canvas LTI integration. Installing one does not install the other.
{% endhint %}

Feedback Machines supports two ways to install its LTI tool in Canvas. **Dynamic Registration is the recommended method** — it configures the developer key, placements, and branding automatically from a single URL. A manual **JSON URL** method is available as a fallback (see [Alternative: install with a JSON URL](#alternative-install-with-a-json-url)).

## Install via Dynamic Registration

{% stepper %}
{% step %}
### Register Feedback Machines

In Canvas, go to **Admin → Developer Keys**, click **+ Developer Key**, and select **+ LTI Registration**:

<figure><img src="../.gitbook/assets/canvas-dr-add-lti-registration.png" alt="Canvas Developer Keys — adding an LTI Registration"><figcaption></figcaption></figure>

Enter the **Dynamic Registration URL**, then click **Continue**:

```
https://lti.feedbackmachines.com/lti/register
```

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-url.png" alt="Register App dialog with the Feedback Machines Dynamic Registration URL entered"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Review the settings and enable

Canvas and Feedback Machines exchange the configuration automatically — the app name, logo, permissions, and placements are filled in for you. Review them, then click **Enable & Close**:

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-settings.png" alt="Feedback Machines Settings showing permissions, user data, and placements"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Check the developer key is ON

Back on the **Developer Keys** page, confirm the new **Feedback Machines** key's state is **ON**:

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-turn-on.png" alt="Feedback Machines developer key with its state toggled ON"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Open the app in Canvas Apps

On the same row, click **View in Canvas Apps**:

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-view-in-apps.png" alt="View in Canvas Apps link on the Feedback Machines developer key row"><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Make the app Available where you want it

On the **Availability and Exceptions** tab, the app starts as **Not Available**. Make it **Available** wherever you want instructors to see it: across the whole account, or only in the specific course(s), department(s), or schools adopting Feedback Machines — use **Add Exception** to scope it to a course or sub-account.

For example, to make it available account-wide, click the pencil icon next to the account row:

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-install-activate.png" alt="Feedback Machines app page with the Not Available chip and its edit control"><figcaption></figcaption></figure>

Change **Not Available** to **Available**, then **Save**:

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-make-available.png" alt="Edit Exception dialog changing availability to Available"><figcaption></figcaption></figure>

{% hint style="warning" %}
This step is easy to miss: the app can show **"App is On"** and still be invisible in courses. Until availability is set to **Available**, the Feedback Machines link won't appear in any course navigation.
{% endhint %}
{% endstep %}

{% step %}
### Send your details to EXAMIND

We connect your Canvas instance to your institution's license on our side. Copy the **Client ID** from the **Details** column of the **Developer Keys** page:

<figure><img src="../.gitbook/assets/fm-canvas-docs/fm-canvas-dr-registration-copy-id.png" alt="Client ID in the Details column of the Feedback Machines developer key"><figcaption></figcaption></figure>

Then email the following to [support@examind.io](mailto:support@examind.io):

* Your **production** Canvas instance URL
* Your **test** Canvas instance URL (if you have one)
* The **Client ID** copied above

We'll confirm when everything is connected.
{% endstep %}

{% step %}
### Verify

In a Canvas course, enable **Feedback Machines** in the course navigation (**Settings → Navigation**) and click the link — it should launch. This is the same per-course activation [instructors do themselves](../feedback-machines/using-canvas.md).
{% endstep %}
{% endstepper %}

## Alternative: install with a JSON URL

If Dynamic Registration isn't available on your Canvas instance, you can install manually. Unlike Dynamic Registration, this method doesn't set the course-navigation placement or register your Canvas instance with us automatically, so it has a few more steps.

{% stepper %}
{% step %}
### Create an LTI developer key

In Canvas, go to **Admin → Developer Keys**, click **+ Developer Key**, and select **+ LTI Key**.

* **Key Name:** `Feedback Machines`
* **Method:** `Enter URL`
* **JSON / Configuration URL:** `https://lti.feedbackmachines.com/lti/register/canvas`

Click **Save**.
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
### Send your registration details to EXAMIND

Copy the **Client ID** shown for the developer key (the number in the **Details** column). Then email the following to [support@examind.io](mailto:support@examind.io):

* Your **production** Canvas instance URL
* Your **test** Canvas instance URL (if you have one)
* Whether your Canvas is **self-hosted** or on **Instructure Cloud**
* The **Client ID** copied above

We'll register your Canvas instance on our side and confirm by email. Until that registration is complete, the Feedback Machines link won't launch for instructors or students.
{% endstep %}

{% step %}
### Install the app by Client ID

Go to **Settings → Apps** and click **View App Configurations**. Click **+ App**, choose **By Client ID** as the configuration type, paste the Client ID, click **Submit**, and confirm the installation.

{% hint style="warning" %}
On Instructure Cloud, a newly installed app can be **blocked by default**. If Canvas reports *"This app has been blocked by your administrator"* when you click **Install**, unblock the Feedback Machines app in your account's app settings, or [contact us](mailto:support@examind.io) for help.
{% endhint %}
{% endstep %}
{% endstepper %}

## Next step

Once installation is confirmed, instructors can [enable Feedback Machines in their course and link a class](../feedback-machines/using-canvas.md).
