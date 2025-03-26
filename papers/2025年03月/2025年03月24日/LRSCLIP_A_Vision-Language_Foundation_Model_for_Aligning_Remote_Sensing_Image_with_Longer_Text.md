# LRSCLIP：用于关联遥感图像与长文本的视觉-语言基础模型

发布时间：2025年03月24日

`LLM应用` `多模态学习`

> LRSCLIP: A Vision-Language Foundation Model for Aligning Remote Sensing Image with Longer Text

# 摘要

> 针对遥感视觉语言基础模型（VLFM）在处理长文本时的技术瓶颈及短文本信息不足引发的“幻觉”问题，我们提出了一种全新的视觉语言基础模型LRSCLIP和多模态数据集LRS2M。研究的主要贡献包括：（1）通过整合多源遥感数据并结合大语言模型标注策略，构建了包含200万图像-文本对的LRS2M数据集，首次同时提供短文本和长文本，有效解决了现有数据集语义粒度受限的问题；（2）基于Long-CLIP的KPS模块设计了LRSCLIP架构，扩展了CLIP的文本处理能力，并通过双文本损失加权机制实现了细粒度跨模态特征对齐。实验结果表明，在零样本长文本跨模态检索任务中，LRSCLIP较Long-CLIP基线模型提升了10%-20%的检索精度。对于零样本短文本跨模态检索任务，LRSCLIP在Text to Image R@1、Image to Text R@1和mR指标上分别比当前最优模型GeoRSCLIP提升了0.17%、0.67%和0.92%（在RSITMD数据集上）以及0.04%、2.93%和1.28%（在RSICD数据集上）。在零样本图像分类任务（平均准确率=75.75%）和语义定位任务（Rmi=0.7653）中，LRSCLIP达到了当前最优性能。这些结果充分验证了LRSCLIP在细粒度语义理解和全局特征匹配方面的双重优势。本研究为遥感多模态学习提供了新的基准模型和数据支持。相关代码已开源，可访问https://github.com/MitsuiChen14/LRSCLIP获取。

> This study addresses the technical bottlenecks in handling long text and the "hallucination" issue caused by insufficient short text information in remote sensing vision-language foundation models (VLFM). We propose a novel vision-language foundation model, LRSCLIP, and a multimodal dataset, LRS2M. The main contributions are as follows: (1) By integrating multi-source remote sensing data and adopting a large language model labeling strategy, we construct the LRS2M dataset, which contains 2 million image-text pairs, providing both short and long texts for the first time, thus solving the problem of semantic granularity limitations in existing datasets; (2) The design of the LRSCLIP architecture based on Long-CLIP's KPS module, which extends CLIP's text processing capacity and achieves fine-grained cross-modal feature alignment through a dual-text loss weighting mechanism. Experimental results show that LRSCLIP improves retrieval accuracy by 10\%-20\% over the Long-CLIP baseline in the zero-shot long-text cross-modal retrieval task. For the zero-shot short-text cross-modal retrieval task, LRSCLIP achieves improvements over the current best model, GeoRSCLIP, with increases of 0.17\%, 0.67\%, and 0.92\% in Text to Image R@1, Image to Text R@1, and mR on RSITMD, respectively, and 0.04\%, 2.93\%, and 1.28\% on RSICD. In the zero-shot image classification task (average accuracy=75.75\%) and semantic localization task (Rmi=0.7653), LRSCLIP achieves state-of-the-art performance. These results validate the dual advantages of fine-grained semantic understanding and global feature matching in LRSCLIP. This work provides a new benchmark model and data support for remote sensing multimodal learning. The related code has been open source and is available at https://github.com/MitsuiChen14/LRSCLIP.

[Arxiv](https://arxiv.org/abs/2503.19311)