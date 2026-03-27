# LAB-WIN-016 — Win32 Application Deployment
 
## Objective
 
Deploy a Win32 application using Microsoft Intune.
 
Win32 applications are packaged using the Intune Win32 Content Prep Tool and deployed to managed devices.
 
---
 
## Navigation Path
 
Intune Admin Center  
Apps → Windows → Add
 
---
 
## Step-by-Step
 
1. Prepare the application package
 
Use Microsoft Win32 Content Prep Tool to convert the installer into `.intunewin` format.
 
2. Open Intune Admin Center
 
3. Navigate to:
 
Apps → Windows → Add
 
4. Select:
 
App type → Windows app (Win32)
 
5. Upload the `.intunewin` package
 
6. Configure application information
 
- App name
- Publisher
- Version
 
7. Configure install command
 
Example:
 
setup.exe /silent
 
8. Configure detection rules
 
Example:
 
File exists  
Path: Program Files\Application
 
9. Assign application to:
 
INT-WIN-Users
 
---
 
## Captured Screenshots
 
Win32 application upload page  
Application configuration screen  
Assignment configuration
 
---
 
## Common Issues
 
Incorrect detection rules causing repeated installation.
 
Silent installation command not configured properly.
 
Incorrect file paths in detection rules.
 
---
 
## Exam Relevance
 
Win32 app deployment is one of the most tested topics in the MD-102 certification.
 
---
 
## Real-World Usage
 
Enterprises deploy internal business applications using Win32 packaging.
 
 
