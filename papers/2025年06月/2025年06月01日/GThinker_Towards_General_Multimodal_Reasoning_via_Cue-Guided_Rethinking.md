# GThinker：迈向通用多模态推理的提示引导再思考

发布时间：2025年06月01日

`LLM应用

理由：这篇论文主要探讨了多模态推理中的问题，并提出了一种新型的推理型MLLM（GThinker）来解决这些问题。论文的重点在于模型的应用和改进，特别是在多模态推理任务中的表现，属于LLM的应用层面。` `人工智能` `科学研究`

> GThinker: Towards General Multimodal Reasoning via Cue-Guided Rethinking

# 摘要

> 尽管多模态推理领域取得了显著进展，现有MLLMs在通用场景下的视觉为中心的多模态推理任务中表现欠佳。这一不足主要源于这些模型过度依赖基于逻辑和知识的慢思考策略，尽管在数学和科学等领域表现有效，但在推理过程中未能有效整合视觉信息。因此，这些模型往往无法充分基于视觉线索进行推理，导致在需要多种合理视觉解释和推断的任务中表现不佳。

为了解决这一问题，我们提出了GThinker（通用推理器），一种在通用场景、数学和科学领域的多模态推理中表现出色的新型推理型MLLM。GThinker引入了Cue-Rethinking（提示重构），一种灵活的推理模式，通过将推理基于视觉线索，并对这些线索进行迭代重新解释，从而解决不一致的问题。

在此模式基础上，我们进一步提出了一种两阶段训练pipeline，包括模式引导的冷启动和激励强化学习，旨在跨领域实现多模态推理能力。此外，为了支持训练，我们构建了GThinker-11K，包含7K高质量、迭代标注的推理路径和4K精选强化学习样本，填补了通用多模态推理领域的数据空白。

大量实验表明，GThinker在具有挑战性的综合多模态推理基准测试M$^3$CoT中达到了81.5%的准确率，超越了最新的O4-mini模型。它还在通用场景下的多模态推理基准测试中平均提升了2.1%的表现，同时在数学推理方面与同类先进推理模型保持相当水平。代码、模型和数据集即将在https://github.com/jefferyZhan/GThinker公开发布。

> Despite notable advancements in multimodal reasoning, leading Multimodal Large Language Models (MLLMs) still underperform on vision-centric multimodal reasoning tasks in general scenarios. This shortfall stems from their predominant reliance on logic- and knowledge-based slow thinking strategies, while effective for domains like math and science, fail to integrate visual information effectively during reasoning. Consequently, these models often fail to adequately ground visual cues, resulting in suboptimal performance in tasks that require multiple plausible visual interpretations and inferences. To address this, we present GThinker (General Thinker), a novel reasoning MLLM excelling in multimodal reasoning across general scenarios, mathematics, and science. GThinker introduces Cue-Rethinking, a flexible reasoning pattern that grounds inferences in visual cues and iteratively reinterprets these cues to resolve inconsistencies. Building on this pattern, we further propose a two-stage training pipeline, including pattern-guided cold start and incentive reinforcement learning, designed to enable multimodal reasoning capabilities across domains. Furthermore, to support the training, we construct GThinker-11K, comprising 7K high-quality, iteratively-annotated reasoning paths and 4K curated reinforcement learning samples, filling the data gap toward general multimodal reasoning. Extensive experiments demonstrate that GThinker achieves 81.5% on the challenging comprehensive multimodal reasoning benchmark M$^3$CoT, surpassing the latest O4-mini model. It also shows an average improvement of 2.1% on general scenario multimodal reasoning benchmarks, while maintaining on-par performance in mathematical reasoning compared to counterpart advanced reasoning models. The code, model, and data will be released soon at https://github.com/jefferyZhan/GThinker.

[Arxiv](https://arxiv.org/abs/2506.01078)