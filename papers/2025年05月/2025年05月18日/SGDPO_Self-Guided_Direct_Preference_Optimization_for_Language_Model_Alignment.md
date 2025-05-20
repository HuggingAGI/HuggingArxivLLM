# SGDPO：自引导直接偏好优化实现语言模型对齐

发布时间：2025年05月18日

`LLM理论` `人工智能` `机器学习`

> SGDPO: Self-Guided Direct Preference Optimization for Language Model Alignment

# 摘要

> 直接偏好优化（DPO）因其灵活性被广泛用于对齐大型语言模型（LLM）与人类价值观。尽管DPO在对齐大型语言模型（LLM）与人类价值观方面表现出色，但其生成人类偏好的响应能力有限，且结果远非稳健。为解决这些局限性，本文提出了一种新型的自我引导直接偏好优化算法——SGDPO。该算法通过在优化过程中引入引导项来控制梯度流，实现对选中和拒绝奖励更新的精细控制。我们对所提出的方法进行了详细理论分析，并阐述了其工作原理。此外，我们在多种模型和基准上进行了全面实验。大量实验结果表明，实证结果与理论分析高度一致，并证实了我们提出方法的有效性（最高提升9.19%的得分）。

> Direct Preference Optimization (DPO) is broadly utilized for aligning Large Language Models (LLMs) with human values because of its flexibility. Despite its effectiveness, it has been observed that the capability of DPO to generate human-preferred response is limited and the results of DPO are far from resilient. To address these limitations, in this paper we propose a novel Self-Guided Direct Preference Optimization algorithm, i.e., SGDPO, which incorporates a pilot term to steer the gradient flow during the optimization process, allowing for fine-grained control over the updates of chosen and rejected rewards. We provide a detailed theoretical analysis of our proposed method and elucidate its operational mechanism. Furthermore, we conduct comprehensive experiments on various models and benchmarks. The extensive experimental results demonstrate the consistency between the empirical results and our theoretical analysis and confirm the effectiveness of our proposed approach (up to 9.19% higher score).

[Arxiv](https://arxiv.org/abs/2505.12435)