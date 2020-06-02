---
layout: default
title: Cybersecurity Event Awareness
navOrder: 6
navTitle: Event
permalink: /technical/event/
---

# Cybersecurity Event Awareness

_See also the [non-technical counterpart to this section](../_8259-Control/event.md)_

## Access to Event Information

Ability to access IOT device state information.  Configurations that may be necessary: 
- Ability to access information about the IOT device&#39;s cybersecurity state and other necessary data (e.g., trustworthy time).
- Ability to preserve system state information.

## Event Identification and Monitoring

Ability for device to provide event identification and monitoring capabilities and/or support interfaced event identification and monitoring tools interfacing with the device, and take specific actions based upon specific types of events. Configurations that may be necessary: 
- The device can identify organizationally defined cybersecurity events (e.g., expected state change) that may occur on or involving the IOT device.
- The device can monitor for organizationally defined cybersecurity events (e.g., expected state change) that may occur on or involving the IOT device.
- Ability to support a list of events that are necessary for auditing purposes (to support the organizational auditing policy).
- Ability to monitor for organizationally defined cybersecurity events.
- Ability for the IOT device to identify unique users interacting with the device (to allow for user session monitoring).
- Ability to support a monitoring process to check for disclosure of organizational information to unauthorized entities. (The device may be able to perform this check itself or provide the information necessary for an external process to check).
- Ability to monitor communications traffic.
- Ability to detect remote activation attempts.
- Ability to detect remote activation of a collaborative computing device.
- Ability to detect remote activation of sensors.
- Ability to define the characteristics of unacceptable content.
- Ability to prevent download of unacceptable content.

## Event Response

The device can respond to organizationally defined cybersecurity events in an organizationally defined way. Configurations that may be necessary:
  - Ability to generate alerts for specific events (e.g., capacity thresholds).
  - Ability to respond to alerts according to predefined responses (e.g., such as those dictated by the auditing policies of the organization).
  - Ability to alert connected information systems of potential issues found during the auditing process.
  - Ability to provide information to an external process that will issue auditing process alerts.
  - Ability to notify users of activation of the collaborative computing device.
  - Ability to provide a physical indicator of sensor use.
  - Ability to respond following an auditing failure according to the alert that was issued (either by the device or and external auditing process that interacts with the device).

## Audit Support

Ability for the device, or an interfaced system, to generate, store, retain, delete, and report on specific device audit events, to run specific audit checks, and report findings in a variety of ways. Configurations that may be necessary: 
- The device can generate audit logs for defined events
  - Ability to identify and capture organization-defined events using a persistent method that can be reviewed later.
  - Ability to provide information related to organization-specified cybersecurity events (e.g., cybersecurity state, timestamp) through organizationally defined means (e.g., logs).
  - Ability to create audit logs within the device for organization-defined and auditable events (e.g. account creation, modification, enabling, disabling, removal actions and notifications).
  - Ability to audit organization-defined and auditable events (e.g. account creation, modification, enabling, disabling, and removal actions and notifications) that are logged within the device and through device interfaces.
- The device can capture required information in audit logs
  - Ability to track users interacting with the device, the time they interacted with the device, the time the user logged out of the device, and to list this information in an audit log
  - Ability to identify the location where organizationally defined events occurred, to support locating the source of the event, the time the event occurred, and the outcome of the event if there is one.
  - Ability to log information pertaining to: 
      - The type of event that occurred, 
      - The time that the event occurred, 
      - Where the event occurred, 
      - The source of the event, 
      - The outcome of the event, 
      - Identity of users/processes associated with the event.
  - Ability to support auditing of configuration actions.
  - Ability to provide adequate information as to why the device captured a particular event or set of events.
  - Ability to provide as much information as necessary for examination of security incidents. <== NOTE: This needs to be written in a way that can be engineered. Include a list of the items needed? Something else?
  - Ability to record IOT device stored data access and usage.
- Ability to maintain audit logs in accordance with organization policy.
  - Ability to store persistent audit logs up to a predefined size established by the user/organization.
  - Ability to establish the storage capacity for retaining audit logs that supports the predefined amount of time.
  - Ability to comply with organizational procedures for how long audit logs must be kept and the size limits.
  - Ability to establish retention length of time to retain audit records (to support organizationally defined policies).  
  - Ability to establish audit record length limits.
  - Ability to delete audit logs.
  - Ability to send alerts that the logs are too big for the device to continue to store if the predefined amount of time has not yet passed to delete them.
- Ability to use timestamps to record the time an auditing event occurred.
  - Ability to support specified granularity in device timing measurements as predefined by the IOT device user.
  - Ability to use synchronization with a verified time source to determine the validity of a timestamp.
  - Ability to record timestamps that can be translated to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) to support a standardized representation of timing.
  - Ability to log timing measurements that go beyond a set threshold value enabling alerts if the device's system time is too far out of sync to be reliable.
- Ability for the device can provide information related to cybersecurity events (using organizationally defined means).
- Ability to report on device cybersecurity state.
- Ability to provide the specifically chosen audit information to the information system.
- Ability to run audit scans (automated or otherwise) to provide specific information (e.g., such as that requested for an external process to audit the device).
- Ability to share data in some way with other system entities participating in the auditing process. (It could possibly need to be able to reveal the results of its own event captures to an external auditing process by another device.)
- Ability to provide specific types of audit information to an (potentially automated) audit reduction process (e.g., where its auditing information can be checked to allow for review, analysis, and reporting.)
- Ability for the IOT device to provide requested information to an external process in a way that provides all possible requested information.
- Ability to support an self-audit generation process for the information system.
- Ability to send requested audit logs to an external audit process.
- Ability to support an alternate auditing process in the event that the primary auditing process fails.
- Ability to protect the audit information provided to the information system through the use of:
  - Encryption
  - Data signing audit files
  - Other access control protections created by the device manufacturer