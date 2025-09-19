# RoboEye：基于选择性三维几何关键点匹配的机器人二维目标识别增强方法

发布时间：2025年09月18日

`其他` `零售与电商`

> RoboEye: Enhancing 2D Robotic Object Identification with Selective 3D Geometric Keypoint Matching

# 摘要

> 大型电商产品类别激增，大大增加了仓库自动化包装中物体精准识别的难度。随着产品目录不断扩大，类内差异增大，罕见或视觉相似物品的长尾问题愈发突出；加之包装形态多样、容器杂乱无章、遮挡频繁且视角变化大，这些因素共同放大了查询图像与参考图像的差异，使得仅依赖2D外观特征的方法性能骤降。为此，我们提出两阶段识别框架RoboEye，它通过领域适配的3D推理与轻量级适配器动态增强2D语义特征，从而弥合训练与部署之间的鸿沟。第一阶段训练大型视觉模型提取2D特征，生成候选排序。随后，轻量级3D特征感知模块会评估3D特征质量并判断是否需要3D重排序，既能防止性能下降，又可避免冗余计算。若需启用第二阶段，则调用机器人3D检索Transformer，其包含生成几何感知密集特征的3D特征提取器，以及基于关键点的匹配器——该匹配器通过计算查询图像与参考图像的关键点对应置信度，替代传统的余弦相似度评分。实验显示，RoboEye将Recall@1指标较现有最优方法（RoboLLM）提升7.1%。此外，该框架仅需RGB图像即可运行，无需依赖显式3D输入，有效降低了部署成本。本文代码已开源：https://github.com/longkukuhi/RoboEye。

> The rapidly growing number of product categories in large-scale e-commerce makes accurate object identification for automated packing in warehouses substantially more difficult. As the catalog grows, intra-class variability and a long tail of rare or visually similar items increase, and when combined with diverse packaging, cluttered containers, frequent occlusion, and large viewpoint changes-these factors amplify discrepancies between query and reference images, causing sharp performance drops for methods that rely solely on 2D appearance features. Thus, we propose RoboEye, a two-stage identification framework that dynamically augments 2D semantic features with domain-adapted 3D reasoning and lightweight adapters to bridge training deployment gaps. In the first stage, we train a large vision model to extract 2D features for generating candidate rankings. A lightweight 3D-feature-awareness module then estimates 3D feature quality and predicts whether 3D re-ranking is necessary, preventing performance degradation and avoiding unnecessary computation. When invoked, the second stage uses our robot 3D retrieval transformer, comprising a 3D feature extractor that produces geometry-aware dense features and a keypoint-based matcher that computes keypoint-correspondence confidences between query and reference images instead of conventional cosine-similarity scoring. Experiments show that RoboEye improves Recall@1 by 7.1% over the prior state of the art (RoboLLM). Moreover, RoboEye operates using only RGB images, avoiding reliance on explicit 3D inputs and reducing deployment costs. The code used in this paper is publicly available at: https://github.com/longkukuhi/RoboEye.

[Arxiv](https://arxiv.org/abs/2509.14966)