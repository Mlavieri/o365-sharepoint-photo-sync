# o365-sharepoint-photo-sync
PowerShell script to sync user photos in Office 365 (Exchange to SharePoint)

TO USE:
1. Extract Temp.zip to your c:\ drive
2. Update the users.csv file with the email address of the photos you like to sync
3. Update the script variables for you organizations URL prefix on line 5
4. Run the Script

WHAT IT DOES:
- download the user's Exchange Online Photo
- create the 3 thumbnail sizes for SharePoint and upload them to the MySite Host site collection
- update the SharePoint user profile (PictureURL) with the medium thumbnail version.
