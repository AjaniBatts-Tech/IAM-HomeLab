# Groups

Overview
- This folder contains all security and organizational groups used in the IAM Home Lab.
- These groups demonstrate how identity teams structure access, enforce least privilege, and organize users based on department, role, device type, and security requirements.
- Each group below represents a real-world IAM pattern used in Microsoft Entra ID.

My Current Groups:
<img width="1920" height="1200" alt="All Groups" src="https://github.com/user-attachments/assets/31e0ae16-620e-474b-b322-2d51e391f43c" />

- App Access:
  - Groups used to assign access to specific applications

- Break-Glass Exclusion:
  - Emergency access group containing only break-glass accounts.
  - Excluded from Conditional Access and MFA
  - Ensure access during outages, heavily monitored and tightly controlled.

- Finance:
  - Department-based group for users on the Finance team.

- Human Resources:
  - Department-based group for Human Resources.

- IT:
  - Department-based group for IT staff and administrators.

- Privileged Access:
  - Contains users with elevated or administrative roles.

- Sales:
  - Department group for Sales users.

- Texas Windows Devices
  - Device-based group containing Windows devices located in Texas.

- Whole Company
  - A broad group containing all standard users.
