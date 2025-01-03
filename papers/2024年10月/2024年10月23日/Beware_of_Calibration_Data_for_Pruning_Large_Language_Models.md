# 修剪大型语言模型时，需警惕校准数据的使用

发布时间：2024年10月23日

`LLM理论

**理由**：这篇论文主要讨论了大型语言模型（LLMs）的模型压缩技术，特别是训练后剪枝方法及其对校准数据的依赖性。研究内容涉及如何通过自生成校准数据来优化剪枝策略，从而提升模型的推理效率。这些内容属于对LLM内部机制和优化方法的理论研究，因此归类为LLM理论。` `模型压缩`

> Beware of Calibration Data for Pruning Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，模型压缩在降低成本和提升推理效率方面变得愈发重要。训练后剪枝作为一种无需迭代训练且仅需少量校准数据的方法，展现出巨大潜力。以往研究多聚焦于设计先进的剪枝方法，而校准数据对剪枝性能的影响却鲜有系统性探讨。我们填补了这一空白，并发现校准数据的影响在高稀疏度下甚至超过剪枝策略的设计。初步探索还表明，使用与训练数据相似的校准数据效果更佳。鉴于高级LLMs的预训练数据通常不可获取，我们提出了一种自生成校准数据合成策略。实验在DCLM和LLaMA-3等开源LLMs上进行，结果显示该方法优于常用校准数据，并能有效增强Wanda、OWL等剪枝方法的性能。

> As large language models (LLMs) are widely applied across various fields, model compression has become increasingly crucial for reducing costs and improving inference efficiency. Post-training pruning is a promising method that does not require resource-intensive iterative training and only needs a small amount of calibration data to assess the importance of parameters. Previous research has primarily focused on designing advanced pruning methods, while different calibration data's impact on pruning performance still lacks systematical exploration. We fill this blank and surprisingly observe that the effects of calibration data even value more than designing advanced pruning strategies, especially for high sparsity. Our preliminary exploration also discloses that using calibration data similar to the training data can yield better performance. As pre-training data is usually inaccessible for advanced LLMs, we further provide a self-generating calibration data synthesis strategy to construct feasible calibration data. We conduct experiments on the recent strong open-source LLMs (e.g., DCLM, and LLaMA-3), and the results show that the proposed method outperforms commonly used calibration data and can effectively enhance strong pruning methods (e.g., Wanda, OWL).

[Arxiv](https://arxiv.org/abs/2410.17711)