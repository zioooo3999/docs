---
title: "Page Module - Create/Setup Plan Your Visit"
sidebarTitle: "Plan Your Visit"
description: "Step-by-step guide for building and configuring the 'Plan Your Visit' page in the Tempe Park CMS."
---

## Overview

The **Create/Setup Plan Your Visit** feature in the Page module allows administrators to construct a dynamic, visitor-friendly planning page. By utilizing the **Page Builder** mechanism, you can add various functional sections—such as ticket purchasing, visitor guides, calendars, and upcoming events—to create an intuitive experience for park guests.

<Tip>
  Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
</Tip>

---

## Page Configuration

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1-2** | **Tabs** | Switch between **Draft** (editable) and **Published** (read-only view). |
| **3-4** | **Title / Slug** | Define the page identity and URL structure. |
| **5-6** | **SEO** | Click `(+)` to add `metaTitle`, `metaDescription`, and `shareImage` for search engine indexing. |
| **7** | **Add Component** | Access the library of structural blocks for the Page Builder. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese. |

---

## Section Builder Guide

### 1. Hero Section

- **Access:** Use the **Shared** group (11) and select **Page Header** (12).
- **Fields:** Upload the **background\_image** (14/15), enable **navigation\_tabs** (16) if required, and enter the **page\_title** (17).

### 2. Buy Ticket Section

- **Access:** Use the **Plan** group (18) and select **Buy Ticket** (19).
- **Content:** Add a **description** (21) and section **image** (22).
- **Buttons:** Configure the **Button Regular** group (23) for individual tickets and the **button\_group** (27) for group tickets, specifying **text**, **link**, and **style** for each.

### 3. Visitor's Guide Section

- **Headers:** Use the **Text** group (33) \> **Heading** (34). Set the **eyebrow** (36), **position** (37), and **heading** (38).
- **Tabs:** Select the **Visitor Guide** component (39). Add tabs via the `(+)` button (41), defining the **image** (42), **tab\_label** (43), **style** (44), and **title** (45).
- **CTA:** Optionally add a CTA (47) per tab with **text**, **link**, and **style**.

### 4. Calendar Section

- **Access:** Add a header (Steps 33-37), then use the **Plan** group (18) to select **Calendar** (52).
- **Settings:** Choose the schedule **view** (weekly/monthly) (53) and set the **items\_limit** (54).

### 5. Upcoming Event Section

- **Access:** Add a header (Steps 33-37), then use the **Triple Active Slider** (55).
- **Source:** Select **manual** (56) to input event details including **image** (58), **time** (59), **title** (60), **location** (61), **link** (62), and **date** (63).

### 6. How To Get Here Section

- **Workflow:** Add a final header using the **Heading** component (Steps 33-38), then populate content using the **Visitor Guide** component steps (Steps 39-50) adjusted to fit map or transit information.

<Warning>
  Always verify your inputs in the **SEO** and **CTA link** fields before publishing to ensure proper navigation and search visibility.
</Warning>