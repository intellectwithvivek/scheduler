# scheduler
To Run this Project
Clone this repository
npm install
gulp build
gulp bundle --ship
gulp package-solution --ship
Summary
This Web Part allows you to manage events in a calendar. Uses a list of existing calendars on any website. The location and name of the list and the dates of the events to be displayed are defined in the properties of the web part.

Each category has its own color that is generated in the load.

The Web Part checks the user's permissions for the View, Add, Edit, and Delete events.

Compatibility
SPFx 1.10.0 Compatible with SharePoint Online "SharePoint Server 2019 requires SPFx 1.4.1 or lower" Does not work with SharePoint 2016 "SharePoint Server 2016 Feature Pack 2 requires SPFx 1.1" Local Workbench Incompatible "The solution requires access to SharePoint content" Only Hosted Workbench Compatible

Applies to
SharePoint Framework
Office 365 tenant
Solution
The Web Part Use PnPjs library, Office-ui-fabric-react components. react Big-Calendar Component
