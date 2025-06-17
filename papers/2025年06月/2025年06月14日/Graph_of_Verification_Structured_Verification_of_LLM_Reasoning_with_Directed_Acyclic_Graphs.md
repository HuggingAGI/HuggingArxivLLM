# # 验证图：基于有向无环图的大型语言模型推理结构化验证

发布时间：2025年06月14日

`LLM理论` `人工智能` `计算机科学`

> Graph of Verification: Structured Verification of LLM Reasoning with Directed Acyclic Graphs

# 摘要

> 在大型语言模型（LLMs）中验证复杂多步推理的可靠性仍是一个核心挑战，现有方法往往难以兼顾准确性和忠实性。为此，我们提出了验证图（GoV）框架，它在推理验证领域做出了三项重要贡献：首先，GoV将推理过程显式建模为有向无环图（DAG），无论该结构是隐含的还是显式构建的。其次，通过施加拓扑顺序，GoV能够有效指导分步验证过程。第三，GoV引入了可定制节点块的概念，这些块能够灵活定义验证粒度，从原子命题到完整段落，并确保每个验证单元都能获取到从图中推导出的所有必要前提作为上下文输入。我们在具有不同推理复杂度的数字三角形求和任务和ProcessBench基准上对GoV进行了评估。实验结果表明，与传统的端到端验证方法相比，GoV在验证准确性、忠实性和错误定位方面均实现了显著提升。我们的代码和数据可在https://github.com/Frevor/Graph-of-Verification获取。

> Verifying the reliability of complex, multi-step reasoning in Large Language Models (LLMs) remains a fundamental challenge, as existing methods often lack both faithfulness and precision. To address this issue, we propose the Graph of Verification (GoV) framework. GoV offers three key contributions: First, it explicitly models the underlying deductive process as a directed acyclic graph (DAG), whether this structure is implicit or explicitly constructed. Second, it enforces a topological order over the DAG to guide stepwise verification. Third, GoV introduces the notion of customizable node blocks, which flexibly define the verification granularity, from atomic propositions to full paragraphs, while ensuring that all requisite premises derived from the graph are provided as contextual input for each verification unit. We evaluate GoV on the Number Triangle Summation task and the ProcessBench benchmark with varying levels of reasoning complexity. Experimental results show that GoV substantially improves verification accuracy, faithfulness, and error localization when compared to conventional end-to-end verification approaches. Our code and data are available at https://github.com/Frevor/Graph-of-Verification.

[Arxiv](https://arxiv.org/abs/2506.12509)