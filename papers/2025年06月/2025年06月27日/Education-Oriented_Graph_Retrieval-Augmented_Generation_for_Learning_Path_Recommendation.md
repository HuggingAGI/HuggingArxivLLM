# 面向教育的图检索增强生成：用于学习路径推荐的探索

发布时间：2025年06月27日

`其他` `学习路径推荐`

> Education-Oriented Graph Retrieval-Augmented Generation for Learning Path Recommendation

# 摘要

> 学习路径推荐旨在为学习者提供结构化的学习序列（如知识概念或练习），以提升学习效率。尽管在这一领域投入了大量研究努力，但现有方法大多依赖于知识点之间的先决关系，这种依赖带来了两个主要问题：首先，许多教育数据集并未明确提供知识点之间的先决关系，限制了现有推荐方法的应用；其次，仅依赖先决关系作为单一的知识结构可能阻碍学习进展，影响学习效果。

为了解决这些挑战，我们提出了一种创新方法——基于区分学习的学习路径推荐增强方法（DLELP）。该方法通过结合知识点之间的先决关系和相似关系，显著提升了学习路径推荐的效果。具体而言，我们设计了一个自适应的知识概念结构图生成模块，能够为不同教育数据集构建相应的知识结构图，从而增强推荐方法的通用性。此外，我们还提出了一种基于区分学习的强化学习框架（DLRL），有效缓解了学习路径被阻塞的问题，进一步提升了推荐效果。

最后，我们在三个基准数据集上进行了全面实验，结果表明，我们的方法不仅达到了当前最优性能，还为推荐的学习路径提供了可解释的推理依据，为实际应用提供了重要参考。

> Learning path recommendation seeks to provide learners with a structured sequence of learning items (e.g., knowledge concepts or exercises) to optimize their learning efficiency. Despite significant efforts in this area, most existing methods primarily rely on prerequisite relationships, which present two major limitations: 1) Many educational datasets do not explicitly provide prerequisite relationships between knowledge concepts, hindering the application of current learning path recommendation methods. 2) Relying solely on prerequisite relationships as the sole knowledge structure can impede learning progress and negatively impact student outcomes. To address these challenges, we propose a novel approach, Discrimination Learning Enhances Learning Path Recommendation (DLELP), which enhances learning path recommendations by incorporating both prerequisite and similarity relationships between knowledge concepts. Specifically, we introduce a knowledge concept structure graph generation module that adaptively constructs knowledge concept structure graphs for different educational datasets, significantly improving the generalizability of learning path recommendation methods. We then propose a Discrimination Learning-driven Reinforcement Learning (DLRL) framework, which mitigates the issue of blocked learning paths, further enhancing the efficacy of learning path recommendations. Finally, we conduct extensive experiments on three benchmark datasets, demonstrating that our method not only achieves state-of-the-art performance but also provides interpretable reasoning for the recommended learning paths.

[Arxiv](https://arxiv.org/abs/2506.22303)