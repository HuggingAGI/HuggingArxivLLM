# X-融合：在冻结的大型语言模型中引入新模态

发布时间：2025年04月29日

`LLM应用` `人工智能` `多模态`

> X-Fusion: Introducing New Modality to Frozen Large Language Models

# 摘要

> 我们提出了一种名为 X-Fusion 的框架，该框架在保持大型语言模型（LLMs）语言能力的同时，将其扩展到多模态任务。X-Fusion 采用双塔设计，使用特定模态的权重，在冻结 LLM 参数的同时，整合视觉信息以实现理解和生成。实验结果表明，X-Fusion 在图像到文本和文本到图像任务中始终优于其他架构。我们发现，加入以理解为导向的数据可以提升生成质量，降低图像数据噪声有助于整体性能提升，特征对齐加速了小模型的收敛，但对大模型影响较小。我们的研究为构建高效的统一多模态模型提供了有价值的见解。

> We propose X-Fusion, a framework that extends pretrained Large Language Models (LLMs) for multimodal tasks while preserving their language capabilities. X-Fusion employs a dual-tower design with modality-specific weights, keeping the LLM's parameters frozen while integrating vision-specific information for both understanding and generation. Our experiments demonstrate that X-Fusion consistently outperforms alternative architectures on both image-to-text and text-to-image tasks. We find that incorporating understanding-focused data improves generation quality, reducing image data noise enhances overall performance, and feature alignment accelerates convergence for smaller models but has minimal impact on larger ones. Our findings provide valuable insights into building efficient unified multimodal models.

[Arxiv](https://arxiv.org/abs/2504.20996)