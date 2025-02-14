# 具身基准：多模态大型语言模型在视觉驱动具身智能体中的全面评估

发布时间：2025年02月13日

`Agent` `机器人`

> EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents

# 摘要

> 多模态大型语言模型（MLLMs）为创建解决现实问题的具身智能体开辟了新的可能性。尽管以语言为核心的具身智能体吸引了大量关注，但基于MLLM的具身智能体由于缺乏系统化的评估体系仍处于探索阶段。为此，我们开发了EmbodiedBench，一个全面的基准测试平台，专注于评估视觉驱动的具身智能体。该平台具有以下特点：（1）在四个不同环境中设置了1,128个多样化测试任务，覆盖从高层次语义任务（如家庭场景）到需要基础操作（如导航和操作）的低层次任务；（2）精心设计了六个子集，用于评估智能体的关键能力，包括常识推理、复杂指令理解、空间感知、视觉识别和长期规划。通过在EmbodiedBench平台上对13款领先的专有和开源MLLMs进行广泛测试，我们发现：MLLMs在高层次任务上表现出色，但在低层次操作任务上表现欠佳，即使是最优的GPT-4o模型也只有28.9%的平均得分。EmbodiedBench不仅提供了一个多维度的标准评测平台，揭示了当前研究的挑战，还为推动基于MLLM的具身智能体的发展提供了宝贵的洞见。我们的代码可在https://embodiedbench.github.io获取。

> Leveraging Multi-modal Large Language Models (MLLMs) to create embodied agents offers a promising avenue for tackling real-world tasks. While language-centric embodied agents have garnered substantial attention, MLLM-based embodied agents remain underexplored due to the lack of comprehensive evaluation frameworks. To bridge this gap, we introduce EmbodiedBench, an extensive benchmark designed to evaluate vision-driven embodied agents. EmbodiedBench features: (1) a diverse set of 1,128 testing tasks across four environments, ranging from high-level semantic tasks (e.g., household) to low-level tasks involving atomic actions (e.g., navigation and manipulation); and (2) six meticulously curated subsets evaluating essential agent capabilities like commonsense reasoning, complex instruction understanding, spatial awareness, visual perception, and long-term planning. Through extensive experiments, we evaluated 13 leading proprietary and open-source MLLMs within EmbodiedBench. Our findings reveal that: MLLMs excel at high-level tasks but struggle with low-level manipulation, with the best model, GPT-4o, scoring only 28.9% on average. EmbodiedBench provides a multifaceted standardized evaluation platform that not only highlights existing challenges but also offers valuable insights to advance MLLM-based embodied agents. Our code is available at https://embodiedbench.github.io.

[Arxiv](https://arxiv.org/abs/2502.09560)