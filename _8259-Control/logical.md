---
layout: default
title: Logical Access to Interfaces
navOrder: 5
navTitle: Logical
permalink: /nontechnical/logical/
---

# Logical Access to Interfaces

**Organizational Policies and Procedures**

## Policies &amp; procedures govern the implementation of the organizational access control requirements on IOT devices.

**Manufacturer:**

- Provide information to IOT device customers describing the needs the manufacturer will have to access the IOT device interfaces for support, updates, ongoing maintenance, etc.
- Provide documentation to IOT device customers describing any requirements for the manufacturer to collect data from the IOT devices.
- Provide documentation with instructions for IOT device users to following describing how to restrict interface connections to specific activities.
- Provide descriptions of the types of access to the device the manufacturer will require on an ongoing or regular basis prior to purchase and/or implementation.

 NOTE: Examples of the types of IOT devices that the manufacturers would typically need access to include medical devices, smart refrigerators, HVAC, maintenance data, etc.

**Agency:**

- Establish policies and procedures to govern the implementation of the organizational access control requirements on IOT devices.
- Establish policies and procedures for:
  - Using discovery tools to identify IOT devices implemented within the system;
  - Governing how IOT devices are reported to the agency before integration within the system is allowed;
  - Steps to follow for how the agency looks for stray and unauthorized devices that have been implemented within the network.
- Establish the roles responsible for implementing authorized IOT devices within the system.
- Provide training for how to securely establish the interfaces and connections to the manufacturer for any requirements from the manufacturer requiring such connections.
- Establish right to audit clauses within IOT device manufacturers contracts where periodic or ongoing access to the IOT devices is required.

_ **NOTE TO MYSELF: See if there is documentation of an information security plan that shows the controls manufacturers with ongoing access are required to do.** _

**Support for Role Based Access Control**

## Policies and procedures establish the reasons and circumstances for when identification and authorization are not needed to be used with IOT devices for specified organization-defined user actions.

**Manufacturer:**

- Provide a description of the privacy protection capabilities built within the IOT device, such as encryption, authentication, access control, data deletion, etc.
- Provide a description for how to access device through the interface without authentication, as applicable to the purpose of the device. For examples, for when visitors should be able to access certain IOT devices without needed to authenticate, such as asking for where a doctor&#39;s office is within a health clinic.

**Agency:**

- Establish policies and procedures describing:
  - The roles within the agency that can use IOT devices without using authorization;
  - Instances where IOT devices can be used by anyone, and roles do not need to be defined. For example: A National Park IOT device where visitors are able to ask questions, and then the IOT device provides answers. The identity of the person asking is not collected (a privacy control), but perhaps the question itself is logged/recorded to determine topic interests.
- Establish policies and procedures describing when certain features can be used for the IOT device without authorization by a role or individual.
  - For example, using a smart coffee maker in an agency&#39;s break room.
  - Include within the policies and/or procedures a description of the compensating controls necessary in such situations, such as the need to be physically present for the use of the IOT device.

## Policies and procedures establish the situations where access controls are not necessary on an individual basis, but are based on the role of the IOT device user. For example:
  - Anyone within the office can use the smart coffee maker as part of a &quot;general use&quot; type of role, but only those within the &quot;admin&quot; type of role can modify the smart coffee maker settings.
  - A device can be configured to all anyone with access to the device to view information in a public space, e.g., a public kiosk. However, the device has an &quot;admin&quot; type of role that allows only those within that role to make changes to the device.

**Manufacturer:**

- Provide a description of the role-based access capabilities built within the IOT device, such as admin, general user, etc.
- Provide instructions for how to establish and changed role-based access settings.
- Provide a description of the role-based access capabilities of the IOT device. If this capability is not available through the IOT device, document this limitation.

**Agency:**

- Establish policies and procedures describing:
  - The roles that can use IOT devices without using authorization;
  - Instances where IOT devices can be used by anyone, and roles do not need to be defined. For example: A National Park IOT device where visitors are able to ask questions, and then the IOT device provides answers. The identity of the person asking is not collected (a privacy control), but perhaps the question itself is logged/recorded to determine topic interests.
- Establish policies and procedures describing when certain features can be used for the IOT device without authorization by a role or individual.
  - For example, turning on a smart coffee maker in an agency&#39;s break room.
  - Include within the policies and/or procedures a description of the compensating controls necessary in such situations, such as the need to be physically present for the use of the IOT device; such as needing to be physically at the coffee making to turn the coffee maker on.

## Establish the security and privacy requirements to include in third party contractual agreements that involve access to, and use of, IOT devices by third parties.

**Manufacturer**

- Include within IOT customer contracts a description and listing of the third parties used by the manufacturers that will have access to the IOT devices and/or the data collected, generated, accessed, processed, or shared through the devices, and a description of the associated security and privacy controls established for such third parties.
- Provide documentation detailing all the cloud services used to support the use of the IOT device.
- Describe all logical interfaces to the IOT device and document the interfaces used by the manufacturer&#39;s third parties, and the purposes for such uses.
- Communicate to IOT device customers the third parties to whom the manufacturer provides IOT device data and/or customer information, and the types of data is provided to the third parties directly by the device (e.g., about the device use, the people using the devices, location, personal data, info).
- Describe other types of devices, systems, etc., that will be accessing the manufacturer&#39;s IOT device during customer use of the device, and how they will be accessing it (using static IP addresses, etc.).
- Provide documentation, in contracts, disclosures or similar types of documents, for what the manufacturer will do regarding possible requested modification of interface capabilities, and describe how device customers should make such requests.
- Describe how the IOT device customers will be notified of changes in the manufacturer&#39;s contractors and third parties with access to the IOT devices, when the origination or locations of the contractors or third parties change, and other related types of contractor and third-party changes.
- Describe the methods by which the manufacturer prevents unauthorized access to the customer&#39;s IOT device by other third parties.
- Describe how third parties can be prohibited from accessing the IOT device and/or restricted in their access to the device.
- Provide documentation describing the expected or typical lifespan of the IOT device, and the associated support that will be provided for the device manufacturer during this time.
- Disclose to Federal agencies how the IOT device supports FedRAMP requirements.

**Agency:**

- Establishpolicies and procedures governing the security and privacy requirements that must be included in the manufacturers&#39; third-party contractual agreements that involve access to, and use of, the IOT devices by third parties
- Establish policies and procedures:
  - Describing the risk evaluation requirements and practices for requested IoT devices, and descriptions for how risk levels will be established for the level of risk the device brings into the system. Often the IOT devices will be used within large systems built for the government, so the interface to the IOT device within the system will need to be used based on the risk levels within the system, and for the risk the IOT device presents to the system.
  - Detailing the documentation requirements for third-party disclosure of IOT device use and data from the manufacturer, and the required types of security and privacy reviews of those disclosures and the related manufacturer documentation to collect that describe those disclosures, that must be performed by each agency.
  - Detailing the acceptable and unacceptable types of contractors (based upon related risk factors such as data use, location of the contractors, etc.), and the acceptable and unacceptable types of data sent out from the device (e.g., personal data, intellectual property, data impacting homeland security, etc.).
  - Detailing any requirements for the IoT device manufacturer to ensure they are using FedRamp approved Cloud Service Providers for their back-end cloud service platform.
  - For working with IOT device manufacturers on possible modification of IOT device interface capabilities for the agency considering use of their IOT device.
  - For implementing compensating controls for IOT devices used that do not have IOT device manufacturer support for IOT device interface software, firmware or support.
- Establish policies and procedures to perform a cost/benefit analysis prior to implementing the IOT device.
- Establish policies and procedures to verify the existence of disaster recovery policies and procedures within the IOD device manufacturer&#39;s practices and documentation. Such disaster recovery documentation should include:
  - Descriptions of existing dependencies on third parties
  - Restrictions obtaining documentation about third party dependencies
- Listings of acceptable and unacceptable contractors and other types of third parties.

**Policies about Device Controls**

## Policies and procedures establish the necessary logical and remote access IOT device controls through device interfaces for information transmission between devices and subjects, objects, systems and components within the system.

**Manufacturer:**

- Provide documentation describing IoT device logical and remote interface access controls.
- Describe how access to the interface can be restricted in terms of both users of the interface and data that can be transmitted through that interface and on what basis restrictions can be defined.
- Disclose the manufacturer&#39;s own policies governing how they share the data obtained from the manufacturer&#39;s IOT device.

**Agency:**

Implement policies and procedures:

- Governing risk evaluation policy for IoT devices, including how risk level will be established for the level of risk the device brings into the system.
- Establishing the required documentation from IOT device manufacturers the available logical and remote interface access controls, and the acceptable controls to allow within agency systems.
- Describing the acceptable and unacceptable types of data that can be sent through each IOT device interface, and the controls need to be implemented to meet the restrictions.
- Governing how to work with manufacturers on possible modifications of interface controls for IOT devices.
- Establishing the requirements for role-based access controls for specific types of data.

Governing the types of compensating controls that should be use when an IOT device manufacturer will not make changes or provide support for IOT device interfaces to support necessary security controls.

## Policies &amp; procedures establish the capabilities necessary to support required IOT control techniques such as PIV Authentication.

**Manufacturer:**

Discloses to IOT device customer details about the controls the IoT device has for the interface, and describes if and how a second factor for authentication can be implemented.

**Agency:**

- Policies and procedures require strong authenticators, which are documented and maintained.
- IOT device requirements will include the following, as applicable to each situation:

- Defining roles that require a second factor for authentication and defining when that second factor must be PIV or a PIV-derived credential.
- Descriptions of the available logical and remote interface access controls for second factor authentication from IOT device manufacturers that appropriate agency roles must review
- Descriptions of the compensating controls to use if PIV card readers or use of a PIV-derived credential is not possible.
