# 利用领域知识进行主题模型拟合的带种子泊松因子分解方法

发布时间：2025年03月04日

`其他` `电子商务` `文本挖掘`

> Seeded Poisson Factorization: Leveraging domain knowledge to fit topic models

# 摘要

> 主题模型在大型文本语料库中发现潜在主题结构方面被广泛应用，但传统无监督方法常难以匹配预定义概念领域。本文提出Seeded Poisson Factorization（SPF），通过引入种子词整合领域知识，对泊松因子分解框架进行了扩展。

SPF通过调整主题特定术语强度的先验分布，赋予预定义种子词更高的初始速率，从而实现更可解释和结构化的主题发现。该模型采用变分推断结合随机梯度优化进行估计，确保了对大规模数据集的适用性。

我们将SPF应用于亚马逊客户反馈数据集，利用预定义的产品类别作为引导结构。评估结果表明，与替代引导主题模型相比，SPF在分类性能上表现更优，尤其在计算效率和预测性能方面。此外，稳健性检验突显了SPF在平衡领域知识与数据驱动主题发现方面的自适应能力，即使在种子词选择不完美时亦然。这些结果确立了SPF作为将专家知识整合到主题建模中的强大且可扩展的替代方案，提升了实际应用中的可解释性和效率。

> Topic models are widely used for discovering latent thematic structures in large text corpora, yet traditional unsupervised methods often struggle to align with predefined conceptual domains. This paper introduces Seeded Poisson Factorization (SPF), a novel approach that extends the Poisson Factorization framework by incorporating domain knowledge through seed words. SPF enables a more interpretable and structured topic discovery by modifying the prior distribution of topic-specific term intensities, assigning higher initial rates to predefined seed words. The model is estimated using variational inference with stochastic gradient optimization, ensuring scalability to large datasets.
  We apply SPF to an Amazon customer feedback dataset, leveraging predefined product categories as guiding structures. Our evaluation demonstrates that SPF achieves superior classification performance compared to alternative guided topic models, particularly in terms of computational efficiency and predictive performance. Furthermore, robustness checks highlight SPF's ability to adaptively balance domain knowledge and data-driven topic discovery, even in cases of imperfect seed word selection. These results establish SPF as a powerful and scalable alternative for integrating expert knowledge into topic modeling, enhancing both interpretability and efficiency in real-world applications.

[Arxiv](https://arxiv.org/abs/2503.02741)