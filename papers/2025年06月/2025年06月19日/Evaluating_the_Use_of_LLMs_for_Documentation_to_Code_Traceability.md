# # 大型语言模型在文档到代码可追溯性中的应用评估

发布时间：2025年06月19日

`LLM应用` `软件工程` `文档到代码可追溯性`

> Evaluating the Use of LLMs for Documentation to Code Traceability

# 摘要

> 大型语言模型（LLMs）为文档到代码的可追溯性带来了新机遇，但其潜力尚未被充分挖掘。我们对三种主流LLM（Claude 3.5 Sonnet、GPT-4o 和 o3-mini）进行了全面评估，测试它们在连接软件文档（如API参考和用户指南）与源代码方面的能力。基于Unity Catalog 和 Crawl4AI 两个开源项目，我们创建了两个新型数据集。通过系统性实验，我们重点评估了三项核心能力：追溯链接识别的准确度、关系解释的质量，以及多步骤链路的重建效果。

实验结果令人振奋：最优LLM在两个数据集上的F1分数分别达到79.4%和80.4%，远超传统方法（TF-IDF、BM25 和 CodeBERT）。尽管完全正确的关系解释占比在42.9%到71.1%之间，但部分准确率高达97%，表明基本关联极少被遗漏。在多步骤链路重建中，LLMs在关键节点的识别上表现出色，但在中间环节的捕捉上存在差异。

深入分析发现，误报主要源于命名假设、幻影链接以及对架构模式的过度概括。我们还发现，任务框架（如采用一对一匹配策略）对模型性能至关重要。这些发现不仅凸显了LLMs在追溯发现中的巨大潜力，也指出了其局限性，提示未来工具设计中需要引入人工干预，并为后续研究提供了重要方向。

> Large Language Models (LLMs) offer new potential for automating documentation-to-code traceability, yet their capabilities remain underexplored. We present a comprehensive evaluation of LLMs (Claude 3.5 Sonnet, GPT-4o, and o3-mini) in establishing trace links between various software documentation (including API references and user guides) and source code. We create two novel datasets from two open-source projects (Unity Catalog and Crawl4AI). Through systematic experiments, we assess three key capabilities: (1) trace link identification accuracy, (2) relationship explanation quality, and (3) multi-step chain reconstruction. Results show that the best-performing LLM achieves F1-scores of 79.4% and 80.4% across the two datasets, substantially outperforming our baselines (TF-IDF, BM25, and CodeBERT). While fully correct relationship explanations range from 42.9% to 71.1%, partial accuracy exceeds 97%, indicating that fundamental connections are rarely missed. For multi-step chains, LLMs maintain high endpoint accuracy but vary in capturing precise intermediate links. Error analysis reveals that many false positives stem from naming-based assumptions, phantom links, or overgeneralization of architectural patterns. We demonstrate that task-framing, such as a one-to-many matching strategy, is critical for performance. These findings position LLMs as powerful assistants for trace discovery, but their limitations could necessitate human-in-the-loop tool design and highlight specific error patterns for future research.

[Arxiv](https://arxiv.org/abs/2506.16440)