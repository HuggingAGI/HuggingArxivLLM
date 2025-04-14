# # POEM: 基于多语言大语言模型控制的精准对象级别编辑

发布时间：2025年04月10日

`LLM应用` `图像处理` `计算机视觉`

> POEM: Precise Object-level Editing via MLLM control

# 摘要

> 扩散模型在文本到图像生成方面取得了显著进展，能够从文本描述生成高质量且逼真的图像。然而，基于对象的图像编辑仍然是一个具有挑战性的问题，需要在保持视觉连贯性的同时进行精确修改。现有的基于文本的指令编辑方法在处理局部形状和布局变换时常常导致意外的全局变化，而基于图像交互的方法虽然能提供更高的精度，但需要手动提供精确的指导，增加了人工干预。为了在保持高精度图像编辑的同时减少人工努力，本文提出了一种名为POEM的框架，用于利用多模态大型语言模型（MLLMs）进行精准的对象级编辑。POEM通过MLLMs分析指令提示，并在变换前后生成精确的对象掩膜，从而实现精细控制，而无需大量用户输入。这一结构化的推理阶段指导了基于扩散模型的编辑过程，确保了对象的精准定位和变换。为了评估我们的方法，我们引入了VOCEdits基准数据集，该数据集基于PASCAL VOC 2012，增加了指令编辑提示、真实变换和精确对象掩膜。实验结果表明，POEM在精度和可靠性方面优于现有基于文本的图像编辑方法，同时相较于交互式方法减少了人工努力。

> Diffusion models have significantly improved text-to-image generation, producing high-quality, realistic images from textual descriptions. Beyond generation, object-level image editing remains a challenging problem, requiring precise modifications while preserving visual coherence. Existing text-based instructional editing methods struggle with localized shape and layout transformations, often introducing unintended global changes. Image interaction-based approaches offer better accuracy but require manual human effort to provide precise guidance. To reduce this manual effort while maintaining a high image editing accuracy, in this paper, we propose POEM, a framework for Precise Object-level Editing using Multimodal Large Language Models (MLLMs). POEM leverages MLLMs to analyze instructional prompts and generate precise object masks before and after transformation, enabling fine-grained control without extensive user input. This structured reasoning stage guides the diffusion-based editing process, ensuring accurate object localization and transformation. To evaluate our approach, we introduce VOCEdits, a benchmark dataset based on PASCAL VOC 2012, augmented with instructional edit prompts, ground-truth transformations, and precise object masks. Experimental results show that POEM outperforms existing text-based image editing approaches in precision and reliability while reducing manual effort compared to interaction-based methods.

[Arxiv](https://arxiv.org/abs/2504.08111)