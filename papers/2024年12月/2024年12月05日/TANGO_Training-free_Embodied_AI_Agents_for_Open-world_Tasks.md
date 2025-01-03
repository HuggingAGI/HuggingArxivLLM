# TANGO: 面向开放世界任务的免训练具身AI智能体

发布时间：2024年12月05日

`Agent

理由：这篇论文主要讨论了如何将大型语言模型（LLMs）的能力扩展到具身代理（embodied agents）中，使其能够在现实世界中观察并行动。论文提出的TANGO方法旨在通过组合模块来创建能够对图像进行复杂推理的程序，并将其应用于具身代理。因此，这篇论文的核心内容与具身代理（Agent）相关，属于Agent分类。` `机器人` `人工智能`

> TANGO: Training-free Embodied AI Agents for Open-world Tasks

# 摘要

> 大型语言模型（LLMs）在组合模块以创建能对图像进行复杂推理的程序方面表现出色。本文提出的TANGO方法，旨在将LLMs在图像上的程序组合能力扩展到具身代理中，使其能够观察并行动于现实世界。我们采用简单的PointGoal导航模型与基于记忆的探索策略相结合，作为引导代理的基础原语，展示了单个模型如何无需额外训练即可应对多样化任务。我们让LLM仅通过少量上下文示例组合原语来解决特定任务，并在开放集对象目标导航、多模态终身导航和开放具身问答三个关键具身AI任务上评估了该方法，在零-shot场景中取得了最先进的结果，且无需特定微调。

> Large Language Models (LLMs) have demonstrated excellent capabilities in composing various modules together to create programs that can perform complex reasoning tasks on images. In this paper, we propose TANGO, an approach that extends the program composition via LLMs already observed for images, aiming to integrate those capabilities into embodied agents capable of observing and acting in the world. Specifically, by employing a simple PointGoal Navigation model combined with a memory-based exploration policy as a foundational primitive for guiding an agent through the world, we show how a single model can address diverse tasks without additional training. We task an LLM with composing the provided primitives to solve a specific task, using only a few in-context examples in the prompt. We evaluate our approach on three key Embodied AI tasks: Open-Set ObjectGoal Navigation, Multi-Modal Lifelong Navigation, and Open Embodied Question Answering, achieving state-of-the-art results without any specific fine-tuning in challenging zero-shot scenarios.

[Arxiv](https://arxiv.org/abs/2412.10402)