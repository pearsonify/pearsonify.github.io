---
author: ["Cassandra Pearson"]
title: "Kerckhoff's Principles"
date: "2026-06-05"
description: "The principles of ciphers."
summary: "Fundamental principles of ciphers and cryptography."
tags: ["cryptography", "math"]
series: []
ShowToc: true
TocOpen: true
---

## **Kerckhoff's Principles**

---

_note: I will be translating any references, names, or information from the original French into English. I apologize if my translations are inaccurate, please submit any feedback on GitHub if you find errors._

In 1883, Auguste Kerckhoff published an article in the Journal of Military Science (_Journal des sciences militaires_) titled "Military Cryptography" (_La Cryptographie Militaire_) covering his six principles of military ciphers [1]. Today, these principles form the foundation of modern electronic cryptography. Here are six principles in full:

Kerckhoff's Principles (Translated from French) [2]
1. The system must be substantially, if not mathematically, undecipherable;
2. The system must not require secrecy and can be stolen by the enemy without causing trouble;
3. It must be easy to communicate and retain the key without the aid of written notes, it must also be easy to change or modify the key at the discretion of the correspondents;
4. The system ought to be compatible with telegraph communication;
5. The system must be portable, and its use must not require more than one person;
6. Finally, given the circumstances in which such system is applied, it must be easy to use and must neither stress the mind or require the knowledge of a long series of rules.

While all six principles remain relevant, the second is foundational. An adversary with a full understanding of the system should not be able to compromise an individual cipher. This means both the system utilized for encryption as well as the encrypted message could be communicated publicly without any un-intended recipient deciphering the message. Obscurity is not security and privacy will not secure a message.

In modern cryptography, we meet the standard of the second principle using problems that are only solvable with certain pieces of information; most often, the discrete log problem. Thousands work on breaking modern cryptosystems every day utilizing decades of public work and discussion. Yet, the security of encrypted information remains. Mistakes in procedure or bugs in management cause more decryptions than mathematical compromise. The public discourse around the systems causes continual improvements in security and reliability. None of which would be possible if Kerckhoff's second principle did not hold.

_note: See my post on the discrete log problem for a thorough discussion._

The first principle provides the goal for ciphers - keep the information secret. This is the only item on the list that I find lacking a component. There are two goals for all ciphers that are particularly relevant in the digital age. Keep the information secret and intact. Partial or corrupted transmission of the message renders the information useless or worse - dangerous. All modern cryptosystems accomplish both goals.

The third principle focuses on the portability and maintenance of the system. The first piece states: "It must be easy to communicate and retain the key without the aid of written notes." This is vital for all cryptographic systems. The users of the system should maintain access over the key in a portable manner. It is possible to store the information and full key together while maintaining secrecy through a password or passphrase. Thus maintaining this principle. The second piece states: "It must also be easy to change or modify the key at the discretion of the correspondents." While the second portion remains important, it should always be _possible_ to change the key, it is not required that it is _easy_ in all cases. Modern at rest symmetric cryptography requires substantial effort to change the key but the information remains secure. While in public key or asymmetric cryptosystems, changing the key is a trivial action. This piece of the principle remains important but does not apply equally to all cases.

The remaining three principles, 4-6 in the above list, require some modernization. Here are my modified versions of the principles:
4. The system ought to be compatible with digital systems;
5. It must be possible to automate and transfer the system, further its use must not require more than one person;
6. Finally, given the circumstances in which such system is applied, it must be easy to use, safe to install, and friendly for non-technical users to operate.
   I changed each of the principles to account for the digital revolution. Principle 4 states that these systems should be digitally compatible. Most modern systems are exclusively digital. A user cannot perform the calculations required in any reasonable fashion. All analog discussion of cryptography is through the lens of modern mathematical theory. Principle 5 states that the system should be portable and usable by a single user. Any modern cryptosystem should be transferrable between computers or across networks. If a system is not  available, then it is not usable. Finally, principle 6 states that the system should be easy to use. Digital tools for cryptography accomplish this goal. Further, for a system to be safe and secure, the tool should be transparent in its operations and preferably open source. Allowing for any individual to interrogate, investigate, and modify the tool to ensure their privacy and security. All three of these principles remain not only relevant but vital today.

The influence of these principles on modern information systems cannot be understated. These principles form the foundation for the secure transfer of information. All secure cryptosystems follow these rules and any future systems will as well.

## **Sources**

---

[1] A. Kerckhoffs, “La cryptographie militaire,” _Journal des sciences militaires_, vol. IX, pp. 5–38.

_note: Full article available online in both English and French_

[2] “The information hiding homepage,” _The information hiding homepage_, 2020. https://www.petitcolas.net/kerckhoffs/index.html (accessed Mar. 27, 2026).

### **Copyright Notice**

---

Copyright © 2026 by Cassandra Pearson.
All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the publisher, except in the case of brief quotations embodied in critical reviews and certain other noncommercial uses permitted by copyright law.

### **AI Training Notice**

---

I do not consent to have my work used for training AI. No portion of this work may be used for training artificial intelligence without written permission.