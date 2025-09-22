# BaseReward：面向多模态奖励模型的强大基线

发布时间：2025年09月19日

`强化学习` `基础理论`

> BaseReward: A Strong Baseline for Multimodal Reward Model

# 摘要

> 多模态大型语言模型（MLLMs）的飞速发展，使得如何使其与人类偏好对齐成为一大关键挑战。奖励模型（RMs）是实现这一目标的核心技术，然而目前学术界和工业界都缺少构建最先进多模态奖励模型（MRMs）的系统性指南。为此，本文通过全面的实验分析，旨在为构建高性能MRMs提供一套清晰的“配方”。我们系统探究了MRM开发流程中的各个关键环节，包括	extit{奖励建模范式}（如朴素RM、基于评论家的RM及生成式RM）、	extit{奖励头架构}、	extit{训练策略}、	extit{数据筛选}（涵盖十余种多模态与纯文本偏好数据集）、	extit{骨干模型}、	extit{模型规模}及	extit{集成方法}。
  基于这些实验发现，我们提出了	extbf{BaseReward}——一个强大且高效的多模态奖励建模基线。该模型采用简洁高效的架构，以{Qwen2.5-VL}为骨干，配备优化的两层奖励头，并在精心筛选的高质量多模态与纯文本偏好数据混合集上训练而成。实验结果显示，BaseReward在MM-RLHF-Reward Bench、VL-Reward Bench和Multimodal Reward Bench等主流基准测试中刷新SOTA，性能超越现有模型。此外，为验证其在静态基准之外的实际价值，我们将BaseReward集成到真实强化学习流程中，成功提升了MLLM在感知、推理、对话等多类任务中的表现。这项工作不仅推出了一款顶级MRM，更重要的是为社区提供了一份清晰的实证指南，助力下一代MLLMs稳健奖励模型的研发。

> The rapid advancement of Multimodal Large Language Models (MLLMs) has made aligning them with human preferences a critical challenge. Reward Models (RMs) are a core technology for achieving this goal, but a systematic guide for building state-of-the-art Multimodal Reward Models (MRMs) is currently lacking in both academia and industry. Through exhaustive experimental analysis, this paper aims to provide a clear ``recipe'' for constructing high-performance MRMs. We systematically investigate every crucial component in the MRM development pipeline, including \textit{reward modeling paradigms} (e.g., Naive-RM, Critic-based RM, and Generative RM), \textit{reward head architecture}, \textit{training strategies}, \textit{data curation} (covering over ten multimodal and text-only preference datasets), \textit{backbone model} and \textit{model scale}, and \textit{ensemble methods}.
  Based on these experimental insights, we introduce \textbf{BaseReward}, a powerful and efficient baseline for multimodal reward modeling. BaseReward adopts a simple yet effective architecture, built upon a {Qwen2.5-VL} backbone, featuring an optimized two-layer reward head, and is trained on a carefully curated mixture of high-quality multimodal and text-only preference data. Our results show that BaseReward establishes a new SOTA on major benchmarks such as MM-RLHF-Reward Bench, VL-Reward Bench, and Multimodal Reward Bench, outperforming previous models. Furthermore, to validate its practical utility beyond static benchmarks, we integrate BaseReward into a real-world reinforcement learning pipeline, successfully enhancing an MLLM's performance across various perception, reasoning, and conversational tasks. This work not only delivers a top-tier MRM but, more importantly, provides the community with a clear, empirically-backed guide for developing robust reward models for the next generation of MLLMs.

[Arxiv](https://arxiv.org/abs/2509.16127)