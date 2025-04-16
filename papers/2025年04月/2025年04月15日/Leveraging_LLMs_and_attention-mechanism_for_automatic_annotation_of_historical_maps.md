# 借助大型语言模型和注意力机制的历史地图自动标注方法

发布时间：2025年04月15日

`LLM应用

论文摘要：历史地图是不可或缺的资源，为我们提供了了解过去地理景观的窗口。它们是研究人员的宝贵工具，尤其在历史、地理和城市研究等领域，帮助我们重建历史环境并分析随时间推移的空间变化。然而，当历史地图受限于模拟或扫描格式时，其解读仅限于人类，因此无法大规模应用。近年来，机器学习，特别是计算机视觉和大型语言模型（LLMs）的进展，为自动识别和分类历史地图中的特征和对象开辟了新的途径。本文提出了一种新颖的蒸馏方法，结合LLMs和注意力机制，用于历史地图的自动标注。LLMs被用于为低分辨率的历史图像块生成粗略分类标签，而注意力机制则用于将这些标签细化到更高的分辨率。实验结果表明，细化后的标签达到了超过90%的高召回率。此外，交并比（IoU）得分——木材类别为84.2%，定居点类别为72.0%——以及各自的精确度得分87.1%和79.5%，表明大多数标签与真实标注高度一致。值得注意的是，这些结果是在训练过程中未使用精细的手动标签的情况下实现的，突显了我们方法在高效和可扩展的历史地图分析方面的潜力。

LLM应用` `历史研究` `地理信息系统`

> Leveraging LLMs and attention-mechanism for automatic annotation of historical maps

# 摘要

> 历史地图是不可或缺的资源，为我们提供了了解过去地理景观的窗口。它们是研究人员的宝贵工具，尤其在历史、地理和城市研究等领域，帮助我们重建历史环境并分析随时间推移的空间变化。然而，当历史地图受限于模拟或扫描格式时，其解读仅限于人类，因此无法大规模应用。近年来，机器学习，特别是计算机视觉和大型语言模型（LLMs）的进展，为自动识别和分类历史地图中的特征和对象开辟了新的途径。本文提出了一种新颖的蒸馏方法，结合LLMs和注意力机制，用于历史地图的自动标注。LLMs被用于为低分辨率的历史图像块生成粗略分类标签，而注意力机制则用于将这些标签细化到更高的分辨率。实验结果表明，细化后的标签达到了超过90%的高召回率。此外，交并比（IoU）得分——木材类别为84.2%，定居点类别为72.0%——以及各自的精确度得分87.1%和79.5%，表明大多数标签与真实标注高度一致。值得注意的是，这些结果是在训练过程中未使用精细的手动标签的情况下实现的，突显了我们方法在高效和可扩展的历史地图分析方面的潜力。

> Historical maps are essential resources that provide insights into the geographical landscapes of the past. They serve as valuable tools for researchers across disciplines such as history, geography, and urban studies, facilitating the reconstruction of historical environments and the analysis of spatial transformations over time. However, when constrained to analogue or scanned formats, their interpretation is limited to humans and therefore not scalable. Recent advancements in machine learning, particularly in computer vision and large language models (LLMs), have opened new avenues for automating the recognition and classification of features and objects in historical maps. In this paper, we propose a novel distillation method that leverages LLMs and attention mechanisms for the automatic annotation of historical maps. LLMs are employed to generate coarse classification labels for low-resolution historical image patches, while attention mechanisms are utilized to refine these labels to higher resolutions. Experimental results demonstrate that the refined labels achieve a high recall of more than 90%. Additionally, the intersection over union (IoU) scores--84.2% for Wood and 72.0% for Settlement--along with precision scores of 87.1% and 79.5%, respectively, indicate that most labels are well-aligned with ground-truth annotations. Notably, these results were achieved without the use of fine-grained manual labels during training, underscoring the potential of our approach for efficient and scalable historical map analysis.

[Arxiv](https://arxiv.org/abs/2504.11050)