# LAB-WIN-003 – Enable Automatic MDM Enrollment
 
## Objective
 
Enable automatic enrollment of Windows devices into Microsoft Intune when users sign in with their work account.
 
This allows devices to be automatically managed during Azure AD Join.
 
---
 
## Navigation Path
 
Intune Admin Center  
Devices → Windows → Windows Enrollment → Automatic Enrollment
 
---
 
## Step-by-Step
 
1. Open Microsoft Intune Admin Center
2. Navigate to:
 
Devices → Windows → Windows Enrollment
 
3. Select **Automatic Enrollment**
 
4. Configure the following settings:
 
MDM User Scope → All  
MAM User Scope → None
 
5. Click **Save**
 
---
 
## Captured Screenshots
 
Capture and store in `/screenshots`
 
- Automatic Enrollment settings page
- MDM User Scope configuration
 
---
 
## Common Issues
 
MDM user scope set to **None**
 
Result  
Devices will join Entra ID but **will not enroll in Intune**
 
MAM user scope incorrectly enabled
 
Result  
Policy conflicts and confusion between MDM and MAM management
 
---
 
## Exam Relevance
 
MD-102 requires understanding of **automatic device enrollment prerequisites**.
 
---
 
## Real-World Usage
 
Automatic enrollment is required for:
 
- Azure AD Join devices
- Windows Autopilot provisioning
- Enterprise device lifecycle management
 
 
---
