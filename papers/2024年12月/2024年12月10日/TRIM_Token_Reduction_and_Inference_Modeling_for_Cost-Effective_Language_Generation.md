# TRIM：实现经济高效语言生成的令牌精简与推理建模

发布时间：2024年12月10日

`LLM应用` `知识领域`

> TRIM: Token Reduction and Inference Modeling for Cost-Effective Language Generation

# 摘要

> 大型语言模型（LLMs）的推理成本因其高计算需求而成为重大挑战，尤其在需要长输出的任务中。不过，自然语言往往存在冗余，这为优化带来了契机。我们发现，在恰当提示下，LLMs 能够生成保留关键含义的精炼简洁语言输出。我们提出了一个节省计算成本的框架，即由推理成本更低的较小模型将 LLM 的较短精炼输出重构为完整叙述。我们的实验成果喜人，特别是在一般知识领域，平均节省 20.58%的标记，评估指标仅有轻微下降，这意味着此方法能有效平衡语言处理任务中的效率与准确性。

> The inference cost of Large Language Models (LLMs) is a significant challenge due to their computational demands, specially on tasks requiring long outputs. However, natural language often contains redundancy, which presents an opportunity for optimization. We have observed that LLMs can generate distilled language-concise outputs that retain essential meaning, when prompted appropriately. We propose a framework for saving computational cost, in which a shorter distilled output from the LLM is reconstructed into a full narrative by a smaller model with lower inference costs. Our experiments show promising results, particularly in general knowledge domains with 20.58% saved tokens on average with tiny decrease in evaluation metrics, hinting that this approach can effectively balance efficiency and accuracy in language processing tasks.

[Arxiv](https://arxiv.org/abs/2412.07682)