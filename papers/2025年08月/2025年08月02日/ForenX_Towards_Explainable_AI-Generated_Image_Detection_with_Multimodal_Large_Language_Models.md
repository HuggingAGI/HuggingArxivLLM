# ForenX：致力于利用多模态大型语言模型实现可解释的AI生成图像检测

发布时间：2025年08月02日

`LLM应用

理由：这篇论文主要探讨了如何利用多模态大型语言模型（MLLMs）来检测AI生成的图像，并提供与人类思维相契合的解释。它展示了LLM在图像真实性检测中的应用，并通过引入专门的取证提示和创建新的数据集ForgeryReason来提升模型性能。因此，这篇论文属于“LLM应用”分类。` `计算机视觉`

> ForenX: Towards Explainable AI-Generated Image Detection with Multimodal Large Language Models

# 摘要

> 生成模型的突破使得AI生成的图像几乎与真实图像难辨真假。尽管已有大量研究利用分类器检测AI生成的图像，但此类方法与人类的认知取证分析之间仍存在差距。我们提出了ForenX，一种不仅能识别图像真实性，还能提供与人类思维相契合的解释的新方法。ForenX采用强大的多模态大型语言模型（MLLMs）来分析和解读取证线索。此外，我们通过引入专门的取证提示（forensic prompt），克服了标准MLLMs在检测伪造图像方面的局限性，从而引导模型关注伪造特征。这种方法不仅提升了伪造检测的泛化能力，还赋予了MLLMs提供准确、相关且全面解释的能力。此外，我们推出了 ForgReason 数据集，专注于AI生成图像中伪造证据的描述。该数据集通过基于LLM的智能体与标注团队的协作整理而成，进一步提升了模型性能。我们发现，即使少量人工标注也能显著提升解释质量。我们在两大基准测试中评估了ForenX的有效性，其可解释性通过全面的主观评估得到了验证。

> Advances in generative models have led to AI-generated images visually indistinguishable from authentic ones. Despite numerous studies on detecting AI-generated images with classifiers, a gap persists between such methods and human cognitive forensic analysis. We present ForenX, a novel method that not only identifies the authenticity of images but also provides explanations that resonate with human thoughts. ForenX employs the powerful multimodal large language models (MLLMs) to analyze and interpret forensic cues. Furthermore, we overcome the limitations of standard MLLMs in detecting forgeries by incorporating a specialized forensic prompt that directs the MLLMs attention to forgery-indicative attributes. This approach not only enhance the generalization of forgery detection but also empowers the MLLMs to provide explanations that are accurate, relevant, and comprehensive. Additionally, we introduce ForgReason, a dataset dedicated to descriptions of forgery evidences in AI-generated images. Curated through collaboration between an LLM-based agent and a team of human annotators, this process provides refined data that further enhances our model's performance. We demonstrate that even limited manual annotations significantly improve explanation quality. We evaluate the effectiveness of ForenX on two major benchmarks. The model's explainability is verified by comprehensive subjective evaluations.

[Arxiv](https://arxiv.org/abs/2508.01402)