---
title: "Page Module - Create/Setup Experience"
sidebarTitle: "Experien"
description: "Step-by-step guide for building and configuring the 'Experience' page in the Tempe Park CMS using the Page Builder."
---

## Overview

The **Create/Setup Experience** feature in the Page module allows administrators to construct and organize the Experience front page of the Tempe Park website using the Page Builder. Through this feature, you can structure sections like the hero header, attractions, activities, and facilities to create an engaging visual experience for visitors.

<Tip>
  Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
</Tip>

---

## Page Configuration

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1-2** | **Tabs** | Switch between **Draft** (editable) and **Published** (read-only view). |
| **3-4** | **Title / Slug** | Define the page title and unique URL slug. |
| **5-6** | **SEO** | Click `(+)` to configure `metaTitle`, `metaDescription`, and `shareImage` for search optimization. |
| **7** | **Add Component** | Access the structural building blocks for the page. |
| **8-9** | **Publish / Save** | Push content live immediately or save as a draft. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese versions. |

---

## Section Builder Guide

### 1. Hero Section

- **Access:** Use the **Shared** group (11) and select **Page Header** (12).
- **Fields:** Upload the **background\_image** (14/15), enable **navigation\_tabs** (16), and enter the **page\_title** (17).

### 2. Attraction Section

- **Spacing:** Add a **Spacer** component (18) and set its **height** (19) to create separation from the header.
- **Header:** Use the **Text** group (20) \> **Heading** (21). Configure the **eyebrow** (22), **heading** (23), and **position** (24).
- **Content Slider:** Use the **Dynamic** group (25) \> **Slider** (26). Set **layout** to `default` (27) and **source\_type** to `attraction` (28) to pull data from the attraction collection. Toggle **show\_dots** (30), **show\_arrows** (31), and set **item\_limits** (32).

### 3. Activities Section

- **Workflow:** Repeat the layout pattern used for the Attraction section. Add a **Spacer** (33), a **Heading** component (34) for titles/descriptions, and a **Slider** component (35) configured to fetch and display activity data items.

### 4. Facilities Section

- **Spacing & Header:** Add a **Spacer** (36) and a **Heading** component (37) to establish section separation and titles.
- **Flexbox Grid:** Go to the dynamic group and select **Flexbox** (38). Configure options including **readmore\_button\_text** (39), **view\_all\_text** (40), set **source\_type** to `facilities` (41), choose layout `grid-equal` (42), set columns to `6` (43), and define **item\_limits** (44).
- **Display Settings:** Set **show\_category\_badge** (45) and **show\_excerpt** (46) to `False`, and enter the **item\_cta\_label** (47).
- **Footer Spacing:** Add a final **Spacer** component (48) to separate the section from the footer.

<Warning>
  Always verify that your `source_type` fields point to the correct collections (e.g., `attraction` or `facilities`) before publishing to ensure dynamic data renders properly.
</Warning>