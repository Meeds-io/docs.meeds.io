---
description: >-
  Create, reuse, and manage section templates to build consistent, modular pages
  across your Meeds hub.
icon: grip-dots
---

# Managing Section Templates

Section templates are reusable layout components that help you build consistent, efficient, and visually appealing pages within your Meeds hub. This guide explains how to create, manage, and reuse section templates using the admin interface and the page builder.

{% embed url="https://www.loom.com/share/2f09a83909914a5a858c612b19922f13?sid=f7d6e3cd-c6bc-4940-8685-d2ce25169c77" %}
Video guide to creating and customizing section templates.
{% endembed %}

### What is a Section Template?

A section template defines the layout and structure of a content block that can be reused across multiple pages. Sections can represent headers, footers, dashboards, or any functional block of content. They are created from individual cells that can contain applications, text, images, and other content. Sections are sued in the Page builder when you [edit a page layout](managing-websites/editing-navigation/editing-pages.md).

Each section can be based on:

* **Dynamic layout**: Responsive, flexible structure for variable content.
* **Fixed layout**: Static structure with predefined dimensions.
* **Custom template**: A previously saved section layout.

<figure><img src="../../.gitbook/assets/add-section-drawer.png" alt="" width="375"><figcaption><p>Choosing a section type when adding a new section</p></figcaption></figure>



### Creating a New Section Template

You can create section templates directly within the Page Builder:

1. Open a page and click **Add Section**.
2. Select a base layout: _Dynamic,_ _Fixed_ or any of your custom templates
3. Customize your layout by adding and configuring cells.
4. When satisfied, click **Save As Template** on the section's right hand side.

<figure><img src="../../.gitbook/assets/save-section-template.png" alt="" width="226"><figcaption></figcaption></figure>

A drawer is opened:

<figure><img src="../../.gitbook/assets/add-seciton-template-drawer.png" alt="" width="375"><figcaption><p>Saving a customized section as a new template</p></figcaption></figure>

1. Provide a **name** and **description**.
2. A **thumbnail preview** is automatically generated.



💡 _Tip: Use clear naming and add helpful descriptions to make templates easy to find later._



***

### Managing Templates in the Admin Interface

As an administrator, go to **Administration > Development > Templates > Sections** to manage all saved templates.

This interface displays a list of all section templates with the following columns:

* Preview thumbnail
* Name and description
* Section type (Dynamic or Fixed)
* Status (Active / Inactive)
* Action menu (⋮)

<figure><img src="../../.gitbook/assets/manage-section-templates.png" alt=""><figcaption><p>Overview of all section templates in the administration interface.</p></figcaption></figure>



### Available Actions

<figure><img src="../../.gitbook/assets/section-actions-dropdown.png" alt="" width="267"><figcaption><p>Managing individual templates via the action menu.</p></figcaption></figure>

From the action menu (⋮), you can:

* **Edit Layout**: Open the template in the Section Editor and adjust its layout. (disabled for default blank templates)

<figure><img src="../../.gitbook/assets/section-editor.png" alt=""><figcaption></figcaption></figure>

* **Edit Properties**: Rename the template, update its description, or replace the thumbnail.

<figure><img src="../../.gitbook/assets/edit-properties-seciton-template.png" alt="" width="375"><figcaption></figcaption></figure>

* **Duplicate**: Clone the template to create a new variation.
* **Export**: Download the section template as a zip file.
* **Delete**: Permanently remove the template (disabled for default blank templates).



### Bulk Operations

Use checkboxes to select multiple templates and perform bulk actions:

<figure><img src="../../.gitbook/assets/bulk-operations-section-templates.png" alt="" width="305"><figcaption><p>Performing bulk operations on multiple section templates</p></figcaption></figure>

* **Export**: Download selected templates.
* **Delete**: Remove several templates at once.



### Creating Templates from the Admin Panel

Click **Add** button in the admin interface to create a section without going through the Page Builder.

<figure><img src="../../.gitbook/assets/add-section-template-dropdown.png" alt="" width="201"><figcaption></figcaption></figure>

* Choose **Import** to upload a previously exported seciton template.
* Choose Create to create a new section from scratch and save it as template

1. Choose a layout type (Dynamic or Fixed).
2. Set the number of columns and/or rows.

<figure><img src="../../.gitbook/assets/add-section-from-admin.png" alt="" width="375"><figcaption></figcaption></figure>

Click **Next** and the Section editor opens

<figure><img src="../../.gitbook/assets/grid-section-editor.png" alt=""><figcaption><p>Creating a new section template directly from the admin interface.</p></figcaption></figure>

1. Customize the section's layout, and tune it to looks as you want including by adding applications and content if you need
2. Click **Save** and then enter a name and description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           &#x20;

***

### 💡 Best Practices

* Use consistent naming conventions.
* Keep descriptions meaningful.
* Regularly clean unused or duplicate templates.
* Test responsiveness for mobile layouts.
* Export templates for backup or sharing across hubs.
