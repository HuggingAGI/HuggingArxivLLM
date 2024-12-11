# RoboMM：适用于机器人操作的一体化多模态大型模型

发布时间：2024年12月10日

`其他` `机器人` `3D 空间交互`

> RoboMM: All-in-One Multimodal Large Model for Robotic Manipulation

# 摘要

> 近年来，机器人技术因整合了更大的模型和大规模数据集而有了显著进步。不过，在把这些模型用于 3D 空间交互以及管控数据收集成本方面，仍存在挑战。为应对这些难题，我们推出了多模态机器人操控模型 RoboMM 以及综合性数据集 RoboData。RoboMM 借助相机参数和占用监督来强化 3D 感知。基于 OpenFlamingo，它融入了模态隔离掩码和多模态解码器模块，优化了模态融合与细粒度感知。RoboData 整合了若干知名数据集，提供了完备的评估系统，实现了多视图图像、相机参数、深度图和动作的首次融合，而且空间对齐有利于从各类机器人数据集中开展全面学习。配备了 RoboData 和统一的物理空间，RoboMM 是一种通用策略，能够对多个数据集中的所有任务同时进行评估，而非聚焦于有限的数据或任务选择。其设计大幅提升了机器人操控性能，将 CALVIN 上的平均序列长度从 1.7 提高到 3.3，并确保了跨实体能力，在多个数据集中达成了最前沿的成果。

> In recent years, robotics has advanced significantly through the integration of larger models and large-scale datasets. However, challenges remain in applying these models to 3D spatial interactions and managing data collection costs. To address these issues, we propose the multimodal robotic manipulation model, RoboMM, along with the comprehensive dataset, RoboData. RoboMM enhances 3D perception through camera parameters and occupancy supervision. Building on OpenFlamingo, it incorporates Modality-Isolation-Mask and multimodal decoder blocks, improving modality fusion and fine-grained perception. RoboData offers the complete evaluation system by integrating several well-known datasets, achieving the first fusion of multi-view images, camera parameters, depth maps, and actions, and the space alignment facilitates comprehensive learning from diverse robotic datasets. Equipped with RoboData and the unified physical space, RoboMM is the generalist policy that enables simultaneous evaluation across all tasks within multiple datasets, rather than focusing on limited selection of data or tasks. Its design significantly enhances robotic manipulation performance, increasing the average sequence length on the CALVIN from 1.7 to 3.3 and ensuring cross-embodiment capabilities, achieving state-of-the-art results across multiple datasets.

[Arxiv](https://arxiv.org/abs/2412.07215)