# 基于RLHF对齐的语言模型通过输出子空间边界上的Logit抑制偏离非答案

发布时间：2025年05月28日

`LLM应用` `人工智能` `内容安全`

> Derailing Non-Answers via Logit Suppression at Output Subspace Boundaries in RLHF-Aligned Language Models

# 摘要

> 我们提出了一种无需修改模型权重或提示词，就能有效降低大型语言模型（LLMs）对敏感内容拒绝率的方法。通过观察发现，某些模型的拒绝行为往往在特定标记序列之后出现，这个序列标记了链式思维（CoT）块的开始（_model），接着是一个双换行符（\n\n）。我们研究了在生成过程中两种简单的格式调整：抑制_model后的\n\n，以及抑制CoT块结束后的序列结束标记（_model）。我们的方法不需要额外的数据集、参数调整或训练，仅通过在生成过程中调整标记概率即可实现。在我们对官方DeepSeek-R1蒸馏模型的实验中，这些干预措施显著增加了对敏感提示的实质性回答比例，同时保持了在标准基准测试中的性能。研究结果表明，通过在生成过程中的关键点阻止拒绝子空间，我们可以有效规避模型的拒绝行为。

> We introduce a method to reduce refusal rates of large language models (LLMs) on sensitive content without modifying model weights or prompts. Motivated by the observation that refusals in certain models were often preceded by the specific token sequence of a token marking the beginning of the chain-of-thought (CoT) block (<think>) followed by a double newline token (\n\n), we investigate the impact of two simple formatting adjustments during generation: suppressing \n\n after <think> and suppressing the end-of-sequence token after the end of the CoT block (</think>). Our method requires no datasets, parameter changes, or training, relying solely on modifying token probabilities during generation. In our experiments with official DeepSeek-R1 distillations, these interventions increased the proportion of substantive answers to sensitive prompts without affecting performance on standard benchmarks. Our findings suggest that refusal behaviors can be circumvented by blocking refusal subspaces at specific points in the generation process.

[Arxiv](https://arxiv.org/abs/2505.23848)