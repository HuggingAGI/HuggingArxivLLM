# 分解、并行规划与合并：面向多约束条件的大型语言模型规划新范式

发布时间：2025年06月03日

`Agent`

> Decompose, Plan in Parallel, and Merge: A Novel Paradigm for Large Language Models based Planning with Multiple Constraints

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但规划任务仍然对基于LLM的代理构成挑战。现有的规划方法面临两个关键限制：严格的约束和级联错误。为了解决这些问题，我们提出了一种新型的并行规划范式——分解、并行规划、合并（DPPM）。具体而言，DPPM基于约束将复杂任务分解为子任务，为每个子任务并行生成子计划，并将它们合并为一个全局计划。此外，我们的方法还集成了一个验证和修正模块，能够进行错误纠正和冲突解决。实验结果表明，DPPM在旅行规划任务中显著优于现有方法。

> Despite significant advances in Large Language Models (LLMs), planning tasks still present challenges for LLM-based agents. Existing planning methods face two key limitations: heavy constraints and cascading errors. To address these limitations, we propose a novel parallel planning paradigm, which Decomposes, Plans for subtasks in Parallel, and Merges subplans into a final plan (DPPM). Specifically, DPPM decomposes the complex task based on constraints into subtasks, generates the subplan for each subtask in parallel, and merges them into a global plan. In addition, our approach incorporates a verification and refinement module, enabling error correction and conflict resolution. Experimental results demonstrate that DPPM significantly outperforms existing methods in travel planning tasks.

[Arxiv](https://arxiv.org/abs/2506.02683)