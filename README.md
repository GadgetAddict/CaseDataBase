# CaseDataBase
AppleScript Based Application  :

This repository contains versions of Case DataBase, an app that consists of dialog boxes and prompts that create, edit and share entries in a DataBase.

#### Use Case
Instead of writing down sensitive case numbers or customer identification, enter those details in Case DataBase and quickly access information, share information with password protection and create event reminders to check on a case.
+ Add/ Edit / Delete / Export  records based on certain criteria
+ Email a report of cases and their details to a peer 
+ Change the status of each case to Closed when case is resolved. This removes the case from the list of "active" cases
+ Easily Delete all cases with a status of "Closed" 

#### Reminders 
Create Calendar events with alarms to remind you to check an account. The notes in the event will have a Link to open the account.   This uses URL handling and account details embedded in the link

#### Speed
+ Use 10 Key to navigate all prompts.
+ Use Keyboard Shortcuts to Launch the App

+ Download FastScripts by RedSweater to assign a keyboard shortcut to anything you want.  
Set up a keyboard shortcut to Launch Case DataBase to quickly open the app and update your case details and notes.

#### Inner Workings

+ Initialize - Check that all required resources are installed
   * Is Numbers installed
   * Download and Install satimage.osax - This gives applescript REGEX support 
   * Create script file within application package/ Resources to save Email address of your assigned buddy
   * Create the Database and save it
