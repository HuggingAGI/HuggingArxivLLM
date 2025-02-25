# OCCULT：评测大型语言模型的网络攻击能力

发布时间：2025年02月18日

`LLM应用` `网络安全`

> OCCULT: Evaluating Large Language Models for Offensive Cyber Operation Capabilities

# 摘要

> AI 在网络安全领域的竞技前景长期被视为最具影响力、挑战性和潜在风险的 AI 应用之一。我们提出了一种评估 AI 进展的新方法，旨在助力并规模化现实世界中现代威胁行为者所使用的进攻性网络操作 (OCO) 技术。我们介绍了轻量级操作评估框架 OCCULT，它让网络安全专家能够参与对任何大型语言模型 (LLM) 或用于 OCO 的 AI 可能带来的网络安全风险的严格且可重复测量。我们设计并评估了三个不同的 LLM OCO 基准测试，以展示我们的方法并作为在 OCCULT 框架下构建基准的示例。初步评估结果显示，该框架超越了传统的非此即彼测试（如基于夺旗环境等教育性练习的测试），将指标和警告置于真正存在针对现代基础设施风险的网络威胁场景中。我们发现，AI 被用于规模化现实网络威胁的风险近期显著提升。首次发现 DeepSeek-R1 模型能够正确回答我们针对 LLM 的威胁行为者能力测试 (TACTL) 多选基准测试中超过 90% 的具有挑战性的进攻性网络知识测试。Meta 的 Llama 和 Mistral 的 Mixtral 模型系列在我们的基准测试中相较于早期模型展现了显著性能提升，其中 LLM 作为进攻性代理在 MITRE 的高保真网络攻防模拟环境 CyberLayer 中表现。

> The prospect of artificial intelligence (AI) competing in the adversarial landscape of cyber security has long been considered one of the most impactful, challenging, and potentially dangerous applications of AI. Here, we demonstrate a new approach to assessing AI's progress towards enabling and scaling real-world offensive cyber operations (OCO) tactics in use by modern threat actors. We detail OCCULT, a lightweight operational evaluation framework that allows cyber security experts to contribute to rigorous and repeatable measurement of the plausible cyber security risks associated with any given large language model (LLM) or AI employed for OCO. We also prototype and evaluate three very different OCO benchmarks for LLMs that demonstrate our approach and serve as examples for building benchmarks under the OCCULT framework. Finally, we provide preliminary evaluation results to demonstrate how this framework allows us to move beyond traditional all-or-nothing tests, such as those crafted from educational exercises like capture-the-flag environments, to contextualize our indicators and warnings in true cyber threat scenarios that present risks to modern infrastructure. We find that there has been significant recent advancement in the risks of AI being used to scale realistic cyber threats. For the first time, we find a model (DeepSeek-R1) is capable of correctly answering over 90% of challenging offensive cyber knowledge tests in our Threat Actor Competency Test for LLMs (TACTL) multiple-choice benchmarks. We also show how Meta's Llama and Mistral's Mixtral model families show marked performance improvements over earlier models against our benchmarks where LLMs act as offensive agents in MITRE's high-fidelity offensive and defensive cyber operations simulation environment, CyberLayer.

[Arxiv](https://arxiv.org/abs/2502.15797)