---
title: "Activity Module"
sidebarTitle: "Activity"
description: "The Activity module in the Tempe Park CMS is used to manage information about the various activities and events available at Tempe Park."
---

<CardGroup cols={3}>
  <Card title="Manage content" icon="clipboard-list" color="#10b981">Use this module to manage structured CMS content for Tempe Park.</Card>
  <Card title="Publish workflow" icon="calendar-days" color="#38bdf8">Save content as Draft or publish it for the website frontpage.</Card>
  <Card title="Relationships" icon="image" color="#f59e0b">Use related data, categories, images, and multilingual fields where the module provides them.</Card>
</CardGroup>

<Note>
This page preserves the original wording from `[EN] Tempe Park Doc-part-3.pdf` and organizes it into Mintlify components for easier scanning.
</Note>

## Collection Types

Collection Types in Strapi are content types used to manage master data that is repetitive  
(multiple entries) and has the same structure. Collection Types allow the system to store  
multiple data entries within a single content schema, making them ideal for data such as  
articles, products, news, landing pages, events, or other master data.

## Reference view
<Frame>
  ![Activity Module reference page](/images/collection-types/activity-module-reference-page-7.png)
</Frame>

<AccordionGroup>
  <Accordion title="1.2.1.1. Activity Module">

    <Warning>
      Review multilingual, status, and relationship fields before publishing content.
    </Warning>

    The Activity module in the Tempe Park CMS is used to manage information about the  
    various activities and events available at Tempe Park. This module serves as a medium for  
    managing activity content, which will then be displayed on the website's front page as  
    information for visitors.  
    Through this module, administrators can add and organize various activity data, such as  
    activity name, description, images, schedule, location, and other supporting information as  
    needed. The activity content displayed aims to provide visitors with an overview of the  
    experiences and activities available at Tempe Park.  
    The following is the main display of the Activity menu:  
    **No Elements Function**  
    1 Search Button Click this icon to search for the desired keyword,  
    the keyword will appear based on general  
    information data, namely title, slug, and  
    short_description  
    2 Filter Button Use this button to search for keywords within a  
    specific field, such as searching for keywords in only  
    one field. When the user clicks, they will be  
    prompted to select a field and then type in  
    keywords that match the data in that field.  
    3 Checkbox Button Use this button if the user wants to perform  
    multiple actions, such as deleting, publishing, or  
    unpublishing more than one record simultaneously.  
    Clicking multiple records will bring up the publish,  
    unpublish, and delete buttons. Clicking one of the  
    action options will cause the selected record to  
    respond accordingly.  
    4 Id Data ID information from Activity Module  
    5 Title Activity title information  
    6 Slug Activity content slug information  
    7 Short Description A brief description of the activity content  
    8 Available In Multilingual data information allows users to edit  
    data using this button. Select multi-language based  
    on the data to be selected. After clicking multi-  
    language, the user will be directed to edit the data in  
    the selected multi-language.  
    9 Status Data status information whether it has been  
    published or is a draft  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on the  
    multilingual data entered. Available languages are  
    English, Indonesian, and Chinese.  
    11 Settings Use this button if the user wants to display fields or  
    columns according to their wishes.  
    12 Tombol Create New Entry Use this button if the user wants to add new  
    position data to the system.  
    The following is a Frontend View based on data taken from the Activity collection module.  
    The contents of this module will become the frontend content on the Experience section  
    of the Activities page:
  </Accordion>

  <Accordion title="1.2.1.1.1. Create New Entry">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry feature in the Activity module is used to add new activity data  
    available at Tempe Park. This feature allows administrators to input various activity  
    information, such as the activity name, description, image, schedule, location, and other  
    supporting information needed for display on the website.  
    Successfully added activity data will be stored in the system and can be published on the  
    Tempe Park website frontpage as information for visitors.  
    Here is the main view of the New Entry Activity page:  
    **No Elements Function**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the data  
    that has been input (published), the form on this tab  
    is read only and cannot be edited.  
    3 Title Enter the activity title  
    4 Slug Enter activity slug  
    5 Description Enter activity description  
    6 Publish Use this button if the user wants to directly publish  
    (implement it on the website landing page) the data  
    that will be entered into the system. Data that has  
    been published in the collection can also be used as  
    a relationship to data from other modules.  
    7 Save button Use this button if the user wants to save new data  
    that will be entered into the system. The saved data  
    will have a Draft status, not a Published one.  
    8 Multilingual Use this button to switch languages. When the user  
    clicks this button, 3 languages will appear, namely  
    English, Indonesian, and Chinese. When a new user  
    adds 1 multilingual data, this button can be used to  
    add a language version to the data.  
    9 short_description Enter a short description of the activity  
    10 Cover image Enter the cover image of the activity section  
    11 Gallery Enter gallery activity image  
    12 opening_hours_weekdays Enter Tempe Park's weekday operating hours  
    13 opening_hours_weekend Enter Tempe Park's operating hours on holidays  
    14 age_requirement Enter age recommendations for Tempe Park  
    activities.  
    15 Note Enter activity notes  
    16 related_activities Click the dropdown to select some related Tempe  
    Park activities to add.  
    17 is_highlight Select false if the activity data to be added will not  
    be highlighted, select true otherwise.
  </Accordion>

  <Accordion title="1.2.1.1.2. Edit">

    The Edit Data feature in the Activity module is used to update or modify activity information  
    already stored in the system. Administrators can make changes to activity data, such as  
    activity name, description, image, schedule, location, and other information as needed.  
    Changes to data made through this feature will immediately affect the activity information  
    displayed on the Tempe Park website after the data is successfully saved, so that the  
    information available to visitors remains accurate and up-to-date.  
    The following is the main view of the Edit activity page.  
    **No Elements Function**  
    1 Tab Draft Use this form tab when the user wants to edit  
    (editable form) data.  
    2 Tab Published Use this form tab if the user wants to see the data  
    that has been inputted (published). The form on this  
    tab is read only and cannot be edited.  
    3 Title Enter activity title changes  
    4 Slug Enter activity slug changes  
    5 Description Enter changes to the activity description  
    6 Publish Use this button if the user wants to immediately  
    publish (apply to the website landing page) the  
    modified data, which will be saved in the system.  
    Data published in the collection can also be used as  
    a relationship to other module data.  
    7 Save button Use this button if the user wants to save or retain  
    data changes. The saved data will have a Draft  
    status, not a Published one.  
    8 Set up preview Use this button to preview previously entered  
    content.  
    9 Multilingual Use this button to switch languages. When the user  
    clicks this button, 3 languages will appear, namely  
    English, Indonesian, and Chinese. When a new user  
    adds 1 multilingual data, this button can be used to  
    add a language version to the data.  
    10 short_description Enter changes to the short description of the  
    activity.  
    11 cover_image Enter changes to the activity cover image  
    12 gallery Enter several gallery images (maximum 3) for the  
    activity  
    13 operning_hours_weekdays Enter Tempe Park's weekday operating hours  
    14 opening_hours_weekend Enter Tempe Park holiday operating hours  
    15 age_recruitment Enter the recommended age for an activity.  
    16 Note Enter Tempe Park activity notes  
    17 related_activity Enter the related activity Tempe Park will add.  
    18 is_highlight Select false if the content to be entered is not  
    highlighted, select true if the content will be  
    highlighted.  
    The following is the main display of the Activity menu:  
    **No Elements Function**  
    1 Search Button Click this icon to search for the desired keyword,  
    the keyword will appear based on general  
    information data, namely title, slug, and  
    short_description  
    2 Filter Button Use this button to search for keywords within a  
    specific field, such as searching for keywords in only  
    one field. When the user clicks, they will be  
    prompted to select a field and then type in  
    keywords that match the data in that field.  
    3 Checkbox Button Use this button if the user wants to perform  
    multiple actions, such as deleting, publishing, or  
    unpublishing more than one record simultaneously.  
    Clicking multiple records will bring up the publish,  
    unpublish, and delete buttons. Clicking one of the  
    action options will cause the selected record to  
    respond accordingly.  
    4 Id Data ID information from Activity Module  
    5 Title Activity title information  
    6 Slug Activity content slug information  
    7 Short Description A brief description of the activity content  
    8 Available In Multilingual data information allows users to edit  
    data using this button. Select multi-language based  
    on the data to be selected. After clicking multi-  
    language, the user will be directed to edit the data in  
    the selected multi-language.  
    9 Status Data status information whether it has been  
    published or is a draft  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on the  
    multilingual data entered. Available languages are  
    English, Indonesian, and Chinese.  
    11 Settings Use this button if the user wants to display fields or  
    columns according to their wishes.  
    12 Tombol Create New Entry Use this button if the user wants to add new  
    position data to the system.
  </Accordion>

</AccordionGroup>

## Screenshots

<Frame>
  ![Activity menu](/images/collection-types/activity-module-menu.png)
</Frame>

<Frame>
  ![Activity frontend view](/images/collection-types/activity-module-frontend-view.png)
</Frame>

<Frame>
  ![New Entry Activity page](/images/collection-types/activity-module-create-new-entry.png)
</Frame>

<Frame>
  ![Edit Activity page](/images/collection-types/activity-module-edit.png)
</Frame>
