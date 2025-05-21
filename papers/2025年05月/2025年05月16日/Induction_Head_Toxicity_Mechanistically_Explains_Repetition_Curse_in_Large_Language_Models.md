# # 归纳头毒性机制性解释大型语言模型中的重复诅咒现象

发布时间：2025年05月16日

`LLM理论`

> Induction Head Toxicity Mechanistically Explains Repetition Curse in Large Language Models

# 摘要

> 重复诅咒是大型语言模型 (LLMs) 生成重复标记序列或循环序列的现象。尽管这一现象已被广泛观察到，但其内在机制仍不为人所知。本研究聚焦于诱导头——一类擅长上下文学习的注意力头——在重复行为中的作用。我们特别关注诱导头的“毒性”，即它们在重复过程中主导模型输出对数概率，从而抑制其他注意力头参与生成过程的倾向。我们的研究发现对 LLM 的设计与训练具有重要启示。通过揭示诱导头是重复诅咒的关键驱动力，我们不仅为这一现象提供了机制解释，还提出了潜在的缓解策略。此外，我们还提出了一种注意力头正则化技术，旨在减少诱导头在生成过程中的主导地位，从而促进输出的多样性和连贯性。

> Repetition curse is a phenomenon where Large Language Models (LLMs) generate repetitive sequences of tokens or cyclic sequences. While the repetition curse has been widely observed, its underlying mechanisms remain poorly understood. In this work, we investigate the role of induction heads--a specific type of attention head known for their ability to perform in-context learning--in driving this repetitive behavior. Specifically, we focus on the "toxicity" of induction heads, which we define as their tendency to dominate the model's output logits during repetition, effectively excluding other attention heads from contributing to the generation process. Our findings have important implications for the design and training of LLMs. By identifying induction heads as a key driver of the repetition curse, we provide a mechanistic explanation for this phenomenon and suggest potential avenues for mitigation. We also propose a technique with attention head regularization that could be employed to reduce the dominance of induction heads during generation, thereby promoting more diverse and coherent outputs.

[Arxiv](https://arxiv.org/abs/2505.13514)