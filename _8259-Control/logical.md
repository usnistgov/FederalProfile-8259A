---
layout: default
title: Logical Access to Interfaces
navOrder: 5
navTitle: Logical
permalink: /nontechnical/logical/
---

# Logical Access to Interfaces

_See also the [technical counterpart to this section](../_8259-Catalog/logical.md)_

The management and operational controls to support secure IoT device interface capabilities according to the requirements established by the organization.

## Policies and procedures for access control capabilities.

Policies and procedures provide the details necessary to implement management and operational controls to support the organizational access control requirements on IoT devices. Controls that may be necessary:

**Manufacturer:**

- Provide information to IoT device customers describing the needs the manufacturer will have to access the IoT device interfaces for support, updates, ongoing maintenance, etc.
- Provide documentation to IoT device customers describing any requirements for the manufacturer to collect data from the IoT devices.
- Provide documentation with instructions for IoT device users to following describing how to restrict interface connections to specific activities.
- Provide descriptions of the types of access to the device the manufacturer will require on an ongoing or regular basis prior to purchase and/or implementation.
  - Guidance: Examples of the types of IoT devices that the manufacturers would typically need access to include, but are not limited to: medical devices, smart refrigerators, HVAC, maintenance data, etc.

**Agency:**

- Establish policies and procedures to govern the implementation of the organizational access control requirements on IoT devices.
- Establish policies and procedures for:
  - Using discovery tools to identify IoT devices implemented within the system;
  - Governing how IoT devices are reported to the agency before integration within the system is allowed;
  - Steps to follow for how the agency looks for stray and unauthorized devices that have been implemented within the network.
- Establish the roles responsible for implementing authorized IoT devices within the system.
- Provide training for how to securely establish the interfaces and connections to the manufacturer for any requirements from the manufacturer requiring such connections.
- Establish right-to-audit clauses within IoT device manufacturers contracts where periodic or ongoing access to the IoT devices is required.

## Policies and procedures for situations where identification and authentication are not needed.

Policies and procedures provide the details necessary to implement management and operational controls to support the organizational requirements for determining circumstances when identification and authentication are not needed to be used with IoT devices for specified organization-defined user actions.

**Manufacturer:**

- Provide a description of the privacy protection capabilities built within the IoT device, such as encryption, authentication, access control, data deletion, etc., to use on devices that do not require authentication.
- Provide a description for how to access the device through the interface without authentication, as applicable to the purpose of the device. For example, when visitors should be able to access certain IoT devices without needed to authenticate, such as when asking for where a doctor's office is within a health clinic.

**Agency:**

- Establish policies and procedures describing:
  - The roles that can use the IoT device without identification and authentication.
  - Situations where the IoT device can be used by anyone, and roles do not need to be defined. 
    -Example: a National Park IoT device where visitors are able to ask questions, and then the IoT device provides answers. The identity of the person asking is not collected (a privacy control), but the question itself may be logged/recorded to determine topic interests.
- Establish policies and procedures describing when certain features can be used for the IoT device without authorization by a role or individual. 
  - For example, using a smart coffee maker in an agency's break room.
  - Include within the policies and/or procedures a description of the compensating controls necessary in such situations, such as the need to be physically present for the use of the IoT device, the requirement to lock the door after normal business hours to the room where the device is located, etc.

## Policies and procedures for managing role-based access controls.

Policies and procedures provide the details necessary to implement management and operational controls in situations where access controls are not necessary on an individual basis, but are based on the role of the IoT device user. For example:
  - Anyone within the office can use the smart coffee maker as part of a "general use" type of role, but only those within the "admin" type of role can modify the smart coffee maker settings.
  - A device can be configured to allow anyone with access to the device to view information in a public space, e.g., a public kiosk. However, the device has an "admin" type of role that allows only those within that role to make changes to the device.
  
Controls that may be necessary:

**Manufacturer:**

- Provide a description of the role-based access capabilities built within the IoT device, such as admin, general user, etc.
- Provide instructions for how to establish and changed role-based access settings.
- Provide a description of the role-based access capabilities of the IoT device. If this capability is not available through the IoT device, document this limitation.

**Agency:**

- Establish policies and procedures describing:
  - The roles that can use IoT devices without using authorization;
  - Situations where IOT devices can be used by anyone, and roles do not need to be defined. For example: A National Park IoT device where visitors are able to ask questions, and then the IoT device provides answers. The identity of the person asking is not collected (a privacy control), but perhaps the question itself is logged/recorded to determine topic interests.
- Establish policies and procedures describing situations when specified features can be used for the IoT device without authorization by a role or individual.
  - For example, turning on a smart coffee maker in an agency's break room.
  - Include within the policies and/or procedures a description of the compensating controls necessary in such situations, such as the need to be physically present for the use of the IOT device; such as needing to be physically at the coffee maker to turn the coffee maker on.

## Policies and procedures for including security and privacy requirements in third party contractual agreements.

Policies and procedures provide the details necessary to implement management and operational controls for including security and privacy requirements within third party contractual agreements that involve access to, and/or use of, IoT devices by third parties. Controls that may be necessary:

**Manufacturer**

- Include within IoT customer contracts a description and listing of the third parties used by the manufacturers that will have access to the IoT device and/or the data collected, generated, accessed, processed, or shared through the device, and a description of the associated security and privacy controls established for such third parties.
- Provide documentation detailing all the cloud services used to support the use of the IoT device.
- Describe all logical interfaces to the IoT device and document the interfaces used by the manufacturer's third parties, and the purposes for such uses.
- Communicate to IoT device customers:
  - A list of the third parties to whom the manufacturer provides IoT device data and/or customer information, and 
  - The types of data provided to the third parties directly by the device (e.g., device usage, entities using the device, device location, personal data, etc.).
- Describe other types of devices, systems, etc., that will be accessing the manufacturer&#39;s IOT device during customer use of the device, and how they will be accessing it (using static IP addresses, etc.).
- Provide documentation, in contracts, disclosures and/or similar types of documents, for the actions the manufacturer will take for requested modification of interface capabilities, and describe how device customers should make such requests.
- Describe how the IoT device customers will be notified of changes in the manufacturer's contractors and third parties that have access to the IoT devices, when the origination or locations (e.g., city, state, country) of the contractors or third parties change, and other related types of contractor and third-party changes.
- Describe the methods by which the manufacturer prevents unauthorized access to the customer's IoT device by third parties not listed on the provided documentation.
- Describe how third parties are, or can be, prohibited from accessing the IoT device and/or restricted in their access to the device.
- Provide documentation describing the expected or typical lifespan of the IoT device, and the associated support that will be provided for the device manufacturer during this time.
- Disclose to Federal agencies how the IoT device supports FedRAMP requirements.

**Agency:**

- Establish policies and procedures governing the security and privacy requirements that must be included in the manufacturer's third-party contractual agreements that involve access to, and/or the use of, the IoT devices by third parties
- Establish policies and procedures:
  - Describing the risk evaluation requirements and practices for requested IoT devices, and descriptions for how risk levels will be established for the level of risk the device brings into the system. NOTE: Often the IoT devices will be used within large systems built for the government, so the interface to the IoT device within the system will need to be used based on the risk levels within the system, and for the risk the IoT device presents to the system.
  - Detailing the documentation requirements for third-party disclosure of IOT device use and data from the manufacturer, and the required types of security and privacy reviews of those disclosures and the related manufacturer documentation to collect that describe those disclosures, that must be performed by each agency.
  - Detailing the acceptable and unacceptable types of contractors (based upon related risk factors such as data use, location of the contractors, etc.), and the acceptable and unacceptable types of data sent out from the device (e.g., personal data, intellectual property, data impacting homeland security, etc.).
  - Detailing any requirements for the IoT device manufacturer to ensure they are using FedRamp-approved cloud service providers for their back-end cloud service platform.
  - Details for working with IoT device manufacturers on possible modification of IoT device interface capabilities for the agency considering use of the manufacturer's IoT device.
  - Details for implementing compensating controls for IoT devices used that do not have IoT device manufacturer support for IoT device interface software, firmware or hardware.
- Establish policies and procedures to perform a cost/benefit analysis prior to implementing the IoT device.
- Establish policies and procedures to verify the existence of disaster recovery policies and procedures within the IoT device manufacturer's practices and documentation. Such disaster recovery documentation should include:
  - Descriptions of existing dependencies on third parties
  - Restrictions obtaining documentation about third party dependencies
- Listings of acceptable and unacceptable contractors and other types of third parties.

## Policies and procedures for device interface controls.

Policies and procedures provide the details necessary to implement management and operational controls for the necessary logical and remote access IoT device controls through device interfaces for information transmission between devices and subjects, objects, systems and components within the system. Controls that may be necessary:

**Manufacturer:**

- Provide documentation describing IoT device logical and remote interface access controls.
- Describe how access to the interface can be restricted in terms of both users of the interface and data that can be transmitted through that interface, and on what basis restrictions can be defined.
- Disclose the manufacturer's own policies governing how they share the data obtained from the manufacturer's IoT device.

**Agency:**

- Establish policies and procedures:
  - Governing risk evaluation for IoT devices, including how risk levels will be established for the risks the device brings into the system.
  - Establishing the required documentation from IoT device manufacturers for the available logical and remote interface access controls, and the required controls to allow usage of the IoT device within agency systems.
  - Describing the acceptable and unacceptable types of data that can be sent through each IoT device interface, and the controls that need to be implemented to meet the restrictions.
  - Governing how to work with manufacturers on possible modifications of interface controls for IOT devices.
  - Establishing the requirements for role-based access controls for specific types of Iot data.
  - Governing the types of compensating controls that should be use when an IoT device manufacturer will not make changes or provide support for IoT device interfaces to support necessary security controls.

## Policies and procedures for required IoT control techniques. 

Policies and procedures establish the capabilities necessary to support required IoT control techniques, such as PIV authentication. Controls that may be necessary:

**Manufacturer:**

- Discloses to IoT device customer details about the IoT device interface controls, and descriptions for if and how a second factor for authentication can be implemented.

**Agency:**

- Policies and procedures require strong IoT device authenticators, which are documented and maintained.
- IoT device requirements will include the following, as applicable to each situation:
  - Defining roles that require a second factor for authentication, and defining situations when a second factor must be a PIV or a PIV-derived credential.
  - Descriptions of the available logical and remote interface access controls for second factor authentication from IoT device manufacturers that must be reviewed by specified agency roles.
  - Descriptions of the compensating controls to use if PIV card readers or use of a PIV-derived credential is not possible.
