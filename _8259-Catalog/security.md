---
layout: default
title: Device Security
navOrder: 7
navTitle: Security
permalink: /technical/security/
---

# Device Security

_See also the [non-technical counterpart to this section](../_8259-Control/security.md)_

- Ability to scan files for unacceptable content.

(From here down from Kevin identified under Device Security in an earlier version:)

Secure Execution – the device can protect the execution of code on the device

- Ability to establish setting to protect the execution of code on the IOT device.
- Ability to enforce IOT device configuration _depending_ execution policies.

  _Requires some or all of the following on implementation:_

  - Ability for the IOT device to execute code in confined virtual environments.
  - Ability to separate IOT device processes into separate execution domains.
- Ability to separate the levels of IOT device user functionality.
- Ability to authorize various levels of IOT device functionality.
- Ability to enforce authentication for IOT device privileged function access (e.g., to management interface).
- Ability for the IOT device settings to be used to establish limits on concurrent sessions for accounts, users, roles, groups, etc., with authorized access to the device and/or interfaces with the device.
- Ability for the IOT device settings to be used to establish time, location, and other limits on concurrent sessions to the device.

Secure Communication – the device can securely initiate and terminate communications with other devices

- Ability to enforce through the IOT device configuration settings traffic flow policies.
- Ability to utilize standardized protocols within the IOT device.
- Ability for the IOT device to establish network connections.
- Ability for the IOT device to terminate network connections
- Ability for the IOT device to de-allocate TCP/IP address/port pairings.
- Ability for the IOT device to establish communications paths.
- Ability for the IOT device to secure the communication paths.
- Ability for the IOT device to interface with DNS/DNSSEC.
- Ability within the IOT device settings to store/process session identifiers.
- Ability to identify and track sessions with identifiers

Secure Resource Usage – the device can securely utilize system resources, including memory

- Ability to support IOT device shared system resources.
  - Ability to release resources from the IOT device back to the associated system.
  - Ability to separate user and process resources use.
- Ability to manage IOT device memory address space assigned to processes.
- Ability to enforce access by the IOT device to memory space through kernel.
- Ability to prevent an IOT device process from accessing memory space of another process.
- Ability to enforce configured IOT device disk quotas.
- Ability to established sufficient code space in IOT device memory.

Device Integrity – the device protects against unauthorized changes to hardware and software

- Ability to perform security compliance checks on system components.
- Ability to establish sufficient resources to store IOT device operating environment in ROM.
- Ability for the IoT device to utilize ROM for disk image/software
- Ability for the IOT device to restrict access to its software, hardware, and data based on organizationally defined roles, used with proper authentication of the identity of the user to determine type of authorization.
- Ability within the IOT device settings to prevent external access to management interface.
- Ability within the IOT device settings to detect unauthorized hardware and software components and must be able to take action when unauthorized components are detected that is defined by the organization.
- Ability for the IOT device to sense the environment and interface with various device components including:

  - emergency shutoff mechanism.
  - emergency lighting mechanism.
  - fire protection mechanism.
  - temperature and humidity mechanism.
  - water damage protection mechanism.

Secure Device Operation – the device can operate securely and safely

- Ability to keep an accurate internal system time
- Ability to define various operational states.
- Ability to operate in various operational states
- Ability to define differing failure types.
- Ability to require the IOT device to fail in a secure state
- Ability to disable the IOT device in the event of security violations.

- Ability for the IOT device to sense the environment and interface with various device components including:

  - emergency shutoff mechanism.
  - emergency lighting mechanism.
  - fire protection mechanism.
  - temperature and humidity mechanism.

- water damage protection mechanism.
