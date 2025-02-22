---
title: "Component / Release"
linkTitle: "Component / Release"
weight: 10
---

## Add a component and release with vendor present

Step | Action | Result
---:|:-----|:----
1 | Sign In with a known user | User successfully signed in and _Home_ page is displayed
2 | Click on _Components_ tab | _Components_ page is displayed
3 | Click _Add Component_ | _New Component_ page is displayed with mandatory fields marked with red star
4 | Fill in a component _Name_ and _Categories_ and click _Add Component_ | The page remain the same and the message _You are editing the original document._ is displayed
5 | Click _Add Release_	| The page changes to _New Release Edit_ page
6 | Fill in a release _Version_ and _CPE ID_ | Values are entered in the fields
7 | Click _Add Release_	| The page remain the same and the message _You are editing the original document._ is displayed
8 | Click _Vendor_ field | _Search Vendor_ dialog is displayed
9 | _Search_ for a Vendor, select it and click _Select_ | Dialog is closed and selected Vendor is added under _Vendor_ field
10 | Click on _Attachments_ link | _Attachments_ page is displayed
11 | Click on _Add Attachment_ | _Upload Attachment_ dialog is displayed
12 | Click _Browse_ and select the attachment | File name is displayed in the dialog
13 | Click _Upload_ button | The file is uploaded and dialog is closed. Also the attached file is listed in the _Attachment_ page
14 | Change the _Attachment type_ to real type, e.g. _Source file_ if it is a source file | Type changed successfully
15 | Click _Update Release_ | _Release updated successfully!_ message is displayed
16 | Click on _Components_ tab | The new component should be added to the components list (e.g. filter by _Keyword Search_)

## Modify a component and release with vendor present

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component (e.g. created in TC01) and click _Edit_ | _You are editing the original document_ message is displayed  
2 | Execute steps 5-16 from TC01

## Add and modify a component and release with all fields filled in

Step | Action | Result
---:|:-----|:----
1 | Click on _Components_ tab | _Components_ page is displayed
2 | Click _Add Component_ | _New Component_ page is displayed with mandatory fields marked with red star
3 | Fill in all editable fields under _Basic Information_ | Values are entered in the fields 
4 | Click _Add Component_ | The page remain the same and the message _You are editing the original document._ is displayed
5 | Click _Add Release_	| The page changes to _New Release Edit_ page
6 | Fill in all editable fields under _Release Summary_ and _Release Repository_ | Values are entered in the fields
7 | Click _Add Release_	| The page remain the same and the message _You are editing the original document._ is displayed
8 | Click on _Linked Releases_ link | _Linked Releases_ page displayed successfully
9 | _Click to add Releases_ | _Search Release_ dialog is displayed
10 | Click _Search by name_ and _Select_ a release to be added | Dialog is closed and selected release is displayed under _Linked Releases_ section
11 | Click on _Clearing Details_ link | _Clearing Details_ dialog is displayed
12 | Fill in all editable fields | Values are entered in the fields
13 | Click on _Attachments_ link and upload a file | File attached successfully
14 | Click _Update Release_ | _Release updated successfully!_ message is displayed
15 | Check all fields of the release under _Summary_, _Linked Releases_, _Clearing Details_ and _Attachments_ | Values are filled in correctly
16 | Click _Edit_ button, modify some fields and _Update Release_ | Values are updated successfully

## Delete a component that is first linked to a project and then not, and a project

Step | Action | Result
---:|:-----|:----
1 | Create a new component | Component is created successfully
2 | Add a new release to this component | Release is added successfully
3 | Create a new project | Project is created successfully
4 | Add the linked release created above to this project | Release linked successfully
5 | Go to components, try to delete the newly created component (that is linked to a project) | Message _I could not delete the component!_ is displayed. 
6 | Click _OK_ | Component is not deleted
7 | Go to Projects, delete the newly created project | Project is deleted successfully
8 | Go to components, delete the newly created components (not linked anymore to a project) | Message _Do you want to delete component?_ is displayed
9 | Click _OK_ | Component is deleted successfully

## Add new attachments to an existing release and delete attachments

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component (e.g. created in TC01) and click _Release Overview_ | The list of releases are displayed
2 | Click on release version that needs a new attachment | _Release Summary: name_ page is displayed for the selected release
3 | Click on _Edit_ | _You are editing the original document._ message is displayed
4 | Click on _Attachments_ link | _Attachments_ page is displayed
5 | Click on _Add Attachment_ | _Upload Attachment_ dialog is displayed
6 | Click _Browse_ and select several attachments | File names are displayed in the dialog
7 | Click _Cancel_ near some files not to be added | File names are removed from the list
8 | Click _Upload_ button for the remaining files | The files are uploaded and dialog is closed. Also the attached file are listed in the _Attachment_ page
9 | Change some _Attachment type_ to real type, e.g. _Source file_ if it is a source file | Type changed successfully
10 | Click _Update Release_ | _Release updated successfully!_ message is displayed
11 | Click on _Edit_ | _You are editing the original document._ message is displayed
12 | Click on _Attachments_ link | _Attachments_ page is displayed
13 | Click on _Delete_ icon to delete an attachment | Message _Do you really want to delete this attachment?_ is displayed
14 | Click _OK_ | Attachment is deleted successfully
15 | Click _Update Release_ | _Release updated successfully!_ message is displayed

## Duplicate an existing release

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component with release with all fields filled in (e.g. created in TC03) and click _Release Overview_ | The list of releases are displayed
2 | Click _Duplicate_ button under Action column | The page changes to _Release name Edit_
3 | Check all fields from copied release | All fields from _Release Summary_ and _Repository_ are unchanged
4 | Change the _Version_ field to a new one, fill in a _CPE ID_ and click _Add Release_ | _You are editing the original document._ message is displayed.
5 | Modify some other fields, e.g. _Release Date_ and click _Clearing Details_ | _Clearing Details_ page is displayed and does not contain any field from copied release
6 | Click _Update Release_ | _Release Component updated successfully!_ message is displayed
7 | Click on component name link on top of the page | Summary page for the component is displayed
8 | Click on _Release Overview | The new copied release is listed among previous releases

## Search for and create a new vendor for a new release

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component and click _Edit_ | _You are editing the original document_ message is displayed
2 | Click _Add Release_	| The page changes to _New Release Edit_ page
3 | Fill in a release _Version_ and _CPE ID_ | Values are entered in the fields
4 | Click _Vendor_ field | _Search Vendor_ dialog is displayed
5 | Click _Add New Vendor_ | _Create New Vendor_ dialog is displayed
6 | Fill in _Full name_, _Short name_ and _URL_ | Values are entered in the fields
7 | Click _Add Vendor_ | Dialog closes and the new vendor is displayed in release _Vendor_ field
8 | Click _Add Release_	| The page remain the same and the message _You are editing the original document._ is displayed
9 | Click on component name link on top of the page | Summary page for the component is displayed. The new vendor for the new release, as well as existing vendors from previous releases are listed under _Vendors_ field for the component

## Link a release to the project in view component page and check used by projects

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component with release and click _Release Overview_ tab | The list of releases are displayed
2 | Click _Link Project_ button under Action column | The dialog _Link Release to Project_ is displayed with _Link to Project_ button is disabled
3 | Click on _Search_ button then choose a project to link | _Link to Project_ button on the dialog is enabled
4 | Click on __Link to Project_ button | _The release {component name} ({version}) has been successfully linked to project {project name}_<br>_Click <ins>here<ins>_ _to edit the release relation as well as the project mainline state in the project._ message is displayed
5 | Click on _here_ hyperlink in the dialog | Redirect to the _edit project_ page with the release was linked (displayed on  _License Clearing_ page)
6 | Re-open the release at view page and click on _Summary_ tab | Used by project information is updated correspondingly

## Link a release to a project in the view release page

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component with release and click _Release Overview_ tab | The list of releases are displayed
2 | Click on _a release name_ hyperlink. Eg: release R1 | Redirect to the _view release_ page
3 | Click on _Link to Project_ button | The dialog _Link Release to Project_ is displayed with _Link to Project_ button is disabled
4 | Click on _Search_ button then choose a project to link | _Link to Project_ button on the dialog is enabled
5 | Click on __Link to Project_ button | _The release {component name} ({version}) has been successfully linked to project {project name}_<br>_Click <ins>here<ins>_ _to edit the release relation as well as the project mainline state in the project._ message is displayed
6 | Click on _here_ hyperlink in the dialog | Redirect to the _edit project_ page with the release was linked (displayed on  _License Clearing_ page)

## Import a new component by .spdx/.xml/ .rdf file

Step | Action | Result
---:|:-----|:----
1 | Click on _Components_ tab | _Components_ page is displayed
2 | Click on _Import SBOM_ button | A dialog _Upload SBOM_ is displayed
3 | Choose a **_.spdx_** or **_.xml_** or **_.rdf_** file by clicking on the _Browse_ button or drop/draft a file into the dialog | The message is displayed in the dialog: <br> _The new Component and new Release will be created, do you want to import? <br> New Component: {new component names} <br> New Release: {new release names}_
4 | Click on _Import_ button | The dialog is closed. New releases and new components are imported successfully

## Export components without releases

Step | Action | Result
---:|:-----|:----
1 | Click on _Components_ tab | _Components_ page is displayed
2 | Click on _Export Spreadsheet_ button and choose _Components only_ option | A new file with name's format _components-{yyyy}-{mm}-{dd}.xlsx_ is downloaded<br> The content of the downloaded file includes information of all components in the system

## Export components with releases

Step | Action | Result
---:|:-----|:----
1 | Click on _Components_ tab | _Components_ page is displayed
2 | Click on _Export Spreadsheet_ button and choose _Components with releases_ option | New file with name _components-{yyyy}-{mm}-{dd}.xlsx_ is downloaded.<br> The content of the downloaded file includes information of all components and releases in the system

## Create a clearing request for a release

Step | Action | Result
---:|:-----|:----
1 | Search for an existing component with releases and click _Release Overview_ tab | The list of releases are displayed
2 | Click _Edit_ button under _Action_ column. Eg: edit release R1 | Redirect to _view release_ page and the message _Success:You are editing the original document._ is displayed
3 | Click on _Attachments_ tab, then add a source file (Eg: .rdf file) with _Type_ is _Source file_ | The data is updated correspondingly
4 | Click on _Update Release_ button | The message _Success:Release {release name} updated successfully!_ is displayed
5 | Click on _Clearing details_ tab, then click on _Possology Process_ icon beside _Clearing State_ field and wait for the process to finish | The message _The FOSSology process already finished. You should find the resulting report as attachment at this release._ is displayed in the _Fossology Process_ dialog
6 | Click on _Close_ button in the dialog | The dialog is closed
7 | Reload this page, then click on _Attachments_ tab | A new file is listed in _Attachments_ page with name's format _{component name}-{version}-{yyyymmdd}-{hhmm}-SPDX.rdf_
