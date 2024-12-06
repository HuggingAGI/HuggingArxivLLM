# SeeGround：用于零样本开放词汇 3D 视觉定位的“观察与定位”

发布时间：2024年12月05日

`LLM应用` `增强现实` `机器人`

> SeeGround: See and Ground for Zero-Shot Open-Vocabulary 3D Visual Grounding

# 摘要

> 3D 视觉定位（3DVG）旨在依据文本描述在 3D 场景中定位对象，这对增强现实和机器人等应用意义重大。传统 3DVG 方法依赖有标注的 3D 数据集和预设的对象类别，限制了其可扩展性和适应性。为突破这些限制，我们推出了 SeeGround，这是一个借助在大规模 2D 数据上训练的 2D 视觉语言模型（VLMs）的零样本 3DVG 框架。我们建议将 3D 场景表示为查询对齐渲染图像与空间丰富文本描述的混合，填补 3D 数据与 2D-VLMs 输入格式的鸿沟。我们提出两个模块：视角适应模块，能动态为查询相关的图像渲染选取视角；融合对齐模块，可将 2D 图像与 3D 空间描述整合以强化对象定位。在 ScanRefer 和 Nr3D 上的大量实验表明，我们的方法大幅优于现有的零样本方法。尤为显著的是，我们超越了弱监督方法，与部分完全监督方法不相上下，在 ScanRefer 上比之前的 SOTA 高 7.7%，在 Nr3D 上高 7.1%，彰显了其有效性。

> 3D Visual Grounding (3DVG) aims to locate objects in 3D scenes based on textual descriptions, which is essential for applications like augmented reality and robotics. Traditional 3DVG approaches rely on annotated 3D datasets and predefined object categories, limiting scalability and adaptability. To overcome these limitations, we introduce SeeGround, a zero-shot 3DVG framework leveraging 2D Vision-Language Models (VLMs) trained on large-scale 2D data. We propose to represent 3D scenes as a hybrid of query-aligned rendered images and spatially enriched text descriptions, bridging the gap between 3D data and 2D-VLMs input formats. We propose two modules: the Perspective Adaptation Module, which dynamically selects viewpoints for query-relevant image rendering, and the Fusion Alignment Module, which integrates 2D images with 3D spatial descriptions to enhance object localization. Extensive experiments on ScanRefer and Nr3D demonstrate that our approach outperforms existing zero-shot methods by large margins. Notably, we exceed weakly supervised methods and rival some fully supervised ones, outperforming previous SOTA by 7.7% on ScanRefer and 7.1% on Nr3D, showcasing its effectiveness.

[Arxiv](https://arxiv.org/abs/2412.04383)