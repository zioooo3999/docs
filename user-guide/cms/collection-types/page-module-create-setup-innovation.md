---
title: "Create / Setup Innovation"
sidebarTitle: "Innovation"
description: "Comprehensive guide for configuring the Innovation page, including products, menu inspiration, collaborations, and partnership inquiries in the Tempe Park CMS."
icon: "lightbulb"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Innovation** feature in the Page module allows administrators to structure the Innovation page layout using the Page Builder. This module supports diverse dynamic content blocks—including hero headers, product collections, journey/inspiration menus, industry collaborations, and partnership inquiry forms—to suit the website's visual and business needs.

Administrators can organize content, section order, and page layout to ensure information is presented in an attractive, dynamic, and intuitive manner for visitors.

---

## Form Fields & Interface Reference

<Frame>
  ![Innovation Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Innovation page sequentially using the controls detailed below.

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
  <Tab title="2. Our Product Section">
    ### Our Product Section Controls (No. 18–29)

    <Frame>
      ![Our Product Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **Spacer** | Component | Select Spacer from the component group to add space between the header and this section. |
    | **19** | **height** | Number Field | Enter the numeric distance value to set vertical spacing height. |
    | **20** | **text** | Group Button | Click this component group to access heading components for titling new sections. |
    | **21** | **Heading** | Component | Click this component to display required detail fields for section titles. |
    | **22** | **eyebrow** | Text Field | Enter the category name for this new section. |
    | **23** | **heading** | Text Field | Enter the primary section title. |
    | **24** | **position** | Dropdown | Select the alignment position for this heading text (e.g., left, center). |
    | **25** | **innovation** | Group Button | Return to this component group to reveal components needed for innovation content. |
    | **26** | **Curated Collection** | Component | Click this component to display fields required for product catalog filters and cards. |
    | **27** | **filter\_label** | Text Field | Enter the label text for the filter trigger (e.g., _Filter_). |
    | **28** | **buy\_button\_label** | Text Field | Enter the text label for the purchase CTA on product cards (e.g., _Buy_). |
    | **29** | **all\_category\_label** | Text Field | Enter the text label for the all-categories filter option (e.g., _All Products_). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Spacer & Heading">
        Add **Spacer** (No. 18) and set **height** (No. 19). Select **text** group (No. 20) $$\rightarrow$$ **Heading** (No. 21) to configure **eyebrow** (No. 22), **heading** (No. 23), and **position** (No. 24).
      </Step>
      <Step title="Add Curated Collection Block">
        Select **innovation** group (No. 25) and click **Curated Collection** (No. 26).
      </Step>
      <Step title="Set Filter & Action Labels">
        Enter filter text in **filter\_label** (No. 27), button label in **buy\_button\_label** (No. 28), and category label in **all\_category\_label** (No. 29).
      </Step>
    </Steps>
  </Tab>
  <Tab title="3. Menu Inspiration">
    ### Menu Inspiration Controls (No. 30–33)

    <Frame>
      ![Menu Inspiration Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **30** | **Re-title Section Heading** | Process | Repeat steps No. 20–24 to add a **Spacer** and **Heading** block for this section. |
    | **31** | **Journey Section** | Component | Select this component from the **innovation** group to populate the Inspiration Menu section. |
    | **32** | **cta\_label** | Text Field | Enter the CTA button label text displayed on image cards in this section. |
    | **33** | **source\_type** | Dropdown | Select data source mode (Default pulls from Inspiration Menu collection; select Manual for custom entries). |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Title the Section">
        Repeat steps No. 20–24 to insert a **Spacer** and configure section **eyebrow** and **heading**.
      </Step>
      <Step title="Add Journey Component">
        Select **Journey Section** (No. 31) from the **innovation** component group.
      </Step>
      <Step title="Set CTA & Source">
        Define card button text in **cta\_label** (No. 32) and set **source\_type** (No. 33) to determine data binding.
      </Step>
    </Steps>
  </Tab>
  <Tab title="4. Collaboration Section">
    ### Collaboration Section Controls (No. 34–40)

    <Frame>
      ![Collaboration Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **34** | **Re-title Section Heading** | Process | Repeat steps No. 20–24 to add a **Spacer** and **Heading** block for this section. |
    | **35** | **Industry Collaboration** | Component | Select this component from the **innovation** group to populate industry partnership cards. |
    | **36** | **Industries** | Component Block | Click the (\+) button on this field to display inputs required for card entries. |
    | **37** | **icon** | Media Upload | Select or upload an icon asset for the collaboration card. |
    | **38** | **title** | Text Field | Enter the title heading for the collaboration card. |
    | **39** | **description** | Text Field | Enter a descriptive summary of the industry collaboration card. |
    | **40** | **(\+) Add an entry** | Action Button | Use this button to add additional collaboration cards to this section. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Title the Section">
        Repeat steps No. 20–24 to insert a **Spacer** and configure section **eyebrow** and **heading**.
      </Step>
      <Step title="Add Collaboration Component">
        Select **Industry Collaboration** (No. 35) from the **innovation** component group.
      </Step>
      <Step title="Populate Industry Cards">
        Under **Industries** (No. 36), upload **icon** (No. 37), fill in card **title** (No. 38), and write narrative text in **description** (No. 39). Click **(\+) Add an entry** (No. 40) for more items.
      </Step>
    </Steps>
  </Tab>
  <Tab title="5. Inquiries Section">
    ### Inquiries Section Controls (No. 41–61)

    <Frame>
      ![Inquiries Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **41** | **Partnership Opportunity** | Component | Select this component from the **innovation** group to set up the partnership inquiry section and form. |
    | **42** | **Heading** | Text Field | Enter the primary section title heading. |
    | **43** | **Image** | Media Upload | Select or upload the featured promotional image asset for this section. |
    | **44** | **cta\_label** | Text Field | Enter the label text for the form submission button (e.g., _Submit Inquiry_). |
    | **45** | **cta\_url** | Text Field | Enter the submission endpoint URL or redirect destination for this section. |
    | **46** | **eyebrow** | Text Field | Enter the category label name for this section (e.g., _Partnerships_). |
    | **47** | **nama\_field\_label** | Text Field | Enter the label text for the Name input field. |
    | **48** | **company\_field\_label** | Text Field | Enter the label text for the Company input field. |
    | **49** | **email\_field\_label** | Text Field | Enter the label text for the Email input field. |
    | **50** | **phone\_field\_label** | Text Field | Enter the label text for the Phone Number input field. |
    | **51** | **inquiry\_field\_label** | Text Field | Enter the label text for the Inquiry Subject field. |
    | **52** | **inquiry\_dropdown\_option** | Component Block | Click (\+) to add dropdown options for inquiry topics (`dropdown_item_label`). |
    | **53** | **note\_field\_label** | Text Field | Enter the label text for the Notes/Message input field. |
    | **54** | **name\_field\_placeholder** | Text Field | Enter placeholder text for the Name input field. |
    | **55** | **company\_field\_placeholder** | Text Field | Enter placeholder text for the Company input field. |
    | **56** | **email\_field\_placeholder** | Text Field | Enter placeholder text for the Email input field. |
    | **57** | **phone\_field\_placeholder** | Text Field | Enter placeholder text for the Phone Number input field. |
    | **58** | **inquiry\_field\_placeholder** | Text Field | Enter placeholder text for the Inquiry Subject dropdown. |
    | **59** | **note\_field\_placeholder** | Text Field | Enter placeholder text for the Notes/Message input field. |
    | **60** | **success\_message** | Text Field | Enter the success alert message displayed upon valid form submission. |
    | **61** | **error\_message** | Text Field | Enter the error alert message displayed upon invalid form submission. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Section Component & Assets">
        Select **Partnership Opportunity** (No. 41). Set section **eyebrow** (No. 46), **Heading** (No. 42), upload **Image** (No. 43), and define **cta\_label** (No. 44) / **cta\_url** (No. 45).
      </Step>
      <Step title="Configure Form Field Labels & Placeholders">
        Fill in field labels (No. 47–51, 53) and corresponding placeholder prompts (No. 54–59) for Name, Company, Email, Phone, Inquiry, and Notes.
      </Step>
      <Step title="Configure Dropdown Options & Alerts">
        Click (\+) on **inquiry\_dropdown\_option** (No. 52) to populate topic choices. Enter system notification messages in **success\_message** (No. 60) and **error\_message** (No. 61).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Innovation**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to build out required visual modules sequentially (Hero Header, Curated Products, Inspiration Journey, Industry Collaborations, and Partnership Inquiries with Spacers).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the Innovation page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Curated Product Collection" color="#10b981" icon="store">
    Showcase innovation products with dynamic filtering options, customizable category labels, and direct buy CTAs.
  </Card>

  <Card title="Industry Collaboration Grid" color="#38bdf8" icon="handshake">
    Highlight B2B partnerships and civil sector initiatives using modular card blocks with icons and descriptions.
  </Card>

  <Card title="Partnership Inquiry Form" color="#f59e0b" icon="envelope-open-text">
    Fully customizable lead generation form complete with custom topic dropdowns, placeholders, and response notifications.
  </Card>
</CardGroup>

---

<Warning>
  Always ensure that all form field placeholders, inquiry dropdown options, and success/error messages are accurately translated across all language tabs before publishing.
</Warning>