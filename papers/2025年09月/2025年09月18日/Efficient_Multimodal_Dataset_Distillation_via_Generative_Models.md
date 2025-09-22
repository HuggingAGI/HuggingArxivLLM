# 基于生成模型的高效多模态数据集蒸馏

发布时间：2025年09月18日

`其他` `媒体与娱乐`

> Efficient Multimodal Dataset Distillation via Generative Models

# 摘要

> 数据集蒸馏技术旨在从大规模数据集中提炼出小型数据集，让模型在该小型数据集上训练后，仍能在原始数据集上保持良好性能。随着大型语言模型与多模态大语言模型的迅猛发展，多模态数据集（尤其是图文数据集）的重要性日益凸显。然而，现有多模态数据集蒸馏方法受限于Matching Training Trajectories算法，不仅计算资源需求巨大，蒸馏过程更是耗时数天。为此，本研究提出EDGE——一种高效多模态数据集蒸馏的生成式蒸馏方法。具体而言，我们指出了生成式模型蒸馏多模态数据集的两大核心挑战：1）生成图像与文本缺乏相关性；2）生成样本多样性不足。为解决上述问题，我们设计了一种新的生成模型训练流程，融合双向对比损失与多样性损失。此外，我们还提出文本合成策略，通过引入更多文本信息进一步提升图文检索性能。在Flickr30K、COCO和CC3M数据集上的实验表明，该方法在性能和效率上均超越现有方案，尤其比当前最先进方法快18倍。

> Dataset distillation aims to synthesize a small dataset from a large dataset, enabling the model trained on it to perform well on the original dataset. With the blooming of large language models and multimodal large language models, the importance of multimodal datasets, particularly image-text datasets, has grown significantly. However, existing multimodal dataset distillation methods are constrained by the Matching Training Trajectories algorithm, which significantly increases the computing resource requirement, and takes days to process the distillation. In this work, we introduce EDGE, a generative distillation method for efficient multimodal dataset distillation. Specifically, we identify two key challenges of distilling multimodal datasets with generative models: 1) The lack of correlation between generated images and captions. 2) The lack of diversity among generated samples. To address the aforementioned issues, we propose a novel generative model training workflow with a bi-directional contrastive loss and a diversity loss. Furthermore, we propose a caption synthesis strategy to further improve text-to-image retrieval performance by introducing more text information. Our method is evaluated on Flickr30K, COCO, and CC3M datasets, demonstrating superior performance and efficiency compared to existing approaches. Notably, our method achieves results 18x faster than the state-of-the-art method.

[Arxiv](https://arxiv.org/abs/2509.15472)