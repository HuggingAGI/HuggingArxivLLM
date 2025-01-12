# 多光谱行人检测：稀疏标注标签的应用

发布时间：2025年01月08日

`其他

理由：这篇论文主要讨论的是稀疏标注目标检测（SAOD）方法在多光谱领域的应用，特别是针对行人检测的改进。虽然涉及到了多光谱数据和行人检测，但并没有直接涉及到大型语言模型（LLM）、检索增强生成（RAG）、智能体（Agent）或LLM的理论研究。因此，这篇论文更适合归类为“其他”。` `多光谱成像` `行人检测`

> Multispectral Pedestrian Detection with Sparsely Annotated Label

# 摘要

> 尽管现有的稀疏标注目标检测（SAOD）方法在多光谱领域的稀疏标注环境（仅标注部分行人）中取得了一定进展，但仍存在两大局限：（i）对缺失标注伪标签的质量提升缺乏考虑；（ii）依赖固定的真实标注，导致只能学习多光谱领域中有限的行人视觉特征。为此，我们提出了一种新框架——稀疏标注多光谱行人检测（SAMPD）。针对局限（i），我们设计了多光谱行人感知自适应权重（MPAW）和正伪标签增强（PPE）模块，利用多光谱知识生成高质量伪标签，并通过模态特性动态调整权重，提升学习效果。针对局限（ii），我们提出了自适应行人检索增强（APRA）模块，自适应整合真实标注的行人图像块，并动态融合高质量伪标签，构建更丰富的行人学习样本池。实验表明，SAMPD在多光谱稀疏标注环境中显著提升了检测性能。

> Although existing Sparsely Annotated Object Detection (SAOD) approches have made progress in handling sparsely annotated environments in multispectral domain, where only some pedestrians are annotated, they still have the following limitations: (i) they lack considerations for improving the quality of pseudo-labels for missing annotations, and (ii) they rely on fixed ground truth annotations, which leads to learning only a limited range of pedestrian visual appearances in the multispectral domain. To address these issues, we propose a novel framework called Sparsely Annotated Multispectral Pedestrian Detection (SAMPD). For limitation (i), we introduce Multispectral Pedestrian-aware Adaptive Weight (MPAW) and Positive Pseudo-label Enhancement (PPE) module. Utilizing multispectral knowledge, these modules ensure the generation of high-quality pseudo-labels and enable effective learning by increasing weights for high-quality pseudo-labels based on modality characteristics. To address limitation (ii), we propose an Adaptive Pedestrian Retrieval Augmentation (APRA) module, which adaptively incorporates pedestrian patches from ground-truth and dynamically integrates high-quality pseudo-labels with the ground-truth, facilitating a more diverse learning pool of pedestrians. Extensive experimental results demonstrate that our SAMPD significantly enhances performance in sparsely annotated environments within the multispectral domain.

[Arxiv](https://arxiv.org/abs/2501.02640)