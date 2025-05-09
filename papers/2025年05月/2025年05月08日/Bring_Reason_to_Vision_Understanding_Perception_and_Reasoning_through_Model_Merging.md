# 将推理引入视觉：通过模型融合探索感知与推理

发布时间：2025年05月08日

`LLM应用` `人工智能` `多模态`

> Bring Reason to Vision: Understanding Perception and Reasoning through Model Merging

# 摘要

> 视觉-语言模型（VLMs）融合了视觉感知与大型语言模型（LLMs）的通用能力，如推理。然而，这两种能力如何协同作用的机制尚不明确。本研究通过模型合并技术，探索了感知与推理的结合方式。与以往研究多专注于同类型模型的合并不同，我们提出跨模态模型合并方法，使LLMs的推理能力得以融入VLMs。通过大量实验，我们证明了模型合并为无需训练即可将LLMs的推理能力迁移至VLMs提供了一条有效路径。此外，我们利用合并后的模型深入探究感知与推理的内在机制及其在合并过程中的变化。研究发现，感知能力主要编码于模型的早期层，而推理则主要由中层到深层驱动。合并后，所有层均开始参与推理过程，而感知能力在各层的分布基本保持不变。这些发现为模型合并作为多模态整合与解释工具的潜力提供了重要启示。

> Vision-Language Models (VLMs) combine visual perception with the general capabilities, such as reasoning, of Large Language Models (LLMs). However, the mechanisms by which these two abilities can be combined and contribute remain poorly understood. In this work, we explore to compose perception and reasoning through model merging that connects parameters of different models. Unlike previous works that often focus on merging models of the same kind, we propose merging models across modalities, enabling the incorporation of the reasoning capabilities of LLMs into VLMs. Through extensive experiments, we demonstrate that model merging offers a successful pathway to transfer reasoning abilities from LLMs to VLMs in a training-free manner. Moreover, we utilize the merged models to understand the internal mechanism of perception and reasoning and how merging affects it. We find that perception capabilities are predominantly encoded in the early layers of the model, whereas reasoning is largely facilitated by the middle-to-late layers. After merging, we observe that all layers begin to contribute to reasoning, whereas the distribution of perception abilities across layers remains largely unchanged. These observations shed light on the potential of model merging as a tool for multimodal integration and interpretation.

[Arxiv](https://arxiv.org/abs/2505.05464)