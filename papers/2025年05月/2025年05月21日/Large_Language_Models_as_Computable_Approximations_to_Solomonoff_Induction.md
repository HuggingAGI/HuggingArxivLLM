# 大型语言模型：Solomonoff归纳的可计算近似

发布时间：2025年05月21日

`LLM理论` `计算机科学` `人工智能`

> Large Language Models as Computable Approximations to Solomonoff Induction

# 摘要

> 大型语言模型（LLMs）的快速发展亟需一个严谨的理论框架来解释其成功。尽管我们对LLM行为的理解取得了显著进展，但现有理论框架仍难以通过统一的数学视角解释各种涌现现象。我们通过证明两个关键结果，首次建立了LLM架构与算法信息论（AIT）之间的正式联系：(1) 训练过程通过损失最小化（即程序长度优化）计算上近似了所罗门诺夫先验；(2) 下一令牌预测实现了所罗门诺夫归纳的近似。我们借助算法信息论，为上下文学习、少样本学习和缩放定律提供了一个统一的理论解释。此外，我们的理论发现为一种基于原则的少样本示例选择方法提供了支持，该方法优先选择模型预测置信度较低的样本。通过在多种文本分类基准上的实验，我们证明与选择高置信度示例相比，该策略在较小的模型架构上带来了显著的性能提升。我们的框架弥合了理论基础与实际LLM行为之间的差距，为未来模型开发提供了强大的解释能力和实用见解。

> The rapid advancement of large language models (LLMs) calls for a rigorous theoretical framework to explain their empirical success. While significant progress has been made in understanding LLM behaviors, existing theoretical frameworks remain fragmented in explaining emergent phenomena through a unified mathematical lens. We establish the first formal connection between LLM architectures and Algorithmic Information Theory (AIT) by proving two fundamental results: (1) the training process computationally approximates Solomonoff prior through loss minimization interpreted as program length optimization, and (2) next-token prediction implements approximate Solomonoff induction. We leverage AIT to provide a unified theoretical explanation for in-context learning, few-shot learning, and scaling laws. Furthermore, our theoretical insights lead to a principled method for few-shot example selection that prioritizes samples where models exhibit lower predictive confidence. We demonstrate through experiments on diverse text classification benchmarks that this strategy yields significant performance improvements, particularly for smaller model architectures, when compared to selecting high-confidence examples. Our framework bridges the gap between theoretical foundations and practical LLM behaviors, providing both explanatory power and actionable insights for future model development.

[Arxiv](https://arxiv.org/abs/2505.15784)