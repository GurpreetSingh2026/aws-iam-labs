# Personal Notes

Today I learned how AWS handles authentication and permissions.

Root User:
- Has full control of the account.
- Should not be used daily.

IAM User:
- Used for normal work.
- Can be granted specific permissions.

MFA:
- Uses an authenticator app.
- Generates a new code every 30 seconds.
- Protects the account if the password is stolen.

Questions:
- Learn how IAM Roles work.
- Learn how permissions are inherited.
