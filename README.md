# TimesheetReportScript
Google Sheets script that makes a table of employee shift hours based on employee Google Calendar events.

# Usage
1. Create a new Spreadsheet in Google Drive.
</br>![Create new spreadsheet](https://github.com/alithadp/TimesheetReportScript/blob/master/Screenshots/1.png?raw=true)
2. Name the Spreadsheet something meaningful, such as "Time Sheet Report".
3. Navigate to Tools > Script Editor. This will open a new tab.
</br>![ToolsScriptEditor](https://github.com/alithadp/TimesheetReportScript/blob/master/Screenshots/2.png?raw=true)
4. In the text editor, copy and paste the code in the "script" file in this repository.
5. Click the "Save" button ![Save](https://github.com/alithadp/TimesheetReportScript/blob/master/Screenshots/Save.png?raw=true).
6. To generate the time sheet report, follow the instructions at the top of the code. Every time the script is run, the spreadsheet is cleared and the newly generated report is stored in the cleared spreadsheet.

# Notes
- Each name in the "calendars" variable should contain each staff member's shift information.
- Each phrase in the "keywords" variable should be a phrase that is present in a calendar event that should not be counted towards the staff member's shift hours.
