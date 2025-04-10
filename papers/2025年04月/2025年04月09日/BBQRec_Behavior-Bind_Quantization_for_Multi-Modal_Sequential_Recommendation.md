# # BBQRec：多模态序列推荐中的行为绑定量化

发布时间：2025年04月09日

`LLM应用` `推荐系统` `电子商务`

> BBQRec: Behavior-Bind Quantization for Multi-Modal Sequential Recommendation

# 摘要

> 多模态序列推荐系统通过引入辅助信号（如文本、图像）来缓解用户-项目交互中的数据稀疏性问题。然而，现有的方法虽然利用大语言模型将不同模态编码为离散语义ID以实现自回归预测，但仍存在两大关键局限：（1）现有方法采用分散量化方式，将各模态独立映射到与行为目标不一致的语义空间中；（2）对语义ID的过度依赖破坏了跨模态语义连贯性，从而削弱了多模态表示对多样化用户偏好的建模能力。

为了解决这些问题，我们提出了一种基于行为绑定的多模态量化方法（BBQRec），该方法结合双对齐量化和语义感知序列建模。首先，我们的行为-语义对齐模块通过对比式代码本学习，从噪声的模态特定特征中提取出模态无关的行为模式，确保生成的语义ID与推荐任务目标天然关联。其次，我们设计了一种离散相似性重加权机制，利用量化语义关系动态调整自注意力分数，在保持多模态协同作用的同时，避免对序列建模架构进行侵入式修改。在四个真实世界基准上的广泛评估表明，BBQRec在性能上显著优于现有的最先进基线方法。

> Multi-modal sequential recommendation systems leverage auxiliary signals (e.g., text, images) to alleviate data sparsity in user-item interactions. While recent methods exploit large language models to encode modalities into discrete semantic IDs for autoregressive prediction, we identify two critical limitations: (1) Existing approaches adopt fragmented quantization, where modalities are independently mapped to semantic spaces misaligned with behavioral objectives, and (2) Over-reliance on semantic IDs disrupts inter-modal semantic coherence, thereby weakening the expressive power of multi-modal representations for modeling diverse user preferences.
  To address these challenges, we propose a Behavior-Bind multi-modal Quantization for Sequential Recommendation (BBQRec for short) featuring dual-aligned quantization and semantics-aware sequence modeling. First, our behavior-semantic alignment module disentangles modality-agnostic behavioral patterns from noisy modality-specific features through contrastive codebook learning, ensuring semantic IDs are inherently tied to recommendation tasks. Second, we design a discretized similarity reweighting mechanism that dynamically adjusts self-attention scores using quantized semantic relationships, preserving multi-modal synergies while avoiding invasive modifications to the sequence modeling architecture. Extensive evaluations across four real-world benchmarks demonstrate BBQRec's superiority over the state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2504.06636)