# # GroundingSuite：评测复杂多粒度像素定位

发布时间：2025年03月13日

`其他` `数据集`

> GroundingSuite: Measuring Complex Multi-Granular Pixel Grounding

# 摘要

> 像素 grounding（包括引用表达分割 RES 等任务）因其在连接视觉与语言模态方面的巨大潜力，吸引了广泛关注。然而，现有数据集的局限性（如有限的对象类别、文本多样性不足及高质量标注稀缺）制约了该领域的发展。为此，我们推出GroundingSuite，包含以下三部分：(1) 一个基于多个视觉-语言模型（VLM）代理的自动化数据标注框架；(2) 一个涵盖956万种多样化引用表达及其对应分割的大规模训练数据集；(3) 一个精心整理的评估基准，包含3,800张图像。GroundingSuite的训练数据集显著提升了模型性能，使其在gRefCOCO上达到68.9的cIoU，在RefCOCOm上实现55.3的gIoU的先进水平。此外，GroundingSuite的标注框架相较于当前领先的GLaMM方法，标注效率提升了4.5倍。


> Pixel grounding, encompassing tasks such as Referring Expression Segmentation (RES), has garnered considerable attention due to its immense potential for bridging the gap between vision and language modalities. However, advancements in this domain are currently constrained by limitations inherent in existing datasets, including limited object categories, insufficient textual diversity, and a scarcity of high-quality annotations. To mitigate these limitations, we introduce GroundingSuite, which comprises: (1) an automated data annotation framework leveraging multiple Vision-Language Model (VLM) agents; (2) a large-scale training dataset encompassing 9.56 million diverse referring expressions and their corresponding segmentations; and (3) a meticulously curated evaluation benchmark consisting of 3,800 images. The GroundingSuite training dataset facilitates substantial performance improvements, enabling models trained on it to achieve state-of-the-art results. Specifically, a cIoU of 68.9 on gRefCOCO and a gIoU of 55.3 on RefCOCOm. Moreover, the GroundingSuite annotation framework demonstrates superior efficiency compared to the current leading data annotation method, i.e., $4.5 \times$ faster than the GLaMM.

[Arxiv](https://arxiv.org/abs/2503.10596)