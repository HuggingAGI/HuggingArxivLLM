# 重新思考多模态大语言模型中的视觉层选择

发布时间：2025年04月30日

`LLM理论

摘要中，研究者探讨了多模态大型语言模型（MLLMs）中视觉编码器CLIP-ViT不同层的选择及其对模型性能的影响。通过系统分析和实验，他们提出了分层表示相似性方法，并重新审视了视觉层选择问题，旨在优化模型性能。这属于对LLM内部机制和结构的深入研究，符合LLM理论的分类标准。` `计算机视觉`

> Rethinking Visual Layer Selection in Multimodal LLMs

# 摘要

> 多模态大型语言模型（MLLMs）在广泛的任务中表现卓越，通常采用CLIP-ViT作为视觉编码器，得益于其强大的文本-图像对齐能力。尽管先前研究表明，CLIP-ViT的不同层捕捉不同类型的信息——浅层关注精细视觉细节，深层贴近文本语义，但大多数MLLMs仍基于经验而非系统分析选择视觉特征。本研究提出了一种分层表示相似性方法，将CLIP-ViT层按行为分为浅层、中层和深层，并评估其对MLLM性能的影响。以此为基础，我们大规模重新审视MLLM中的视觉层选择问题，训练了从14亿到70亿参数的LLaVA风格模型。通过涵盖10个数据集和4个任务的广泛实验，我们发现：（1）深层对OCR任务至关重要；（2）浅层和中层在涉及计数、定位和目标定位的推理任务中远超深层；（3）跨浅层、中层和深层特征的轻量级融合始终优于专门的融合基线和单层选择，在10个数据集中有9个实现了提升。我们的工作首次对MLLM中的视觉层选择进行了系统研究，为深入探究MLLM的视觉表示学习奠定了基础。

> Multimodal large language models (MLLMs) have achieved impressive performance across a wide range of tasks, typically using CLIP-ViT as their visual encoder due to its strong text-image alignment capabilities. While prior studies suggest that different CLIP-ViT layers capture different types of information, with shallower layers focusing on fine visual details and deeper layers aligning more closely with textual semantics, most MLLMs still select visual features based on empirical heuristics rather than systematic analysis. In this work, we propose a Layer-wise Representation Similarity approach to group CLIP-ViT layers with similar behaviors into {shallow, middle, and deep} categories and assess their impact on MLLM performance. Building on this foundation, we revisit the visual layer selection problem in MLLMs at scale, training LLaVA-style models ranging from 1.4B to 7B parameters. Through extensive experiments across 10 datasets and 4 tasks, we find that: (1) deep layers are essential for OCR tasks; (2) shallow and middle layers substantially outperform deep layers on reasoning tasks involving counting, positioning, and object localization; (3) a lightweight fusion of features across shallow, middle, and deep layers consistently outperforms specialized fusion baselines and single-layer selections, achieving gains on 9 out of 10 datasets. Our work offers the first principled study of visual layer selection in MLLMs, laying the groundwork for deeper investigations into visual representation learning for MLLMs.

[Arxiv](https://arxiv.org/abs/2504.21447)