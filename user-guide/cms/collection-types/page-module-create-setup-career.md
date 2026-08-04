---
title: "Create / Setup Career"
sidebarTitle: "Career"
description: "Comprehensive guide for configuring the Career page layout in the Tempe Park CMS using the Page Builder, including hero headers, job search filters, and navigation controls."
icon: "briefcase"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Career** feature in the Page module allows administrators to build and manage the Career page. Utilizing the Page Builder mechanism, administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for job seekers—combining hero banners, search and filtering tools, dynamic job listing labels, empty states, and back-to-top navigation controls.

---

## Form Fields & Interface Reference

<Frame>
  ![Career Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Career page sequentially using the controls detailed below.

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
  <Tab title="2. Career List Section">
    ### Career List Section Controls (No. 18–36)

    <Frame>
      ![Career List Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **career** | Group Button | Select this component group to access components needed for the career page. |
    | **19** | **Career List** | Component | Click this component to display required detail fields for the job openings list and filters. |
    | **20** | **search\_placeholder** | Text Field | Enter placeholder prompt text for the job search input field. |
    | **21** | **job\_level\_label** | Text Field | Enter label text for the Job Level dropdown column filter. |
    | **22** | **job\_type\_label** | Text Field | Enter label text for the Job Type dropdown column filter. |
    | **23** | **location\_label** | Text Field | Enter label text for the Location dropdown column filter. |
    | **24** | **see\_detail\_label** | Text Field | Enter label text for the "SEE DETAIL" button on job listing cards. |
    | **25** | **apply\_label** | Text Field | Enter label text for the "APPLY" action button on job listing cards. |
    | **26** | **all\_level\_label** | Text Field | Enter label text for the "All Levels" option in the job level dropdown filter. |
    | **27** | **all\_type\_label** | Text Field | Enter label text for the "All Types" option in the job type dropdown filter. |
    | **28** | **all\_location\_label** | Text Field | Enter label text for the "All Locations" option in the location dropdown filter. |
    | **29** | **closing\_data\_label** | Text Field | Enter label text indicating vacancy closing date status. |
    | **30** | **loading\_label** | Text Field | Enter label text displayed while job listing data is fetching/loading. |
    | **31** | **showing\_label** | Text Field | Enter text for "Showing" (e.g., used in sentence "Showing {x} jobs"). |
    | **32** | **job\_label** | Text Field | Enter label text for single "job" noun result count display. |
    | **33** | **jobs\_label** | Text Field | Enter label text for plural "jobs" noun result count display. |
    | **34** | **not\_found\_label** | Text Field | Enter title header text displayed when search yields no job results. |
    | **35** | **not\_found\_description** | Text Field | Enter body text displayed when search yields no results (e.g., _"Please check your spelling or try different keywords."_). |
    | **36** | **not\_found\_image** | Media Field | Select or upload graphic illustration for the empty search state. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Career List Block">
        Click **Add a component to blocks** (No. 7), select the **career** component group (No. 18), and click **Career List** (No. 19).
      </Step>
      <Step title="Configure Search & Dropdown Labels">
        Define search prompt in **search\_placeholder** (No. 20) and configure filter titles (No. 21–23) alongside default "All" choices (No. 26–28).
      </Step>
      <Step title="Set Action Buttons & Dynamic UI States">
        Define card button labels (No. 24, 25), status alerts (No. 29, 30), and search count words (No. 31–33).
      </Step>
      <Step title="Configure Empty Search State">
        Upload illustration in **not\_found\_image** (No. 36) and enter clear guidance text in **not\_found\_label** (No. 34) and **not\_found\_description** (No. 35).
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. To Top Navigation">
    ### To Top Button Controls (No. 37–41)

    <Frame>
      ![To Top Button Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **37** | **To Top Button** | Component | Select this component from the group to configure scroll-to-top navigation. |
    | **38** | **career\_variant** | Toggle Switch | Set to `TRUE` for career page layout, or `FALSE` for standard pages. |
    | **39** | **scroll\_label** | Text Field | Enter text for the primary scroll action prompt (e.g., _Scroll_). |
    | **40** | **up\_label** | Text Field | Enter text for the direction prompt (e.g., _Up_). |
    | **41** | **icon** | Media Field | Select or upload directional arrow icon asset. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add To Top Component">
        Click **Add a component to blocks** (No. 7) and select **To Top Button** (No. 37).
      </Step>
      <Step title="Set Variant & Labeling">
        Toggle **career\_variant** to `TRUE` (No. 38), and input action text in **scroll\_label** (No. 39) and **up\_label** (No. 40).
      </Step>
      <Step title="Upload Arrow Icon">
        Select or upload directional graphic asset in **icon** (No. 41).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Career**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to sequentially construct required visual modules (Page Header, Career List filters, and To Top navigation).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the Career page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Multi-Criteria Search & Filter" color="#10b981" icon="sliders">
    Filter job listings by Job Level, Job Type, and Location with fully customizable dropdown labels and placeholder text.
  </Card>

  <Card title="Dynamic UI & Empty States" color="#38bdf8" icon="layer-group">
    Tailored response messages for dynamic result counters, loading status, and user-friendly "no results found" screens.
  </Card>

  <Card title="Smooth Navigation Controls" color="#f59e0b" icon="circle-chevron-up">
    Integrated To Top Button component with custom icon and scroll prompts designed for high-density listing pages.
  </Card>
</CardGroup>

---

<Warning>
  Ensure all labels are localized correctly across all multilingual tabs before publishing. Specifically, double-check `not_found_description` to maintain UI guidelines (e.g., "Please check your spelling or try different keywords.").
</Warning>