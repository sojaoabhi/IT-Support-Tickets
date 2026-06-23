# VPN Connectivity and Network Drive Access

## Ticket Summary

A remote Marketing department user was unable to access files on the shared drive. The user received a "The network path was not found" error, and all mapped drives appeared disconnected. Internet and email access were functioning normally.

## Symptoms

* Unable to access Marketing shared drive
* "The network path was not found" error
* Mapped drives displayed as disconnected
* User working remotely
* Internet and email functioning normally

## Investigation

1. Connected to the user's workstation using Remote Support.
2. Reviewed network connectivity and VPN status.
3. Identified that the VPN client was disconnected.
4. Consulted internal documentation to obtain the correct Marketing department file share path.
5. Reviewed current drive mappings.

## Root Cause

The user's VPN connection was disconnected, preventing access to internal file servers and causing mapped network drives to become unavailable.

## Resolution

1. Reconnected the VPN client.
2. Verified successful VPN connectivity.
3. Retrieved the correct Marketing shared drive UNC path from documentation.
4. Mapped the Marketing network share to drive D:.
5. Verified successful access to shared files and folders.

## Resolution Notes

Connected remotely to the user's workstation and investigated the reported shared drive access issue. Verified that the VPN client was disconnected, preventing access to internal network resources and causing mapped drives to appear unavailable.

Reconnected the VPN client and confirmed successful network connectivity. Reviewed file server documentation, obtained the correct Marketing department UNC path, and mapped the network share to drive D:. Verified that the shared drive was accessible and that required files could be opened successfully.

Issue resolved and ticket closed.

## Skills Demonstrated

* Remote Support
* VPN Troubleshooting
* Network Drive Mapping
* File Server Access
* Documentation Usage
* End-User Support
* Incident Resolution
