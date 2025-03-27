# 跨模态原型分配机制：基于补丁与文本对比的计算病理学无监督幻灯片表征学习

发布时间：2025年03月25日

`LLM应用` `人工智能`

> Cross-Modal Prototype Allocation: Unsupervised Slide Representation Learning via Patch-Text Contrast in Computational Pathology

# 摘要

> 病理学基础模型（FMs）的快速发展推动了全幻灯片图像（WSIs）表示学习领域的关注热潮。当前研究通过高质量的补丁特征提取器和精心设计的聚合方案，成功实现了幻灯片级别的表示推导。然而，基于多实例学习（MIL）的主流弱监督方法存在局限性，它们专为特定下游任务设计，导致泛化能力不足。针对这一问题，一些研究转向无监督幻灯片表示学习，但现有方法仅关注补丁的视觉特征，忽视了文本数据中蕴含的丰富语义信息。为突破这一限制，我们提出了ProAlign——一个创新的跨模态无监督幻灯片表示学习框架。具体而言，ProAlign通过大型语言模型（LLM）为WSI中的原型类型生成描述性文本，引入补丁-文本对比机制构建初始原型嵌入。同时，我们提出了一种无需额外参数的注意力聚合策略，通过衡量补丁与原型间的相似性，生成适用于多种下游任务的无监督幻灯片嵌入。在四个公开数据集上的大量实验表明，ProAlign不仅超越了现有的无监督框架，其性能甚至可与部分弱监督模型相媲美。

> With the rapid advancement of pathology foundation models (FMs), the representation learning of whole slide images (WSIs) attracts increasing attention. Existing studies develop high-quality patch feature extractors and employ carefully designed aggregation schemes to derive slide-level representations. However, mainstream weakly supervised slide representation learning methods, primarily based on multiple instance learning (MIL), are tailored to specific downstream tasks, which limits their generalizability. To address this issue, some studies explore unsupervised slide representation learning. However, these approaches focus solely on the visual modality of patches, neglecting the rich semantic information embedded in textual data. In this work, we propose ProAlign, a cross-modal unsupervised slide representation learning framework. Specifically, we leverage a large language model (LLM) to generate descriptive text for the prototype types present in a WSI, introducing patch-text contrast to construct initial prototype embeddings. Furthermore, we propose a parameter-free attention aggregation strategy that utilizes the similarity between patches and these prototypes to form unsupervised slide embeddings applicable to a wide range of downstream tasks. Extensive experiments on four public datasets show that ProAlign outperforms existing unsupervised frameworks and achieves performance comparable to some weakly supervised models.

[Arxiv](https://arxiv.org/abs/2503.20190)