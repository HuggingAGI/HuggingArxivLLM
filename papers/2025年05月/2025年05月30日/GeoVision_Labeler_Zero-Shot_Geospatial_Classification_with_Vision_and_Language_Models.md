# GeoVision 标注器：基于视觉与语言模型的零样本地理空间分类

发布时间：2025年05月30日

`LLM应用

理由：这篇论文展示了大型语言模型（LLM）在地理空间图像分类中的应用，特别是通过零样本分类框架GeoVision Labeler (GVL) 实现图像分类任务。该框架利用vLLM生成图像描述，再通过传统LLM进行分类，属于LLM的实际应用案例。` `地理空间` `图像分类`

> GeoVision Labeler: Zero-Shot Geospatial Classification with Vision and Language Models

# 摘要

> 地理空间图像分类在灾害响应和土地使用监测等领域仍面临重大挑战，特别是在数据标注稀缺的地区。现有工具（如RS-CLIP）虽声称具备零样本分类能力，但实际仍需依赖特定任务的预训练和调整。我们推出GeoVision Labeler (GVL)，一个严格的零样本分类框架：视觉大型语言模型（vLLM）生成丰富且易于理解的图像描述，再通过传统大型语言模型（LLM）将其映射至用户定义的类别。这种模块化且可解释的流程为多种应用场景提供了灵活的图像分类解决方案。我们在SpaceNet v7、UC Merced和RESISC45三个基准测试中评估了GVL的表现。在SpaceNet v7的二元“建筑 vs. 非建筑”任务中，GVL实现了高达93.2%的零样本分类准确率。针对UC Merced和RESISC45等复杂多类分类任务，我们采用递归LLM驱动的聚类方法，在不同层次形成元类别，并通过层次分类——先解决粗略类别，再进行精细区分——实现了优异的零样本性能。GVL已在GitHub开源（https://github.com/microsoft/geo-vision-labeler），旨在推动其在实际地理空间工作流程中的广泛应用。

> Classifying geospatial imagery remains a major bottleneck for applications such as disaster response and land-use monitoring-particularly in regions where annotated data is scarce or unavailable. Existing tools (e.g., RS-CLIP) that claim zero-shot classification capabilities for satellite imagery nonetheless rely on task-specific pretraining and adaptation to reach competitive performance. We introduce GeoVision Labeler (GVL), a strictly zero-shot classification framework: a vision Large Language Model (vLLM) generates rich, human-readable image descriptions, which are then mapped to user-defined classes by a conventional Large Language Model (LLM). This modular, and interpretable pipeline enables flexible image classification for a large range of use cases. We evaluated GVL across three benchmarks-SpaceNet v7, UC Merced, and RESISC45. It achieves up to 93.2% zero-shot accuracy on the binary Buildings vs. No Buildings task on SpaceNet v7. For complex multi-class classification tasks (UC Merced, RESISC45), we implemented a recursive LLM-driven clustering to form meta-classes at successive depths, followed by hierarchical classification-first resolving coarse groups, then finer distinctions-to deliver competitive zero-shot performance. GVL is open-sourced at https://github.com/microsoft/geo-vision-labeler to catalyze adoption in real-world geospatial workflows.

[Arxiv](https://arxiv.org/abs/2505.24340)