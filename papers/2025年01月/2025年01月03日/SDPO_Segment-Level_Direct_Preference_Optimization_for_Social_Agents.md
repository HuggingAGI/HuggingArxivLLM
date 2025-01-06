# SDPO: 社交智能体的分段级直接偏好优化

发布时间：2025年01月03日

`Agent

理由：这篇论文主要讨论了如何通过段级直接偏好优化（SDPO）来优化大型语言模型（LLMs）驱动的社交代理在多轮交互中的行为。论文的核心关注点是提升LLM代理的社交智能，特别是在处理复杂目标导向的社交对话时的表现。因此，这篇论文属于Agent分类，因为它主要研究的是如何改进和优化基于LLM的代理行为。` `社交智能` `人机交互`

> SDPO: Segment-Level Direct Preference Optimization for Social Agents

# 摘要

> # 摘要
大型语言模型（LLMs）驱动的社交代理虽能模拟人类社交行为，但在处理复杂目标导向的社交对话时仍有不足。直接偏好优化（DPO）已在多种代理任务中成功对齐LLM行为与人类偏好。现有基于DPO的多轮交互方法分为轮次级和会话级：轮次级方法过于细粒度，仅关注单轮次；会话级方法则过于粗粒度，常引入训练噪声。为此，我们提出段级直接偏好优化（SDPO），专注于交互中的关键段，优化多轮代理行为并减少训练噪声。SOTOPIA基准测试显示，SDPO调整后的代理在性能上持续超越现有DPO方法和GPT-4o等专有LLMs，展现了SDPO在提升LLM代理社交智能方面的潜力。代码和数据已发布于https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/SDPO。

> Social agents powered by large language models (LLMs) can simulate human social behaviors but fall short in handling complex goal-oriented social dialogues. Direct Preference Optimization (DPO) has proven effective in aligning LLM behavior with human preferences across a variety of agent tasks. Existing DPO-based approaches for multi-turn interactions are divided into turn-level and session-level methods. The turn-level method is overly fine-grained, focusing exclusively on individual turns, while session-level methods are too coarse-grained, often introducing training noise. To address these limitations, we propose Segment-Level Direct Preference Optimization (SDPO), which focuses on specific key segments within interactions to optimize multi-turn agent behavior while minimizing training noise. Evaluations on the SOTOPIA benchmark demonstrate that SDPO-tuned agents consistently outperform both existing DPO-based methods and proprietary LLMs like GPT-4o, underscoring SDPO's potential to advance the social intelligence of LLM-based agents. We release our code and data at https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/SDPO.

[Arxiv](https://arxiv.org/abs/2501.01821)