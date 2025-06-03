# 并非所有令牌都需要遗忘：选择性遗忘以限制大型语言模型遗忘中的效用变化

发布时间：2025年06月01日

`LLM理论` `隐私保护` `人工智能`

> Not Every Token Needs Forgetting: Selective Unlearning to Limit Change in Utility in Large Language Model Unlearning

# 摘要

> 大型语言模型的遗忘机制近期受到广泛关注，这一机制旨在从模型中移除不需要的信息，例如私人、敏感或受版权保护的内容。然而，传统的遗忘方法不分青红皂白地更新模型参数，使模型忘记目标文档中的所有 token，包括携带通用知识的常见 token（如代词、介词、普通名词）。本文中，我们指出并非所有 token 都需要遗忘。我们提出选择性遗忘 (SU)，该方法识别出与不需要信息相关的遗忘集合中的关键 token 子集，并仅对这些 token 进行遗忘。实验结果表明，选择性遗忘不仅有效实现了目标数据的遗忘，还显著保留了模型在保留数据集中的实用性。

> Large Language Model (LLM) unlearning has recently gained significant attention, driven by the need to remove unwanted information, such as private, sensitive, or copyrighted content, from LLMs. However, conventional unlearning approaches indiscriminately update model parameters to forget all tokens in a target document, including common tokens (e.g., pronouns, prepositions, general nouns) that carry general knowledge. In this paper, we highlight that not every token needs forgetting. We propose Selective Unlearning (SU), which identifies a critical subset of tokens within the forgetting set that is relevant to the unwanted information, and unlearns only those tokens. Experiments on two benchmarks and six baseline unlearning algorithms demonstrate that SU not only achieves effective unlearning on the targeted forget data, but also significantly preserves the model's utility in the retaining set.

[Arxiv](https://arxiv.org/abs/2506.00876)