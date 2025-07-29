# # Text2Vis：一个多模态可视化生成评测基准，兼具挑战性与多样性。

发布时间：2025年07月26日

`LLM应用` `数据可视化` `数据科学`

> Text2Vis: A Challenging and Diverse Benchmark for Generating Multimodal Visualizations from Text

# 摘要

> 自动化数据可视化在简化数据解释、提升决策能力和提高效率方面发挥着关键作用。尽管大型语言模型（LLMs）在从自然语言生成可视化方面显示出潜力，但缺乏全面的基准测试限制了对其能力的严格评估。我们引入了Text2Vis，这是一个用于评估文本到可视化模型的基准测试，涵盖了20多种图表类型和多样化数据科学查询，包括趋势分析、相关性、异常值检测和预测分析。它包含1,985个样本，每个样本包括数据表、自然语言查询、简短答案、可视化代码和标注图表。查询涉及复杂推理、对话轮次和动态数据检索。我们评估了11个开源和闭源模型，揭示了显著的性能差距，突出了关键挑战，并为未来的发展提供了见解。为缩小这一差距，我们提出了首个跨模态Actor-Critic智能体框架，该框架联合优化文本答案和可视化代码，使GPT-4o的通过率比直接方法提高了26%至42%，并提升了图表质量。我们还引入了一个基于LLM的自动化评估框架，无需人工标注即可在数千个样本上进行扩展评估，衡量答案正确性、代码执行成功率、可视化可读性和图表准确性。我们已在https://github.com/vis-nlp/Text2Vis发布了Text2Vis。


> Automated data visualization plays a crucial role in simplifying data interpretation, enhancing decision-making, and improving efficiency. While large language models (LLMs) have shown promise in generating visualizations from natural language, the absence of comprehensive benchmarks limits the rigorous evaluation of their capabilities. We introduce Text2Vis, a benchmark designed to assess text-to-visualization models, covering 20+ chart types and diverse data science queries, including trend analysis, correlation, outlier detection, and predictive analytics. It comprises 1,985 samples, each with a data table, natural language query, short answer, visualization code, and annotated charts. The queries involve complex reasoning, conversational turns, and dynamic data retrieval. We benchmark 11 open-source and closed-source models, revealing significant performance gaps, highlighting key challenges, and offering insights for future advancements. To close this gap, we propose the first cross-modal actor-critic agentic framework that jointly refines the textual answer and visualization code, increasing GPT-4o`s pass rate from 26% to 42% over the direct approach and improving chart quality. We also introduce an automated LLM-based evaluation framework that enables scalable assessment across thousands of samples without human annotation, measuring answer correctness, code execution success, visualization readability, and chart accuracy. We release Text2Vis at https://github.com/vis-nlp/Text2Vis.

[Arxiv](https://arxiv.org/abs/2507.19969)