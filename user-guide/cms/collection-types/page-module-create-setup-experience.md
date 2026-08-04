---
title: "Create / Setup Experience"
sidebarTitle: "Experience"
description: "Comprehensive guide for building and configuring the Experience page in the Tempe Park CMS using the Page Builder."
icon: "compass"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Experience** feature in the Page module allows administrators to construct and organize the main Experience front page of the Tempe Park website using the Page Builder. Through this feature, you can structure dynamic sections like hero headers, park attractions, activity sliders, and facility grids to create an engaging visual experience for visitors.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Experience Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Experience page sequentially using the controls detailed below.

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
    | **13** | **Page Header Display** | Layout View | Form interface view displayed after clicking Page Header, showing detail fields. |
    | **14** | **background\_image** | Media Field | Image field used to store and manage hero section background media. |
    | **15** | **(\+) Click to add an asset** | Action | Click this button to upload an image file to be applied as the hero section image. |
    | **16** | **navigation\_tabs** | Toggle Switch | Slide to `true` if this page has tabbed sub-navigation controls. |
    | **17** | **page\_title** | Text Field | Enter the main display title for the page header. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Page Header Block">
        Click **Add a component to blocks** (No. 7), select the **Shared** component group (No. 11), and click **Page Header** (No. 12).
      </Step>
      <Step title="Upload Background Image">
        In **background\_image** (No. 14), click **(\+) Click to add an asset** (No. 15) to upload or select the hero banner background image.
      </Step>
      <Step title="Configure Title & Sub-navigation">
        Toggle **navigation\_tabs** (No. 16) to `true` if tabbed navigation is required, and enter the main page header name in **page\_title** (No. 17).
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. Attraction Section">
    ### Attraction Section Controls (No. 18–32)

    <Frame>
      ![Attraction Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **Spacer** | Component | Select Spacer from the component group to add vertical spacing between the hero header and this section. |
    | **19** | **height** | Number Field | Enter the numeric height value to set the spacing separation distance. |
    | **20** | **text** | Group Button | Select the text component group to access heading blocks for adding section titles. |
    | **21** | **Heading** | Component | Click Heading to display fields for adding the title and eyebrow for this section. |
    | **22** | **eyebrow** | Text Field | Input the section category name in the eyebrow field (e.g., _Discover_). |
    | **23** | **heading** | Text Field | Enter the main section title (e.g., _Park Attractions_). |
    | **24** | **position** | Dropdown | Select alignment position for the section heading (Left, Center, Right). |
    | **25** | **dynamic** | Group Button | Select and click dynamic component group to bring up slider components for image content. |
    | **26** | **Slider** | Component | Click the slider component to display fields needed to populate dynamic banner sliders. |
    | **27** | **layout** | Dropdown | Select `default` to match the standard Figma layout design for attraction sliders. |
    | **28** | **source\_type** | Dropdown | Select `attraction` so data sourcing automatically points to the **Attractions** collection. |
    | **30** | **show\_dots** | Toggle Switch | Slide right (`true`) to display dot pagination below the banner image slider; slide left (`false`) to hide. |
    | **31** | **show\_arrows** | Toggle Switch | Swipe right (`true`) to enable arrow navigation controls; swipe left (`false`) to disable. |
    | **32** | **item\_limits** | Number Field | Enter the maximum data limit to display from the **Attractions** collection. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Vertical Spacer">
        Click **Add a component to blocks** $$\rightarrow$$ select **Spacer** (No. 18) $$\rightarrow$$ enter pixel value in **height** (No. 19).
      </Step>
      <Step title="Create Section Header">
        Select **text** group (No. 20) $$\rightarrow$$ **Heading** (No. 21). Populate **eyebrow** (No. 22), main **heading** title (No. 23), and text alignment **position** (No. 24).
      </Step>
      <Step title="Configure Attraction Slider">
        Select **dynamic** group (No. 25) $$\rightarrow$$ **Slider** (No. 26). Set **layout** to `default` (No. 27) and **source\_type** to `attraction` (No. 28). Adjust **show\_dots** (No. 30), **show\_arrows** (No. 31), and set **item\_limits** (No. 32).
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. Activities Section">
    ### Activities Section Controls (No. 33–35)

    <Frame>
      ![Activities Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Function & Description |
    | :-- | :-- | :-- |
    | **33** | **Re-use Steps 18 to 19** | Add vertical separation between sections by inserting a **Spacer** component and configuring the **height** property. |
    | **34** | **Re-use Steps 20 to 24** | Add a section title block using **text** group $$\rightarrow$$ **Heading**. Populate section eyebrow, heading, and alignment position. |
    | **35** | **Re-use Steps 25 to 32** | Add dynamic slider content by selecting **dynamic** group $$\rightarrow$$ **Slider**. Configure parameters and set **source\_type** to pull activity collection data. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Separation">
        Repeat steps No. 18–19 to insert a **Spacer** block and set spacing height.
      </Step>
      <Step title="Add Activities Section Header">
        Repeat steps No. 20–24 (**text** $$\rightarrow$$ **Heading**) to enter the section **eyebrow** (_Things To Do_), main **heading** title, and alignment **position**.
      </Step>
      <Step title="Configure Activities Dynamic Slider">
        Repeat steps No. 25–32 (**dynamic** $$\rightarrow$$ **Slider**). Set layout options, enable pagination controls, and configure **source\_type** to dynamically fetch activity records.
      </Step>
    </Steps>
  </Tab>
  <Tab title="4. Facilities Section">
    ### Facilities Section Controls (No. 36–48)

    <Frame>
      ![Facilities Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **36** | **Re-use Steps 18 to 19** | Return to Spacer steps to provide vertical distance before the Facilities section. |  |
    | **37** | **Re-use Steps 20 to 24** | Return to Heading steps to configure section title, eyebrow, and text alignment for Facilities. |  |
    | **38** | **Flexbox** | Component | Select **dynamic** component group and click **Flexbox** to handle facilities grid layout. |
    | **39** | **readmore\_button\_text** | Text Field | Enter labeling for the card read more button as specified in the UI design. |
    | **40** | **view\_all\_text** | Text Field | Enter labeling for the "View All" section button if applicable. |
    | **41** | **source\_type** | Dropdown | Select `facilities` so source data automatically queries the **Facilities** collection. |
    | **42** | **layout** | Dropdown | Select layout grid form. Choose `grid-equal` to match equal-sized card designs. |
    | **43** | **columns** | Number Field | Set the column count setup (e.g., input `6` for a 6-column grid view). |
    | **44** | **item\_limits** | Number Field | Define the maximum limit of facility items/cards displayed on the grid. |
    | **45** | **show\_category\_badge** | Toggle Switch | Set to `false` to hide category badges on facility cards. |
    | **46** | **show\_excerpt** | Toggle Switch | Set to `false` to hide text excerpts on facility cards. |
    | **47** | **item\_cta\_label** | Text Field | Enter naming or labeling for the CTA button on facility card items. |
    | **48** | **Re-use Steps 18 to 19** | Add a final **Spacer** component to separate the last section from the page footer content. |  |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Separation & Header">
        Follow steps No. 18–19 to set spacing, then steps No. 20–24 (**text** $$\rightarrow$$ **Heading**) to set section **eyebrow** (_Amenities_) and **heading** (_Park Facilities_).
      </Step>
      <Step title="Configure Facilities Flexbox Grid">
        Select **dynamic** group $$\rightarrow$$ **Flexbox** (No. 38). Set **source\_type** to `facilities` (No. 41), **layout** to `grid-equal` (No. 42), and specify grid **columns** (No. 43) and **item\_limits** (No. 44).
      </Step>
      <Step title="Set Display Flags & Card Labels">
        Enter button text in **readmore\_button\_text** (No. 39) and **item\_cta\_label** (No. 47). Toggle **show\_category\_badge** (No. 45) and **show\_excerpt** (No. 46) to `false`.
      </Step>
      <Step title="Add Footer Spacer">
        Repeat steps No. 18–19 (No. 48) to insert a bottom **Spacer** component before the footer.
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Experience**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to build out required visual modules sequentially (Hero Header, Attraction Slider, Activities Slider, and Facilities Grid with Spacers).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the Experience page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Dynamic Collection Binding" color="#10b981" icon="database">
    Automatically stream live attraction and facility collections by setting dedicated `source_type` dynamic bindings.
  </Card>

  <Card title="Flexible Grid & Sliders" color="#38bdf8" icon="table-cells">
    Customizable `grid-equal` layouts and dynamic carousel sliders with dot and arrow navigation controls.
  </Card>

  <Card title="Controlled Spacing Systems" color="#f59e0b" icon="arrows-up-down">
    Utilize modular Spacer components to maintain consistent vertical rhythm and pixel-perfect UI spacing.
  </Card>
</CardGroup>

---

<Warning>
  Always verify that your `source_type` fields point to the correct collections (e.g., `attraction` or `facilities`) before publishing to ensure dynamic data renders properly on the live website.
</Warning>