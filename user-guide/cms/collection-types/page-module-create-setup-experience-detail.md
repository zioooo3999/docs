---
title: "Create / Setup Experience Detail"
sidebarTitle: "Experience Detail"
description: "Comprehensive guide for setting up the Experience Detail page layout, sidebar labels, and related attractions in the Tempe Park CMS."
icon: "circle-info"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Experience Detail** feature in the Page module is used to build and configure the template and sidebar labels for specific experience detail pages. It utilizes the **Page Builder** mechanism to manage core details—such as content type mapping, breadcrumb parents, operating hours labels, age requirements, and related attraction highlights—ensuring a consistent and informative layout across all experience entries.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Experience Detail Setup Form Interface](/images/0-\(53\).png)
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

Configure the Experience Detail template and labels sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Experience Detail Setup">
    ### Experience Detail Controls (No. 11–22)

    <Frame>
      ![Experience Detail Component Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **experience** | Group Button | To display this component, click step No. 7 (**Add a component to blocks**), then click this component group. |
    | **12** | **Experience Detail** | Component | Click this component to setup the experience page details such as labeling and sidebar configurations. |
    | **13** | **content\_type** | Dropdown | Select one of the experience detail content types to be used (e.g., select `attraction` if content comes from the attraction section). Applies to all experience sections. |
    | **14** | **breadcrumb\_parent\_label** | Text Field | Enter the parent breadcrumb label for the Experience Detail page (e.g., _Experiences_). |
    | **15** | **sidebar\_label\_opening\_hours\_weekdays** | Text Field | Enter the label text for weekday opening hours displayed in the sidebar. |
    | **16** | **sidebar\_label\_opening\_hours\_weekend** | Text Field | Enter the label text for weekend opening hours displayed in the sidebar. |
    | **17** | **sidebar\_label\_age\_requirements** | Text Field | Enter the label text for age requirements displayed in the sidebar. |
    | **18** | **sidebar\_label\_note** | Text Field | Enter the label text for additional notes displayed in the sidebar. |
    | **19** | **related\_attraction\_section\_heading** | Text Field | Enter the heading label or title for the **Related Attractions** section. |
    | **20** | **related\_attraction\_cta\_label** | Text Field | Enter the label text for the main "Explore More" CTA button in the related attractions section. |
    | **21** | **related\_attraction\_cta\_url** | Text Field | Enter the target URL destination for the main related attractions CTA button. |
    | **22** | **related\_attraction\_item\_cta\_label** | Text Field | Enter the label text for CTA buttons attached to individual related attraction cards. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Experience Detail Block">
        Click **Add a component to blocks** (No. 7), select the **experience** component group (No. 11), and click **Experience Detail** (No. 12).
      </Step>
      <Step title="Set Source Type & Navigation">
        Select the target collection type in **content\_type** (No. 13) (e.g., `attraction`) and specify the parent link text in **breadcrumb\_parent\_label** (No. 14).
      </Step>
      <Step title="Configure Sidebar Meta Labels">
        Enter the localized sidebar labels for **sidebar\_label\_opening\_hours\_weekdays** (No. 15), **sidebar\_label\_opening\_hours\_weekend** (No. 16), **sidebar\_label\_age\_requirements** (No. 17), and **sidebar\_label\_note** (No. 18).
      </Step>
      <Step title="Configure Related Attractions Block">
        Set the section title in **related\_attraction\_section\_heading** (No. 19). Specify the main section CTA **related\_attraction\_cta\_label** (No. 20) and **related\_attraction\_cta\_url** (No. 21), then define individual item card buttons in **related\_attraction\_item\_cta\_label** (No. 22).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Experience Detail**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Component Controls via Page Builder">
    Click **Add a component to blocks** (No. 7) to insert the **Experience Detail** block and configure content mapping, sidebar labels, and related item buttons.
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the detail template live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Dynamic Collection Binding" color="#10b981" icon="database">
    Map detail layouts directly to specific data models (e.g., `attraction`) using `content_type` bindings.
  </Card>

  <Card title="Customized Sidebar Metadata" color="#38bdf8" icon="sidebar">
    Configure flexible labels for opening hours, age limits, and guest guidelines across multi-language views.
  </Card>

  <Card title="Cross-Promotional Linking" color="#f59e0b" icon="link">
    Promote related attractions on experience detail pages with customizable section headings and CTA URLs.
  </Card>
</CardGroup>

---

<Warning>
  Ensure the `content_type` field correctly matches your target collection source (e.g., `attraction`) to prevent empty dynamic sections on the live website.
</Warning>