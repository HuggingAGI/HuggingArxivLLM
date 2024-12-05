# AIM: 借助令牌合并与修剪实现对多模态大型语言模型的自适应推理

发布时间：2024年12月04日

`LLM应用`

> AIM: Adaptive Inference of Multi-Modal LLMs via Token Merging and Pruning

# 摘要

> 大型语言模型（LLMs）已促成多模态LLMs的诞生，其对图像、视频等视觉数据有着出色的理解能力。然而，这类模型往往依赖视觉编码器的大量视觉标记，致使计算需求颇高，从而限制了其在资源受限环境及长上下文任务中的应用。在此项工作中，我们为多模态LLMs提出了一种无需训练的自适应推理方法，能在性能微降的前提下满足各类效率需求。我们的方法包含：a）LLMs之前基于嵌入相似度的迭代标记合并；b）基于多模态重要性在LLM层内进行渐进式标记修剪。凭借极简设计，我们的方法可用于视频和图像LLMs。在众多视频和图像基准上开展的大量实验表明，我们的方法大幅降低了计算负荷（例如，FLOPs减少【数学公式】7倍），同时维持了视频和图像LLMs的性能。而且，在相近计算成本下，我们的方法在长视频理解方面优于前沿方法（例如，在MLVU上【数学公式】+4.6）。此外，我们的深入分析为标记冗余和LLM层行为提供了见解，为设计高效多模态LLMs的未来研究给予了指导。我们的代码将在https://github.com/LaVi-Lab/AIM 上公布。

> Large language models (LLMs) have enabled the creation of multi-modal LLMs that exhibit strong comprehension of visual data such as images and videos. However, these models usually rely on extensive visual tokens from visual encoders, leading to high computational demands, which limits their applicability in resource-constrained environments and for long-context tasks. In this work, we propose a training-free adaptive inference method for multi-modal LLMs that can accommodate a broad range of efficiency requirements with a minimum performance drop. Our method consists of a) iterative token merging based on embedding similarity before LLMs, and b) progressive token pruning within LLM layers based on multi-modal importance. With a minimalist design, our method can be applied to both video and image LLMs. Extensive experiments on diverse video and image benchmarks demonstrate that, our method substantially reduces computation load (e.g., a $\textbf{7-fold}$ reduction in FLOPs) while preserving the performance of video and image LLMs. Further, under a similar computational cost, our method outperforms the state-of-the-art methods in long video understanding (e.g., $\textbf{+4.6}$ on MLVU). Additionally, our in-depth analysis provides insights into token redundancy and LLM layer behaviors, offering guidance for future research in designing efficient multi-modal LLMs. Our code will be available at https://github.com/LaVi-Lab/AIM.

[Arxiv](https://arxiv.org/abs/2412.03248)