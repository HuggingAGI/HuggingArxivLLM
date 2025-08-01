# FastDriveVLA：基于即插即用的重构式标记剪枝实现高效端到端驾驶

发布时间：2025年07月31日

`其他` `自动驾驶` `计算机视觉`

> FastDriveVLA: Efficient End-to-End Driving via Plug-and-Play Reconstruction-based Token Pruning

# 摘要

> 视觉-语言-动作（VLA）模型在复杂场景理解和动作推理方面表现优异，因此在端到端自动驾驶系统中得到了广泛应用。然而，VLA模型的长视觉令牌显著增加了计算成本。当前视觉-语言模型（VLM）中的视觉令牌剪枝方法主要依赖视觉令牌相似性或视觉-文本注意力，但在自动驾驶场景中表现欠佳。鉴于人类驾驶员在驾驶时会集中注意力于相关前景区域，我们认为保留包含前景信息的视觉令牌对于有效决策至关重要。由此启发，我们提出了FastDriveVLA，这是一种专为自动驾驶设计的基于重建的新型视觉令牌剪枝框架。FastDriveVLA包含一个即插即用的视觉令牌剪枝器ReconPruner，它通过类似MAE的像素重建优先考虑前景信息。我们还设计了一种新型的对抗式前景-背景重建策略，用于训练VLA模型视觉编码器的ReconPruner。一旦训练完成，ReconPruner可以无缝应用于具有相同视觉编码器的不同VLA模型，无需重新训练。为了训练ReconPruner，我们引入了一个大规模数据集nuScenes-FG，包含241K张带标注前景区域的图像-掩码对。我们的方法在不同剪枝比例下，在nuScenes闭环规划基准测试中达到了最先进的结果。

> Vision-Language-Action (VLA) models have demonstrated significant potential in complex scene understanding and action reasoning, leading to their increasing adoption in end-to-end autonomous driving systems. However, the long visual tokens of VLA models greatly increase computational costs. Current visual token pruning methods in Vision-Language Models (VLM) rely on either visual token similarity or visual-text attention, but both have shown poor performance in autonomous driving scenarios. Given that human drivers concentrate on relevant foreground areas while driving, we assert that retaining visual tokens containing this foreground information is essential for effective decision-making. Inspired by this, we propose FastDriveVLA, a novel reconstruction-based vision token pruning framework designed specifically for autonomous driving. FastDriveVLA includes a plug-and-play visual token pruner called ReconPruner, which prioritizes foreground information through MAE-style pixel reconstruction. A novel adversarial foreground-background reconstruction strategy is designed to train ReconPruner for the visual encoder of VLA models. Once trained, ReconPruner can be seamlessly applied to different VLA models with the same visual encoder without retraining. To train ReconPruner, we also introduce a large-scale dataset called nuScenes-FG, consisting of 241K image-mask pairs with annotated foreground regions. Our approach achieves state-of-the-art results on the nuScenes closed-loop planning benchmark across different pruning ratios.

[Arxiv](https://arxiv.org/abs/2507.23318)