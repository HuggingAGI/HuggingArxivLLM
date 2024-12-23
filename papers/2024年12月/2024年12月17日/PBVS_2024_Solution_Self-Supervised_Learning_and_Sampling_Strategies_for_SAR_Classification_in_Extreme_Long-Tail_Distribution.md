# PBVS 2024 解决方案：针对极端长尾分布中 SAR 分类的自监督学习与采样策略

发布时间：2024年12月17日

`其他` `图像识别`

> PBVS 2024 Solution: Self-Supervised Learning and Sampling Strategies for SAR Classification in Extreme Long-Tail Distribution

# 摘要

> 多模态学习研讨会（PBVS 2024）旨在借助合成孔径雷达（SAR）数据（虽难以解读，但不受天气和可见光影响）与光电（EO）数据共同学习，提升自动目标识别（ATR）系统的性能。其中子任务——多模态航拍图像挑战 - 分类，重点在于依据一组 SAR - EO 图像对及其各自的类别标签，预测低分辨率航拍图像的类别。所提供的数据集由 SAR - EO 对构成，呈现出严重的长尾分布，最大类和最小类相差超 1000 倍，导致典型的长尾方法难以适用。而且，SAR 与 EO 数据集之间的域差异，让标准多模态方法的效果大打折扣。为应对这些严峻挑战，我们提出了一种两阶段学习法，利用自监督技术，结合多模态学习，并通过 SAR 到 EO 的转换进行推理，以有效利用 EO。在 PBVS 2024 多模态航拍图像挑战 - 分类（SAR 分类）任务的最终测试阶段，我们的模型准确率达 21.45%、AUC 为 0.56、总分为 0.30，在竞赛中排名第 9 。

> The Multimodal Learning Workshop (PBVS 2024) aims to improve the performance of automatic target recognition (ATR) systems by leveraging both Synthetic Aperture Radar (SAR) data, which is difficult to interpret but remains unaffected by weather conditions and visible light, and Electro-Optical (EO) data for simultaneous learning. The subtask, known as the Multi-modal Aerial View Imagery Challenge - Classification, focuses on predicting the class label of a low-resolution aerial image based on a set of SAR-EO image pairs and their respective class labels. The provided dataset consists of SAR-EO pairs, characterized by a severe long-tail distribution with over a 1000-fold difference between the largest and smallest classes, making typical long-tail methods difficult to apply. Additionally, the domain disparity between the SAR and EO datasets complicates the effectiveness of standard multimodal methods. To address these significant challenges, we propose a two-stage learning approach that utilizes self-supervised techniques, combined with multimodal learning and inference through SAR-to-EO translation for effective EO utilization. In the final testing phase of the PBVS 2024 Multi-modal Aerial View Image Challenge - Classification (SAR Classification) task, our model achieved an accuracy of 21.45%, an AUC of 0.56, and a total score of 0.30, placing us 9th in the competition.

[Arxiv](https://arxiv.org/abs/2412.12565)