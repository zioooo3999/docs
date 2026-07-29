---
title: "News Category Module"
sidebarTitle: "News Category"
description: "The News Category module in the Tempe Park CMS is used to manage categories for News content."
---

<CardGroup cols={3}>
  <Card title="Manage content" icon="tags" color="#10b981">Use this module to manage structured CMS content for Tempe Park.</Card>
  <Card title="Publish workflow" icon="folder-tree" color="#38bdf8">Save content as Draft or publish it for the website frontpage.</Card>
  <Card title="Relationships" icon="newspaper" color="#f59e0b">Use related data, categories, images, and multilingual fields where the module provides them.</Card>
</CardGroup>

<Note>
This page preserves the original wording from `[EN] Tempe Park Doc-part-3.pdf` and organizes it into Mintlify components for easier scanning.
</Note>

## Reference view

<Frame>
</Frame>

<Warning>
  Review multilingual, status, and relationship fields before publishing content.
</Warning>

The News Category module in the Tempe Park CMS is used to manage and store news  
category data used in the News module. This module serves as a CMS collection for  
grouping news so that the information content displayed on the Tempe Park website can  
be arranged more neatly, structured, and easily accessed by visitors.  
Through this module, administrators can create and organize various news categories as  
needed, such as events, promotions, announcements, activities, latest information, and  
other categories. These categories will then be used in the News module to group each  
news item published on the website.  
Here is the main display of the News Category menu:  
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
5 Name News category name information  
6 Slug News category slug information  
7 CreatedAt Data creation date and time information  
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
12 Tombol Create New Entry Use this button if the user wants to add new News  
Category data to the system.  
The following is a frontend view based on data taken from the News Category collection  
module. The contents of this module will become the frontend content on the News page  
under the News category:
