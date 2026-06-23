# Active Directory Password Reset and Account Recovery

## Ticket Summary

A user returning from an extended absence was unable to log in to their workstation. The system indicated that the user's password had expired, but the password could not be changed from the login screen.

## Symptoms

* User unable to log in to workstation
* Password expiration message displayed
* Password change from login screen unsuccessful
* User had been inactive for several weeks

## Investigation

1. Accessed Active Directory administration tools.
2. Searched for the affected user account.
3. Reviewed account details and status.
4. Verified the user's identity using the approved verification process.
5. Confirmed that a password reset was required to restore access.

## Root Cause

The user's password had expired during an extended period of inactivity, preventing successful authentication.

## Resolution

1. Verified the user's identity before making account changes.
2. Reset the user's password in Active Directory.
3. Generated a temporary password.
4. Shared the temporary password securely through the approved communication channel.
5. Instructed the user to change the password upon first login.
6. Verified that account access was successfully restored.

## Resolution Notes

Reviewed the user's Active Directory account and verified identity using the approved verification process. Confirmed that the account password had expired due to an extended period of inactivity.

Reset the password and generated a temporary credential for account recovery. Shared the temporary password securely with the user and instructed them to create a new password during the next login. Verified that the user successfully regained access to their workstation.

Issue resolved and ticket closed.

## Skills Demonstrated

* Active Directory Administration
* Password Reset Procedures
* Identity Verification
* Account Recovery
* User Authentication Support
* Secure Credential Handling
* End-User Support
* Incident Resolution

## Technologies Used

* Active Directory
* Microsoft Teams
* User Account Management Tools
