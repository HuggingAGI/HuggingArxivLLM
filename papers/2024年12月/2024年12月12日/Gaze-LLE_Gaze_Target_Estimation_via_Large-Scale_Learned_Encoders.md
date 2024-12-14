# Gaze-LLE：借助大规模学习编码器实现凝视目标的估计

发布时间：2024年12月12日

`LLM应用` `计算机视觉` `注视估计`

> Gaze-LLE: Gaze Target Estimation via Large-Scale Learned Encoders

# 摘要

> 摘要：我们致力于解决注视目标估计的问题，旨在预测人在场景中的注视位置。预测人的注视目标，既要考量人的外表，也要考虑场景内容。此前的工作已开发出愈发复杂的、手工打造的注视目标估计流程，精心融合了来自单独的场景编码器、头部编码器以及深度和姿势等信号的辅助模型的特征。受通用特征提取器在各类视觉任务中的成功所启发，我们提出了 Gaze-LLE，这是一个全新的 Transformer 框架，借助冻结的 DINOv2 编码器的特征来简化注视目标估计。我们为场景提取单一特征表示，并应用针对个人的位置提示，通过轻量级模块解码注视。我们在多个注视基准测试中展现出了顶尖水平的性能，并提供了大量分析来验证我们的设计选择。我们的代码可在：这个 http URL 获取。

> 
Abstract:We address the problem of gaze target estimation, which aims to predict where a person is looking in a scene. Predicting a person's gaze target requires reasoning both about the person's appearance and the contents of the scene. Prior works have developed increasingly complex, hand-crafted pipelines for gaze target estimation that carefully fuse features from separate scene encoders, head encoders, and auxiliary models for signals like depth and pose. Motivated by the success of general-purpose feature extractors on a variety of visual tasks, we propose Gaze-LLE, a novel transformer framework that streamlines gaze target estimation by leveraging features from a frozen DINOv2 encoder. We extract a single feature representation for the scene, and apply a person-specific positional prompt to decode gaze with a lightweight module. We demonstrate state-of-the-art performance across several gaze benchmarks and provide extensive analysis to validate our design choices. Our code is available at: this http URL .
    

[Arxiv](https://arxiv.org/pdf/2412.09586)