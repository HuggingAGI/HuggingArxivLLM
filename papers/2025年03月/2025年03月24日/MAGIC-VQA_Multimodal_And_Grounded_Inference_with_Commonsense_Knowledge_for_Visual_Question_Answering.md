# MAGIC-VQA：结合常识知识的多模态推理，应用于视觉问答任务

发布时间：2025年03月24日

`LLM应用` `计算机视觉` `人工智能`

> MAGIC-VQA: Multimodal And Grounded Inference with Commonsense Knowledge for Visual Question Answering

# 摘要

> 视觉问答（VQA）需要在视觉与文本之间进行跨模态推理，但大型视觉语言模型（LVLMs）往往缺乏整合的常识知识，这限制了它们在实际应用中的表现。为解决这一问题，我们提出了MAGIC-VQA——一个通过系统整合常识知识与LVLMs来增强VQA能力的新框架。MAGIC-VQA采用三阶段流程：首先从外部来源整合显性知识，其次通过类型后处理进行上下文优化，最后借助图神经网络（GNN）实现结构化推理的隐性知识增强。GNN不仅为结构化推理提供了更深层次的支持，还实现了超越LVLMs的卓越关系推理能力。MAGIC-VQA通过将常识知识与基于LVLM的推理相结合，填补了这一关键空白，无需大量预训练或复杂提示调优。我们的框架在基准数据集上达到了最先进的性能，显著提升了VQA中的常识推理能力。

> Visual Question Answering (VQA) requires reasoning across visual and textual modalities, yet Large Vision-Language Models (LVLMs) often lack integrated commonsense knowledge, limiting their robustness in real-world scenarios. To address this, we introduce MAGIC-VQA, a novel framework that enhances VQA by systematically integrating commonsense knowledge with LVLMs. MAGIC-VQA employs a three-stage process: (1) Explicit Knowledge Integration from external sources, (2) By-Type Post-Processing for contextual refinement, and (3) Implicit Knowledge Augmentation using a Graph Neural Network (GNN) for structured reasoning. While GNNs bring greater depth to structured inference, they enable superior relational inference beyond LVLMs. MAGIC-VQA bridges a key gap by unifying commonsensse knowledge with LVLM-driven reasoning, eliminating the need for extensive pre-training or complex prompt tuning. Our framework achieves state-of-the-art performance on benchmark datasets, significantly improving commonsense reasoning in VQA.

[Arxiv](https://arxiv.org/abs/2503.18491)