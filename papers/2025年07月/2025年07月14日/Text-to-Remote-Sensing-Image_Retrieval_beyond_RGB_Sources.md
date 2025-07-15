# 超越RGB数据源的基于文本的遥感图像检索

发布时间：2025年07月14日

`其他` `灾害防治` `环境监测`

> Text-to-Remote-Sensing-Image Retrieval beyond RGB Sources

# 摘要

> 从卫星存档中检索相关图像对灾害响应和长期气候监测至关重要。然而，现有文本到图像检索系统大多局限于RGB数据，未能充分利用合成孔径雷达（SAR）的全天候结构敏感性和光学多光谱数据的光谱特征等独特信息。为此，我们推出了CrisisLandMark——一个包含647,000多张Sentinel-1 SAR和Sentinel-2多光谱图像的大型语料库，这些图像与来自权威土地覆盖系统（CORINE和Dynamic World）及危机特定来源的结构化文本注释配对，涵盖土地覆盖、土地利用和危机事件。我们还提出了CLOSP（对比语言光学SAR预训练）这一创新框架，利用文本作为桥梁，将未配对的光学和SAR图像融合到统一嵌入空间中。实验结果显示，CLOSP实现了54%的检索nDGC提升，显著超越现有模型。值得注意的是，通过从光学域向SAR域转移丰富的语义知识，CLOSP成功克服了SAR图像解释的固有挑战。此外，我们开发的GeoCLOSP框架将地理坐标纳入其中，在通用性和特定性之间实现了完美平衡：CLOSP在通用语义任务中表现卓越，而GeoCLOSP则成为专门用于检索位置相关危机事件和罕见地理特征的专业工具。这项研究表明，多传感器数据与地理上下文的整合对于充分释放遥感存档潜力至关重要。


> Retrieving relevant imagery from vast satellite archives is crucial for applications like disaster response and long-term climate monitoring. However, most text-to-image retrieval systems are limited to RGB data, failing to exploit the unique physical information captured by other sensors, such as the all-weather structural sensitivity of Synthetic Aperture Radar (SAR) or the spectral signatures in optical multispectral data. To bridge this gap, we introduce CrisisLandMark, a new large-scale corpus of over 647,000 Sentinel-1 SAR and Sentinel-2 multispectral images paired with structured textual annotations for land cover, land use, and crisis events harmonized from authoritative land cover systems (CORINE and Dynamic World) and crisis-specific sources. We then present CLOSP (Contrastive Language Optical SAR Pretraining), a novel framework that uses text as a bridge to align unpaired optical and SAR images into a unified embedding space. Our experiments show that CLOSP achieves a new state-of-the-art, improving retrieval nDGC by 54% over existing models. Additionally, we find that the unified training strategy overcomes the inherent difficulty of interpreting SAR imagery by transferring rich semantic knowledge from the optical domain with indirect interaction. Furthermore, GeoCLOSP, which integrates geographic coordinates into our framework, creates a powerful trade-off between generality and specificity: while the CLOSP excels at general semantic tasks, the GeoCLOSP becomes a specialized expert for retrieving location-dependent crisis events and rare geographic features. This work highlights that the integration of diverse sensor data and geographic context is essential for unlocking the full potential of remote sensing archives.

[Arxiv](https://arxiv.org/abs/2507.10403)