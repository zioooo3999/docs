---
title: "Page Module - Create/Setup Carrer Detail"
sidebarTitle: "Career Detail"
description: "Guide for configuring the Career Detail page layout, including job requirements, responsibilities, and application call-to-actions in the Tempe Park CMS."
---

## Overview

The **Create/Setup Career Detail** feature allows administrators to structure individual job vacancy pages. Using the Page Builder, you can manage the display of critical career information such as job descriptions, responsibilities, requirements, and benefits, ensuring a comprehensive view for potential candidates.

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
| **7** | **Add Component** | Access structural building blocks for the page builder. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese versions. |

---

## Career Detail Setup

To populate the career detail page, follow these steps using the Page Builder:

### Component Configuration

- **Access:** Click **Add a component to blocks** (7) and select the **Career** component group (11).
- **Initialization:** Click on **Career Detail** (12) to begin configuring the layout fields.

### Configuration Fields

| Field | Description |
| :-- | :-- |
| **back\_label** | Label for the "Back" button in the breadcrumb navigation. |
| **career\_label** | Label for the career section in the breadcrumb navigation. |
| **share\_label** | Label for the article sharing section. |
| **job\_description\_label** | Header title for the Job Description section. |
| **responsibilities\_heading** | Header title for the Responsibilities section. |
| **requirement\_heading** | Header title for the Requirements section. |
| **perks\_benefits\_heading** | Header title for the Perks & Benefits section. |
| **apply\_label** | Label text for the "Apply Now" CTA button. |

### Additional Components

- **To Top Button:** Navigate to the **Shared** component group (21) to add the "To Top" feature.
  - **career\_variant:** Set to `TRUE` for career pages.
  - **scroll\_label / up\_label:** Define text (e.g., "Scroll", "Up") for the button.
  - **icon:** Upload the icon asset for the button (25).

<Warning>
  Always verify that all section headers (Requirements, Perks, etc.) and navigation labels are accurately translated across all language tabs before publishing.
</Warning>