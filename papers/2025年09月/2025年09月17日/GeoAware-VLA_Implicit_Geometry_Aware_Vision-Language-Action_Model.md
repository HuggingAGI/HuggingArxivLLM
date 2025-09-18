# GeoAware-VLA：隐式几何感知的视觉-语言-动作模型

发布时间：2025年09月17日

`Agent` `工业与制造`

> GeoAware-VLA: Implicit Geometry Aware Vision-Language-Action Model

# 摘要

> 视觉-语言-动作（VLA）模型在面对新相机视角时常常泛化乏力，症结在于它们难以从2D图像中推断出鲁棒的3D几何结构。为此，我们提出了GeoAware-VLA——一种简洁高效的方法，通过在视觉骨干网络中融入强大的几何先验来增强视角不变性。我们并未训练新的视觉编码器，也不依赖显式3D数据，而是将冻结的预训练几何视觉模型用作特征提取器，再通过可训练的投影层将这些几何信息丰富的特征适配给策略解码器，从而省去从零学习3D一致性的麻烦。在LIBERO基准子集上的广泛评估显示，GeoAware-VLA在零样本泛化到新相机姿态方面表现卓越，模拟环境中的成功率提升超2倍。更重要的是，这些优势成功迁移到了物理世界：我们的模型在真实机器人上性能显著提升，尤其在面对从未见过的相机角度时。该方法在连续与离散动作空间中均有效，印证了鲁棒的几何基础是构建更具泛化能力的机器人智能体的核心要素。

> Vision-Language-Action (VLA) models often fail to generalize to novel camera viewpoints, a limitation stemming from their difficulty in inferring robust 3D geometry from 2D images. We introduce GeoAware-VLA, a simple yet effective approach that enhances viewpoint invariance by integrating strong geometric priors into the vision backbone. Instead of training a visual encoder or relying on explicit 3D data, we leverage a frozen, pretrained geometric vision model as a feature extractor. A trainable projection layer then adapts these geometrically-rich features for the policy decoder, relieving it of the burden of learning 3D consistency from scratch. Through extensive evaluations on LIBERO benchmark subsets, we show GeoAware-VLA achieves substantial improvements in zero-shot generalization to novel camera poses, boosting success rates by over 2x in simulation. Crucially, these benefits translate to the physical world; our model shows a significant performance gain on a real robot, especially when evaluated from unseen camera angles. Our approach proves effective across both continuous and discrete action spaces, highlighting that robust geometric grounding is a key component for creating more generalizable robotic agents.

[Arxiv](https://arxiv.org/abs/2509.14117)