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
![Uploading Block Android if High Risk.png…]()


- Insider Risk
  - Enforce MFA and session controls for internal users while excluding break-glass and test accounts.

![Uploading Insider Risk Conditional Access.png…]()
