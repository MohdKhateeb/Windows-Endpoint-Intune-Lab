# LAB-WIN-002 – Core Windows Groups Creation

## Objective

Create standard security groups used for Intune policy targeting.

---

## Navigation Path

Entra ID  
→ Groups  
→ New Group

---

## Groups to Create

INT-WIN-Autopilot-Devices  
INT-WIN-Enrolled-Devices  
INT-WIN-Users  
INT-WIN-Test-Devices

---

## Group Configuration

### INT-WIN-Autopilot-Devices

Purpose  
Devices imported into Windows Autopilot.

Type  
Dynamic Device Group

Dynamic Rule

(device.devicePhysicalIDs -any (_ -contains "[ZTDId]"))

Used for

- Autopilot Deployment Profile
- Enrollment Status Page

---

### INT-WIN-Enrolled-Devices

Purpose  
All Windows devices enrolled in Intune.

Dynamic Rule

(device.managementType -eq "MDM")

Used for

- Compliance policies
- BitLocker
- Defender policies
- Update Rings

---

### INT-WIN-Users

Purpose  
User targeting group.

Members

- Corporate users

Used for

- Conditional Access
- Windows Hello for Business
- Company Portal apps

---

### INT-WIN-Test-Devices

Purpose

Pilot devices for testing policies.

Members

1–2 test devices only.

Used for

- Policy testing
- Security baseline validation

---

## Architecture Principle

Users authenticate  
Devices comply  
Policies target devices  
Access targets users

---

## Common Mistake

Adding users to device groups.

This causes:

- BitLocker failures
- Compliance confusion
- ESP deployment errors