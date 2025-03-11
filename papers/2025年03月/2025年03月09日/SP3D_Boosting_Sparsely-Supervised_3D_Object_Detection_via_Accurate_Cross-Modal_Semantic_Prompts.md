# SP3D：基于精准跨模态语义提示的稀疏监督3D物体检测增强方法

发布时间：2025年03月09日

`LLM应用

摘要中提到的论文探讨了如何利用大规模多模态模型（LMMs）生成的跨模态语义提示来提升3D物体检测的性能。虽然主要讨论的是3D物体检测，但其核心在于利用多模态模型（可以视为一种LLM的扩展）来生成辅助信息，从而改善检测器的表现。因此，这篇论文属于LLM应用类别。` `计算机视觉` `多模态`

> SP3D: Boosting Sparsely-Supervised 3D Object Detection via Accurate Cross-Modal Semantic Prompts

# 摘要

> 稀疏监督的3D物体检测近期备受关注，其性能接近完全监督的3D物体检测器，但只需少量标注实例。然而，当准确标签极度缺失时，现有方法仍面临挑战。本文提出了一种名为SP3D的提升策略，通过利用大规模多模态模型（LMMs）生成的跨模态语义提示，增强稀疏标注条件下具有强大特征区分能力的3D检测器。具体而言，我们开发了Confident Points Semantic Transfer（CPST）模块，通过边界约束的中心聚类选择生成准确的跨模态语义提示。基于这些准确的语义提示（作为种子点），我们引入Dynamic Cluster Pseudo-label Generation（DCPG）模块，从多尺度邻近点的几何形状中生成伪监督信号。此外，我们设计了Distribution Shape分数（DS分数），用于选择高质量监督信号以训练初始3D检测器。实验表明，在标注条件极为有限的情况下，SP3D显著提升了稀疏监督检测器的性能。在零样本设置下，SP3D的表现超越了现有最优方法。代码可在https://github.com/xmuqimingxia/SP3D获取。

> Recently, sparsely-supervised 3D object detection has gained great attention, achieving performance close to fully-supervised 3D objectors while requiring only a few annotated instances. Nevertheless, these methods suffer challenges when accurate labels are extremely absent. In this paper, we propose a boosting strategy, termed SP3D, explicitly utilizing the cross-modal semantic prompts generated from Large Multimodal Models (LMMs) to boost the 3D detector with robust feature discrimination capability under sparse annotation settings. Specifically, we first develop a Confident Points Semantic Transfer (CPST) module that generates accurate cross-modal semantic prompts through boundary-constrained center cluster selection. Based on these accurate semantic prompts, which we treat as seed points, we introduce a Dynamic Cluster Pseudo-label Generation (DCPG) module to yield pseudo-supervision signals from the geometry shape of multi-scale neighbor points. Additionally, we design a Distribution Shape score (DS score) that chooses high-quality supervision signals for the initial training of the 3D detector. Experiments on the KITTI dataset and Waymo Open Dataset (WOD) have validated that SP3D can enhance the performance of sparsely supervised detectors by a large margin under meager labeling conditions. Moreover, we verified SP3D in the zero-shot setting, where its performance exceeded that of the state-of-the-art methods. The code is available at https://github.com/xmuqimingxia/SP3D.

[Arxiv](https://arxiv.org/abs/2503.06467)