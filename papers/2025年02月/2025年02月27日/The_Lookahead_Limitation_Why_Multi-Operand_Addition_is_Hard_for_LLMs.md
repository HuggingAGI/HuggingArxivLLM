# 多操作数加法难题：LLMs的“向前看”限制

发布时间：2025年02月27日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在处理算术运算时的内在机制和局限性，特别是分析了模型在多操作数加法中的表现不佳的原因。研究深入分析了模型的分词策略及其对算术性能的影响，揭示了模型在数值推理任务中的根本性限制。这些内容属于对LLMs工作原理和局限性的理论分析，因此归类为LLM理论。` `数值推理`

> The Lookahead Limitation: Why Multi-Operand Addition is Hard for LLMs

# 摘要

> 自回归大型语言模型（LLMs）在各类任务中表现出色，但在简单的算术运算，尤其是两个或多个操作数的加法上却表现挣扎。我们发现，这种挣扎源于LLMs采用的一位数前瞻启发式方法。这种方法在两个操作数的加法中表现尚可，但在多操作数加法中却失效，因为此时的进位逻辑更为复杂。我们的探查实验和逐位准确性评估表明，LLMs在需要一位数前瞻不足以处理级联进位的场景中表现失败。我们分析了分词策略对算术性能的影响，发现所有研究的模型，无论采用何种分词方式，由于依赖一位数前瞻启发式方法，在多个操作数的加法中都存在根本性的局限性。我们的研究发现揭示了LLMs在更复杂的数值推理任务中无法有效推广的根本限制。

> Autoregressive large language models (LLMs) exhibit impressive performance across various tasks but struggle with simple arithmetic, such as addition of two or more operands. We show that this struggle arises from LLMs' use of a simple one-digit lookahead heuristic, which works fairly well (but not perfect) for two-operand addition but fails in multi-operand cases, where the carry-over logic is more complex. Our probing experiments and digit-wise accuracy evaluation show that LLMs fail precisely where a one-digit lookahead is insufficient to account for cascading carries. We analyze the impact of tokenization strategies on arithmetic performance and show that all investigated models, regardless of tokenization, are inherently limited in the addition of multiple operands due to their reliance on a one-digit lookahead heuristic. Our findings reveal fundamental limitations that prevent LLMs from generalizing to more complex numerical reasoning.

[Arxiv](https://arxiv.org/abs/2502.19981)