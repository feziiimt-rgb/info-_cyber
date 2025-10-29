# Fundmental of computer Security
## identificstion , authentication and Authorification



| Concept | Description | Example |
|----------|--------------|----------|
| Identification | Claiming an identity | Typing username |
| Authentication | Proving identity | Entering password / fingerprint |
| Authorization | Granting access | Accessing certain files after login |

---

##  Key Principle:
> “Authentication verifies who you are. Authorization decides what you can do.”

---

##  Authentication Methods

- Knowledge-based: Passwords, PINs
- Possesssio-bond: smart card , OTP tokens
- Inherence-based : Biometrics (fingerprint,face ID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- Single sign-0n (SSO):  one-time login across multiple system (eg,Google or Microsoft SS0)

# Authorization  Model

- DAC (Discretionay Access Control): owner decides who can access (windos permisssion)
- MAC ( Mandatory Access COontrol): Acess based on classifiacation levels (military system)
- RBAC (Role - Baesed Access Control): permission assigned to role (admin ,manager, user)
- ABAC (Attribute-Based Access Control): Access based on condition

## Example:

An "HR Manager" role can view employee data, while "Employee" role can only view their own profil

Best Practices

strong, unique unique passwords.

Apply MFA wherever possible.

Review role-based permissions regularly.

Log all authentication and access events.
