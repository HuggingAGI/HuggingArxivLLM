# FinS-Pilot：在线金融系统基准测试

发布时间：2025年05月30日

`RAG`

> FinS-Pilot: A Benchmark for Online Financial System

# 摘要

> 大型语言模型（LLMs）在多个专业领域展现出了卓越的能力，但其在金融领域的评估却因数据保密和动态数据整合的限制而受到制约。为了解决这一难题，我们推出了FinS-Pilot——一个专为在线金融应用设计的全新RAG系统评估基准。该基准基于真实的金融助手交互数据构建，整合了实时API数据和结构化文本来源，并通过涵盖股票分析和宏观经济预测等关键金融领域的意图分类框架进行组织。通过与多个中国领先的大型语言模型进行系统性实验，我们验证了FinS-Pilot在识别适合金融应用的模型方面的能力，同时填补了金融领域专用评估工具的空白。我们的工作不仅提供了一个实用的评估框架，还整理了一个专门的数据集，为金融NLP系统的研究提供了重要支持。相关代码和数据集已在GitHub上开放ootnote{https://github.com/PhealenWang/financial\_rag\_benchmark}。

> Large language models (LLMs) have demonstrated remarkable capabilities across various professional domains, with their performance typically evaluated through standardized benchmarks. However, the development of financial RAG benchmarks has been constrained by data confidentiality issues and the lack of dynamic data integration. To address this issue, we introduces FinS-Pilot, a novel benchmark for evaluating RAG systems in online financial applications. Constructed from real-world financial assistant interactions, our benchmark incorporates both real-time API data and structured text sources, organized through an intent classification framework covering critical financial domains such as equity analysis and macroeconomic forecasting. The benchmark enables comprehensive evaluation of financial assistants' capabilities in handling both static knowledge and time-sensitive market information. Through systematic experiments with multiple Chinese leading LLMs, we demonstrate FinS-Pilot's effectiveness in identifying models suitable for financial applications while addressing the current gap in specialized evaluation tools for the financial domain. Our work contributes both a practical evaluation framework and a curated dataset to advance research in financial NLP systems. The code and dataset are accessible on GitHub\footnote{https://github.com/PhealenWang/financial\_rag\_benchmark}.

[Arxiv](https://arxiv.org/abs/2506.02037)