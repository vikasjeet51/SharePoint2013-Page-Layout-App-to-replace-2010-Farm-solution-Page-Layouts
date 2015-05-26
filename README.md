# SharePoint2013-Page-Layout-App-to-replace-2010-Farm-solution-Page-Layouts

This App is developed to provision page Layouts in the same way how it was provisioned in the SharePoint 2010 farm solution.
App creates the site columns with a fixed GUID and it has some Managed site columns as well, which is mapped with central admin Manages Metadata properties.
App creates Content Types which contains custom site columns and OOB SharePoint Columns.
All the page layouts are using Javascript to render language specific text and custom control on the page.
PageLayouts are hosted in Master Page gallery and corresponding JavaScript, CSS, Image files are in style library.
Normally when we upload the files to the master Page gallery, it uploads with default design document template but we have to change it to Page Layout template, then we will get to see corresponding properties to update.
Next step is to inherit the page with existing or custom defined Content Type that Pagelayout can use fields defined in the page layout.
