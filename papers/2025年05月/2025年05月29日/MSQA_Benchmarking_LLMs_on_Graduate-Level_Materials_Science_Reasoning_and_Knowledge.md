# MSQA：评估大型语言模型在研究生级别材料科学推理与知识上的基准评测

发布时间：2025年05月29日

`LLM理论` `材料科学` `评估基准`

> MSQA: Benchmarking LLMs on Graduate-Level Materials Science Reasoning and Knowledge

# 摘要

> 尽管材料科学领域的大语言模型（LLMs）取得了显著进展，但目前仍缺乏评估其领域知识和复杂推理能力的基准。为解决这一问题，我们推出了MSQA，这是一个包含1,757个研究生水平材料科学问题的综合评估基准，采用详细解释性回答和二元True/False两种评估形式。MSQA的独特之处在于，它要求LLMs在材料科学的七个子领域（如结构-性能关系、合成过程和计算建模）中结合精确的事实知识和多步骤推理能力。通过测试10个最先进的LLMs，我们发现当前模型的性能存在显著差异。基于API的专有LLMs表现最佳，准确率高达84.5%，而开源（OSS）LLMs的准确率峰值约为60.5%。此外，特定领域的LLMs往往因过拟合和分布偏移而表现欠佳。MSQA是首个同时评估LLMs事实和推理能力的基准，这对于LLMs在高级材料科学中的应用具有重要意义。

> Despite recent advances in large language models (LLMs) for materials science, there is a lack of benchmarks for evaluating their domain-specific knowledge and complex reasoning abilities. To bridge this gap, we introduce MSQA, a comprehensive evaluation benchmark of 1,757 graduate-level materials science questions in two formats: detailed explanatory responses and binary True/False assessments. MSQA distinctively challenges LLMs by requiring both precise factual knowledge and multi-step reasoning across seven materials science sub-fields, such as structure-property relationships, synthesis processes, and computational modeling. Through experiments with 10 state-of-the-art LLMs, we identify significant gaps in current LLM performance. While API-based proprietary LLMs achieve up to 84.5% accuracy, open-source (OSS) LLMs peak around 60.5%, and domain-specific LLMs often underperform significantly due to overfitting and distributional shifts. MSQA represents the first benchmark to jointly evaluate the factual and reasoning capabilities of LLMs crucial for LLMs in advanced materials science.

[Arxiv](https://arxiv.org/abs/2505.23982)