# MADTP是一种创新方法，通过多模态对齐指导下的动态令牌剪枝策略，有效提升视觉-语言Transformer模型的运算效率。

发布时间：2024年03月05日

`Agent`

> MADTP: Multimodal Alignment-Guided Dynamic Token Pruning for Accelerating Vision-Language Transformer

# 摘要

> 近期大放异彩的视觉-语言Transformer（VLT）虽表现出色，却面临着因海量视觉与语言标记带来的沉重计算负担。现有针对VLT的标记压缩研究大多基于单一模态方案，忽视了跨模态对齐对修剪过程的关键导向作用，往往导致某一模态的重要标记在另一模态分支中被误删。与此同时，现存的VLT压缩方法还欠缺依据不同输入样本灵活调整各层压缩比例的能力。因此，我们创新性地提出了一个名为“多模态对齐引导动态标记修剪”（MADTP）的新框架，旨在为各类VLT加速运算。具体而言，我们率先设计了一个巧妙的“多模态对齐引导”（MAG）模块，它能确保跨模态对齐同一语义概念的特征，使得被修剪的标记在所有模态中相对不重要。接着，我们研发出一种新颖的“动态标记修剪”（DTP）模块，可根据不同输入样例智能调整每一层的标记压缩比率。广泛的实验证明，MADTP能够在保持竞争力的同时，显著降低各类多模态模型的计算复杂度。特别是在NLVR2数据集上的BLIP模型应用中，MADTP能够将GFLOPs降低80%，且性能仅下降不到4%。

> Vision-Language Transformers (VLTs) have shown great success recently, but are meanwhile accompanied by heavy computation costs, where a major reason can be attributed to the large number of visual and language tokens. Existing token pruning research for compressing VLTs mainly follows a single-modality-based scheme yet ignores the critical role of aligning different modalities for guiding the token pruning process, causing the important tokens for one modality to be falsely pruned in another modality branch. Meanwhile, existing VLT pruning works also lack the flexibility to dynamically compress each layer based on different input samples. To this end, we propose a novel framework named Multimodal Alignment-Guided Dynamic Token Pruning (MADTP) for accelerating various VLTs. Specifically, we first introduce a well-designed Multi-modality Alignment Guidance (MAG) module that can align features of the same semantic concept from different modalities, to ensure the pruned tokens are less important for all modalities. We further design a novel Dynamic Token Pruning (DTP) module, which can adaptively adjust the token compression ratio in each layer based on different input instances. Extensive experiments on various benchmarks demonstrate that MADTP significantly reduces the computational complexity of kinds of multimodal models while preserving competitive performance. Notably, when applied to the BLIP model in the NLVR2 dataset, MADTP can reduce the GFLOPs by 80% with less than 4% performance degradation.

[Arxiv](https://arxiv.org/abs/2403.02991)