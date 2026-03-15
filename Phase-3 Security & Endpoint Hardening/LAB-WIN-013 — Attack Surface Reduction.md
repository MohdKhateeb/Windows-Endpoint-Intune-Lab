# LAB-WIN-013 — Attack Surface Reduction (ASR)
 
## Objective
 
Reduce attack vectors using Attack Surface Reduction rules.
 
---
 
## Navigation Path
 
Intune Admin Center  
Endpoint security → Attack surface reduction
 
---
 
## Step-by-Step
 
1. Open Intune Admin Center
 
2. Navigate to:
 
Endpoint security → Attack surface reduction
 
3. Create new policy
 
4. Enable rules:
 
Block Office applications from creating child processes
 
Block credential stealing from LSASS
 
5. Assign to:
 
INT-WIN-Test-Devices
 
---
 
## Captured Screenshots
 
ASR rules configuration  
Policy assignment
 
---
 
## Common Issues
 
Strict ASR rules breaking legitimate applications.
 
Not testing rules in audit mode before enforcement.
 
---
 
## Exam Relevance
 
ASR rules are part of Microsoft Defender security controls.
 
---
 
## Real-World Usage
 
ASR rules protect systems from ransomware and credential theft attacks.
