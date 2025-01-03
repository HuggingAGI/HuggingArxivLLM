# MINIMA：跨模态图像匹配

发布时间：2024年12月26日

`其他

理由：这篇论文主要讨论的是跨模态图像匹配的问题，提出了一个统一的跨模态图像匹配框架MINIMA，并设计了一种高效的数据引擎来生成大规模数据集。虽然论文中提到了生成模型的使用，但整体内容与Agent、RAG、LLM应用、LLM理论等分类关系不大，因此归类为“其他”。` `计算机视觉` `图像处理`

> MINIMA: Modality Invariant Image Matching

# 摘要

> # 摘要
跨视角和跨模态的图像匹配在多模态感知中至关重要。然而，不同成像系统或风格导致的模态差异给匹配任务带来了巨大挑战。现有方法通常针对特定模态提取不变特征，并在有限数据集上训练，泛化能力较差。本文提出MINIMA，一个统一的跨模态图像匹配框架。MINIMA不依赖复杂模块，而是通过数据扩展提升通用性能。我们设计了一种高效的数据引擎，能够生成包含多种模态、丰富场景和精确匹配标签的大规模数据集。具体而言，我们利用生成模型从廉价的RGB匹配数据中扩展模态，确保生成的跨模态数据继承RGB数据集的匹配标签和多样性。基于此，我们构建了MD-syn数据集，填补了通用跨模态图像匹配的数据空白。借助MD-syn，我们可以在随机模态对上直接训练先进的匹配模型，赋予其跨模态能力。在包含19种跨模态情况的领域内和零样本匹配任务中，MINIMA显著优于基线方法，甚至超越了特定模态方法。数据集和代码已开源：https://github.com/LSXI7/MINIMA。

> Image matching for both cross-view and cross-modality plays a critical role in multimodal perception. In practice, the modality gap caused by different imaging systems/styles poses great challenges to the matching task. Existing works try to extract invariant features for specific modalities and train on limited datasets, showing poor generalization. In this paper, we present MINIMA, a unified image matching framework for multiple cross-modal cases. Without pursuing fancy modules, our MINIMA aims to enhance universal performance from the perspective of data scaling up. For such purpose, we propose a simple yet effective data engine that can freely produce a large dataset containing multiple modalities, rich scenarios, and accurate matching labels. Specifically, we scale up the modalities from cheap but rich RGB-only matching data, by means of generative models. Under this setting, the matching labels and rich diversity of the RGB dataset are well inherited by the generated multimodal data. Benefiting from this, we construct MD-syn, a new comprehensive dataset that fills the data gap for general multimodal image matching. With MD-syn, we can directly train any advanced matching pipeline on randomly selected modality pairs to obtain cross-modal ability. Extensive experiments on in-domain and zero-shot matching tasks, including $19$ cross-modal cases, demonstrate that our MINIMA can significantly outperform the baselines and even surpass modality-specific methods. The dataset and code are available at https://github.com/LSXI7/MINIMA .

[Arxiv](https://arxiv.org/abs/2412.19412)