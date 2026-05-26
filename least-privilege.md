# Least Privilege Principle

## What is Least Privilege?
The principle of least privilege means giving users only the minimum permissions they need to do their job — nothing more, nothing less.

## How it was applied in this lab
- Developer-User was given ReadOnlyAccess — they can view resources but cannot create, modify, or delete anything
- Admin-User was given AdministratorAccess — only the administrator has full access to manage AWS resources
- MFA was enabled for Admin-User to add an extra layer of security for the most privileged account

## Why it matters
- Reduces the risk of accidental changes to critical resources
- Limits the damage if an account is compromised
- Ensures accountability by restricting who can make changes
