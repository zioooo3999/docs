---
title: "Create / Setup FAQ"
sidebarTitle: "FAQ"
description: "Comprehensive guide for configuring the FAQ page layout in the Tempe Park CMS using the Page Builder, including hero headers and dynamic FAQ accordion integration."
icon: "hands-helping"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup FAQ** feature in the Page module allows administrators to design and structure the Frequently Asked Questions page layout using the Page Builder. Utilizing this mechanism, administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors—integrating a hero header section alongside a dynamic accordion component that seamlessly pulls content directly from the FAQ collection.

---

## Form Fields & Interface Reference

<Frame>
  ![FAQ Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the FAQ page sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Hero Section">
    ### Hero Section Controls (No. 11–17)

    <Frame>
      ![Hero Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **Shared** | Group Button | A grouping of content components typically used on all pages, or common components commonly used to structure content on a page. Click to display common components. |
    | **12** | **Page Header** | Component | In the components group, click the Page Header component to add a header or hero section to this page. |
    | **13** | **Page Header Display** | Layout View | Form interface view displayed after clicking Page Header, showing detail input fields. |
    | **14** | **background\_image** | Media Field | Image field used to store hero section background images. |
    | **15** | **(\+) Click to add an asset** | Action | Click this button to upload an image to be applied as the hero section image. |
    | **16** | **navigation\_tabs** | Toggle Switch | Slide to `true` if this page has tabbed navigation controls. |
    | **17** | **page\_title** | Text Field | Enter the main display title for the hero section page header. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Page Header Block">
        Click **Add a component to blocks** (No. 7), select the **Shared** component group (No. 11), and click **Page Header** (No. 12).
      </Step>
      <Step title="Upload Hero Background">
        In **background\_image** (No. 14), click **(\+) Click to add an asset** (No. 15) to upload or select the background banner image.
      </Step>
      <Step title="Configure Title & Navigation">
        Toggle **navigation\_tabs** (No. 16) to `true` if tab controls are used, and enter the main page header text in **page\_title** (No. 17).
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. FAQ Section">
    ### FAQ Section Controls (No. 18–19)

    <Frame>
      ![FAQ Accordion Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **FAQ Accordion** | Component | Return to the Shared component group to select this component, used to display fields required by the FAQ page builder. |
    | **19** | **source\_type** | Dropdown Field | Select `faq` from the source type selection dropdown, ensuring that data displayed on this page is automatically populated from the FAQ collection type. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add FAQ Accordion Block">
        Click **Add a component to blocks** (No. 7), access the **Shared** component group (No. 11), and click **FAQ Accordion** (No. 18).
      </Step>
      <Step title="Configure Collection Source Type">
        In the **source\_type** dropdown field (No. 19), select `faq` to connect the page module dynamically to the FAQ collection entries.
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup FAQ**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to sequentially insert required blocks (Page Header and FAQ Accordion).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the FAQ page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Dynamic Collection Binding" color="#10b981" icon="database">
    Automatic synchronization with the main FAQ collection type via the `source_type` binding property.
  </Card>

  <Card title="Interactive Accordion Interface" color="#38bdf8" icon="list-dropdown">
    Clean, space-efficient accordion view optimizing content organization and user readability for common questions.
  </Card>

  <Card title="Flexible Visual Hero" color="#f59e0b" icon="image">
    Customizable header block supporting dedicated background banners and navigation tab toggles.
  </Card>
</CardGroup>

---

<Warning>
  Ensure that all FAQ entries in the collection are properly categorized and translated across all language tabs before publishing to ensure the accordion displays content correctly for all global visitors.
</Warning>