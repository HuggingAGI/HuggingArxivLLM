# OW-CLIP：基于人机协作的开放世界目标检测高效视觉监督方案

发布时间：2025年07月26日

`其他` `计算机视觉` `目标检测`

> OW-CLIP: Data-Efficient Visual Supervision for Open-World Object Detection via Human-AI Collaboration

# 摘要

> 开放世界目标检测（OWOD）突破了传统目标检测的局限，不仅识别已知对象，还能发现未知目标，同时需要持续优化模型以适应新标注。然而，现有方法存在三大瓶颈：1）依赖海量众包标注，训练过程数据饥渴；2）易受“部分特征过拟合”困扰；3）由于模型架构调整需求，灵活性大打折扣。为应对这些挑战，我们推出了OW-CLIP，一个集精选数据与高效增量训练于一体的视觉分析系统。OW-CLIP创新性地采用了针对OWOD场景的插件式多模态提示微调，并引入了独特的“裁剪平滑”技术，有效缓解部分特征过拟合问题。为满足训练需求，我们设计了双模态数据精炼方法，借助大型语言模型和跨模态相似性实现数据生成与筛选。同时，我们开发了一款可视化界面，让用户能够轻松探索并生成高质量标注，包括类别专属的视觉特征描述和精细区分的图像。实验结果显示，OW-CLIP仅需3.8%的自生成数据，即可达到89%的最先进性能水平，且在相同数据量下超越现有最优方法。通过案例研究，我们验证了该方法的有效性以及可视化系统在提升标注质量方面的显著优势。

> Open-world object detection (OWOD) extends traditional object detection to identifying both known and unknown object, necessitating continuous model adaptation as new annotations emerge. Current approaches face significant limitations: 1) data-hungry training due to reliance on a large number of crowdsourced annotations, 2) susceptibility to "partial feature overfitting," and 3) limited flexibility due to required model architecture modifications. To tackle these issues, we present OW-CLIP, a visual analytics system that provides curated data and enables data-efficient OWOD model incremental training. OW-CLIP implements plug-and-play multimodal prompt tuning tailored for OWOD settings and introduces a novel "Crop-Smoothing" technique to mitigate partial feature overfitting. To meet the data requirements for the training methodology, we propose dual-modal data refinement methods that leverage large language models and cross-modal similarity for data generation and filtering. Simultaneously, we develope a visualization interface that enables users to explore and deliver high-quality annotations: including class-specific visual feature phrases and fine-grained differentiated images. Quantitative evaluation demonstrates that OW-CLIP achieves competitive performance at 89% of state-of-the-art performance while requiring only 3.8% self-generated data, while outperforming SOTA approach when trained with equivalent data volumes. A case study shows the effectiveness of the developed method and the improved annotation quality of our visualization system.

[Arxiv](https://arxiv.org/abs/2507.19870)