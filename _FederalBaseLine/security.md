---
layout: default
title: Device Security
navOrder: 7
navTitle: Security
permalink: /security/
---

# Device Security

- Ability to keep an accurate internal system time
- Ability to perform security compliance checks on system components.
- Ability to define various operational states. (7,24)
- Ability to operate in various operational states
- Ability to define differing failure types. (24)
- Ability to scan files for unacceptable content. (18)
- Ability to require the IOT device to fail in a secure state (7, 24)
- Ability to disable the IOT device in the event of security violations.
- Ability to establish setting to protect the execution of code on the IOT device.
- Ability to support IOT device shared system resources. (4)
  - Ability to release resources from the IOT device back to the associated system. (4)
  - Ability to separate user and process resources use. (4)
- Ability to enforce IOT device configuration execution policies. (18)

  _Requires some or all of the following depending on implementation:_

  - Ability for the IOT device to execute code in confined virtual environments. (18)
  - Ability to separate IOT device processes into separate execution domains. (39,44)
  - Ability to manage IOT device memory address space assigned to processes. (39)
  - Ability to enforce access by the IOT device to memory space through kernel. (39)
  - Ability to prevent an IOT device process from accessing memory space of another process. (39)
  - Ability to enforce configured IOT device disk quotas. (5)
- Ability to establish sufficient resources to store IOT device operating environment in ROM. (34)
- Ability to established sufficient code space in IOT device memory. (34)
- Ability to enforce through the IOT device configuration settings traffic flow policies. (7)
- Ability to utilize standardized protocols within the IOT device. (7)
- Ability for the IOT device to establish network connections. (10)
- Ability for the IOT device to terminate network connections (10)
- Ability for the IOT device to de-allocate TCP/IP address/port pairings. (10)
- Ability for the IOT device to establish communications paths. (11,23)
- Ability for the IOT device to secure the communication paths. (11,23)
- Ability for the IOT device to interface with DNS/DNSSEC. (20)


(From here down from Kevin identified under Device Security in an earlier version:)

Secure Execution – the device can protect the execution of code on the device

- Ability to establish setting to protect the execution of code on the IOT device.
- Ability to enforce IOT device configuration _depending_ execution policies. (18)

  _Requires some or all of the following on implementation:_

  - Ability for the IOT device to execute code in confined virtual environments. (18)
  - Ability to separate IOT device processes into separate execution domains. (39,44)
- Ability to separate the levels of IOT device user functionality. (2,3,32)
- Ability to authorize various levels of IOT device functionality. (2,3)
- Ability to enforce authentication for IOT device privileged function access (e.g., to management interface). (7,19)
- Ability for the IOT device settings to be used to establish limits on concurrent sessions for accounts, users, roles, groups, etc., with authorized access to the device and/or interfaces with the device.
- Ability for the IOT device settings to be used to establish time, location, and other limits on concurrent sessions to the device.
- Ability within the IOT device settings to prevent download of unacceptable content. (18)
-

Secure Communication – the device can securely initiate and terminate communications with other devices

- Ability to enforce through the IOT device configuration settings traffic flow policies. (7)
- Ability to utilize standardized protocols within the IOT device. (7)
- Ability for the IOT device to establish network connections. (10)
- Ability for the IOT device to terminate network connections (10)
- Ability for the IOT device to de-allocate TCP/IP address/port pairings. (10)
- Ability for the IOT device to establish communications paths. (11,23)
- Ability for the IOT device to secure the communication paths. (11,23)
- Ability for the IOT device to interface with DNS/DNSSEC. (20)
- Ability within the IOT device settings to store/process session identifiers. (23)
- Ability to identify and track sessions with identifiers (23)

Secure Resource Usage – the device can securely utilize system resources, including memory

- Ability to support IOT device shared system resources. (4)
  - Ability to release resources from the IOT device back to the associated system. (4)
  - Ability to separate user and process resources use. (4)
- Ability to manage IOT device memory address space assigned to processes. (39)
- Ability to enforce access by the IOT device to memory space through kernel. (39)
- Ability to prevent an IOT device process from accessing memory space of another process. (39)
- Ability to enforce configured IOT device disk quotas. (5)
- Ability to established sufficient code space in IOT device memory. (34)

Device Integrity – the device protects against unauthorized changes to hardware and software

- Ability to perform security compliance checks on system components.
- Ability to establish sufficient resources to store IOT device operating environment in ROM. (34)
- Ability for the IOT device to restrict access to its software, hardware, and data based on organizationally defined roles, used with proper authentication of the identity of the user to determine type of authorization.
- Ability within the IOT device settings to prevent external access to management interface. (5)
- Ability within the IOT device settings to detect unauthorized hardware and software components and must be able to take action when unauthorized components are detected that is defined by the organization. (CM-8 (3))
- Ability for the IOT device to sense the environment and interface with various device components including:

  - emergency shutoff mechanism.
  - emergency lighting mechanism.
  - fire protection mechanism.
  - temperature and humidity mechanism.
  - water damage protection mechanism.

Secure Device Operation – the device can operate securely and safely

- Ability to keep an accurate internal system time
- Ability to define various operational states. (7,24)
- Ability to operate in various operational states
- Ability to define differing failure types. (24)
- Ability to require the IOT device to fail in a secure state (7, 24)
- Ability to disable the IOT device in the event of security violations.

- Ability for the IOT device to sense the environment and interface with various device components including:

  - emergency shutoff mechanism.
  - emergency lighting mechanism.
  - fire protection mechanism.
  - temperature and humidity mechanism.

- water damage protection mechanism.
