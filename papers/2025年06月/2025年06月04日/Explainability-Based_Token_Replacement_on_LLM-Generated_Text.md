# 基于可解释性的标记替换应用于LLM生成的文本

发布时间：2025年06月04日

`LLM应用

理由：这篇论文探讨了如何利用可解释性人工智能（XAI）方法来降低AI生成文本（AIGT）的可检测性，并提出了一种稳健的基于集成的检测方法。研究集中在生成模型的应用层面，特别是如何优化生成过程和检测技术，因此属于LLM应用类别。` `人工智能` `内容安全`

> Explainability-Based Token Replacement on LLM-Generated Text

# 摘要

> 生成模型，尤其是大型语言模型（LLMs），在生成人类风格文本方面取得了显著进展。然而，AI生成的文本往往具有可识别的模式，这让它们比人类写作更容易被辨别。本文探讨了如何利用可解释性人工智能（XAI）方法降低AI生成文本（AIGT）的可检测性，同时提出了一种稳健的基于集成的检测方法。我们首先训练一个集成分类器来区分AIGT和人类写作，随后应用SHAP和LIME来识别对预测影响最大的标记。我们提出了四种基于可解释性的标记替换策略来修改这些关键标记。实验结果表明，这些替换方法能显著削弱单一分类器检测AIGT的能力。然而，我们的集成分类器在多种语言和领域中仍表现出色，证明了多模型方法能有效缓解基于标记的操作带来的影响。这些结果表明，通过关注最具影响力的标记，XAI方法可以显著降低AIGT的可检测性。同时，它们也强调了开发稳健、基于集成的检测策略的重要性，以应对日益复杂的隐藏AIGT的方法。

> Generative models, especially large language models (LLMs), have shown remarkable progress in producing text that appears human-like. However, they often exhibit patterns that make their output easier to detect than text written by humans. In this paper, we investigate how explainable AI (XAI) methods can be used to reduce the detectability of AI-generated text (AIGT) while also introducing a robust ensemble-based detection approach. We begin by training an ensemble classifier to distinguish AIGT from human-written text, then apply SHAP and LIME to identify tokens that most strongly influence its predictions. We propose four explainability-based token replacement strategies to modify these influential tokens. Our findings show that these token replacement approaches can significantly diminish a single classifier's ability to detect AIGT. However, our ensemble classifier maintains strong performance across multiple languages and domains, showing that a multi-model approach can mitigate the impact of token-level manipulations. These results show that XAI methods can make AIGT harder to detect by focusing on the most influential tokens. At the same time, they highlight the need for robust, ensemble-based detection strategies that can adapt to evolving approaches for hiding AIGT.

[Arxiv](https://arxiv.org/abs/2506.04050)