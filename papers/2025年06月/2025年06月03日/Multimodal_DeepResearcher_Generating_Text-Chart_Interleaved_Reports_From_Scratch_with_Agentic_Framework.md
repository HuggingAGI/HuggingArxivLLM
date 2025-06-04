# 多模态DeepResearcher：基于智能体框架生成文本与图表交错的报告

发布时间：2025年06月03日

`LLM应用` `可视化` `信息处理`

> Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports From Scratch with Agentic Framework

# 摘要

> 可视化在信息传达中至关重要。得益于推理和检索增强生成的最新进展，大型语言模型（LLMs）如今能够深入研究并生成详尽报告。然而，现有深度研究框架主要局限于纯文本内容的生成，对文本与可视化交织的自动化生成探索尚浅。这一新兴任务在设计信息可视化以及与文本报告的有效整合方面面临诸多挑战。为解决这些问题，我们提出了一种名为形式化可视化描述（FDV）的结构化文本表示方法，使LLMs能够学习并生成多样化、高质量的可视化内容。基于此，我们开发了多模态深度研究员（Multimodal DeepResearcher），这是一个智能框架，将任务分解为四个核心阶段：研究、示例报告文本化、规划以及多模态报告生成。为了评估生成的多模态报告，我们创建了MultimodalReportBench，其中包含100个多样化主题作为输入，并配备了5个专用评估指标。通过跨模型和评估方法的广泛实验，我们验证了Multimodal DeepResearcher的卓越性能。值得注意的是，即使使用相同的Claude 3.7 Sonnet模型，Multimodal DeepResearcher的整体胜率也达到了82%，显著超越了基线方法。

> Visualizations play a crucial part in effective communication of concepts and information. Recent advances in reasoning and retrieval augmented generation have enabled Large Language Models (LLMs) to perform deep research and generate comprehensive reports. Despite its progress, existing deep research frameworks primarily focus on generating text-only content, leaving the automated generation of interleaved texts and visualizations underexplored. This novel task poses key challenges in designing informative visualizations and effectively integrating them with text reports. To address these challenges, we propose Formal Description of Visualization (FDV), a structured textual representation of charts that enables LLMs to learn from and generate diverse, high-quality visualizations. Building on this representation, we introduce Multimodal DeepResearcher, an agentic framework that decomposes the task into four stages: (1) researching, (2) exemplar report textualization, (3) planning, and (4) multimodal report generation. For the evaluation of generated multimodal reports, we develop MultimodalReportBench, which contains 100 diverse topics served as inputs along with 5 dedicated metrics. Extensive experiments across models and evaluation methods demonstrate the effectiveness of Multimodal DeepResearcher. Notably, utilizing the same Claude 3.7 Sonnet model, Multimodal DeepResearcher achieves an 82\% overall win rate over the baseline method.

[Arxiv](https://arxiv.org/abs/2506.02454)