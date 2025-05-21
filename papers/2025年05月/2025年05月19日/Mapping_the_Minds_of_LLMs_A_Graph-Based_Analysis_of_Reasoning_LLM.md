# # 探索 LLM 的思维：基于图谱的推理型 LLM 分析

发布时间：2025年05月19日

`LLM理论` `人工智能` `认知科学`

> Mapping the Minds of LLMs: A Graph-Based Analysis of Reasoning LLM

# 摘要

> 测试时扩展的最新进展使大型语言模型（LLMs）能够通过扩展链式思维（CoT）生成展示出复杂的推理能力。然而，尽管这些推理型LLMs（RLMs）潜力巨大，它们却常常表现出违反直觉和不稳定的行为，如在少量提示下性能下降，这挑战了我们对RLMs的理解。本研究引入了一个统一的图分析框架，以深入建模RLMs的推理过程。我们的方法首先将冗长的CoT输出聚类为语义连贯的推理步骤，随后构建有向推理图来捕捉这些步骤之间的上下文与逻辑依赖关系。通过对不同模型和提示策略的全面分析，我们发现结构属性（如探索密度、分支度和收敛率）与推理准确性密切相关。我们的研究揭示了提示策略如何显著重塑RLMs的内部推理结构，直接影响任务结果。本框架不仅超越传统指标，实现了对推理质量的定量评估，还为提示工程和LLMs的认知分析提供了实用见解。为了推动未来研究，相关代码和资源将公开发布。

> Recent advances in test-time scaling have enabled Large Language Models (LLMs) to display sophisticated reasoning abilities via extended Chain-of-Thought (CoT) generation. Despite their potential, these Reasoning LLMs (RLMs) often demonstrate counterintuitive and unstable behaviors, such as performance degradation under few-shot prompting, that challenge our current understanding of RLMs. In this work, we introduce a unified graph-based analytical framework for better modeling the reasoning processes of RLMs. Our method first clusters long, verbose CoT outputs into semantically coherent reasoning steps, then constructs directed reasoning graphs to capture contextual and logical dependencies among these steps. Through comprehensive analysis across models and prompting regimes, we reveal that structural properties, such as exploration density, branching, and convergence ratios, strongly correlate with reasoning accuracy. Our findings demonstrate how prompting strategies substantially reshape the internal reasoning structure of RLMs, directly affecting task outcomes. The proposed framework not only enables quantitative evaluation of reasoning quality beyond conventional metrics but also provides practical insights for prompt engineering and the cognitive analysis of LLMs. Code and resources will be released to facilitate future research in this direction.

[Arxiv](https://arxiv.org/abs/2505.13890)