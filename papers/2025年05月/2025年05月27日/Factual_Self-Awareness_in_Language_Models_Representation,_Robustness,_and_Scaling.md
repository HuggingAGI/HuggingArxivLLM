# 语言模型的事实自我认知：表示、鲁棒性与扩展性

发布时间：2025年05月27日

`LLM理论`

> Factual Self-Awareness in Language Models: Representation, Robustness, and Scaling

# 摘要

> 生成内容中的事实错误是大型语言模型（LLMs）广泛应用中的主要担忧之一。先前研究表明，LLMs有时能够检测其生成内容中的事实错误（即生成后事实核查）。本研究发现，LLMs在生成时具备内部指南，能够决定事实回忆的正确性。具体而言，对于给定的主题实体和关系，LLMs在Transformer的残差流中编码线性特征，这些特征决定了其是否能够回忆正确的属性（即形成有效的实体-关系-属性三元组）。这一自我意识信号对格式的小变化具有鲁棒性。我们通过不同的示例选择策略研究了上下文扰动的影响。跨模型规模和训练动态的扩展实验表明，自我意识在训练中迅速出现，并在中间层达到峰值。这些发现揭示了LLMs内在的自我监控能力，有助于提高其可解释性和可靠性。

> Factual incorrectness in generated content is one of the primary concerns in ubiquitous deployment of large language models (LLMs). Prior findings suggest LLMs can (sometimes) detect factual incorrectness in their generated content (i.e., fact-checking post-generation). In this work, we provide evidence supporting the presence of LLMs' internal compass that dictate the correctness of factual recall at the time of generation. We demonstrate that for a given subject entity and a relation, LLMs internally encode linear features in the Transformer's residual stream that dictate whether it will be able to recall the correct attribute (that forms a valid entity-relation-attribute triplet). This self-awareness signal is robust to minor formatting variations. We investigate the effects of context perturbation via different example selection strategies. Scaling experiments across model sizes and training dynamics highlight that self-awareness emerges rapidly during training and peaks in intermediate layers. These findings uncover intrinsic self-monitoring capabilities within LLMs, contributing to their interpretability and reliability.

[Arxiv](https://arxiv.org/abs/2505.21399)