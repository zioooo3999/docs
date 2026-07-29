---
title: "Page Module - Create/Setup Career"
sidebarTitle: "Career"
description: "Step-by-step guide for configuring the 'Career' page in the Tempe Park CMS using the Page Builder, including hero headers and job listing filters."
---

## Overview

The **Create/Setup Career** feature allows administrators to build and manage the Career page. Using the Page Builder, you can structure the page with a hero banner, search/filter functionality for job seekers, and a dynamic list of job openings to ensure a user-friendly recruitment experience.

<Tip>
  Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
</Tip>

---

## Page Configuration

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

### 2. Career List Section

- **Access:** Select the **career** component group (18) and choose **Career List** (19).
- **Filters & Labels:** Configure the following static labels for your localized versions:
  - **Search/Filter:** `search_placeholder` (20), `job_level_label` (21), `job_type_label` (22), `location_label` (23).
  - **Dropdown Options:** `all_level_label` (26), `all_type_label` (27), `all_location_label` (28).
  - **Action Buttons:** `see_detail_label` (24), `apply_label` (25).
  - **Status/UI:** `closing_data_label` (29), `loading_label` (30), `showing_label` (31), `job_label` (32), `jobs_label` (33).
- **Empty State:** If no jobs match search criteria, configure: `not_found_label` (34), `not_found_description` (35), and `not_found_image` (36).

### 3. Navigation & Variants

- **To Top Button:** Select the component (37) and set `career_variant` to `TRUE` (38).
- **Scroll UI:** Define `scroll_label` (39), `up_label` (40), and upload the `icon` (41).

<Warning>
  Ensure all labels are localized correctly across the multilingual tabs. Specifically, double-check the `not_found_description` to maintain the tone of the UI guidelines (e.g., "Please check your spelling or try different keywords.").
</Warning>