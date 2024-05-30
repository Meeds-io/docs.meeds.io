---
description: How to configure the GitHub connector for Meeds as an administrator
---

# 🐙 GitHub

If your organization uses [GitHub](https://github.com) to manage code or documentation and wants to foster open contributions and collaboration, the GitHub connector for Meeds is for you!

You can activate it to allow contributors to earn points by interacting with your repositories.

Events that the GitHub connector can capture include:

* Issues
* Pull Requests
* Code



To start configuring the GitHub connector for Meeds go to _Administration > Recognition > Connectors > GitHub_

<figure><img src="../../.gitbook/assets/GitHub-connectors-list.png" alt="" width="563"><figcaption><p>GitHub connector card</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/GitHub-connector-home.png" alt="" width="563"><figcaption><p>List of events of the GitHub connector</p></figcaption></figure>

Next, Click _Configure_&#x20;

<figure><img src="../../.gitbook/assets/GitHub-connector-config.png" alt="" width="563"><figcaption><p>GitHub configuration</p></figcaption></figure>

## :point\_right: **Allow users to connect their X account in Meeds**

Click on _'Allow connection' and_ follow the instructions in the form&#x20;

<figure><img src="../../.gitbook/assets/GitHub-connector-profile1.png" alt="" width="375"><figcaption></figcaption></figure>

**Step 1:** Go to your [Developer Settings](https://github.com/settings/apps) in your GitHub account

Click on _OAuthApps > Register new application_

<figure><img src="../../.gitbook/assets/GitHub-oauth-new-app.png" alt="" width="563"><figcaption><p>OAuth Apps tab in DGitHub's Developer Settings</p></figcaption></figure>

Fill the _Application name_ and _description_,

<figure><img src="../../.gitbook/assets/gitHub-oauth-new-app2.png" alt="" width="375"><figcaption><p>OAuth app form in GitHub</p></figcaption></figure>

&#x20;Now head back to Meeds to retrieve the URLs

**Step 2:** Click _Next_ and copy the _Homepage URL_ and _Authorization callback URL_ from Meeds

<figure><img src="../../.gitbook/assets/GitHub-connector-profile2.png" alt="" width="375"><figcaption><p>oAuth apps URLs in Meeds</p></figcaption></figure>

Now paste the URLs into the oAuth application form on GitHub and Create the App.

<figure><img src="../../.gitbook/assets/GitHub-oauth-app-credentials.png" alt="" width="563"><figcaption><p>Client ID in GitHub</p></figcaption></figure>

Click on _Generate a new client secret and authenticate_

<figure><img src="../../.gitbook/assets/GitHub-oauth-app-secret.png" alt="" width="563"><figcaption><p>Client secret in GitHub</p></figcaption></figure>

Head back to Meeds

**Step 2:** Click _Next_ and copy-paste the Client ID and _Client secret_ from GitHub to Meeds&#x20;

<figure><img src="../../.gitbook/assets/GitHub-connector-profile3.png" alt="" width="375"><figcaption><p>Connect GitHub profile config 3/3</p></figcaption></figure>

Click _Save_

<figure><img src="../../.gitbook/assets/GitHub-connector-profile4.png" alt="" width="563"><figcaption></figcaption></figure>

You can click on the <img src="../../.gitbook/assets/toggle.png" alt="" data-size="line">toggle button to temporarily disable profile connections, or you can ✏️ _Edit_ or 🗑️ _Delete_ the configuration to start over.

## :point\_right: **Add a GitHub organization to watch**

Now, you must add one or more organizations that Meeds will watch to track events your contributors perform.

<figure><img src="../../.gitbook/assets/GitHub-connector-organization1.png" alt="" width="563"><figcaption></figcaption></figure>

Click on _Add Organization_

<figure><img src="../../.gitbook/assets/GitHub-connector-organization2.png" alt="" width="375"><figcaption><p>Personal access token field in Meeds</p></figcaption></figure>

On GitHub head back to your [Developer Settings ](https://github.com/settings/developers)_> Personal access tokens (classic)_

<figure><img src="../../.gitbook/assets/GitHub-personal-access-token.png" alt="" width="563"><figcaption><p>Personal acess tokens in GitHub</p></figcaption></figure>



Click _Generate new token > Personal access token (classic)_&#x20;

<figure><img src="../../.gitbook/assets/GitHub-personal-access-token-form.png" alt="" width="563"><figcaption><p>Personal</p></figcaption></figure>

Fill out the form by selecting scopes :

* repo
* admin:org\_hook

Then click the _Generate token_ button

<figure><img src="../../.gitbook/assets/GitHub-personal-access-token-copy (1).png" alt="" width="563"><figcaption></figcaption></figure>

Copy the token and head back to Meeds to paste it, then click the ✅ checkmark to validate.

<figure><img src="../../.gitbook/assets/GitHub-connector-organization3.png" alt="" width="375"><figcaption></figcaption></figure>

Click _Next_ and enter your GitHub organization name.

<figure><img src="../../.gitbook/assets/GitHub-connector-organization4.png" alt="" width="375"><figcaption></figcaption></figure>

Click _Save,_ and the organization should be listed:

<figure><img src="../../.gitbook/assets/GitHub-connector-organizations-list.png" alt="" width="563"><figcaption></figcaption></figure>

You may add  ➕  more organizations to watch , ✏️ Edit  or 🗑️ Delete to start over

Click on the organization's name

<figure><img src="../../.gitbook/assets/GitHub)connector-org-events.png" alt="" width="563"><figcaption></figcaption></figure>

From there, you may restrict what events to watch for that particular organization.

Click on _Repositories_&#x20;

<figure><img src="../../.gitbook/assets/GitHub-connector-org-repos.png" alt="" width="563"><figcaption></figcaption></figure>

From there, you can restrict which repositories to watch on that particular organization.



**🎉 Congratulations! Your Meeds Hub is now ready to incentivize contributions on GitHub! Your program owner can now start designing incentives to** [**Foster open collaboration on GitHub**](../designing-incentives/fostering-open-collaboration-on-github.md)**.**
