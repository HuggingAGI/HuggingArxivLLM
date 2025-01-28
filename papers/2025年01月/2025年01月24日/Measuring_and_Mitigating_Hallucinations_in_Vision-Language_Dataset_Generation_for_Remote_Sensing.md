# 遥感视觉语言数据集生成中的幻觉测量与缓解

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）生成遥感领域的图像字幕，并提出了缓解LLM生成文本中幻觉问题的方法。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `多模态数据集`

> Measuring and Mitigating Hallucinations in Vision-Language Dataset Generation for Remote Sensing

# 摘要

> 视觉语言模型在多个领域表现亮眼，但在遥感领域的应用却寥寥无几，主要原因是缺乏配对的图像-文本数据。为了填补这一空白，合成字幕生成逐渐受到关注，传统方法依赖基于规则的系统，利用元数据或边界框生成描述。然而，这些方法往往难以深入捕捉复杂的广域场景。大型语言模型（LLMs）为生成更具描述性的字幕提供了新思路，但其输出容易泛化且存在幻觉问题。本文提出了一种新方法，通过引入地图作为外部数据源，增强遥感领域的视觉语言数据集，生成细节丰富、上下文充实的字幕。同时，我们还提出了测量和缓解LLM生成文本中幻觉的方法。我们推出了fMoW-mm，一个包含卫星图像、地图、元数据和文本注释的多模态数据集，并在少样本设置中展示了其在自动目标识别中的卓越性能，超越了其他视觉语言遥感数据集。

> Vision language models have achieved impressive results across various fields. However, adoption in remote sensing remains limited, largely due to the scarcity of paired image-text data. To bridge this gap, synthetic caption generation has gained interest, traditionally relying on rule-based methods that use metadata or bounding boxes. While these approaches provide some description, they often lack the depth needed to capture complex wide-area scenes. Large language models (LLMs) offer a promising alternative for generating more descriptive captions, yet they can produce generic outputs and are prone to hallucination. In this paper, we propose a new method to enhance vision-language datasets for remote sensing by integrating maps as external data sources, enabling the generation of detailed, context-rich captions. Additionally, we present methods to measure and mitigate hallucinations in LLM-generated text. We introduce fMoW-mm, a multimodal dataset incorporating satellite imagery, maps, metadata, and text annotations. We demonstrate its effectiveness for automatic target recognition in few-shot settings, achieving superior performance compared to other vision-language remote sensing datasets.

[Arxiv](https://arxiv.org/abs/2501.14905)