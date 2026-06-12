---
author: ["Cassandra Pearson"]
title: "Parkerian Hexad"
date: "2026-06-06"
description: "Parkerian Hexad an expansion to the CIA triad."
summary: "An explanation of the Parkerian Hexad's expansion to the CIA triad."
tags: ["security", "cybersecurity"]
series: []
ShowToc: true
TocOpen: true
---

## **Parkerian Hexad**

---

The CIA triad, shown in Figure 1 below, likely[^1] originated in the 1970's as a response to the digitization of physical records [1]. It is a framework that emphasizes three primary security objectives: Confidentiality, Integrity, and Availability. Balancing these three objectives is crucial in maintaining private, secure, and usable systems. While the CIA triad is primarily applied to digital security, the concepts transfer to physical security systems well.

_note: See my previous post on the CIA triad for a more detailed discussion of the topic_

Figure 1: CIA Triad [2]
![CIA Triad](/images/cia_triad.png "CIA Triad")

In the 1990's, cybersecurity began to evolve as a field. Digitization coinciding with the origination of the internet necessitated new technologies and methodologies for securing information. During this time, Donn B. Parker, proposed a new framework to replace the overly simplified CIA framework [3]. It became known as the Parkerian Hexad, shown in Figure 2 below, and adds three new components to the triad: Possession/Control, Authenticity, and Utility.

Figure 2: Parkerian Hexad [4]
![Parkerian Hexad](/images/parkerian_hexad.png "Parkerian Hexad")

The first addition is Possession or Control, which is an expansion to Confidentiality from the CIA triad. Confidentiality focuses on the preservation of authorized accessed to restricted information such as personal or proprietary information. Parker shows there are few important security considerations missed by this narrow definition. For instance, the theft of confidential information without disclosure or observation does not violate confidentiality [3]. Yet, the information is still lost or could potentially be held for ransom. A practice which became common with crypto ransomware in the early 2010's. Both the Petya ransomware and the LastPass breaches are famous examples of this type of loss. Information remained confidential while the attackers possessed it. Parker emphasizes the important of Possession or Control over confidential information within the hexad. Confidentiality on its own is insufficient to cover the modern threat landscape.

The next addition is Authenticity, which acts as an expansion to Integrity. Parker states that integrity focuses on the soundness or state of an object without considering the preservation of content or meaning [3]. For example, hardware degradation could result in a readable data modification. This would not cause a loss of integrity, as all data remains in intact, but a loss of authenticity due to the improper modification. For data to be usable, it must maintain both integrity and authenticity. Further, Parker expands Integrity to cover non-repudiation or the inability of the sender to deny the authenticity of the object. False repudiation of data does not compromise the data's integrity instead it compromises its authenticity. Integrity focuses on the condition of the data while authenticity focuses on the validity [3]. The security controls required for each of these concepts differ and consideration for both is necessary to preserve data in a meaningful and usable manner.

The final addition is Utility, which acts as an expansion to Availability. Availability ensures timely and reliable^[2] access to data [3]. While the data may be available, it fails to consider the state of the data. If the data is improperly formatted or encrypted, the end user will not be able to utilize it. Inability to utilize the data negates its availability. Further, if the format of the data is unusable, then the integrity of the data is meaningless. If all data is intact in a file format that is no longer readable, then the data is lost. Demonstrating that availability is too narrow to account for all modern scenarios.

The Parkerian Hexad is relatively unknown in comparison to the popular CIA triad. The CIA triad is widely taught due to its simplicity and capture of the essential trade offs of security. Perfectly confidential data is useless if no one can access it, accessible data is meaningless if it lacks integrity, and integral data is insecure if it's all public. Parker does not refute the accuracy or usefulness of the CIA triad but instead expands it to cover modern threats and considerations, many of which did not exist during the inception of the CIA triad.

Personally, I find the Parkerian Hexad more applicable to modern information security and threat modeling discussions. The CIA triad, while beneficial, is overly simplified for the internet age. As technology evolves, our model of information security must keep pace. Today's threat landscape is more diverse than ever. Attackers are intelligent, dedicated, observant, and may have substantial resources. We must use a more complete model to keep pace. The Parkerian Hexad is the best proposal I have seen for such a model so far.

## **Sources**

---

[1] Jim Holdsworth and M. Kosinski, “Information Security,” _Ibm.com_, Jul. 26, 2024. https://www.ibm.com/think/topics/information-security

[2] https://i0.wp.com/thecyberthrone.in/wp-content/uploads/2025/06/file_00000000311461f684ba4c98c9c92d2d4829824476695499797.png?resize=1024%2C1024&ssl=11 (accessed Mar. 26, 2026).

[3] Parker, Donn B. “Our Excessively Simplistic Information Security Model and How to Fix It.” _Information Systems Security Association_, vol. 8, no. 7, July 2010, pp. 12–21.

[4] G. Pender-Bey, “THE PARKERIAN HEXAD,” 2019. Available: https://cs.lewisu.edu/mathcs/msisprojects/papers/georgiependerbey.pdf

## **Footnotes**

---

[^1]: There is some disagreement on the origins of the CIA triad. IBM claims to have invented it in the 1970's but there are several competing claims. Some historians go as far as tracing it back to the origins of information security in the Roman Empire.

[^2]: The NIST definition omits the term reliability. Parker assumes reliability is implied. An assumption I generally agree with based on the popular writing on these topics.

### **Copyright Notice**

---

Copyright © 2026 by Cassandra Pearson.
All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the publisher, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law.

### **AI Training Notice**

---

I do not consent to have my work used for training AI. No portion of this work may be used for training artificial intelligence without written permission.
