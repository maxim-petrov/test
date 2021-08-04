![Supported DevExpress Version](https://img.shields.io/badge/Supported_Versions-17.1.3--latest-57AD0A?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAACbSURBVHgBnZINDYMwEIWPZAImAQmTMBQNCTiYhM0JoAAcVAIo6OMdOUjDX1pe8qVp2q+9Sy4D4EQkl7S4jCIkPcMj8mJPWlsbMgrO40hFnoutxemevI/Eej7YX/7YmcaH4kDKsD7uX+R/8PgqdiQPBP3hi/PM4m/pw8oqrD9cipteSsTFh1KF+Pg70ioWSI/Xkbszq9CRg5ESNwFUT8NXxYB0CAAAAABJRU5ErkJggg==)
![View this example in Support Center](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAACbSURBVHgBnZINDYMwEIWPZAImAQmTMBQNCTiYhM0JoAAcVAIo6OMdOUjDX1pe8qVp2q+9Sy4D4EQkl7S4jCIkPcMj8mJPWlsbMgrO40hFnoutxemevI/Eej7YX/7YmcaH4kDKsD7uX+R/8PgqdiQPBP3hi/PM4m/pw8oqrD9cipteSsTFh1KF+Pg70ioWSI/Xkbszq9CRg5ESNwFUT8NXxYB0CAAAAABJRU5ErkJggg==)
![How to use DevExpress Example](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)

# Dashboard for Blazor - How to implement multi-tenant Dashboard architecture by using the ASP.NET Core's Identity authentication system
This example shows how to configure the Dashboard control so that it works in the multi-user environment.

You can identify a user in the ASP.NET Core's HttpContext.User and return the following user-specific content:

## Dashboards
Custom dashboard storage allows you to specify which dashboards the user can access, edit, and save.

**API:** IEditableDashboardStorage Interface

**Files to look at:** CustomDashboardStorage.cs

## Data Sources
Custom data source storage allows you to specify which data sources are available to the user.

**API:** IDataSourceStorage Interface

**Files to look at:** CustomDataSourceStorage.cs
