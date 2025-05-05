# 无线电指纹识别中协议无关且无需数据的预训练模型后门攻击

发布时间：2025年05月01日

`其他` `通信技术` `人工智能`

> Protocol-agnostic and Data-free Backdoor Attacks on Pre-trained Models in RF Fingerprinting

# 摘要

> 尽管监督式深度神经网络（DNNs）在射频指纹识别（RF fingerprinting）用于设备认证方面表现出色，但它们面临着领域迁移问题和标注数据匮乏的挑战。大型语言模型的成功推动了无监督预训练模型（PTMs）的研究热潮，这类模型凭借出色的泛化能力且无需标注数据，有望解决上述难题。然而，PTMs在射频指纹识别中的固有安全漏洞仍未被充分探索。本文聚焦于攻击者无法获取下游数据、标签信息及训练过程的现实场景，深入研究了射频指纹识别中PTMs的无数据后门攻击。通过精心设计触发器和预定义输出表示（PORs），并在后门训练中将二者进行映射，我们成功将后门行为植入PTMs，从而在不同下游射频指纹识别任务中制造漏洞，且无需任何先验知识。实验结果表明，我们的攻击方法在多种输入域、协议和PTMs中具有广泛应用前景。此外，我们还探索了潜在的检测与防御策略，揭示了全面抵御此类后门攻击的难度。

> While supervised deep neural networks (DNNs) have proven effective for device authentication via radio frequency (RF) fingerprinting, they are hindered by domain shift issues and the scarcity of labeled data. The success of large language models has led to increased interest in unsupervised pre-trained models (PTMs), which offer better generalization and do not require labeled datasets, potentially addressing the issues mentioned above. However, the inherent vulnerabilities of PTMs in RF fingerprinting remain insufficiently explored. In this paper, we thoroughly investigate data-free backdoor attacks on such PTMs in RF fingerprinting, focusing on a practical scenario where attackers lack access to downstream data, label information, and training processes. To realize the backdoor attack, we carefully design a set of triggers and predefined output representations (PORs) for the PTMs. By mapping triggers and PORs through backdoor training, we can implant backdoor behaviors into the PTMs, thereby introducing vulnerabilities across different downstream RF fingerprinting tasks without requiring prior knowledge. Extensive experiments demonstrate the wide applicability of our proposed attack to various input domains, protocols, and PTMs. Furthermore, we explore potential detection and defense methods, demonstrating the difficulty of fully safeguarding against our proposed backdoor attack.

[Arxiv](https://arxiv.org/abs/2505.00881)