# Mobile Email Synchronization Troubleshooting

## Ticket Summary

A user reported that their work email was no longer synchronizing on their Android device. Email access from other platforms was unaffected, indicating a mobile configuration issue.

## Symptoms

* Work email not syncing on Android device
* User unable to receive new emails on mobile
* Existing account present but synchronization failing
* Other services functioning normally

## Investigation

1. Reviewed internal documentation for approved mail server configuration settings.
2. Verified the correct incoming mail server details.
3. Determined that the user's mobile email configuration required updating.
4. Prepared user guidance for updating server settings on the Android device.

## Root Cause

The mobile email client was configured with incorrect or outdated mail server settings, preventing successful synchronization with the mail server.

## Resolution

1. Retrieved the correct mail server configuration from internal documentation.
2. Provided the user with step-by-step instructions through Teams Chat.
3. Guided the user to update the incoming mail server settings on the Android device.
4. Configured:

   * Server: mail.servicedesk-simulator.com
   * Port: 443
   * Security Type: SSL/TLS
5. Instructed the user to save the changes and allow the mailbox to re-synchronize.
6. Verified that email synchronization resumed successfully.

## Resolution Notes

Reviewed mail server configuration documentation and verified the correct server settings for the user's mobile email account. Provided updated server information and detailed instructions for updating the Android email configuration.

The user updated the incoming mail server settings, saved the changes, and allowed the account to re-synchronize. Verified that email synchronization resumed successfully and that new messages were being received on the device.

Issue resolved and ticket closed.

## Skills Demonstrated

* Mobile Device Support
* Email Troubleshooting
* Mail Server Configuration
* Documentation Usage
* End-User Communication
* Microsoft Exchange Concepts
* Technical Support

## Technologies Used

* Android
* Email Client Configuration
* SSL/TLS
* Microsoft Teams
* Internal Documentation

## User Instructions Provided

1. Open Settings → Accounts → Work Email Account
2. Open Account Settings / Server Settings
3. Update Incoming Server Settings:

   * Server: mail.servicedesk-simulator.com
   * Port: 443
   * Security Type: SSL/TLS
4. Save changes and allow the account to re-sync
5. Verify that new emails are received successfully
