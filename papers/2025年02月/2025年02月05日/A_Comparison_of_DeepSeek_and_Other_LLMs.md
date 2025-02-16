# DeepSeek与其它大型语言模型对比分析

发布时间：2025年02月05日

`LLM应用` `机器学习`

> A Comparison of DeepSeek and Other LLMs

# 摘要

> 近日，深度求索（DeepSeek）成为了 AI 领域内外关注的焦点。一个有趣的问题是，DeepSeek 与其他大型语言模型（LLMs）相比如何？LLM 可以完成许多任务，本文中，我们使用基于短文本预测结果的任务来进行比较。我们考虑两种设置：作者分类设置和引用分类设置。在第一种设置中，目标是判断一段短文本是由人类还是 AI 编写的。在第二种设置中，目标是根据文本内容将引用分类为四种类型之一。对于每个实验，我们将 DeepSeek 与 4 个流行的 LLM 进行比较：Claude、Gemini、GPT 和 Llama。

我们发现，在分类准确性方面，DeepSeek 在大多数情况下优于 Gemini、GPT 和 Llama，但在性能上略逊于 Claude。我们还发现，DeepSeek 的速度与其他模型相比相对较慢，但使用成本较低，而 Claude 的成本则远高于其他模型。最后，我们发现，在相似性方面，DeepSeek 的输出与 Gemini 和 Claude 的输出最为相似（而在所有 5 个 LLM 中，Claude 和 Gemini 的输出最为相似）。

在本文中，我们还介绍了一个完全标注的数据集，并提出了一种方法，可以利用 LLM 和最近的数据集 MADStat 生成新的数据集。我们论文中的数据集可以作为未来 LLM 研究的基准。


> Recently, DeepSeek has been the focus of attention in and beyond the AI community. An interesting problem is how DeepSeek compares to other large language models (LLMs). There are many tasks an LLM can do, and in this paper, we use the task of predicting an outcome using a short text for comparison. We consider two settings, an authorship classification setting and a citation classification setting. In the first one, the goal is to determine whether a short text is written by human or AI. In the second one, the goal is to classify a citation to one of four types using the textual content. For each experiment, we compare DeepSeek with $4$ popular LLMs: Claude, Gemini, GPT, and Llama.
  We find that, in terms of classification accuracy, DeepSeek outperforms Gemini, GPT, and Llama in most cases, but underperforms Claude. We also find that DeepSeek is comparably slower than others but with a low cost to use, while Claude is much more expensive than all the others. Finally, we find that in terms of similarity, the output of DeepSeek is most similar to those of Gemini and Claude (and among all $5$ LLMs, Claude and Gemini have the most similar outputs).
  In this paper, we also present a fully-labeled dataset collected by ourselves, and propose a recipe where we can use the LLMs and a recent data set, MADStat, to generate new data sets. The datasets in our paper can be used as benchmarks for future study on LLMs.

[Arxiv](https://arxiv.org/abs/2502.03688)