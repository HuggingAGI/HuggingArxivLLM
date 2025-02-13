# 忠实、不忠实，还是模糊？基于初始立场的多智能体辩论用于评估摘要

发布时间：2025年02月12日

`LLM应用` `信息检索`

> Faithful, Unfaithful or Ambiguous? Multi-Agent Debate with Initial Stance for Summary Evaluation

# 摘要

> 基于大型语言模型（LLMs）的忠实度评估器容易被文本的流畅性所迷惑，难以发现摘要中的错误。我们提出了一种摘要忠实度评估方法，其中多个基于LLM的代理被分配初始立场，并被迫提出理由来证明被强加的信念，从而进行多轮辩论以达成一致。均匀分布的初始立场分配带来了更大的立场多样性，进而产生更有意义的辩论，最终发现更多错误。此外，通过分析最近的忠实度评估数据集，我们发现摘要并不总是要么忠实于源文档，要么不忠实。因此，我们引入了一个新的维度——模糊性，并制定了详细的分类法来识别此类特殊情况。实验表明，我们的方法有助于识别模糊性，并在非模糊摘要上表现更佳。

> Faithfulness evaluators based on large language models (LLMs) are often fooled by the fluency of the text and struggle with identifying errors in the summaries. We propose an approach to summary faithfulness evaluation in which multiple LLM-based agents are assigned initial stances (regardless of what their belief might be) and forced to come up with a reason to justify the imposed belief, thus engaging in a multi-round debate to reach an agreement. The uniformly distributed initial assignments result in a greater diversity of stances leading to more meaningful debates and ultimately more errors identified. Furthermore, by analyzing the recent faithfulness evaluation datasets, we observe that naturally, it is not always the case for a summary to be either faithful to the source document or not. We therefore introduce a new dimension, ambiguity, and a detailed taxonomy to identify such special cases. Experiments demonstrate our approach can help identify ambiguities, and have even a stronger performance on non-ambiguous summaries.

[Arxiv](https://arxiv.org/abs/2502.08514)