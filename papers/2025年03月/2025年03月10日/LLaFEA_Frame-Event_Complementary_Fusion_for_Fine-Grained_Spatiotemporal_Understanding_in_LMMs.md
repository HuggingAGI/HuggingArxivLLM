# LLaFEA：帧-事件互补融合，助力大语言模型实现细粒度时空理解

发布时间：2025年03月10日

`其他` `计算机视觉` `视频分析`

> LLaFEA: Frame-Event Complementary Fusion for Fine-Grained Spatiotemporal Understanding in LMMs

# 摘要

> 大型多模态模型（LMMs）在场景理解方面表现出色，但在细粒度时空推理方面表现欠佳，这归因于语言与视觉表示之间的弱对齐问题。现有方法将文本位置和持续时间映射到基于帧视频编码的视觉空间中，但面临时间稀疏性问题，限制了语言-视觉时间协调能力。为解决这一问题，我们引入了LLaFEA（大型语言和帧-事件助手），利用事件相机实现密集时序感知，并进行帧-事件融合。我们的方法采用交叉注意力机制整合互补的空间和时间特征，随后通过自注意力匹配实现全局时空关联。此外，我们将文本位置和持续时间令牌嵌入融合后的视觉空间，以提升细粒度对齐效果。这一统一框架确保了强大的时空坐标对齐能力，使LMMs能够解读任意位置和任意时间的场景。此外，我们构建了一个包含真实世界帧-事件及其坐标指令的数据集，并通过广泛实验验证了所提方法的有效性。

> Large multimodal models (LMMs) excel in scene understanding but struggle with fine-grained spatiotemporal reasoning due to weak alignment between linguistic and visual representations. Existing methods map textual positions and durations into the visual space encoded from frame-based videos, but suffer from temporal sparsity that limits language-vision temporal coordination. To address this issue, we introduce LLaFEA (Large Language and Frame-Event Assistant) to leverage event cameras for temporally dense perception and frame-event fusion. Our approach employs a cross-attention mechanism to integrate complementary spatial and temporal features, followed by self-attention matching for global spatio-temporal associations. We further embed textual position and duration tokens into the fused visual space to enhance fine-grained alignment. This unified framework ensures robust spatio-temporal coordinate alignment, enabling LMMs to interpret scenes at any position and any time. In addition, we construct a dataset of real-world frames-events with coordinate instructions and conduct extensive experiments to validate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2503.06934)