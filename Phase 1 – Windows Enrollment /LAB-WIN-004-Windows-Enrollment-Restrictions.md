# LAB-WIN-004 – Windows Enrollment Restrictions
 
## Objective
 
Control which devices are allowed to enroll into Microsoft Intune.
 
Enrollment restrictions prevent unsupported or unauthorized devices from joining the management environment.
 
---
 
## Navigation Path
 
Intune Admin Center  
Devices → Windows → Windows Enrollment → Enrollment Restrictions
 
---
 
## Step-by-Step
 
1. Open Intune Admin Center
 
2. Navigate to:
 
Devices → Windows → Windows Enrollment → Enrollment Restrictions
 
3. Open **Default Device Type Restriction**
 
4. Configure allowed device platforms
 
Allow:
 
- Windows (MDM)
- Personally owned devices
- Corporate owned devices
 
5. Save the configuration
 
---
 
## Captured Screenshots 
 
Save in `/screenshots`
 
- Device platform restriction page
- Device type restriction configuration
 
---
 
## Common Issues
 
Windows platform accidentally blocked
 
Result  
Windows devices cannot enroll.
 
Personally owned devices blocked
 
Result  
BYOD enrollment fails.
 
---
 
## Exam Relevance
 
Enrollment restrictions are part of **MD-102 device onboarding governance**.
 
---
 
## Real-World Usage
 
Organizations use enrollment restrictions to:
 
- Block unsupported platforms
- Enforce device ownership rules
- Control corporate device onboarding
 
 
---
