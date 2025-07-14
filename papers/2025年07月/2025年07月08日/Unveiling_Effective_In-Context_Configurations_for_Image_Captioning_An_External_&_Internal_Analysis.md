# 揭秘图像描述的高效上下文配置：内外部分析

发布时间：2025年07月08日

`LLM理论` `计算机视觉`

> Unveiling Effective In-Context Configurations for Image Captioning: An External & Internal Analysis

# 摘要

> 大模型的演变见证了 In-Context Learning (ICL) 能力的出现。在自然语言处理 (NLP) 领域，已有大量研究证明了 ICL 的有效性。受大型语言模型 (LLMs) 成功的启发，研究人员开发了具备 ICL 能力的大型多模态模型 (LMMs)。然而，针对多模态 ICL 的演示配置探索仍处于初步阶段。此外，In-Context Examples (ICEs) 的可控性为观察和分析 LMMs 在不同输入下的推理特性提供了一种高效且经济的手段。本文对图像描述任务中的多模态在上下文中学习进行了全面的外部和内部研究。从外部来看，我们从三个方面探索了演示配置策略：样本数量、图像检索和描述分配。我们采用多种指标对实验结果进行了系统、全面的评估和总结。从内部来看，我们分析了典型 LMM 的注意力特征，并开发了基于注意力的指标来量化模型行为。我们还进行了辅助实验，探索了注意力驱动的模型加速和压缩的可行性。我们进一步比较了具有相同模型设计和预训练策略的 LMMs 的性能差异，并从预训练数据特性的角度解释了这些差异。我们的研究不仅通过外部实验揭示了 ICEs 配置策略对模型性能的影响，还通过内部检查揭示了典型模式，为理解 LMMs 中的多模态 ICL 提供了双重视角。我们结合外部和内部分析研究大型模型的方法，以及新提出的指标方法，可以应用于更广泛的研究领域。

> The evolution of large models has witnessed the emergence of In-Context Learning (ICL) capabilities. In Natural Language Processing (NLP), numerous studies have demonstrated the effectiveness of ICL. Inspired by the success of Large Language Models (LLMs), researchers have developed Large Multimodal Models (LMMs) with ICL capabilities. However, explorations of demonstration configuration for multimodal ICL remain preliminary. Additionally, the controllability of In-Context Examples (ICEs) provides an efficient and cost-effective means to observe and analyze the inference characteristics of LMMs under varying inputs. This paper conducts a comprehensive external and internal investigation of multimodal in-context learning on the image captioning task. Externally, we explore demonstration configuration strategies through three dimensions: shot number, image retrieval, and caption assignment. We employ multiple metrics to systematically and thoroughly evaluate and summarize key findings. Internally, we analyze typical LMM attention characteristics and develop attention-based metrics to quantify model behaviors. We also conduct auxiliary experiments to explore the feasibility of attention-driven model acceleration and compression. We further compare performance variations between LMMs with identical model design and pretraining strategies and explain the differences from the angles of pre-training data features. Our study reveals both how ICEs configuration strategies impact model performance through external experiments and characteristic typical patterns through internal inspection, providing dual perspectives for understanding multimodal ICL in LMMs. Our method of combining external and internal analysis to investigate large models, along with our newly proposed metrics, can be applied to broader research areas.

[Arxiv](https://arxiv.org/abs/2507.08021)