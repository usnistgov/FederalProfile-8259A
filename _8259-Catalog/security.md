---
layout: default
title: Device Security
navOrder: 7
navTitle: Security
permalink: /technical/security/
---

# Device Security

_See also the [non-technical counterpart to this section](../_8259-Control/security.md)_

## Secure Execution 

Ability for the IoT device to protect the execution of code on the device. Capabilities that may be necessary:
- Ability to enforce organization defined execution policies.
  - Ability to execute code in confined virtual environments.
  - Ability to separate IoT device processes into separate execution domains.
- Ability to separate the levels of IoT device user functionality.
- Ability to authorize various levels of IoT device functionality.

## Secure Communication 

Ability for the IoT device to securely initiate and terminate communications with other devices.  Capabilities that may be necessary:
- Ability to enforce traffic flow policies.
- Ability to utilize standardized protocols.
- Ability to establish network connections.
- Ability to terminate network connections.
- Ability to de-allocate TCP/IP address/port pairings.
- Ability to establish communications paths.
- Ability to secure the communication paths.
- Ability to interface with DNS/DNSSEC.
- Ability to store and process session identifiers.
- Ability to identify and track sessions with identifiers

## Secure Resource Usage 

Ability for the IoT device to securely utilize system resources and memory. Capabilities that may be necessary:
- Ability to support shared system resources.
  - Ability to release resources back to the system.
  - Ability to separate user and process resources use.
- Ability to manage memory address space assigned to processes.
- Ability to enforce access to memory space through the kernel.
- Ability to prevent a process from accessing memory space of another process.
- Ability to enforce configured disk quotas.
- Ability to provide sufficient resources to store and run the operating environment (e.g., operating systems, firmware, applications).
- Ability to utilize file compression technologies (e.g., to provide denial of service protection).

## Device Integrity 

Ability for the IoT device to protect against unauthorized changes to hardware and software. Capabilities that may be necessary:
- Ability to perform security compliance checks on system components.
- Ability to detect unauthorized hardware and software components. 
- Ability to take organizationally-defined actions when unauthorized hardware and software components are detected.
- Ability to store the operating environment (e.g., firmware image, software, applications) in read-only media (e.g., ROM).

## Secure Device Operation

Ability for the IoT device to operate securely and safely. Capabilities that may be necessary: 
- Ability to keep an accurate internal system time.
- Ability to define various operational states.
- Ability to operate in various operational states.
- Ability to define differing failure types.
- Ability to fail in a secure state.
- Ability to disable operations and/or functionality in the event of security violations.
- Ability to sense the environment and interface with various device components. Possible capabilities include:
  - Emergency shutoff mechanism
  - Emergency lighting mechanism
  - Fire protection mechanism
  - Temperature and humidity mechanism
  - Water damage protection mechanism
  - Manufacturer defined capability
