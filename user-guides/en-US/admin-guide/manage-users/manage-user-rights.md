---
description: Understand how your users can act on the platform
---

# Manage User Rights

### Understanding Different User Rights

#### :point\_right: **Platform Administration**

Multiple administrators can coexist within the platform. This can be useful for delegating rights without granting full authority:



<table><thead><tr><th width="191">Type</th><th width="329">Permissions</th><th>Group</th></tr></thead><tbody><tr><td>Platform Administrator</td><td>Platform Management (settings, notifications, applications)</td><td>platform/administrators</td></tr><tr><td></td><td>Users, Groups &#x26; Spaces Management</td><td></td></tr><tr><td></td><td>Access to analytics</td><td></td></tr><tr><td>Analytics Administrator</td><td>Access to analytics</td><td>platform/analytics</td></tr><tr><td></td><td>Analytics Management</td><td></td></tr><tr><td>Rewarding Administrator</td><td>Reward Settings Managament</td><td>platform/rewarding</td></tr><tr><td></td><td>Programs Management</td><td></td></tr><tr><td></td><td>Rewards Management</td><td></td></tr><tr><td></td><td>Wallets Management</td><td></td></tr><tr><td>Content Manager</td><td>Content Management (i.e Public Site)</td><td>platform/web-contributors</td></tr></tbody></table>

#### :point\_right: Community Management

By default:&#x20;

* Anyone can create a space.
* Only the platform administrator can manage communities and therefore access spaces to support space moderators

It is possible to modify these settings if needed to delegate community management to other individuals.



<table><thead><tr><th width="192">Type</th><th width="297">Permissions</th><th>Comment</th></tr></thead><tbody><tr><td>Platform Administrator</td><td>Space creation</td><td>Restrict this option to only few groups of people if needed</td></tr><tr><td></td><td></td><td>In such cases, only few people will be able to create space</td></tr><tr><td></td><td>Spaces Management: access to its settings, &#x26; Ability to bind groups to spaces</td><td></td></tr><tr><td>Animateurs de communautés</td><td>If identified, then:</td><td></td></tr><tr><td></td><td>Spaces Management: access to its settings, &#x26; Ability to bind groups to spaces</td><td></td></tr></tbody></table>

#### :point\_right: **Roles in Spaces**

By default, anyone who is a member of a space can publish messages, add notes, and participate in interactions.&#x20;

The space host can decide to restrict these writing rights by identifying specific authors. This can be useful in informational spaces.

<table><thead><tr><th width="192">Type</th><th width="297">If no redactor</th><th>If redactor</th></tr></thead><tbody><tr><td>Space Host</td><td>Space Management (customization of application and space assets)</td><td>idem</td></tr><tr><td></td><td>Members Management (invitation and roles identification)</td><td>idem</td></tr><tr><td>Space Redactor</td><td>--</td><td>Writing and sharing informations (message, notes)</td></tr><tr><td>Space Member</td><td>View of contents</td><td>View of contents</td></tr><tr><td></td><td>Writing and sharing informations (message, notes)</td><td>Interaction to informations</td></tr><tr><td></td><td>Interaction to informations</td><td></td></tr></tbody></table>

#### :point\_right: **Program Hosting**

By default, any recognition administrator can host a program.&#x20;

* They can delegate this to other members, manually or implicitly.&#x20;

If the program's audience is a space, then Space Hosts are the programs owners.&#x20;

* Conversely, moderators can be explicitly appointed by other program moderators.

<table><thead><tr><th width="192">Type</th><th width="297">Audience: No space</th><th>Audience : Espace</th></tr></thead><tbody><tr><td>Rewarding Administrator</td><td>Creation of Programs</td><td>Idem</td></tr><tr><td></td><td>Programs management (mission description, addition of actions, contributions management &#x26; review)</td><td>Idem</td></tr><tr><td></td><td>Promotion of new Program Owners</td><td>Idem</td></tr><tr><td>Space Host</td><td>NA</td><td>Programs management (mission description, addition of actions, contributions management &#x26; review)</td></tr><tr><td></td><td></td><td>Promotion of new Program Owners</td></tr><tr><td>Owner added manually by another Program Owner</td><td>--</td><td>Programs management (mission description, addition of actions, contributions management &#x26; review)</td></tr><tr><td></td><td></td><td>Promotion of new Program Owners</td></tr></tbody></table>

### Adding User Rights

#### :point\_right: Administrator Roles

* From the administration site, access user group management
* Go to the Platform group
* Then, access the desired sub-group (administration, analytics, rewarding, content management)
* The list of previously identified administrators is displayed
* Add or modify rights

:bulb: **Add the \* role for any user you add to an administrator group**

#### :point\_right: Space Management Permissions

* From the administration site, access space management
* From the permissions tab, modify space management rights
* Add a user group or space
* Members of these groups will be considered 'Community Managers' of all spaces

#### :point\_right: Program Management Permissions

* From the program you want to modify, access program editing
* In the second step, add program moderators by searching for their names.&#x20;

:bulb: **As a reminder, any space moderator is considered a program moderator if the audience is the same space**
