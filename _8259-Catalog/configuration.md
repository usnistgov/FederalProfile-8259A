---
layout: default
title: Device Configuration
navOrder: 2
navTitle: Configuration
permalink: /technical/configuration/
---

# Device Configuration

_See also the [non-technical counterpart to this section](../_8259-Control/configuration.md)_

The capability to configure the IOT device to meet the baseline configurations set by the organization and to update the baseline configuration requirements of the IOT device as established by the user/organization.

## Privilege Configuration

Ability to apply least privilege settings within the IOT device, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required functions. Configurations that may be necessary:
  - Ability to create within the IOT device additional processes, roles, and accounts as necessary, to achieve least privilege. 
  - Ability to establish least privilege IOT device settings to establish time/date/etc. when privileged roles, accounts, etc. should expire. 
  - Ability for the IOT device user to use IOT device settings to establish access privileges through IOT device interfaces or within the IOT device.
  - Ability to establish a defined list within the IOT device to control logical access privileges (e.g., admin, emergency, temporary, etc.).

## Authentication and Authorization Configuration

Ability to configure IOT device authentication policies and limitations. Configurations that may be necessary:
- Ability to use IOT device-based authentication controls to set/change authentication configurations, policies and limitations settings.
- Ability to modify IOT device configuration settings to automatically terminate the IOT device user's session.
- Ability to set and change IOT device settings for wireless authentication protocols (e.g., EAP/TLS, PEAP).
- Ability to set the time period for how long the IOT device will remain locked after an established configurable limit of unsuccessful login attempts has been met.
- Ability to prohibit access to the IOT device after an established pre-defined umber of unsuccessful login authentication attempts.
- Ability to prohibit access to the IOT device after a user-configurable number of unsuccessful login authentication attempts.
- Ability to log previous date and time of last successful login following successful login authentication.
- Ability to view previous date and time of last successful login following successful login authentication.
- Ability for require a second factor of device authentication through out of band pathways.
- Ability to require authentication prior to connecting to the IOT device through the device interface.
- Ability for the IOT device user to view privileges settings (to be able to view a defined list of dynamic privilege management capabilities).
- Ability for the IOT device user to change privileges settings.
- Ability to remotely establish and administer privileged user accounts to support role-based access.

## Interface Configuration

Ability for only authorized entities to configure aspects related to the device's interfaces. Configurations that may be necessary: 
  - Ability to make device configuration changes through the device's physcial interface.
  - Ability to make device configuration changes through the device's logical interface. 
  - Ability to change IOT device execution policy settings.
  - Ability to change IOT device services (e.g., VoIP, video-over-IP).
  - Ability to change IOT device logical interface(s).
  - Ability to control the IOT device's logical interface through network processes.

## Display Configuration

Ability to create content within a device display. Configurations that may be necessary:
  - Ability to display an organization-defined system use notification message or banner to the IOT device user prior to successful authentication. 
  - Ability to edit an existing IOT device display.
  - Ability to establish the maximum size (in characters, bytes, etc.) of the available device display.
  - Ability to retain the display on the screen until the IOT device user actively acknowledges and agrees to the usage conditions and takes an explicit action (e.g., press an agree button, enters initials) to further access the IOT device.

## Device Configuration

Ability to configure and change the IoT device's settings and software configurations. Configurations that may be necessary:
  - Ability to restrict changes to the IoT device's settings and software configurations to authorized entities only. 
  - Ability to establish IOT device configuration settings to enforce software installation policies and restrictions defined by the user/organization.
  - Ability to configure IOT device communications settings.
  - Ability to establish requirements for remote access to the device including:
      -- Usage restrictions.
      -- Configuration requirements.
      -- Connection requirements.
  - Ability to establish requirements for remote access to the device interface including:
      -- Usage restrictions.
      -- Configuration requirements.
      -- Connection requirements.
  - Ability to modify IOT device configuration settings to automatically terminate the IOT device network connection(s) when nonlocal maintenance is completed.
  - Ability to establish the circumstances within IOT device settings for when information sharing from the IOT device will be allowed.
  - Ability to establish the circumstances within IOT device settings for when information sharing from the IOT device will be prohibited.
  - Ability to establish the circumstances within IOT device settings for when information sharing through the IOT device interface will be allowed.
  - Ability to establish the circumstances within IOT device settings for when information sharing through the IOT device interface will be prohibited.
  - Ability to be configure the IOT device settings to disallow established types of connections even if a physical port is present (e.g., disallow a flash drive to be connected even if a USB port is present).
  - Ability to establish IOT device configuration settings to allow only the necessary functionality and be able to restrict components of the IOT device (e.g., ports, functions, protocols, services, etc.) as applicable.
  - Ability to disable individual IOT device system services.
  - Ability to uninstall IOT device system software.
  - Ability to configure parameters of the IOT device system.
  - Ability for the IOT device to detect unauthorized hardware and software components
  - Ability for the IOT device to take action when unauthorized components are detected as defined by the user.

**Adaptable Configuration**
Ability to establish adaptable configurations on the IOT device. Configurations that may be necessary: 
  - Ability to support different modes of IOT device operation with more restrictive access.
      -- "travel mode" for transit.
      -- "safe mode" for operation when some or all network security is unavailable.
      -- Others as determined necessary based on the purpose and goals for the IOT device.
  - Ability to support "alternative security mechanisms" within the IOT device when primary mechanisms (e.g., login protocol, encryption, etc.) are compromised.
