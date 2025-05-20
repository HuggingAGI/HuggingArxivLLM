# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月18日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）在视觉空间认知领域的应用，提出了ViCA2模型和ViCA-322K数据集，并展示了其在特定任务中的优越性能。这些内容属于模型的应用和改进，因此归类为LLM应用。` `视觉空间认知` `视觉语言任务`

> Towards Visuospatial Cognition via Hierarchical Fusion of Visual Experts

# 摘要

> 多模态大型语言模型（MLLMs）在通用视觉语言任务中表现出色，但在视觉空间认知领域仍有待突破。现有模型往往缺乏精细空间理解所需的架构组件和训练数据。我们推出ViCA2（视觉空间认知助手2），一款专为提升空间推理能力打造的新型MLLM。ViCA2采用双视觉编码器架构，整合SigLIP处理语义，Hiera解析空间结构，并配备令牌比例控制机制提升效率。同时，我们开发了ViCA-322K数据集，包含322,000多个基于空间的问题-答案对，专为指令微调设计。在高难度的VSI-Bench基准测试中，ViCA2-7B模型以56.8的平均分创下新高，远超LLaVA-NeXT-Video-72B（40.9）和Gemini-1.5 Pro（45.4）等强劲对手。这充分证明了ViCA2在紧凑模型架构下实现卓越视觉空间智能的能力。我们已开源ViCA2模型、代码库及ViCA-322K数据集，助力相关研究的进一步发展。

> While Multimodal Large Language Models (MLLMs) excel at general vision-language tasks, visuospatial cognition - reasoning about spatial layouts, relations, and dynamics - remains a significant challenge. Existing models often lack the necessary architectural components and specialized training data for fine-grained spatial understanding. We introduce ViCA2 (Visuospatial Cognitive Assistant 2), a novel MLLM designed to enhance spatial reasoning. ViCA2 features a dual vision encoder architecture integrating SigLIP for semantics and Hiera for spatial structure, coupled with a token ratio control mechanism for efficiency. We also developed ViCA-322K, a new large-scale dataset with over 322,000 spatially grounded question-answer pairs for targeted instruction tuning. On the challenging VSI-Bench benchmark, our ViCA2-7B model achieves a state-of-the-art average score of 56.8, significantly surpassing larger open-source models (e.g., LLaVA-NeXT-Video-72B, 40.9) and leading proprietary models (Gemini-1.5 Pro, 45.4). This demonstrates the effectiveness of our approach in achieving strong visuospatial intelligence with a compact model. We release ViCA2, its codebase, and the ViCA-322K dataset to facilitate further research.

[Arxiv](https://arxiv.org/abs/2505.12363)