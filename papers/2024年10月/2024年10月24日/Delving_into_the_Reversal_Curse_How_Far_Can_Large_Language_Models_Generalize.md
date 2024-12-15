# 深入探寻反转之咒：大型语言模型的泛化能力究竟能走多远？

发布时间：2024年10月24日

`LLM理论` `语言模型` `泛化能力`

> Delving into the Reversal Curse: How Far Can Large Language Models Generalize?

# 摘要

> 尽管大型语言模型（LLMs）展现出了前所未有的强大能力，但在应对看似简单的任务时，它们也暴露出了一些固有的缺陷。其中一个典型的例子就是近期备受争议的“反转诅咒”，即模型在接受了“A 是 B”的训练后，却难以将此知识推广从而推断出“B 是 A”。在本文中，我们对“反转诅咒”在各类任务中的表现进行了研究，并深入探究了 LLMs 的泛化能力和问题解决机制。此次研究得出了一系列重要结论：（1）当 A 和 B 都在上下文中呈现时，比如在选择题中，LLMs 能够将其泛化到“B 是 A”。（2）这种泛化能力与训练文档中“A 是 B”这一事实的结构密切相关。例如，这种泛化仅适用于“[姓名]是[描述]”结构的传记，而不适用于“[描述]是[姓名]”。（3）我们提出并验证了一个假设，即在知识应用过程中，LLMs 在事实回忆方面存在内在偏差，这解释并突显了文档结构对于成功学习的重要性。（4）这种偏差对 LLMs 下游性能的负面影响很难仅通过训练来缓解。基于这些有趣的发现，我们的工作不仅从 LLMs 的内在工作机制为解释其泛化能力提供了新视角，还为开发更有效的 LLMs 学习方法带来了新的启示。

> While large language models (LLMs) showcase unprecedented capabilities, they also exhibit certain inherent limitations when facing seemingly trivial tasks. A prime example is the recently debated "reversal curse", which surfaces when models, having been trained on the fact "A is B", struggle to generalize this knowledge to infer that "B is A". In this paper, we examine the manifestation of the reversal curse across various tasks and delve into both the generalization abilities and the problem-solving mechanisms of LLMs. This investigation leads to a series of significant insights: (1) LLMs are able to generalize to "B is A" when both A and B are presented in the context as in the case of a multiple-choice question. (2) This generalization ability is highly correlated to the structure of the fact "A is B" in the training documents. For example, this generalization only applies to biographies structured in "[Name] is [Description]" but not to "[Description] is [Name]". (3) We propose and verify the hypothesis that LLMs possess an inherent bias in fact recalling during knowledge application, which explains and underscores the importance of the document structure to successful learning. (4) The negative impact of this bias on the downstream performance of LLMs can hardly be mitigated through training alone. Based on these intriguing findings, our work not only presents a novel perspective for interpreting LLMs' generalization abilities from their intrinsic working mechanism but also provides new insights for the development of more effective learning methods for LLMs.

[Arxiv](https://arxiv.org/abs/2410.18808)