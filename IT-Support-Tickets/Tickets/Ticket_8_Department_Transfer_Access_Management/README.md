# Department Transfer Access Management

## Ticket Summary

A user transferred from the Engineering department to the IT Infrastructure department and required access permissions to be updated. The request involved removing obsolete access and granting permissions appropriate for the user's new role.

## Symptoms

* User changed departments within the organization
* Existing access permissions no longer matched job responsibilities
* New department access required
* Access review and update requested

## Investigation

1. Reviewed the department transfer request.
2. Accessed Active Directory user management tools.
3. Examined the user's current group memberships.
4. Identified outdated access associated with the Engineering department.
5. Verified the required access group for the IT Infrastructure department.

## Root Cause

The user's Active Directory group memberships had not yet been updated following an internal department transfer, resulting in outdated access permissions.

## Resolution

1. Accessed the user's account in Active Directory.
2. Removed the user from the Engineering security group.
3. Added the user to the IT Infrastructure security group.
4. Verified successful group membership changes.
5. Confirmed that access permissions aligned with the user's new department responsibilities.

## Resolution Notes

Processed a department transfer access request by reviewing the user's Active Directory group memberships. Identified that the user retained access associated with their previous department.

Removed the user from the Engineering security group and assigned the user to the IT Infrastructure security group. Verified that the membership changes were successfully applied and that access permissions reflected the user's current role requirements.

Issue resolved and ticket closed.

## Skills Demonstrated

* Active Directory Administration
* Group Membership Management
* Identity and Access Management (IAM)
* Access Control
* User Lifecycle Management
* Security Administration
* Change Management

## Technologies Used

* Active Directory
* Security Groups
* User Account Management
* Access Control Systems

## Key Learning Points

* Department transfers require both access removal and access provisioning.
* Users should retain only the permissions necessary for their current role.
* Removing outdated access is as important as granting new access.
* Security group memberships directly control access to organizational resources.
* Following the principle of least privilege reduces unnecessary security risk.
