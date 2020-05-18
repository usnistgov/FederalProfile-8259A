---
layout: default
title: Logical Access to Interfaces
navOrder: 4
navTitle: Logical
permalink: /technical/logical/
---

# Logical Access to Interfaces

Previously identified by Jeff in an earlier version under Access Control (need to identify where goes in new structure below):

- Ability to control local and remote access to IOT device audit data, to and through the device interfaces.
- Ability to assign IOT device audit controls access to specific roles or organization-define personnel.
- Ability to identify the user, process or device requesting the audit/ accountability information to ensure that only authorized user or device has access to internal information that the audit could require.

## Authentication and Identity Management

- Ability for the IOT device to support and require appropriate authentication.
  - Ability for the IOT device to require authentication prior to connecting to the device.
  - Ability for the IOT device to support a second, or more, authentication method through an out of band path such as:
    - temporary passwords or other one-use logon credentials.
    - third-party credential checks.
    - Biometric
    - Text message
    - Hard Token
  - Ability for the IOT device to hide authentication information during authentication process

- Ability for the IOT device to use authentication controls to set and change authentication configurations, policies and limitations settings.
  - Ability for the IOT device to set the time period for how long the device will remain locked after an established configurable limit of unsuccessful login attempts has been met.
  - Ability for the IOT device to prohibit access to the device after an established pre-defined or user-configurable number of unsuccessful login authentication attempts.
  - Ability for the IOT device to log and view previous date and time of last successful login following successful login authentication.
  - Ability to support automatic disabling of inactive accounts for the IOT device.
    - Ability to support automatic logout of inactive accounts for the IOT device after a configurable established time period.
    - Ability to support automatic removal of temporary, emergency and other special use accounts from the IOT device.

- Ability to display to IOT device users an organization-defined system use notification message or banner prior to successful IOT device authentication.
  - The message or banner would provide privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance.
  - The device should have the ability to keep the notification message or banner on screen until the device user actively acknowledges and agrees to the usage conditions.

- Ability for the IOT device to be able to identify authorized users and processes and restrict all unauthorized interactions.
  - The device should have the ability to remotely differentiate through the logical interface between authorized and unauthorized users (physical and remote).
- Ability to establish access to the IOT device or through IOT device interfaces to perform organization-defined user actions without identification or authentication.

## Role Support and Management

- Ability to assign and identify unique IOT device user accounts.

- Ability to support a hierarchy of logical access privileges for the IOT device based on roles (e.g., admin, emergency, user, local, temporary, etc.)
  - Ability for the IOT device to establish and administer through logical access privileged user accounts to support role-based access.
  - Ability for the IOT device to use organizationally defined roles to define each user&#39;s access and range of permitted actions to a device.
  - Ability to support multiple levels of user/process account functionality and roles for the IOT device.

- Ability to apply least privilege through the IOT device interfaces, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required functions. 
  - Ability to create additional processes, roles, and accounts as necessary, to achieve least privilege.
  - Ability to apply least privilege settings within the device, ensuring that the processes operate at privilege levels no higher than necessary to accomplish required functions.
  - Ability for the IOT device to limit access to the device settings to establish and administer, logically and remotely, authorization requirements to support access controls for users, roles, groups, other devices, etc.
  - Ability for the IOT device user to access privileges settings to establish access privileges through device interfaces.

- Ability to support organization-defined actions for the IOT device.
  - Ability to dynamically create through IOT device interfaces organization-defined accounts that support privileged roles assignment expirations.
  - Ability to establish organization-defined user actions for the device, or to access IOT device interfaces.
  - Ability to allow the user to assign audit controls access to specific roles or organization-define personnel.
  - Ability to establish and administer, logically and remotely, organization pre-defined conditions for the IOT device for establishing shared/group accounts.
  - Ability to restrict the use of shared/group accounts that meet the conditions established for the IOT device.

- Ability to implement within the IOT device dynamic access control approaches (e.g., service-oriented architectures) that rely on:
  - run time access control decisions facilitated by dynamic privilege management.
  - rganization-defined actions to access/use device.

- Ability to provide IOT device settings to allow information sharing capabilities based upon the type of user that is attempting to share the information. 
- Ability to enable automation and reporting of account management activities through IOT device interfaces.
- Ability to provide IOT device settings to establish pre-defined restrictions for information searches within the device or through device interfaces.

## External Connections

- Ability to provide IOT device settings to securely interact with external, third-party systems.
- Ability to provide IOT device settings to allow for the user/organization to establish the circumstances within device settings for when information sharing from the device and/or through the device interface will be allowed and prohibited.
- Ability to provide IOT device settings to establish automated information sharing to identified parties/entities.
- Ability to provide IOT device settings to authorize external users, groups, roles, etc. to identify when the external user&#39;s system meets the required security requirements.

## Interface Control

- Ability to establish requirements for remote access to the IOT device and/or IOT device interface including usage restrictions, configuration and connection requirements.
  - Ability to enforce the established interface local and remote access requirements within the IOT device or through the IOT device interfaces.
- Ability to provide IOT device settings to update logical interface configuration through a network process and control the device&#39;s logical interface through that process.
- Ability to provide IOT device settings to control device responses to input and the form of output from the device.
- Ability to provide IOT device settings and capabilities to support wireless technologies, such as microwave, packet radio (UHF/VHF), 802.11x, and Bluetooth, etc.
  - Ability for user to establish and configure wireless settings within the IOT device for wireless technologies.
  - Ability to prohibit wireless access to the IOT device and/or device interfaces until after successful authorization.

