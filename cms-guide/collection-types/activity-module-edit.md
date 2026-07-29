---
title: "Edit"
sidebarTitle: "Edit"
description: "The Activity module in the Tempe Park CMS is used to manage information about the various activities and events available at Tempe Park."
---

<Note>
  Use **Save button** to retain changes as Draft, or **Publish** to immediately push modified activity data to the live website.
</Note>

## Procedure<br /><br />

<Steps>
  <Step title="Review the form">
    Edit Data feature in the Activity module is used to update or modify activity information already stored in the system. Administrators can make changes to activity data, such as activity name, description, image, schedule, location, and other information as needed.

    Changes to data made through this feature will immediately affect the activity information displayed on the Tempe Park website after the data is successfully saved, so that the information available to visitors remains accurate and up-to-date.

    The following is the main view of the Edit activity page.
  </Step>
  <Step title="Complete the form">
    <Frame>
      ![0 (6)](/images/0-\(6\).png "0 (6)")
    </Frame>

    <Frame>
      ![0 (7)](/images/0-\(7\).png "0 (7)")
    </Frame>

    ### Edit Activity Form Elements

    | No | Element | Function |
    | :-- | :-- | :-- |
    | **1** | **Tab Draft (editable form)** | Use this form tab when the user wants to edit data. |
    | **2** | **Tab Published** | Use this form tab if the user wants to see the data that has been inputted (published). The form on this tab is read only and cannot be edited. |
    | **3** | **Title** | Enter activity title changes. |
    | **4** | **Slug** | Enter activity slug changes. |
    | **5** | **Description** | Enter changes to the activity description. |
    | **6** | **Publish** | Use this button if the user wants to immediately publish (apply to the website landing page) the modified data, which will be saved in the system. Data published in the collection can also be used as a relationship to other module data. |
    | **7** | **Save button** | Use this button if the user wants to save or retain data changes. The saved data will have a Draft status, not a Published one. |
    | **8** | **Set up preview** | Use this button to preview previously entered content. |
    | **9** | **Multilingual** | Use this button to switch languages. When the user clicks this button, 3 languages will appear, namely English, Indonesian, and Chinese. When a new user adds 1 multilingual data, this button can be used to add a language version to the data. |
    | **10** | **short\_description** | Enter changes to the short description of the activity. |
    | **11** | **cover\_image** | Enter changes to the activity cover image. |
    | **12** | **gallery** | Enter several gallery images (maximum 3) for the activity. |
    | **13** | **operning\_hours\_weekdays** | Enter Tempe Park's weekday operating hours. |
    | **14** | **opening\_hours\_weekend** | Enter Tempe Park holiday operating hours. |
    | **15** | **age\_recruitment** | Enter the recommended age for an activity. |
    | **16** | **Note** | Enter Tempe Park activity notes. |
    | **17** | **related\_activity** | Enter the related activity Tempe Park will add. |
    | **18** | **is\_highlight** | Select false if the content to be entered is not highlighted, select true if the content will be highlighted. |

    ---

    <Frame>
      ![0 (8)](/images/0-\(8\).png "0 (8)")
    </Frame>

    ### Activity List View Controls

    The following is the main display of the Activity menu:

    | No | Element | Function |
    | :-- | :-- | :-- |
    | **1** | **Search Button** | Click this icon to search for the desired keyword, the keyword will appear based on general information data, namely title, slug, and short\_description. |
    | **2** | **Filter Button** | Use this button to search for keywords within a specific field, such as searching for keywords in only one field. When the user clicks, they will be prompted to select a field and then type in keywords that match the data in that field. |
    | **3** | **Checkbox Button** | Use this button if the user wants to perform multiple actions, such as deleting, publishing, or unpublishing more than one record simultaneously. Clicking multiple records will bring up the publish, unpublish, and delete buttons. Clicking one of the action options will cause the selected record to respond accordingly. |
    | **4** | **Id** | Data ID information from Activity Module. |
    | **5** | **Title** | Activity title information. |
    | **6** | **Slug** | Activity content slug information. |
    | **7** | **Short Description** | A brief description of the activity content. |
    | **8** | **Available In** | Multilingual data information allows users to edit data using this button. Select multi-language based on the data to be selected. After clicking multi-language, the user will be directed to edit the data in the selected multi-language. |
    | **9** | **Status** | Data status information whether it has been published or is a draft. |
    | **10** | **Multilingual Button** | Use this button if the user wants to switch languages. The data displayed will be based on the multilingual data entered. Available languages are English, Indonesian, and Chinese. |
    | **11** | **Settings** | Use this button if the user wants to display fields or columns according to their wishes. |
    | **12** | **Tombol Create New Entry** | Use this button if the user wants to add new position data to the system. |
  </Step>
</Steps>

---

## Workflow Features

<CardGroup cols={3}>
  <Card title="Live Preview & Draft" color="#10b981" icon="eye">
    Inspect updates via Set Up Preview before making live revisions on the frontpage.
  </Card>

  <Card title="Batch Operations" color="#38bdf8" icon="list-check">
    Execute bulk actions like multi-select publish, unpublish, or delete across entry records.
  </Card>

  <Card title="Localized Editing" color="#f59e0b" icon="language">
    Manage and translate activity records independently across English, Indonesian, and Chinese.
  </Card>
</CardGroup>