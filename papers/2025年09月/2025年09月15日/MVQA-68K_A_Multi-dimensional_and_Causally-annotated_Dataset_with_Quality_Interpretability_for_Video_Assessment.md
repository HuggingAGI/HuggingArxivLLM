# MVQA-68K：多维度因果标注且具备质量可解释性的视频评估数据集

发布时间：2025年09月15日

`LLM应用` `媒体与娱乐`

> MVQA-68K: A Multi-dimensional and Causally-annotated Dataset with Quality Interpretability for Video Assessment

# 摘要

> 随着Sora等视频生成模型的迅猛发展，视频质量评估（VQA）在从预训练大规模数据集中筛选高质量视频方面愈发关键。传统VQA方法通常仅输出单一数值分数，往往缺乏全面性与可解释性。为应对这些挑战，我们推出了MVQA-68K——一个全新的多维度VQA数据集，涵盖68,000余个精心标注的视频，涉及七个核心质量维度：整体美感、相机运动、动态程度、纹理细节、构图、视觉质量及事实一致性。每个标注均附带详细的思维链推理过程，以增强可解释性并助力全面理解。大量实验结果显示，MVQA-68K大幅提升了各类多模态大型语言模型（MLLMs）在VQA任务上的表现，不仅在我们的内部测试集（图1）上，还在LSVQ-test、LSVQ-1080p及LIVE-VQC等公共基准测试集上均刷新了当前最佳性能。同时，在VQA训练中融入显式推理过程能显著增强模型的零样本泛化能力。代码与数据集将在GitHub开源：https://github.com/Controller01-ai/MVQA-68K

> With the rapid advancement of video generation models such as Sora, video quality assessment (VQA) is becoming increasingly crucial for selecting high-quality videos from large-scale datasets used in pre-training. Traditional VQA methods, typically producing single numerical scores, often lack comprehensiveness and interpretability. To address these challenges, we introduce MVQA-68K, a novel multi-dimensional VQA dataset comprising over 68,000 carefully annotated videos, covering seven essential quality dimensions: overall aesthetics, camera movement, dynamic degree, texture detail, composition, visual quality, and factual consistency. Each annotation includes detailed chain-of-thought reasoning to facilitate interpretability and comprehensive understanding. Extensive experiments demonstrate that MVQA-68K significantly enhances the performance of various multimodal large language models (MLLMs) on the VQA task, achieving state-of-the-art results not only on our internal test set (Fig.1) but also on public benchmarks including LSVQ-test, LSVQ-1080p, and LIVE-VQC. Meantime, incorporating explicit reasoning process during VQA training substantially boosts the zero-shot generalization. Code and dataset will be available at github: https://github.com/Controller01-ai/MVQA-68K

[Arxiv](https://arxiv.org/abs/2509.11589)