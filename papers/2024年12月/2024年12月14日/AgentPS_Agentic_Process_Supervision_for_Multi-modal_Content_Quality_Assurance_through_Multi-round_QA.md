# AgentPS: 多轮问答驱动的多模态内容质量智能体流程监督

发布时间：2024年12月14日

`Agent

理由：这篇论文提出了一个名为\textit{AgentPS}的框架，通过在微调阶段引入多轮问答，将智能体过程监督融入多模态大型语言模型（MLLMs）。这表明该研究主要关注智能体（Agent）的设计和应用，特别是在多模态任务中的表现和优化。因此，将其分类为Agent是合适的。` `社交媒体` `人工智能`

> AgentPS: Agentic Process Supervision for Multi-modal Content Quality Assurance through Multi-round QA

# 摘要

> 多模态大型语言模型（MLLMs）凭借其强大的处理和推理能力，在视觉-语言（VL）理解任务中取得了显著进展。然而，MLLMs在处理简单逻辑任务时表现出色，但在面对复杂、相互依赖的逻辑结构时却常常力不从心。为此，我们提出了	extit{AgentPS}框架，通过在微调阶段引入多轮问答，将智能体过程监督融入MLLMs。	extit{AgentPS}在TikTok专有数据集上表现优异，显著超越了基线MLLMs，这得益于其结合了过程监督和结构化顺序推理。此外，我们发现用LLM生成的标签替代人工标注标签，仍能保留大部分性能提升，这凸显了该框架在工业应用中的强大可扩展性。这些成果表明，	extit{AgentPS}是一个高效且适应性强的多模态分类架构，尤其在自动标注生成的加持下，能够轻松应对大规模现实世界挑战。

> The advanced processing and reasoning capabilities of multimodal large language models (MLLMs) have driven substantial progress in vision-language (VL) understanding tasks. However, while effective for tasks governed by straightforward logic, MLLMs often encounter challenges when reasoning over complex, interdependent logic structures. To address this limitation, we introduce \textit{AgentPS}, a novel framework that integrates Agentic Process Supervision into MLLMs via multi-round question answering during fine-tuning. \textit{AgentPS} demonstrates significant performance improvements over baseline MLLMs on proprietary TikTok datasets, due to its integration of process supervision and structured sequential reasoning. Furthermore, we show that replacing human-annotated labels with LLM-generated labels retains much of the performance gain, highlighting the framework's practical scalability in industrial applications. These results position \textit{AgentPS} as a highly effective and efficient architecture for multimodal classification tasks. Its adaptability and scalability, especially when enhanced by automated annotation generation, make it a powerful tool for handling large-scale, real-world challenges.

[Arxiv](https://arxiv.org/abs/2412.15251)