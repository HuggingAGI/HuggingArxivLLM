# 多模态LLM的自由令牌减少学习

发布时间：2025年01月28日

`LLM应用

**理由**：该论文主要讨论的是如何通过压缩视觉提示来优化视觉-语言模型（VLMs）的推理性能，并降低计算成本。虽然涉及多模态任务，但其核心是优化大型语言模型（LLM）在实际应用中的效率和性能，因此应归类为LLM应用。` `计算机视觉`

> Learning Free Token Reduction for Multi-Modal LLM

# 摘要

> # 视觉-语言模型（VLMs）在多模态任务中表现出色，但其实际应用常受限于高计算成本和长推理时间。由于视觉模态通常比文本模态信息量更大，压缩视觉提示成为解决这些问题的有效途径。现有方法多聚焦于优化模型架构或直接减少视觉标记数量，但往往因忽视视觉数据的时空特性而影响推理性能。本文提出了一种在时空维度上操作的标记压缩范式，包含一个无需学习的即插即用压缩管道，可轻松集成到多数多模态大型语言模型（MLLM）框架中。该方法不仅提升了模型推理能力，还降低了计算成本。视频问答任务的实验结果验证了该方法的有效性，展示了在不牺牲性能的前提下显著提升效率的优势。

> Vision-Language Models (VLMs) have achieved remarkable success across a range of multimodal tasks; however, their practical deployment is often constrained by high computational costs and prolonged inference times. Since the vision modality typically carries more information than the text modality, compressing visual prompts offers a promising solution to alleviate these challenges. Existing approaches predominantly focus on refining model architectures or directly reducing the number of visual tokens. However, these methods often compromise inference performance due to a lack of consideration for the unique spatial and temporal characteristics of visual data. In this work, we propose a token compression paradigm that operates on both spatial and temporal dimensions. Our approach includes a learning-free, plug-and-play compression pipeline that can be seamlessly integrated into most Multimodal Large Language Model (MLLM) frameworks. By leveraging this method, we enhance the model inference capability while simultaneously reducing its computational cost. Experimental results on the Video-QA task demonstrate the effectiveness of the proposed approach, showcasing significant improvements in efficiency without sacrificing performance.

[Arxiv](https://arxiv.org/abs/2501.17391)