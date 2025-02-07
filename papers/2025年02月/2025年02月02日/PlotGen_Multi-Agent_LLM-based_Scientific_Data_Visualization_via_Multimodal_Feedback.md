# PlotGen: 基于多智能体LLM的多模态反馈科学数据可视化

发布时间：2025年02月02日

`Agent

理由：这篇论文提出了一个名为PlotGen的多智能体框架，旨在自动化生成精确的科学可视化。该框架整合了多个基于LLM的智能体，包括查询规划智能体、代码生成智能体和多个检索反馈智能体。这些智能体通过协作和自我反思来优化生成的可视化结果。因此，这篇论文主要关注的是多智能体系统的设计和应用，属于Agent分类。` `数据可视化` `人工智能`

> PlotGen: Multi-Agent LLM-based Scientific Data Visualization via Multimodal Feedback

# 摘要

> # 摘要
科学数据可视化是将原始数据转化为直观视觉表示的关键，助力模式识别、预测和数据驱动见解的展示。然而，新手用户常因工具选择和可视化技术的复杂性而困扰。近期，大型语言模型（LLMs）在代码生成辅助方面展现出潜力，尽管其准确性尚待提升且需迭代调试。本文提出PlotGen，一个创新的多智能体框架，旨在自动化生成精确的科学可视化。PlotGen整合了多个基于LLM的智能体，包括将复杂用户请求拆解为可执行步骤的查询规划智能体、将伪代码转化为可执行Python代码的代码生成智能体，以及三个检索反馈智能体——数值反馈、词汇反馈和视觉反馈智能体——它们借助多模态LLM，通过自我反思迭代优化生成图的数据准确性、文本标签和视觉正确性。大量实验证明，PlotGen在MatPlotBench数据集上表现优异，提升4-6%，增强了用户对LLM生成可视化的信任，并因减少绘图错误调试时间而提升了新手用户的生产力。

> Scientific data visualization is pivotal for transforming raw data into comprehensible visual representations, enabling pattern recognition, forecasting, and the presentation of data-driven insights. However, novice users often face difficulties due to the complexity of selecting appropriate tools and mastering visualization techniques. Large Language Models (LLMs) have recently demonstrated potential in assisting code generation, though they struggle with accuracy and require iterative debugging. In this paper, we propose PlotGen, a novel multi-agent framework aimed at automating the creation of precise scientific visualizations. PlotGen orchestrates multiple LLM-based agents, including a Query Planning Agent that breaks down complex user requests into executable steps, a Code Generation Agent that converts pseudocode into executable Python code, and three retrieval feedback agents - a Numeric Feedback Agent, a Lexical Feedback Agent, and a Visual Feedback Agent - that leverage multimodal LLMs to iteratively refine the data accuracy, textual labels, and visual correctness of generated plots via self-reflection. Extensive experiments show that PlotGen outperforms strong baselines, achieving a 4-6 percent improvement on the MatPlotBench dataset, leading to enhanced user trust in LLM-generated visualizations and improved novice productivity due to a reduction in debugging time needed for plot errors.

[Arxiv](https://arxiv.org/abs/2502.00988)