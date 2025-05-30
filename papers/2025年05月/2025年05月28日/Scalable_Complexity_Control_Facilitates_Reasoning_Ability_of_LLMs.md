# 可扩展复杂度控制提升大型语言模型推理能力

发布时间：2025年05月28日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的复杂度控制方法，包括调整初始化速率和权重衰减系数，以优化模型在不同规模下的扩展规律。这些研究属于模型理论层面的探讨，旨在改进模型的泛化能力，因此归类为LLM理论。` `机器学习`

> Scalable Complexity Control Facilitates Reasoning Ability of LLMs

# 摘要

> 近年来，大型语言模型 (LLMs) 的推理能力突飞猛进，吸引了研究者们对更基础方法的兴趣，这些方法能够可靠地提升模型的泛化能力。本研究展示了模型复杂度控制的重要性，这一方法可通过调整初始化速率和权重衰减系数来方便地实现，它能够持续改进 LLMs 在不同模型规模和数据规模下的扩展规律。通过比较在 1T 个标记上进行预训练的 2.4B 模型在不同复杂度超参数下的基准性能，这一优势得到了进一步的验证。与固定初始化标准差不同，我们发现，保持一个恒定的初始化速率（即标准差的指数）能够使模型和数据规模的扩展规律以更快的速度下降。这些结果表明，复杂度控制是推动 LLMs 持续进步的一个有前景的方向。

> The reasoning ability of large language models (LLMs) has been rapidly advancing in recent years, attracting interest in more fundamental approaches that can reliably enhance their generalizability. This work demonstrates that model complexity control, conveniently implementable by adjusting the initialization rate and weight decay coefficient, improves the scaling law of LLMs consistently over varying model sizes and data sizes. This gain is further illustrated by comparing the benchmark performance of 2.4B models pretrained on 1T tokens with different complexity hyperparameters. Instead of fixing the initialization std, we found that a constant initialization rate (the exponent of std) enables the scaling law to descend faster in both model and data sizes. These results indicate that complexity control is a promising direction for the continual advancement of LLMs.

[Arxiv](https://arxiv.org/abs/2505.23013)