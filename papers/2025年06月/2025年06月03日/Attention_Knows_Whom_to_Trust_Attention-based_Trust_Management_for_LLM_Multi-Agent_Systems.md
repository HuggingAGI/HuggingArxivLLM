# 注意力机制懂得该信任谁：基于注意力机制的LLM多智能体系统信任管理

发布时间：2025年06月03日

`LLM应用` `多智能体系统` `可信度管理`

> Attention Knows Whom to Trust: Attention-based Trust Management for LLM Multi-Agent Systems

# 摘要

> 基于大型语言模型的多智能体系统 (LLM-MAS) 虽然在复杂任务中表现出色，但面对不可靠信息时仍显脆弱。其根本原因在于：LLM 智能体未能评估消息可信度，将所有信息同等对待。现有研究虽关注可信度问题，却仅针对单一类型的有害信息，缺乏多维度的全面分析。为解决这一问题，我们提出了注意力信任评分 (A-Trust)，一种轻量级、基于注意力机制的消息可信度评估方法。受人类交流文献[1]启发，通过系统分析六个正交信任维度上的注意力行为，我们发现 LLM 中某些注意力头专门用于检测特定类型的违规行为。基于这些发现，A-Trust 直接从内部注意力模式中推断可信度，无需外部提示或验证器。在此基础上，我们为 LLM-MAS 开发了一个原理清晰且高效的可信度管理系统 (TMS)，支持消息级和智能体级的可信度评估。实验结果表明，应用我们的 TMS 能够显著提升系统对恶意输入的鲁棒性。

> Large Language Model-based Multi-Agent Systems (LLM-MAS) have demonstrated strong capabilities in solving complex tasks but remain vulnerable when agents receive unreliable messages. This vulnerability stems from a fundamental gap: LLM agents treat all incoming messages equally without evaluating their trustworthiness. While some existing studies approach the trustworthiness, they focus on a single type of harmfulness rather than analyze it in a holistic approach from multiple trustworthiness perspectives. In this work, we propose Attention Trust Score (A-Trust), a lightweight, attention-based method for evaluating message trustworthiness. Inspired by human communication literature[1], through systematically analyzing attention behaviors across six orthogonal trust dimensions, we find that certain attention heads in the LLM specialize in detecting specific types of violations. Leveraging these insights, A-Trust directly infers trustworthiness from internal attention patterns without requiring external prompts or verifiers. Building upon A-Trust, we develop a principled and efficient trust management system (TMS) for LLM-MAS, enabling both message-level and agent-level trust assessment. Experiments across diverse multi-agent settings and tasks demonstrate that applying our TMS significantly enhances robustness against malicious inputs.

[Arxiv](https://arxiv.org/abs/2506.02546)