---
title: "Create / Setup Career Detail"
sidebarTitle: "Career Detail"
description: "Comprehensive guide for configuring the Career Detail page layout, section headers, breadcrumbs, and application CTA controls in the Tempe Park CMS."
icon: "file-user"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Career Detail** feature in the Page module allows administrators to structure and configure the static interface labels for individual job vacancy pages. Utilizing the Page Builder mechanism, administrators can manage the display and localized headers of critical career sections—such as job descriptions, core responsibilities, requirements, perks & benefits, breadcrumb navigation, and call-to-action (CTA) buttons—ensuring a comprehensive, professional, and clear layout for potential candidates.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for job seekers.

---

## Form Fields & Interface Reference

<Frame>
  ![Career Detail Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Career Detail page sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Career Detail Setup">
    ### Career Detail Controls (No. 11–20)

    <Frame>
      ![Career Detail Component Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **Career** | Group Button | After clicking "Add a component to blocks", click on this component group to display the Career Detail component. |
    | **12** | **Career Detail** | Component | Click this component to display the fields required to fill in the static content of the career details. |
    | **13** | **back\_label** | Text Field | Enter the back label text (return to previous page) for the Breadcrumb Navigation on the career detail page. |
    | **14** | **share\_label** | Text Field | Enter the share section labeling on the career detail page. |
    | **15** | **job\_description\_label** | Text Field | Enter the section title header for the job description on the career detail page. |
    | **16** | **requirement\_heading** | Text Field | Enter the section title header for the requirement description on the career detail page. |
    | **17** | **career\_label** | Text Field | Enter the career breadcrumb item label following back navigation on the career detail page. |
    | **18** | **apply\_label** | Text Field | Enter the button label text for the primary "Apply" CTA on the career detail page. |
    | **19** | **responsibilities\_heading** | Text Field | Enter the section title header for the responsibilities description on the career detail page. |
    | **20** | **perks\_benefits\_heading** | Text Field | Enter the section title header for the Perks & Benefits description on the career detail page. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Career Detail Component">
        Click **Add a component to blocks** (No. 7), select the **Career** component group (No. 11), and click **Career Detail** (No. 12).
      </Step>
      <Step title="Configure Breadcrumbs & Action Labels">
        Enter breadcrumb navigation text in **back\_label** (No. 13) and **career\_label** (No. 17). Input social sharing prompt in **share\_label** (No. 14) and main application CTA in **apply\_label** (No. 18).
      </Step>
      <Step title="Set Section Headings">
        Define localized section titles for **job\_description\_label** (No. 15), **responsibilities\_heading** (No. 19), **requirement\_heading** (No. 16), and **perks\_benefits\_heading** (No. 20).
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. To Top Navigation">
    ### To Top Button Controls (No. 21–25)

    <Frame>
      ![To Top Button Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **21** | **To Top Button** | Component | Access the Shared component group and click To Top Button to display fields needed to configure scroll up functionality on this page. |
    | **22** | **career\_variant** | Toggle Switch | Select `FALSE` if the page is not a career page, select `TRUE` otherwise. |
    | **23** | **scroll\_label** | Text Field | Enter the word "scroll" to bring up the scroll label for scroll up. |
    | **24** | **up\_label** | Text Field | Enter the word "up" to bring up the scroll label for scroll up. |
    | **25** | **icon** | Media Field | Enter or upload an icon asset for the scroll up button icon. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add To Top Component">
        Click **Add a component to blocks** (No. 7), select the **Shared** component group, and click **To Top Button** (No. 21).
      </Step>
      <Step title="Configure Variant & Text">
        Set **career\_variant** to `TRUE` (No. 22). Enter primary action text in **scroll\_label** (No. 23) and direction text in **up\_label** (No. 24).
      </Step>
      <Step title="Upload Button Graphic">
        Upload or select the directional arrow graphic in **icon** (No. 25).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Career Detail**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Components via Page Builder">
    Click **Add a component to blocks** (No. 7) to sequentially insert the **Career Detail** labels block and the **To Top Button** navigation control.
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the Career Detail template live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Structured Section Headings" color="#10b981" icon="align-left">
    Customizable headings for Job Description, Responsibilities, Requirements, and Perks & Benefits to maintain formatting standards.
  </Card>

  <Card title="Breadcrumbs & Share Controls" color="#38bdf8" icon="route">
    Configurable breadcrumb links and social sharing callouts for seamless navigational UX across career pages.
  </Card>

  <Card title="Smooth Scroll Navigation" color="#f59e0b" icon="circle-chevron-up">
    Integrated back-to-top component optimized with career variant toggles, scroll labels, and custom directional icons.
  </Card>
</CardGroup>

---

<Warning>
  Always verify that all section headers (Requirements, Perks, etc.) and navigation labels are accurately translated across all language tabs before publishing to ensure a seamless experience for all global candidates.
</Warning>