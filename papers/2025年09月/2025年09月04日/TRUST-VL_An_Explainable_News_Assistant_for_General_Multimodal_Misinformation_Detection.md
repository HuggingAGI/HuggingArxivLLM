# TRUST-VL：面向通用多模态虚假信息检测的可解释性新闻助手

发布时间：2025年09月04日

`LLM应用` `媒体与娱乐`

> TRUST-VL: An Explainable News Assistant for General Multimodal Misinformation Detection

# 摘要

> 多模态虚假信息涵盖文本、视觉及跨模态扭曲，已成为日益严峻的社会威胁，而生成式AI更是加剧了这一问题。现有方法往往局限于单一扭曲类型，难以推广到未见场景。本研究发现，不同扭曲类型虽共享通用推理能力，却也需具备特定任务技能。我们推测，跨扭曲类型的联合训练可促进知识共享，进而提升模型的泛化能力。为此，我们提出TRUST-VL——一个统一且可解释的视觉-语言模型，专门用于通用多模态虚假信息检测。该模型内置新颖的问题感知视觉增强模块，可精准提取特定任务的视觉特征。为支持模型训练，我们还构建了TRUST-Instruct数据集——一个包含19.8万样本的大规模指令集，其结构化推理链与人类事实核查流程高度吻合。在域内及零样本基准测试中，大量实验证实TRUST-VL不仅性能达到当前最优，还具备优异的泛化能力与可解释性。

> Multimodal misinformation, encompassing textual, visual, and cross-modal distortions, poses an increasing societal threat that is amplified by generative AI. Existing methods typically focus on a single type of distortion and struggle to generalize to unseen scenarios. In this work, we observe that different distortion types share common reasoning capabilities while also requiring task-specific skills. We hypothesize that joint training across distortion types facilitates knowledge sharing and enhances the model's ability to generalize. To this end, we introduce TRUST-VL, a unified and explainable vision-language model for general multimodal misinformation detection. TRUST-VL incorporates a novel Question-Aware Visual Amplifier module, designed to extract task-specific visual features. To support training, we also construct TRUST-Instruct, a large-scale instruction dataset containing 198K samples featuring structured reasoning chains aligned with human fact-checking workflows. Extensive experiments on both in-domain and zero-shot benchmarks demonstrate that TRUST-VL achieves state-of-the-art performance, while also offering strong generalization and interpretability.

[Arxiv](https://arxiv.org/abs/2509.04448)