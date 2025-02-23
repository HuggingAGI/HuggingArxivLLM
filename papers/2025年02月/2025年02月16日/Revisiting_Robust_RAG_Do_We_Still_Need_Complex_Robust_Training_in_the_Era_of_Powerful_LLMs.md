# # 重新审视鲁棒 RAG：在强大的 LLM 时代下，是否仍需复杂鲁棒训练？

发布时间：2025年02月16日

`RAG` `人工智能`

> Revisiting Robust RAG: Do We Still Need Complex Robust Training in the Era of Powerful LLMs?

# 摘要

> 检索增强生成（RAG）系统在面对噪声或不相关文档时，性能往往会下降，因此研究人员开发了复杂的训练策略以提高其对检索噪声的鲁棒性。然而，随着大型语言模型（LLMs）的不断进步，这些复杂训练方法的必要性逐渐受到质疑。在本文中，我们系统研究了随着模型能力的提升，复杂的稳健训练策略是否仍然必要。通过涵盖多种模型架构和参数规模的全面实验，我们在不同数据集上评估了多种文档选择方法和对抗训练技术。我们的大量实验一致表明，随着模型变得更强大，复杂稳健训练方法带来的性能提升显著下降。我们深入探讨其原因，发现更强大的模型在本质上表现出更优的信心校准能力，更好的跨数据集泛化能力（即使在随机选择文档进行训练时也是如此），以及通过更简单策略学习到的最优注意力机制。我们的研究结果表明，随着模型变得更为强大，RAG系统可以通过更简单的架构和训练策略获益，从而实现更易于扩展的应用，同时保持极低的复杂度。

> Retrieval-augmented generation (RAG) systems often suffer from performance degradation when encountering noisy or irrelevant documents, driving researchers to develop sophisticated training strategies to enhance their robustness against such retrieval noise. However, as large language models (LLMs) continue to advance, the necessity of these complex training methods is increasingly questioned. In this paper, we systematically investigate whether complex robust training strategies remain necessary as model capacity grows. Through comprehensive experiments spanning multiple model architectures and parameter scales, we evaluate various document selection methods and adversarial training techniques across diverse datasets. Our extensive experiments consistently demonstrate that as models become more powerful, the performance gains brought by complex robust training methods drop off dramatically. We delve into the rationale and find that more powerful models inherently exhibit superior confidence calibration, better generalization across datasets (even when trained with randomly selected documents), and optimal attention mechanisms learned with simpler strategies. Our findings suggest that RAG systems can benefit from simpler architectures and training strategies as models become more powerful, enabling more scalable applications with minimal complexity.

[Arxiv](https://arxiv.org/abs/2502.11400)