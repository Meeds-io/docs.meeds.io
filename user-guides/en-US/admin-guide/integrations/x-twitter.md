---
description: How to configure the X connector for Meeds as an administrator
---

# 🐦 X (Twitter)

If your organization uses X for general communication and wants to boost your audience's engagement, the X connector for Meeds is for you.

You can activate it to allow contributors to earn points by interacting with your accounts on X.

Events that the X connector can capture include:

* Likes
* Mentions
* Reposts



Go to _Administration > Recognition > Connectors > Twitter_

<figure><img src="../../.gitbook/assets/Twitter-Connector-home.png" alt="" width="563"><figcaption><p>List of events supported by the X connector</p></figcaption></figure>

Next, click `Configure`

<figure><img src="../../.gitbook/assets/Twitter-connector-configure.png" alt="" width="563"><figcaption><p>X connector ready to be configured</p></figcaption></figure>

## :point\_right: **Allow users to connect their X account**

Click on `Allow connection` _and_ follow the instructions in the form to activate this connection

<figure><img src="../../.gitbook/assets/Twitter-connector-profile-step1.png" alt="" width="375"><figcaption><p>Enable Twitter profile (1/3)</p></figcaption></figure>

**Step 1:** Create or connect to your account on the X [Developer portal](https://x.developer.com)

<figure><img src="../../.gitbook/assets/Twitter-developer-portal.png" alt="" width="563"><figcaption><p>Twitter Developer portal</p></figcaption></figure>

Create a project with _X API v2_ access

:bulb: **Note:** _X requires a subscription to access its API, which is not free of charge. Hence, you must acquire at minimum a **Basic** plan to use the connector._&#x20;

**Step 2:** Create a custom app and edit the _User authentication settings:_

<figure><img src="../../.gitbook/assets/Twitter-app-permissions.png" alt="" width="375"><figcaption><p>Set Read permission</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Twitter-app-type.png" alt="" width="375"><figcaption><p>Choose Web App type</p></figcaption></figure>

Fill in the _App info's_ _Callback URL_ and _Website URL_ fields by copy-pasting the information from Meeds:

<figure><img src="../../.gitbook/assets/Twitter-connector-profile-step2.png" alt="" width="375"><figcaption><p>Copy Callback URI and Website URL in Meeds (2/3)</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/Twitter-app-info.png" alt="" width="375"><figcaption><p>Paste Callback URI and Website URL in X</p></figcaption></figure>

**Step 3:** Copy/paste the _Client ID_ and _Client Secret and Save_

<figure><img src="../../.gitbook/assets/Twitter-connector-profile-step3.png" alt="" width="375"><figcaption><p>Enter Client credentials in Meeds (3/3)</p></figcaption></figure>

Once done, users can [connect their X account](../../user-guide/connecting-your-apps/twitter.md) from their user settings.

<figure><img src="../../.gitbook/assets/Twitter-connector-profile-ok.png" alt="" width="563"><figcaption><p>Connect  Twitter profile configured</p></figcaption></figure>

You can click on the <img src="../../.gitbook/assets/toggle.png" alt="" data-size="line">toggle button to temporarily disable profile connections, or you can ✏️ _Edit_ or 🗑️ _Delete_ the configuration to start over.



## :point\_right: **Add an X account to watch**

Next, tell Meeds which X account to watch for your organization. Click `Add Token`

<figure><img src="../../.gitbook/assets/Twitter-connector-org.png" alt="" width="375"><figcaption><p>Add token field in Meeds</p></figcaption></figure>

Go back to your app in the X Developer portal and click _Keys and tokens_

<figure><img src="../../.gitbook/assets/Twitter-app-tokens.png" alt="" width="375"><figcaption><p>Keys and tokens in X</p></figcaption></figure>

In _Authentication Tokens > Bearer Token,_ click `Regenerate` and confirm

<figure><img src="../../.gitbook/assets/Twitter-app-bearer.png" alt="" width="375"><figcaption><p>Copy the bearer token in X </p></figcaption></figure>

Click `Copy`, then paste it into Meeds. Then, click on the  ✔️ green checkmark and `Save`

&#x20;Click on `Add account` and enter the X username of the organization to watch and `Save`

<figure><img src="../../.gitbook/assets/Twitter-connector-addorg.png" alt="" width="375"><figcaption><p>Enter the X account name</p></figcaption></figure>

Meeds is now ready to watch the organization's account.&#x20;

<figure><img src="../../.gitbook/assets/Twitter-connector-meedsorg.png" alt="" width="563"><figcaption><p>List of X accounts to watch</p></figcaption></figure>

Click on ➕ to add more accounts to watch and 🔑 to update your bearer token.

Optionally, you can click on the organization name and disable some events to watch specifically for that organization.

<figure><img src="../../.gitbook/assets/Twitter-connector-org-events.png" alt="" width="563"><figcaption><p>List of events enabled for the X account</p></figcaption></figure>

_**🎉 Congratulations! Your Meeds Hub is ready to boost your organization on X! Your program owner can now design incentives to**_[ _**Grow your audience on X (Twitter)**_](../designing-incentives/growing-your-audience-on-x.md)_**.**_
