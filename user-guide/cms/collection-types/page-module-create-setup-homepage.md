---
title: "Create / Setup Homepage"
sidebarTitle: "Create/Setup Homepage Page"
description: "Comprehensive guide for building and configuring the Tempe Park homepage using the Page Builder."
icon: "house"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Homepage** feature in the Page module allows you to create a new homepage and organize the front page content of the Tempe Park website using the Page Builder. This feature enables administrators to add various sections—such as a hero section, banner slider, event lists, and commitment sections—to suit specific visual and informational needs.

Administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Homepage Setup Form Interface](/images/0-\(53\).png)
</Frame>

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1** | **Tab Draft** _(editable form)_ | Use this form tab when creating or modifying a draft data entry. |
| **2** | **Tab Published** | Read-only view showing the current published version of the homepage. |
| **3** | **title** | Enter the primary page title. |
| **4** | **slug** | Enter the unique URL-friendly slug identifier for the page. |
| **5** | **this** | Column to fill in SEO grouping to fill in SEO page. |
| **6** | **No Entry yet. Click to add One** | Click the (\+) button to display the SEO input column. After clicking, the `metaTitle`, `metaDescription`, and `shareImage` columns will appear. Fill them in according to the page you want to add. |
| **7** | **Add Component** | Click to insert structural block components into the page layout. |
| **8** | **Publish** | Instantly publishes entry to the website frontpage and enables cross-module relationships. |
| **9** | **Save** | Stores the entry as a **Draft** without making it publicly visible. |
| **10** | **Multilingual** | Switch or add content versions in **English**, **Indonesian**, or **Chinese**. |

---

## Section Builder Reference & Procedures

Configure each homepage section sequentially using the controls detailed below.

<Tabs>
  <Tab title="1. Hero Section">
    ### Hero Section Controls (No. 11–18)

    <Frame>
      ![Hero Section Configuration](/images/0-\(54\).png)
    </Frame>

    <Frame>
      ![Hero Section Configuration](/images/0-\(55\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **11** | **Shared** | Group Button | A grouping of content components typically used on all pages or common components used to structure content. Click to display common components. |
    | **12** | **Hero** | Component | Click this component to add the Hero section block to the Homepage layout. |
    | **13** | **Hero Display** | Layout View | Form interface view displayed after selecting the Hero component. |
    | **14** | **title** | Text Field | Enter the main title of the Hero section of the Homepage. |
    | **15** | **description** | Text Field | Enter the sub-description or tagline text of the Hero section. |
    | **16** | **Image** | Media Upload | Upload an image file to be displayed as the main Hero banner media. |
    | **17** | **text\_button\_1** | Text Field | Enter the Primary Call-To-Action (CTA 1) button label text. |
    | **18** | **text\_button\_2** | Text Field | Enter the Secondary Call-To-Action (CTA 2) button label text. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Hero Block">
        Click **Add Component** (No. 7), select the **Shared** component group (No. 11), and click **Hero** (No. 12).
      </Step>
      <Step title="Configure Content">
        Enter the primary heading in **title** (No. 14) and supporting narrative in **description** (No. 15).
      </Step>
      <Step title="Upload Media & Action Buttons">
        Select or upload the main hero banner image in **Image** (No. 16), then set labels for **text\_button\_1** (No. 17) and **text\_button\_2** (No. 18).
      </Step>
    </Steps>
  </Tab>
  <Tab title="2. Banner Slider Section">
    ### Banner Slider Section Controls (No. 19–35)

    <Frame>
      ![Banner Slider Configuration](/images/0-\(56\).png)
    </Frame>

    <Frame>
      ![0 (58) 1](/images/0-\(58\)-1.png "0 (58) 1")
    </Frame>

    <Frame>
      ![Banner Slider Configuration](/images/0-\(57\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **19** | **Dynamic** | Group Button | Click to expand dynamic components required for filling slider content sections. |
    | **20** | **Slider** | Component | Click to insert the fields required for configuring the banner slider setup. |
    | **21** | **layout** | Dropdown | Select the slider layout format. For the Homepage, select `default`. |
    | **22** | **source\_type** | Dropdown | Select data source mode. For the Homepage banner slider, select `manual`. |
    | **23** | **item\_cta\_label** | Text Field | CTA label item setting (leave blank for standard homepage slider). |
    | **24** | **show\_dots** | Toggle Switch | Set to `true` to enable dot navigation pagination below the slider. |
    | **25** | **show\_arrows** | Toggle Switch | Set to `true` to display navigation arrows for moving between slides. |
    | **26** | **items\_limit** | Number Field | Define the maximum number of slider items that can be displayed. |
    | **27** | **Slides** | Component Block | Component list block that opens after selecting `manual` in **source\_type**. |
    | **28** | **heading** | Text Field | Enter slide sequence number or header title. |
    | **29** | **eyebrow** | Text Field | Eyebrow text label (leave blank for standard homepage slider). |
    | **30** | **highlight** | Text Field | Highlight text overlay (leave blank for standard homepage slider). |
    | **31** | **description** | Text Field | Slide description text (leave blank for standard homepage slider). |
    | **32** | **image** | Media Upload | Upload or select the banner image file for the current slide. |
    | **33** | **cta\_label** | Text Field | CTA button text label (leave blank for standard homepage slider). |
    | **34** | **cta\_url** | Text Field | Target URL link for the CTA button (leave blank for standard homepage slider). |
    | **35** | **enable\_button** | Toggle Switch | Toggle button visibility (set to `false` for standard homepage slider). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Slider Component">
        Click **Add Component**, select **Dynamic** (No. 19), and choose **Slider** (No. 20).
      </Step>
      <Step title="Set Global Parameters">
        Set **layout** to `default` (No. 21), **source\_type** to `manual` (No. 22), and toggle **show\_dots** (No. 24) and **show\_arrows** (No. 25) to `true`.
      </Step>
      <Step title="Populate Slide Items">
        Under **Slides** (No. 27), enter slide index in **heading** (No. 28), upload media in **image** (No. 32), and keep **enable\_button** set to `false` (No. 35).
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. What's On Section">
    ### What's On Tempe Park Section Controls (No. 36–58)

    <Frame>
      ![What's On Section Configuration](/images/0-\(61\).png)
    </Frame>

    <Frame>
      ![0 (62)](/images/0-\(62\).png "0 (62)")
    </Frame>

    <Frame>
      ![What's On Section Configuration](/images/0-\(63\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **36** | **Text** | Group Button | Component group used for adding text and heading sections to the page layout. |
    | **37** | **Heading** | Component | Click to insert title and eyebrow heading fields for a new section. |
    | **38** | **Eyebrow** | Text Field | Enter the eyebrow header label for the section (e.g., _What's On_). |
    | **39** | **heading** | Text Field | Enter the main title heading for the section. |
    | **40** | **position** | Dropdown | Select alignment positioning for the section heading (Left, Center, Right). |
    | **41** | **Flexbox** | Component | Click the Flexbox component in the **Dynamic** group to display content grid controls. |
    | **42** | **Flexbox Display** | Layout View | Displays the required field configurations for Flexbox content input. |
    | **43** | **readmore\_button\_text** | Text Field | Read more CTA button text configuration. |
    | **44** | **view\_all\_text** | Text Field | View all link text label configuration. |
    | **45** | **source\_type** | Dropdown | Define content data source mode. |
    | **46** | **layout** | Dropdown | Define grid layout display format. |
    | **47** | **columns** | Number Field | Define column count for card layout display. |
    | **48** | **items\_limit** | Number Field | Define maximum limit of card items to display. |
    | **49** | **show\_category\_badge** | Toggle Switch | Enable or disable category badge tags on cards. |
    | **50** | **show\_excerpt** | Toggle Switch | Enable or disable short description excerpts on cards. |
    | **51** | **item\_cta\_label** | Text Field | Individual card CTA button label text. |
    | **52** | **Button** | Group Button | Component group used to add Call-To-Action buttons to the section. |
    | **53** | **Button Multiple** | Component | Click to display fields required to add multiple CTA buttons. |
    | **54** | **(\+) Add Entry** | Action Button | Click to insert button configuration detail fields. |
    | **55** | **Text** | Text Field | Enter the title or label text displayed on the button. |
    | **56** | **link** | Text Field | Enter the target page URL link for button redirection. |
    | **57** | **style** | Dropdown / Text | Select or enter the visual styling format for the button. |
    | **58** | **Add an Entry** | Action Button | Use to add additional secondary or back buttons within the section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Header">
        Select **Text** group (No. 36) $$\rightarrow$$ **Heading** (No. 37). Enter section category in **Eyebrow** (No. 38), primary title in **heading** (No. 39), and select layout **position** (No. 40).
      </Step>
      <Step title="Configure Flexbox Grid Layout">
        Select **Dynamic** group $$\rightarrow$$ **Flexbox** (No. 41). Configure grid attributes including **columns** (No. 47) and **items\_limit** (No. 48).
      </Step>
      <Step title="Add Section Buttons">
        Select **Button** group (No. 52) $$\rightarrow$$ **Button Multiple** (No. 53). Click **(\+) Add Entry** (No. 54) and fill in button **Text** (No. 55), **link** (No. 56), and **style** (No. 57).
      </Step>
    </Steps>
  </Tab>
  <Tab title="4. Journey Section">
    ### Journey Section Controls (No. 59 & Sequence 28–35)

    <Frame>
      ![Journey Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Function & Description |
    | :-- | :-- | :-- |
    | **59** | **Re-use Steps 19 to 27** | Return to slider setup controls (**Dynamic** $$\rightarrow$$ **Slider**). Populate slide entries using sequence No. 28–35 detailed below. |
    | _28_ | **heading** | Enter slide sequence number or header title. |
    | _29_ | **eyebrow** | Enter the section name identifier (e.g., _Journey_). |
    | _30_ | **highlight** | Enter the section highlight title displayed on the slider image. |
    | _31_ | **description** | Enter the supporting narrative description overlay for the slide. |
    | _32_ | **image** | Upload or select the background slider image. |
    | _33_ | **cta\_label** | Insert the CTA button text label displayed on the slider image. |
    | _34_ | **cta\_url** | Enter the target page URL link for the CTA button on the slider image. |
    | _35_ | **enable\_button** | Set to `true` to activate CTA button display and enable `cta_label` & `cta_url` fields. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Create Journey Slider">
        Insert a new **Slider** component (**Dynamic** $$\rightarrow$$ **Slider** as per No. 19–27).
      </Step>
      <Step title="Populate Journey Cards">
        For each Journey slide entry, enter **eyebrow** (_Journey_, No. 29), **highlight** title (No. 30), narrative **description** (No. 31), and banner **image** (No. 32).
      </Step>
      <Step title="Activate CTA Links">
        Toggle **enable\_button** to `true` (No. 35), then populate **cta\_label** (No. 33) and target **cta\_url** path (No. 34).
      </Step>
    </Steps>
  </Tab>
  <Tab title="5. Our Commitment Section">
    ### Our Commitment Section Controls (No. 60–61)

    <Frame>
      ![Our Commitment Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Function & Description |
    | :-- | :-- | :-- |
    | **60** | **Re-use Steps 36 to 40** | Return to Heading setup steps to create section title, eyebrow name, and alignment position for _Our Commitment_. |
    | **61** | **Re-use Steps 19 to 35** | Return to Slider setup steps to create custom image slider content tailored for commitment values. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Header">
        Follow controls No. 36–40 (**Text** group $$\rightarrow$$ **Heading**). Set **Eyebrow** to _Our Commitment_ and specify text alignment **position**.
      </Step>
      <Step title="Add Commitment Slider Block">
        Follow controls No. 19–35 (**Dynamic** group $$\rightarrow$$ **Slider**). Adjust slide items, images, and descriptions to match corporate commitment parameters.
      </Step>
    </Steps>
  </Tab>
  <Tab title="6. Article & News Update">
    ### Article & News Update Section Controls (No. 62–64)

    <Frame>
      ![Article & News Update Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Function & Description |
    | :-- | :-- | :-- |
    | **62** | **Re-use Steps 36 to 40** | Return to Heading setup steps to configure section name (_News & Updates_), main title, and header alignment. |
    | **63** | **Re-use Steps 41 to 51** | Return to Flexbox setup steps. Ensure **source\_type** field is explicitly set to `news` to dynamically fetch live article content. |
    | **64** | **Re-use Steps 53 to 58** | Return to Button setup steps (**Button Multiple**) to add a bottom section CTA button redirecting to `/news`. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Create News Section Heading">
        Insert a **Heading** block (No. 36–40) with **Eyebrow** set to _Articles & News Update_.
      </Step>
      <Step title="Configure Dynamic News Sourcing">
        Insert a **Flexbox** component (No. 41–51). Set **source\_type** parameter to `news` to automatically feed live articles into the grid layout.
      </Step>
      <Step title="Add View All News CTA">
        Insert a **Button Multiple** block (No. 53–58), set **Text** to _View All News_ (No. 55), and set **link** to `/news` (No. 56).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Homepage**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and expand **SEO Section** (No. 6) to configure meta titles, descriptions, and share image preview cards.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add Component** (No. 7) to build out required visual modules sequentially (Hero, Banner Slider, What's On, Journey, Commitment, and News & Updates).
  </Step>
  <Step title="Save or Publish">
    Click **Save** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the homepage layout live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Modular Layout Builder" color="#10b981" icon="cubes">
    Assemble hero banners, dynamic sliders, and content blocks using drag-and-drop component groups.
  </Card>

  <Card title="Dynamic Data Sourcing" color="#38bdf8" icon="database">
    Automatically fetch live articles by configuring structural blocks with dynamic source types (`news`).
  </Card>

  <Card title="Integrated SEO Controls" color="#f59e0b" icon="magnifying-glass">
    Configure meta titles, descriptions, and social share image cards directly inside the entry editor.
  </Card>
</CardGroup>

---

<Warning>
  Always verify your `source_type` and `layout` configurations before hitting **Publish** to ensure the page renders correctly on the live website.
</Warning>