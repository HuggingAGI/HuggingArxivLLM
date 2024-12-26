# 考虑令牌预算的 LLM 推理

发布时间：2024年12月24日

`LLM应用` `语言模型`

> Token-Budget-Aware LLM Reasoning

# 摘要

> 推理对于大型语言模型（LLMs）在众多任务中脱颖而出至关重要。像思维链（CoT）推理这类方法，通过将问题拆解为中间步骤来提升LLM的性能，然而这在令牌使用上产生了大量开销，致使成本上升。我们发现当下LLM的推理过程过于冗长，在提示中纳入合理的令牌预算能够对其进行压缩，不过令牌预算的选择对实际压缩效果起着关键作用。随后，我们提出了一个令牌预算感知的LLM推理框架，它依据推理的复杂程度动态估算不同问题的令牌预算，并利用估算的令牌预算来引导推理过程。实验表明，我们的方法在CoT推理中能有效降低令牌成本，且仅有轻微的性能降低，为LLM推理中平衡效率与准确性提供了切实可行的解决方案。代码：https://github.com/GeniusHTX/TALE。

> Reasoning is critical for large language models (LLMs) to excel in a wide range of tasks. While methods like Chain-of-Thought (CoT) reasoning enhance LLM performance by decomposing problems into intermediate steps, they also incur significant overhead in token usage, leading to increased costs. We find that the reasoning process of current LLMs is unnecessarily lengthy and it can be compressed by including a reasonable token budget in the prompt, but the choice of token budget plays a crucial role in the actual compression effectiveness. We then propose a token-budget-aware LLM reasoning framework, which dynamically estimates token budgets for different problems based on reasoning complexity and uses the estimated token budgets to guide the reasoning process. Experiments show that our method effectively reduces token costs in CoT reasoning with only a slight performance reduction, offering a practical solution to balance efficiency and accuracy in LLM reasoning. Code: https://github.com/GeniusHTX/TALE.

[Arxiv](https://arxiv.org/abs/2412.18547)