# Title

## Executive Summary

*The creation of a Data Export that will query a currently existing Database View and deposit that content into a worksheet of an Open Office Spreadsheet Workbook. *

## Business Objectives

*The front-end navigation needs to be similar to how other reports in the same module are generated for continuity.  
The code must be designed to maximize the ability to update the database view, without requiring changes in how the code will query the data in most cases.
The data extract needs to ignore duplicate data by selecting ONLY the most recent version of the duplicated data.*


## Background

*The clients do not have a large budget for development and would like the design allow their team to make most updates or design changes to either the database view or the spreadsheet without requiring new code be updated by a developer each time to allow quick adjustments as situations require.*

## Scope

*The development includes, designing the front end navigation and allow the user the ability to input parameters that determine the range of data that will be exported to the Open Office Workbook.*

## Functional requirements

*Front End Navigation:  The users will selection the reports module, the reports module page will have a new link below “Report Type A” and be titled “Report Type B”.  After selecting “Report Type B “, this link would lead to the data selection screen.  The data query target is the currently existing Database view “vReportTypeB”

Include All columns within the view, but WITHOUT specifically referencing the columns buy name.  Instead, querying as a “Select * “ or “Select ALL”.  This is important as the client requires the ability to update the View “vReportTypeB“ without requiring changes in how the code will query the data.	

The data entry screen is to be a copy of the “Report Type A” screen only hiding the fields 2, 3, and 4 to potentially use them later.
Selector Fields include the following.

Location:  The location drop-down is similar to “Report Type A” only requiring an additional, “Organization Wide” Selection Option for Level 2 Users. This will include all of the sites in the users organization.

Date Fields: (Start Date & End Date) – These fields function the same as “Report Type A” in terms of filtering the data however we’d like to add default values to show ALL of the data.  Starting Date default = The earliest date of the data present.  Ending Date default = Today’s Date.
 
The "Export" Report Button triggers the report generation based on the preceding field values.
The data queried based on the previously discussed fields will export to the first worksheet in the Open Office Workbook template.

Data Filters Summary in addition to the previously discussed location and date fields will be limited to the organization and permission level of the active user.  Level 2 users can “see” data from all site locations and have the option to select either an individual site, or all sites at once, while Level 1 users can only “see” data from their local site.

Report Naming Convention will vary slightly based on the type of report selected.
Level 2 Organization Wide Reports will have a naming convention as follows:
[ReportName] Report - [Organization] [firstName] [lastName] [YYYY.MM.DD][hh:mm]

Level 1 or Level 2 Single Site Only Reports will have a naming convention as follows:
[ReportName] Report - [Local Site Name] [firstName] [lastName] [YYYY.MM.DD][hh:mm]
*


## Personnel requirements

*This development work will require close communication and collaboration between our coding developer and their Data Science Specialist to make sure the code is interacting with the spreadsheet as desired.*

## Delivery schedule

*Phase 1 their team will determine all the data that will need to be joined into the view, which will require collaboration from multiple team members.  Due to other time commitments this will require 1 week.
Phase 2 will commence after the database view has been created and our developer will write the code to extract the data and deposit that data into the open office workbook.  We estimate an additional week of design and testing to be completed.
*

## Other requirements

*This development work needs to work seamlessly with Google Chrome and Safari, but does not need to be tuned to any other browsers at this time.*

## Assumptions

*This business requirements document assumes intimate knowledge with the front-end and back-end functioning of “Report Type A” or would otherwise require greater explanation.*

## Limitations

* These timelines are subject to change based on when the actual start date of the project based on when the initial fee and development information document is received. *

## Risks

* This project is pretty straight forward and risks are minimal both in terms of time and finances.* 
