---
title: "Page Module - Create/Setup Innovatio"
sidebarTitle: "Innovation"
description: "Guide for configuring the Innovation page, including products, menu inspiration, collaborations, and partnership inquiries in the Tempe Park CMS."
---

## Overview

The **Create/Setup Innovation** feature allows administrators to structure the Innovation page layout using the Page Builder. This module supports diverse content blocks, including hero headers, product collections, journey/inspiration menus, industry collaborations, and partnership inquiry forms.

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
| **7** | **Add Component** | Access the structural building blocks for the page. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese versions. |

---

## Section Builder Guide

### 1. Hero Section

- **Access:** Use the **Shared** group (11) and select **Page Header** (12).
- **Fields:** Upload the **background\_image** (14/15), toggle **navigation\_tabs** (16), and enter the **page\_title** (17).

### 2. Our Product Section

- **Setup:** Add a **Spacer** (18) for layout control, then add a **Heading** (21) using the **Text** group (20) to set the **eyebrow** (22) and **heading** (23).
- **Collection:** Select the **Curated Collection** component (26) from the **innovation** group (25).
- **Fields:** Configure **filter\_label** (27), **buy\_button\_label** (28), and **all\_category\_label** (29).

### 3. Menu Inspiration

- **Setup:** Return to the **Heading** component to title the section.
- **Component:** Select the **Journey Section** (31) from the innovation group.
- **Fields:** Set the **cta\_label** (32) and **source\_type** (33) (default pulls from the Inspiration Menu collection).

### 4. Collaboration Section

- **Component:** Select the **Industry Collaboration** (35) from the innovation group.
- **Cards:** Click `(+)` on the **Industries** field (36) to add entries with **icon** (37), **title** (38), and **description** (39).

### 5. Inquiries Section (Partnership)

- **Component:** Select the **Partnership Opportunity** (41) component.
- **Configuration:** Fill in the **Heading** (42), **Image** (43), **cta\_label** (44), and **cta\_url** (45).
- **Form Fields:** Configure all input labels (Name, Company, Email, Phone, etc.) (47-53) and placeholders (54-59).
- **Alerts:** Set the **success\_message** (60) and **error\_message** (61) for form submission handling.

<Warning>
  Always ensure that the form field placeholders and inquiry dropdown options are accurately translated for each multilingual tab.
</Warning>