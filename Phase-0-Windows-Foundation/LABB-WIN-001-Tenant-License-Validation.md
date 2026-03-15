# LAB-WIN-001 – Tenant & License Validation

## Objective

Ensure tenant and licensing prerequisites are met for Windows device management using Microsoft Intune.

---

## Navigation Path

Entra Admin Center  
→ Entra ID  
→ Licenses

---

## Step-by-Step

1. Open Microsoft Entra Admin Center
2. Navigate to **Entra ID → Overview**
3. Note the following information

- Tenant Name
- Tenant ID

4. Go to **Licenses → All Products**
5. Confirm the following licenses exist

- Microsoft Intune
- Entra ID P1 or P2
- Windows Enterprise or Microsoft 365 E3/E5

---

## Captured Screenshots 

- Entra ID Overview page
- Licenses assigned page

See screenshots in the `/screenshots` folder.
![Entra Tenant Overview](../screenshots/phase-0/Entra ID Overview page.png)

![License Verification](../screenshots/phase-0/Licenses assigned page)

---

## Common Issues

Intune license missing  
→ Devices cannot enroll

No Entra ID P1  
→ Conditional Access unavailable

---

## Exam Relevance

MD-102 requires understanding of tenant readiness and licensing prerequisites.

---

## Real-World Usage

Administrators always validate licensing before onboarding devices to avoid enrollment failures.
