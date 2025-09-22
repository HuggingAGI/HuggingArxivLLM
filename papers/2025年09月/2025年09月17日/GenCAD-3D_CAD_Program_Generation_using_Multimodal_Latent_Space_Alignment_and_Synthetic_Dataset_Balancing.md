# GenCAD-3D：基于多模态隐空间对齐与合成数据集平衡的CAD程序生成

发布时间：2025年09月17日

`其他` `工业与制造`

> GenCAD-3D: CAD Program Generation using Multimodal Latent Space Alignment and Synthetic Dataset Balancing

# 摘要

> CAD程序通过参数化命令序列编译生成精确的3D几何模型，是实现准确高效工程设计流程的基础。从点云、网格等非参数化数据生成CAD程序是一项关键但极具挑战的任务，通常需要大量人工干预。当前用于自动化CAD生成的深度生成模型受限于数据集的不平衡和规模不足，尤其是缺乏复杂CAD程序的样本表示。为此，我们提出GenCAD-3D——一个多模态生成框架，它利用对比学习对齐CAD编码器与几何编码器的潜在嵌入，并结合潜在扩散模型实现CAD序列的生成与检索。此外，我们还提出SynthBal，这是一种专门设计的合成数据增强策略，用于平衡和扩展数据集，显著提升复杂CAD几何形状的表示能力。实验结果表明，SynthBal大幅提高了重建精度，减少了无效CAD模型的生成，并显著提升了在高复杂度几何形状上的性能，超越了现有基准。这些进展对简化逆向工程流程和增强工程设计自动化具有重要意义。我们将公开发布数据集和代码，包括项目网站上的51个3D打印及激光扫描零件样本。

> CAD programs, structured as parametric sequences of commands that compile into precise 3D geometries, are fundamental to accurate and efficient engineering design processes. Generating these programs from nonparametric data such as point clouds and meshes remains a crucial yet challenging task, typically requiring extensive manual intervention. Current deep generative models aimed at automating CAD generation are significantly limited by imbalanced and insufficiently large datasets, particularly those lacking representation for complex CAD programs. To address this, we introduce GenCAD-3D, a multimodal generative framework utilizing contrastive learning for aligning latent embeddings between CAD and geometric encoders, combined with latent diffusion models for CAD sequence generation and retrieval. Additionally, we present SynthBal, a synthetic data augmentation strategy specifically designed to balance and expand datasets, notably enhancing representation of complex CAD geometries. Our experiments show that SynthBal significantly boosts reconstruction accuracy, reduces the generation of invalid CAD models, and markedly improves performance on high-complexity geometries, surpassing existing benchmarks. These advancements hold substantial implications for streamlining reverse engineering and enhancing automation in engineering design. We will publicly release our datasets and code, including a set of 51 3D-printed and laser-scanned parts on our project site.

[Arxiv](https://arxiv.org/abs/2509.15246)