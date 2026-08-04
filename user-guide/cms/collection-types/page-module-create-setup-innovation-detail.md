---
title: "Create / Setup Innovation Detail"
sidebarTitle: "Innovation Detail"
description: "Comprehensive guide for setting up the Innovation Detail page layout and static product labels in the Tempe Park CMS."
icon: "cube"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Innovation Detail** feature in the Page module is used to build and configure the template and static interface labels for specific innovation or product detail pages. Utilizing the **Page Builder** mechanism, administrators can configure essential interface labels for product variants, sizing options, and retail availability information, ensuring a clear, localized, and consistent user experience across product detail views.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Innovation Detail Setup Form Interface](/images/0-\(53\).png)
</Frame>

| No | Field / Element | Type | Function & Description |
| :-- | :-- | :-- | :-- |
| **1** | **Tab Draft** _(editable form)_ | Tab | Use this form tab when creating or modifying a draft data entry. |
| **2** | **Tab Published** | Tab | Read-only view showing the current published version of the page. |
| **3** | **title** | Text Field | Enter the primary page title. |
| **4** | **slug** | Text Field | Enter the unique URL-friendly slug identifier for the page. |
| **5** | **this** | Group Field | Column to fill in SEO grouping to fill in SEO page. |
| **6** | **No entry yet. Click to add one.** | Action Button | Click the (\+) button to display the SEO input column. After clicking, the `metaTitle`, `metaDescription`, and `shareImage` columns will appear. Fill them in according to the page you want to add. |
| **7** | **Add a component to blocks** | Action Button | Use or click this button to add the component blocks needed to structure the CMS content on a page. |
| **8** | **Publish** | Control | Use this button to directly publish the data to the website landing page. Data published in the collection can also be used as a relationship to data from other modules. |
| **9** | **Save button** | Control | Stores the entry as a **Draft** without making it publicly visible on the live website. |
| **10** | **Multilingual Button** | Control | Switch or add content versions in **English**, **Indonesian**, or **Chinese**. |

---

## Section Builder Reference & Procedures

Configure the Innovation Detail template and labels sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Innovation Detail Setup">
    ### Innovation Detail Controls (No. 11–15)

    <Frame>
      ![Innovation Detail Component Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **innovation** | Group Button | To display this component, click step No. 7 (**Add a component to blocks**), then click this component group. |
    | **12** | **Innovation Detail** | Component | Click on this component in the innovation group to set up the static content of the innovation detail page. |
    | **13** | **select\_variant\_label** | Text Field | Enter or name the static label text for the product variant selector (e.g., _Select Variant_). |
    | **14** | **choose\_size\_label** | Text Field | Enter or name the static label text for the product size option selector (e.g., _Choose Size_). |
    | **15** | **available\_on\_label** | Text Field | Enter or name the static label text for the retail/platform availability section (e.g., _Available On_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Component Block">
        Click **Add a component to blocks** (No. 7), select the **innovation** component group (No. 11), and click **Innovation Detail** (No. 12).
      </Step>
      <Step title="Set Product Option Labels">
        Enter the localized static text for variant selection in **select\_variant\_label** (No. 13) and sizing options in **choose\_size\_label** (No. 14).
      </Step>
      <Step title="Configure Availability Heading">
        Define the availability channel label in **available\_on\_label** (No. 15) matching the selected active language view.
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Innovation Detail**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Component Controls via Page Builder">
    Click **Add a component to blocks** (No. 7) to insert the **Innovation Detail** block and configure variant, size, and channel availability labels.
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the detail template live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Variant Selection Labels" color="#10b981" icon="layer-group">
    Customizable interface labels for product colorways, flavors, or material variations.
  </Card>

  <Card title="Sizing & Specification Controls" color="#38bdf8" icon="ruler-combined">
    Configurable front-end headings for unit sizing, portions, or package volume choices.
  </Card>

  <Card title="Multi-Channel Retail Display" color="#f59e0b" icon="store">
    Dedicated section headers to display store locations, partner retailers, or e-commerce links.
  </Card>
</CardGroup>

---

<Warning>
  Always verify that all static text labels (`select_variant_label`, `choose_size_label`, `available_on_label`) are accurately translated across all multilingual tabs before publishing to ensure a seamless experience for all global users.
</Warning>