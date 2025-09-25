# PEPS：量子启发强化学习助力大型语言模型（LLMs）生成连贯推理轨迹

发布时间：2025年09月24日

`强化学习` `基础理论`

> PEPS: Quantum-Inspired Reinforcement Learning for Coherent Reasoning Traces in LLMs

# 摘要

> 大型语言模型（LLMs）在多步推理追踪的连贯性上常显乏力，尤其在需要结构化逻辑流程的任务中表现突出。为此，本研究提出一种受量子启发的新方法：将源自投影纠缠对状态（PEPS）的保真度奖励整合到近端策略优化中，以应对这一挑战。不同于以往采用直接监督或对比目标的方法，该方法通过结构一致性引导学习，为确保生成推理追踪的全局连贯性提供了新思路。研究团队在GSM8K、StrategyQA、EntailmentBank等涵盖算术推理、直觉推理和基于蕴含推理的多样化数据集上，采用多种连贯性评估指标对该框架进行了测试。结果显示，这种受量子启发的方法在性能上显著优于监督学习、对比学习及预训练基线方法，印证了受量子启发的保真度作为提升LLMs推理追踪连贯性基础的有效性。

> Large Language Models (LLMs) often struggle with maintaining coherent multi-step reasoning traces, particularly in tasks that require a structured logical flow. This work introduces a quantum-inspired approach to address the challenge by incorporating a fidelity-based reward derived from Projected Entangled Pair States (PEPS) into Proximal Policy Optimization. Unlike prior approaches that use direct supervision or contrastive objectives, the proposed method guides learning through structural consistency, offering a novel approach to enforce global coherence in generated reasoning traces. The proposed framework is evaluated using multiple coherence-determining metrics on diverse datasets such as GSM8K, StrategyQA, and EntailmentBank spanning arithmetic, intuitive, and entailment-based reasoning. Results show that the proposed quantum-inspired approach offers significant improvements over supervised, contrastive, and pretrained baseline approaches, highlighting the effectiveness of quantum-inspired fidelity as a foundation to improve reasoning trace coherence in LLMs.

[Arxiv](https://arxiv.org/abs/2509.20105)