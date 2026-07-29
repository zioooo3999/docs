---
title: "Create/Setup Homepage"
sidebarTitle: "Create/Setup Homepage Page"
description: "Comprehensive guide for building and configuring the Tempe Park homepage using the Page Builder."
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Homepage** feature in the Page module allows you to create a new homepage and organize the front page content of the Tempe Park website using the Page Builder. This feature enables administrators to add various sections—such as a hero section, banner slider, event lists, and commitment sections—to suit specific visual and informational needs.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1** | **Tab Draft** _(editable form)_ | Use this form tab when creating or modifying a draft data entry. |
| **2** | **Tab Published** | Read-only view showing the current published version of the homepage. |
| **3** | **title** | Enter the primary page title. |
| **4** | **slug** | Enter the unique URL-friendly slug identifier for the page. |
| **5** | **SEO Section** | Add metadata by clicking `(+)` for `metaTitle`, `metaDescription`, and `shareImage`. |
| **6** | **Add Component** | Click to insert structural block components into the page layout. |
| **7** | **Publish** | Instantly publishes entry to the website frontpage and enables cross-module relationships. |
| **8** | **Save** | Stores the entry as a **Draft** without making it publicly visible. |
| **9** | **Multilingual** | Switch or add content versions in **English**, **Indonesian**, or **Chinese**. |

---

## Section Builder Guide

### 1. Hero Section

- **Access:** Click the **Shared** group and select **Hero**.
- **Fields:** Fill in the **Title**, **Description**, **Image**, and configure **CTA 1 & 2** labels and link properties.

### 2. Banner Slider Section

- **Access:** Open the **Dynamic** group and select **Slider**.
- **Settings:** Set **Layout** to `default` and **Source Type** to `manual`.
- **Controls:** Toggle **show\_dots** and **show\_arrows** to `true`.
- **Slides:** In the **Slides** component, configure **heading** and **image**, and set **enable\_button** to `false` for the homepage slider.

### 3. "What's On" Section

- **Heading:** Open **Text** group \> **Heading**. Configure **Eyebrow**, **Heading**, and **Position**.
- **Content:** Use the **Flexbox** component in the Dynamic group to structure content modules.
- **CTA Button:** Open **Button** group \> **Button Multiple**. Click `(+)` to define **Title**, **Link**, and **Style**.

### 4. Journey & Commitment Sections

- **Journey Section:** Add a **Slider** component. Fill in **Eyebrow** as "Journey", **Highlight**, and **Description**, enabling **CTA** controls as needed.
- **Commitment Section:** Configure standard header and content blocks following the "What's On" structure.

### 5. News & Update Section

- **Structure:** Add a **Heading** block followed by a **Flexbox** layout container.
- **Important Configuration:** Ensure the `source_type` field is set strictly to **"news"** to automatically pull dynamic articles into the layout.
- **CTA Link:** Add a **Button** component linking directly to the full news archive page.

---

## Step-by-Step Procedure

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Homepage**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter the page **title**, page **slug**, and expand the **SEO Section** to configure meta titles, descriptions, and share image preview cards.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add Component** to build out the required visual modules sequentially (Hero Section, Banner Slider, What's On, Journey/Commitment, and News & Updates).
  </Step>
  <Step title="Save or Publish">
    Click **Save** to keep your page configurations as a draft, or click **Publish** to push the homepage layout live to the website.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Modular Layout Builder" color="#10b981" icon="cubes">
    Assemble hero banners, dynamic sliders, and content blocks using drag-and-drop component groups.
  </Card>

  <Card title="Dynamic Data Sourcing" color="#38bdf8" icon="database">
    Automatically fetch live articles by configuring structural blocks with dynamic source types.
  </Card>

  <Card title="Integrated SEO Controls" color="#f59e0b" icon="magnifying-glass">
    Configure meta titles, descriptions, and social share image cards directly inside the entry editor.
  </Card>
</CardGroup>

---

<Warning>
  Always verify your `source_type` and `layout` configurations before hitting **Publish** to ensure the page renders correctly on the live website.
</Warning>