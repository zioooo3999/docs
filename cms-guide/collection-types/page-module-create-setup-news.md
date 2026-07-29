---
title: "Page Module - Create/Setup News"
sidebarTitle: "News"
description: "Step-by-step guide for building and configuring the 'News' page in the Tempe Park CMS using the Page Builder."
---

## Overview

The **Create/Setup News** feature in the Page module allows you to create a new News page and structure the front page content of the Tempe Park website using the Page Builder. This feature enables administrators to add and organize sections such as the banner highlight and news listing insights to suit the website's visual and informational needs.

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
| **7** | **Add Component** | Access structural building blocks for the page. |
| **8-9** | **Publish / Save** | Push content live immediately or save changes as a draft. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese versions. |

---

## Section Builder Guide

### 1. Banner Section

- **Access:** Click **Add a component to blocks** (7) and select the **News** component group (11).
- **Component:** Choose **News Highlight Banner** (12) to set up the featured banner image on the page.
- **Fields:** Enter the **read\_more\_label** (13) with localized static text (e.g., "Read More" for English) for the CTA button on the banner.

### 2. News List / Other Insights Section

- **Access:** Return to the news component group and select **News List** (14).
- **Listing Settings:** Configure the static filter and section header labels based on the active language:
  - **listing\_section\_heading:** Section title for other news insights (e.g., "OTHER INSIGHTS") (15).
  - **all\_categories\_label:** Label for filtering all categories (e.g., "All Categories") (16).
  - **sort\_by\_label:** Label for sorting options (e.g., "Sort By") (17).
  - **year\_label:** Label for year-based filters (e.g., "Year") (18).
  - **oldest\_label:** Label for sorting by oldest items (e.g., "Oldest") (19).
  - **newest\_label:** Label for sorting by latest items (e.g., "Newest") (20).
  - **all\_years\_label:** Label for all years filter option (e.g., "All") (21).

<Warning>
  Always verify that all static text labels (`read_more_label`, `listing_section_heading`, etc.) are translated accurately across all multilingual tabs before publishing.
</Warning>