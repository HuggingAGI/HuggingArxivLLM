# MG-3D：多粒度知识强化的 3D 医学视觉语言预训练

发布时间：2024年12月08日

`LLM应用` `图像分析`

> MG-3D: Multi-Grained Knowledge-Enhanced 3D Medical Vision-Language Pre-training

# 摘要

> 3D 医疗图像分析在众多临床应用中举足轻重。然而，标注数据的稀缺和有限的泛化能力，阻碍了人工智能赋能模型的进步。放射学报告容易获取，能充当弱监督信号。但大规模的视觉语言预训练（VLP）在 3D 医疗图像分析中探索不足。具体来说，对多粒度放射学语义及其跨患者的相关性研究不够，致使大规模的体积报告数据未被充分利用。
  鉴于患者内的跨模态语义一致性和患者间的语义相关性，我们提出了一种多任务 VLP 方法 MG-3D，在大规模数据（47.1K）上进行预训练，从以下两个方面应对挑战：1）借助跨模态全局对齐和互补模态引导的局部重建，建立每个患者的体积语义与多粒度医学知识的对应关系，保证不同模态的患者内特征能连贯地呈现相同语义内容；2）依据跨患者的细粒度报告相关性关联患者间的视觉语义，并通过对比学习保持对全局个体差异的敏感性，增强判别特征表示。此外，我们深入探究缩放定律，以寻求潜在的性能提升。针对九个单模态和跨模态临床任务展开了全面评估，以衡量模型的有效性。在内部和外部数据集上进行的大量实验表明 MG-3D 具有出色的转移性、可扩展性和泛化性，展现了其在推动 3D 医疗图像分析的特征表示方面的潜力。代码将可获取：https://github.com/Xuefeng-Ni/MG-3D。

> 3D medical image analysis is pivotal in numerous clinical applications. However, the scarcity of labeled data and limited generalization capabilities hinder the advancement of AI-empowered models. Radiology reports are easily accessible and can serve as weakly-supervised signals. However, large-scale vision-language pre-training (VLP) remains underexplored in 3D medical image analysis. Specifically, the insufficient investigation into multi-grained radiology semantics and their correlations across patients leads to underutilization of large-scale volume-report data.
  Considering intra-patient cross-modal semantic consistency and inter-patient semantic correlations, we propose a multi-task VLP method, MG-3D, pre-trained on large-scale data (47.1K), addressing the challenges by the following two aspects: 1) Establishing the correspondence between volume semantics and multi-grained medical knowledge of each patient with cross-modal global alignment and complementary modality-guided local reconstruction, ensuring intra-patient features of different modalities cohesively represent the same semantic content; 2) Correlating inter-patient visual semantics based on fine-grained report correlations across patients, and keeping sensitivity to global individual differences via contrastive learning, enhancing the discriminative feature representation. Furthermore, we delve into the scaling law to explore potential performance improvements. Comprehensive evaluations across nine uni- and cross-modal clinical tasks are carried out to assess model efficacy. Extensive experiments on both internal and external datasets demonstrate the superior transferability, scalability, and generalization of MG-3D, showcasing its potential in advancing feature representation for 3D medical image analysis. Code will be available: https://github.com/Xuefeng-Ni/MG-3D.

[Arxiv](https://arxiv.org/abs/2412.05876)