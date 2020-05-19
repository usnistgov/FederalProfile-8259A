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

Ability to apply least privilege settings within the IOT device, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required functions., including the ability to create within the IOT device additional processes, roles, and accounts as necessary, to achieve least privilege. Additional configurations that may be necessary:
  - Ability to establish least privilege IOT device settings to establish time/date/etc. when privileged roles, accounts, etc. should expire. 
  - Ability for the IOT device user to use IOT device settings to establish access privileges through IOT device interfaces or within the IOT device.
  - Ability to establish a defined list within the IOT device to control logical access privileges (e.g., admin, emergency, temporary, etc.).

## Authentication and Authorization Configuration

- Ability to configure IOT device authentication policies and limitations., such as:
- Ability to use IOT device-based authentication controls to set and change authentication configurations, policies and limitations settings.
- Ability to modify IOT device configuration settings to automatically terminate the IOT device user&#39;s session
- Ability to set and change IOT device settings for wireless authentication protocols (e.g., EAP/TLS, PEAP).
- Ability to set the time period for how long the IOT device will remain locked after an established configurable limit of unsuccessful login attempts has been met.
- Ability to prohibit access to the IOT device after an established pre-defined or user-configurable number of unsuccessful login authentication attempts.
- Ability to log and view previous date and time of last successful login following successful login authentication.
- Ability for IOT device to support requiring a second factor of authentication through out of band pathways.
- Ability to require authentication prior to connecting to the IOT device.
- Ability for the IOT device user to access privileges settings to establish a defined list of dynamic privilege management capabilities.
- Ability to remotely establish and administer privileged user accounts to support role-based access.

## Interface Configuration

- Ability for only authorized entities to configure via a network process and/or logical interface aspects related to the device&#39;s interfaces, such as:
  - IOT device execution policy settings
  - IOT device services. (e.g., VoIP)
  - IOT device logical interface(s)
- Ability to control the IOT device&#39;s logical interface through that network process.

## Display Configuration

- Ability to display to IOT device user an organization-defined system use notification message or banner prior to successful authentication that provides privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance. This includes:
  - Ability to tailor the display of a publicly accessible IOT device with applicable required information.
  - Ability to retain the notification message or banner on the screen until the IOT device user actively acknowledges and agrees to the usage conditions and take explicit actions to log on to or further access the IOT device system.

## Device Configuration

- Ability to configure and change the IoT device&#39;s settings and software configurations, and
- the ability to restrict changes to the IoT device&#39;s settings and software configurations to authorized entities only. [Source: NIST IR 8259] Aspects to be configured include, but are not limited to:
  - The ability to establish IOT device configuration settings to enforce software installation policies and restrictions defined by the user/organization.
  - Ability to configure IOT device communications settings.
  - Ability to establish requirements for remote access to the device and/or device interface including usage restrictions, configuration and connection requirements.
  - Ability to modify IOT device configuration settings to automatically terminate the IOT device network connection(s) when nonlocal maintenance is completed.
  - Ability for the organization/user to establish the circumstances within IOT device settings for when information sharing from the IOT device and/or through the IOT device interface will be allowed and prohibited.
  - Ability to be configure the IOT device settings to disallow established types of connections even if a physical port is present (e.g., disallow a flash drive to be connected even if a USB port is present).
  - The capability to configure the IOT device as strict as possible while still meeting the operational requirements of the organization.
  - The capability to establish IOT device configuration settings to allow only the necessary functionality and be able to restrict components of the IOT device (e.g., ports, functions, protocols, services, etc.) as applicable.
  - Ability to disable individual IOT device system services.
  - Ability to uninstall IOT device system software.
- The ability to configure parameters of the IOT device system.
- Ability for the IOT device to detect unauthorized hardware and software components, and to take action when unauthorized components are detected as defined by the user.

**Adaptable Configuration**

- Ability to support different modes of IOT device operation with more restrictive access, for example:
  - "travel mode" for transit
  - "safe mode" for operation when some or all network security is unavailable
  - [TBD]
- Ability to support "alternative security mechanisms" within the IOT device when primary mechanisms (e.g., login protocol, encryption, etc.) are compromised.
