# EffiComm：高效带宽的多智能体通信方案

发布时间：2025年07月25日

`其他` `智能驾驶` `车联网`

> EffiComm: Bandwidth Efficient Multi Agent Communication

# 摘要

> 协作感知让联网车辆实现信息共享，突破单车感知局限。但直接传输原始点云或完整特征图会造成车对车通信堵塞，引发时延与扩展性难题。我们提出EffiComm框架，在保持3D目标检测精度的同时，数据传输量仅为传统方案的40%。该框架基于任意模态的鸟瞰图特征图，采用两阶段优化流程：首先通过置信度掩码进行选择性传输，剪裁低效区域；随后借助图神经网络自适应调整车辆特征保留比例。剩余特征经软门控专家混合层融合，提升整合效率与效果。在OPV2V基准测试中，EffiComm以平均每帧1.5 MB的轻量传输，实现0.84 mAP@0.7的检测精度，性能超越现有方法。这充分展现了自适应学习通信在车联万物感知中的巨大潜力。

> Collaborative perception allows connected vehicles to exchange sensor information and overcome each vehicle's blind spots. Yet transmitting raw point clouds or full feature maps overwhelms Vehicle-to-Vehicle (V2V) communications, causing latency and scalability problems. We introduce EffiComm, an end-to-end framework that transmits less than 40% of the data required by prior art while maintaining state-of-the-art 3D object detection accuracy. EffiComm operates on Bird's-Eye-View (BEV) feature maps from any modality and applies a two-stage reduction pipeline: (1) Selective Transmission (ST) prunes low-utility regions with a confidence mask; (2) Adaptive Grid Reduction (AGR) uses a Graph Neural Network (GNN) to assign vehicle-specific keep ratios according to role and network load. The remaining features are fused with a soft-gated Mixture-of-Experts (MoE) attention layer, offering greater capacity and specialization for effective feature integration. On the OPV2V benchmark, EffiComm reaches 0.84 mAP@0.7 while sending only an average of approximately 1.5 MB per frame, outperforming previous methods on the accuracy-per-bit curve. These results highlight the value of adaptive, learned communication for scalable Vehicle-to-Everything (V2X) perception.

[Arxiv](https://arxiv.org/abs/2507.19354)