# iam-identity-lab
Azure Entra ID + SSO + MFA + SCIM + LDAP hands-on IAM portfolio project

# End-to-End Identity Platform: Azure Entra ID + SSO + MFA + SCIM + LDAP

## Goal
Build a real-world IAM lab that demonstrates enterprise identity skills:
- SSO using SAML
- MFA enforcement using Conditional Access
- Automated provisioning using SCIM
- Group + Dynamic Group access control
- (Optional) LDAP integration for attribute storage and identity sources

## What I Built (High Level)
- Microsoft Entra ID tenant with test users and groups
- Conditional Access policy to enforce MFA
- SSO integration to a real SaaS application using SAML
- SCIM provisioning to automatically create/update/deprovision users in the SaaS app
- Dynamic Groups based on user attributes (department, role, etc.)
- Troubleshooting logs for common IAM failures (SSO errors, MFA blocks, provisioning failures)

## Tools / Platforms
- Microsoft Entra ID (Azure AD)
- Conditional Access + MFA
- SAML SSO (Shibboleth or SaaS SAML integration)
- SCIM provisioning
- (Optional) LDAP on a Linux VM

## Lab Accounts (Example)
- HR User (basic access)
- IT User (admin tools access)
- Contractor (restricted access)
- Test User (used for troubleshooting scenarios)

## Deliverables in This Repo
- /architecture: diagrams + design notes
- /runbooks: step-by-step configuration guides I wrote
- /screenshots: proof of working SSO/MFA/provisioning (no secrets)
- /configs: sanitized config snippets (no tenant IDs/secrets)
- /evidence: troubleshooting notes + “what I broke and how I fixed it”

## Security Note
No secrets are stored in this repo.
All screenshots are sanitized and any keys/tokens are removed.
