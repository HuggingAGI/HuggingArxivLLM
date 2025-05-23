# 混合参数化量子态在变分量子学习中的应用

发布时间：2025年05月22日

`其他` `量子计算` `量子机器学习`

> Hybrid Parameterized Quantum States for Variational Quantum Learning

# 摘要

> 变分量子学习在噪声中等规模量子（NISQ）时代面临诸多挑战。参数化量子电路（PQC）模型受限于有限次测量导致的统计不确定性，并且对量子噪声极为敏感；而纯粹的古典近似方法如神经量子态（NQS）则无法真正捕捉量子关联，且在扩展性上存在局限。针对这些挑战，我们提出了混合参数化量子态（HPQS），一种融合量子与古典参数化的通用建模框架。通过结合基于PQC的测量与神经估计器，并借助混合机制和后处理函数，HPQS在硬件约束下实现了更高效、更精准的评估。我们通过三个典型任务验证了HPQS的优势：（1）在基于期望的量子机器学习任务中，HPQS显著提升了分类准确率；（2）在Quantum-Train任务中，HPQS以多项式对数可训练变量生成完整经典网络参数；（3）在量子参数适应（QPA）任务中，HPQS有效提升了大语言模型（如GPT-2和Gemma-2）的微调效果。这些结果表明，HPQS不仅兼容现有NISQ硬件，更具备在未来容错架构中广泛应用的潜力，为变分量子学习提供了一种高效且鲁棒的解决方案。

> Variational quantum learning faces practical challenges in the noisy intermediate-scale quantum (NISQ) era. Parameterized quantum circuit (PQC) models suffer from statistical uncertainty due to finite-shot measurements and are highly sensitive to quantum noise, while purely classical approximations like neural quantum states (NQS) lack access to genuine quantum correlations and are limited in scalability. This work introduces Hybrid Parameterized Quantum States (HPQS), a general-purpose modeling framework that interpolates between quantum and classical parameterizations. HPQS combines PQC-based measurements with neural estimators via a blending mechanism and postprocessing functions, enabling enhanced, shot-efficient evaluation under hardware constraints. We demonstrate HPQS across three representative quantum learning tasks: (1) Expectation-based QML, where HPQS yields higher classification accuracy than PQC-only and NQS-only baselines under limited quantum measurements. (2) Quantum-Train, where HPQS generates the entire parameter set of classical networks using polylogarithmic trainable variables; and (3) Quantum Parameter Adaptation (QPA), where HPQS produces LoRA adapter parameters for fine-tuning large language models like GPT-2 and Gemma-2 with improved perplexity under low-shot conditions; Together, these results position HPQS as a scalable, noise-resilient approach for variational quantum learning, compatible with both current NISQ hardware and future fault-tolerant architectures.

[Arxiv](https://arxiv.org/abs/2505.16676)