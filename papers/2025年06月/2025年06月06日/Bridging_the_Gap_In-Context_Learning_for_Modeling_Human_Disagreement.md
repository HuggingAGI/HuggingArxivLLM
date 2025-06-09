# 跨越鸿沟：上下文学习理解人类意见分歧

发布时间：2025年06月06日

`LLM应用` `社交媒体分析`

> Bridging the Gap: In-Context Learning for Modeling Human Disagreement

# 摘要

> 大型语言模型（LLMs）在NLP分类任务中表现出色，但在处理主观标注任务时，它们通常依赖于聚合标签（常通过多数投票实现），这可能掩盖人类标注中的分歧。本研究旨在探索LLMs是否能捕捉多重视角，并在仇恨言论和冒犯性语言检测等任务中反映标注者的分歧。我们采用上下文学习（ICL）在零样本和少样本设置中，评估了四种开源LLMs在三种标签建模策略下的表现：聚合硬标签、分解硬标签和软标签。在少样本提示中，我们评估了基于文本相似性（BM25、基于PLM）、标注分歧（熵）、组合排序以及示例排序策略（随机 vs. 基于课程）的演示选择方法。结果显示，零样本设置下多重视角生成是可行的，而少样本设置通常无法完全捕捉人类判断的全部范围。提示设计和演示选择对性能有显著影响，尽管示例排序的影响有限。这些发现突显了使用LLMs建模主观性所面临的挑战，并强调了构建更具视角意识、社交智能模型的重要性。

> Large Language Models (LLMs) have shown strong performance on NLP classification tasks. However, they typically rely on aggregated labels-often via majority voting-which can obscure the human disagreement inherent in subjective annotations. This study examines whether LLMs can capture multiple perspectives and reflect annotator disagreement in subjective tasks such as hate speech and offensive language detection. We use in-context learning (ICL) in zero-shot and few-shot settings, evaluating four open-source LLMs across three label modeling strategies: aggregated hard labels, and disaggregated hard and soft labels. In few-shot prompting, we assess demonstration selection methods based on textual similarity (BM25, PLM-based), annotation disagreement (entropy), a combined ranking, and example ordering strategies (random vs. curriculum-based). Results show that multi-perspective generation is viable in zero-shot settings, while few-shot setups often fail to capture the full spectrum of human judgments. Prompt design and demonstration selection notably affect performance, though example ordering has limited impact. These findings highlight the challenges of modeling subjectivity with LLMs and the importance of building more perspective-aware, socially intelligent models.

[Arxiv](https://arxiv.org/abs/2506.06113)