---
title: "Create / Setup News"
sidebarTitle: "News"
description: "Comprehensive guide for building and configuring the News page in the Tempe Park CMS using the Page Builder."
icon: "newspaper"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup News** feature in the Page module allows administrators to create a new News page and structure the front page content of the Tempe Park website using the Page Builder. This feature enables administrators to add and organize dynamic sections—such as highlighted news banners, category filters, and news listing grids—to suit the website's visual and informational needs.

Administrators can organize content, section order, and page layout to ensure information is presented in an attractive, dynamic, and intuitive manner for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![News Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the News page sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Banner Section">
    ### Banner Section Controls (No. 11–13)

    <Frame>
      ![News Banner Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **News** | Group Button | Select the news component group after clicking "Add a component to blocks" to display news components. |
    | **12** | **News Highlight Banner** | Component | Click this component to display the fields needed to setup the main featured news banner on this page. |
    | **13** | **read\_more\_label** | Text Field | Enter the localized static text for the Read More CTA button on the banner image (e.g., _Read More_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add News Highlight Block">
        Click **Add a component to blocks** (No. 7), select the **News** component group (No. 11), and click **News Highlight Banner** (No. 12).
      </Step>
      <Step title="Configure Banner CTA Text">
        Fill in the **read\_more\_label** (No. 13) field with the appropriate static button text matching the current active language version.
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. News List / Other Insights Section">
    ### News List Section Controls (No. 14–21)

    <Frame>
      ![News List Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **14** | **News List** | Component | Select News List from the news component group to display the fields required for the news grid and filter controls. |
    | **15** | **listing\_section\_heading** | Text Field | Enter the static section header text for the lower news section (e.g., _OTHER INSIGHTS_). |
    | **16** | **all\_categories\_label** | Text Field | Enter the localized text for the all-categories dropdown filter option (e.g., _All Categories_). |
    | **17** | **sort\_by\_label** | Text Field | Enter the localized text label for the sorting filter control (e.g., _Sort By_). |
    | **18** | **year\_label** | Text Field | Enter the localized text label for the year filter control (e.g., _Year_). |
    | **19** | **oldest\_label** | Text Field | Enter the localized text option for sorting by oldest entries (e.g., _Oldest_). |
    | **20** | **newest\_label** | Text Field | Enter the localized text option for sorting by latest entries (e.g., _Newest_). |
    | **21** | **all\_years\_label** | Text Field | Enter the localized text option for selecting all years in the filter (e.g., _All_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add News List Component">
        Return to the **News** component group and select **News List** (No. 14).
      </Step>
      <Step title="Configure Section Heading">
        Enter the lower section title in **listing\_section\_heading** (No. 15) matching the selected language.
      </Step>
      <Step title="Set Filter Labels & Sort Controls">
        Populate filter dropdown labels: **all\_categories\_label** (No. 16), **sort\_by\_label** (No. 17), and **year\_label** (No. 18).
      </Step>
      <Step title="Configure Dropdown Options">
        Provide static text for sort order options: **oldest\_label** (No. 19), **newest\_label** (No. 20), and **all\_years\_label** (No. 21).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup News**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to build out required visual modules sequentially (News Highlight Banner and News List Filter Block).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the News page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Featured News Banner" color="#10b981" icon="bullhorn">
    Prominently display headline stories and announcements using high-impact hero banners with direct CTAs.
  </Card>

  <Card title="Multi-Filter News Grid" color="#38bdf8" icon="filter">
    Allow users to sort and filter news articles by category, publishing year, or chronological order (newest/oldest).
  </Card>

  <Card title="Multilingual Static Labels" color="#f59e0b" icon="language">
    Fully customizable front-end labels ensuring seamless translation across English, Indonesian, and Chinese views.
  </Card>
</CardGroup>

---

<Warning>
  Always verify that all static text labels (`read_more_label`, `listing_section_heading`, etc.) are translated accurately across all multilingual tabs before publishing.
</Warning>