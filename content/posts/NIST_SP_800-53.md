---
author: ["Cassandra Pearson"]
title: "NIST SP800-53 Security and Privacy Controls"
date: "2024-09-21"
description: "NIST SP800-53 Security and Privacy Controls for Information Systems and Organizations"
summary: "NIST SP800-53 Security and Privacy Controls summary."
tags: ["security", "cybersecurity", "nist"]
series: ["NIST"]
ShowToc: true
TocOpen: true
---

## **Introduction**

---

NIST SP800-53 details the controls discussed in SP800-37 and SP800-39. I recommend familiarizing yourself with them before continuing. SP800-53 differs from the previous two publications by focusing on the security controls. A departure from the risk management framework(RMF)'s focus on organizational structure. This document acts as a reference for implementation of the controls described. Providing information about when to apply the control. Further including a discussion of the control, related controls, and sources. Referencing this document ensures the full control is in place. It is easy to overlook the detailed compensating and accompanying controls. This post is a guide for utilizing this document as a reference; providing context and background information.

Sources are cited below, original article available free of charge [here](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf).

## **Purpose of Publication**

---

Quoting the publication: 

"This publication establishes controls for systems and organizations. The controls can be implemented within any organization or system that processes, stores, or transmits information."[1]

This document provides details on common security controls within information systems.

## **Control Structure and Example**

---

Each control within the document is assigned a category referred to as a family. "Security and privacy controls may involve aspects of policy, oversight, supervision, manual processes, and automated mechanisms that are implemented by systems or actions by individuals. Table 1 lists the security and privacy control families and their associated family identifiers."[1]

![NISTSP80053_1](/images/NIST80053_table1.png "NIST SP800-53 Table 1")

When implementing a security control, consider if there are necessary accompanying base controls. Diving controls up into families helps in this effort. When any control is desired, closely related controls exist in the family. Allowing for a quick check if the desired control is a base or enhancement. In practice, this shows if the desired control is sufficient alone. 

Every control uses the structure from the diagram below [1]. The structure is self-explanatory but should be considered in detail. First, the identifier; made up of the family designation and a number. Allowing users to quickly find closely related controls. Next, the organization-defined parameters. These parameters differ based on the risk management strategy and resources allocated by the implementing organization. Finally, the related controls sections. Providing a list of closely related controls that may be compensating or enhancing.

![NISTSP80053_2](/images/NIST80053_example1.bmp "NIST SP800-53 Example 1")

Now that the general structure is known, consider the following access control policy[1]:

![NISTSP80053_3](/images/NIST80053_example2.bmp "NIST SP800-53 Example 2")

As highlighted, the organizational parameters used throughout have a substantial effect. Still, the description is information rich and useful as a guide to all organizations. With references to best practices and RMF documents to determine organizational parameter values. 

## **Conclusion**

---

Although not a technical guide on use of the tools of the trade, NIST800-53 is a practical guide for security controls. Each control is described in detail and discussed thoroughly. The only component missing is the technical "how" of applying the control. Which varies based on the information system structure and resources. All organizations should compare these controls with their documented controls. 

## **Sources**

---

[1] Joint Task Force Interagency Working Group, “Security and privacy controls for information systems and organizations,” National Institute of Standards and Technology, 2020.

## **Acronym Dictionary**

---

IR: Interagency Report
OMB: Office of Management and Budget
NIST: National Institute of Standards and Technology
SP: Special Publication