---
title: "Page Module - Create/Setup News Detail"
sidebarTitle: "News Detail"
description: "Guide for configuring the News Detail page layout, metadata, and sidebar ticket components in the Tempe Park CMS."
---

## Overview

The **Create/Setup News Detail** feature enables administrators to structure the individual detail page for news articles using the Page Builder. This module manages critical display elements such as breadcrumb navigation, publication date labels, sharing functionality, and sidebar redirect links for ticketing.

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
| **7** | **Add Component** | Access structural block components for the page builder. |
| **10** | **Multilingual** | Toggle between English, Indonesian, and Chinese versions. |

---

## News Detail Setup

To populate the news article details, follow these steps using the Page Builder:

### Component Configuration

- **Access:** Click **Add a component to blocks** (7) and select the **News** component group (11).
- **Initialization:** Click on **News Detail** (12) to begin configuring the layout fields.

### Configuration Fields

| Field | Description |
| :-- | :-- |
| **breadcrumb\_parent\_label** | Parent labeling for the breadcrumb navigation. |
| **share\_label** | Custom label for the article sharing section. |
| **published\_date\_label** | Custom label for the publication date display. |
| **career\_variant** | Set to `false` (default for news) or `true` if this page is a career entry. |
| **ticket\_label** | Label for the ticketing section in the right sidebar. |
| **ticket\_icon** | Icon for the ticketing sidebar element. |
| **ticket\_href** | Target URL/slug for the ticketing page. |

### Additional Components

- **To Top Button:** Navigate to the **Shared** component group (16) and select the **To Top Button** component to add the quick-scroll feature to the page.

<Warning>
  Always verify that the `ticket_href` links to a valid page to ensure the call-to-action correctly redirects users to the ticketing landing page.
</Warning>