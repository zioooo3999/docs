---
title: "Create / Setup Education Detail"
sidebarTitle: "Education Detail"
description: "Comprehensive guide for setting up the Education Detail page layout, sidebar program labels, schedules, and related school program links in the Tempe Park CMS."
icon: "book-open-reader"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Education Detail** feature in the Page module allows administrators to build and configure detailed information templates for educational programs. Utilizing the **Page Builder** mechanism, this module manages core content settings such as program descriptions, schedules, sidebar call-to-actions, breadcrumb navigation, and related school program links to ensure a consistent educational layout.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Education Detail Setup Form Interface](/images/0-\(53\).png)
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

Configure the Education Detail template and labels sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Education Detail Setup">
    ### Education Detail Controls (No. 11–20)

    <Frame>
      ![Education Detail Component Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **experience** | Group Button | To display this component, click step No. 7 (**Add a component to blocks**), then click this component group. |
    | **12** | **Experience Detail** | Component | Click this component to setup the education detail page options such as labeling and sidebar fields. |
    | **13** | **breadcrumb\_parent\_label** | Text Field | Enter the parent breadcrumb label on this page (e.g., _Education_). |
    | **14** | **sidebar\_label\_about\_program** | Text Field | Enter the section title label for the **ABOUT THIS PROGRAM** sidebar section. |
    | **15** | **sidebar\_cta\_label** | Text Field | Enter the label text for the CTA button in the About This Program sidebar section. |
    | **16** | **sidebar\_cta\_url** | Text Field | Enter the URL destination for the CTA button in the **ABOUT THIS PROGRAM** sidebar. |
    | **17** | **schedule\_section\_heading** | Text Field | Enter the section title heading for the **Program Schedule** block. |
    | **18** | **related\_section\_heading** | Text Field | Enter the title text for the **Explore Other School Programs** section. |
    | **19** | **sidebar\_join\_label** | Text Field | Enter the section title heading for **Join This Program** in the sidebar. |
    | **20** | **related\_item\_readmore\_label** | Text Field | Enter the CTA button label text for **Learn More** items in the related school programs section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Component Block">
        Click **Add a component to blocks** (No. 7), select the **experience** component group (No. 11), and click **Experience Detail** (No. 12).
      </Step>
      <Step title="Configure Navigation & Program Sidebar">
        Specify parent link text in **breadcrumb\_parent\_label** (No. 13). Fill in **sidebar\_label\_about\_program** (No. 14) along with **sidebar\_cta\_label** (No. 15) and **sidebar\_cta\_url** (No. 16).
      </Step>
      <Step title="Set Schedule & Action Headings">
        Define main page section titles in **schedule\_section\_heading** (No. 17) and enter sidebar conversion titles in **sidebar\_join\_label** (No. 19).
      </Step>
      <Step title="Configure Related School Programs">
        Set the cross-promotional title in **related\_section\_heading** (No. 18) and specify card button text in **related\_item\_readmore\_label** (No. 20).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Education Detail**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Component Controls via Page Builder">
    Click **Add a component to blocks** (No. 7) to insert the **Experience Detail** block and configure content mapping, schedule headings, and sidebar CTA settings.
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the detail template live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Program Sidebar CTA" color="#10b981" icon="sidebar">
    Highlight program details with dedicated "About This Program" and "Join This Program" call-to-action sidebar blocks.
  </Card>

  <Card title="Program Schedule Display" color="#38bdf8" icon="calendar-days">
    Organized heading structures dedicated to displaying session schedules and excursion timelines.
  </Card>

  <Card title="Cross-Educational Discovery" color="#f59e0b" icon="graduation-cap">
    Seamlessly guide visitors to additional educational activities via "Explore Other School Programs" links.
  </Card>
</CardGroup>

---

<Warning>
  Always verify the accuracy of your CTA URLs (`sidebar_cta_url`) and program labeling across all language versions before publishing to ensure seamless user navigation.
</Warning>