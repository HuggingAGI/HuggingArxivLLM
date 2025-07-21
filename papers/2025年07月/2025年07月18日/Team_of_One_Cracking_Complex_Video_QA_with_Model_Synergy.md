# 单兵团队：通过模型协作解决复杂视频问答难题

发布时间：2025年07月18日

`LLM应用` `视频处理` `问答系统`

> Team of One: Cracking Complex Video QA with Model Synergy

# 摘要

> 我们提出了一种创新的开放域视频问答框架，旨在提升复杂现实场景下的推理深度与鲁棒性，该框架在CVRR-ES数据集上进行了基准测试。现有视频-大型多模态模型（Video-LMMs）在上下文理解、时间建模以及对模糊或组合性查询的泛化能力方面存在明显不足。为解决这些问题，我们引入了一种提示与响应的整合机制，通过结构化的思维链协调多个异构的视频-语言模型（VLMs），每个模型针对不同的推理路径进行定制。一个外部的大语言模型（LLM）作为评估者和整合者，负责选择并融合最可靠的响应。大量实验结果表明，我们的方法在所有评估指标上均显著优于现有基线，展现出卓越的泛化能力和鲁棒性。我们的方法提供了一种轻量级、可扩展的策略，无需重新训练模型即可提升多模态推理能力，为未来Video-LMM的发展奠定了坚实的基础。

> We propose a novel framework for open-ended video question answering that enhances reasoning depth and robustness in complex real-world scenarios, as benchmarked on the CVRR-ES dataset. Existing Video-Large Multimodal Models (Video-LMMs) often exhibit limited contextual understanding, weak temporal modeling, and poor generalization to ambiguous or compositional queries. To address these challenges, we introduce a prompting-and-response integration mechanism that coordinates multiple heterogeneous Video-Language Models (VLMs) via structured chains of thought, each tailored to distinct reasoning pathways. An external Large Language Model (LLM) serves as an evaluator and integrator, selecting and fusing the most reliable responses. Extensive experiments demonstrate that our method significantly outperforms existing baselines across all evaluation metrics, showcasing superior generalization and robustness. Our approach offers a lightweight, extensible strategy for advancing multimodal reasoning without requiring model retraining, setting a strong foundation for future Video-LMM development.

[Arxiv](https://arxiv.org/abs/2507.13820)