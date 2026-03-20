🔐 Microsoft Entra ID P2 - Enterprise IAM Lab

A hands-on Identity and Access Management lab built on Microsoft 
Entra ID P2, mirroring a production enterprise environment. 
Everything was completed manually through the Entra Admin Center 
with full screenshot evidence at every step.

🧩 Modules Covered

Module 1 - Identity Lifecycle (Joiner · Mover · Leaver)
- Provisioned 5 users across 3 regions with correct department 
  attributes and P2 licences
- Built 5 Dynamic Security Groups with ABAC rules on the 
  Department attribute
- Tested Joiner, Mover, and Leaver scenarios end-to-end

Module 2 - Access Governance & Entitlement Management
- Created an Access Package with self-service requests, 
  single-stage approval, and custom audit questions
- Configured a monthly recurring Access Review for guest (B2B) 
  users with auto-remediation

Module 3 - Zero Trust / Conditional Access
- Registered a trusted Named Location
- Deployed CA policy requiring Passwordless MFA for Global Admins
- Triaged a real Low-risk detection in ID Protection

Module 4 - Privileged Identity Management (PIM)
- Configured JIT access for User Administrator: 2hr max, 
  MFA required, ticket number required, human approval required
- Tested full activation workflow end-to-end across dual sessions
- Exported PIM audit log as compliance evidence

⚠️ Real Blockers Hit & Resolved

| Blocker | Resolution |
|---|---|
| Licence assignment blocked in Entra Admin Center | Switched to M365 Admin Center > Billing > Licences |
| Dynamic Groups show Owner only in Access Packages | Created dedicated Assigned Security Group for entitlement delivery |
| Lifecycle Workflows require Governance licence | Used Dynamic Groups as P2-native alternative |
| Security Defaults blocked CA policy creation | Disabled with break-glass account in place first |
| Inactive users filter disabled in Access Reviews | Used No sign-in within 30 days recommendation flag as proxy |

📄 Portfolio Document

Full step-by-step documentation with screenshots:
👉 https://github.com/MayankKhurasiya/Microsoft-Entra-IAM-Lab/blob/main/IAM_Portfolio_Final.pdf

🛠️ Environment

- Platform: Microsoft Entra ID P2
- Lab machine: Mac Mini (browser only - no scripts or automation)
- Completed: March 2026

🔗 Connect

