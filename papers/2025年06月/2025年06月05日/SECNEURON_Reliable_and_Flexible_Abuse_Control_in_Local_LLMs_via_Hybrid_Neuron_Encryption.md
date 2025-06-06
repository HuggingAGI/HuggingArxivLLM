# SECNEURON：本地LLM的可靠滥用防护新方案——混合神经元加密技术

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在本地环境中的安全性和可控性挑战，并提出了一种名为SECNEURON的框架，以防止恶意利用。该研究属于LLMs的应用层面，因为它专注于实际部署和安全防护，而不是模型本身的理论改进。` `人工智能` `计算机安全`

> SECNEURON: Reliable and Flexible Abuse Control in Local LLMs via Hybrid Neuron Encryption

# 摘要

> 具备多样化能力的大型语言模型（LLMs）在本地环境中的广泛应用带来了显著的安全性和可控性挑战。这些本地部署的LLMs由于脱离了开发者的直接控制，更容易遭受恶意利用。现有的防护技术主要针对基于云的LLM服务，在本地部署环境下往往难以奏效或被轻易规避。我们提出SECNEURON，这是首个将经典访问控制机制无缝融入LLMs内在能力的框架，实现了对本地部署LLMs的可靠、经济、灵活且经过认证的滥用防护。

SECNEURON通过神经元级别加密和选择性解密技术，动态调控LLMs的任务特定能力，有效遏制未经授权的任务滥用，同时确保其他功能不受影响。我们设计了任务特定的神经元提取机制，实现逻辑相关神经元的解耦，并构建分层策略树来处理耦合神经元。此外，我们开发了灵活高效的混合加密框架，能够处理LLMs中数百万个神经元。最后，我们在密文基础上创新性地引入了分布式的解密神经元检测机制，确保部分解密后的LLMs仍能保持高效运作。

理论证明显示，SECNEURON在任务可控性原则下，满足IND-CPA安全性和抗共谋安全性。实验结果表明，在多种任务设置下，SECNEURON将未经授权的任务准确率限制在25%以下，同时仅使授权任务的准确率损失2%。以恶意代码生成任务为例，滥用相关准确率从59%显著降至15%。此外，SECNEURON还有效缓解了数据泄露风险，个人身份信息提取率降至5%以下，成员推断结果接近随机猜测水平。

> Large language models (LLMs) with diverse capabilities are increasingly being deployed in local environments, presenting significant security and controllability challenges. These locally deployed LLMs operate outside the direct control of developers, rendering them more susceptible to abuse. Existing mitigation techniques mainly designed for cloud-based LLM services are frequently circumvented or ineffective in deployer-controlled environments. We propose SECNEURON, the first framework that seamlessly embeds classic access control within the intrinsic capabilities of LLMs, achieving reliable, cost-effective, flexible, and certified abuse control for local deployed LLMs. SECNEURON employs neuron-level encryption and selective decryption to dynamically control the task-specific capabilities of LLMs, limiting unauthorized task abuse without compromising others. We first design a task-specific neuron extraction mechanism to decouple logically related neurons and construct a layered policy tree for handling coupled neurons. We then introduce a flexible and efficient hybrid encryption framework for millions of neurons in LLMs. Finally, we developed a distribution-based decrypted neuron detection mechanism on ciphertext to ensure the effectiveness of partially decrypted LLMs. We proved that SECNEURON satisfies IND-CPA Security and Collusion Resistance Security under the Task Controllability Principle. Experiments on various task settings show that SECNEURON limits unauthorized task accuracy to below 25% while keeping authorized accuracy loss with 2%. Using an unauthorized Code task example, the accuracy of abuse-related malicious code generation was reduced from 59% to 15%. SECNEURON also mitigates unauthorized data leakage, reducing PII extraction rates to below 5% and membership inference to random guesses.

[Arxiv](https://arxiv.org/abs/2506.05242)