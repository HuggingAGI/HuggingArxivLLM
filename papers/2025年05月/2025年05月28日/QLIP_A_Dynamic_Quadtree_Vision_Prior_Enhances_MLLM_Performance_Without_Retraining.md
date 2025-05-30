# QLIP：动态四叉树视觉先验，助力MLLM性能提升，无需重新训练

发布时间：2025年05月28日

`LLM应用` `多模态` `视觉内容`

> QLIP: A Dynamic Quadtree Vision Prior Enhances MLLM Performance Without Retraining

# 摘要

> 多模态大型语言模型（MLLMs）通过将图像编码为视觉标记，并在一个共享的潜在空间中对齐视觉与文本信号，实现了跨模态表征学习。CLIP 模型作为广泛使用的视觉语言基础模型，其视觉编码器在 LLaVA 等 MLLMs 的发展中起到了关键作用。然而，CLIP 视觉编码器存在两大局限：仅支持固定分辨率输入，且无法为不相似图像生成独立嵌入。替换现有模型的视觉编码器通常会带来高昂的计算成本，因为这通常需要重新训练整个模型。

在本研究中，我们发现 CLIP 视觉编码器局限性的两大根源：中观偏见和插值偏见。为此，我们提出了 QLIP，这一解决方案可直接替代 CLIP，仅需少量代码即可无缝集成到现有 MLLMs 中，且无需重新训练即可提升对视觉内容的粗粒度和细粒度理解。QLIP 以图像四叉树为核心，采用创新的内容感知分块方法取代标准均匀网格分块。实验结果表明，QLIP 在 LLaVA v1.5 模型系列的通用视觉问答任务中显著提升了准确性，且这一改进适用于不同规模的模型，无需对整个 MLLM 进行重新训练或微调。特别地，QLIP 在具有挑战性的 $V^{st}$ 基准测试中，将详细理解性能提升了高达 13.6%。

> Multimodal Large Language Models (MLLMs) encode images into visual tokens, aligning visual and textual signals within a shared latent space to facilitate crossmodal representation learning. The CLIP model is a widely adopted foundational vision language model whose vision encoder has played a critical role in the development of MLLMs such as LLaVA. However, the CLIP vision encoder suffers from notable limitations including being constrained to only handling fixed input resolutions and a failure to produce separated embeddings for dissimilar images. Replacing the vision encoder of an existing model typically incurs substantial computational costs because such a change often necessitates retraining the entire model pipeline.
  In this work, we identify two factors which underlie the limitations of the CLIP vision encoder: mesoscopic bias and interpolation bias. To address these issues, we propose QLIP, a drop-in replacement for CLIP that can be seamlessly integrated with existing MLLMs with only a few lines of code and can enhance both coarse-grained and fine-grained visual understanding, without re-training. QLIP is designed around an image quadtree which replaces the standard uniform grid patches with a novel content aware patchification. Our experimental results demonstrate that QLIP improves the general visual question answering accuracy of the LLaVA v1.5 model series across various model sizes--without requiring retraining or fine-tuning of the full MLLM. Notably, QLIP boosts detailed understanding performance on the challenging $V^{\ast}$ benchmark by up to 13.6 percent.

[Arxiv](https://arxiv.org/abs/2505.23004)