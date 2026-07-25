# Create a New Active Directory User

## Overview

This document describes the standard procedure for creating a new user account in Microsoft Active Directory within an enterprise environment.

---

## Purpose

To ensure that new user accounts are created consistently, securely, and according to organizational standards.

---

## Scope

This procedure applies to IT administrators responsible for managing Active Directory user accounts.

---

## Prerequisites

- Active Directory Users and Computers (ADUC)
- Appropriate administrative permissions
- User information provided by Human Resources or the responsible department

---

## Procedure

### Step 1 – Open Active Directory Users and Computers

Launch **Active Directory Users and Computers (ADUC)** from the Administrative Tools.

### Step 2 – Select the Organizational Unit (OU)

Navigate to the appropriate Organizational Unit (OU) where the new user account should be created.

### Step 3 – Create a New User

Right-click the OU and select:

**New → User**

### Step 4 – Enter User Information

Fill in:

- First Name
- Last Name
- Display Name
- User Logon Name (UPN)

### Step 5 – Configure Password

- Set an initial password.
- Enable **User must change password at next logon** if required.
- Apply organizational password policies.

### Step 6 – Assign Security Groups

Add the user to the required security groups based on their department or role.

### Step 7 – Verify the Account

Confirm that:

- The account is enabled.
- Group memberships are correct.
- Login name is accurate.

---

## Verification Checklist

- User account created successfully
- Correct Organizational Unit
- Appropriate group memberships
- Password configured
- Account enabled

---

## Best Practices

- Follow organizational naming conventions.
- Apply the principle of least privilege.
- Assign users only to required security groups.
- Verify all user information before saving.

---

## Common Issues

| Issue | Possible Cause |
|-------|----------------|
| User cannot log in | Incorrect password |
| Missing permissions | Wrong security group |
| Account disabled | User account not enabled |

---

## Troubleshooting

- Verify Active Directory replication.
- Confirm DNS functionality.
- Check group memberships.
- Review Event Viewer if authentication fails.

---

## Security Considerations

- Never share administrative credentials.
- Apply password policies.
- Remove unused accounts promptly.
- Follow organizational security procedures.

---

## References

- Microsoft Active Directory Documentation

---

**Version:** 1.0

**Author:** Maryam Farmanbar

**Last Updated:** July 2026
