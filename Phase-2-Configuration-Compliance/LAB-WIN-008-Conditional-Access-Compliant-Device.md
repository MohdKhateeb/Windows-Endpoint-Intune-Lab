# LAB-WIN-008 – Conditional Access with Device Compliance
 
## Objective
 
Use Conditional Access to restrict access to corporate applications unless the device is compliant.
 
This enforces a Zero Trust security model.
 
---
 
## Navigation Path
 
Microsoft Entra Admin Center  
Protection → Conditional Access
 
---
 
## Step-by-Step
 
1. Open **Microsoft Entra Admin Center**
 
2. Navigate to:
 
Protection → Conditional Access
 
3. Create new policy
 
4. Configure:
 
Users  
INT-WIN-Users
 
Cloud Apps  
Office 365
 
Conditions  
Device Platform = Windows
 
Grant Control  
Require device to be marked as compliant
 
5. Enable the policy.
 
---
 
## Captured Screenshots
 
Conditional Access policy configuration  
 
Grant control settings  
 
Policy assignment page
 
---
 
## Common Issues
 
Locking out administrative accounts.
 
Conditional Access targeting device groups instead of users.
 
Missing break-glass account exclusion.
 
---
 
## Exam Relevance
 
Conditional Access combined with compliance policies is a major focus area in MD-102.
 
---
 
## Real-World Usage
 
Conditional Access enforces secure access to cloud resources based on device health and compliance.
 
