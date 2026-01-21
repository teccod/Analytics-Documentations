# Analytics / Users / Overview.dashboard

This dashboard displays monthly newcomers activity. Monitoring is performed across all three community portals: Developer Community, Open Exchange, and Ideas Portal.

This dashboard has group of filters:
- **Date of first registration**: _The first ever user registration date on all three community portals._
- **Portals**: _All three community portals._
- **User`s country**: _The newcomer's country, as specified by the newcomer in the developer community or Open Exchange registration form (or taken from PEGA)_
- **User`s company**: _The newcomer's company, as specified by the newcomer in the developer community or Open Exchange registration form (or taken from PEGA)_
- **Last user active date**: _The date of the newcomer's last activity on one of the three community portals._
- **Last user login date**: _The last date a newcomer logged into the Developer Community or Open Exchange system._
- **Communities**: _All 6 developer communities laguages._

This dashboard has detailisation level for some widget.
- **Detailed user-action listing**: _The list consists of 8 columns (User Name, Action Type, User First Registration Date, Action Date, Action Title, Action Link, Oex User Profile, Community User Profile). Each row represents _actions_ performed by the user, so a user may appear multiple times. The **Action Name** column depends on the action type and represents the name of the action result: application name, publication title, etc. Some actions, such as Community View or App download, have no visible results, so the action name may be "No Data"._

## Widgets

### Overall Amounts

_This histogram shows (for a specified period. current month by default) the total number of newcomers (Newcomers), the number of users who are active across different portals (active newcomers), the number of users who contribute across different portals (contributors), and the number of returning users (retention)._  

#### Available Filters
- Date of first registration
- Portals
- User`s country
- User`s company
- Last user active date
- Last user login date
- Communities

#### Available Listing (Click on the bar to call the detailsation)
- Detailed user-action table

### Overall Activity 

_This histogram displays (for a specified period. current month by default) the ratio of active newcomers to total newcomers as a percentage (Active newcomers %) and the ratio of newcomers who contributed to total newcomers (Contributors %)._ 

#### Available Filters
- Date of first registration
- Portals
- User`s country
- User`s company
- Last user active date
- Last user login date
- Communities
 
### Users Info

_This table displays information about each newcomer (for a specified period. current month by default). User profile columns, such as "Community Profile," "Oex Profile," and "Ideas Profile," may be absent if the user doesn't have any of these profiles._ 

#### Available Filters
- Date of first registration
- Portals
- User`s country
- User`s company
- Last user active date
- Last user login date
- Communities

#### Available listing (Click on the any line to call the detailsation)
- Detailed user-action table

### Activity by days

_This table displays newcomer activity for the specified period (the current month by default) grouped by day. These metrics include: the number of new and total registered users (Active newcomers, Total Registered), the ratio of newcomer activity to total registered users (Active newcomers %), and the number of newcomers who contributed and their ratio to the total number of newcomers._

#### Available Filters
- Date of first registration
- Portals
- User`s country
- User`s company
- Last user active date
- Last user login date
- Communities

#### Available listing (Click on the any line to call the detailsation)
- Detailed user-action table
