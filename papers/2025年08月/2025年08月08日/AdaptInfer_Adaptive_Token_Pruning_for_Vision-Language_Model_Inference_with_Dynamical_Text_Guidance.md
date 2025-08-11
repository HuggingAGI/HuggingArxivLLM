# AdaptInfer: 带动态文本引导的视觉语言模型自适应剪枝推理方法

发布时间：2025年08月08日

`LLM应用` `计算机视觉`

> AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance

# 摘要

> 视觉语言模型（VLMs）在视觉问答（VQA）等多模态推理任务中表现卓越，但其推理成本因预填阶段处理的大量视觉标记而居高不下。现有剪枝方法多依赖静态文本提示或注意力模式，未能有效利用推理过程中的动态信号。为此，我们提出了一种即插即用的自适应视觉标记剪枝框架——AdaptInfer。该框架通过细粒度的动态文本引导机制，利用层间文本注意力图构建软先验，实现对视觉标记的智能评分。同时，我们通过对跨模态注意力转移的分析，识别出推理过程中的稳定拐点，从而设计出更高效合理的剪枝策略。AdaptInfer不仅轻量灵活，还在多模态任务中表现出色。实验表明，该方法在保持LLaVA-1.5-7B模型92.9%准确率的同时，将CUDA延迟降低了61.3%。在相同标记预算下，AdaptInfer的准确率超越了现有最优方法（SOTA）。

> Vision-language models (VLMs) have achieved impressive performance on multimodal reasoning tasks such as visual question answering (VQA), but their inference cost remains a significant challenge due to the large number of vision tokens processed during the prefill stage. Existing pruning methods often rely on directly using the attention patterns or static text prompt guidance, failing to exploit the dynamic internal signals generated during inference. To address these issues, we propose AdaptInfer, a plug-and-play framework for adaptive vision token pruning in VLMs. First, we introduce a fine-grained, dynamic text-guided pruning mechanism that reuses layer-wise text-to-text attention maps to construct soft priors over text-token importance, allowing more informed scoring of vision tokens at each stage. Second, we perform an offline analysis of cross-modal attention shifts and identify consistent inflection locations in inference, which inspire us to propose a more principled and efficient pruning schedule. Our method is lightweight and plug-and-play, also generalizable across multi-modal tasks. Experimental results have verified the effectiveness of the proposed method. For example, it reduces CUDA latency by 61.3\% while maintaining an average accuracy of 92.9\% on vanilla LLaVA-1.5-7B. Under the same token budget, AdaptInfer surpasses SOTA in accuracy.

[Arxiv](https://arxiv.org/abs/2508.06084)