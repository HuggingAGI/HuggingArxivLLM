# 评测与解决：多模态情感推理中的情绪冲突

发布时间：2025年08月02日

`LLM应用` `情感计算` `多模态`

> Benchmarking and Bridging Emotion Conflicts for Multimodal Emotion Reasoning

# 摘要

> 尽管现有的多模态大型语言模型（MLLMs）在多模态情感推理方面表现出色，但它们往往忽视了涉及情感冲突的场景，即不同模态的情感线索存在不一致。为填补这一空白，我们引入了CA-MER，这是一个新的基准测试，旨在考察MLLMs在现实情感冲突中的表现。它包含三个子集：视频对齐、音频对齐和一致，其中仅有一种或所有模态反映了真实情感。然而，通过在CA-MER上的评估发现，现有的先进情感多模态大模型在情感冲突场景中过度依赖音频信号，忽视了视觉模态中的关键线索。为了解决这一问题，我们提出了MoSEAR，一个参数高效的框架，旨在促进模态的平衡整合。MoSEAR包含两个模块：（1）MoSE，具有正则化门控机制的模态特定专家，减少了微调头中的模态偏差；（2）AR，一种注意力重分配机制，在推理过程中重新平衡冻结主干中的模态贡献。我们的框架具有两大优势：它既缓解了情感冲突，又在一致样本上提升了性能，而无需在音频和视觉模态之间进行权衡。在多个基准测试上的实验，包括MER2023、EMER、DFEW和我们的CA-MER，结果表明MoSEAR实现了最先进的性能，特别是在模态冲突条件下表现尤为突出。

> Despite their strong performance in multimodal emotion reasoning, existing Multimodal Large Language Models (MLLMs) often overlook the scenarios involving emotion conflicts, where emotional cues from different modalities are inconsistent. To fill this gap, we first introduce CA-MER, a new benchmark designed to examine MLLMs under realistic emotion conflicts. It consists of three subsets: video-aligned, audio-aligned, and consistent, where only one or all modalities reflect the true emotion. However, evaluations on our CA-MER reveal that current state-of-the-art emotion MLLMs systematically over-rely on audio signal during emotion conflicts, neglecting critical cues from visual modality. To mitigate this bias, we propose MoSEAR, a parameter-efficient framework that promotes balanced modality integration. MoSEAR consists of two modules: (1)MoSE, modality-specific experts with a regularized gating mechanism that reduces modality bias in the fine-tuning heads; and (2)AR, an attention reallocation mechanism that rebalances modality contributions in frozen backbones during inference. Our framework offers two key advantages: it mitigates emotion conflicts and improves performance on consistent samples-without incurring a trade-off between audio and visual modalities. Experiments on multiple benchmarks-including MER2023, EMER, DFEW, and our CA-MER-demonstrate that MoSEAR achieves state-of-the-art performance, particularly under modality conflict conditions.

[Arxiv](https://arxiv.org/abs/2508.01181)