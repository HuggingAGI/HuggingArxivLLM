# # 融合空间与语义嵌入实现视频中的立体声事件定位

发布时间：2025年09月08日

`其他` `媒体与娱乐`

> Integrating Spatial and Semantic Embeddings for Stereo Sound Event Localization in Videos

# 摘要

> 本研究聚焦于常规视频内容中的立体声声事件定位与检测（含声源距离估计）这一多模态任务（3D SELD）。3D SELD是一项复杂任务，它融合了时间事件分类与空间定位，需要在空间、时间和语义维度上进行推理，而语义维度的建模难度可以说最大。传统SELD方法通常依赖多通道输入，受数据限制，难以充分利用大规模预训练的优势。为解决这一问题，我们引入语义信息来增强标准SELD架构，具体做法是整合预训练的对比性语言对齐模型：音频采用CLAP，视觉输入采用OWL-ViT。我们在DCASE2025 Task3立体SELD数据集的开发集上开展消融研究，评估这些语言对齐模型的单独作用，并与DCASE Task3基线系统进行对比测试。此外，我们还详细阐述了用于模型预训练的大型合成音频及视听数据集的构建流程，并通过左右声道交换的数据增强方法进一步扩充了这些数据集。我们的方法融合了大规模预训练、模型集成和视觉后处理技术，在DCASE 2025挑战赛Task3（B赛道）中荣获第二名，充分证明了该方法的有效性。未来研究将进一步探索特定模态的贡献及架构优化方向。

> In this study, we address the multimodal task of stereo sound event localization and detection with source distance estimation (3D SELD) in regular video content. 3D SELD is a complex task that combines temporal event classification with spatial localization, requiring reasoning across spatial, temporal, and semantic dimensions. The last is arguably the most challenging to model. Traditional SELD approaches typically rely on multichannel input, limiting their capacity to benefit from large-scale pre-training due to data constraints. To overcome this, we enhance a standard SELD architecture with semantic information by integrating pre-trained, contrastive language-aligned models: CLAP for audio and OWL-ViT for visual inputs. These embeddings are incorporated into a modified Conformer module tailored for multimodal fusion, which we refer to as the Cross-Modal Conformer. We perform an ablation study on the development set of the DCASE2025 Task3 Stereo SELD Dataset to assess the individual contributions of the language-aligned models and benchmark against the DCASE Task 3 baseline systems. Additionally, we detail the curation process of large synthetic audio and audio-visual datasets used for model pre-training. These datasets were further expanded through left-right channel swapping augmentation. Our approach, combining extensive pre-training, model ensembling, and visual post-processing, achieved second rank in the DCASE 2025 Challenge Task 3 (Track B), underscoring the effectiveness of our method. Future work will explore the modality-specific contributions and architectural refinements.

[Arxiv](https://arxiv.org/abs/2509.06598)