---
title: "Page Module - Create/Setup Experience Detail"
sidebarTitle: "Experience Detail"
description: "Guide for setting up the Experience Detail page layout and sidebar content in the Tempe Park CMS."
---

## Overview

The **Create/Setup Experience Detail** feature is used to build the detail page for specific experiences. It utilizes the **Page Builder** mechanism to manage core details such as operating hours, age requirements, and related attraction links, ensuring a consistent and informative layout for every experience entry.

<Tip>
  Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
</Tip>

---

## Form Configuration

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1-2** | **Tabs** | Switch between **Draft** (editable) and **Published** (read-only view). |
| **3-4** | **Title / Slug** | Define the page identity and URL structure. |
| **5-6** | **SEO** | Click `(+)` to configure `metaTitle`, `metaDescription`, and `shareImage`. |
| **7** | **Add Component** | Access structural block components to build the page. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese. |

---

## Experience Detail Setup

To populate the page content, follow these steps using the Page Builder:

### Component Configuration

- **Access:** Click **Add a component to blocks** (7) and select the **Experience** component group (11).
- **Initialization:** Click on **Experience Detail** (12) to begin configuring the layout.

### Configuration Fields

| Field | Description |
| :-- | :-- |
| **content\_type** | Select the source type (e.g., `attraction`) to map the dynamic content. |
| **breadcrumb\_parent\_label** | Label for the parent breadcrumb on the detail page. |
| **sidebar\_label\_opening\_hours\_weekdays** | Custom label for weekday opening hours. |
| **sidebar\_label\_opening\_hours\_weekend** | Custom label for weekend opening hours. |
| **sidebar\_label\_age\_requirements** | Label for the age requirement display in the sidebar. |
| **sidebar\_label\_note** | Label for the notes/additional information section. |

### Related Attraction Settings

- **related\_attraction\_section\_heading:** Enter the section title for related attractions.
- **related\_attraction\_cta\_label:** Label for the main "Explore More" button.
- **related\_attraction\_cta\_url:** URL destination for the main CTA.
- **related\_attraction\_item\_cta\_label:** Label for the CTA button attached to individual related items.

<Warning>
  Ensure the `content_type` correctly matches your collection source to prevent empty sections on the front end.
</Warning>