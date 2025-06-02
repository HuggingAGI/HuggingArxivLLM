# 大型语言模型邂逅约束传播

发布时间：2025年05月29日

`LLM应用

摘要中讨论了如何改进大型语言模型（LLMs）在文本生成任务中的表现，特别是通过集成约束编程（CP）和掩码语言模型（MLMs）来增强生成的可靠性和约束满足能力。这种方法属于对LLM的应用改进，因此归类为LLM应用。` `内容生成`

> Large Language Model Meets Constraint Propagation

# 摘要

> 大型语言模型（LLMs）在生成流畅文本方面表现出色，但难以有效施加外部约束，因为它们在没有显式控制机制的情况下按顺序生成标记。GenCP通过将LLM预测与约束编程（CP）推理相结合，将文本生成建模为一个约束满足问题（CSP），从而解决了这一局限性。在本文中，我们通过集成掩码语言模型（MLMs）来改善GenCP在领域生成方面的表现，这使得双向约束传播成为可能，充分利用了过去和未来的标记。这种集成弥合了标记级预测与结构化约束施加之间的差距，从而实现了更可靠且符合约束的文本生成。我们在COLLIE基准上的评估表明，通过MLM调用引入领域预览显著提升了GenCP的性能。尽管这种方法增加了MLM调用次数，并在某些情况下增加了回溯次数，但总体效果是更高效地利用LLM推理，并增强了生成可行且有意义解决方案的能力，特别是在内容约束严格的任务中。


> Large Language Models (LLMs) excel at generating fluent text but struggle to enforce external constraints because they generate tokens sequentially without explicit control mechanisms. GenCP addresses this limitation by combining LLM predictions with Constraint Programming (CP) reasoning, formulating text generation as a Constraint Satisfaction Problem (CSP). In this paper, we improve GenCP by integrating Masked Language Models (MLMs) for domain generation, which allows bidirectional constraint propagation that leverages both past and future tokens. This integration bridges the gap between token-level prediction and structured constraint enforcement, leading to more reliable and constraint-aware text generation. Our evaluation on COLLIE benchmarks demonstrates that incorporating domain preview via MLM calls significantly improves GenCP's performance. Although this approach incurs additional MLM calls and, in some cases, increased backtracking, the overall effect is a more efficient use of LLM inferences and an enhanced ability to generate feasible and meaningful solutions, particularly in tasks with strict content constraints.

[Arxiv](https://arxiv.org/abs/2505.24012)