# 利用次模子集选择优化多图像问答

发布时间：2025年05月15日

`LLM应用

理由：这篇论文主要探讨了大型多模态模型在多图问答场景中的应用，提出了基于次模子集选择技术的改进方案，优化了检索框架以提升模型的性能。虽然涉及多模态模型，但其核心在于应用层面的优化，因此归类为LLM应用。` `图像检索`

> Enhancing Multi-Image Question Answering via Submodular Subset Selection

# 摘要

> 大型多模态模型（LMMs）在单图视觉语言任务中表现优异，但在多图问答场景下却面临挑战。处理大量图像的推理任务中，这些模型面临可扩展性和检索性能的双重挑战。本研究针对MIRAGE模型的检索框架，提出了一种基于次模子集选择技术的改进方案。通过引入基于查询的次模函数（如GraphCut），我们在主要检索组件之前预选出语义相关的图像子集。实验结果表明，采用基于锚点的查询和数据增强方法能够显著提升次模检索流水线的效果，尤其在大规模数据集中的表现尤为突出。

> Large multimodal models (LMMs) have achieved high performance in vision-language tasks involving single image but they struggle when presented with a collection of multiple images (Multiple Image Question Answering scenario). These tasks, which involve reasoning over large number of images, present issues in scalability (with increasing number of images) and retrieval performance. In this work, we propose an enhancement for retriever framework introduced in MIRAGE model using submodular subset selection techniques. Our method leverages query-aware submodular functions, such as GraphCut, to pre-select a subset of semantically relevant images before main retrieval component. We demonstrate that using anchor-based queries and augmenting the data improves submodular-retriever pipeline effectiveness, particularly in large haystack sizes.

[Arxiv](https://arxiv.org/abs/2505.10533)