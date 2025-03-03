# ProBench：大型语言模型在竞赛编程中的基准测试

发布时间：2025年02月28日

`LLM应用` `编程竞赛` `人工智能`

> ProBench: Benchmarking Large Language Models in Competitive Programming

# 摘要

> # 摘要  
随着推理型语言模型如 OpenAI-o3 和 DeepSeek-R1 的出现，大型语言模型 (LLMs) 进入了发展的新阶段。然而，现有的代码评估基准逐渐无法充分评估先进 LLM 在代码推理方面的能力。为了弥补这一不足，我们提出了 ProBench，这是一个基于国际大学生程序设计竞赛灵感的编程竞赛基准测试，用于评估 LLM 的能力。  
ProBench 从 Codeforces、Luogu 和 Nowcoder 平台收集了 2024 年 7 月至 12 月期间的一系列编程竞赛问题，并通过在线提交获取真实测试结果，确保评估的公平性和准确性。我们建立了统一的问题属性系统，包括难度分级和算法标签。  
借助 ProBench 中精心收集和标注的数据，我们从多个维度对 9 个最新 LLM 的编程竞赛能力进行了系统性评估，包括思维链分析、错误类型诊断和推理深度评估。实验结果表明，QwQ-32B-Preview 以 20.93 分的成绩位居榜首，紧随其后的是 DeepSeek-V3，得分为 16.38。这表明经过专门推理任务训练的模型在编程方面显著优于通用模型（甚至优于以推理为导向的模型）。  
进一步分析还揭示了编程能力提升的关键领域，例如算法适应性和推理充分性，为未来推理模型的发展提供了重要启示。

> With reasoning language models such as OpenAI-o3 and DeepSeek-R1 emerging, large language models (LLMs) have entered a new phase of development. However, existing benchmarks for coding evaluation are gradually inadequate to assess the capability of advanced LLMs in code reasoning. To bridge the gap for high-level code reasoning assessment, we propose ProBench to benchmark LLMs in competitive programming, drawing inspiration from the International Collegiate Programming Contest. ProBench collects a comprehensive set of competitive programming problems from Codeforces, Luogu, and Nowcoder platforms during the period from July to December 2024, obtaining real test results through online submissions to ensure the fairness and accuracy of the evaluation. We establish a unified problem attribute system, including difficulty grading and algorithm tagging. With carefully collected and annotated data in ProBench, we systematically assess 9 latest LLMs in competitive programming across multiple dimensions, including thought chain analysis, error type diagnosis, and reasoning depth evaluation. Experimental results show that QwQ-32B-Preview achieves the best score of 20.93 followed by DeepSeek-V3 with a score of 16.38, suggesting that models trained with specialized reasoning tasks significantly outperform general-purpose models (even larger than reasoning-oriented models) in programming. Further analysis also reveals key areas for programming capability enhancement, e.g., algorithm adaptability and reasoning sufficiency, providing important insights for the future development of reasoning models.

[Arxiv](https://arxiv.org/abs/2502.20868)