---
title: "Create / Setup Contact Us"
sidebarTitle: "Contact Us"
description: "Comprehensive guide for configuring the Contact Us page layout in the Tempe Park CMS using the Page Builder, including hero headers and the 'Let's Connect' inquiry form."
icon: "address-book"
---

<Tip>
  Use the **Save** button to keep content as a Draft, or click **Publish** when the data is ready to appear on the website frontpage.
</Tip>

## Overview

The **Create/Setup Contact Us** feature in the Page module allows administrators to design and structure the Contact Us page layout using the Page Builder. Utilizing this mechanism, administrators can organize content, section order, and page layout to ensure the front page remains attractive, dynamic, and intuitive for visitors—integrating a hero header section alongside a dedicated "Let's Connect" inquiry form to provide a streamlined, user-friendly contact experience.

---

## Form Fields & Interface Reference

<Frame>
  ![Contact Us Setup Form Interface](/images/0-\(53\).png)
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

Configure each section of the Contact Us page sequentially using the controls detailed below.

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
  <Tab title="2. Let's Connect Section">
    ### Let's Connect Section Controls (No. 18–35)

    <Frame>
      ![Let's Connect Section Configuration](/images/0-\(53\).png)
    </Frame>

    | No | Component / Field | Type | Function & Description |
    | :-- | :-- | :-- | :-- |
    | **18** | **Contact** | Group Button | Return to the Contact component group to display the Contact Us component. |
    | **19** | **Contact Us** | Component | Click this component to display the fields required to add content to the Let's Connect section on the Contact Us page. |
    | **20** | **eyebrow** | Text Field | Enter the section category/eyebrow name. |
    | **21** | **heading** | Text Field | Enter the primary section heading title. |
    | **22** | **image** | Media Field | Select or upload an image asset for this section. |
    | **23** | **name\_label** | Text Field | Enter the field label for the Name input column in the form. |
    | **24** | **email\_label** | Text Field | Enter the field label for the Email input column in the form. |
    | **25** | **phone\_label** | Text Field | Enter the field label for the Phone input column in the form. |
    | **26** | **topics\_label** | Text Field | Enter the field label for the Topics selection column in the form. |
    | **27** | **notes\_label** | Text Field | Enter the field label for the Note/Message column in the form. |
    | **28** | **name\_placeholder** | Text Field | Enter prompt placeholder text for the Name input field. |
    | **29** | **email\_placeholder** | Text Field | Enter prompt placeholder text for the Email input field. |
    | **30** | **phone\_placeholder** | Text Field | Enter prompt placeholder text for the Phone input field. |
    | **31** | **topics\_placeholder** | Text Field | Enter prompt placeholder text for the Topics selection field. |
    | **32** | **notes\_placeholder** | Text Field | Enter prompt placeholder text for the Notes/Message field. |
    | **33** | **cta\_label** | Text Field | Enter the button label text for the form submission CTA button. |
    | **34** | **success\_message** | Text Field | Enter the alert message displayed when a visitor successfully submits the contact form. |
    | **35** | **error\_message** | Text Field | Enter the error message displayed when form submission fails or contains validation errors. |

    #### Step-by-Step Procedure

    <Steps>
      <Step title="Add Contact Us Component">
        Click **Add a component to blocks** (No. 7), select the **Contact** component group (No. 18), and click **Contact Us** (No. 19).
      </Step>
      <Step title="Configure Section Heading & Image">
        Define category in **eyebrow** (No. 20), title in **heading** (No. 21), and upload visual asset in **image** (No. 22).
      </Step>
      <Step title="Set Form Labels & Placeholders">
        Input field titles for **name\_label** (No. 23) through **notes\_label** (No. 27), and enter corresponding hint text in **name\_placeholder** (No. 28) through **notes\_placeholder** (No. 32).
      </Step>
      <Step title="Define Submission Button & Feedback Alerts">
        Set submit button text in **cta\_label** (No. 33), positive feedback in **success\_message** (No. 34), and error notifications in **error\_message** (No. 35).
      </Step>
    </Steps>
  </Tab>
</Tabs>

---

## Finalizing Page Publication

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Page module in the CMS navigation bar and select **Create/Setup Contact Us**.
  </Step>
  <Step title="Configure Page Titles & SEO Metadata">
    Enter page **title** (No. 3), page **slug** (No. 4), and click **(\+) No entry yet** (No. 6) to fill in `metaTitle`, `metaDescription`, and `shareImage`.
  </Step>
  <Step title="Assemble Page Sections via Page Builder">
    Click **Add a component to blocks** (No. 7) to sequentially insert required blocks (Page Header and Contact Us inquiry form).
  </Step>
  <Step title="Save or Publish">
    Click **Save button** (No. 9) to keep configurations as a draft, or click **Publish** (No. 8) to push the Contact Us page live.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Customizable Inquiry Fields" color="#10b981" icon="list-check">
    Fully editable form labels and placeholder prompts for Name, Email, Phone, Topic, and Message entries.
  </Card>

  <Card title="Dynamic Submission Feedback" color="#38bdf8" icon="message-check">
    Configurable success and error toast notifications to provide instant feedback upon form submission.
  </Card>

  <Card title="Rich Visual Layout" color="#f59e0b" icon="image">
    Integrated visual banner and section imagery to complement form fields and maintain brand identity.
  </Card>
</CardGroup>

---

<Warning>
  Always verify that all form labels, placeholders, and feedback messages are accurately translated across all multilingual tabs before publishing to ensure a consistent experience for all global visitors.
</Warning>