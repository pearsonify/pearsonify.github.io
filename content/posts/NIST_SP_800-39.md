---
author: ["Cassandra Pearson"]
title: "NIST SP800-39 Managing Information Security Risk"
date: "2024-10-10"
description: "NIST SP 800-39 Managing Information Security Risk: Organization, Mission, and Information System View"
summary: "NIST SP 800-39 Managing Information Security Risk summary"
tags: ["security", "cybersecurity", "nist"]
series: ["NIST"]
ShowToc: true
TocOpen: true
---

## **Introduction**

---

The National Institute of Standards and Technology (NIST) maintains important publications about risk management and security. Furthering its mission to promote innovation and industrial competitiveness[1]. Special publication (SP) 800-39 'Managing Information Security Risk: Organization, Mission, and Information System View' is one of the most notable. The target audience is any individual or organization associated with the design, development, implementation, assessment, operation, maintenance, and disposition of information systems [2].  The focus is on providing guidance for an integrated, organization wide program of managing information security risk. Applying to all organizational operations (function, image, and reputation)[2]. Expaning upon the risk management framework (RMF) described in NIST SP800-37 'Risk Management Framework for Information Systems and Organizations: A System Life Cycle Approach for Security and Privacy'. I preivously summarized NIST SP800-37. I recommend becoming familiar with that article before continuing.

Sources are cited below, original article available free of charge [here](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-39.pdf).

## **Purpose of Publication**

---

Quoting the publication: 

"The purpose of Special Publication 800-39 is to provide guidance for an integrated, organization-wide program for managing information security risk to organizational operations (i.e., mission, functions, image, and reputation), organizational assets, individuals, other organizations, and the Nation resulting from the operation and use of federal information systems. Special Publication 800-39 provides a structured, yet flexible approach for managing risk that is intentionally broad-based, with the specific details of assessing, responding to, and monitoring risk on an ongoing basis provided by other supporting NIST security standards and guidelines."[2]

This document provides details on the NIST RMF from an organizational risk perspective. Focusing less on the specific tasks and organizational structure than SP800-37. But expanding on the general ideas and principles behind the RMF. This document includes: information on the tasks within each tier of the RMF, details on specific terms and functions (i.e. risk executive and enterprise architecture), and information on risk management strategies. Providing means for practical implementation of the RMF's concepts.

## **Fundamentals and Organizational Architecture**

---

The three tier model introduced in NIST SP800-37 includes arrows showing the flow of communication among components. The terms changed slightly from NIST800-37. Tiers become levels, but the concept is the same[3]. To review this model, consider figure 2. 

![NISTSP80039_Figure2](/images/NIST80039_Fig2.bmp "NIST SP800-39 Figure 2")

Summary of the tiers in figure 2:
- Organization
	- This tier focuses on governance and program-related risk management[1]. Preparing the organization to execute the RMF[3]. Here, important decisions linked to the business objectives, system modernization, enterprise architecture, and resource allocation are made. The primary responsibilities are: to understand risk, to assign roles, to identify critical functions, and to prioritize security requirements. 
- Mission/Business Process
	- This level focuses on the business or mission objectives. Such as defining the criticality of information flow between the organization and its partners [1]. Although related to level one, the focus is information flow, communication, and assigning task criticality. 
- Information System
	- This level defines the risk to information technology. Where risk to physical and digital information becomes less organizational and more practical.
In figure 2 above, the arrows are not shown to be bidirectional indicating information flow. There is a continuous feedback loop for risk management policies and strategies. The organizational decisions on strategic risk are made transparently by the stakeholders within the organizational tier. While tactics used to address the risk, based on the resources allocated at the strategic level, are left to the stakeholders at the information system tier.

The following diagram (figure 1) describes the communication between tiers. The bidirectional nature of the arrows indicates that the information and communication flows are flexible. Allowing for the dynamic nature of this process.[2]

![NISTSP80039_Figure1](/images/NIST80039_Fig1.png "NIST SP800-39 Figure 1")

There are four components that describe the communication between the levels of an organization[1]:
1. Frame risk
	- Defines the context for all risk activities. What are the constraints of the system? What are the organizational priorities?
2. Assess risk
	- The most critical aspect. Assessment of risks is continuous, thorough, and show awareness of the threat landscape.
3. Respond to risk
	- In responding, the threat and acceptable scope of response are apparent. Resources are allocated to stop the critical and likely threats.
4. Monitor risk
	- No system is perfect, no assessment can cover all threats. Monitoring for new threats is an ongoing process. As is monitoring the effectivity of existent controls.

Combining figures 1 and 2, results in figure 4[2]. Demonstrating how each tier is responsible for communication and feedback within the organization.

![NISTSP80039_Figure4](/images/NIST80039_Fig4.png "NIST SP800-39 Figure 4")

Stakeholders decide the risk management strategy for operations to carry through. Decisions filter through several levels before put into place. The enterprise architecture communicates with information security architecture. Finally, communicating the technical security controls to operations. 

The enterprise architecture is a management practice employed by organizations. Maximizing the effectiveness of mission/business processes and information resources [2]. 

The information security architecture is a part of the enterprise architecture. Specifically addressing information system resilience. Providing architectural information for the implementation of security controls [2]. 

Finally, information security controls are the technical components.  The following diagram (figure 3) shows risk management considerations as part of the enterprise architecture [2].

![NISTSP80039_Figure3](/images/NIST80039_Fig3.png "NIST SP800-39 Figure 3")


Figure 3 describes how a risk management strategy decision made at tier 1 flows into operation at tier 3. Traveling through the enterprise architecture of an organization. The strategy and mission inform the enterprise architecture. Allowing for the information security architecture to create requirements and allocate resources. Resulting in the technical security control in the operation environment.

## **Conclusion**

---

NIST SP800-39 provides details on the organizational concepts and structures within the RMF. Focusing less on the stakeholder and tasks, instead providing methods to determine and address risk. This summary provides only a very broad conceptual outline. Omitting tasks and guidance for carrying out each step discussed in figure 1. The publication goes into detail on each of the RMF tiers. As well as related concepts such as establishing trust. This publication clarifies the concepts and ideas behind the NIST RMF. Allowing for operations staff to process the RMF.

## **Sources**

---

1. B. Chapman and F. Maymi, CompTIA CySA+ cybersecurity analyst certification all-in-one exam guide, second edition (exam CS0-002), 2nd ed. Columbus, OH: McGraw-Hill Education, 2020.
2. Joint Task Force Transformation Initiative, “Managing information security risk  :: Organization, mission, and information system view,” National Institute of Standards and Technology, Gaithersburg, MD, 2011.
3. Joint Task Force Transformation Initiative, “Risk management framework for information systems and organizations:: A system life cycle approach for security and privacy,” National Institute of Standards and Technology, Gaithersburg, MD, 2018.

## **Acronym Dictionary**

---

NIST: National Institute of Standards and Technology
RMF: Risk Management Framework
SP: Special Publication

### **Copyright Notice**

---

Copyright © 2024 by Cassandra Pearson.
All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the publisher, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law.

### **AI Training Notice**

---

I do not consent to have my work used for training AI. No portion of this work may be used for training artificial intelligence without written permission.
