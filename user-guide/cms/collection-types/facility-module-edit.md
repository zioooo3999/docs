---
title: "Edit Entry"
sidebarTitle: "Edit Entry Facility"
description: "User guide for editing and updating existing facility entries in the Tempe Park CMS."
---

## Overview

The **Edit Data** feature in the Facility module is used to update or modify facility information stored in the system. Administrators can make changes to facility data such as the facility name, description, image, location, and other information as needed.

Changes to data made through this feature will immediately affect the facility information displayed on the Tempe Park website after the data is successfully saved, ensuring that the information available to visitors remains accurate and up-to-date.

---

## Form Fields & Interface Reference

<Frame>
  ![Edit Facility Page](/images/0-\(26\).png "Edit Facility Page")
</Frame>

<Frame>
  ![Edit Facility Page](/images/0-\(25\).png "Edit Facility Page")
</Frame>

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1** | **Tab Draft** _(editable form)_ | Switch to this tab when editing active form fields. |
| **2** | **Tab Published** | Read-only view showing the current live content on the frontend. |
| **3** | **Title** | Update the primary facility title. |
| **4** | **Slug** | Modify the URL-friendly identifier for the facility page. |
| **5** | **Description** | Edit the main narrative/body description. |
| **6** | **Publish** | Save and deploy changes immediately to the live website landing page. |
| **7** | **Save** | Preserve edits as a **Draft** without publishing them publicly. |
| **8** | **Set up Preview** | Preview content layout on the frontpage before saving modifications. |
| **9** | **Multilingual** | Switch between localized languages (**English**, **Indonesian**, **Chinese**). |
| **10** | **short\_description** | Update the brief summary used in listing cards and teasers. |
| **11** | **Cover image** | Change or replace the main hero cover image. |
| **12** | **Gallery** | Select or update secondary gallery images (maximum of 3 images). |
| **13** | **opening\_hours\_weekdays** | Adjust weekday operational schedules. |
| **14** | **opening\_hours\_weekdend** | Adjust weekend and public holiday closing hours. |
| **15** | **age\_requirement** | Set or modify age recommendations and restrictions. |
| **16** | **Note** | Input special notices or advisory information for visitors. |
| **17** | **related\_facilities** | Select or update related facility linkages from the dropdown. |
| **18** | **is\_highlight** | Set to `true` to feature/highlight the facility on landing hubs; otherwise select `false`. |

---

## Step-by-Step Procedure

<Steps>
  <Step title="Review the Form Interface">
    Navigate to the Facility list and select the facility entry you wish to modify to load the editor.
  </Step>
  <Step title="Update Form Fields">
    Modify the necessary facility attributes (such as title, operating schedules, gallery images, or related facility linkages).
  </Step>
  <Step title="Preview & Save or Publish">
    Use **Set up Preview** to check changes on the frontpage, then click **Save** to preserve edits in **Draft** state or click **Publish** to deploy updates to the live website.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Live Preview" color="#10b981" icon="eye">
    Test layout and visual changes on the frontpage before committing edits to the database.
  </Card>

  <Card title="Gallery Limit" color="#38bdf8" icon="images">
    Supports dynamic gallery updates with a constrained maximum of 3 visual assets.
  </Card>

  <Card title="Instant Publishing" color="#f59e0b" icon="paper-plane">
    Directly update live production content or store modifications safely in draft state.
  </Card>
</CardGroup>

---

<Note>
  **Note:** Verify both `opening_hours_weekdays` and `opening_hours_weekdend` values when modifying schedule information to keep visitor details accurate.
</Note>