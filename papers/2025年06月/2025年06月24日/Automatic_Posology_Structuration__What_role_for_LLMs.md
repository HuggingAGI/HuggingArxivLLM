# 自动剂量结构化：LLMs在此扮演什么角色？

发布时间：2025年06月24日

`LLM应用

摘要讨论了使用大型语言模型（LLMs）来处理法语处方中的给药说明结构化问题，并比较了不同方法的性能，探讨了LLMs在临床应用中的实际解决方案。这属于将LLMs应用于具体任务的研究，因此归类为LLM应用。`

> Automatic Posology Structuration : What role for LLMs?

# 摘要

> 自动结构化给药说明对于提升用药安全性和支持临床决策至关重要。然而，在法语处方中，给药说明常因模糊、不规则或口语化而影响传统机器学习流水线的效果。我们尝试使用大型语言模型（LLMs）将自由文本的给药说明转化为结构化格式，并对比了基于提示的方法和微调模型与基于命名实体识别与链接（NERL）的“pre-LLM”系统的性能。结果显示，尽管提示式方法有所提升，但仅微调后的LLMs能达到基线的准确性。通过错误分析，我们发现NERL在结构上更精准，而LLMs更擅长处理语义细微差别。基于此，我们提出了一种混合流水线，将NERL信心分数低于0.8的案例路由到LLM，并根据信心分数选择输出。这种方法在最小化延迟和计算成本的同时，实现了91%的结构化准确率。我们的结果显示，这种混合方法不仅提高了结构化准确性，还降低了计算成本，为现实世界的临床应用提供了一种可扩展的解决方案。

> Automatically structuring posology instructions is essential for improving medication safety and enabling clinical decision support. In French prescriptions, these instructions are often ambiguous, irregular, or colloquial, limiting the effectiveness of classic ML pipelines. We explore the use of Large Language Models (LLMs) to convert free-text posologies into structured formats, comparing prompt-based methods and fine-tuning against a "pre-LLM" system based on Named Entity Recognition and Linking (NERL). Our results show that while prompting improves performance, only fine-tuned LLMs match the accuracy of the baseline. Through error analysis, we observe complementary strengths: NERL offers structural precision, while LLMs better handle semantic nuances. Based on this, we propose a hybrid pipeline that routes low-confidence cases from NERL (<0.8) to the LLM, selecting outputs based on confidence scores. This strategy achieves 91% structuration accuracy while minimizing latency and compute. Our results show that this hybrid approach improves structuration accuracy while limiting computational cost, offering a scalable solution for real-world clinical use.

[Arxiv](https://arxiv.org/abs/2506.19525)