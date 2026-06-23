# WiFi Connectivity Troubleshooting and Profile Reset

## Ticket Summary

A user reported an inability to connect to the company wireless network. Other users were able to connect successfully, indicating that the issue was isolated to the affected workstation rather than the wireless infrastructure.

## Symptoms

* Unable to connect to the SDSim-Secure WiFi network
* Network connectivity unavailable on a single device
* Other users connected successfully
* Internet access unavailable on the affected workstation

## Investigation

1. Connected to the user's workstation using Remote Support.
2. Reviewed network and wireless adapter settings.
3. Verified that the issue affected only the user's device.
4. Consulted internal documentation for the approved SDSim-Secure wireless configuration.
5. Determined that the saved wireless profile was likely corrupted.

## Root Cause

A corrupted WiFi profile prevented the workstation from successfully authenticating and connecting to the SDSim-Secure wireless network.

## Resolution

1. Connected remotely to the user's workstation.
2. Opened Network & Internet settings.
3. Disconnected from the current wireless network.
4. Removed the saved SDSim-Secure WiFi profile.
5. Retrieved the correct wireless security key from internal documentation.
6. Reconnected to the SDSim-Secure network using the documented credentials.
7. Verified successful wireless authentication and network connectivity.
8. Confirmed that internet access was restored.

## Resolution Notes

Connected remotely to the user's workstation and investigated the reported wireless connectivity issue. Verified that the issue was isolated to the user's device and identified a corrupted wireless profile as the likely cause.

Removed the existing SDSim-Secure WiFi profile and reconfigured the connection using the approved network settings and security key obtained from documentation. Verified successful connectivity and confirmed that internet access was restored.

Issue resolved and ticket closed.

## Skills Demonstrated

* Wireless Network Troubleshooting
* Remote Support
* Network Configuration
* Connectivity Diagnostics
* Documentation Usage
* End-User Support
* Technical Troubleshooting
* Incident Resolution

## Technologies Used

* Windows Network Settings
* WiFi Network Profiles
* Wireless Authentication
* Remote Support Tools
* Internal Documentation

## Key Learning Points

* Determine whether a connectivity issue affects a single user or multiple users before troubleshooting.
* Device-specific wireless issues are often caused by corrupted network profiles.
* Removing and recreating a WiFi profile can resolve authentication and connectivity problems.
* Documentation should be consulted to ensure the correct network configuration is applied.
* Verifying connectivity after remediation confirms successful resolution.
