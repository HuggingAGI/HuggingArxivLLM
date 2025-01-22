# PlotEdit: 利用多模态LLM代理，实现PDF中基于自然语言的便捷图表编辑

发布时间：2025年01月19日

`Agent

理由：这篇论文介绍了一个名为PlotEdit的多智能体框架，该框架通过多个LLM智能体协同工作，实现自然语言驱动的图表图像编辑。论文中提到的五个LLM智能体分别负责不同的任务，如数据表提取、样式属性识别、渲染代码获取、指令分解和多模态编辑。这些智能体通过多模态反馈协调工作，确保视觉保真度。因此，这篇论文主要涉及智能体（Agent）的设计和应用，属于Agent分类。` `数据可视化` `无障碍设计`

> PlotEdit: Natural Language-Driven Accessible Chart Editing in PDFs via Multimodal LLM Agents

# 摘要

> # 摘要
图表可视化在数据解释和沟通中不可或缺，但PDF中的图表通常仅以图像形式呈现，缺乏源数据表和样式信息。为此，我们推出了PlotEdit，一个创新的多智能体框架，通过自反思的LLM智能体实现自然语言驱动的端到端图表图像编辑。PlotEdit整合了五个LLM智能体：(1) Chart2Table提取数据表，(2) Chart2Vision识别样式属性，(3) Chart2Code获取渲染代码，(4) 指令分解智能体解析用户请求为可执行步骤，(5) 多模态编辑智能体实现图表组件的精细修改——所有操作通过多模态反馈协调，确保视觉保真度。PlotEdit在ChartCraft数据集上表现卓越，涵盖样式、布局、格式和数据编辑，不仅提升了视觉障碍用户的可访问性，还显著提高了新手的工作效率。

> Chart visualizations, while essential for data interpretation and communication, are predominantly accessible only as images in PDFs, lacking source data tables and stylistic information. To enable effective editing of charts in PDFs or digital scans, we present PlotEdit, a novel multi-agent framework for natural language-driven end-to-end chart image editing via self-reflective LLM agents. PlotEdit orchestrates five LLM agents: (1) Chart2Table for data table extraction, (2) Chart2Vision for style attribute identification, (3) Chart2Code for retrieving rendering code, (4) Instruction Decomposition Agent for parsing user requests into executable steps, and (5) Multimodal Editing Agent for implementing nuanced chart component modifications - all coordinated through multimodal feedback to maintain visual fidelity. PlotEdit outperforms existing baselines on the ChartCraft dataset across style, layout, format, and data-centric edits, enhancing accessibility for visually challenged users and improving novice productivity.

[Arxiv](https://arxiv.org/abs/2501.11233)