### **About**
Get Intune Assignments is a C#.NET free app built for Intune that queries Intune and Entra ID via MS Graph.
This app aims to retrieve all active Intune item assignments.
The focus is to retrieve Assignments, so if you have an item (policy, settings, app) but it does not have an assignment, 
GIA will not report it.
You can also export the data to a CSV file if desired.
Please send me any comments you would like. This can help me fix bugs and create better solutions to help everyone.

### **Copyrights Warranty and Support**
This application is completely **free**. I created it for personal needs and my work needs, as it was extremely useful, I 
decided to share it with the community.
I created this app in my spare time which I don't have much of, like most people, so I can't provide support or 
guarantee that the app will work as expected in your environment. 
I'm just trying to do my part in the world.
You don't need to use this app; you don't need to be rude to me because you don't know me and don't trust me or 
think the app is malicious. Like I said: you have no obligation to use the app. If you want to give it a try, I hope it can 
be helpful to you and/or your clients.
And feel free to send me feedback as it helps everyone.

### **What's New on GIA 3.0 - April 04, 2024**

Added new themes including color-blind high contrast.
Created a new settings dialog box with combos.
Created a new panel for assignment detail.
Created a new panel for details about group members.
Logs folder location changed to %temp% folder.
New icon.
New title bar with Maximize/Restore function.
Re-design window appearance
Removed the undock window function.
Show the result status of the assignment.
New information tabs for assignments, groups, devices and users.
Added Functions:
- Autopilot devices.
- Bring assignments target All Devices and All Users.
- Clear button in membership search.
- Filter assignments resulting information.
- Information about Logged on user.
- Information about Primary User for devices.
- Information from Group, devices and users.
- Member of from devices and users.
- Merged all types of devices configurations in a single assignment item.
- Status information from assignments (which are support).
- Search assignments in UpLevel groups.
- Search and retrieve information for devices and users.
- Search function for members.
- Search group by ID.
BUG Fix
- Created a clear button in the member search box.
- Fixed catalog settings missing assignments.
- Fixed columns in export csv file.
- Fixed group search limit.
- Fixed groups names on logs.
- Fixed missing status bar messages.
- Fixed tip color from Dark theme
- Hand cursor for all buttons.
- Search limit results for groups.

### **Requirements**

An User account with access to Intune and Azure Resources:\
Users must have access to read All Intune Items and query for Azure AD Groups.

To use this app you need to:\
Create/Register an Azure App to Get Intune Assignments get data from the environment.\
Follow the **READ ONLY** Rights the User and the Azure App may need:

Device.Read.All\
DeviceManagementApps.Read.All\
DeviceManagementConfiguration.Read.All\
DeviceManagementManagedDevices.Read.All\
DeviceManagementServiceConfig.Read.All\
Group.Read.All\
GroupMember.Read.All\
Policy.Read.All\
User.Read.All


### **Be Safe!**

![GIA3 0-Screen](https://github.com/sibranda/GetIntuneAssignments/assets/62342144/2dcc3ac6-75f5-4e17-8f85-a1ccf044c9f6)



Download the Latest Release 3.0 from April, 2024
https://github.com/sibranda/GetIntuneAssignments/releases/tag/v3.0

