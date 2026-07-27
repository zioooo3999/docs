---
title: "Create New Entry"
sidebarTitle: "Create New Entry FAQ Category"
description: "User guide for creating and configuring new FAQ category entries in the Tempe Park CMS."
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create New Entry** button in the FAQ Category module is used to add a new FAQ category to the system. This feature allows administrators to input category information, such as the category name, slug, and display order.

The FAQ category data that is successfully added will be stored in the system and can be used in the FAQ module as a grouping mechanism for questions and answers displayed on the Tempe Park website.

---

## Form Fields & Interface Reference

<Frame>
  ![New FAQ Category Page](/images/0-\(32\).png "New FAQ Category Page")
</Frame>

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1** | **Tab Draft** _(editable form)_ | Use this form tab when creating or modifying a draft data entry. |
| **2** | **Tab Published** | Read-only view showing the current published version of the FAQ category entry. |
| **3** | **Name** | Enter the primary name of the FAQ Category. |
| **4** | **Order** | Set the numerical display sequence number for frontpage tab ordering. |
| **5** | **Faqs** | Click the dropdown to select and link multiple FAQ entries to this category. |
| **6** | **Slug** | Enter the URL-friendly slug for the FAQ Category. |
| **7** | **Publish** | Instantly publishes entry to the website frontpage and enables cross-module relationships. |
| **8** | **Save** | Stores the entry as a **Draft** without making it publicly visible. |
| **9** | **Multilingual** | Switch or add content versions in **English**, **Indonesian**, or **Chinese**. |

---

## Step-by-Step Procedure

<Steps>
  <Step title="Review the Form Interface">
    Open the FAQ Category module from the CMS navigation bar and click on **Create New Entry**.
  </Step>
  <Step title="Input Category Details & Slug">
    Enter the category **Name**, URL **Slug**, and assign a numerical **Order** index to control frontend tab sequence.
  </Step>
  <Step title="Associate FAQs & Multilingual Settings">
    Select linked questions via the **Faqs** dropdown and configure language localized versions via the **Multilingual** switcher.
  </Step>
  <Step title="Save or Publish">
    Click **Save** to preserve the category as a draft, or click **Publish** to deploy it directly to the frontend.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Relational Mapping" color="#10b981" icon="diagram-project">
    Associate multiple individual FAQ entries directly through the Faqs multi-select relation field.
  </Card>

  <Card title="Tab Positioning" color="#38bdf8" icon="arrow-down-1-9">
    Define the frontend visual tab sequence using custom order indices.
  </Card>

  <Card title="Multilingual Capabilities" color="#f59e0b" icon="language">
    Configure translated category names across English, Indonesian, and Chinese localization channels.
  </Card>
</CardGroup>