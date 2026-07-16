# Windows 11 Help Desk Home Lab

## Overview

This home lab simulates common Tier 1 Help Desk tasks performed in a Windows 11 Pro environment. The objective was to practice real-world desktop support responsibilities, including user account management, software installation, Windows maintenance, and basic network troubleshooting while documenting each task using help desk ticket formats.

---

## Lab Environment

- **OS:** Windows 11 Pro (25H2)
- **Processor:** Intel Core i5
- **Memory:** 8 GB RAM

---

## Skills Demonstrated

- Local user account management
- Administrator permission management
- Windows Update maintenance
- Software installation and removal
- Network troubleshooting
- DNS verification
- Command Prompt utilities
- Help Desk ticket documentation
- Basic Windows system administration

---

# Lab Tasks

## 1. Create Local User Account

### Ticket #001

**Issue**

A new employee required a local Windows account.

**Actions Performed**

- Created a new Standard User account.
- Verified successful account creation.
- Confirmed the user could sign in.

**Resolution**

Local user account created successfully.

---

## 2. Administrator Permissions

### Scenario

A user needed software installed but did not have administrator privileges.

**Actions Performed**

- Temporarily changed the user account to Administrator.
- Installed the requested software.
- Returned the account to Standard User.

**Real-World Note**

In a production environment, I would authenticate using my administrator credentials rather than permanently changing the user's account type.

---

## 3. Windows Update

### Ticket #002

**Issue**

The workstation required Windows updates.

**Actions Performed**

- Checked Windows Update.
- Installed available firmware updates.
- Restarted the system.
- Verified updates completed successfully.

**Resolution**

System updated successfully.

---

## 4. Software Installation & Removal

### Ticket #003

**Issue**

User requested installation of Google Chrome.

**Actions Performed**

- Downloaded Google Chrome.
- Installed the application.
- Verified successful installation.
- Uninstalled Chrome to practice software removal.

**Resolution**

Software installed and removed successfully.

---

## 5. Network Troubleshooting

### Ticket #004

**Issue**

User reported no internet connectivity.

**Actions Performed**

Opened Command Prompt and performed the following diagnostics:

- Used `ipconfig` to review network configuration.
- Used `ping 8.8.8.8` to verify IP connectivity.
- Used `ping google.com` to test DNS name resolution.
- Used `nslookup google.com` to verify DNS functionality.

**Findings**

- IP connectivity was functioning normally.
- DNS successfully resolved hostnames.
- Internet connectivity could not be reproduced as failed.

**Resolution**

Verified normal network operation. User confirmed internet access was restored.

---


# Commands Used

```cmd
ipconfig
ping 8.8.8.8
ping google.com
nslookup google.com
```

---

# Key Takeaways

Through this lab I gained hands-on experience with common Tier 1 Help Desk responsibilities, including:

- Managing local Windows user accounts
- Understanding administrator permissions
- Maintaining Windows systems through updates
- Installing and removing software
- Troubleshooting network connectivity using Command Prompt
- Documenting technical work using help desk ticket formats

This project demonstrates foundational Windows administration and troubleshooting skills commonly required for entry-level IT Support and Help Desk roles.
