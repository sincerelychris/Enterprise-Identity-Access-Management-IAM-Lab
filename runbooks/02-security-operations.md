## Client Secret Rotation

**Purpose:**  
Client secrets must be rotated when exposure is suspected or as part of regular security hygiene.

**When to perform:**
- Secret accidentally exposed
- Developer offboarding
- Scheduled security maintenance

**Steps:**
1. Navigate to Auth0 Dashboard → Applications → Enterprise SSO App
2. Open Settings tab
3. Locate Client Secret section
4. Click "Rotate Client Secret"
5. Confirm application continues functioning after rotation

**Security Outcome:**
Old secret becomes invalid immediately, reducing risk of credential compromise.
