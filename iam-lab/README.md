# IAM Security Lab

## Objective

Set up a secure AWS environment by creating an IAM user and enabling Multi-Factor Authentication (MFA).

---

## Steps Performed

1. Logged into AWS console using root account
2. Navigated to IAM service
3. Created a new IAM user with administrative permissions
4. Enabled console access for the user
5. Assigned "AdministratorAccess" policy
6. Logged out from root account
7. Logged in using IAM user
8. Enabled MFA using an authenticator app

---

## Key Learnings

* Root account should not be used for daily tasks
* IAM users provide better access control
* MFA is essential for securing accounts
* AWS security starts with identity management

---

## Issues Encountered

* Initially accessed AWS from the wrong page (not the console)
* Confusion between root user and IAM user login

---

## Solutions

* Used AWS Management Console correctly
* Logged in with root email instead of IAM credentials
* Followed IAM workflow step-by-step

---

## Security Best Practices

* Avoid using root account
* Enable MFA for all users
* Use least privilege (temporary admin for setup only)

---

## Next Lab

S3 Security Lab (public vs private access)
