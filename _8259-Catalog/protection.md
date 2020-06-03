---
layout: default
title: Data Protection
navOrder: 3
navTitle: Protection
permalink: /technical/protection/
---

# Data Protection

_See also the [non-technical counterpart to this section](../_8259-Control/protection.md)_

## Cryptography Capabilities and Support

- Ability for the IOT device to use cryptography for data protection.

	_Requires some or all of the following depending on implementation:_

  - Ability for the IOT device to utilize sufficient resources to employ cryptographic mechanisms.
  - Ability for the IOT device to obtain and validate certificates.
  - Ability for the IOT device to verify digital signatures.
  - Ability for the IOT device to run hashing algorithms.
  - Ability for the IOT device to compute and compare hashes.
  - Ability for the IOT device to change keys securely.
  - Ability for the IOT device to manage cryptographic keys securely.

    _Requires some or all of the following depending on implementation:_

    - Ability for the IOT device to generate key pairs
    - Ability for the IOT device to store encryption keys securely
    - Ability for the IoT device to change keys securely

## Secure Storage

Ability for the IOT device, or tools used through the IOT device interface, to enable secure device storage. Configurations that may be necessary:
- Ability to support encryption of data at rest. 
  - Ability to cryptographically store passwords at rest, as well as other authentication data.
  - Ability to support data encryption and signing to prevent data from being altered in device storage.
- Ability to secure data in device storage. 
  - Ability to secure data stored locally on the device.
  - Ability to secure data stored in remote storage areas (e.g., cloud, server, etc.).
  - Ability to utilize separate storage partitions for system and user data.
- Ability to "sanitize" or "purge" specific or all data within the device.


## Secure Transmission

- Ability for the IOT device to configure the cryptographic algorithm to protect data in transit.
  - Ability for the IOT device to support trusted data exchange with a specified minimum strength cryptography algorithm.
  - Ability for the IOT device to support data encryption and signing to prevent data from being altered in transit.
- The IoT device can utilize one or more capabilities to protect the data it transmits from unauthorized access and modification.
- Ability for the IOT device to use cryptographic means to validate integrity of data transmitted

