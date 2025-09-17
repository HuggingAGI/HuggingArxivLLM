# WHU-STree：面向行道树清查的多模态基准数据集

发布时间：2025年09月16日

`其他` `能源与环保`

> WHU-STree: A Multi-modal Benchmark Dataset for Street Tree Inventory

# 摘要

> 行道树是城市宜居的重要支柱，具有不可替代的生态与社会效益。在空间资源紧张的城市环境中，建立详细、准确且动态更新的行道树清单，对优化这些多功能资产至关重要。传统实地调查耗时费力，而利用移动测绘系统（MMS）开展自动化调查则能提供更高效的解决方案。但现有MMS树木数据集存在场景规模小、标注数据少或模态单一等问题，难以满足综合分析需求。为此，我们构建了WHU-STree——一个跨城市、标注丰富的多模态城市行道树数据集。该数据集采集自两座差异显著的城市，整合了同步点云和高分辨率图像，共包含21,007个标注树木实例，涵盖50个树种及2项形态参数。依托这些特性，WHU-STree可同时支持10余项行道树清单相关任务。我们针对树种分类和单木分割这两项核心任务，对代表性基线模型进行了性能评估。大量实验与深入分析表明，多模态数据融合具备巨大应用潜力，而跨域适用性则是算法实际落地的关键前提。特别地，我们还明确了充分挖掘WHU-STree价值面临的核心挑战，并展望了未来研究方向，包括多模态融合、多任务协同、跨域泛化、空间模式学习，以及将多模态大型语言模型应用于行道树资产管理等。WHU-STree数据集的获取链接为：https://github.com/WHU-USI3DV/WHU-STree。

> Street trees are vital to urban livability, providing ecological and social benefits. Establishing a detailed, accurate, and dynamically updated street tree inventory has become essential for optimizing these multifunctional assets within space-constrained urban environments. Given that traditional field surveys are time-consuming and labor-intensive, automated surveys utilizing Mobile Mapping Systems (MMS) offer a more efficient solution. However, existing MMS-acquired tree datasets are limited by small-scale scene, limited annotation, or single modality, restricting their utility for comprehensive analysis. To address these limitations, we introduce WHU-STree, a cross-city, richly annotated, and multi-modal urban street tree dataset. Collected across two distinct cities, WHU-STree integrates synchronized point clouds and high-resolution images, encompassing 21,007 annotated tree instances across 50 species and 2 morphological parameters. Leveraging the unique characteristics, WHU-STree concurrently supports over 10 tasks related to street tree inventory. We benchmark representative baselines for two key tasks--tree species classification and individual tree segmentation. Extensive experiments and in-depth analysis demonstrate the significant potential of multi-modal data fusion and underscore cross-domain applicability as a critical prerequisite for practical algorithm deployment. In particular, we identify key challenges and outline potential future works for fully exploiting WHU-STree, encompassing multi-modal fusion, multi-task collaboration, cross-domain generalization, spatial pattern learning, and Multi-modal Large Language Model for street tree asset management. The WHU-STree dataset is accessible at: https://github.com/WHU-USI3DV/WHU-STree.

[Arxiv](https://arxiv.org/abs/2509.13172)