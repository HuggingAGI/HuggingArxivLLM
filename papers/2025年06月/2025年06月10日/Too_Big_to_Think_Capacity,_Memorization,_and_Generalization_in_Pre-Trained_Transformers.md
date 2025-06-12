# # 太大而不能思考：预训练Transformer中的容量、记忆化与泛化能力
预训练Transformer模型在自然语言处理（NLP）任务中取得了显著成功，但它们的行为和性质尚未完全理解，尤其是在容量、记忆化与泛化方面。

发布时间：2025年06月10日

`LLM理论` `人工智能` `机器学习`

> Too Big to Think: Capacity, Memorization, and Generalization in Pre-Trained Transformers

# 摘要

> 大型语言模型（LLMs）中记忆与泛化的相互关系仍然是一个开放的研究领域，越来越多的证据表明，两者之间有着深刻的联系。在本研究中，我们通过从头训练一系列容量受限的Transformer模型，分别在两个合成的字符级任务上探究了这一关系。这两个任务分别通过算术外推和事实记忆来单独考察模型的泛化和记忆能力。我们的观察结果显示出一致的权衡：小型模型能够外推到未见的算术案例，但却无法记住事实；而大型模型能够记住事实，但却无法外推。中等容量的模型也表现出类似的向记忆的转变。当模型同时在这两项任务上进行训练时，无论模型大小如何，都无法成功实现外推。这些发现表明，预训练可能内在地倾向于一种学习模式，而忽视另一种。通过在受控环境下隔离这些动态，我们的研究揭示了模型容量如何塑造学习行为，并为小型语言模型的设计和部署提供了更广泛的启示。

> The relationship between memorization and generalization in large language models (LLMs) remains an open area of research, with growing evidence that the two are deeply intertwined. In this work, we investigate this relationship by pre-training a series of capacity-limited Transformer models from scratch on two synthetic character-level tasks designed to separately probe generalization (via arithmetic extrapolation) and memorization (via factual recall). We observe a consistent trade-off: small models extrapolate to unseen arithmetic cases but fail to memorize facts, while larger models memorize but fail to extrapolate. An intermediate-capacity model exhibits a similar shift toward memorization. When trained on both tasks jointly, no model (regardless of size) succeeds at extrapolation. These findings suggest that pre-training may intrinsically favor one learning mode over the other. By isolating these dynamics in a controlled setting, our study offers insight into how model capacity shapes learning behavior and offers broader implications for the design and deployment of small language models.

[Arxiv](https://arxiv.org/abs/2506.09099)