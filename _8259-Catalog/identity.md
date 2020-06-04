---
layout: default
title: Device Identity
navOrder: 1
navTitle: Identity
permalink: /technical/identity/
---

# Device Identity

_See also the [non-technical counterpart to this section](../_8259-Control/identity.md)_

## Asset Identifier Support

Ability for device identification. Configurations that may be necessary: 
- Ability to uniquely identify the IoT device physically.
- Ability to uniquely identify the IoT device logically.
- Ability to uniquely identify a remote IoT device.
- Ability for the IoT device to support a unique device ID (e.g. to allow it to be linked to the person or process assigned to use the IoT device).

## Actions Based on Device Identity

Actions that can occur based on or using the identity of the device. Configurations that may be necessary:  
- Ability to configure IoT device access control policies using IoT device identity.
  - Ability to hide IoT device identity from non-authorized entities.
  - Ability for the IoT device to differentiate between authorized and unauthorized remote users.
  - Ability for the IoT device to differentiate between authorized and authorized physical device users.
- Ability to monitor specific actions based on IoT device identity.
- Ability to identify software loaded on IoT device based on IoT device identity.

## Device Authentication Support

Actions to support local or interfaced device authentication. Configurations that may be necessary:
- Ability for the IoT device to authenticate itself as an authorized entity to other devices.
- Ability to remotely authenticate the IoT device.

