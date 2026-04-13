# LAB-WIN-020 — Application Packaging via Content Prep Tool

## Objective

Package Win32 applications into `.intunewin` format for deployment through Microsoft Intune.

---

## Navigation Path

Microsoft Intune Admin Center
Apps → Windows → Add → App type: Windows app (Win32)

---

## Step-by-Step

1. Download the Microsoft Win32 Content Prep Tool

2. Prepare application source files:

   * Place installer (e.g., `.exe` or `.msi`) in a folder
   * Remove unnecessary files

3. Run the Content Prep Tool:

   * Launch `IntuneWinAppUtil.exe`
   * Specify:

     * Source folder
     * Setup file
     * Output folder

4. Generate `.intunewin` package

5. Upload package to Intune:

   * Go to Apps → Windows → Add
   * Select **Windows app (Win32)**

6. Configure application details:

   * Name, description, publisher

7. Set program installation commands:

   * Install command
   * Uninstall command

8. Define requirements:

   * OS architecture
   * Minimum OS version

9. Configure detection rules:

   * File, registry, or MSI detection

10. Assign application to users/devices

---

## Captured Screenshots

* Content Prep Tool execution window
* `.intunewin` file creation
* App upload screen in Intune

---

## Common Issues

* Incorrect install command causing failure
* Missing dependencies not included in package
* Detection rules misconfigured leading to reinstall loops

---

## Exam Relevance

Understanding Win32 app packaging is essential for managing enterprise application deployment in Microsoft Intune.

---

## Real-World Usage

Administrators package custom or legacy applications into `.intunewin` format and deploy them securely across managed endpoints using Microsoft Intune.

---

If you want, I can also create:

* a **hands-on lab with sample commands**
* or a **screenshot-by-screenshot guide matching your uploaded images**
