# MODA: 一种创新的模块化双路注意力机制，专为多模态感知、认知与情感理解设计

发布时间：2025年07月06日

`LLM理论` `人工智能` `跨模态数据处理`

> MODA: MOdular Duplex Attention for Multimodal Perception, Cognition, and Emotion Understanding

# 摘要

> 多模态大型语言模型（MLLMs）凭借通用化的注意力架构，近期在跨模态数据整合方面展现出强大能力。然而，现有方法主要聚焦于语言中心的微调，对通过注意力机制混合的多模态令牌探索不足，这对需要精细认知和情感理解的高级任务构成挑战。本研究发现多模态学习中的注意力缺陷问题，该问题源于跨模态注意力不一致和逐层衰减的注意力激活。为解决此问题，我们提出了一种新型注意力机制——模块化双模态注意力（MODA，MOdular Duplex Attention），它能够同时实现模态内优化和模态间交互。MODA采用“先对齐后修正”的策略，有效分离了模态对齐与跨层令牌混合。在对齐阶段，令牌基于基向量映射到双模态空间，从而实现视觉与语言模态的交互。此外，通过自适应掩码注意力确保注意力分数的准确性，允许为不同模态定制掩码模式，提升模型的灵活性。在21个基准数据集上的广泛实验验证了MODA在感知、认知和情感任务中的有效性。源代码和演示可在https://zzcheng.top/MODA获取。

> Multimodal large language models (MLLMs) recently showed strong capacity in integrating data among multiple modalities, empowered by a generalizable attention architecture. Advanced methods predominantly focus on language-centric tuning while less exploring multimodal tokens mixed through attention, posing challenges in high-level tasks that require fine-grained cognition and emotion understanding. In this work, we identify the attention deficit disorder problem in multimodal learning, caused by inconsistent cross-modal attention and layer-by-layer decayed attention activation. To address this, we propose a novel attention mechanism, termed MOdular Duplex Attention (MODA), simultaneously conducting the inner-modal refinement and inter-modal interaction. MODA employs a correct-after-align strategy to effectively decouple modality alignment from cross-layer token mixing. In the alignment phase, tokens are mapped to duplex modality spaces based on the basis vectors, enabling the interaction between visual and language modality. Further, the correctness of attention scores is ensured through adaptive masked attention, which enhances the model's flexibility by allowing customizable masking patterns for different modalities. Extensive experiments on 21 benchmark datasets verify the effectiveness of MODA in perception, cognition, and emotion tasks. Source code and demo are available in https://zzcheng.top/MODA.

[Arxiv](https://arxiv.org/abs/2507.04635)