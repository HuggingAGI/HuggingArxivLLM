# LSDM：基于LLM增强的时空扩散模型，用于服务级别移动流量预测

发布时间：2025年07月23日

`LLM应用

理由：这篇论文讨论了将大型语言模型（LLMs）应用于移动流量预测的任务，结合扩散模型和多模态环境信息来提升预测性能。它展示了LLMs在特定应用中的实际效果，因此属于LLM应用类别。` `移动通信`

> LSDM: LLM-Enhanced Spatio-temporal Diffusion Model for Service-Level Mobile Traffic Prediction

# 摘要

> 针对个人用户的业务级别移动流量预测，对于提升网络效率和优化服务质量至关重要。然而，现有方法在不同城市环境中的适应性有限，且因个人流量的高不确定性、缺乏环境上下文及服务间复杂依赖，导致预测结果不准确。为应对这些挑战，我们提出了一种基于扩散模型与大型语言模型（LLMs）的LLM增强时空扩散模型（LSDM）。该模型结合了扩散模型的生成能力与Transformer的自适应学习能力，并通过多模态环境信息增强了业务级别模式的建模。在真实数据集上的评估表明，LSDM在流量预测方面表现出色，且通过LLM引入上下文信息后，性能提升了至少2.83%（以决定系数衡量），与类似模型（如CSDI）相比，均方根误差降低了至少8.29%。代码和数据集可在以下链接获取：https://github.com/SoftYuaneR/LSDM.

> Service-level mobile traffic prediction for individual users is essential for network efficiency and quality of service enhancement. However, current prediction methods are limited in their adaptability across different urban environments and produce inaccurate results due to the high uncertainty in personal traffic patterns, the lack of detailed environmental context, and the complex dependencies among different network services. These challenges demand advanced modeling techniques that can capture dynamic traffic distributions and rich environmental features. Inspired by the recent success of diffusion models in distribution modeling and Large Language Models (LLMs) in contextual understanding, we propose an LLM-Enhanced Spatio-temporal Diffusion Model (LSDM). LSDM integrates the generative power of diffusion models with the adaptive learning capabilities of transformers, augmented by the ability to capture multimodal environmental information for modeling service-level patterns and dynamics. Extensive evaluations on real-world service-level datasets demonstrate that the model excels in traffic usage predictions, showing outstanding generalization and adaptability. After incorporating contextual information via LLM, the performance improves by at least 2.83% in terms of the coefficient of determination. Compared to models of a similar type, such as CSDI, the root mean squared error can be reduced by at least 8.29%. The code and dataset will be available at: https://github.com/SoftYuaneR/LSDM.

[Arxiv](https://arxiv.org/abs/2507.17795)