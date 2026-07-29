---
title: "Edit"
sidebarTitle: "Edit"
description: "Overview and step-by-step procedure for editing existing event and calendar entries in the Tempe Park CMS."
---

## Overview

The **Edit Data** feature in the Event/Calendar module is used to update or modify event information stored in the system. Administrators can make changes to event data such as the activity name, date, time, location, description, image, and other information as needed.

Changes to data made through this feature will immediately affect the event information displayed on the Tempe Park website after the data is successfully saved, so that the schedule and activity information available to visitors remains accurate and up-to-date.

---

## Form Fields & Interface Reference

<Frame>
  ![Edit Event / Calendar Page](/images/0-\(19\).png "Edit Event / Calendar Page")
</Frame>

<Frame>
  ![Edit Event / Calendar Page](/images/0-\(20\).png "Edit Event / Calendar Page")
</Frame>

| No | Field / Element | Function & Description |
| :-- | :-- | :-- |
| **1** | **Tab Draft** _(editable form)_ | Switch to this tab when editing active form fields. |
| **2** | **Tab Published** | Read-only view showing the current live content on the frontend. |
| **3** | **Title** | Update the primary event/calendar title. |
| **4** | **Slug** | Modify the URL-friendly identifier for the event page. |
| **5** | **Description** | Edit the main narrative/body description. |
| **6** | **Publish** | Save and deploy changes immediately to the live website landing page. |
| **7** | **Save** | Preserve edits as a **Draft** without publishing them publicly. |
| **8** | **Set up Preview** | Preview content layout before publishing live. |
| **9** | **Multilingual** | Switch between localized languages (**English**, **Indonesian**, **Chinese**). |
| **10** | **short\_description** | Update the brief summary used in listing cards and teasers. |
| **11** | **Cover image** | Change or replace the main hero cover image. |
| **12** | **Gallery** | Upload, replace, or remove secondary images showcasing the event. |
| **13** | **start\_date** | Adjust the starting date and time of the event. |
| **14** | **end\_date** | Adjust the concluding date and time of the event. |
| **15** | **location** | Update the designated venue or location within Tempe Park. |
| **16** | **event\_tipe** | Select or update the event category/type. |

---

## Step-by-Step Procedure

<Steps>
  <Step title="Review the Form Interface">
    Open the desired event/calendar record from the main list view to access the editor.
  </Step>
  <Step title="Update Form Fields">
    Modify the necessary field values according to your schedule updates (such as event title, start/end dates, location, or gallery images).
  </Step>
  <Step title="Preview & Save">
    Use **Set up Preview** to check layout changes, then click **Save** to keep as a draft or click **Publish** to push updates live to the website calendar.
  </Step>
</Steps>

---

## Key Features

<CardGroup cols={3}>
  <Card title="Real-Time Schedule Sync" color="#10b981" icon="arrows-rotate">
    Updated dates, venues, and activity details reflect immediately on the visitor-facing calendar upon saving or publishing.
  </Card>

  <Card title="Live Preview & Drafts" color="#38bdf8" icon="eye">
    Inspect changes via Set Up Preview or preserve modifications safely in Draft state before making them live.
  </Card>

  <Card title="Multilingual Updates" color="#f59e0b" icon="language">
    Manage synchronized schedule updates across English, Indonesian, and Chinese language versions.
  </Card>
</CardGroup>

---

<Note>
  **Note:** Verify both `start_date` and `end_date` fields when adjusting multi-day events to prevent scheduling overlaps on the frontend.
</Note>