# 基于扩散模型的可见-红外行人重识别数据合成方法

发布时间：2025年03月16日

`其他` `行人重识别` `计算机视觉`

> Diffusion-based Synthetic Data Generation for Visible-Infrared Person Re-Identification

# 摘要

> 模型性能与训练数据的丰富程度密不可分。在可见-红外行人重识别（VI-ReID）任务中，收集和标注大规模的、在不同摄像头和模态下拍摄的个体图像，不仅耗时费力、成本高昂，还需严格遵守数据保护法规，这为满足数据集要求带来了严峻的挑战。当前研究正在探索生成合成数据作为一种高效且保护隐私的替代方案，以替代在实际场景中收集真实数据。然而，目前尚未有专门针对VI-ReID任务的数据合成方法被提出。

本文提出了一种全新的数据生成框架——扩散模型驱动的VI-ReID数据扩展框架（DiVE），通过将身份信息与图像模态进行解耦，自动获取大量保持身份一致性的RGB-IR配对图像，从而提升VI-ReID模型的性能。具体而言，身份表征从一组具有相同ID的样本中提取，而图像模态则通过在特定模态数据上微调Stable Diffusion（SD）模型来学习。DiVE将文本驱动的图像合成扩展至保持身份一致性的RGB-IR多模态图像合成。通过直接将合成数据融入ReID模型训练，这一方法大幅降低了数据收集和标注的成本。

实验结果表明，利用DiVE生成的合成数据训练的VI-ReID模型表现显著提升。特别是在LLCM数据集上，采用合成图像进行训练的最先进方法CAJ相比基线模型，mAP指标提升了约【数学公式】。代码已开源：https://github.com/BorgDiven/DiVE

> The performance of models is intricately linked to the abundance of training data. In Visible-Infrared person Re-IDentification (VI-ReID) tasks, collecting and annotating large-scale images of each individual under various cameras and modalities is tedious, time-expensive, costly and must comply with data protection laws, posing a severe challenge in meeting dataset requirements. Current research investigates the generation of synthetic data as an efficient and privacy-ensuring alternative to collecting real data in the field. However, a specific data synthesis technique tailored for VI-ReID models has yet to be explored. In this paper, we present a novel data generation framework, dubbed Diffusion-based VI-ReID data Expansion (DiVE), that automatically obtain massive RGB-IR paired images with identity preserving by decoupling identity and modality to improve the performance of VI-ReID models. Specifically, identity representation is acquired from a set of samples sharing the same ID, whereas the modality of images is learned by fine-tuning the Stable Diffusion (SD) on modality-specific data. DiVE extend the text-driven image synthesis to identity-preserving RGB-IR multimodal image synthesis. This approach significantly reduces data collection and annotation costs by directly incorporating synthetic data into ReID model training. Experiments have demonstrated that VI-ReID models trained on synthetic data produced by DiVE consistently exhibit notable enhancements. In particular, the state-of-the-art method, CAJ, trained with synthetic images, achieves an improvement of about $9\%$ in mAP over the baseline on the LLCM dataset. Code: https://github.com/BorgDiven/DiVE

[Arxiv](https://arxiv.org/abs/2503.12472)