# AxelSMOTE：一种面向不平衡分类的基于智能体过采样算法

发布时间：2025年09月08日

`Agent` `基础理论`

> AxelSMOTE: An Agent-Based Oversampling Algorithm for Imbalanced Classification

# 摘要

> 机器学习中的类别不平衡是一大难题，倾斜的数据集往往会影响少数类别的性能表现。传统过采样技术常用于缓解这一问题，但存在诸多不足：它们独立处理各个特征，缺乏基于相似性的控制机制，限制了样本多样性，且难以有效控制合成样本的多样性。为此，我们提出了AxelSMOTE——一种创新的智能体驱动方法，该方法将数据实例视为能进行复杂交互的自主智能体。AxelSMOTE借鉴Axelrod的文化传播模型，实现了四项核心创新：（1）基于属性的特征分组，以保留特征间的相关性；（2）基于相似性的概率交换机制，确保交互的有效性；（3）采用Beta分布混合，实现真实的插值效果；（4）通过受控的多样性注入，避免过拟合问题。在八个不平衡数据集上的实验结果显示，AxelSMOTE不仅性能优于当前最先进的采样方法，还能保持较高的计算效率。

> Class imbalance in machine learning poses a significant challenge, as skewed datasets often hinder performance on minority classes. Traditional oversampling techniques, which are commonly used to alleviate class imbalance, have several drawbacks: they treat features independently, lack similarity-based controls, limit sample diversity, and fail to manage synthetic variety effectively. To overcome these issues, we introduce AxelSMOTE, an innovative agent-based approach that views data instances as autonomous agents engaging in complex interactions. Based on Axelrod's cultural dissemination model, AxelSMOTE implements four key innovations: (1) trait-based feature grouping to preserve correlations; (2) a similarity-based probabilistic exchange mechanism for meaningful interactions; (3) Beta distribution blending for realistic interpolation; and (4) controlled diversity injection to avoid overfitting. Experiments on eight imbalanced datasets demonstrate that AxelSMOTE outperforms state-of-the-art sampling methods while maintaining computational efficiency.

[Arxiv](https://arxiv.org/abs/2509.06875)