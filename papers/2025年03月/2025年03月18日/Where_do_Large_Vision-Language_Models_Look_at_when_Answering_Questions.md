# 大型视觉-语言模型在回答问题时究竟会关注哪些细节？

发布时间：2025年03月18日

`其他` `计算机视觉` `人工智能`

> Where do Large Vision-Language Models Look at when Answering Questions?

# 摘要

> 大型视觉-语言模型（LVLMs）在视觉语言理解和推理任务中表现优异，但它们的视觉理解行为仍有待深入探索。一个核心问题是：大型视觉-语言模型在多大程度上依赖视觉输入？哪些图像区域对其生成结果起到了关键作用？由于这些模型复杂的视觉架构（如多编码器和多分辨率）以及可变长度输出，解读其生成内容颇具挑战性。本文扩展了现有的热图可视化方法（如iGOS++），以支持大型视觉-语言模型在开放性视觉问答任务中的应用。我们提出了一种方法，用于选择与视觉相关的标记，以反映生成答案与输入图像之间的关联性。此外，我们在要求视觉信息才能作答的基准测试上，对最先进的大型视觉-语言模型进行了全面分析。我们的研究发现揭示了大型视觉-语言模型的多项行为特征，包括关注区域与答案正确性之间的关系、不同架构在视觉注意力上的差异，以及大规模语言模型对视觉理解的影响。代码和数据可在https://github.com/bytedance/LVLM_Interpretation获取。

> Large Vision-Language Models (LVLMs) have shown promising performance in vision-language understanding and reasoning tasks. However, their visual understanding behaviors remain underexplored. A fundamental question arises: to what extent do LVLMs rely on visual input, and which image regions contribute to their responses? It is non-trivial to interpret the free-form generation of LVLMs due to their complicated visual architecture (e.g., multiple encoders and multi-resolution) and variable-length outputs. In this paper, we extend existing heatmap visualization methods (e.g., iGOS++) to support LVLMs for open-ended visual question answering. We propose a method to select visually relevant tokens that reflect the relevance between generated answers and input image. Furthermore, we conduct a comprehensive analysis of state-of-the-art LVLMs on benchmarks designed to require visual information to answer. Our findings offer several insights into LVLM behavior, including the relationship between focus region and answer correctness, differences in visual attention across architectures, and the impact of LLM scale on visual understanding. The code and data are available at https://github.com/bytedance/LVLM_Interpretation.

[Arxiv](https://arxiv.org/abs/2503.13891)