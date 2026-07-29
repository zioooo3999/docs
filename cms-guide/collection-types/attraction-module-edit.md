---
title: "Attraction Module - Edit"
sidebarTitle: "Edit"
description: "Overview and step-by-step procedure for editing existing attraction entries in the Tempe Park CMS."
---

## Overview

The **Edit Data** feature in the Attraction module allows administrators to update or modify existing attraction information stored in the system—including attraction names, descriptions, media assets, locations, amenities, and operational schedules.

Changes saved or published through this feature immediately synchronize with the Tempe Park website, ensuring all visitor-facing information remains accurate, engaging, and up-to-date.

---

## Form Fields & Interface Reference

<Frame>
  ![Edit Attraction Primary View](/images/0-\(13\).png "Edit Attraction Primary View")
</Frame>

<Frame>
  <img
    alt="Edit Attraction Page View"
    lightAlt="Edit Attraction Page View"
    darkAlt="Edit Attraction Page View"
    src="/images/0-(14).png"
    className="dark:hidden"
  />
  <img
    alt="Edit Attraction Page View"
    lightAlt="Edit Attraction Page View"
    darkAlt="Edit Attraction Page View"
    src="/images/0-(14).png"
    className="hidden dark:block"
  />
</Frame>

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1** | **Tab Draft** _(Editable Form)_ | Switch to this tab when editing active form fields. |
| **2** | **Tab Published** | Read-only view showing the current live content on the frontend. |
| **3** | **Title** | Update the primary attraction name. |
| **4** | **Slug** | Modify the URL-friendly identifier for the attraction page. |
| **5** | **Description** | Edit the main narrative/body description. |
| **6** | **Publish** | Save and deploy changes immediately to the live website landing page. |
| **7** | **Save** | Preserve edits as a **Draft** without publishing them publicly. |
| **8** | **Set up Preview** | Preview content layout before publishing live. |
| **9** | **Multilingual** | Switch between localized languages (**English**, **Indonesian**, **Chinese**). |
| **10** | **short\_description** | Update the brief summary used in listing cards and teasers. |
| **11** | **Cover Image** | Change or replace the main hero header graphic. |
| **12** | **Gallery** | Add or remove supplementary images for the attraction gallery. |
| **13** | **opening\_hours\_weekdays** | Adjust operational schedule for regular weekdays. |
| **14** | **opening\_hours\_weekend** | Adjust operational schedule for weekends and public holidays. |
| **15** | **age\_requirement** | Set or modify age recommendations and restrictions. |
| **16** | **Note** | Input special notices or advisory information for visitors. |
| **17** | **related\_activities** | Link related activities from the dropdown menu. |
| **18** | **is\_highlight** | Set to `true` to feature this attraction on main landing hubs; otherwise select `false`. |

---

## Step-by-Step Procedure

<Steps>
  <Step title="Review the Form Interface">
    Open the desired attraction entry from the main Attraction menu list to load the editor.
  </Step>
  <Step title="Update the Form Fields">
    Modify the necessary field values according to your content updates (such as title, operational schedule, gallery images, or related activities).
  </Step>
  <Step title="Save or Publish Changes">
    Click **Save** to preserve edits in **Draft** state, or click **Publish** to deploy the updated information directly to the live landing page.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Instant Synchronization" color="#10b981" icon="arrows-rotate">
    Updates published through this module directly refresh live attraction details across the platform.
  </Card>

  <Card title="Schedule & Media Control" color="#38bdf8" icon="calendar-days">
    Full governance over gallery collections, age guidelines, and weekday vs. weekend operating hours.
  </Card>

  <Card title="Relational Integration" color="#f59e0b" icon="link">
    Connect attractions seamlessly to related activities and highlight entries on key showcase pages.
  </Card>
</CardGroup>

---

<Note>
  **Note:** Remember to verify all localized language versions under the **Multilingual** toggle prior to publishing changes.
</Note>