---
layout: default
title: Device Configuration
navOrder: 2
navTitle: Configuration
permalink: /technical/configuration/
---

# Device Configuration

_See also the [non-technical counterpart to this section](../_8259-Control/configuration.md)_

The capability to configure the IoT device through logical and/or physical interfaces to meet organizational requirements.

## Logical Access Privilege Configuration

Ability for only authorized entities to apply logical access privilege settings within the IoT device and configure logical access privilege as described in Logical Access to Interfaces.
 
## Authentication and Authorization Configuration

Ability for only authorized entities to configure IoT device authentication policies and limitations as described in Logical Access to Interfaces.

## Interface Configuration

Ability for only authorized entities to configure aspects related to the device's interfaces as described in Logical Access to Interfaces. 
    
## Display Configuration

Ability to configure content to be shown within a device display as described in Logical Access to Interfaces.
    
## Device Configuration

Ability to configure and change the IoT device's settings and software configurations. Configurations that may be necessary:
  - Ability to restrict changes to the IoT device's settings and software configurations to authorized entities only. 
  - Ability to establish IoT device configuration settings to enforce software installation policies and restrictions defined by the user/organization.
  - Ability to configure IoT device communications settings.
  - Ability to establish requirements for remote access to the device including:
      -- Usage restrictions.
      -- Configuration requirements.
      -- Connection requirements.
  - Ability to establish requirements for remote access to the device interface including:
      -- Usage restrictions.
      -- Configuration requirements.
      -- Connection requirements.
  - Ability to modify IoT device configuration settings to automatically terminate the IoT device network connection(s) when nonlocal maintenance is completed.
  - Ability to establish the circumstances within IoT device settings for when information sharing from the IoT device will be allowed.
  - Ability to establish the circumstances within IoT device settings for when information sharing from the IoT device will be prohibited.
  - Ability to establish the circumstances within IoT device settings for when information sharing through the IoT device interface will be allowed.
  - Ability to establish the circumstances within IoT device settings for when information sharing through the IoT device interface will be prohibited.
  - Ability to be configure the IoT device settings to disallow established types of connections even if a physical port is present (e.g., disallow a flash drive to be connected even if a USB port is present).
  - Ability to establish IoT device configuration settings to allow only the necessary functionality and be able to restrict components of the IoT device (e.g., ports, functions, protocols, services, etc.) as applicable.
  - Ability to disable individual IoT device system services.
  - Ability to uninstall IoT device system software.
  - Ability to configure parameters of the IoT device system.
  - Ability for the IoT device to detect unauthorized hardware and software components
  - Ability for the IoT device to take action when unauthorized components are detected as defined by the user.

## Adaptable Configuration
Ability to establish adaptable configurations on the IoT device. Configurations that may be necessary: 
  - Ability to support different modes of IoT device operation with more restrictive access.
      -- "travel mode" for transit.
      -- "safe mode" for operation when some or all network security is unavailable.
      -- Others as determined necessary based on the purpose and goals for the IoT device.
  - Ability to support "alternative security mechanisms" within the IoT device when primary mechanisms (e.g., login protocol, encryption, etc.) are compromised.
