# ResearchBench：基于灵感的任务分解方法在科学发现领域的LLM基准测试

发布时间：2025年03月27日

`LLM应用` `科学研究` `科学发现`

> ResearchBench: Benchmarking LLMs in Scientific Discovery via Inspiration-Based Task Decomposition

# 摘要

> 大型语言模型（LLMs）在辅助科学研究方面展现出潜力，但它们发现高质量研究假设的能力尚未得到充分研究，主要原因是缺乏专门的基准测试。为填补这一空白，我们引入了首个大规模基准测试，用于评估LLMs在科学研究发现方面的能力，涵盖灵感检索、假设构建以及假设排序三大子任务。我们开发了一个自动化框架，能够从跨12个学科的科学论文中提取关键要素——研究问题、背景调查、灵感来源和研究假设，并通过专家验证确保其准确性。为了避免数据污染，我们仅专注于2024年发表的论文，确保与LLM预训练数据的重叠最小。我们的评估结果显示，LLMs在灵感检索这一需要处理分布外任务方面表现出色，这表明它们能够揭示新颖的知识关联。这使LLMs成为"研究假设挖掘工具"，能够通过生成创新假设并以最小的人为干预实现自动化的科学研究发现。

> Large language models (LLMs) have demonstrated potential in assisting scientific research, yet their ability to discover high-quality research hypotheses remains unexamined due to the lack of a dedicated benchmark. To address this gap, we introduce the first large-scale benchmark for evaluating LLMs with a near-sufficient set of sub-tasks of scientific discovery: inspiration retrieval, hypothesis composition, and hypothesis ranking. We develop an automated framework that extracts critical components - research questions, background surveys, inspirations, and hypotheses - from scientific papers across 12 disciplines, with expert validation confirming its accuracy. To prevent data contamination, we focus exclusively on papers published in 2024, ensuring minimal overlap with LLM pretraining data. Our evaluation reveals that LLMs perform well in retrieving inspirations, an out-of-distribution task, suggesting their ability to surface novel knowledge associations. This positions LLMs as "research hypothesis mines", capable of facilitating automated scientific discovery by generating innovative hypotheses at scale with minimal human intervention.

[Arxiv](https://arxiv.org/abs/2503.21248)