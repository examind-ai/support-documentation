# Honorlock Integration

EXAMIND supports Honorlock proctoring via a third-party integration. With this setup, students complete two LTI launches to access a Honorlock-proctored EXAMIND assessment: one into Honorlock, then one into EXAMIND.

A direct integration (single LTI launch) is not currently supported. If your institution is interested in this option, contact us at [**support@examind.io**](mailto:support@examind.io) — we'd like to hear from you.

## Third-Party Integration

Open the Honorlock widget (typically launched via the Honorlock LTI tool in your LMS) and choose `Register Third Party Assessment`:

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

In `Admin Settings`, select the following:

Assessment Platform: `Use Another Platform`

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Enter the following:

Platform Name: `EXAMIND`

Direct URL: `(leave empty)`

Password: Enter the access code used to secure EXAMIND's assessment

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Save changes.

{% hint style="info" %}
Students must access EXAMIND's assessment through a specific sequence. Do not share the EXAMIND access code directly with them. Instead:

1. Direct students to launch the Honorlock assessment you created via Honorlock's LTI Launch.
2. Honorlock will verify the browser extension is installed.
3. After starting their Honorlock session, instruct them to return to the LMS.
4. Students should then launch EXAMIND's assessment via LTI, where Honorlock's extension will automatically unlock the assessment.

This sequence ensures proper proctoring activation before students can access the assessment.
{% endhint %}
