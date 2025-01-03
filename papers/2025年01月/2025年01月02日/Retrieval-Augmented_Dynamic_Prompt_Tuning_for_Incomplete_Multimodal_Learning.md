# 用于不完整多模态学习的检索增强型动态提示调整

发布时间：2025年01月02日

`RAG` `多模态学习` `信息检索`

> Retrieval-Augmented Dynamic Prompt Tuning for Incomplete Multimodal Learning

# 摘要

> 多模态学习在模态不完整的情况下既实用又充满挑战。近来，研究人员致力于通过运用可学习的提示来增强预训练的多模态转换器（MMTs）在模态缺失状况下的稳健性。然而，这些基于提示的方法存在若干局限：（1）不完整的模态为特定任务的推理提供的模态线索有限；（2）对缺失内容的虚拟填补会造成信息丢失并引入噪声；（3）静态提示与实例无关，对于各种缺失情况的实例所能提供的知识有限。为应对这些问题，我们提出了 RAGPT，这是一种新颖的检索增强型动态提示调整框架。RAGPT 涵盖三个模块：（I）多通道检索器，通过模态内检索策略识别相似实例；（II）缺失模态生成器，利用检索到的上下文恢复缺失信息；（III）上下文感知提示器，从相关实例获取上下文知识并生成动态提示，极大地增强 MMT 的稳健性。在三个真实世界数据集上开展的大量实验表明，RAGPT 在处理模态不完整问题时始终优于所有竞争基线。我们工作的代码和基于提示的基线可在 https://github.com/Jian-Lang/RAGPT 获取。

> Multimodal learning with incomplete modality is practical and challenging. Recently, researchers have focused on enhancing the robustness of pre-trained MultiModal Transformers (MMTs) under missing modality conditions by applying learnable prompts. However, these prompt-based methods face several limitations: (1) incomplete modalities provide restricted modal cues for task-specific inference, (2) dummy imputation for missing content causes information loss and introduces noise, and (3) static prompts are instance-agnostic, offering limited knowledge for instances with various missing conditions. To address these issues, we propose RAGPT, a novel Retrieval-AuGmented dynamic Prompt Tuning framework. RAGPT comprises three modules: (I) the multi-channel retriever, which identifies similar instances through a within-modality retrieval strategy, (II) the missing modality generator, which recovers missing information using retrieved contexts, and (III) the context-aware prompter, which captures contextual knowledge from relevant instances and generates dynamic prompts to largely enhance the MMT's robustness. Extensive experiments conducted on three real-world datasets show that RAGPT consistently outperforms all competitive baselines in handling incomplete modality problems. The code of our work and prompt-based baselines is available at https://github.com/Jian-Lang/RAGPT.

[Arxiv](https://arxiv.org/abs/2501.01120)