# # X-SAM：从万物分割到任意分割

发布时间：2025年08月06日

`LLM应用` `计算机视觉` `多模态模型`

> X-SAM: From Segment Anything to Any Segmentation

# 摘要

> 大型语言模型（LLMs）在知识表示方面表现出色，但在像素级感知理解上仍有不足。Segment Anything Model（SAM）虽然在视觉提示驱动的图像分割领域取得突破，但在多掩膜预测和特定类别分割任务中存在局限，且无法在单一模型架构中整合所有分割任务。为此，我们提出X-SAM，一个简洁的多模态大型语言模型（MLLM）框架，将分割范式从	extit{Segment Anything}扩展到	extit{Any Segmentation}。具体来说，我们引入了一种新型统一框架，显著提升了MLLM的像素级感知能力。此外，我们提出了一种新的分割任务——视觉基础（Visual GrounDed，VGD）分割，通过交互式视觉提示实现对所有实例对象的分割，并赋予MLLM视觉基础的像素级解释能力。为了支持跨多数据集的高效训练，我们提出了一种统一的训练策略。实验结果表明，X-SAM在多种图像分割基准测试中表现优异，充分展现了其在多模态、像素级视觉理解方面的强大能力。代码可在https://github.com/wanghao9610/X-SAM获取。

> Large Language Models (LLMs) demonstrate strong capabilities in broad knowledge representation, yet they are inherently deficient in pixel-level perceptual understanding. Although the Segment Anything Model (SAM) represents a significant advancement in visual-prompt-driven image segmentation, it exhibits notable limitations in multi-mask prediction and category-specific segmentation tasks, and it cannot integrate all segmentation tasks within a unified model architecture. To address these limitations, we present X-SAM, a streamlined Multimodal Large Language Model (MLLM) framework that extends the segmentation paradigm from \textit{segment anything} to \textit{any segmentation}. Specifically, we introduce a novel unified framework that enables more advanced pixel-level perceptual comprehension for MLLMs. Furthermore, we propose a new segmentation task, termed Visual GrounDed (VGD) segmentation, which segments all instance objects with interactive visual prompts and empowers MLLMs with visual grounded, pixel-wise interpretative capabilities. To enable effective training on diverse data sources, we present a unified training strategy that supports co-training across multiple datasets. Experimental results demonstrate that X-SAM achieves state-of-the-art performance on a wide range of image segmentation benchmarks, highlighting its efficiency for multimodal, pixel-level visual understanding. Code is available at https://github.com/wanghao9610/X-SAM.

[Arxiv](https://arxiv.org/abs/2508.04655)