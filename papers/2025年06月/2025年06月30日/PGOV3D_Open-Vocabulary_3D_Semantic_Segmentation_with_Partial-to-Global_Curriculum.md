# PGOV3D: 开放词汇三维语义分割，基于从局部到全局的课程学习方法。

发布时间：2025年06月30日

`LLM应用

理由：这篇论文主要探讨了如何将多模态大型语言模型（MLLM）应用于3D语义分割任务，特别是通过生成开放词汇表标签和伪标签来提升模型性能。虽然涉及到了LLM的应用，但其核心贡献在于如何利用LLM来改进3D分割模型，属于LLM的具体应用领域。` `计算机视觉` `机器学习`

> PGOV3D: Open-Vocabulary 3D Semantic Segmentation with Partial-to-Global Curriculum

# 摘要

> 现有的开放词汇表 3D 语义分割方法通常通过将多视图图像中提取的与文本对齐的特征（如 CLIP）合并到 3D 点上，来监督 3D 分割模型。然而，这些方法仅将多视图图像视为传输开放词汇表信息的中介，忽略了它们丰富的语义内容和跨视图对应关系，这限制了模型的效果。为了解决这一问题，我们提出了 PGOV3D，这是一个引入部分到全局课程学习框架来改进开放词汇表 3D 语义分割的新颖框架。

PGOV3D 的核心创新在于其两阶段训练策略。第一阶段，我们使用提供密集语义信息但几何相对简单的局部场景对模型进行预训练。这些局部点云通过基于多视图 RGB-D 输入的逐像素深度投影获得。为了实现开放词汇表学习，我们利用多模态大型语言模型 (MLLM) 和 2D 分割基础模型为每个视点生成开放词汇表标签，提供丰富且对齐的监督信号。同时，引入辅助帧间一致性模块以强制执行不同视点之间的特征一致性并增强空间理解。

第二阶段，我们对模型进行微调，使用完整场景级别的点云，这些点云较为稀疏且结构更为复杂。我们聚合每个场景相关的部分词汇表，并使用预训练模型生成伪标签，有效弥合密集局部观察与大规模 3D 环境之间的语义鸿沟。

在 ScanNet、ScanNet200 和 S3DIS 基准测试上的大量实验表明，PGOV3D 在开放词汇表 3D 语义分割方面实现了具有竞争力的性能。

> Existing open-vocabulary 3D semantic segmentation methods typically supervise 3D segmentation models by merging text-aligned features (e.g., CLIP) extracted from multi-view images onto 3D points. However, such approaches treat multi-view images merely as intermediaries for transferring open-vocabulary information, overlooking their rich semantic content and cross-view correspondences, which limits model effectiveness. To address this, we propose PGOV3D, a novel framework that introduces a Partial-to-Global curriculum for improving open-vocabulary 3D semantic segmentation. The key innovation lies in a two-stage training strategy. In the first stage, we pre-train the model on partial scenes that provide dense semantic information but relatively simple geometry. These partial point clouds are derived from multi-view RGB-D inputs via pixel-wise depth projection. To enable open-vocabulary learning, we leverage a multi-modal large language model (MLLM) and a 2D segmentation foundation model to generate open-vocabulary labels for each viewpoint, offering rich and aligned supervision. An auxiliary inter-frame consistency module is introduced to enforce feature consistency across varying viewpoints and enhance spatial understanding. In the second stage, we fine-tune the model on complete scene-level point clouds, which are sparser and structurally more complex. We aggregate the partial vocabularies associated with each scene and generate pseudo labels using the pre-trained model, effectively bridging the semantic gap between dense partial observations and large-scale 3D environments. Extensive experiments on ScanNet, ScanNet200, and S3DIS benchmarks demonstrate that PGOV3D achieves competitive performance in open-vocabulary 3D semantic segmentation.

[Arxiv](https://arxiv.org/abs/2506.23607)