# CLiViS: 通过语言与视觉的协同作用释放认知地图，助力具身视觉推理

发布时间：2025年06月21日

`Agent` `计算机视觉`

> CLiViS: Unleashing Cognitive Map through Linguistic-Visual Synergy for Embodied Visual Reasoning

# 摘要

> # 嵌入式视觉推理 (EVR)
EVR基于第一人称视角视频，通过遵循复杂指令实现动态环境中的语义理解和时空推理。尽管潜力巨大，但EVR面临两大核心挑战：复杂指令的多样性与长期视频中的时空动态。现有解决方案各有利弊：LLMs处理静态视频描述时容易忽略关键视觉细节，而VLMs在逐步推理方面表现不足。

为充分发挥LLMs的推理能力和VLMs的感知优势，我们提出了CLiViS——一个无需训练的全新框架。它利用LLMs进行高层次任务规划，并通过VLM驱动的开放世界视觉感知迭代更新场景上下文。CLiViS的核心是动态认知图，它在整个推理过程中不断演变，构建结构化的场景表示，连接低级感知与高级推理。

实验结果表明，CLiViS在多个基准上表现出色，尤其擅长处理长期视觉依赖问题。代码已开源，欢迎访问https://github.com/Teacher-Tom/CLiViS了解详情。

> Embodied Visual Reasoning (EVR) seeks to follow complex, free-form instructions based on egocentric video, enabling semantic understanding and spatiotemporal reasoning in dynamic environments. Despite its promising potential, EVR encounters significant challenges stemming from the diversity of complex instructions and the intricate spatiotemporal dynamics in long-term egocentric videos. Prior solutions either employ Large Language Models (LLMs) over static video captions, which often omit critical visual details, or rely on end-to-end Vision-Language Models (VLMs) that struggle with stepwise compositional reasoning. Consider the complementary strengths of LLMs in reasoning and VLMs in perception, we propose CLiViS. It is a novel training-free framework that leverages LLMs for high-level task planning and orchestrates VLM-driven open-world visual perception to iteratively update the scene context. Building on this synergy, the core of CLiViS is a dynamic Cognitive Map that evolves throughout the reasoning process. This map constructs a structured representation of the embodied scene, bridging low-level perception and high-level reasoning. Extensive experiments across multiple benchmarks demonstrate the effectiveness and generality of CLiViS, especially in handling long-term visual dependencies. Code is available at https://github.com/Teacher-Tom/CLiViS.

[Arxiv](https://arxiv.org/abs/2506.17629)