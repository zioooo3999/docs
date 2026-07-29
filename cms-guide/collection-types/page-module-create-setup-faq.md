---
title: "Page Module - Create/Setup FAQ"
sidebarTitle: "FAQ"
description: "Guide for configuring the FAQ page in the Tempe Park CMS, including hero header and dynamic FAQ accordion setup."
---

## Overview

The **Create/Setup FAQ** feature allows administrators to design the Frequently Asked Questions page using the Page Builder. This module supports the integration of a hero section and a dynamic accordion component that pulls data directly from the FAQ collection.

<Tip>
  Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
</Tip>

---

## Form Configuration

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1-2** | **Tabs** | Switch between **Draft** (editable) and **Published** (read-only view). |
| **3-4** | **Title / Slug** | Define the page title and unique URL slug. |
| **5-6** | **SEO** | Click `(+)` to configure `metaTitle`, `metaDescription`, and `shareImage`. |
| **7** | **Add Component** | Access structural building blocks for the page. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese versions. |

---

## Section Builder Guide

### 1. Hero Section

- **Access:** Use the **Shared** group (11) and select **Page Header** (12).
- **Fields:** Upload the **background\_image** (14/15), toggle **navigation\_tabs** (16), and enter the **page\_title** (17).

### 2. FAQ Section

- **Component:** Navigate back to the **Shared** component group (11) and select **FAQ Accordion** (18).
- **Data Source:** Configure the **source\_type** (19) field by selecting `faq`. This ensures the page automatically pulls content from the pre-defined FAQ collection type.

<Warning>
  Ensure that all FAQ entries in the collection are properly categorized and translated before publishing to ensure the accordion displays content correctly across all language versions.
</Warning>