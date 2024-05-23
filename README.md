# automate-tasks

FileName: Automate Emailing Users When Document is Added

Purpose: Emails those w/ access (viewers + editors) to google folder when a document is added to that folder 

Instructions: 

_Replace Placeholder_
- Ensure correct folder ids being used 

_Services_
- Go to services tab (left menu) and press the plus sign
- scroll to **Drive API** and select it to Add it

_Set Up Trigger_
- Go to 'Triggers' section in the Google Apps Script editor (left hand menu w/ timer symbol) 
- Click on 'Add Trigger'
- Set up trigger for the 'checkNewFiles' function to run every hour (or every minute depending what you prefer)
- Also set notify me to hourly as well to know when executions fail 

  _Authorizations_
  - When prompted, authorize the script.
  - If the OAuth consent screen displays the warning, This app isn't verified, continue by selecting Advanced > Go to {Project Name} (unsafe).
