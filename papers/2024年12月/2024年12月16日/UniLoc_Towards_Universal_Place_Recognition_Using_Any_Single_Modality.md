# UniLoc：致力于利用任意单一模态达成通用地点识别

发布时间：2024年12月16日

`其他` `地点识别`

> UniLoc: Towards Universal Place Recognition Using Any Single Modality

# 摘要

> 迄今为止，多数地点识别方法聚焦于单模态检索。虽说它们在特定环境里表现不错，但跨模态方法因能在地图和查询源间无缝切换而更具灵活性。其还承诺凭借统一模型降低计算需求，并通过共享参数提高样本效率。在此工作中，我们研发出通用的地点识别解决方案 UniLoc，适用于任何单一查询模态（自然语言、图像或点云）。UniLoc 借助大规模对比学习的最新成果，通过在两个层面进行分层匹配来学习：实例级匹配和场景级匹配。具体而言，我们提出了新颖的基于自注意力的池化（SAP）模块，用于评估实例描述符在聚合成地点级描述符时的重要性。在 KITTI-360 数据集上的实验表明了跨模态对地点识别的益处，在跨模态设置中性能卓越，在单模态场景中也有出色表现。我们的项目页面可在 https://yan-xia.github.io/projects/UniLoc/ 公开访问。

> To date, most place recognition methods focus on single-modality retrieval. While they perform well in specific environments, cross-modal methods offer greater flexibility by allowing seamless switching between map and query sources. It also promises to reduce computation requirements by having a unified model, and achieving greater sample efficiency by sharing parameters. In this work, we develop a universal solution to place recognition, UniLoc, that works with any single query modality (natural language, image, or point cloud). UniLoc leverages recent advances in large-scale contrastive learning, and learns by matching hierarchically at two levels: instance-level matching and scene-level matching. Specifically, we propose a novel Self-Attention based Pooling (SAP) module to evaluate the importance of instance descriptors when aggregated into a place-level descriptor. Experiments on the KITTI-360 dataset demonstrate the benefits of cross-modality for place recognition, achieving superior performance in cross-modal settings and competitive results also for uni-modal scenarios. Our project page is publicly available at https://yan-xia.github.io/projects/UniLoc/.

[Arxiv](https://arxiv.org/abs/2412.12079)