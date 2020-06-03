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

## Secure Resource Usage 
Ability for the device to securely utilize system resources and memory. Configurations that may be necessary:
- Ability to support IOT device shared system resources.
  - Ability to release resources from the IOT device back to the associated system.
  - Ability to separate user and process resources use.
- Ability to manage IOT device memory address space assigned to processes.
- Ability to enforce access by the IOT device to memory space through the kernel.
- Ability to prevent an IOT device process from accessing memory space of another process.
- Ability to enforce configured IOT device disk quotas.
- Provide sufficient resources to store and run the operating environment.

Device Integrity – the device protects against unauthorized changes to hardware and software

- Ability to perform security compliance checks on system components.
- Ability for the IoT device to utilize file compression technologies
- Ability to detect unauthorized hardware and software components 
- Ability to take organizationally-defined actions when unauthorized hardware and software components are detected.
- Ability for the IoT device to store the operating environment (e.g., firmware image, software, applications) in read-only media (e.g., ROM).

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
