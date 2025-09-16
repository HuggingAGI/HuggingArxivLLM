# Spec-LLaVA：基于动态树的投机解码加速视觉语言模型

发布时间：2025年09月15日

`LLM应用` `基础理论`

> Spec-LLaVA: Accelerating Vision-Language Models with Dynamic Tree-Based Speculative Decoding

# 摘要

> 视觉语言模型（VLMs）拥有强大的多模态推理能力，但自回归推理速度偏慢，限制了其在实时应用中的部署。为此，我们提出Spec-LLaVA——一个采用推测解码技术加速VLMs、且不损失输出质量的系统。该系统将轻量级草稿VLM与大型目标模型相结合：草稿模型负责推测后续token，目标模型则并行验证这些token，从而实现每步生成多个token。为提升效率，我们设计了动态树结构验证算法，借助草稿模型的置信度自适应扩展和修剪推测分支。在MS COCO的域外图像测试中，Spec-LLaVA在LLaVA-1.5（7B、13B）上解码速度提升高达【数学公式】倍，同时保持生成质量不下降。本研究提出了一种基于动态树结构推测解码的VLMs无损加速框架，为构建实用的实时多模态助手奠定了基础。值得注意的是，轻量级草稿模型的设计让该框架能适配资源受限或设备端部署场景。

> Vision-Language Models (VLMs) enable powerful multimodal reasoning but suffer from slow autoregressive inference, limiting their deployment in real-time applications. We introduce Spec-LLaVA, a system that applies speculative decoding to accelerate VLMs without sacrificing output quality. Spec-LLaVA pairs a lightweight draft VLM with a large target model: the draft speculates future tokens, which the target verifies in parallel, allowing multiple tokens to be generated per step. To maximize efficiency, we design a dynamic tree-based verification algorithm that adaptively expands and prunes speculative branches using draft model confidence. On MS COCO out-of-domain images, Spec-LLaVA achieves up to 3.28$\times$ faster decoding on LLaVA-1.5 (7B, 13B) with no loss in generation quality. This work presents a lossless acceleration framework for VLMs using dynamic tree-structured speculative decoding, opening a path toward practical real-time multimodal assistants. Importantly, the lightweight draft model design makes the framework amenable to resource-constrained or on-device deployment settings.

[Arxiv](https://arxiv.org/abs/2509.11961)