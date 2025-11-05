### About
### Origins: Addressing Real Need 
The GIA story began in June **2022**, when the need arose for a practical method to audit Intune assignments. Initially 
conceived as a set of PowerShell scripts, the project provided basic functionality for extracting assignment data, 
addressing a critical gap for IT professionals managing large-scale deployments. These early scripts laid the 
groundwork for automating tedious manual tasks and demonstrated the potential for a more comprehensive tool. 
Feature Expansion and Transition 
Responding to growing user needs, GIA quickly expanded beyond its original scope. New features were added to 
include compliance policies, application assignments, device configurations, and update management. Recognizing 
the limitations of command-line tools for broader adoption, development shifted in September 2022 to a graphical 
interface built in C#.NET, dramatically improving usability and enabling more sophisticated data visualization. The 
transition marked a pivotal milestone, transforming GIA from a niche script into an accessible, robust application for 
the entire community. 
### Community Impact and Collaboration 
The launch of GIA on GitHub marked the beginning of genuine community collaboration. Feedback from beta testers 
and contributors, including valuable insights from IT professionals, helped prioritize new features and guide bug fixes. 
Each release was shaped by constructive input, ensuring GIA stayed relevant and responsive to users’ evolving needs. 
The open distribution model fostered a dynamic cycle of improvement, with enhancements and refinements driven 
by real-world challenges. 
Major Releases: Building Value 
GIA’s version history reflects its commitment to continuous innovation. Version 1.5 introduced export capabilities, 
allowing users to generate CSV reports for further analysis. Version 2.0 brought expanded support for new 
assignment types and performance optimizations. With version 3.0 and 3.1, advanced filtering and reporting tools 
were added, making the application indispensable for IT teams seeking efficiency and clarity in their management 
workflows. 

### Latest Innovations: GIA 4.0 and Beyond 
The release of GIA 4.0 represents the most significant advancement to date. It introduces a groundbreaking comparison engine, allowing administrators to analyze assignment differences across policies, applications, and devices with precision. Another highly impactful feature is the ability to identify items without assignments, enabling IT teams to quickly detect orphaned or unused objects. This functionality empowers administrators to sanitize the Intune environment, improving performance, reducing clutter, and ensuring a streamlined configuration that retains only what is actively in use.

### A Commitment to Excellence 
GIA is more than a tool; it is a collaborative project shaped by the needs and feedback of a passionate community. 
The application continues to be refined and improved, embodying a commitment to delivering practical value while 
adapting to the challenges faced by modern IT environments. Users are encouraged to share comments and 
suggestions, knowing that their contributions help drive the evolution of GIA and benefit the broader professional 
community. 

### Copyrights Warranty and Support 
This application is provided **free of charge**. It was initially developed to meet both my personal and professional 
requirements, and, having found it highly effective, I have chosen to share it with the community. 
As this project was built during my limited spare time, I am unable to offer user support or ensure compatibility 
across all systems. 
Use of this application is entirely optional. I kindly request that users approach its use with civility and 
professionalism. Should you choose to try it, I hope it proves valuable for you and your clients. 
Additionally, I welcome any constructive feedback, as it benefits the broader community. 



### What's New on GIA 4.0 - October 27, 2025
Added two new themes: aqua and game. 
All internal graph and azure authentication packages were updated to improve performance 
and security. 
Created new Tab Settings for assignment information. 
Redesigned interface for better visualization. 
Added Functions: 
- Compare Mode. 
- Created new tab devices when selecting a user. 
- Created new tab hardware when selecting a device. 
- Device Information now brings all information including extension attributes. 
- Enabled multi-threading to get assignments faster. 
- New Tab Settings bring information about the item settings. 
- Retrieve Windows 365 assignments. 
- Show Unassigned items. 
- Tab Settings for proactive remediation can bring PS1 script decoded. 
- Tabs with information now, bring information about the assignment. 
- Windows 365 and Cloud PC assignments. 
Bug Fix: 
- CA role based not showing CA name. 
- Fixed export CSV was not exporting data from columns assignment and intent for applications. 
- Fixed iPhone and iPad devices don’t show configurations and compliances. 
- Fixed not showing assignment type in Update Rings. 
- Item information was reloaded every time you clicked on it. 
- Multiples of error messages when expire token. 
- Renew token if expires when leave GIA opened for long time. 
- Unable to retrieve scripts and remediation information because the new required Graph API permission. 

### Screen Shot
<img width="753" height="378" alt="image001" src="https://github.com/user-attachments/assets/5cbac7fc-0e49-448e-ae99-ee3200ae699d" />



Thank you for your trust, engagement, and support in advancing GIA. 
