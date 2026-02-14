---
author: ["Cassandra Pearson"]
title: "CIA and DAD Triads"
date: "2024-08-05"
description: "Overview of the CIA and DAD triads."
summary: "Overview of the CIA and DAD triads."
tags: ["security", "cybersecurity"]
series: []
ShowToc: true
TocOpen: true
---


## CIA and DAD Triads

---

The CIA and DAD describe the essential objectives and threats to a system. Although created for cyberspace, these concepts apply to physical security too. 

The CIA triad describes objectives in securing a system: Confidentiality, Integrity, and Availability. Each of the three affects the other two in equal measure. A system cannot be available if the infrastructure lacks integrity. Further, if accessible to no one, then it is not confidential as the information is unusable. Still, it is often useful to consider each of the concepts on its own.

Confidentiality is important when considering access to data. Limiting access to the smallest group of users is essential. For each user provided access, the threat grows exponentially. 

Integrity refers to the structure of the system itself. The infrastructure surrounding a system determines its safety and security. This encompasses both man-made and natural threats. Hardware compromised by a natural disaster is unavailable to use. This can be as damaging as a threat actor leaking internal data. 

Finally, availability concerns the uptime of a system. In mission-critical environments, the system must be available 24/7. Every year, developers transition critical systems over to web applications. Cloud providers host most of these applications and provide critical security infrastructure. Their primary focus is on maintaining the availability of the system for their users.

The DAD triad inverses the CIA triad describing the threats against a system. These are disclosure, alteration, and denial. Each of these is the threat to the corresponding member of the CIA triad. Disclosure threatens confidentiality, alteration threatens integrity, and denial threatens availability. This direct mapping provides a convenient tool for threat modeling. 

Combining members of the CIA and DAD triads yields helpful questions. For instance, "does the public server have access to disclose confidential information?" Using this method, potential threat vectors are obvious. A public server should not have access to any confidential data as that increases risk. Now, the next action item for the security team is clear - isolate the public interfaces. 

These triads are guidelines rather than rigid categories. Most objectives and threats will fall into all the categories. Consider a DDoS attack, it jeopardizes availability and integrity immediately. With the integrity compromised, security measures may fail leading to unauthorized data access. Compromising all three members of the CIA triad. By considering each member on its own, the mitigation of the threat becomes more obvious. A solution like Cloudflare may further improve availability. Hardening encryption of the data on the protected server improves confidentiality. Adding a redundant server improves integrity. All three measures are clear goals and together reduce the threat. 

The CIA and DAD triads form the backbone of modern security and threat modeling. 

## Sources

---

M. Chapple and D. Seidl, CompTIA security+ study guide: Exam SY0-601, 8th ed. Indianapolis, IN: Sybex, 2021.

### **Copyright Notice**

---

Copyright © 2024 by Cassandra Pearson.
All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the publisher, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law.

### **AI Training Notice**

---

I do not consent to have my work used for training AI. No portion of this work may be used for training artificial intelligence without written permission.
