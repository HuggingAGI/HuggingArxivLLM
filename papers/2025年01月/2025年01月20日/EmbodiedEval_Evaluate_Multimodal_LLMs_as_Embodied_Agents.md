# EmbodiedEval: 多模态LLMs的具身代理评估

发布时间：2025年01月20日

`Agent

理由：这篇论文主要讨论的是多模态大型语言模型（MLLMs）在具身智能体（Embodied Agents）中的应用和评估。论文提出了一个名为EmbodiedEval的评估基准，专门用于评估MLLMs在具身任务中的表现。具身智能体通常是指能够与环境进行交互的智能体，因此这篇论文的核心内容与智能体（Agent）相关，而不是单纯的LLM应用或理论。` `人工智能` `机器人`

> EmbodiedEval: Evaluate Multimodal LLMs as Embodied Agents

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）取得了显著进展，为具身智能体描绘了美好前景。然而，现有评估基准多依赖静态图像或视频，局限于非交互场景。同时，具身AI基准任务单一且多样性不足，难以全面评估MLLMs的具身能力。为此，我们推出EmbodiedEval，一个全面且交互式的评估基准，专为MLLMs的具身任务设计。EmbodiedEval包含125个多样化的3D场景中的328个任务，每个任务均经过精心挑选和标注。它涵盖了现有具身AI任务的广泛领域，并显著提升了多样性，所有任务均在一个为MLLMs量身定制的统一模拟和评估框架内进行。任务分为五类：导航、对象交互、社交交互、属性问答和空间问答，以全面评估智能体的各项能力。我们在EmbodiedEval上测试了最先进的MLLMs，发现它们在具身任务上与人类水平存在显著差距。分析揭示了现有MLLMs在具身能力上的不足，为未来研究指明了方向。所有评估数据和模拟框架已在https://github.com/thunlp/EmbodiedEval开源。

> Multimodal Large Language Models (MLLMs) have shown significant advancements, providing a promising future for embodied agents. Existing benchmarks for evaluating MLLMs primarily utilize static images or videos, limiting assessments to non-interactive scenarios. Meanwhile, existing embodied AI benchmarks are task-specific and not diverse enough, which do not adequately evaluate the embodied capabilities of MLLMs. To address this, we propose EmbodiedEval, a comprehensive and interactive evaluation benchmark for MLLMs with embodied tasks. EmbodiedEval features 328 distinct tasks within 125 varied 3D scenes, each of which is rigorously selected and annotated. It covers a broad spectrum of existing embodied AI tasks with significantly enhanced diversity, all within a unified simulation and evaluation framework tailored for MLLMs. The tasks are organized into five categories: navigation, object interaction, social interaction, attribute question answering, and spatial question answering to assess different capabilities of the agents. We evaluated the state-of-the-art MLLMs on EmbodiedEval and found that they have a significant shortfall compared to human level on embodied tasks. Our analysis demonstrates the limitations of existing MLLMs in embodied capabilities, providing insights for their future development. We open-source all evaluation data and simulation framework at https://github.com/thunlp/EmbodiedEval.

[Arxiv](https://arxiv.org/abs/2501.11858)