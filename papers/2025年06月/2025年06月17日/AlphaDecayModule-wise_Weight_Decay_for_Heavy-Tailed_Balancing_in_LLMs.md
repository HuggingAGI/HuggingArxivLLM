# AlphaDecay：LLMs 重尾分布平衡的模块化权重衰减方法

发布时间：2025年06月17日

`LLM理论`

> AlphaDecay:Module-wise Weight Decay for Heavy-Tailed Balancing in LLMs

# 摘要

> 权重衰减是训练大型语言模型（LLMs）的标准正则化技术。尽管通常为每一层分配相同的衰减率，但这种方式忽略了 LLM 的结构多样性以及各模块之间不同的谱特性。本文中，我们引入了 AlphaDecay，这是一种简单而有效的方法，能够为 LLM 的每个模块自适应地分配不同的权重衰减强度。我们的方法基于重尾自我正则化（HT-SR）理论，该理论通过分析权重相关矩阵的经验谱密度（ESD）来量化“重尾性”。表现出更显著重尾特性的模块，反映出更强的特征学习能力，会被分配较弱的衰减；而具有较轻尾谱特性的模块则会接受较强的衰减。我们的方法通过定制化的权重衰减分配，平衡了各模块在谱特性上的差异，从而提升了模型性能。大量从 60M 到 1B 不同规模的预训练任务表明，AlphaDecay 在困惑度和泛化能力上均优于传统的均匀衰减和其他自适应衰减基线方法。

> Weight decay is a standard regularization technique for training large language models (LLMs). While it is common to assign a uniform decay rate to every layer, this approach overlooks the structural diversity of LLMs and the varying spectral properties across modules. In this paper, we introduce AlphaDecay, a simple yet effective method that adaptively assigns different weight decay strengths to each module of an LLM. Our approach is guided by Heavy-Tailed Self-Regularization (HT-SR) theory, which analyzes the empirical spectral density (ESD) of weight correlation matrices to quantify "heavy-tailedness." Modules exhibiting more pronounced heavy-tailed ESDs, reflecting stronger feature learning, are assigned weaker decay, while modules with lighter-tailed spectra receive stronger decay. Our method leverages tailored weight decay assignments to balance the module-wise differences in spectral properties, leading to improved performance. Extensive pre-training tasks with various model sizes from 60M to 1B demonstrate that AlphaDecay achieves better perplexity and generalization than conventional uniform decay and other adaptive decay baselines.

[Arxiv](https://arxiv.org/abs/2506.14562)