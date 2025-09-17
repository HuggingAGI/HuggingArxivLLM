# MSGFusion：多模态场景图引导的红外与可见光图像融合

发布时间：2025年09月16日

`其他` `医疗健康` `交通运输`

> MSGFusion: Multimodal Scene Graph-Guided Infrared and Visible Image Fusion

# 摘要

> 红外与可见光图像融合凭借两种模态在复杂恶劣环境中的强互补性，已成为研究热点。尽管基于深度学习的融合方法在特征提取、对齐、融合及重建上成效显著，但这类方法仍主要依赖纹理、对比度等低级视觉线索，难以捕捉图像中蕴含的高级语义信息。近年来，虽有研究尝试引入文本作为语义指导，但所采用的非结构化描述既未显式建模实体、属性及关系，也无法提供空间定位信息，导致细粒度融合效果受限。为解决上述问题，我们提出了MSGFusion——一种基于多模态场景图引导的红外与可见光图像融合框架。该框架通过深度耦合文本与视觉模态提取的结构化场景图，显式建模实体、属性及空间关系，并借助场景图表示、层次聚合及图驱动融合等连续模块，同步优化高级语义与低级细节。在多个公开基准数据集上的大量实验验证了MSGFusion的优越性：其性能显著超越现有最优方法，尤其在细节保留和结构清晰度上表现突出；在低光目标检测、语义分割、医学图像融合等下游任务中，也展现出更优的语义一致性和泛化能力。

> Infrared and visible image fusion has garnered considerable attention owing to the strong complementarity of these two modalities in complex, harsh environments. While deep learning-based fusion methods have made remarkable advances in feature extraction, alignment, fusion, and reconstruction, they still depend largely on low-level visual cues, such as texture and contrast, and struggle to capture the high-level semantic information embedded in images. Recent attempts to incorporate text as a source of semantic guidance have relied on unstructured descriptions that neither explicitly model entities, attributes, and relationships nor provide spatial localization, thereby limiting fine-grained fusion performance. To overcome these challenges, we introduce MSGFusion, a multimodal scene graph-guided fusion framework for infrared and visible imagery. By deeply coupling structured scene graphs derived from text and vision, MSGFusion explicitly represents entities, attributes, and spatial relations, and then synchronously refines high-level semantics and low-level details through successive modules for scene graph representation, hierarchical aggregation, and graph-driven fusion. Extensive experiments on multiple public benchmarks show that MSGFusion significantly outperforms state-of-the-art approaches, particularly in detail preservation and structural clarity, and delivers superior semantic consistency and generalizability in downstream tasks such as low-light object detection, semantic segmentation, and medical image fusion.

[Arxiv](https://arxiv.org/abs/2509.12901)