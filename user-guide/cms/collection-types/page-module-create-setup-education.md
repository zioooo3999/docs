---
title: "Create / Setup Education"
sidebarTitle: "Education"
description: "Comprehensive guide for building and configuring the Education page in the Tempe Park CMS using the Page Builder."
icon: "graduation-cap"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Education** feature in the Page module allows administrators to create a new Education page and structure the content of the Tempe Park website's Education frontpage using the Page Builder. This feature enables administrators to add various dynamic sections—such as a hero header, History of Tempe, Fun Facts, Tempe Warriors & Heroes, and School Programs—to suit the website's visual and informational needs.

Administrators can organize content, section order, and page layout to ensure information is presented in an attractive, dynamic, and intuitive manner for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Education Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Education page sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Hero Section">
    ### Hero Section Controls (No. 11–17)

    <Frame>
      ![Hero Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **Shared** | Group Button | A grouping of content components typically used on all pages, or common components commonly used to structure content on a page. Click to display a collection of common components. |
    | **12** | **Page Header** | Component | In the components group, click the Page Header component to add a header or hero section to this page. |
    | **13** | **Page Header Display** | Layout View | Form interface view displayed after clicking Page Header, showing detail input fields. |
    | **14** | **background\_image** | Media Field | Image field used to store and manage hero section background media. |
    | **15** | **(\+) Click to add an asset** | Action | Click this button to upload an image file to be applied as the hero section image. |
    | **16** | **navigation\_tabs** | Toggle Switch | Slide to `true` if this page has tabbed sub-navigation controls. |
    | **17** | **page\_title** | Text Field | Enter the main display title for the page header. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Page Header Block">
        Click **Add a component to blocks** (No. 7), select the **Shared** component group (No. 11), and click **Page Header** (No. 12).
      </Step>
      <Step title="Upload Hero Background">
        In **background\_image** (No. 14), click **(\+) Click to add an asset** (No. 15) to upload or select the main background banner image.
      </Step>
      <Step title="Configure Title & Navigation">
        Toggle **navigation\_tabs** (No. 16) to `true` if sub-navigation tabs are used, and enter the main page header text in **page\_title** (No. 17).
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. History Section">
    ### History Section Controls (No. 18–28)

    <Frame>
      ![History Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **Spacer** | Component | Select Spacer from the component group to add vertical spacing between the hero header and this section. |
    | **19** | **height** | Number Field | Enter the numeric distance value to set vertical spacing height. |
    | **20** | **education** | Group Button | After inserting the spacer component, click on this component group again to access educational components. |
    | **21** | **History Section** | Component | After clicking education, select the History Section component from the list. |
    | **22** | **cards** | Component Block | Click the (\+) button on this field to display the field list for historical card items. |
    | **23** | **heading** | Text Field | Enter the title or heading for the historical card item. |
    | **24** | **image** | Media Upload | Select or upload an image file for the history card. |
    | **25** | **body** | Text Field / Rich Text | Enter detailed narrative information about the history entry. |
    | **26** | **(\+) Add an entry** | Action Button | Use this button again if you want to add additional history card entries. |
    | **27** | **eyebrow** | Text Field | Enter the section category identifier (e.g., _Our Origins_). |
    | **28** | **Heading** | Text Field | Enter the main title heading for the History section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Separation Spacer">
        Click **Add a component to blocks** $$\rightarrow$$ select **Spacer** (No. 18) $$\rightarrow$$ enter numeric spacing value in **height** (No. 19).
      </Step>
      <Step title="Add History Section Component">
        Select **education** component group (No. 20) $$\rightarrow$$ choose **History Section** (No. 21). Set overall section **eyebrow** (No. 27) and **Heading** (No. 28).
      </Step>
      <Step title="Populate History Cards">
        Under **cards** (No. 22), enter item **heading** (No. 23), upload **image** (No. 24), and fill in descriptive text in **body** (No. 25). Click **(\+) Add an entry** (No. 26) to add more historical timeline items.
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. Fun Fact Section">
    ### Fun Fact Section Controls (No. 29–36)

    <Frame>
      ![Fun Fact Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **29** | **Fun Facts Section** | Component | Select this component from the **education** group to set up the Fun Facts Section. |
    | **30** | **card** | Component Block | Click the (\+) button on this field to display inputs required for adding fun fact card items. |
    | **31** | **icon** | Media Upload | Select or upload an icon asset for the fun fact card. |
    | **32** | **heading** | Text Field | Enter the headline or key statistical title for each fun fact card. |
    | **33** | **description** | Text Field | Enter a supporting narrative description for the fun fact card item. |
    | **34** | **Add an entry** | Action Button | Use this button to add additional fun fact card entries to this section. |
    | **35** | **eyebrow** | Text Field | Enter the category label name for this section (e.g., _Did You Know?_). |
    | **36** | **heading** | Text Field | Enter the main section title heading. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Separation & Component">
        Repeat steps No. 18–19 to insert a vertical **Spacer**, then select **Fun Facts Section** (No. 29).
      </Step>
      <Step title="Set Header Identifiers">
        Enter the section category name in **eyebrow** (No. 35) and title in **heading** (No. 36).
      </Step>
      <Step title="Populate Fact Cards">
        Under **card** (No. 30), upload an **icon** (No. 31), fill in card **heading** (No. 32), and write narrative text in **description** (No. 33). Click **Add an entry** (No. 34) for additional cards.
      </Step>
    </Steps>
  </Tab>
  <Tab title="4. Warriors Section">
    ### Warriors Section Controls (No. 37–45)

    <Frame>
      ![Warriors Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **37** | **Warriors Section** | Component | Select this component from the **education** group to setup the Tempe Warriors & Heroes section. |
    | **38** | **warriors** | Component Block | Click the (\+) sign to display fields used to enter individual warrior entries. |
    | **39** | **name** | Text Field | Enter the name of the warrior or mascot character. |
    | **40** | **role\_title** | Text Field | Enter the role title or designation for the warrior. |
    | **41** | **description** | Text Field | Enter a biographical or background description of the warrior entry. |
    | **42** | **photo** | Media Upload | Select or upload a profile photo asset for the warrior character. |
    | **43** | **Add an entry** | Action Button | Use this button again if you want to add more warrior character profiles. |
    | **44** | **eyebrow** | Text Field | Enter a section category name for this section (e.g., _Meet the Heroes_). |
    | **45** | **heading** | Text Field | Enter a primary section title for this section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Separation & Component">
        Insert a **Spacer** block (steps No. 18–19), then select **Warriors Section** (No. 37).
      </Step>
      <Step title="Set Header Identifiers">
        Fill in section **eyebrow** (No. 44) and primary **heading** (No. 45).
      </Step>
      <Step title="Populate Warrior Profiles">
        Under **warriors** (No. 38), enter character **name** (No. 39), **role\_title** (No. 40), narrative **description** (No. 41), and upload character **photo** (No. 42). Click **Add an entry** (No. 43) for additional profiles.
      </Step>
    </Steps>
  </Tab>
  <Tab title="5. School Section">
    ### School Section Controls (No. 46–51)

    <Frame>
      ![School Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **46** | **School Section** | Component | Select this component from the **education** group to display fields required for school programs. |
    | **47** | **description** | Text Field / Rich Text | Enter overall content description for the school program offerings. |
    | **48** | **image** | Media Upload | Select or upload a promotional image asset for the school program section. |
    | **49** | **eyebrow** | Text Field | Enter the category label name for this section (e.g., _Educational Visits_). |
    | **50** | **Heading** | Text Field | Enter the primary section title heading. |
    | **51** | **item\_learn\_more\_label** | Text Field | Enter the CTA button label text for school program items (e.g., _Learn More_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Component">
        Select **School Section** (No. 46) from the **education** component block group.
      </Step>
      <Step title="Configure Heading & Narrative">
        Set section **eyebrow** (No. 49), main **Heading** (No. 50), overall program **description** (No. 47), and upload media in **image** (No. 48).
      </Step>
      <Step title="Set Action Labels">
        Define button label text in **item\_learn\_more\_label** (No. 51).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Education**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to build out required visual modules sequentially (Hero Header, History Timeline, Fun Facts Grid, Warriors Roster, and School Programs with Spacers).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the Education page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Interactive History Cards" color="#10b981" icon="clock-rotate-left">
    Present park origin stories and timeline historical events using modular card blocks with images and narrative text.
  </Card>

  <Card title="Character & Warrior Rosters" color="#38bdf8" icon="user-shield">
    Showcase park mascots, heroes, and educators with structured profile cards featuring roles, photos, and descriptions.
  </Card>

  <Card title="Structured School Programs" color="#f59e0b" icon="school">
    Dedicated educational program blocks with customizable call-to-action buttons for student groups and excursion booking.
  </Card>
</CardGroup>

---

<Warning>
  Always verify your content entries and asset uploads across all language tabs before hitting **Publish** to ensure accurate display across all localized views.
</Warning>