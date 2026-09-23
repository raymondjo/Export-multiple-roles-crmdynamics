# Export Multiple Security Roles

An [XrmToolBox](https://www.xrmtoolbox.com/) plugin that exports Microsoft Dataverse security roles to Excel.

Select one or more security roles and save a workbook with a privileges sheet for each role. When miscellaneous privileges are included, each role also gets a miscellaneous privileges sheet.

The workbook opens on an **Index** sheet:

- The Index header stays frozen while you scroll the list of roles.
- Each row links to that role's sheet.
- Each role sheet has a frozen **Back to Index** link so you can return without scrolling the sheet tabs.

## Install

In XrmToolBox, open **Tool Library**, search for **Export Multiple Security Roles**, and install the plugin. Restart XrmToolBox after installation.

You can also install the NuGet package `ExportMultipleSecurityRoles` from the XrmToolBox plugin store.

## Export

1. Connect to a Dataverse environment.
2. Load the security roles and select the roles to export.
3. Choose whether to include miscellaneous privileges.
4. Export to Excel and choose the save location.

## Feedback

Questions and issues: [github.com/raymondjo/Export-multiple-roles-crmdynamics](https://github.com/raymondjo/Export-multiple-roles-crmdynamics)
