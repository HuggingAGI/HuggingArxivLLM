# # VGR：基于视觉的推理

发布时间：2025年06月13日

`LLM应用` `多模态` `计算机视觉`

> VGR: Visual Grounded Reasoning

# 摘要

> 在多模态链式推理（CoT）领域，现有方法主要依赖纯语言空间推理，存在语言偏见且局限于数学或科学领域。这种局限性限制了它们处理复杂视觉推理任务的能力。为了解决这一问题，本文提出了一种名为VGR的新型多模态大型语言模型（MLLM），它具有增强的细粒度视觉感知能力。与传统MLLM仅在语言空间进行推理不同，VGR首先检测可能有助于解决问题的相关区域，然后基于重放的图像区域提供精确答案。为此，我们构建了一个大规模SFT数据集VGR-SFT，包含混合视觉接地和语言推理的推理数据。VGR的推理管道允许模型选择用于视觉参考的边界框，并引入重放阶段将相关区域整合到推理过程中，从而增强了多模态理解。在LLaVA-NeXT-7B基线上进行的实验表明，VGR在需要全面理解图像细节的多模态基准测试中表现出色。与基线相比，VGR仅使用30%的图像令牌数量，同时在MMStar上提升了4.1分，在AI2D上提升了7.1分，在ChartQA上的改进达到了12.9分。

> In the field of multimodal chain-of-thought (CoT) reasoning, existing approaches predominantly rely on reasoning on pure language space, which inherently suffers from language bias and is largely confined to math or science domains. This narrow focus limits their ability to handle complex visual reasoning tasks that demand comprehensive understanding of image details. To address these limitations, this paper introduces VGR, a novel reasoning multimodal large language model (MLLM) with enhanced fine-grained visual perception capabilities. Unlike traditional MLLMs that answer the question or reasoning solely on the language space, our VGR first detects relevant regions that may help to solve problems, and then provides precise answers based on replayed image regions. To achieve this, we conduct a large-scale SFT dataset called VGR -SFT that contains reasoning data with mixed vision grounding and language deduction. The inference pipeline of VGR allows the model to choose bounding boxes for visual reference and a replay stage is introduced to integrates the corresponding regions into the reasoning process, enhancing multimodel comprehension. Experiments on the LLaVA-NeXT-7B baseline show that VGR achieves superior performance on multi-modal benchmarks requiring comprehensive image detail understanding. Compared to the baseline, VGR uses only 30\% of the image token count while delivering scores of +4.1 on MMStar, +7.1 on AI2D, and a +12.9 improvement on ChartQA.

[Arxiv](https://arxiv.org/abs/2506.11991)