---
description: How to configure the Crowdin Connector for Meeds
---

# 🌐 Crowdin

If your organization uses [Crowdin](https://crowdin.com) for translation management, you can seamlessly involve your community and shape incentives to drive your localization programs.

You can activate the Crowdin connector to let contributors earn points based on their participation in your translation project on Crowdin.&#x20;

## Quick Video Tutorial

{% embed url="https://youtu.be/N5Wuj0y0iV0" %}

:bulb: **Note:**&#x20;

_The Crowdin integration requires your account to have high privileges on the Crowdin projects you want to integrate with Meeds. However, you don't need to own a Crowdin Enterprise subscription._



⚙️ Go to the Platform Settings  > Recognition > Connectors

<figure><img src="../../.gitbook/assets/meeds-admin-connectors-crowdin.png" alt="" width="332"><figcaption><p>Crowdin Connector card</p></figcaption></figure>

Click the Crowdin card to start configuring the connector :

<figure><img src="../../.gitbook/assets/crowdin-admin-events.png" alt="" width="315"><figcaption><p>Crowdin Gamification Connector</p></figcaption></figure>



## :point\_right: **Allow users to connect their Crowdin account**

Click on _Configure > Allow connection_

<figure><img src="../../.gitbook/assets/crowdin-admin-step1.png" alt="" width="323"><figcaption><p>Connect Crowdin Profile Config 1/3</p></figcaption></figure>

Access your Crowdin account _Settings > oAuth._ Click  _"New Application"_

<figure><img src="../../.gitbook/assets/crowdin-oauth.png" alt="" width="563"><figcaption><p>oAuth tab on Crowdin</p></figcaption></figure>

Fill in the _Name_ and _Description_, and select the _Notifications_ scope.&#x20;

<figure><img src="../../.gitbook/assets/crowdin-oauth2.png" alt="" width="335"><figcaption><p>New oAuth App form on Crowdin</p></figcaption></figure>

For the _Authorization callback URL_, open your Meeds tab and copy it from _Step 2_

<figure><img src="../../.gitbook/assets/crowdin-admin-step2.png" alt="" width="213"><figcaption><p>Connect Crowdin Profile Config 2/3</p></figcaption></figure>

Click _Create_, then _Edit_ in _Action_ to capture the _Client Credentials_.

<figure><img src="../../.gitbook/assets/crowdin-oauth3.png" alt="" width="563"><figcaption><p>Edit the oAuth Application</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/crowdin-oauth4.png" alt="" width="345"><figcaption><p>Copy credentials</p></figcaption></figure>

Report the Client ID and Client Secret in Step 3 on the Meeds tab

<figure><img src="../../.gitbook/assets/crowin-admin-step3.png" alt="" width="214"><figcaption><p>Connect Crowdin Profile Config 3/3</p></figcaption></figure>

_Save_, and your users can now [bind their Crowdin and Meeds accounts](../../user-guide/connecting-your-apps/crowdin.md) from their user settings.

You can temporarily <img src="../../.gitbook/assets/toggle.png" alt="" data-size="line"> disable the ability for users to connect, ✏️ edit, or 🗑️ remove the credentials.

<figure><img src="../../.gitbook/assets/crowdin-connect-buttons.png" alt="" width="451"><figcaption></figcaption></figure>

## :point\_right: **Add a Crowdin project to watch**

Now, you must connect Crowdin projects that your Meeds Hub will watch.

Click on 'Add Project'



<figure><img src="../../.gitbook/assets/crowdin-connector-add-project.png" alt="" width="427"><figcaption><p>Configure projects to watch</p></figcaption></figure>



<figure><img src="../../.gitbook/assets/crowdin-connector-add-project2.png" alt="" width="210"><figcaption><p>Add a Crowdin project 1/2</p></figcaption></figure>

Now go back to your Crowdin _Settings_ > _API_ tab, then click the _New Token_ button and select the scopes:&#x20;

* _Projects (List, Get, Create, Edit)_
* _Project Source Files & Strings_
* &#x20;_Project Webhooks_

<figure><img src="../../.gitbook/assets/crowdin-pat.png" alt="" width="323"><figcaption><p>New Personal Access Token form in Crowdin</p></figcaption></figure>

Click _Create_. If requested, enter your Crowdin password and confirm, then copy the _Access Token_ string.&#x20;

Back to Meeds,  paste  into the personal access token field:&#x20;

<figure><img src="../../.gitbook/assets/crowdin-connector-add-project3.png" alt="" width="296"><figcaption><p>Persona access token field in Meeds</p></figcaption></figure>

Hit the ✅ icon to verify your token is valid

<figure><img src="../../.gitbook/assets/crowdin-connector-add-project4.png" alt="" width="208"><figcaption><p>Step 1 with valid perosnal access token</p></figcaption></figure>

Click _Next_ and select the Crowdin project to watch from the dropdown menu and Save

<figure><img src="../../.gitbook/assets/crowdin-select-project.gif" alt="" width="212"><figcaption><p>Select the project from the list</p></figcaption></figure>

Once you have selected a project, Meeds will start watching it for events. You can ✏️ edit, 🗑️ delete, or ➕ add another project if needed

<figure><img src="../../.gitbook/assets/crowdin-connector-add-project6.png" alt="" width="449"><figcaption><p>Projects to watch in Meeds</p></figcaption></figure>

By clicking on a project you can even fine-tune which events you want to enable on a per-project basis



<figure><img src="../../.gitbook/assets/crowdin-connector-project-events.png" alt="" width="302"><figcaption><p>Choose Events to enable per project</p></figcaption></figure>



**🎉  You're now done with the connector configuration! Your translation program owners can now start** [**designing incentives for your localization program**](../designing-incentives/building-a-translation-program.md)**.**
