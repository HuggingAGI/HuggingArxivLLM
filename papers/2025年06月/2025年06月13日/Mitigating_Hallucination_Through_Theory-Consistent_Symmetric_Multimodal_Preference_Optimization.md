# 基于对称多模态优化的理论一致方法，减轻AI幻觉现象

发布时间：2025年06月13日

`LLM理论` `多模态`

> Mitigating Hallucination Through Theory-Consistent Symmetric Multimodal Preference Optimization

# 摘要

> 直接偏好优化（DPO）作为一种有效的解决方案，被提出用于缓解多模态大型语言模型（MLLMs）中的幻觉问题。现有方法通过采用视觉导向的对比目标来增强MLLMs对视觉输入的关注，从而显著减少了幻觉现象，但它们仍然面临优化目标函数不够严谨以及偏好监督不够直接的问题。为了解决这些问题，我们提出了对称多模态偏好优化（SymMPO）。该方法在保持与标准DPO严格的理论一致性的同时，通过直接的偏好监督（即响应对）进行对称偏好学习，从而提升视觉理解能力。除了传统的顺序偏好学习外，SymMPO还引入了一种偏好边际一致性损失，用于定量调节对称偏好对之间的偏好差距。在五个基准测试中的全面评估表明，SymMPO展现了优越的性能，证明了其在缓解MLLMs幻觉方面的有效性。

> Direct Preference Optimization (DPO) has emerged as an effective approach for mitigating hallucination in Multimodal Large Language Models (MLLMs). Although existing methods have achieved significant progress by utilizing vision-oriented contrastive objectives for enhancing MLLMs' attention to visual inputs and hence reducing hallucination, they suffer from non-rigorous optimization objective function and indirect preference supervision. To address these limitations, we propose a Symmetric Multimodal Preference Optimization (SymMPO), which conducts symmetric preference learning with direct preference supervision (i.e., response pairs) for visual understanding enhancement, while maintaining rigorous theoretical alignment with standard DPO. In addition to conventional ordinal preference learning, SymMPO introduces a preference margin consistency loss to quantitatively regulate the preference gap between symmetric preference pairs. Comprehensive evaluation across five benchmarks demonstrate SymMPO's superior performance, validating its effectiveness in hallucination mitigation of MLLMs.

[Arxiv](https://arxiv.org/abs/2506.11712)