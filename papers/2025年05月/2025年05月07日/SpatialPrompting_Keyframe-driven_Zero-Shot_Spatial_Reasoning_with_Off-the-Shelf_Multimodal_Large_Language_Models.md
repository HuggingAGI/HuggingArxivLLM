# 空间提示：基于关键帧的零样本空间推理，借助现成的多模态大型语言模型实现

发布时间：2025年05月07日

`LLM应用` `三维空间推理` `计算机视觉`

> SpatialPrompting: Keyframe-driven Zero-Shot Spatial Reasoning with Off-the-Shelf Multimodal Large Language Models

# 摘要

> 本研究提出了 SpatialPrompting，一种新颖的框架，巧妙地利用现成的多模态大型语言模型的推理能力，在三维（3D）环境中实现零样本空间推理。与传统方法不同，SpatialPrompting摒弃了昂贵的3D特定微调过程，转而采用基于关键帧的提示生成策略。通过视觉语言相似性、马哈拉诺比斯距离、视场和图像清晰度等指标，该框架从图像序列中精选出多样且信息丰富的关键帧，并与相应的相机姿态数据相结合，有效抽象空间关系并推断复杂的3D结构。SpatialPrompting不仅开创了一种全新的灵活空间推理范式，利用直观的视觉和位置线索，还在ScanQA和SQA3D等基准数据集上实现了多个指标的零样本性能新高度。更重要的是，该方法彻底摆脱了对专用3D输入和微调的依赖，为传统方法提供了一种更简单、更可扩展的替代方案。

> This study introduces SpatialPrompting, a novel framework that harnesses the emergent reasoning capabilities of off-the-shelf multimodal large language models to achieve zero-shot spatial reasoning in three-dimensional (3D) environments. Unlike existing methods that rely on expensive 3D-specific fine-tuning with specialized 3D inputs such as point clouds or voxel-based features, SpatialPrompting employs a keyframe-driven prompt generation strategy. This framework uses metrics such as vision-language similarity, Mahalanobis distance, field of view, and image sharpness to select a diverse and informative set of keyframes from image sequences and then integrates them with corresponding camera pose data to effectively abstract spatial relationships and infer complex 3D structures. The proposed framework not only establishes a new paradigm for flexible spatial reasoning that utilizes intuitive visual and positional cues but also achieves state-of-the-art zero-shot performance on benchmark datasets, such as ScanQA and SQA3D, across several metrics. The proposed method effectively eliminates the need for specialized 3D inputs and fine-tuning, offering a simpler and more scalable alternative to conventional approaches.

[Arxiv](https://arxiv.org/abs/2505.04911)