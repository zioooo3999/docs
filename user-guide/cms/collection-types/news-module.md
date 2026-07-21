---
title: "News Module"
sidebarTitle: "News"
description: "The News module in the Tempe Park CMS is used to manage news data displayed on the Tempe Park website."
---

<CardGroup cols={3}>
  <Card title="Manage content" icon="newspaper" color="#10b981">Use this module to manage structured CMS content for Tempe Park.</Card>
  <Card title="Publish workflow" icon="image" color="#38bdf8">Save content as Draft or publish it for the website frontpage.</Card>
  <Card title="Relationships" icon="tag" color="#f59e0b">Use related data, categories, images, and multilingual fields where the module provides them.</Card>
</CardGroup>

<Note>
This page preserves the original wording from `[EN] Tempe Park Doc-part-3.pdf` and organizes it into Mintlify components for easier scanning.
</Note>

## Reference view
<Frame>
  ![News Module reference page](/images/collection-types/news-module-reference-page-49.png)
</Frame>

<AccordionGroup>
  <Accordion title="1.2.1.7. News Module">

    <Warning>
      Review multilingual, status, and relationship fields before publishing content.
    </Warning>

    The News module in the Tempe Park CMS is used to manage and store news information,  
    the latest updates, and updates on Tempe Park-related activities. This module serves as a  
    CMS collection for publishing news content, which will then be displayed on the Tempe  
    Park website as an information resource for visitors.  
    Through this module, administrators can add and organize various news information, such  
    as news titles, content, images, publication dates, authors, and other supporting information  
    as needed. The managed news content aims to provide the latest information on Tempe  
    Park's activities, events, announcements, promotions, and other developments.  
    Here is the main view of the News menu:  
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
    4 Id ID information from News data  
    5 Title News title information  
    6 Slug Slug news information  
    7 Excerpt Brief description information of the content to be  
    displayed  
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
    12 Tombol Create New Entry Use this button if the user wants to add new FAQ  
    Category data to the system.  
    The following is a frontend view based on data taken from the News collection module. The  
    contents of this module will become the frontend content on the News page, taking the  
    form of a visual news pagination list:
  </Accordion>

  <Accordion title="1.2.1.7.1. Create New Entry">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry button in the News module is used to add new news data to the  
    system. This feature allows administrators to input various news information, such as the  
    title, content, image, publication date, author, and other supporting information, which will  
    be displayed on the website.  
    Successfully added news data will be stored in the system and can be published on the  
    Tempe Park website news page as the latest information for visitors.  
    Here is the main view of the New News page:  
    **No Elements Function**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the data  
    that has been input (published), the form on this tab  
    is read only and cannot be edited.  
    3 Title Enter the news title  
    4 Excerpt Enter a short description of the news that will be  
    displayed as a preview of the news description.  
    5 Content Enter news content or description  
    6 Slug Enter news slug  
    7 Publish Use this button if the user wants to directly publish  
    (implement it on the website landing page) the data  
    that will be entered into the system. Data that has  
    been published in the collection can also be used as  
    a relationship to data from other modules.  
    8 Save button Use this button if the user wants to save new data  
    that will be entered into the system. The saved data  
    will have a Draft status, not a Published one.  
    9 Multilingual Use this button to switch languages. When the user  
    clicks this button, 3 languages will appear, namely  
    English, Indonesian, and Chinese. When a new user  
    adds 1 multilingual data, this button can be used to  
    add a language version to the data.  
    10 cover_image Enter or upload a cover image file for the news  
    content to be added.  
    11 author Enter the name of the news author  
    12 published_date Enter the news publish date  
    13 category Enter news category  
    14 Tags Enter news tags
  </Accordion>

  <Accordion title="1.2.1.7.2. Edit">

    The Edit Data feature in the News module is used to update or modify news data stored in  
    the system. Administrators can make changes to news titles, content, images, publication  
    dates, and other information as needed.  
    Changes to data made through this feature will immediately affect the news information  
    displayed on the Tempe Park website after the data is successfully saved, so that the  
    information available to visitors remains accurate, relevant, and up-to-date.  
    The following is the main view of the Edit FAQ Category page:  
    **No Elements Function**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the data  
    that has been input (published), the form on this tab  
    is read only and cannot be edited.  
    3 Title Enter the news title  
    4 Slug Enter news slug  
    5 Excerpt Enter a short description of the news that will be  
    displayed as a preview of the news description.  
    6 Content Enter news content or description  
    7 Publish Use this button if the user wants to directly publish  
    (implement it on the website landing page) the data  
    that will be entered into the system. Data that has  
    been published in the collection can also be used as  
    a relationship to data from other modules.  
    8 Save button Use this button if the user wants to save new data  
    that will be entered into the system. The saved data  
    will have a Draft status, not a Published one.  
    9 Multilingual Use this button to switch languages. When the user  
    clicks this button, 3 languages will appear, namely  
    English, Indonesian, and Chinese. When a new user  
    adds 1 multilingual data, this button can be used to  
    add a language version to the data.  
    10 cover_image Enter or upload a cover image file for the news  
    content to be added.  
    11 author Enter the name of the news author  
    12 published_date Enter the news publish date  
    13 category Enter news category  
    14 Tags Enter news tags
  </Accordion>

</AccordionGroup>

## Screenshots

<Frame>
  ![News menu](/images/collection-types/news-module-menu.png)
</Frame>

<Frame>
  ![News frontend view](/images/collection-types/news-module-frontend-view.png)
</Frame>

<Frame>
  ![New News page](/images/collection-types/news-module-create-new-entry.png)
</Frame>

<Frame>
  ![Edit News page](/images/collection-types/news-module-edit.png)
</Frame>
