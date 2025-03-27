# # 动态动作融合：灵活动作编辑

发布时间：2025年03月26日

`其他` `计算机图形学`

> Dynamic Motion Blending for Versatile Motion Editing

# 摘要

> 文本引导的运动编辑突破了传统关键帧动画的限制，实现了高层语义控制和迭代修改。然而，现有方法受限于有限的预收集训练三元组，难以应对多样化的编辑场景。为此，我们提出了 MotionCutMix，在线数据增强技术，它基于输入文本动态生成训练三元组，通过融合身体部位动作。尽管 MotionCutMix 扩展了训练分布，但其组合特性带来了随机性和潜在的不协调问题。为了解决这一挑战，我们推出了 MotionReFit，一种配备运动协调器的自回归扩散模型。该模型通过分解长序列实现高效学习，而运动协调器则有效减少了运动组合带来的 artifacts。MotionReFit 无需额外规格或大型语言模型，直接从高层指令处理空间和时间上的运动编辑。通过大量实验验证，MotionReFit 在文本引导的运动编辑领域达到了当前最优水平。

> Text-guided motion editing enables high-level semantic control and iterative modifications beyond traditional keyframe animation. Existing methods rely on limited pre-collected training triplets, which severely hinders their versatility in diverse editing scenarios. We introduce MotionCutMix, an online data augmentation technique that dynamically generates training triplets by blending body part motions based on input text. While MotionCutMix effectively expands the training distribution, the compositional nature introduces increased randomness and potential body part incoordination. To model such a rich distribution, we present MotionReFit, an auto-regressive diffusion model with a motion coordinator. The auto-regressive architecture facilitates learning by decomposing long sequences, while the motion coordinator mitigates the artifacts of motion composition. Our method handles both spatial and temporal motion edits directly from high-level human instructions, without relying on additional specifications or Large Language Models. Through extensive experiments, we show that MotionReFit achieves state-of-the-art performance in text-guided motion editing.

[Arxiv](https://arxiv.org/abs/2503.20724)