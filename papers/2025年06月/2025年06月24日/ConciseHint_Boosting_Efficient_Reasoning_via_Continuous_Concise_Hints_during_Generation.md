# ConciseHint：生成过程中的持续简洁提示，助力高效推理

发布时间：2025年06月24日

`LLM应用

理由：这篇论文讨论了如何优化大型推理模型（LRMs）在生成过程中的效率问题，提出了一种名为ConciseHint的框架，通过在生成阶段注入文本提示来引导模型进行简洁表达。这属于对大型语言模型的应用层面的改进，因此归类到LLM应用。` `人工智能` `软件工程`

> ConciseHint: Boosting Efficient Reasoning via Continuous Concise Hints during Generation

# 摘要

> 近期，DeepSeek-R1 和 OpenAI o1 系列等大型推理模型 (LRMs) 通过 Chain-of-Thought (CoT) 扩展生成长度，在复杂推理任务中取得了显著性能提升。然而，这些模型在生成过程中过于冗长，导致效率问题日益突出。现有研究主要关注于推理前的优化方法，如提示或微调，却忽视了在推理生成过程中直接引导模型简洁表达的潜力。为此，我们提出了一种名为 ConciseHint 的框架，通过在推理过程的生成阶段注入文本提示（可手动设计或基于简洁数据训练），持续引导模型进行简洁表达。此外，该框架还能根据查询复杂性自适应调整提示强度，确保性能不受影响。实验结果表明，在 DeepSeek-R1 和 Qwen-3 系列等先进 LRMs 上，我们的方法不仅保持了良好性能，还显著提升了推理过程的简洁性。例如，使用 Qwen-3 4B 在 GSM8K 基准测试中，推理长度减少了 65%，且准确率几无损失。

> Recent advancements in large reasoning models (LRMs) like DeepSeek-R1 and OpenAI o1 series have achieved notable performance enhancements on complex reasoning tasks by scaling up the generation length by Chain-of-Thought (CoT). However, an emerging issue is their inclination to produce excessively verbose reasoning processes, leading to the inefficiency problem. Existing literature on improving efficiency mainly adheres to the before-reasoning paradigms such as prompting and reasoning or fine-tuning and reasoning, but ignores the promising direction of directly encouraging the model to speak concisely by intervening during the generation of reasoning. In order to fill the blank, we propose a framework dubbed ConciseHint, which continuously encourages the reasoning model to speak concisely by injecting the textual hint (manually designed or trained on the concise data) during the token generation of the reasoning process. Besides, ConciseHint is adaptive to the complexity of the query by adaptively adjusting the hint intensity, which ensures it will not undermine model performance. Experiments on the state-of-the-art LRMs, including DeepSeek-R1 and Qwen-3 series, demonstrate that our method can effectively produce concise reasoning processes while maintaining performance well. For instance, we achieve a reduction ratio of 65\% for the reasoning length on GSM8K benchmark with Qwen-3 4B with nearly no accuracy loss.

[Arxiv](https://arxiv.org/abs/2506.18810)