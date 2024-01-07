---
layout: default
title: "Doc Library - Notes & Web Template"
nav_order: 1
description: "Doc Library - Notes & Web Template"
has_children: false
---
<h1>Doc Library - Notes & Web Template</h1>
A Document Library application is an electronic filing cabinet that stores reference documents for access by a workgroup.  The database might contain anything from environmental impact statements for a group of engineers to financial statements for a group of loan officers.

<details close markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

![Screenshot RSS Feed Generator](assets/images/png/screenshot.png)

## Info

Property | Value
---|---
Filename | doclbw7_EN.ntf
Templatename | StdR7WebDocLib
Template version | 9.0.1
Signed by | Open Source Template/Domino Development
Optimized for | Notes Client & Web

## What does this database do?
A Document Library application is an electronic filing cabinet that stores reference documents for access by a workgroup.  The database might contain anything from environmental impact statements for a group of engineers to financial statements for a group of loan officers.

## Who will use this database?
Anyone who wishes to create a record of a document or review available documents may use this database.

## Features
- Web or Notes client: Database can be accessed from either a Web browser or a Notes Client.
- Review Cycle: Used to route a document to a series of recipients.
- Document Archiving: Used to move expired documents to an archive database.
- 
### Document Review Cycle:
The author of a document has the option of setting up a document review cycle for that document. To do so fill in the reviewers, select  review cycle options and click Submit for Review button.   
Note:  Do not use @Domain when entering reviewer names.  Any domain added may prevent the reviewer from receiving mail notifications.  Also, only enter Person-names as approvers.  Group names are not supported.

### Processing Late Reviews:
If the Process Late Reviews agent is enabled, it selects those documents which are in review and have due dates which have passed.  Based on the time limit options chosen by the originator, it then either moves it along to the next reviewer, marks it as complete, or notifies the current reviewer that the review is overdue.

### Archiving

Notes users only:  To set up Archiving for the Document Library, click the Archive button on the second tab of the File-Database-Properties infobox.  Fill out the information and click the OK button.  Set up the Archiving task to run on the server.  An archive database will be set up automatically.

### Marking documents as "Expired"  
The Archive feature can act upon documents that have been marked as Expired.  
Notes users:  Select a document in the view and choose Mark/Unmark Expired from the Actions menu.
Web browser users:  Put the document into edit mode by clicking the Edit Document hotspot.  Then click the Mark/Unmark Expired hotspot at the top of the document.  

### Deleting Documents on the Web

You can now delete documents on the web while at the view level.  Click the document once to 'highlight' it and click the "Move to Trash" button.  A trash can icon will appear next to the document.  To remove the document permanently from the database, click the "Empty Trash" button.


## Suggestions for Modifications
Full text search: If you wish to use Notes' full text search capabilities for a database created with this template, select menu File, Database, Properties, go to the Full Text panel and then select Create Index... to create the full text index.

## Access Control
This application was designed with the intention that all users, except the manager, should have Author access.  If they have editor access, the review cycle may not function correctly.  Anonymous access is not permitted.

**Very Important**:  Access level should be Author for all users of this database.  This will prevent unauthorized editing of documents within the database.  The Author fields within the forms govern who will be able to edit/review particular documents.   Errors will occur if someone with Editor access attempts to review a document when they are not an authorized reviewer of that document.  For those accessing the database from a Web browser, the database does not accept Anonymous users.

