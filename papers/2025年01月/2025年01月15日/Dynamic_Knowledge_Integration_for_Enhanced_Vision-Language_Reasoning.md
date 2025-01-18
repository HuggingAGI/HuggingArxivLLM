# 动态知识整合：提升视觉-语言推理能力

发布时间：2025年01月15日

`LLM应用

理由：该论文主要讨论了如何通过自适应知识引导预训练大型视觉-语言模型（AKGP-LVLM）来提升多模态任务中的性能，特别是在视觉问答和推理等知识密集型任务中。该方法通过整合结构化和非结构化知识，并使用知识编码器、检索机制和动态适配器等技术来增强模型的表现。这些内容属于大型语言模型（LLM）在实际应用中的改进和优化，因此应归类为LLM应用。` `计算机视觉`

> Dynamic Knowledge Integration for Enhanced Vision-Language Reasoning

# 摘要

> 大型视觉-语言模型（LVLMs）在多模态任务中表现出色，但其性能常因缺乏外部知识整合而受限，尤其在视觉问答和推理等知识密集型任务中。为此，我们提出了自适应知识引导预训练大型视觉-语言模型（AKGP-LVLM），在预训练和微调阶段动态整合结构化和非结构化知识。该方法通过知识编码器表示外部知识，检索机制筛选任务相关信息，动态适配器对齐多模态与知识表示。我们在四个基准数据集上验证了该方法的有效性，性能显著超越现有模型。人类评估也表明，模型输出的正确性和相关性更优。深入分析证实了AKGP-LVLM的鲁棒性、高效性和可扩展性，使其成为解决现实世界知识密集型任务的理想方案。

> Large Vision-Language Models (LVLMs) have demonstrated impressive capabilities in multimodal tasks, but their performance is often constrained by the lack of external knowledge integration, limiting their ability to handle knowledge-intensive tasks such as visual question answering and reasoning. To address this challenge, we propose a novel method, Adaptive Knowledge-Guided Pretraining for Large Vision-Language Models (AKGP-LVLM), which dynamically incorporates structured and unstructured knowledge into LVLMs during pretraining and fine-tuning. Our approach employs a knowledge encoder to represent external knowledge, a retrieval mechanism to select task-relevant information, and a dynamic adaptor to align multimodal and knowledge representations effectively. We evaluate our method on four benchmark datasets, demonstrating significant performance improvements over state-of-the-art models. Furthermore, human evaluations highlight the superior correctness and relevance of our model's outputs. Extensive analyses confirm the robustness, efficiency, and scalability of AKGP-LVLM, making it a compelling solution for real-world knowledge-intensive tasks.

[Arxiv](https://arxiv.org/abs/2501.08597)