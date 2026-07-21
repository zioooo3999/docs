---
title: "Page Module"
sidebarTitle: "Page"
description: "The Page module in the Tempe Park CMS is used to create and structure front page content using the Page Builder mechanism."
---

<CardGroup cols={3}>
  <Card title="Manage content" icon="layout-template" color="#10b981">Use this module to manage structured CMS content for Tempe Park.</Card>
  <Card title="Publish workflow" icon="blocks" color="#38bdf8">Save content as Draft or publish it for the website frontpage.</Card>
  <Card title="Relationships" icon="globe" color="#f59e0b">Use related data, categories, images, and multilingual fields where the module provides them.</Card>
</CardGroup>

<Note>
This page preserves the original wording from `[EN] Tempe Park Doc-part-3.pdf` and organizes it into Mintlify components for easier scanning.
</Note>

## Reference view
<Frame>
  ![Page Module reference page](/images/collection-types/page-module-reference-page-61.png)
</Frame>

<AccordionGroup>
  <Accordion title="1.2.1.9. Page Module">

    <Warning>
      Review multilingual, status, and relationship fields before publishing content.
    </Warning>

    The Page module in the Tempe Park CMS is used to manage and structure the appearance  
    of a website's front page using the Page Builder mechanism. This module allows  
    administrators to create, organize, and update various sections or page components without  
    making direct changes to the application code.  
    Each page can be flexibly structured using available blocks or sections, such as banners,  
    event information, galleries, ticket information, promotions, and other sections as needed.  
    This module allows for more dynamic, structured, and customizable frontpage content  
    management by CMS administrators.  
    The following is the main display of the Page menu:  
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
    4 Id Displays page ID information  
    5 Title Displays page title information  
    6 Slug Displays page slug information  
    7 This Displays seo page information  
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
    12 Create button Use this button if the user wants to add new News  
    New Entry  
    Category data to the system.
  </Accordion>

  <Accordion title="1.2.1.9.1. Create Setup Homepage">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Homepage feature in the Page module allows you  
    to create a new homepage and organize the front page content of the Tempe Park website  
    using the Page Builder. This feature allows administrators to add various sections or  
    homepage components, such as a hero section, banner slider, what's on Tempe Park section,  
    journey section, our commitment section, and other sections to suit their website's visual  
    needs.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    The following is the main view of the Create New Entry Page:  
    
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To fill in the complete content using this page module (page builder), follow these steps. (In  
    this case, it's the Homepage)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Hero Click this component to fill in the hero section  
    content on the Homepage.  
    13 Hero After the Hero component is clicked, the display  
    will look like this, and the user can fill in the hero  
    section content for the Homepage.  
    14 title Enter the title of the hero section of the  
    Homepage  
    15 description Enter the description of the hero section of the  
    Homepage  
    16 Image Upload an image to be displayed in the hero  
    section of the Homepage.  
    17 text_button_1 Enter the CTA 1 button text that will be  
    displayed in the hero section of the Homepage.  
    18 text_button_2 Enter the CTA 2 button text that will be  
    displayed in the hero section of the homepage.  
    Banner Slider Section  
    19 Dynamic Click this component button to display the  
    components needed to fill the slider content in  
    the next section on the homepage.  
    20 Slider Click this button to display the fields required to  
    fill in the slider content setup.  
    21 layout Click to bring up the layout dropdown, for the  
    homepage select "default"  
    22 source_type Click to bring up the source_type dropdown, for  
    the homepage select manual  
    23 item_cta_label Enter the CTA label item, for (homepage just  
    leave it blank)  
    24 show_dots Slide to true to display dots below the slider  
    (dotted pagination)  
    25 show_arrows Slide to true to reveal the arrows used to move  
    the slides.  
    26 items_limit Enter the limit of slider items that can be  
    displayed.  
    27 Slides After the user selects manual in the source_type  
    field option, a slide component will appear which  
    must be filled in by the user.  
    28 heading Enter slide sequence number  
    29 eyebrow (For the home page slider section, leave this  
    section blank)  
    30 highlight (For the home page slider section, leave this  
    section blank)  
    31 description (For the home page slider section, leave this  
    section blank)  
    32 image Select or enter a slider image  
    33 cta_label (For the home page slider section, leave this  
    section blank)  
    34 cta_url (For the home page slider section, leave this  
    section blank)  
    35 enable_button (For the home page slider section, slide it to the  
    false section)  
    What's On Tempe Park Section  
    36 Text The next step is to click on this component group  
    to add a new section to the homepage.  
    37 Heading Click on the heading component to display the  
    fields needed to add a new section to the  
    homepage.  
    38 Eyebrow Enter the name of the next section to be added.  
    39 heading Enter the title of the next section to be added.  
    40 position Click to bring up the dropdown, select what  
    alignment to apply to the next section.  
    41 Flexbox To apply the next content on the homepage, click  
    the Flexbox component in the dynamic  
    component group.  
    42 Flexbox The display will look like this and will display the  
    fields required for further content input.  
    43 readmore_button_text NOT YET  
    44 view_all_text NOT YET  
    45 source_type NOT YET  
    46 layout NOT YET  
    47 columns NOT YET  
    48 items_limit NOT YET  
    49 show_category_badge NOT YET  
    50 show_excerpt NOT YET  
    51 item_cta_label NOT YET  
    52 Button Click on this component group to bring up the  
    fields required to populate this CTA dissection  
    button.  
    53 Button Multiple Click this component to display the fields  
    required to fill in the CTA button in this section.  
    54 (+) No. entry yet. Click to Click to display the button filling detail field in  
    add one  
    this section.  
    55 Text Enter the button title  
    56 link Enter the page URL link as the direct page button  
    57 style Enter button style  
    58 Add an Entry Use this button again if you want to include a  
    back button in this section.  
    Journey Section  
    59 Go back to steps 19 to 27 Return to step number to add a Journey Section,  
    then to add a slider image, follow the steps  
    below (The sequence number repeats from no.  
    28 to 35)  
    28 heading Enter slide sequence number  
    29 eyebrow Enter the section name (Journey)  
    30 highlight Enter the section title on the slider image  
    31 description Enter slider description in slider image  
    32 image Select or enter a slider image  
    33 cta_label Insert CTA label on slider image  
    34 cta_url Enter the page URL for the CTA on the slider  
    image.  
    35 enable_button When TRUE is selected, it will display the  
    button_text and button_link fields. If TRUE is  
    selected, fill in the fields to fill in the CTA button  
    text.  
    Our Commitment  
    60 Go back to steps 36 to 40 To name or create the next section, return to  
    that number to create a new name, title and  
    section position.  
    61 Go back to steps 19 to 35 To create slider content, return to the number,  
    adjust it to the needs of the image slider content.  
    Article & News Update Section  
    62 Go back to steps 36 to 40 To name or create the next section, return to  
    that number to create the name, title, position of  
    the new section or this section.  
    63 Go back to steps 41 to 51 Return to that section to add highlight content to  
    the article & news update section. Adjust the  
    settings as needed, including selecting "news" for  
    the source_type field. This is because it's  
    capturing news data.  
    64 Go back to steps 53 to 58 To add a CTA button to this section (Article &  
    News Update), return to that number.
  </Accordion>

  <Accordion title="1.2.1.9.2. Create Setup Plan Your Visit">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Plan Your Visit feature in the Page module is used  
    to create a new Plan Your Visit page and organize the front page content of the Tempe Park  
    website using the Page Builder mechanism. Through this feature, administrators can add  
    various sections or components to the Plan Your Visit page, such as a hero section, a ticket  
    section, a visitor's guide section, a calendar, a home section, upcoming events, or other  
    sections according to the website's display requirements.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup Plan Your Visit:  
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    this area applied as the hero section image.  
    16 navigation_tabs Slide to true if this page has tabbed navigation  
    17 page_title Enter page title  
    Buy Ticket Section  
    18 Plan Click this component group to display the Buy  
    Ticket component.  
    19 Buy Ticket Click this component to display the detailed  
    fields to fill in the content in this section.  
    20 Buy Ticket After clicking, a display like this will appear  
    (details of the fields that need to be filled in)  
    21 description Enter a description of this section  
    22 Image In the (+) sign in this field, enter or upload the  
    image that will be used for this section.  
    23 Button regular In this group, click the (+) sign to display the  
    fields required to fill in the regular buy button in  
    the section.  
    24 text Enter the text button to buy a regular ticket  
    25 link Enter the URL link of the regular ticket page  
    26 style Select one of the button style types  
    27 button_group In this group, click the (+) sign to display the  
    fields required to fill in the buy group button in  
    the section.  
    28 text Enter the buy group ticket button text  
    29 link Enter the URL link of the ticket group page  
    30 style Select one of the button style types that will be  
    the buy group button style.  
    31 eyebrow Enter a section name for this section.  
    32 heading Enter a section title for this section.  
    Visitor's Guide Section  
    33 text Click on this component group to reveal the  
    Heading component.  
    34 Heading After clicking, the Heading component will  
    appear. Click this component again to display the  
    field details required to input the title content for  
    this section.  
    35 Heading The display will look like this when the Heading  
    component has been clicked.  
    36 eyebrow Enter the name of this section  
    37 position Select one of the section alignment positions on  
    this page.  
    38 heading Enter the section title. After you have finished  
    entering the content of the new section title or  
    the next section,Go back to step number 18. After  
    number 18, continue to number 39.  
    39 Visitor Guide After clicking the plan component group again, a  
    list of components will appear, click on the  
    Visitor Guide component.  
    40 Visitor Guide After clicking on the component, the display will  
    display the details of the fields that need to be  
    filled in to fill in the content in this section or the  
    Visitor Guide section.  
    41 Tabs On the field tabs, click (+) and the field list will  
    appear again as shown in the image.  
    42 image Enter or upload an image to be displayed in this  
    section.  
    43 tab_label Enter the name or label of the tab that will be  
    displayed in this section.  
    44 style Select one of the tab styles (text_image)  
    45 title Enter the content title on the tab  
    46 (+) Add an entry Use this button again if you want to re-enter  
    other tabs in this section.  
    47 cta If you want a CTA button on a tab in this section,  
    click (+) and the required field will appear to fill in  
    the CTA button content.  
    48 text Enter the name or text of the CTA button to be  
    created.  
    49 link Enter the page URL for the direct CTA button to  
    be created.  
    50 style Select the CTA button style to be created  
    Calendar Section  
    Go back to steps 33 to 37 Return to step 1 to add a new section, or the  
    next section, the Calendar section. Once  
    completed, return to step 18. Click the plan  
    component group, and the components needed  
    to fill the content in this section will appear.  
    52 Calendar After clicking on the Calendar component group,  
    the detailed fields that must be filled in to setup  
    the content in this section will appear.  
    53 view Select one of the setups to be applied to the  
    Calendar section, whether the schedule will be  
    displayed weekly or monthly.  
    54 items_limit Enter the limit for displaying the schedule based  
    on the previously selected one.  
    Upcoming Event Section  
    Go back to steps 33 to 37 Return to step 1 to add a new section, or the  
    next section, the Calendar section. Once  
    completed, return to step 18. Click the plan  
    component group, and the components needed  
    to fill the content in this section will appear.  
    55 Triple Active Slider After selecting the plan again, select the Triple  
    Active Slider component to fill the content of this  
    section.  
    56 source_type Select this field by default if the content to be  
    displayed comes from the event collection  
    source, select manual if you want to fill it in  
    manually.  
    57 Items After selecting manual, what will appear is a  
    group of fields that are needed to fill in the  
    content in this section.  
    58 Image Input or upload an image for the content of this  
    section.  
    59 time Enter the event time to be entered manually  
    60 title Enter the title of the event content to be entered  
    manually.  
    61 location Enter the event location, the location in question  
    is the location in Tempe Park  
    62 href Enter the href link for the event to be added  
    manually.  
    63 date Enter the event date to be added manually  
    64 (+) Add an entry Use this button again if you want to add the  
    event again manually.  
    How To Get Here Section  
    65 Go back to steps 33 to 38 To add a new section to this page (How To Get  
    Here Section) return to the number listed and  
    input the section title as required.  
    66 Go back to steps 39 to 50 To add content from the last section on this  
    page, return to the steps in the numbers already  
    written and adjust the content to be added to  
    this section.
  </Accordion>

  <Accordion title="1.2.1.9.3. Create Setup Experience">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Experience feature in the Page module allows you  
    to create a new Experience page and structure the content of the Tempe Park website's  
    Experience front page using the Page Builder. This feature allows administrators to add  
    various sections or components to the Experience page, such as a hero section, Attractions  
    section, Activities section, Facilities section, or other sections, depending on the website's  
    visual requirements.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup Experience:  
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation.  
    17 page_title Enter page title  
    Attraction Section  
    18 Spacer Go back to the component group and select it  
    and click Spacer to add space between this  
    section or the new section you want to add and  
    the header.  
    19 height After clicking the spacer component, it will  
    appear as shown in the image and enter the  
    height to set the spacing distance.  
    20 text Go back to the component group and select text  
    to bring up the component to add a new section  
    title or this section.  
    21 Heading After the component group is selected (text), it  
    will appear as in the image and click Heading to  
    display the field for adding the title of this  
    section.  
    22 eyebrow After clicking the Heading component, a display  
    will appear as shown in the image. Input the  
    section name in the eyebrow field.  
    23 heading Enter the title of this section  
    24 position Select one position for this section  
    25 dynamic Go back to the component group and select and  
    click dynamic to bring up the slider component to  
    add slider image content to this section.  
    26 Slider After clicking the dynamic component group, in  
    that group, click the slider component to display  
    the fields needed to fill in the slider image  
    content.  
    27 layout To add a slider image to the section according to  
    Figma, select default for this field.  
    28 source_type Select one of the sources to be selected, because  
    this is the attraction section, then select  
    attraction, the data source will point to the  
    attraction collection.  
    30 show_dots Slide to the right if you want to use the dots  
    slider on the banner image that will be applied,  
    slide to the left if the opposite is true.  
    31 show_arrows Swipe right if you want to use the arrow keys to  
    move the banner image content. Swipe left if you  
    don't want to.  
    32 item_limits Enter the data limit that will be displayed on the  
    banner image. Please remember that the data  
    source for this section comes from the collection  
    attraction.  
    Activities Section  
    33 Back to numbers 18 to 19 To add space between the next sections, return  
    to that number.  
    34 Back to numbers 20 to 24 To add a section title first, return to that number  
    to add a heading component which functions to  
    add a new or subsequent section title and  
    description.  
    35 Back to numbers 25 to 32 To add content in this section (slider image) the  
    user must return to that number to add the slider  
    component again, the user can add the slider  
    image content back to that component.  
    Facilities Section  
    36 Back to numbers 18 to 19 To provide spacing between the next section or  
    this section, return to that number.  
    37 Back to numbers 20 to 24 To add a title to this section, return to the  
    number to add a heading component which  
    functions to add a title and description for the  
    new or next section.  
    38 Flexbox To add content to this section (Facilities), the  
    user must return to the dynamic component  
    group and click the Flexbox component.  
    39 readmore_button_text Enter the naming or labeling based on the design  
    for the read more button shown in the image in  
    this section.  
    40 view_all_text If there's a "view all" button in this section that  
    allows you to see all the image content in the  
    section, enter the labeling name in this field.  
    Note that this button doesn't exist yet, so it  
    needs to be developed first.  
    41 source_type In this column, select facilities, because the  
    source data that will be taken is based on  
    collection facilities.  
    42 layout Select the layout form for grouping images in this  
    section, if it suits the design, select grid-equal.  
    43 columns Enter or set how many image column setups, if  
    appropriate input design 6  
    44 item_limits Enter the limit number of images or content  
    based on the data source that will be displayed in  
    this section.  
    45 show_category_badge To display the content in this section, select  
    False.  
    46 show_excerpt For this section in this column select False  
    47 item_cta_label Enter the labeling or naming of the CTA button  
    in the content image of this section.  
    48 Back to numbers 18 to 19 To provide space between the last section or this  
    section and the footer content, the user must  
    add a spacer component in the following step.
  </Accordion>

  <Accordion title="1.2.1.9.4. Create Setup Experience Detail">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create Setup Experience Detail feature in the Page module is used to create an  
    Experience Detail page, which is also part of the Experience page on the front page. This  
    setup is used to organize the content of the Tempe Park website's Experience Detail front  
    page, which uses the Page Builder mechanism. Through this feature, administrators can  
    manage Experience Detail content, such as detail content, a section explaining operating  
    hours, and related attraction sections.  
    Here is the main view of Create Setup Experience Detail:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been inputted (published). The form  
    on this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Experience Detail  
    11 experience To display this component, the user must click  
    the button in step number 7, then click this  
    component group.  
    12 Experience Detail Click this component to setup the experience  
    page details such as labeling.  
    13 content_type Select one of the experience details to be used. If  
    the content comes from the attraction section,  
    select the attraction in this column. This applies  
    to all sections on the Experience page.  
    14 breadcrumb_parent_label Enter the parent breadcrumb labeling from the  
    Experience Detail page.  
    15 sidebar_label_opening_ho Enter labeling opening hours weekdays content  
    urs_weekdays  
    in the sidebar  
    16 sidebar_label_opening_ho Enter labeling opening hours weekend content in  
    urs_weekend  
    the sidebar  
    17 sidebar_label_age_requir Enter the labeling age requirement of the  
    ements  
    content in the sidebar.  
    18 sidebar_label_note Enter the labeling note for the content in the  
    sidebar.  
    19 related_attraction_sectio Enter a labeling heading or title for the Related  
    n_heading  
    Attraction section.  
    20 related_attraction_cta_la Enter the labeling of the CTA button for Explore  
    bel  
    More in the related attraction content section.  
    21 related_attraction_cta_ur Enter the URL of the CTA button in the related  
    l  
    attraction content.  
    22 related_attraction_item_c Enter the labeling of the CTA button in each  
    ta_label  
    related attraction content.
  </Accordion>

  <Accordion title="1.2.1.9.5. Create Setup Education">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Education feature in the Page module allows you to  
    create a new Education page and structure the content of the Tempe Park website's  
    Education frontpage using the Page Builder. This feature allows administrators to add  
    various sections or components to the Education page, such as a hero section, a History of  
    Tempe section, a Fun Facts section, a Tempe Warrior & Hero section, a School Programs  
    section, or other sections to suit their website's visual needs.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup Education:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been inputted (published). The form  
    on this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation  
    17 page_title Enter page title  
    History Section  
    18 Spacer Go back to the component group and select it  
    and click Spacer to add space between this  
    section or the new section you want to add and  
    the header.  
    19 height After clicking, a height column will appear, enter  
    the distance value.  
    20 education After inserting the spacer component, click on  
    this component group again to fill in the next  
    content.  
    21 History Section After clicking education, a list of history sections  
    will appear, select the history section  
    component.  
    22 cards In this field, click the (+) button to display the  
    field in the image.  
    23 heading Enter history title  
    24 image Enter or upload an image  
    25 body Enter information about the history  
    26 (+) Add an entry Use this button again if you want to add back  
    content that has been added previously.  
    27 eyebrow Enter the name of this section  
    28 Heading Enter section title  
    Go back to steps 18 to 19 To add further content to this section, the user  
    must return to the steps already written to add  
    the space component so that later the content  
    will have space.  
    Fun Fact Section  
    29 Fun Facts Section Go back to the component group and click on  
    this component to setup the next section or Fun  
    Facts Section.  
    30 card Click the (+) button on this field to display the  
    fields in the image, the fields in your field to add  
    card content to this section.  
    31 icon Enter or upload icon  
    32 heading Enter the content title for each card.  
    33 description Enter a description of the card content in this  
    section.  
    34 Add an entry Use this button to add card content back to this  
    section.  
    35 eyebrow Enter the name of this section  
    36 heading Enter the title of this section  
    Warriors Section  
    37 Warriors Section Go back to the component group and click on  
    this component to setup the next section or  
    Warriors Section.  
    38 warriors Click the (+) sign to display the fields in the  
    image, these fields are used to enter the content  
    of the warriors section.  
    39 name Enter the name warrior  
    40 role_title Enter the warrior role to be added  
    41 description Enter a description of the warrior to be added.  
    42 photo Enter or upload a warrior photo  
    43 Add an entry Use this button again if the user wants to add  
    warrior content.  
    44 eyebrow Enter a section name for this section.  
    45 heading Enter a section title for this section.  
    School Section  
    46 School Section Go back to the component group and click on  
    this component to bring up the fields required to  
    fill in the school section content.  
    47 description Enter a content description  
    48 image Enter or upload a photo of the content section  
    49 eyebrow Enter the name of this section  
    50 Heading Enter the title of this section  
    51 item_learn_more_label Enter the CTA button labeling name for the  
    school program content
  </Accordion>

  <Accordion title="1.2.1.9.6. Create Setup Education Detail">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create Setup Education Detail feature in the Page module is used to create an  
    Education Detail page, which is also part of the Education page on the front page. This setup  
    is used to organize the content of the Education Detail front page of the Tempe Park  
    website using the Page Builder mechanism. Through this feature, administrators can  
    manage Education Detail content, such as detail content, a section explaining operating  
    hours, and related attraction sections.  
    The following is the main view of Create Setup Education Detail:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been inputted (published). The form  
    on this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Education Detail  
    11 experience To display this component, the user must click  
    the button in step number 7, then click this  
    component group.  
    12 Experience Detail Click this component to setup the experience  
    page details such as labeling.  
    13 breadcrumb_parent_label Enter the parent breadcrumb content labeling on  
    this page  
    14 sidebar_label_about_prog Enter the labeling of the section title content in  
    ram  
    the ABOUT THIS PROGRAM sidebar section on  
    this page.  
    15 sidebar_cta_label Enter the CTA button labeling in the About This  
    Program sidebar section content.  
    16 sidebar_cta_url Enter the URL of the CTA button in the ABOUT  
    THIS PROGRAM sidebar section on this page.  
    17 schedule_section_headin Enter the title of the Program Schedule section  
    g  
    of this page.  
    18 related_section_heading Enter text for the title in the Explore Other  
    School Programs section on this page.  
    19 sidebar_join_label Enter a section title for Join This Program on this  
    page.  
    20 related_item_readmore_l Enter text for the Learn More CTA button in the  
    abel  
    Explore Other School Programs section.
  </Accordion>

  <Accordion title="1.2.1.9.7. Create Setup News">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup News feature in the Page module allows you to  
    create a new News page and structure the front page content of the Tempe Park website's  
    News page using the Page Builder. This feature allows administrators to add various  
    sections or components to the News page, such as a banner section, other insights section,  
    or other sections to suit their website's visual needs.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup News:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been inputted (published). The form  
    on this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Banner Section  
    11 News After clicking the "Add a component to blocks"  
    button, several component groups will appear.  
    Select the news component group to display the  
    News Highlight Banner component to fill in the  
    banner image content on this page.  
    12 News Highlight Banner After clicking on the news group, click on this  
    component to display the fields needed to set  
    the banner image on this page.  
    13 read_more_label After successfully clicking the previous  
    component, this field will appear, and fill it with  
    text according to the current multi-language (For  
    example, if the current multi-language is English,  
    then fill it with "Read More"), because this label is  
    for filling static content on the Read More CTA  
    on the banner image.  
    14 News List Return to the news component group and click  
    News List again to display the fields required for  
    setting the content of the next section on this  
    page.  
    15 listing_section_heading Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "OTHER  
    INSIGHTS"), because this field is for filling in  
    static content in the names of other news  
    sections.  
    16 all_categories_label Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "All  
    Categories"), because this field is for filling in  
    static content for naming filters for all categories.  
    17 sort_by_label Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "Sort By"),  
    because this field is for filling in static content for  
    labeling sorting filters.  
    18 year_label Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "Year"),  
    because this field is for filling in static content for  
    labeling filters based on the year.  
    19 oldest_label Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "Newest"),  
    because this field is for filling in static content to  
    label the contents of the Sort By filter based on  
    the oldest news.  
    20 newest_label Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "Newest"),  
    because this field is for filling in static content to  
    label the contents of the Sort By filter based on  
    the latest news.  
    21 all_years_label Fill it with static content according to the current  
    multi-language (For example, if the current multi-  
    language is English, then fill it with "All"), because  
    this field is for filling in static content for labeling  
    filters based on all years.
  </Accordion>

  <Accordion title="1.2.1.9.8. Create Setup News Detail">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create Setup News Detail feature in the Page module is used to create a News Detail  
    page, which is also part of the News page on the front page. This setup is used to organize  
    the Education Detail front page content for the Tempe Park website, which uses the Page  
    Builder mechanism. Through this feature, administrators can manage Education Detail  
    content, such as detail content, a section explaining operating hours, and related attraction  
    sections.  
    Here is the main view of Create Setup News Detail:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the News Detail page.)  
    News Detail  
    11 News Click on this component group to bring up News  
    Details.  
    12 News Detail After clicking the News component group, the  
    user then clicks on this component to display the  
    fields required to fill in the news details.  
    13 breadcrumb_parent_pane Enter the parent labeling of the Breadcrumb  
    l  
    navigation on the news detail page.  
    14 share_label Enter content share labeling on the news detail  
    page  
    15 published_date_label Enter the published date labeling on the news  
    detail page.  
    16 To Top Button Go back to the shared components group and  
    select the To Top Button component.  
    17 career_variant Select false if this page is not a career page,  
    select true otherwise.  
    18 ticket_label Enter the ticket labeling position in the right  
    sidebar on the News Detail page.  
    19 ticket_icon Enter or upload an icon for the ticketing icon  
    which is positioned on the right sidebar on the  
    News Detail page.  
    20 ticket_href Enter the href or slug link of the page to redirect  
    to the ticketing landing page.
  </Accordion>

  <Accordion title="1.2.1.9.9. Create Setup Innovation">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Innovation feature in the Page module allows you  
    to create a new Innovation page and structure the content of the Tempe Park website's  
    Innovation frontpage using the Page Builder. This feature allows administrators to add  
    various sections or components to the Innovation page, such as a hero section, our product  
    section, a menu inspiration section, a collaboration section, an inquiries section, or other  
    sections to suit their website's visual needs.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup Innovation:  
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation  
    17 page_title Enter page title  
    Our Product Section  
    18 Spacer Go back to the component group and select it  
    and click Spacer to add space between this  
    section or the new section you want to add and  
    the header.  
    19 height After clicking, a height column will appear, enter  
    the distance value.  
    20 text To add a new or subsequent section, you must  
    first add a heading to give the section a title.  
    Click on this component group.  
    21 Heading Click this component to bring up the detail fields  
    required to fill in the title of the new section or  
    subsequent sections.  
    22 eyebrow Enter the name of the new or next section  
    23 heading Enter a new or next section title  
    24 position Select one of the position alignments for this  
    section.  
    25 innovation Return to this component group to reveal the  
    components needed to populate the content in  
    this section.  
    26 Curated Collection After clicking the innovation component group,  
    click this component to display the fields  
    required to fill in the content of this section.  
    27 filter_label Enter the text "Filter", the contents of this  
    column will be the labeling of the filtering section  
    on this page.  
    28 buy_button_label Fill in with "Buy", the contents of this column will  
    become the Buy button for users on each  
    product displayed on this page.  
    29 all_category_label Fill in according to your wishes, in essence this  
    column will be a filtering category in the filter  
    section on this page.  
    Menu Inspiration  
    30 Back to numbers 20 to 24 To fill in the next section, the user must return to  
    that number to re-title the new section or the  
    next section.  
    31 Journey Section Return to the innovation component group and  
    click on this component to fill in the next content  
    or Inspiration Menu section.  
    32 cta_label Enter the desired CTA labeling, the CTA label will  
    be displayed as a CTA button on every image in  
    this section or the Inspiration Menu.  
    33 source_type In this column, select the default option (Source  
    data will be taken from the Inspiration Menu data  
    collection), if you want to fill it in manually, select  
    manual.  
    Collaboration Section  
    34 Back to numbers 20 to 24 To fill in the next section, the user must return to  
    that number to re-title the new section or the  
    next section.  
    35 Industry Collaboration Go back to the innovation component group and  
    click on this component to fill in the content of  
    this section or Collaboration Section.  
    36 Industries After clicking on the component in the previous  
    step, then in this column, click the (+) button to  
    display the fields in the image.  
    37 icon Enter the upload of the icon image that will be  
    used in the civil code in this section.  
    38 title Enter a civil card title for this section's content.  
    39 description Enter a description of the card content that will  
    be displayed in this section.  
    40 (+) Add an entry Use this button again if you want to add more  
    card content to this section.  
    Inquiries Section  
    41 Partnership Opportunity Go back to the innovation component group and  
    click on this component to add the next section  
    (Inquiries Section)  
    42 Heading After clicking the component in the previous  
    step, in this field enter the section title.  
    43 Image Enter or upload the image that will be used as  
    the image in this section.  
    44 cta_label Enter a label for the submit form button in this  
    section.  
    45 cta_url Enter the URL of the button in this section.  
    46 eyebrow Enter the title of this section  
    47 nama_field_label Enter the labeling field name  
    48 company_field_label Enter the labeling field company name  
    49 email_field_label Enter email field labeling  
    50 phone_field_label Enter the phone number field labeling  
    51 inquiry_field_label Enter the inquiry field labeling  
    52 inquiry_dropdown_option Click (+) on this field to add a dropdown option  
    to the inquiry topic column, there will be a  
    dropdown_item_label column, fill in the column  
    for the dropdown item value  
    53 note_field_label Enter labeling field note  
    54 name_field_placeholder Enter labeling placeholder for field name  
    55 company_field_placehold Enter a labeling placeholder for the company  
    er  
    name field.  
    56 email_field_placeholder Enter labeling placeholder for email field  
    57 phone_field_placeholder Enter a labeling placeholder for the phone  
    number field.  
    58 inquiry_field_placeholder Enter labeling placeholder for inquiry topic field  
    59 note_field_placeholder Enter labeling placeholder for note field  
    60 success_message Enter a success alert when the user successfully  
    submits the form.  
    61 error_message Enter an error alert message when the user  
    submits and fills in the form incorrectly.
  </Accordion>

  <Accordion title="1.2.1.9.10. Create Setup Innovation Detail">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create Setup Innovation Detail feature in the Page module is used to create an  
    Innovation Detail page, which is also part of the Innovation page on the front page. This  
    setup is used to organize the content of the Innovation Detail front page of the Tempe Park  
    website using the Page Builder mechanism. Through this feature, administrators can  
    manage Innovation Detail content such as managing content such as detailed content,  
    sections explaining operating hours, and sections related to attractions.  
    Here is the main view of Create Setup Innovation Detail:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been inputted (published). The form  
    on this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Innovation Detail  
    11 innovation To display this component, the user must click  
    "Add a component to blocks" in step number 7,  
    after clicking this button, this component will  
    appear, click  
    12 Innovation Detail Click on this component in the innovation group  
    to set up the static content of the innovation  
    detail page.  
    13 select_variant_label Enter or name the labeling on the select variant  
    on the product detail page.  
    14 choose_size_label Enter or name the labeling in the choose size  
    section on the product details page.  
    15 available_on_label Enter or name the labeling section in the section  
    available on.
  </Accordion>

  <Accordion title="1.2.1.9.11. Create Setup About Us">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup About Us feature in the Page module allows you to  
    create a new About Us page and structure the content of the Tempe Park website's About  
    Us front page using the Page Builder. This feature allows administrators to add various  
    sections or components to the About Us page, such as a hero section, foundation section,  
    vision & mission section, and Advisor section.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup About Us:  
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been inputted (published). The form  
    on this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation  
    17 page_title Enter page title  
    Foundation Section  
    18 Image Content Click on this component to add foundation  
    section content to this page.  
    19 eyebrow Enter the section name  
    20 heading Enter section title  
    21 description Enter section description  
    22 Image Enter image section  
    23 Image position Select image position in the related section  
    24 Overlay_image Enter or upload an overlay image in the relevant  
    section.  
    25 thumbnail Insert video thumbnail  
    26 Video Enter or upload video  
    Vision Section  
    27 about Click this component group to display the About  
    Us Vision component.  
    28 About Us Vision Click this component to bring up the fields  
    required to fill in the vision section.  
    29 description Enter section description  
    30 background_image Enter background image section  
    31 person_image Enter a person or photo of a person for this  
    section.  
    32 eyebrow Enter the section name  
    Mission Section  
    34 description Enter section description  
    35 background_image Enter background image section  
    36 person_image Enter a picture of a person or people for this  
    section  
    37 eyebrow Enter the name of this section
  </Accordion>

  <Accordion title="1.2.1.9.12. Create Setup Career">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Career feature in the Page module allows you to  
    create a new Career page and structure the content of the Tempe Park website's Career  
    front page using the Page Builder. This feature allows administrators to add various sections  
    or components to the Career page, such as a hero section, a Search & Filter section, and a  
    List of Job Openings section.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup Career:  
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation.  
    17 page_title Enter page title  
    Career List Section  
    18 career Go back to the component group and select this  
    component to display the career list component.  
    19 Career List Click this component to display the fields needed  
    to add content to the career list section.  
    20 search_placeholder Enter a placeholder for the search field  
    21 job_level_label Enter the Job Level dropdown column labeling  
    22 job_type_label Enter the labeling for the Job Type dropdown  
    column.  
    23 location_label Enter the label in the Location dropdown column.  
    24 see_detail_label Enter the labeling button SEE DETAIL on the job  
    list  
    25 apply_label Enter the APPLY button labeling on the job list  
    26 all_level_label Enter the labeling dropdown filter option All  
    Level  
    27 all_type_label Enter the labeling dropdown filter option All  
    Type  
    28 all_location_label Enter the labeling dropdown filter option All  
    locations  
    29 closing_data_label Enter a label if the description "job vacancy  
    closes" is closed  
    30 loading_label Enter the labeling information that the job list  
    data is loading when the web browser page is  
    refreshed.  
    31 showing_label Enter the label description "Showing" data. The  
    label will appear as the word "Showing" in the  
    sentence Showing {banyaknya_data} jobs, when  
    the user successfully searches the job list.  
    32 job_label Enter the labeling description "job. The labeling  
    will appear as the word "job" in the sentence  
    Showing {banyaknya_data} jobs, when the user is  
    unable to find a job on the career page  
    33 jobs_label Enter the label description "jobs". The label will  
    appear as the word "jobs" in the sentence  
    Showing {many_data} jobs, when the user  
    successfully searches for a job on the career  
    page.  
    34 not_found_label Data labeling input is not found when users  
    search for jobs based on keywords and filters.  
    35 not_found_description Data labeling input is missing when users search  
    for jobs using keywords and filters. Figma says,  
    "Please check your spelling or try different  
    keywords."  
    36 not_found_image Input or upload image on data not found  
    37 To Top Button Go back to the component group to click this  
    component.  
    38 career_variant Select FALSE if the page is not a career page,  
    select TRUE otherwise.  
    39 scroll_label Enter the word "scroll" to bring up the scroll label  
    for scroll up.  
    40 up_label Enter the word "up" to bring up the scroll label  
    for scroll up.  
    41 icon Enter or upload an icon for the scroll up icon
  </Accordion>

  <Accordion title="1.2.1.9.13. Create Setup Career Detail">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create Setup Career Detail feature in the Page module is used to create a Career Detail  
    page, which is also part of the Career page on the front page. This setup is used to organize  
    the content of the Tempe Park website's Career Detail front page, which uses the Page  
    Builder mechanism. Through this feature, administrators can manage Career Detail content,  
    such as job descriptions, key responsibilities, and benefits.  
    Here is the main view of Create Setup Career Detail:  
    
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Plan Your Visit page.)  
    Hero Section  
    11 Career After the previous user clicks "Add a component  
    to blocks", the next user must click on this  
    component group to display the Career Detail  
    component.  
    12 Career Detail Click this component to display the fields  
    required to fill in the static content of the career  
    details.  
    13 back_label Enter the back label (return to the previous page)  
    in the Breadcrumb Navigation on the career  
    detail page.  
    14 share_label Enter share labeling on the career detail page  
    15 job_description_label Enter the title labeling in the job description on  
    the career detail page.  
    16 requirement_heading Enter the title labeling in the requirement  
    description on the career detail page.  
    17 career_label Enter career labeling after back navigation on  
    Breadcrumb Navigation on career detail page  
    18 apply_label Enter the labeling of the apply CTA button on  
    the career detail page.  
    19 responsibilities_heading Enter the title labeling in the responsibilities  
    description on the career detail page.  
    20 perks_benefits_heading Enter the title labeling in the Benefit description  
    on the career detail page.  
    21 To Top Button Go back to the component group and click the  
    shared component group, then click the To Top  
    Button component to display the fields needed  
    to add content to the top button on this career  
    detail page.  
    22 career_variant Select FALSE if the page is not a career page,  
    select TRUE otherwise.  
    23 scroll_label Enter the word "scroll" to bring up the scroll label  
    for scroll up.  
    24 up_label Enter the word "up" to bring up the scroll label  
    for scroll up.  
    25 icon Enter or upload an icon for the scroll up icon
  </Accordion>

  <Accordion title="1.2.1.9.14. Create Setup Contact Us">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup Contact Us feature in the Page module is used to  
    create a new Contact Us page and structure the content of the Tempe Park website's  
    Contact Us front page using the Page Builder mechanism. This feature allows administrators  
    to add various sections or components to the Contact Us page, such as the Let's Connect  
    section.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup Contact Us:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the Contact Us page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation.  
    17 page_title Enter page title  
    Let's Connect Section  
    18 Contact Return to the Contact component group to  
    display the Contact Us component.  
    19 Contact Us Click this component to display the fields  
    required to add content to the Let's Connect  
    section on the Contact Us page.  
    20 eyebrow Enter the section name  
    21 heading Enter section title  
    22 image Upload an image for this section  
    23 name_label Enter the name column labeling in the form  
    24 email_label Enter the email column labeling on the form  
    25 phone_label Enter the phone column labeling on the form  
    26 topics_label Enter the labeling of the topics column in the  
    form  
    27 notes_label Enter the note column labeling on the form  
    28 name_placeholder Enter the name column placeholder in the form  
    29 email_placeholder Enter the email column placeholder in the form  
    30 phone_placeholder Enter the phone column placeholder in the form  
    31 topics_placeholder Enter the topics column placeholder in the form  
    32 notes_placeholder Enter the notes column placeholder in the form  
    33 cta_label Enter the submit button labeling on the form  
    34 success_message Enter the desired alert message, this message will  
    appear if the visitor successfully fills in the form  
    and submits it.  
    35 error_message Enter an error message when a visitor fills in the  
    form incorrectly.
  </Accordion>

  <Accordion title="1.2.1.9.15. Create Setup FAQ">

    <Tip>
      Use **Save button** to keep content as Draft, or **Publish** when the data is ready to appear on the website frontpage.
    </Tip>

    The Create New Entry or Create Setup FAQ in the Page module is used to create a new  
    FAQ page and structure the content of the Tempe Park website's FAQ front page using the  
    Page Builder mechanism. This feature allows administrators to add various sections or  
    components to the FAQ page, such as the FAQ section.  
    Administrators can also organize the content, section order, and page layout so that the  
    information displayed on the website's front page can be arranged in a more attractive,  
    dynamic, and easy-to-understand manner for visitors.  
    Here is the main view of Create Setup FAQ:  
    **No Sub Elements Function**  
    **No**  
    1 Tab Draft Use this form tab when the user wants to add  
    (editable form) new data entry  
    2 Tab Published Use this form tab if the user wants to see the  
    data that has been input (published), the form on  
    this tab is read only and cannot be edited.  
    3 title Enter the title or page title  
    4 slug Enter the page slug.  
    5 this Column to fill in seo grouping to fill in seo page.  
    6 No entry yet. Click to add Click the (+) button to display the SEO input  
    one.  
    column. After clicking, the metaTitle,  
    metaDescription, and shareImage columns will  
    appear. Fill them in according to the page you  
    want to add.  
    7 Add a component to Use or click this button to add the component  
    blocks  
    blocks needed to structure the cms content on a  
    page.  
    8 Publish Use this button if the user wants to directly  
    publish (implement it on the website landing  
    page) the data that will be entered into the  
    system. Data that has been published in the  
    collection can also be used as a relationship to  
    data from other modules.  
    9 Save button Use this button if the user wants to save new  
    data that will be entered into the system. The  
    saved data will have a Draft status, not a  
    Published one.  
    10 Multilingual Button Use this button if the user wants to switch  
    languages. The data displayed will be based on  
    the multilingual data entered. Available languages  
    are English, Indonesian, and Chinese.  
    To complete the content using this page builder module, follow these steps. (In this case, it's  
    the FAQ page.)  
    Hero Section  
    11 Shared A grouping of content components typically used  
    on all pages, or common components commonly  
    used to structure content on a page. Click this  
    button to drop down or display a collection of  
    common content components.  
    12 Page Header In the components group, click the Page Header  
    component to add a header or hero section to  
    this page.  
    13 Page Header After clicking on the Page Header, it will appear  
    like this, the details of the fields that need to be  
    filled in to fill in the hero section.  
    14 background_image Image field used to store hero section images  
    15 (+) Click to add an asset Click this button to upload an image to be  
    or drag and drop one in  
    applied as the hero section image.  
    this area  
    16 navigation_tabs Slide to true if this page has tabbed navigation  
    17 page_title Enter page title  
    FAQ Section  
    18 FAQ Accordion Go back to the component group for shared to  
    click and select this component, this component  
    is used to display the fields required by the FAQ  
    page builder.  
    19 source_type After clicking FAQ Accordion, the following field  
    will appear, select faq, because the data that will  
    be displayed on this page comes from the FAQ  
    collection type.
  </Accordion>

</AccordionGroup>

## Screenshots

<Frame>
  ![Page menu](/images/collection-types/page-module-menu.png)
</Frame>

<Frame>
  ![Create Setup Homepage](/images/collection-types/page-module-create-setup-homepage.png)
</Frame>

<Frame>
  ![Create Setup Plan Your Visit](/images/collection-types/page-module-create-setup-plan-your-visit.png)
</Frame>

<Frame>
  ![Create Setup Experience](/images/collection-types/page-module-create-setup-experience.png)
</Frame>

<Frame>
  ![Create Setup Experience Detail](/images/collection-types/page-module-create-setup-experience-detail.png)
</Frame>

<Frame>
  ![Create Setup Education](/images/collection-types/page-module-create-setup-education.png)
</Frame>

<Frame>
  ![Create Setup Education Detail](/images/collection-types/page-module-create-setup-education-detail.png)
</Frame>

<Frame>
  ![Create Setup News](/images/collection-types/page-module-create-setup-news.png)
</Frame>

<Frame>
  ![Create Setup News Detail](/images/collection-types/page-module-create-setup-news-detail.png)
</Frame>

<Frame>
  ![Create Setup Innovation](/images/collection-types/page-module-create-setup-innovation.png)
</Frame>

<Frame>
  ![Create Setup Innovation Detail](/images/collection-types/page-module-create-setup-innovation-detail.png)
</Frame>

<Frame>
  ![Create Setup About Us](/images/collection-types/page-module-create-setup-about-us.png)
</Frame>

<Frame>
  ![Create Setup Career](/images/collection-types/page-module-create-setup-career.png)
</Frame>

<Frame>
  ![Create Setup Career Detail](/images/collection-types/page-module-create-setup-career-detail.png)
</Frame>

<Frame>
  ![Create Setup Contact Us](/images/collection-types/page-module-create-setup-contact-us.png)
</Frame>

<Frame>
  ![Create Setup FAQ](/images/collection-types/page-module-create-setup-faq.png)
</Frame>
