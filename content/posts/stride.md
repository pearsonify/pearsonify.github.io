---
author: ["Cassandra Pearson"]
title: "STRIDE Threat Model"
date: "2026-06-07"
description: "Explanation of the STRIDE threat model."
summary: "An explanation of the STRIDE threat model."
tags: ["security", "cybersecurity"]
series: []
ShowToc: true
TocOpen: true
---

## **STRIDE Threat Model**

---

Threat modeling is the proactive practice of analyzing potential risks and threats while utilizing a system or application for active identification and mitigation [1]. Threat modeling focuses on analyzing the weaknesses in a system from the point of view of an attacker to reduce risk. This process results in a list of threats as well as their priority. Allowing for teams to meaningfully reduce risk by addressing the most prevalent and pervasive threats first.

There are many threat modeling frameworks worth exploring. I will focus on the STRIDE model today but encourage readers to explore alternatives such as PASTA, LINDDUN, and RRA. The STRIDE threat modeling framework is a systematic approach used to identify and analyze potential threats and vulnerabilities within a software system [1]. STRIDE is somewhat broad for a threat modeling framework. Other models, such as Mozilla's RRA, focus on smaller software components. Despite the broader scope of STRIDE, I find it captures the threats to the security properties laid out in the CIA triad and Parkerian Hexad.

_note: See my posts on the CIA Triad and Parkerian Hexad for more detailed discussions of the topics.

STRIDE stands for Spoofing, Tampering, Repudiation, Information disclosure, Denial of service, and Elevation of privilege. Each piece of the acronym represents a common threat to one of the key properties of security. Figure 1, below, shows each property, the corresponding threat, as well as an example of the threat [2].

Figure 1: STRIDE Model Chart [2]
![STRIDE Table](/images/STRIDE.png "STRIDE Table")

To implement STRIDE (or most other threat models), there are a few simple steps. First, gather the target system information including the name, description, data utilized, scope of interaction, and workflows [1]. While doing so, collect any available information regarding the organization and system data flow. Next, identify the key stakeholders [1]. It is crucial to understand those who work on and with the system to maintain the system function while ensuring its security. Finally, identify threats against the system using the STRIDE model as a guide. This could be accomplished through Confluence, written reports, or meetings with the security team and stakeholders. After walking through each of the STRIDE threats and documenting it, order them by risk and impact to create a mitigation plan. Repeat the process to ensure the system remains up to date with the current threat landscape.

Threat modeling is essential for maintaining the security of information system and services. Without consideration of the current threat landscape for a system, it is impossible to adequately prepare security. Modeling threats and creating tailored mitigation plans reduces the total resource cost of security while ensuring the system is safe against the highest risk attack vectors. Security teams should regularly re-model the threats against their systems to ensure they stay up to date.

Personally, I recommend STRIDE as a starting point for anyone looking into threat modeling. While simplified compared to other modern methodologies, it focuses on the key security properties applicable to digital and physical security environments. Further, I recommend teams create their own threat models based on information from their system logs and open source intelligence on the advanced persistent threats (APTs) in their industry.

## **Sources**

---

[1] “CMS Threat Modeling Handbook | CMS Information Security and Privacy Program,” _Cms.gov_, 2024. https://security.cms.gov/learn/cms-threat-modeling-handbook

[2] M. Security, “STRIDE chart,” _Microsoft Security Blog_, Sep. 11, 2007. https://www.microsoft.com/en-us/security/blog/2007/09/11/stride-chart/

### **Copyright Notice**

---

Copyright © 2026 by Cassandra Pearson.
All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the publisher, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law.

### **AI Training Notice**

---

I do not consent to have my work used for training AI. No portion of this work may be used for training artificial intelligence without written permission.
