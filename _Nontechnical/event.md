---
layout: default
title: Cybersecurity Event Awareness
navOrder: 7
navTitle: Event
permalink: /nontechnical/event/
---

# Cybersecurity Event Awareness

_See also the [technical counterpart to this section](../_8259-Catalog/event.md)_
{:latex-ignore="true"}

The management and operational controls to support reporting the IoT device cybersecurity state and associated security events within the system where the IoT device is used. Controls that may be necessary:

## Policies and procedures govern malicious code protection.

Policies and procedures provide the details necessary to implement management and operational controls for malicious code protection in the IoT device and associated systems, as well as within related systems entry and exit points, to detect and eradicate malicious code. Controls that may be necessary:

**Manufacturer:**

- Provide information to the IoT device clients/customers that describe the vulnerabilities to malware for the associated IoT devices, and advice for the best types of anti-malware to use. If no anti-malware is needed for the IoT device, explain why.
- Provide information about the IoT device resource restraints related to malicious code protection and possible compensating controls that IoT device customers can use for such restraints.

**Agency:**

- Implement policies and procedures requiring IoT devices, and associated systems, to have malicious code protection mechanisms integrated into IoT devices and related systems entry and exit points that can detect and eradicate malicious code.
- Follow procedures to use IoT device anti--malware tools based upon the types of malware possible to be loaded onto each associated IoT device.
- Establish, or assign to existing, roles within the organization responsibilities for ensuring anti-malware is implemented appropriately within IoT devices used within the organizational systems.

## Policies and procedures govern malicious code protection updates. 

Policies and procedures provide the details necessary to implement management and operational controls for how to update IoT device and related systems malicious code protection mechanisms when new releases are available, in accordance with organizational configuration management policy and procedures. Controls that may be necessary:

**Manufacturer:**

Provide information to the IoT device clients/customers that describe newly identified vulnerabilities for malware for the associated IoT devices.

**Agency:**

- Implement policies and procedures to govern how to update IoT device and related systems malicious code protection mechanisms whenever new releases are available, in accordance with organizational configuration management policy and procedures.
- Require the appropriate roles to subscribe to available notifications for anti-malware updates from the manufacturer or the software provider, as appropriate.

## Policies and procedures govern malicious code protection configurations.

Policies and procedures provide the details necessary to implement management and operational controls for how to configure malicious code protection mechanisms in IoT devices and related systems. Controls that may be necessary:

**Manufacturer:**

- If the IoT device manufacturer provides anti-malware for the associated IoT device, or if the IoT device has built-in anti-malware capabilities, the manufacturer should provide documentation to the IoT device customers describing:
  - How to schedule automatic scanning on the IOT device.
  - How to perform real-time scanning for new files introduced through the IoT device interfaces.
  - How to block and/or quarantine malicious code to allow for inspection of that code by customer organizational roles with those responsibilities.
  - How to configure the IoT device to shut-down upon detecting malicious code, as appropriate to the purpose of the IoT device.
- Provide information to IoT device customers describing the operational impacts of the anti-malware activities on mission critical processes in the system where the IoT device is used.
  - Provide additional information on recommended responses to malware beyond just shutting down the IoT device.
  - Provide options for responding to malicious code identification within the IoT device. Some examples: shutting down, redirecting the network traffic, sending alerts, logging the events, etc.

**Agency:**

Implement policies and procedures to govern how to configure malicious code protection mechanisms in IoT devices and related systems to:
- Perform periodic scans of the IoT devices and associated systems on an ongoing basis.
- Perform real-time scans of files from external sources at IoT device interfaces, and associated systems entry/exit points, as the files are downloaded, opened, or executed in accordance with organizational security policies.
- Block and/or quarantine malicious code and send an alert to the organization administrator, as well as shutting down the IoT device if appropriate, in response to malicious code detection.

## Policies and procedures for malicious code detection and eradication.

Policies and procedures provide the details necessary to implement management and operational controls for malicious code detection and eradication. Controls that may be necessary:

**Manufacturer:**

- If the IoT device manufacturer provides anti-malware tools for the associated IoT device, or if the IoT device has built-in anti-malware capabilities, the manufacturer should:
  - Document how the IoT device user should address false positives and report the false positives to the manufacturer.
  - Document the possible availability and functioning impacts on the associated IoT device and the system within which it is implemented.

**Agency:**

- Implement policies and procedures to perform periodic scans of the IoT devices and related systems, and real-time scans of files from external sources as the files are downloaded, opened, or executed in accordance with the organizational security policy.
- Implement policies and procedures to block malicious code; quarantine malicious code; and send alerts to admin roles.
- Implement policies and procedures governing how to identify and respond to malware false positives for IoT devices, and how to identify and resolve any potential impacts to the associated IoT device and associated systems.
- Implement policies and procedures establishing how to address the receipt of false positives during IoT device and associated systems malicious code detection and eradication, and the resulting potential impact on the availability of the IoT device and associated systems.

## Policies and procedures for information system monitoring.

Policies and procedures provide the details necessary to implement management and operational controls for how to monitor IoT devices and associated systems. Controls that may be necessary:

**Manufacturer:**

- Provide documentation to IoT device customers:
  - Describing all the ways in which the IoT device can be monitored, and the recommended associated tools to perform monitoring.
  - Describing the indicators of attacks on the IoT device.
  - Describing how to identify local, network and remote IoT device access attempts and connections.
  - Describing expected behavior of the normal operation of the IoT device. 
  - Describe IoT device behavior indicators that could occur when an attack is being launched.

**Agency:**

- Establish or assign to existing roles within the organization responsibilities for monitoring access to IoT devices and associated systems, identifying suspicious and malicious access, and for reacting appropriately.
- Establish policies and procedures to monitor IoT devices and associated systems to detect:
  - Attacks and indicators of potential attacks in accordance with organizationally-defined monitoring policies and objectives.
  - Unauthorized local, network, and remote IoT device, and associated systems, connections.

## Policies and procedures to identify unauthorized use.

Policies and procedures provide the details necessary to implement management and operational controls for how to identify unauthorized use of IoT devices and their associated systems, in accordance with the organizationally-defined techniques and methods. Controls that may be necessary:

**Manufacturer:**

- Provide documentation to the IoT device customers that describes indicators of unauthorized use of the IoT device.

**Agency:**

- Establish or assign to existing roles within the organizational responsibilities for identifying unauthorized use of IoT devices and associated systems and for reacting appropriately.
- Implement policies and procedures to establish how to identify unauthorized use of IoT devices and their associated systems, in accordance with the organizationally-defined techniques and methods.

## Policies and procedures for monitoring devices and tools.

Policies and procedures provide the details necessary to implement management and operational controls for how to deploy monitoring devices and tools for IoT devices and associated systems. Controls that may be necessary:

**Manufacturer:**

- Provide documentation to the IoT device customers describing how to best implement and secure the IoT device and associated systems monitoring.

**Agency:**

- Establish or assign to existing organizational roles responsibilities for monitoring use of IoT devices within the organization.
- Implement policies and procedures to govern how to deploy monitoring of IoT devices and associated systems to collect organizationally-defined essential information:
  - Strategically within IoT devices.
  - In information systems where IoT devices are used.
- Implement policies and procedures to govern how to deploy monitoring of IoT devices and associated systems in ad hoc locations to track specific types of transactions of interest to the organization.

## Policies and procedures for protecting cybersecurity event information from unauthorized access, modification, and deletion.

Policies and procedures provide the details necessary to implement management and operational controls for protecting information obtained from IoT devices, and associated systems and intrusion-monitoring tools, from unauthorized access, modification, and deletion. Controls that may be necessary:

**Manufacturer:**

- Provide documentation to IoT device customers describing the types of usage and environmental systems data that can be collected from the IoT device.

**Agency:**

- Establish or assign to existing organizational roles responsibilities for collecting, securing and analyzing organizationally-defined data of interest from IoT devices and associated systems.
- Develop policies and procedures to establish the requirements for protecting information from unauthorized access, modification, and deletion that was obtained from IoT devices and associated systems using intrusion-monitoring tools.

## Policies and procedures for security level changes.

Policies and procedures provide the details necessary to implement management and operational controls to govern when to heighten the level of security for an IoT device and associated systems. Controls that may be necessary:

**Manufacturer:**

- Provide documentation to IoT device customers describing the security controls and monitoring capabilities built within the IoT device, and how to configure the device to best fit the risk levels within the systems where they are used.

**Agency:**

- Establish policies and procedures to govern when to increase the level of security for an IoT device and associated systems, including for monitoring activity, whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information.

## Policies and procedures for ensuring legal compliance.

Policies and procedures provide the details necessary to implement management and operational controls for establishing whether the IoT device, and associated systems, monitoring activities are in compliance with applicable Federal laws, Executive Orders, directives, policies, and regulations. Controls that may be necessary:

**Manufacturer:**

- Provide the legal (Federal regulations, state and local laws) requirements for security and privacy controls that the IoT device supports. Some examples: Federal Information Security Modernization Act (FISMA), Health Insurance Portability and Accountability Act (HIPAA), California Consumer Privacy Act (CCPA), EU General Data Protection Regulation(GDPR).

**Agency:**

- Establish policies and procedures for determining if the monitoring activities for IoT devices and associated systems are in compliance with applicable Federal laws, Executive Orders, directives, policies, and regulations.

## Policies and procedures for providing monitoring information to authorized personnel or roles.

Policies and procedures provide the details necessary to implement management and operational controls for how to provide organizationally-defined IoT device and associated systems monitoring information to authorized personnel or roles as needed and according to organizationally-defined frequencies. Controls that may be necessary:

**Manufacturer:**

- Provide IoT device customers documentation describing the types of monitoring tools with which the IoT device is compatible, and recommendations for how to configure the IoT device to best work with such monitoring tools.

**Agency:**

- Establish policies and procedures to govern how to provide organizationally-defined IoT device and associated systems monitoring information to authorized personnel or roles as needed and according to organizationally-defined frequencies.

## Policies and procedures for receiving external security alerts, advisories, and directives.

Policies and procedures provide the details necessary to implement management and operational controls for how and when to receive up-to-date security and privacy information on an ongoing basis about IoT devices and associated systems, such as information system security alerts, advisories, and directives from IoT device manufacturers, information security researchers, and other sources the organization determines to be valuable. Controls that may be necessary:

**Manufacturer:**

- Provide documentation to the IoT device customers about related security and privacy updates, such as IoT device information system security and privacy alerts, advisories, directives, security and/or privacy research, and other information that would be valuable for IoT device customers to help ensure security and privacy of the IoT device.

**Agency:**

- Establish policies and procedures to govern how and when to receive up-to-date security and privacy information on an ongoing basis about IoT devices and associated systems, such as information system security alerts, advisories, and directives from IoT device vendors, information security researches, and other sources the organization determines to be valuable.

## Policies and procedures for receiving internal security alerts, advisories, and directives.

Policies and procedures provide the details necessary to implement management and operational controls for when and how to generate internal security alerts, advisories, and directives about the IoT devices. Controls that may be necessary:

**Manufacturer:**

- Provide necessary information to customers to inform the review and update of the IoT device systems and services practices.  

**Agency:**

- Establish policies and procedures to govern when and how to generate internal security alerts, advisories, and directives about the IoT devices, and associated systems, used within the organization as deemed necessary.

## Policies and procedures for disseminating privacy and security alerts, advisories, and directives outside of the organization.

Policies and procedures provide the details necessary to implement management and operational controls to disseminate privacy and security alerts, advisories, and directives about the IoT devices, and associated systems outside of the organization. Controls that may be necessary:

**Manufacturer:**

- Provide necessary information to IoT device customers to inform the review and update of the IoT device systems and services practices.

**Agency:**

- Establish policies and procedures to disseminate privacy and security alerts, advisories, and directives about the organizational IoT devices, and associated systems to appropriate organizationally-defined personnel and roles, and to organizationally-defined external organizations.

## Policies and procedures for implementing security control directives.

Policies and procedures provide the details necessary to implement management and operational controls to govern the implementation of IoT device and associated systems security directives in accordance with established time frames, and/or to notify the IoT device manufacturer and/or vendor of the degree of noncompliance. Controls that may be necessary:

**Manufacturer:**

- Provide directions and procedures to IoT device customers for how to submit questions and requests for information about their IoT device related to security and privacy compliance requirements. Some examples: Federal Information Security Modernization (FISMA), Health Insurance Portability and Accountability Act (HIPAA), California Consumer Privacy Act (CCPA), EU General Data Protection Regulation(GDPR). 
- Include a timeframe within which such IoT device compliance questions and requests will be answered.

**Agency:**

- Establish policies and procedures to govern the implementation of IoT devices and associated systems security directives in accordance with established compliance requirements, including time frames, and/or notices to the IoT device manufacturers and/or vendors of the degree of noncompliance.

