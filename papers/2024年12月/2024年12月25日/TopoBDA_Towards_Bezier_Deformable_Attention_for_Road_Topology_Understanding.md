# TopoBDA: 贝塞尔可变形注意力机制在道路拓扑理解中的应用

发布时间：2024年12月25日

`其他

**理由**：这篇论文主要讨论的是自动驾驶中的道路拓扑理解，提出了一种名为TopoBDA的新方法，通过贝塞尔可变形注意力（BDA）来增强道路拓扑的理解。虽然论文中提到了Transformer解码器，但其核心内容与LLM（大型语言模型）无关，而是专注于计算机视觉和自动驾驶领域的技术。因此，这篇论文不属于Agent、RAG、LLM应用或LLM理论中的任何一个类别，应归类为其他。` `自动驾驶` `道路拓扑`

> TopoBDA: Towards Bezier Deformable Attention for Road Topology Understanding

# 摘要

> # 摘要
道路拓扑的理解对自动驾驶至关重要。本文提出了一种名为TopoBDA的新方法，通过贝塞尔可变形注意力（BDA）来增强道路拓扑的理解。BDA利用贝塞尔控制点驱动可变形注意力机制，显著提升了细长多段线结构（如车道中心线）的检测与表示能力。TopoBDA通过处理多摄像头360度图像生成鸟瞰图（BEV）特征，并借助BDA驱动的Transformer解码器进行优化，在保持高精度中心线预测的同时，提升了计算效率。此外，TopoBDA还引入了实例掩码公式和辅助的一对多集合预测损失策略，进一步优化了中心线检测和道路拓扑理解。在OpenLane-V2数据集上的实验表明，TopoBDA在中心线检测和拓扑推理方面超越了现有方法，达到了业界领先水平。通过集成激光雷达和雷达等多模态数据，特别是用于道路拓扑理解，进一步提升了模型性能，凸显了其在自动驾驶中的重要性。

> Understanding road topology is crucial for autonomous driving. This paper introduces TopoBDA (Topology with Bezier Deformable Attention), a novel approach that enhances road topology understanding by leveraging Bezier Deformable Attention (BDA). BDA utilizes Bezier control points to drive the deformable attention mechanism, significantly improving the detection and representation of elongated and thin polyline structures, such as lane centerlines. TopoBDA processes multi-camera 360-degree imagery to generate Bird's Eye View (BEV) features, which are refined through a transformer decoder employing BDA. This method enhances computational efficiency while maintaining high accuracy in centerline prediction. Additionally, TopoBDA incorporates an instance mask formulation and an auxiliary one-to-many set prediction loss strategy to further refine centerline detection and improve road topology understanding. Experimental evaluations on the OpenLane-V2 dataset demonstrate that TopoBDA outperforms existing methods, achieving state-of-the-art results in centerline detection and topology reasoning. The integration of multi-modal data, including lidar and radar, specifically for road topology understanding, further enhances the model's performance, underscoring its importance in autonomous driving applications.

[Arxiv](https://arxiv.org/abs/2412.18951)