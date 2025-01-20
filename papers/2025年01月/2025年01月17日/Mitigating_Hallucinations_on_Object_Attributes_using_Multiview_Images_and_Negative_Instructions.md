# 利用多视角图像与负面指令缓解对象属性幻觉

发布时间：2025年01月17日

`LLM应用

**理由**：这篇论文主要讨论了如何通过多视角图像增强视觉语言模型（MIAVLM）来缓解大型视觉语言模型（LVLMs）中的对象属性幻觉问题。虽然涉及到了视觉语言模型和大型语言模型（LLMs），但其核心是应用这些模型来解决具体问题（即对象属性幻觉），因此应归类为LLM应用。` `计算机视觉` `3D建模`

> Mitigating Hallucinations on Object Attributes using Multiview Images and Negative Instructions

# 摘要

> 当前主流的大型视觉语言模型（LVLMs）饱受对象属性幻觉（HoOA）的困扰，导致对图像中细粒度属性的误判。本文基于单图生成3D模型的重大进展，提出了一种新方法，通过从生成的3D表示中采样的多视角图像作为视觉提示，为LVLMs提供更多视角的视觉信息，从而缓解HoOA。我们还发现，多视角图像的输入顺序对LVLMs的性能有显著影响。为此，我们设计了多视角图像增强视觉语言模型（MIAVLM），并引入多视角属性感知器（MAP）子模块，既能消除输入顺序的影响，又能将多视角图像的视觉信息与大型语言模型（LLMs）对齐。此外，我们设计了负面指令，以减少LVLMs对“是”回答的倾向。实验结果表明，我们的方法效果显著。

> Current popular Large Vision-Language Models (LVLMs) are suffering from Hallucinations on Object Attributes (HoOA), leading to incorrect determination of fine-grained attributes in the input images. Leveraging significant advancements in 3D generation from a single image, this paper proposes a novel method to mitigate HoOA in LVLMs. This method utilizes multiview images sampled from generated 3D representations as visual prompts for LVLMs, thereby providing more visual information from other viewpoints. Furthermore, we observe the input order of multiple multiview images significantly affects the performance of LVLMs. Consequently, we have devised Multiview Image Augmented VLM (MIAVLM), incorporating a Multiview Attributes Perceiver (MAP) submodule capable of simultaneously eliminating the influence of input image order and aligning visual information from multiview images with Large Language Models (LLMs). Besides, we designed and employed negative instructions to mitigate LVLMs' bias towards ``Yes" responses. Comprehensive experiments demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2501.10011)