# MEraser：针对大型语言模型的指纹消除有效方法

发布时间：2025年06月14日

`LLM应用` `知识产权保护` `网络安全`

> MEraser: An Effective Fingerprint Erasure Approach for Large Language Models

# 摘要

> 大语言模型（LLMs）在各行业的广泛应用引发了对模型所有权和知识产权保护的广泛关注。虽然基于后门的指纹识别技术为模型认证提供了有前景的解决方案，但如何有效去除这些指纹仍是一个未被充分探索的领域。因此，我们提出了Mismatched Eraser（MEraser），一种从LLMs中有效去除基于后门指纹的同时保持模型性能的创新方法。我们的方法采用两阶段微调策略，通过精心构建的不匹配数据集和干净数据集实现。经过在多种LLM架构和指纹识别方法上的全面评估，我们发现MEraser仅需少于1,000个样本的少量训练数据，即可实现完整的指纹识别去除，同时保持模型性能。此外，我们还引入了一种可迁移擦除机制，无需重复训练即可在不同模型间实现有效的指纹识别去除。综上所述，我们的方法为LLMs中的指纹识别去除提供了实用解决方案，揭示了现有指纹识别技术的关键漏洞，并为未来开发更具韧性的模型保护方法奠定了全面的评估基准。

> Large Language Models (LLMs) have become increasingly prevalent across various sectors, raising critical concerns about model ownership and intellectual property protection. Although backdoor-based fingerprinting has emerged as a promising solution for model authentication, effective attacks for removing these fingerprints remain largely unexplored. Therefore, we present Mismatched Eraser (MEraser), a novel method for effectively removing backdoor-based fingerprints from LLMs while maintaining model performance. Our approach leverages a two-phase fine-tuning strategy utilizing carefully constructed mismatched and clean datasets. Through extensive evaluation across multiple LLM architectures and fingerprinting methods, we demonstrate that MEraser achieves complete fingerprinting removal while maintaining model performance with minimal training data of fewer than 1,000 samples. Furthermore, we introduce a transferable erasure mechanism that enables effective fingerprinting removal across different models without repeated training. In conclusion, our approach provides a practical solution for fingerprinting removal in LLMs, reveals critical vulnerabilities in current fingerprinting techniques, and establishes comprehensive evaluation benchmarks for developing more resilient model protection methods in the future.

[Arxiv](https://arxiv.org/abs/2506.12551)