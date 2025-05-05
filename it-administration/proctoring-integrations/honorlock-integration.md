# Honorlock Integration

There are 2 forms of integration with Honorlock:

* 3rd Party Integration
* Direct Integration

**3rd Party Integration**: Quicker setup with no IT admin support needed, but students must complete two separate LTI launches to access Honorlock-proctored EXAMIND assessments.

**Direct Integration**: Requires one-time setup where EXAMIND receives your institution's Honorlock Client ID and Secret. Students then need only one LTI launch to access Honorlock-proctored EXAMIND assessments, creating a more streamlined experience.

## 3rd Party Integration

Open the Honorlock widget (usually accessed through Honorlock's LTI) and choose `Register Third Party Assessment`:

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

In `Admin Settings`, select for following:

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
2. They will first verify their Honorlock browser extension is properly installed.
3. After starting their Honorlock session, instruct them to return to the LMS.
4. Students should then perform an LTI Launch into EXAMIND's assessment, where Honorlock's extension will automatically unlock the assessment.

This sequence ensures proper proctoring activation before students can access the assessment.
{% endhint %}

## Direct Integration

With direct integration, EXAMIND will be calling Honorlock's API on behalf of the institution. Before getting started, EXAMIND will require the institution's Client ID and Client Secret. To generate these, go to Honorlock's `API Clients` page and create a new client for EXAMIND:

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Assign any client name (we suggest `EXAMIND`), then copy the `Client ID` and `Client Secret` and share those with EXAMIND in a secure way.

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

EXAMIND's access to Honorlock's API can be revoked at any time by deleting the API Client.
