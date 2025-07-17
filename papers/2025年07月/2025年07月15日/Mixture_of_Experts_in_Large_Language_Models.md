# # 混合专家在大型语言模型中的应用  
混合专家（Mixture of Experts，MoE）是一种通过将任务分配给专门的子模型（即“专家”）来提升模型性能的技术。与传统的单体模型不同，MoE 模型通过动态路由机制，能够根据输入特征选择最合适的专家进行处理，从而实现更高的计算效率和更好的模型性能。

发布时间：2025年07月15日

`LLM理论` `大型语言模型`

> Mixture of Experts in Large Language Models

# 摘要

> 本文对大型语言模型中的专家混合（MoE）架构进行了全面综述，展现了其在不增加计算负担的情况下显著提升模型性能的潜力。通过从理论基础到实际应用的系统性分析，我们深入探讨了MoE的核心要素，包括专家门控与路由机制、层级与稀疏配置、元学习方法、多模态与多任务学习场景，以及实际部署案例和最新进展。研究发现，MoE架构相比传统方法具有多项优势：其模型容量更强大，任务表现更出色，且能更高效地扩展能力。我们还指出，专家多样性、精确校准和可靠的推理聚合是MoE成功的关键。最后，本文总结了当前研究的局限性、开放性挑战及未来发展方向，为MoE架构的持续创新提供了重要参考。

> This paper presents a comprehensive review of the Mixture-of-Experts (MoE) architecture in large language models, highlighting its ability to significantly enhance model performance while maintaining minimal computational overhead. Through a systematic analysis spanning theoretical foundations, core architectural designs, and large language model (LLM) applications, we examine expert gating and routing mechanisms, hierarchical and sparse MoE configurations, meta-learning approaches, multimodal and multitask learning scenarios, real-world deployment cases, and recent advances and challenges in deep learning. Our analysis identifies key advantages of MoE, including superior model capacity compared to equivalent Bayesian approaches, improved task-specific performance, and the ability to scale model capacity efficiently. We also underscore the importance of ensuring expert diversity, accurate calibration, and reliable inference aggregation, as these are essential for maximizing the effectiveness of MoE architectures. Finally, this review outlines current research limitations, open challenges, and promising future directions, providing a foundation for continued innovation in MoE architecture and its applications.

[Arxiv](https://arxiv.org/abs/2507.11181)