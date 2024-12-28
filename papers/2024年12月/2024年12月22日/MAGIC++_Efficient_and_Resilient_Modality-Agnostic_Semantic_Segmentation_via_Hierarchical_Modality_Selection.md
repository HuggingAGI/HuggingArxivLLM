# MAGIC++：借助分层模态选择达成高效且具弹性的模态无关语义分割

发布时间：2024年12月22日

`其他` `计算机视觉` `语义分割`

> MAGIC++: Efficient and Resilient Modality-Agnostic Semantic Segmentation via Hierarchical Modality Selection

# 摘要

> 在本文中，我们致力于攻克颇具挑战的模态无关语义分割（MaSS）难题，旨在让每种模态在每个特征粒度上的价值得以凸显。在语义分割中，借助所有可用的视觉模态进行训练，并有效融合它们的任意组合，这对于实现强大的多模态融合至关重要，尤其是在现实场景中，然而至今相关研究尚少。现有的方法往往将 RGB 置于核心，把其他模态视作次要，致使架构不对称。但仅靠 RGB 在诸如夜间等场景中存在局限，而像事件数据这类模态则表现出众。为此，我们推出了 MAGIC++ 框架，它涵盖两个关键的即插即用模块，用于实现有效的多模态融合和分层模态选择，能够与各类骨干模型适配。首先，我们引入了一个多模态交互模块，高效处理来自输入多模态批次的特征，并在通道和空间层面的引导下提取互补的场景信息。在此之上，提出了一个统一的多尺度任意模态选择模块，以聚合特征为基准，依据分层特征空间中的相似性得分对多模态特征进行排序。如此一来，我们的方法能够在每个特征粒度上摆脱对 RGB 模态的依赖，在确保分割性能的同时，更好地应对传感器故障和环境噪声。在常见的多模态设定下，我们的方法在现实世界和合成基准测试中均达到了领先水平。此外，在新颖的模态无关设定中，我们的方法表现出色，大幅超越了先前的技术。

> In this paper, we address the challenging modality-agnostic semantic segmentation (MaSS), aiming at centering the value of every modality at every feature granularity. Training with all available visual modalities and effectively fusing an arbitrary combination of them is essential for robust multi-modal fusion in semantic segmentation, especially in real-world scenarios, yet remains less explored to date. Existing approaches often place RGB at the center, treating other modalities as secondary, resulting in an asymmetric architecture. However, RGB alone can be limiting in scenarios like nighttime, where modalities such as event data excel. Therefore, a resilient fusion model must dynamically adapt to each modality's strengths while compensating for weaker inputs.To this end, we introduce the MAGIC++ framework, which comprises two key plug-and-play modules for effective multi-modal fusion and hierarchical modality selection that can be equipped with various backbone models. Firstly, we introduce a multi-modal interaction module to efficiently process features from the input multi-modal batches and extract complementary scene information with channel-wise and spatial-wise guidance. On top, a unified multi-scale arbitrary-modal selection module is proposed to utilize the aggregated features as the benchmark to rank the multi-modal features based on the similarity scores at hierarchical feature spaces. This way, our method can eliminate the dependence on RGB modality at every feature granularity and better overcome sensor failures and environmental noises while ensuring the segmentation performance. Under the common multi-modal setting, our method achieves state-of-the-art performance on both real-world and synthetic benchmarks. Moreover, our method is superior in the novel modality-agnostic setting, where it outperforms prior arts by a large margin.

[Arxiv](https://arxiv.org/abs/2412.16876)