# AMoPO：无需奖励模型和参考模型的自适应多目标优化

发布时间：2025年06月08日

`LLM理论

摘要讨论了大型语言模型（LLMs）的多目标偏好对齐方法，提出了自适应多目标偏好优化（AMoPO）框架，属于模型优化和理论层面的贡献，因此归类为LLM理论。` `人工智能`

> AMoPO: Adaptive Multi-objective Preference Optimization without Reward Models and Reference Models

# 摘要

> 现有的大型语言模型（LLMs）多目标偏好对齐方法面临两大局限：一是难以有效平衡各类偏好维度，二是依赖辅助奖励/参考模型导致计算复杂度增加。为解决这些挑战，我们提出了自适应多目标偏好优化（AMoPO），这是一种能够实现偏好维度动态平衡的创新框架。通过引入多目标优化范式，将维度感知生成指标作为隐式奖励，AMoPO使LLMs能够与多样化偏好对齐，无需额外的奖励模型或参考模型。我们还引入了一种自适应权重分配机制，将生成空间建模为高斯分布，从而实现对偏好维度的动态优先级排序。实验结果表明，AMoPO在性能上超越现有最优方法28.5%，且在7B、14B和32B规模模型上的实验验证了其扩展能力。此外，对多维度的进一步分析证实了其适应性和有效性。这些发现证明了AMoPO实现维度感知偏好对齐的能力，并凸显了其优势。我们的代码和数据集可在https://github.com/Javkonline/AMoPO获取。

> Existing multi-objective preference alignment methods for large language models (LLMs) face limitations: (1) the inability to effectively balance various preference dimensions, and (2) reliance on auxiliary reward/reference models introduces computational complexity. To address these challenges, we propose Adaptive Multi-objective Preference Optimization (AMoPO), a novel framework that achieves dynamic balance across preference dimensions. By introducing the multi-objective optimization paradigm to use the dimension-aware generation metrics as implicit rewards, AMoPO aligns LLMs with diverse preferences without additional reward models or reference models. We introduce an adaptive weight assignment mechanism that models the generation space as a Gaussian distribution, allowing dynamic prioritization of preference dimensions. Empirical results demonstrate that AMoPO outperforms state-of-the-art baselines by 28.5%, and the experiments on 7B, 14B, and 32B models reveal the scaling ability of AMoPO. Moreover, additional analysis of multiple dimensions verifies its adaptability and effectiveness. These findings validate AMoPO's capability to achieve dimension-aware preference alignment, highlighting its superiority. Our codes and datasets are available at https://github.com/Javkonline/AMoPO.

[Arxiv](https://arxiv.org/abs/2506.07165)