# 先观察，再推理：MLLMs中的细粒度视觉数学理解

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在数学问题解决任务中的表现，并提出了一种新的方法（SVE-Math）来改进这些模型的视觉理解能力。论文的核心在于如何通过改进视觉编码器和特征路由器来增强MLLMs的视觉基础能力，从而提高其在数学问题解决任务中的表现。这属于LLM在实际应用中的改进和优化，因此归类为“LLM应用”。` `计算机视觉`

> Open Eyes, Then Reason: Fine-grained Visual Mathematical Understanding in MLLMs

# 摘要

> # 摘要
当前的多模态大型语言模型（MLLMs）在需要细粒度视觉理解的数学问题解决任务上表现欠佳，主要原因是图像级对比预训练（如CLIP）中对几何基元的感知不足。尽管近期改进数学MLLMs的努力集中在扩大数学视觉指令数据集和采用更强的LLM骨干上，但视觉识别中的持续错误常被忽视。本文系统评估了最先进MLLMs的视觉基础能力，发现视觉基础准确性与问题解决性能之间存在显著负相关，凸显了细粒度视觉理解的关键作用。值得注意的是，像GPT-4o这样的先进模型在识别几何实体时错误率高达70%，表明这仍是视觉数学推理的关键瓶颈。为此，我们提出了一种新方法——SVE-Math（选择性视觉增强数学MLLM），其特点是几何基础的视觉编码器和动态调整分层视觉特征图贡献的特征路由器。该模型能识别准确的视觉基元，并生成适合语言模型推理需求的精确视觉提示。实验表明，SVE-Math-Qwen2.5-7B在MathVerse上比其他7B模型高出15%，并在MathVista上与GPT-4V兼容。尽管在较小数据集上训练，SVE-Math-7B在GeoQA上表现优异，与在更大数据集上训练的模型不相上下。我们的研究强调了将细粒度视觉理解纳入MLLMs的重要性，为未来研究指明了方向。

> Current multimodal large language models (MLLMs) often underperform on mathematical problem-solving tasks that require fine-grained visual understanding. The limitation is largely attributable to inadequate perception of geometric primitives during image-level contrastive pre-training (e.g., CLIP). While recent efforts to improve math MLLMs have focused on scaling up mathematical visual instruction datasets and employing stronger LLM backbones, they often overlook persistent errors in visual recognition. In this paper, we systematically evaluate the visual grounding capabilities of state-of-the-art MLLMs and reveal a significant negative correlation between visual grounding accuracy and problem-solving performance, underscoring the critical role of fine-grained visual understanding. Notably, advanced models like GPT-4o exhibit a 70% error rate when identifying geometric entities, highlighting that this remains a key bottleneck in visual mathematical reasoning. To address this, we propose a novel approach, SVE-Math (Selective Vision-Enhanced Mathematical MLLM), featuring a geometric-grounded vision encoder and a feature router that dynamically adjusts the contribution of hierarchical visual feature maps. Our model recognizes accurate visual primitives and generates precise visual prompts tailored to the language model's reasoning needs. In experiments, SVE-Math-Qwen2.5-7B outperforms other 7B models by 15% on MathVerse and is compatible with GPT-4V on MathVista. Despite being trained on smaller datasets, SVE-Math-7B achieves competitive performance on GeoQA, rivaling models trained on significantly larger datasets. Our findings emphasize the importance of incorporating fine-grained visual understanding into MLLMs and provide a promising direction for future research.

[Arxiv](https://arxiv.org/abs/2501.06430)