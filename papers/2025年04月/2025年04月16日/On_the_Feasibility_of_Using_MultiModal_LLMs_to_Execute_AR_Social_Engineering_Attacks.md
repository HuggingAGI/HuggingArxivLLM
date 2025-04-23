# 探讨借助多模态大语言模型实施增强现实社会工程攻击的可能性

发布时间：2025年04月16日

`LLM应用` `增强现实` `网络安全`

> On the Feasibility of Using MultiModal LLMs to Execute AR Social Engineering Attacks

# 摘要

> 增强现实 (AR) 和多模态大型语言模型 (LLMs) 的飞速发展，为人类与计算机的交互开辟了全新可能。然而，它们的结合也为社会工程攻击带来了新的风险。本文首次提出 SEAR 框架，系统性地研究了利用多模态 LLM 协调 AR 驱动的社会工程攻击的可行性。SEAR 框架通过以下三个关键阶段运作：(1) 基于 AR 的社交环境合成，融合视觉、听觉和环境提示等多模态输入；(2) 基于角色的多模态 RAG（检索增强生成），在保持角色差异性的同时动态检索和整合上下文数据；(3) ReInteract 社会工程代理，通过推理交互循环执行自适应多阶段攻击策略。为验证 SEAR 的有效性，我们开展了一项经过 IRB 批准的研究，招募 60 名参与者，分别在无辅助、AR+LLM 和完整 SEAR 流程三种实验配置下，在模拟社交场景中收集了 180 个标注对话的新数据集。研究结果表明，SEAR 在引发高风险行为方面表现出色，例如 93.3% 的参与者容易受到电子邮件钓鱼攻击。该框架在建立信任方面尤为突出，85% 的目标在交互后愿意接受攻击者的电话。同时，我们也发现了一些局限性，如由于感知真实性差距导致的“偶尔人工”现象。本研究不仅为 AR-LLM 驱动的社会工程攻击提供了概念验证，还为开发防御下一代增强现实威胁的对策提供了宝贵见解。

> Augmented Reality (AR) and Multimodal Large Language Models (LLMs) are rapidly evolving, providing unprecedented capabilities for human-computer interaction. However, their integration introduces a new attack surface for social engineering. In this paper, we systematically investigate the feasibility of orchestrating AR-driven Social Engineering attacks using Multimodal LLM for the first time, via our proposed SEAR framework, which operates through three key phases: (1) AR-based social context synthesis, which fuses Multimodal inputs (visual, auditory and environmental cues); (2) role-based Multimodal RAG (Retrieval-Augmented Generation), which dynamically retrieves and integrates contextual data while preserving character differentiation; and (3) ReInteract social engineering agents, which execute adaptive multiphase attack strategies through inference interaction loops. To verify SEAR, we conducted an IRB-approved study with 60 participants in three experimental configurations (unassisted, AR+LLM, and full SEAR pipeline) compiling a new dataset of 180 annotated conversations in simulated social scenarios. Our results show that SEAR is highly effective at eliciting high-risk behaviors (e.g., 93.3% of participants susceptible to email phishing). The framework was particularly effective in building trust, with 85% of targets willing to accept an attacker's call after an interaction. Also, we identified notable limitations such as ``occasionally artificial'' due to perceived authenticity gaps. This work provides proof-of-concept for AR-LLM driven social engineering attacks and insights for developing defensive countermeasures against next-generation augmented reality threats.

[Arxiv](https://arxiv.org/abs/2504.13209)