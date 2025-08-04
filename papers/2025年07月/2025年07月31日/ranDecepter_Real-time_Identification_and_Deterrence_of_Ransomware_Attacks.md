# # ranDecepter：实时识别并威慑勒索软件攻击

发布时间：2025年07月31日

`其他` `网络安全` `信息安全`

> ranDecepter: Real-time Identification and Deterrence of Ransomware Attacks

# 摘要

> 勒索软件（RW）作为数字世界中的重大威胁，亟需有效的应对策略。主动网络欺骗技术通过误导勒索软件传播并揭示其真实行为，成为一项有潜力的解决方案。此外，勒索软件常作为攻击者与防御者之间的通信桥梁，使得欺骗技术能够向攻击者反馈虚假信息，从而耗尽其资源。本文提出了一种名为ranDecepter的创新方法，它将主动网络欺骗与实时分析相结合，以增强防御勒索软件攻击的能力。该方法能够实时识别勒索软件，并将其隔离在欺骗环境中。通过自主识别勒索软件代码中的关键要素，ranDecepter创建了一个循环机制。通过不断重启恶意软件并传输虚假加密信息及秘密密钥给攻击者，它迫使攻击者为每位受害者存储这些伪造的细节，从而耗尽其资源。我们使用1,134个真实恶意软件样本和十二个良性应用程序对ranDecepter进行了全面评估，结果显示其在勒索软件识别方面达到了惊人的100%准确率，无误报，且对响应时间的影响极小。此外，仅使用50个代理，ranDecepter在24小时内就能在攻击者的数据库中生成多达9,223K条记录，展示了其潜在的资源耗尽攻击者的能力。

> Ransomware (RW) presents a significant and widespread threat in the digital landscape, necessitating effective countermeasures. Active cyber deception is a promising strategy to thwart RW and limiting its propagation by misleading it with false information and revealing its true behaviors. Furthermore, RW often acts as a communication conduit between attackers and defenders, allowing deception to return false data to attackers and deplete their resources. This paper introduces ranDecepter, a novel approach that combines active cyber deception with real-time analysis to enhance defenses against RW attacks. The ranDecepter identifies RW in real-time and isolates it within a deceptive environment, autonomously identifying critical elements in the RW code to create a loop mechanism. By repeatedly restarting the malware and transmitting counterfeit encryption information and secret keys to the attacker, it forces the attacker to store these fabricated details for each victim, thereby depleting their resources. Our comprehensive evaluation of ranDecepter, conducted using 1,134 real-world malware samples and twelve benign applications, demonstrates a remarkable 100% accuracy in RW identification, with no false positives and minimal impact on response times. Furthermore, within 24-hours, ranDecepter generates up to 9,223K entries in the attacker's database using 50 agents, showcasing its potential to undermine attacker resources.

[Arxiv](https://arxiv.org/abs/2508.00293)