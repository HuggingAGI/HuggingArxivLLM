# CROSSAN：多模态基础模型在序列推荐中的高效适配方法

发布时间：2025年04月14日

`其他` `推荐系统` `多模态处理`

> CROSSAN: Towards Efficient and Effective Adaptation of Multiple Multimodal Foundation Models for Sequential Recommendation

# 摘要

> 多模态基础模型（MFMs）擅长处理多样化的原始模态（如文本、图像、音频、视频等）。随着推荐系统逐步整合这些模态，利用MFMs生成更优的表示具有巨大潜力。然而，这些模型在序列推荐任务中的应用仍处于探索阶段。这主要是因为主流的适配方法，如微调（Fine-Tuning）甚至参数高效微调（PEFT）技术（例如Adapter和LoRA），在集成多个模态编码器时计算成本过高，严重阻碍了研究进展。因此，如何高效且有效地将多个（>2）MFMs适配到序列推荐任务中仍是一个未解之谜。
为了解决这一挑战，我们提出了一种即插即用的跨模态侧适配器网络（CROSSAN）。通过采用完全解耦的侧适配器范式，CROSSAN在实现高效计算的同时，支持跨多种模态的学习。为了优化多模态跨模态融合的最终阶段，我们引入了模态专家混合融合（MOMEF）机制。在公共数据集上，CROSSAN针对四种原始模态的基础模型适配表现优异。随着适配的MFMs数量增加，性能持续提升。我们将开放代码和数据集，以促进未来研究。

> Multimodal Foundation Models (MFMs) excel at representing diverse raw modalities (e.g., text, images, audio, videos, etc.). As recommender systems increasingly incorporate these modalities, leveraging MFMs to generate better representations has great potential. However, their application in sequential recommendation remains largely unexplored. This is primarily because mainstream adaptation methods, such as Fine-Tuning and even Parameter-Efficient Fine-Tuning (PEFT) techniques (e.g., Adapter and LoRA), incur high computational costs, especially when integrating multiple modality encoders, thus hindering research progress. As a result, it remains unclear whether we can efficiently and effectively adapt multiple (>2) MFMs for the sequential recommendation task.
  To address this, we propose a plug-and-play Cross-modal Side Adapter Network (CROSSAN). Leveraging the fully decoupled side adapter-based paradigm, CROSSAN achieves high efficiency while enabling cross-modal learning across diverse modalities. To optimize the final stage of multimodal fusion across diverse modalities, we adopt the Mixture of Modality Expert Fusion (MOMEF) mechanism. CROSSAN achieves superior performance on the public datasets for adapting four foundation models with raw modalities. Performance consistently improves as more MFMs are adapted. We will release our code and datasets to facilitate future research.

[Arxiv](https://arxiv.org/abs/2504.10307)