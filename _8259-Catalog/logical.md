---
layout: default
title: Logical Access to Interfaces
navOrder: 4
navTitle: Logical
permalink: /technical/logical/
---

# Logical Access to Interfaces

_See also the [non-technical counterpart to this section](../_8259-Control/logical.md)_

## Authentication and Identity Management

Ability to require, or not require, authentication to, and/or identification of, the IOT device, and to establish authentication and identification configuration and display requirements. Configurations that may be necessary: 

- Ability for the IOT device to support and require appropriate authentication.
  - Ability for the IOT device to require authentication prior to connecting to the device.
  - Ability for the IOT device to support a second, or more, authentication method(s) through an out of band path such as:
    - temporary passwords or other one-use logon credentials.
    - third-party credential checks.
    - Biometrics.
    - Text messages.
    - Hard Tokens.
    - Manufacturer proprietary method.
  - Ability for the IOT device to hide or mask authentication information during authentication process
- Ability to set and change authentication configurations, policies and limitations settings for the IOT device .
  - Ability to set the time period for how long the device will remain locked after an established configurable limit of unsuccessful login attempts has been met.
  - Ability to disable or lock access to the device after an established pre-defined or user-configurable number of unsuccessful login authentication attempts.
  - Ability to log successful and unsuccessful login authentications.
  - Ability to display and/or report the previous date and time of the last successful login following successful login authentication.
  - Ability to automatically disable accounts for the IOT device after an establish period of inactivity.
    - Ability to support automatic logout of inactive accounts for the IOT device after a configurable established time period.
    - Ability to support automatic removal of temporary, emergency and other special use accounts from the IOT device after an established time period.
- Ability to display to IOT device users an organization-defined system use notification message or banner prior to successful IOT device authentication. (e.g., the message or banner would provide privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance.)
  - Ability to create an organization-defined system use notification message or banner to be displayed on the IOT device.
  - Ability to keep the notification message or banner on the device screen until the device user actively acknowledges and agrees to the usage conditions.
- Ability for the IOT device to be able to restrict all unauthorized interactions.
  - Ability for the IOT device to be able to identify authorized users and processes.
  - Ability to remotely differentiate through the logical interface between authorized and unauthorized users (physical and remote).
- Ability to establish access to the IOT device to perform organization-defined user actions without identification or authentication.
- Ability to establish access through the IOT device interface to perform organization-defined user actions without identification or authentication.

## Role Support and Management

Ability to establish unique, privileged, organization-wide, and other types of role-based IOT device user accounts. Configurations that may be necessary: 
- Ability to create unique IOT device user accounts.
- Ability to assign roles to IOT device user accounts.
- Ability to identify unique IOT device user accounts.
- Ability to support a hierarchy of logical access privileges for the IOT device based on roles (e.g., admin, emergency, user, local, temporary, etc.)
  - Ability to establish user accounts to support role-based logical access privileges.
  - Ability to administer user accounts to support role-based logical access privileges.
  - Ability to use organizationally defined roles to define each user account's access and permitted device actions.
  - Ability to support multiple levels of user/process account functionality and roles for the IOT device.
- Ability to apply least privilege to user accounts through the IOT device interfaces (to ensure that the processes operate at privilege levels no higher than necessary to accomplish required functions). 
  - Ability to create additional processes, roles, and accounts as necessary to achieve least privilege.
  - Ability to apply least privilege settings within the device (to ensure that the processes operate at privilege levels no higher than necessary to accomplish required functions).
  - Ability to limit access to the device settings that are used to establish and administer, logically and remotely, authorization requirements to support access controls for users, roles, groups, other devices, etc.
  - Ability to access privileges settings to establish access privileges through device interfaces.
- Ability to support organization-defined actions for the IOT device.
  - Ability to dynamically create organization-defined accounts through IOT device interfaces that support privileged roles assignment expirations.
  - Ability to establish organization-defined IOT device user actions and/or device interface access.
  - Ability to enable automation and reporting of account management activities through IOT device interfaces.
    - Ability to assign IOT device audit controls access to specific roles or organization-define personnel.
    - Ability to control local and remote access to IOT device audit data.
    - Ability to identify the user, process or device requesting the audit/accountability information to ensure only authorized users and/or devices have access to internal information that the audit could require.
   - Ability to establish, logically and remotely, organization pre-defined conditions for the IOT device for establishing shared/group accounts.
   - Ability to administer, logically and remotely, organization pre-defined conditions for the IOT device for establishing shared/group accounts.
  - Ability to restrict the use of shared/group accounts that meet the conditions established for the IOT device.
- Ability to implement dynamic access control approaches (e.g., service-oriented architectures) that rely on:
  - run-time access control decisions facilitated by dynamic privilege management.
  - organization-defined actions to access/use device.
- Ability to allow information sharing capabilities based upon the type and/or role of user attempting to share the information. 
- Ability to restrict access to IOT device software, hardware, and data based on user account roles, used with proper authentication of the identity of the user to determine type of authorization.

## Limitations on Device Usage

- Ability to establish pre-defined restrictions for information searches within the device or through device interfaces.
- Ability for the IOT device settings to be used to establish limits on concurrent sessions for accounts, users, roles, groups, etc., with authorized access to the device and/or interfaces with the device.
- Ability for the IOT device settings to be used to establish time, location, and other limits on concurrent sessions to the device.

## External Connections

- Ability to securely interact with external, third-party systems.
- Ability to allow for the user/organization to establish the circumstances within device settings for when information sharing from the device and/or through the device interface will be allowed and prohibited.
- Ability to establish automated information sharing to identified parties/entities.
- Ability to authorize external users, groups, roles, etc. to identify when the external user&#39;s system meets the required security requirements.

## Interface Control

- Ability to establish requirements for remote access to the IOT device and/or IOT device interface including usage restrictions, configuration and connection requirements.
  - Ability to enforce the established interface local and remote access requirements within the IOT device or through the IOT device interfaces.
  - Ability to prevent external access to management interface.
- Ability to update logical interface configuration through a network process and control the device&#39;s logical interface through that process.
- Ability to control device responses to input and the form of output from the device.
- Ability to support wireless technologies, such as microwave, packet radio (UHF/VHF), 802.11x, and Bluetooth, etc.
  - Ability for user to establish and configure wireless settings within the IOT device for wireless technologies.
  - Ability to prohibit wireless access to the IOT device and/or device interfaces until after successful authorization.

