# 从组织学角度对前列腺切除术标本进行体积重建

发布时间：2024年11月29日

`其他`

> Volumetric Reconstruction of Prostatectomy Specimens from Histology

# 摘要

> 前列腺癌的外科治疗往往包含器官切除，也就是前列腺切除术。这些标本的病理报告传递了与治疗相关的信息。除这些报告外，诊断过程会产生大量复杂的信息，虽其他相关医学专科对此颇感兴趣，但难以在报告中呈现。3D 组织重建能实现更好的空间可视化，还能与其他成像方式相结合。此领域现有的方法被证实劳动强度大，难以融入临床工作流程。3D-SLIVER 提供了一个简化的解决方案，以开源的 3DSlicer 扩展形式实现。我们列举了三个具体的实际场景，以展现其在提升诊断工作流程透明度以及推动多模态研究方面的潜力。实施 3D 重建过程涉及 3D-SLIVER 的四个子模块：切片协议数字化、基于该协议对任意 3D 模型进行虚拟切片、使用相干点漂移算法将切片与虚拟切片进行配准，以及利用凸包、高斯散射和线性挤压对配准信息进行 3D 重建。介绍了 3D-SLIVER 的三个应用案例：一种低工作量的病理工作流程整合方式，以及两个研究相关的案例，说明了如何对 PI-RADS 预测进行回顾性评估以及对形态模式的 3D 分布进行统计建模。3D-SLIVER 有利于增进各专科之间的跨学科交流。其设计追求应用简便，能够灵活融入各类工作流程和应用场景。在此，我们聚焦于前列腺癌患者的临床护理，但在其他肿瘤以及教育和研究方面，未来的可能性十分广阔。

> Surgical treatment for prostate cancer often involves organ removal, i.e., prostatectomy. Pathology reports on these specimens convey treatment-relevant information. Beyond these reports, the diagnostic process generates extensive and complex information that is difficult to represent in reports, although it is of significant interest to the other medical specialties involved. 3D tissue reconstruction would allow for better spatial visualization, as well as combinations with other imaging modalities. Existing approaches in this area have proven labor-intensive and challenging to integrate into clinical workflows. 3D-SLIVER provides a simplified solution, implemented as an open-source 3DSlicer extension. We outline three specific real-world scenarios to illustrate its potential to improve transparency in diagnostic workflows and contribute to multi-modal research endeavors. Implementing the 3D reconstruction process involved four sub-modules of 3D-SLIVER: digitization of slicing protocol, virtual slicing of arbitrary 3D models based on that protocol, registration of slides with virtual slices using the Coherent Point Drift algorithm, and 3D reconstruction of registered information using convex hulls, Gaussian splatter and linear extrusion. Three use cases to employ 3D-SLIVER are presented: a low-effort approach to pathology workflow integration and two research-related use cases illustrating how to perform retrospective evaluations of PI-RADS predictions and statistically model 3D distributions of morphological patterns. 3D-SLIVER allows for improved interdisciplinary communication among specialties. It is designed for simplicity in application, allowing for flexible integration into various workflows and use cases. Here we focused on the clinical care of prostate cancer patients, but future possibilities are extensive with other neoplasms and in education and research.

[Arxiv](https://arxiv.org/abs/2412.01855)