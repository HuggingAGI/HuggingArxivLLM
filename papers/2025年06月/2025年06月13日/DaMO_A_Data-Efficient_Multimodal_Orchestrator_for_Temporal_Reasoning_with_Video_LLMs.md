# DaMO: 面向视频大语言模型时间推理的高效数据多模态编排器

发布时间：2025年06月13日

`LLM应用` `视频处理` `视频理解`

> DaMO: A Data-Efficient Multimodal Orchestrator for Temporal Reasoning with Video LLMs

# 摘要

> 大型语言模型（LLMs）近期已成功扩展到视频领域，实现了复杂视频语言理解能力。然而，现有视频LLMs在精细时间推理方面存在局限性，尤其在监督受限的情况下，难以将响应准确对应到特定视频时刻。为此，我们提出了DaMO——一种专为精准时间推理和多模态理解设计的数据高效视频LLM。其核心创新在于采用时序感知Fuseformer，该模型通过层次化双流架构逐步捕捉各模态的时间动态，并有效融合视觉与音频信息。此外，DaMO引入全局残差模块，既减少空间冗余又保留关键语义细节，进一步提升计算效率。我们采用结构化的四阶段渐进训练范式训练DaMO，逐步赋予模型多模态对齐、语义接地及时间推理能力。本研究还通过GPT生成的时间接地QA对增强现有数据集，为需要时间监督的任务提供多组数据支持。在时间接地和视频QA基准测试中，DaMO在需要精确时间对齐和推理的任务上表现尤为突出，超越了现有方法。这项工作为数据高效的视频语言建模奠定了有前景的基础。

> Large Language Models (LLMs) have recently been extended to the video domain, enabling sophisticated video-language understanding. However, existing Video LLMs often exhibit limitations in fine-grained temporal reasoning, restricting their ability to precisely attribute responses to specific video moments, especially under constrained supervision. We introduce DaMO, a data-efficient Video LLM explicitly designed for accurate temporal reasoning and multimodal understanding. At its core, the proposed Temporal-aware Fuseformer employs a hierarchical dual-stream architecture that progressively captures temporal dynamics within each modality and effectively fuses complementary visual and audio information. To further enhance computational efficiency, DaMO integrates a global residual that reduces spatial redundancy while preserving essential semantic details. We train DaMO via a structured four-stage progressive training paradigm, incrementally equipping the model with multimodal alignment, semantic grounding, and temporal reasoning capabilities. This work also contributes multiple datasets augmented from existing ones with GPT-generated temporally grounded QA pairs for tasks requiring temporal supervision. Comprehensive experiments on temporal grounding and video QA benchmarks demonstrate that DaMO consistently surpasses prior methods, particularly in tasks demanding precise temporal alignment and reasoning. Our work establishes a promising direction for data-efficient video-language modeling.

[Arxiv](https://arxiv.org/abs/2506.11558)