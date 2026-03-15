# LAB-WIN-011 — BitLocker Encryption Policy
 
## Objective
 
Encrypt Windows devices using BitLocker and store recovery keys securely in Microsoft Entra ID.
 
---
 
## Navigation Path
 
Intune Admin Center  
Endpoint security → Disk encryption
 
---
 
## Step-by-Step
 
1. Open Intune Admin Center
 
2. Navigate to:
 
Endpoint security → Disk encryption
 
3. Click **Create Policy**
 
4. Configure:
 
Platform  
Windows 10 and later
 
Profile  
BitLocker
 
5. Configure settings:
 
Enable BitLocker  
Encrypt operating system drives  
Store recovery key in Entra ID
 
6. Assign to:
 
INT-WIN-Enrolled-Devices
 
---
 
## Captured Screenshots
 
BitLocker policy configuration  
Device encryption status  
Recovery key stored in Entra ID
 
---
 
## Common Issues
 
Device does not support TPM 2.0.
 
Encryption stuck due to existing BitLocker configuration.
 
---
 
## Exam Relevance
 
BitLocker management through Intune is a common MD-102 exam topic.
 
---
 
## Real-World Usage
 
Organizations use BitLocker to protect corporate data in case of device loss or theft.
 
 
