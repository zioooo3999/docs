---
title: "Create / Setup Plan Your Visit"
sidebarTitle: "Plan Your Visit"
description: "Comprehensive guide for building and configuring the 'Plan Your Visit' page in the Tempe Park CMS using the Page Builder."
icon: "map-location-dot"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Plan Your Visit** feature in the Page module allows administrators to construct a dynamic, visitor-friendly planning page. By utilizing the **Page Builder** mechanism, you can add various functional sections—such as hero headers, ticket purchasing options, visitor guides, calendars, upcoming events, and transit directions—to create an intuitive experience for park guests.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Plan Your Visit Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Plan Your Visit page sequentially using the controls detailed below.

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
    | **13** | **Page Header Display** | Layout View | Form interface view displayed after clicking the Page Header component, showing field details. |
    | **14** | **background\_image** | Media Field | Image field used to store and manage hero section background media. |
    | **15** | **(\+) Click to add an asset** | Action | Click this button to upload an image file to be applied as the hero section image. |
    | **16** | **navigation\_tabs** | Toggle Switch | Slide to `true` if this page has tabbed sub-navigation controls. |
    | **17** | **page\_title** | Text Field | Enter the main display title for the page header. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Page Header Block">
        Click **Add a component to blocks** (No. 7), select the **Shared** component group (No. 11), and click **Page Header** (No. 12).
      </Step>
      <Step title="Upload Background Media">
        In **background\_image** (No. 14), click **(\+) Click to add an asset** (No. 15) to upload or select the main hero image file.
      </Step>
      <Step title="Set Title & Tabs">
        Toggle **navigation\_tabs** (No. 16) to `true` if sub-tabs are needed, and enter the header text in **page\_title** (No. 17).
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. Buy Ticket Section">
    ### Buy Ticket Section Controls (No. 18–32)

    <Frame>
      ![Buy Ticket Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **Plan** | Group Button | Click this component group to display the Buy Ticket component and related planning blocks. |
    | **19** | **Buy Ticket** | Component | Click this component to display the detailed fields to fill in the content in this section. |
    | **20** | **Buy Ticket Display** | Layout View | Form interface view displayed after clicking Buy Ticket, showing detail input fields. |
    | **21** | **description** | Text Field | Enter a description or overview narrative of this section. |
    | **22** | **Image** | Media Upload | Click the (\+) sign in this field to upload or select the image that will be used for this section. |
    | **23** | **Button regular** | Component Group | Click the (\+) sign in this group to display the fields required to fill in the regular buy button in the section. |
    | **24** | **text** | Text Field | Enter the button text to buy a regular ticket. |
    | **25** | **link** | Text Field | Enter the target URL link of the regular ticket purchasing page. |
    | **26** | **style** | Dropdown / Text | Select one of the button style types for the regular ticket button. |
    | **27** | **button\_group** | Component Group | Click the (\+) sign in this group to display the fields required to fill in the buy group button in the section. |
    | **28** | **text** | Text Field | Enter the buy group ticket button text. |
    | **29** | **link** | Text Field | Enter the target URL link of the group ticket page. |
    | **30** | **style** | Dropdown / Text | Select one of the button style types that will be the buy group button style. |
    | **31** | **eyebrow** | Text Field | Enter a section eyebrow name for this section (e.g., _Ticketing_). |
    | **32** | **heading** | Text Field | Enter a primary section heading title for this section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Buy Ticket Component">
        Click **Add a component to blocks** (No. 7), select **Plan** (No. 18), and choose **Buy Ticket** (No. 19).
      </Step>
      <Step title="Configure Heading & Description">
        Fill in **eyebrow** (No. 31), **heading** (No. 32), narrative **description** (No. 21), and upload media in **Image** (No. 22).
      </Step>
      <Step title="Configure Purchasing Buttons">
        Expand **Button regular** (No. 23) to set single-ticket CTA **text** (No. 24), **link** (No. 25), and **style** (No. 26). Expand **button\_group** (No. 27) to configure group-ticket CTA **text** (No. 28), **link** (No. 29), and **style** (No. 30).
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. Visitor's Guide Section">
    ### Visitor's Guide Section Controls (No. 33–50)

    <Frame>
      ![Visitor's Guide Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **33** | **Text** | Group Button | Click on this component group to reveal the Heading component. |
    | **34** | **Heading** | Component | Click to display the field details required to input the title content for this section. |
    | **35** | **Heading Display** | Layout View | Display view shown when the Heading component has been selected. |
    | **36** | **eyebrow** | Text Field | Enter the eyebrow name of this section (e.g., _Guide_). |
    | **37** | **position** | Dropdown | Select one of the section alignment positions on this page (Left, Center, Right). |
    | **38** | **heading** | Text Field | Enter the section title. After finishing, return to step No. 18 then continue to No. 39. |
    | **39** | **Visitor Guide** | Component | After clicking the **Plan** component group (No. 18), click on the Visitor Guide component. |
    | **40** | **Visitor Guide Display** | Layout View | Displays the detail fields needed to populate content in the Visitor Guide section. |
    | **41** | **Tabs** | Component Block | On the field tabs, click (\+) to display the field list for individual tab configurations. |
    | **42** | **image** | Media Upload | Enter or upload an image file to be displayed within the guide tab. |
    | **43** | **tab\_label** | Text Field | Enter the name or tab label displayed in the guide section menu. |
    | **44** | **style** | Dropdown | Select one of the tab styles (e.g., `text_image`). |
    | **45** | **title** | Text Field | Enter the main content title on the active tab card. |
    | **46** | **(\+) Add an entry** | Action Button | Use this button again if you want to enter additional tab items in this section. |
    | **47** | **cta** | Component Group | Click (\+) in this group to display fields required to fill in the CTA button content for the tab. |
    | **48** | **text** | Text Field | Enter the name or text label of the CTA button to be created. |
    | **49** | **link** | Text Field | Enter the target page URL for direct button redirection. |
    | **50** | **style** | Dropdown / Text | Select the CTA button style to be created. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Create Section Header">
        Select **Text** group (No. 33) $$\rightarrow$$ **Heading** (No. 34). Fill in **eyebrow** (No. 36), select alignment **position** (No. 37), and enter **heading** (No. 38).
      </Step>
      <Step title="Add Visitor Guide Block">
        Select **Plan** group (No. 18) $$\rightarrow$$ **Visitor Guide** (No. 39).
      </Step>
      <Step title="Populate Guide Tabs">
        Under **Tabs** (No. 41), upload **image** (No. 42), enter **tab\_label** (No. 43), select **style** (No. 44), and enter tab **title** (No. 45). Click **(\+) Add an entry** (No. 46) for more tabs.
      </Step>
      <Step title="Add Tab CTA Controls">
        In **cta** (No. 47), define button **text** (No. 48), target **link** (No. 49), and button **style** (No. 50).
      </Step>
    </Steps>
  </Tab>
  <Tab title="4. Calendar Section">
    ### Calendar Section Controls (No. 51–54)

    <Frame>
      ![Calendar Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Function & Description |
    | :-- | :-- | :-- |
    | **51** | **Re-use Steps 33 to 37 & 18** | Return to step No. 33–37 to add a section header using the **Heading** component. Once completed, return to step No. 18 (**Plan** group). |
    | **52** | **Calendar** | After clicking the **Plan** component group, select **Calendar** to display detailed setup fields. |
    | **53** | **view** | Select one of the schedule display views to be applied (Weekly or Monthly). |
    | **54** | **items\_limit** | Enter the limit for displaying schedule items based on the selected view mode. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Heading">
        Follow steps No. 33–37 (**Text** group $$\rightarrow$$ **Heading**) to create a header titled _Park Operating Calendar_.
      </Step>
      <Step title="Add Calendar Component">
        Click **Add a component to blocks** $$\rightarrow$$ select **Plan** group (No. 18) $$\rightarrow$$ choose **Calendar** (No. 52).
      </Step>
      <Step title="Set View & Limits">
        Configure calendar display **view** to weekly or monthly (No. 53), and specify **items\_limit** (No. 54).
      </Step>
    </Steps>
  </Tab>
  <Tab title="5. Upcoming Event Section">
    ### Upcoming Event Section Controls (No. 55–64)

    <Frame>
      ![Upcoming Event Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **55** | **Triple Active Slider** | Component | After selecting the **Plan** group (No. 18), select the Triple Active Slider component to fill the content of this section. |
    | **56** | **source\_type** | Dropdown | Select `default` if content source comes from event collection, or select `manual` to enter events manually. |
    | **57** | **Items** | Component Block | Appears after selecting `manual`, containing field groups needed to populate manual event content. |
    | **58** | **Image** | Media Upload | Input or upload an image file for the event item card. |
    | **59** | **time** | Text Field | Enter the event time schedule to be entered manually (e.g., _10:00 AM - 02:00 PM_). |
    | **60** | **title** | Text Field | Enter the title of the event content to be entered manually. |
    | **61** | **location** | Text Field | Enter the event venue location inside Tempe Park. |
    | **62** | **href** | Text Field | Enter the target href URL link for the manually added event item. |
    | **63** | **date** | Date Field | Enter the event execution date to be added manually. |
    | **64** | **(\+) Add an entry** | Action Button | Use this button again if you want to add additional event entries manually. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Create Event Section Header">
        Follow steps No. 33–37 (**Text** group $$\rightarrow$$ **Heading**) to add an _Upcoming Events_ title block.
      </Step>
      <Step title="Add Triple Active Slider">
        Select **Plan** group (No. 18) $$\rightarrow$$ choose **Triple Active Slider** (No. 55). Set **source\_type** to `manual` (No. 56).
      </Step>
      <Step title="Populate Event Entries">
        Under **Items** (No. 57), upload **Image** (No. 58), enter **time** (No. 59), **title** (No. 60), **location** (No. 61), target **href** (No. 62), and **date** (No. 63). Click **(\+) Add an entry** (No. 64) for more event cards.
      </Step>
    </Steps>
  </Tab>
  <Tab title="6. How To Get Here Section">
    ### How To Get Here Section Controls (No. 65–66)

    <Frame>
      ![How To Get Here Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Function & Description |
    | :-- | :-- | :-- |
    | **65** | **Re-use Steps 33 to 38** | Return to step No. 33–38 (**Text** group $$\rightarrow$$ **Heading**) to add section title and eyebrow for _How To Get Here_. |
    | **66** | **Re-use Steps 39 to 50** | Return to step No. 39–50 (**Plan** group $$\rightarrow$$ **Visitor Guide**) to add tabbed transit content (e.g., By Bus, By Train, By Car). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Create Transit Section Header">
        Follow steps No. 33–38 to configure section **eyebrow** (_Directions_) and **heading** (_How To Get Here_).
      </Step>
      <Step title="Build Location & Transit Guide">
        Follow steps No. 39–50 to insert a **Visitor Guide** component block. Populate individual tab labels (e.g., _Public Transport_, _Private Vehicle_) along with images, descriptions, and CTA links.
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Plan Your Visit**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to build out required visual modules sequentially (Hero, Buy Ticket, Visitor's Guide, Calendar, Upcoming Events, and How To Get Here).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the page layout live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Interactive Visitor Tools" color="#10b981" icon="ticket">
    Integrated ticketing, calendar schedule views, and transit direction tabs for effortless park planning.
  </Card>

  <Card title="Dynamic & Manual Events" color="#38bdf8" icon="calendar-days">
    Flexibly switch between automated database event feeds or manual custom event highlights using Triple Active Sliders.
  </Card>

  <Card title="Multi-Language Support" color="#f59e0b" icon="language">
    Seamlessly localize content across English, Indonesian, and Chinese to serve international park visitors.
  </Card>
</CardGroup>

---

<Warning>
  Always verify your inputs in the **SEO** and **CTA link** fields before publishing to ensure proper navigation and search engine visibility.
</Warning>