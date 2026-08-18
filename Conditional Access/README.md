# Conditional Access

Overview:
This folder documents Conditional Access policies configured in the IAM Home Lab using Microsoft Entra ID.
Conditional Access enforces adaptive access controls based on user risk, device compliance, and sign-in conditions.
These policies demonstrate how identity security can be strengthened through dynamic enforcement.

Objectives:
- Implement risk-based access restrictions
- Protect high-risk sign-ins and sensitive resources
- Exclude break-glass and test accounts safely
- Apply device-specific controls (Android, Windows, etc.)
- Validate policy impact through report-only mode

Policies Implemented:
- Block Android if High Risk
 - Prevent access from Android devices when sign-in risk is high.

- Insider Risk
  - Enforce MFA and session controls for internal users while excluding break-glass and test accounts.<img width="1920" height="1200" alt="Block Android if High Risk" src="https://github.com/user-attachments/assets/ced9f958-35d0-45f8-88d2-6103f898aa13" />
<img width="1920" height="1200" alt="Insider Risk Conditional Access" src="https://github.com/user-attachments/assets/e1162ef0-2586-4d51-bb59-20bc90e89eb3" />
