# LAB-WIN-005 – Manual Windows Enrollment
 
## Objective
 
Enroll an existing Windows device into Microsoft Intune using a work account.
 
This method is commonly used for devices that were not provisioned using Windows Autopilot.
 
---
 
## Navigation Path
 
Windows Device  
Settings → Accounts → Access Work or School
 
---
 
## Step-by-Step
 
1. On a Windows device open:
 
Settings → Accounts
 
2. Select **Access Work or School**
 
3. Click **Connect**
 
4. Enter corporate email address
 
5. Complete authentication
 
6. Device will automatically enroll into Microsoft Intune
 
---
 
## Captured Screenshots
 
Save in `/screenshots`
 
- Access Work or School enrollment screen
- Intune device record in portal
 
---
 
## Common Issues
 
Missing Intune license
 
Result  
Enrollment fails.
 
MDM authority not configured
 
Result  
Device joins Entra ID but not Intune.
 
---
 
## Exam Relevance
 
Manual enrollment is a **core Windows device enrollment method tested in MD-102**.
 
---
 
## Real-World Usage
 
Used for:
 
- Existing corporate devices
- BYOD scenarios
- Devices not provisioned via Autopilot
