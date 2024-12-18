# ComprehendEdit：一个用于多模态知识编辑的综合性数据集及评估框架

发布时间：2024年12月17日

`LLM应用` `多模态知识编辑`

> ComprehendEdit: A Comprehensive Dataset and Evaluation Framework for Multimodal Knowledge Editing

# 摘要

> 大型多模态语言模型（MLLMs）在自然语言处理和视觉理解领域带来了变革，但常包含过时或不准确的信息。当下的多模态知识编辑评估范围有限且可能有偏差，聚焦于狭窄任务，未评估对域内样本的影响。为应对这些问题，我们推出了 ComprehendEdit，这一综合基准涵盖来自多个数据集的八项不同任务。我们提出两个全新指标：知识泛化指数（KGI）和知识保存指数（KPI），它们无需依赖人工智能合成样本即可评估对域内样本的编辑效果。基于我们框架的洞察，我们构建了分层上下文编辑（HICE），这是一种采用两阶段方法、能在所有指标上平衡性能的基线方法。本研究为多模态知识编辑提供了更全面的评估框架，揭示了该领域的独特挑战，并给出了展现性能提升的基线方法。我们的工作为未来研究开辟了新视野，为开发更强大有效的 MLLMs 编辑技术奠定了基础。ComprehendEdit 基准和实现代码可在 https://github.com/yaohui120/ComprehendEdit 获取。

> Large multimodal language models (MLLMs) have revolutionized natural language processing and visual understanding, but often contain outdated or inaccurate information. Current multimodal knowledge editing evaluations are limited in scope and potentially biased, focusing on narrow tasks and failing to assess the impact on in-domain samples. To address these issues, we introduce ComprehendEdit, a comprehensive benchmark comprising eight diverse tasks from multiple datasets. We propose two novel metrics: Knowledge Generalization Index (KGI) and Knowledge Preservation Index (KPI), which evaluate editing effects on in-domain samples without relying on AI-synthetic samples. Based on insights from our framework, we establish Hierarchical In-Context Editing (HICE), a baseline method employing a two-stage approach that balances performance across all metrics. This study provides a more comprehensive evaluation framework for multimodal knowledge editing, reveals unique challenges in this field, and offers a baseline method demonstrating improved performance. Our work opens new perspectives for future research and provides a foundation for developing more robust and effective editing techniques for MLLMs. The ComprehendEdit benchmark and implementation code are available at https://github.com/yaohui120/ComprehendEdit.

[Arxiv](https://arxiv.org/abs/2412.12821)