# 大型语言模型在匿名化数据上的时间问答能力研究

发布时间：2025年04月10日

`LLM应用` `数据处理`

> On the Temporal Question-Answering Capabilities of Large Language Models Over Anonymized Data

# 摘要

> 大型语言模型（LLMs）在处理未出现在训练数据中的时间推理任务中的应用仍是一个值得探索的领域。本文聚焦于结构化和半结构化匿名数据，不仅构建了直接的LLM流水线，还进行了多方法比较与深入分析。我们识别并研究了自然语言中十七种常见的时序推理任务，重点关注其算法组件。为了评估LLM的表现，我们创建了	extit{推理与时间推理能力}数据集（RATA），该数据集采用半结构化匿名数据，以确保依赖推理而非先前知识。我们比较了多种方法，包括针对此场景特别调整的最先进（SoTA）技术，如思路树、自我反思和代码执行。我们的研究结果表明，仅靠独立的LLMs难以实现可扩展且可靠的解决方案，强调了集成方法的重要性。

> The applicability of Large Language Models (LLMs) in temporal reasoning tasks over data that is not present during training is still a field that remains to be explored. In this paper we work on this topic, focusing on structured and semi-structured anonymized data. We not only develop a direct LLM pipeline, but also compare various methodologies and conduct an in-depth analysis. We identified and examined seventeen common temporal reasoning tasks in natural language, focusing on their algorithmic components. To assess LLM performance, we created the \textit{Reasoning and Answering Temporal Ability} dataset (RATA), featuring semi-structured anonymized data to ensure reliance on reasoning rather than on prior knowledge. We compared several methodologies, involving SoTA techniques such as Tree-of-Thought, self-reflexion and code execution, tuned specifically for this scenario. Our results suggest that achieving scalable and reliable solutions requires more than just standalone LLMs, highlighting the need for integrated approaches.

[Arxiv](https://arxiv.org/abs/2504.07646)