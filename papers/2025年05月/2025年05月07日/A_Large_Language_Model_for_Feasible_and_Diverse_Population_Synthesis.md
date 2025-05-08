# 面向可行且多样化人口合成的大型语言模型

发布时间：2025年05月07日

`LLM应用

理由：这篇论文讨论了如何将大型语言模型（LLMs）应用于生成综合人口的任务，并提出了一种结合贝叶斯网络的微调方法。该研究专注于LLMs在实际应用中的使用，特别是在提高生成结果的可行性和多样性方面，属于LLM应用的范畴。` `城市规划` `人口统计`

> A Large Language Model for Feasible and Diverse Population Synthesis

# 摘要

> 生成既可行又多样化的综合人口对于确保活动基于模型 (ABMs) 中的活动日程模拟至关重要。尽管深度生成模型（DGMs）如变分自编码器和生成对抗网络已被用于此任务，但它们难以平衡合理组合的纳入与不合理组合的排除。为在保持多样性的同时提升可行性，我们提出了一种针对大型语言模型（LLMs）的微调方法，通过贝叶斯网络（BN）的拓扑排序显式控制生成过程。实验表明，我们的混合 LLM-BN 方法在 Few-shot 学习中优于传统 DGMs 和专有 LLMs（如 ChatGPT-4o）。具体来说，我们的方法实现了约 95% 的可行性，显著高于 DGMs 的约 80%，同时保持了多样性，非常适合实际应用。重要的是，该方法基于轻量级开源 LLM，可在标准个人计算环境中进行微调和推理，使其在成本效益和可扩展性方面适用于大规模应用，如特大城市的人口合成。通过使用高质量综合人口作为 ABM 管道的起点，我们的方法提高了模拟可靠性并减少了错误传播。源代码可供研究和实际应用使用。

> Generating a synthetic population that is both feasible and diverse is crucial for ensuring the validity of downstream activity schedule simulation in activity-based models (ABMs). While deep generative models (DGMs), such as variational autoencoders and generative adversarial networks, have been applied to this task, they often struggle to balance the inclusion of rare but plausible combinations (i.e., sampling zeros) with the exclusion of implausible ones (i.e., structural zeros). To improve feasibility while maintaining diversity, we propose a fine-tuning method for large language models (LLMs) that explicitly controls the autoregressive generation process through topological orderings derived from a Bayesian Network (BN). Experimental results show that our hybrid LLM-BN approach outperforms both traditional DGMs and proprietary LLMs (e.g., ChatGPT-4o) with few-shot learning. Specifically, our approach achieves approximately 95% feasibility, significantly higher than the ~80% observed in DGMs, while maintaining comparable diversity, making it well-suited for practical applications. Importantly, the method is based on a lightweight open-source LLM, enabling fine-tuning and inference on standard personal computing environments. This makes the approach cost-effective and scalable for large-scale applications, such as synthesizing populations in megacities, without relying on expensive infrastructure. By initiating the ABM pipeline with high-quality synthetic populations, our method improves overall simulation reliability and reduces downstream error propagation. The source code for these methods is available for research and practical application.

[Arxiv](https://arxiv.org/abs/2505.04196)