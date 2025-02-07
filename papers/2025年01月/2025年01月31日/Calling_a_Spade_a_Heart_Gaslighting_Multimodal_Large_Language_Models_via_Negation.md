# 指鹿为马：通过否定操控多模态大型语言模型

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在面对对抗性输入时的表现和脆弱性，特别是针对否定论点的处理能力。论文评估了不同MLLMs在复杂理解和生成任务中的表现，并揭示了这些模型在推理和对齐机制中的关键漏洞。虽然涉及模型的理论分析，但主要关注的是模型在实际应用中的表现和改进，因此归类为“LLM应用”更为合适。` `人工智能` `对话系统`

> Calling a Spade a Heart: Gaslighting Multimodal Large Language Models via Negation

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在整合多种模态方面取得了显著进展，尤其在复杂理解和生成任务中表现出色。然而，MLLMs在面对对话中的对抗性输入，特别是否定论点时，仍显脆弱。本文系统评估了当前最先进的MLLMs在不同基准上的表现，发现当否定论点被引入到原本正确的响应时，模型性能显著下降。我们揭示了这些模型在推理和对齐机制中的关键漏洞。与开源模型如Qwen2-VL和LLaVA相比，专有模型如GPT-4o和Claude-3.5-Sonnet表现出更强的韧性。尽管如此，所有评估的MLLMs在对话中面对否定论点时都难以保持逻辑一致性。本文旨在为提高MLLMs对抗对抗性输入的鲁棒性提供洞见，助力开发更可靠和可信的多模态AI系统。

> Multimodal Large Language Models (MLLMs) have exhibited remarkable advancements in integrating different modalities, excelling in complex understanding and generation tasks. Despite their success, MLLMs remain vulnerable to conversational adversarial inputs, particularly negation arguments. This paper systematically evaluates state-of-the-art MLLMs across diverse benchmarks, revealing significant performance drops when negation arguments are introduced to initially correct responses. We show critical vulnerabilities in the reasoning and alignment mechanisms of these models. Proprietary models such as GPT-4o and Claude-3.5-Sonnet demonstrate better resilience compared to open-source counterparts like Qwen2-VL and LLaVA. However, all evaluated MLLMs struggle to maintain logical consistency under negation arguments during conversation. This paper aims to offer valuable insights for improving the robustness of MLLMs against adversarial inputs, contributing to the development of more reliable and trustworthy multimodal AI systems.

[Arxiv](https://arxiv.org/abs/2501.19017)