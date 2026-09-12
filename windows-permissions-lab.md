# Windows Permissions Lab

## Objective

To test the difference between authentication and authorization in Windows by creating separate user accounts and applying NTFS permissions to control what each authenticated user could access or modify.

## What I learned

While authetnication provies identity, authorication controls what that identity is allowed to do. NTFS Permissions are a part of that authorization layer. An explict Deny takes precedence over a conflicitng Allow permisson. So while a user may have authentication, windows will usually honor the Deny.