---
title: "Create / Setup About Us"
sidebarTitle: "About Us"
description: "Comprehensive guide for structuring the 'About Us' page in the Tempe Park CMS using the Page Builder, including hero, foundation, vision, and mission sections."
icon: "building"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup About Us** feature in the Page module allows administrators to design and structure the About Us page layout using the Page Builder. Administrators can manage key dynamic content sections—such as the hero header, organization foundation, and vision & mission statements—to provide an engaging, professional, and comprehensive introduction to Tempe Park.

Administrators can organize content, section order, and page layout to ensure information is presented in an attractive, dynamic, and intuitive manner for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![About Us Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the About Us page sequentially using the controls detailed below.

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
  <Tab title="2. Foundation Section">
    ### Foundation Section Controls (No. 18–26)

    <Frame>
      ![Foundation Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **Image Content** | Component | Click on this component to add foundation section content to this page. |
    | **19** | **eyebrow** | Text Field | Enter the category name for this section (e.g., _Our Story_). |
    | **20** | **heading** | Text Field | Enter the primary section heading title. |
    | **21** | **description** | Text Field | Enter the main descriptive text for the foundation section. |
    | **22** | **Image** | Media Field | Select or upload the main image asset for this section. |
    | **23** | **Image position** | Dropdown | Select the alignment position for the image in the section (e.g., Left or Right). |
    | **24** | **Overlay\_image** | Media Field | Enter or upload an overlay image asset to enhance the section layout. |
    | **25** | **thumbnail** | Media Field | Insert thumbnail image asset for video content preview. |
    | **26** | **Video** | Media Upload | Enter or upload the video media asset for this section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Image Content Component">
        Click **Add a component to blocks** (No. 7) and select **Image Content** (No. 18).
      </Step>
      <Step title="Fill Narrative Content">
        Configure **eyebrow** (No. 19), **heading** (No. 20), and detailed narrative in **description** (No. 21).
      </Step>
      <Step title="Upload Visual & Media Assets">
        Upload main **Image** (No. 22) and set its **Image position** (No. 23). Optionally attach an **Overlay\_image** (No. 24), video **thumbnail** (No. 25), and featured **Video** (No. 26).
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. Vision Section">
    ### Vision Section Controls (No. 27–32)

    <Frame>
      ![Vision Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **27** | **about** | Group Button | Click this component group to display the About Us Vision component. |
    | **28** | **About Us Vision** | Component | Click this component to bring up the fields required to fill in the vision section. |
    | **29** | **description** | Text Field | Enter the vision statement description text. |
    | **30** | **background\_image** | Media Field | Upload or select a background image asset for this section. |
    | **31** | **person\_image** | Media Field | Enter a photo asset of key leadership or featured individuals for this section. |
    | **32** | **eyebrow** | Text Field | Enter the category label name for this section (e.g., _Our Vision_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Select About Group">
        Click **Add a component to blocks** (No. 7), select the **about** group (No. 27), and click **About Us Vision** (No. 28).
      </Step>
      <Step title="Configure Vision Content">
        Enter section category in **eyebrow** (No. 32) and main statement in **description** (No. 29).
      </Step>
      <Step title="Attach Vision Media Assets">
        Upload background media to **background\_image** (No. 30) and executive/leadership photography to **person\_image** (No. 31).
      </Step>
    </Steps>
  </Tab>
  <Tab title="4. Mission Section">
    ### Mission Section Controls (No. 34–37)

    <Frame>
      ![Mission Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **34** | **description** | Text Field | Enter the mission statement description text. |
    | **35** | **background\_image** | Media Field | Upload or select a background image asset for this section. |
    | **36** | **person\_image** | Media Field | Enter a photo asset of key leadership or team members for this section. |
    | **37** | **eyebrow** | Text Field | Enter the category label name for this section (e.g., _Our Mission_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Select About Group">
        Click **Add a component to blocks** (No. 7), select the **about** group (No. 27), and click the Mission component.
      </Step>
      <Step title="Configure Mission Content">
        Enter section category in **eyebrow** (No. 37) and detailed mission goals in **description** (No. 34).
      </Step>
      <Step title="Attach Mission Media Assets">
        Upload background visuals in **background\_image** (No. 35) and representative imagery in **person\_image** (No. 36).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup About Us**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to sequentially construct required visual modules (Page Header, Image Content Foundation, Vision, and Mission blocks).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the About Us page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Foundation Media Spotlight" color="#10b981" icon="photo-film">
    Flexible rich-media showcase supporting main imagery, overlay graphics, and embedded video previews.
  </Card>

  <Card title="Vision & Purpose Cards" color="#38bdf8" icon="eye">
    Dedicated visual callouts linking corporate vision statements with key organizational leadership assets.
  </Card>

  <Card title="Mission Framework" color="#f59e0b" icon="bullseye">
    Structured narrative blocks to effectively present core organizational values, mission goals, and team photos.
  </Card>
</CardGroup>

---

<Warning>
  Ensure that all image assets, video links, and multilingual text translations are verified across all language tabs before publishing to maintain a consistent presentation.
</Warning>