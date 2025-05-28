# # 一种以LLM为评判标准的指标，用于弥合与人工评估之间的差距，特别是在软件工程任务中。

发布时间：2025年05月27日

`LLM应用

摘要讨论了大型语言模型在软件开发中的应用，特别是评估生成工件的正确性。SWE-Judge作为一个评估指标，展示了LLM在实际应用中的潜力，属于LLM的应用领域。` `软件工程`

> An LLM-as-Judge Metric for Bridging the Gap with Human Evaluation in SE Tasks

# 摘要

> 大型语言模型（LLMs）和其他自动化技术在软件开发中发挥着越来越重要的作用，它们能够生成代码片段、补丁和注释等软件工件。然而，准确评估这些生成工件的正确性仍然是一个难题。人工评估虽然准确，但耗时且难以扩展；现有自动评估指标虽高效，却常无法准确反映工件质量。

本文提出了一种全新的解决方案——SWE-Judge，这是首个专为准确评估生成软件工件正确性而设计的LLM作为集成裁判的评估指标。SWE-Judge通过五种独立的评估策略，结合动态团队选择机制，生成最终正确性评分。我们在CoNaLa、Card2Code、HumanEval-X、APPS、APR-Assess和Summary-Assess等多个基准测试中评估了SWE-Judge，覆盖代码生成、自动程序修复和代码摘要三大任务。实验结果表明，SWE-Judge与人工判断的一致性显著优于现有指标，提升幅度达5.9%至183.8%。此外，SWE-Judge的评估结果与人工标注者的一致性可媲美代码生成和程序修复任务中的标注者间一致性。这些结果充分展现了SWE-Judge作为高效可靠的替代人工评估方案的潜力。


> Large Language Models (LLMs) and other automated techniques have been increasingly used to support software developers by generating software artifacts such as code snippets, patches, and comments. However, accurately assessing the correctness of these generated artifacts remains a significant challenge. On one hand, human evaluation provides high accuracy but is labor-intensive and lacks scalability. On the other hand, other existing automatic evaluation metrics are scalable and require minimal human effort, but they often fail to accurately reflect the actual correctness of generated software artifacts.
  In this paper, we present SWE-Judge, the first evaluation metric for LLM-as-Ensemble-Judge specifically designed to accurately assess the correctness of generated software artifacts. SWE-Judge first defines five distinct evaluation strategies, each implemented as an independent judge. A dynamic team selection mechanism then identifies the most appropriate subset of judges to produce a final correctness score through ensembling. We evaluate SWE-Judge across a diverse set of software engineering (SE) benchmarks, including CoNaLa, Card2Code, HumanEval-X, APPS, APR-Assess, and Summary-Assess. These benchmarks span three SE tasks: code generation, automated program repair, and code summarization. Experimental results demonstrate that SWE-Judge consistently achieves a higher correlation with human judgments, with improvements ranging from 5.9% to 183.8% over existing automatic metrics. Furthermore, SWE-Judge reaches agreement levels with human annotators that are comparable to inter-annotator agreement in code generation and program repair tasks. These findings underscore SWE-Judge's potential as a scalable and reliable alternative to human evaluation.

[Arxiv](https://arxiv.org/abs/2505.20854)