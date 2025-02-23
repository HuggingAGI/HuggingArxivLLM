# # 强化信息检索

发布时间：2025年02月17日

`LLM应用` `信息检索` `生成增强`

> Reinforced Information Retrieval

# 摘要

> 检索技术在实际应用中虽已广泛应用，但在跨领域场景下仍面临重大挑战。最近，生成增强方法作为一种有前景的解决方案应运而生。这些方法通过整合基于LLM的生成器提供的额外信息来增强原始查询，从而更直接地检索相关文档。然而，现有方法在处理需要大量领域专业知识的高专业性场景时仍然力不从心。为了解决这一问题，我们提出了	extbf{Reinforced-IR}，这是一种通过联合调整预训练检索器和生成器来实现精准跨领域检索的全新方法。Reinforced-IR的核心创新在于其	extbf{Self-Boosting}框架，该框架使检索器和生成器能够互相学习对方的反馈。具体来说，生成器被强化以生成能够提升检索器性能的查询增强，同时检索器则被训练以更好地识别生成器所确定的相关文档。这一迭代过程利用目标域的无标签语料库，逐步优化端到端检索性能。在我们的实验中，Reinforced-IR显著超越现有领域自适应方法，大幅提升了各类应用场景下的检索质量。

> While retrieval techniques are widely used in practice, they still face significant challenges in cross-domain scenarios. Recently, generation-augmented methods have emerged as a promising solution to this problem. These methods enhance raw queries by incorporating additional information from an LLM-based generator, facilitating more direct retrieval of relevant documents. However, existing methods struggle with highly specialized situations that require extensive domain expertise. To address this problem, we present \textbf{Reinforced-IR}, a novel approach that jointly adapts a pre-trained retriever and generator for precise cross-domain retrieval. A key innovation of Reinforced-IR is its \textbf{Self-Boosting} framework, which enables retriever and generator to learn from each other's feedback. Specifically, the generator is reinforced to generate query augmentations that enhance the retriever's performance, while the retriever is trained to better discriminate the relevant documents identified by the generator. This iterative process allows the end-to-end retrieval performance to be progressively optimized using an unlabeled corpus from the target domain. In our experiment, Reinforced-IR outperforms existing domain adaptation methods by a large margin, leading to substantial improvements in retrieval quality across a wide range of application scenarios.

[Arxiv](https://arxiv.org/abs/2502.11562)