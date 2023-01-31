# WesTech_Rounds_App
A cross platform application built using Flutter. Made as a practice project to learn Flutter and replace the PowerApps rounds app. This app allows a user to login and choose the site location as well as the type of round being done. 

This app was built for the needs of 1 site but should be expanded to work for all sites. In the app *Operators* can either submit their rounds data or their lab data. This data should be sent to a database to store and provide a seperate data visualization software.

## Essential TODO:
1. Create a dictionary to store normal value limits/recomendations.
2. Create a list to store variables data for data transfer/manipulation. (Most likely store as json)
    1. Create and store list in 'roundsVariableData.json' file.
    2. Create and store list in 'labsVariableData.json' file.
3. Use Lab variables to calculate Total Suspended Solids (TSS) then store in a labsVariable.
4. Create User dictionary to store: 
    1. EmpID:
    2. Name:
    3. Email:
    4. Password:
    5. Primary Location:
    6. Job Title:
    7. Security Level: 'basic' (DEFAULT) (Others: 'Supv.', 'Mgmt.','Admin')
 5. Connect app to database.
 
 ## Future TODO:
 1. Create SiteLocation class for site specific data. (rounds/labsVariables, normal value limits/recomendations)
 2. Default location points to users primary location.
 3. Create local storage to save data while offline.
    1. Send data to database once reconnected to internet.
 4. Create page to review siteLocation previous data submitions. (previous rounds and lab data)
    1. Allow option to edit that is restrigted by permissions.
    2. Create version history.
