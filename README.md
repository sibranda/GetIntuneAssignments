### **About**
GIA is a C#.NET free app built for Intune that queries Intune and Entra ID via MS Graph.
Which has already reached more than 1,400 downloads!
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

### **What's New on GIA 3.1 - June 18, 2024**

ver. 3.1 – June 18, 2024
Implementation of new tabs in Device Information.
Removed status tabs from selected assignments.
Search limited to 100 results for best performance.
Added Functions:
- Retrieve Conditional Access (CA) assignments based on roles.
- Windows Updates including Rings, Quality, Features and Drivers.
BUG Fix
- CA excluded by group was not showing to user member.
- CA for all users was not working.
- Fixed error when multiple clicks in assignments list.
- Fixed error when user have assignments in uplevel groups.
- Fixed display name missing from policy sets in logs.
- Fixed filters function to filter without need to click clear button first.
- Fixed log information during the search.
- Fixed text information when selecting a user from search.

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

![GIA3 1-Screen](https://github.com/sibranda/GetIntuneAssignments/assets/62342144/fdb9d9d5-8fe0-4048-a3c4-c8c9b25ad1b3)

You can test all other themes by selecting from GIA settings:

![GIA3 1-ThemeScreen](https://github.com/sibranda/GetIntuneAssignments/assets/62342144/1925b47c-ae46-49d8-a7b1-b8c09e3ef889)


Download the Latest Release 3.1 from June, 2024
https://github.com/sibranda/GetIntuneAssignments/releases/tag/v3.1

