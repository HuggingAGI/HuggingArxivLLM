# 多模态大型语言模型实现医疗报告生成的定制提示微调

发布时间：2025年06月18日

`LLM应用` `医学影像` `医学报告生成`

> Multimodal Large Language Models for Medical Report Generation via Customized Prompt Tuning

# 摘要

> 从影像数据生成医学报告仍是临床实践中的难题。尽管大型语言模型（LLMs）在解决这一问题上展现出巨大潜力，但如何有效整合医学影像数据仍值得深入探索。本文提出了一种名为MRG-LLM的新型多模态大型语言模型（MLLM），它结合了冻结的LLM和可学习的视觉编码器，并引入了动态提示定制机制。我们的创新在于通过基于视觉特征的条件仿射变换，为每个医学图像生成定制的实例提示。我们提出了两种实现方式：基于提示和基于提示集的定制，从而实现精准且有针对性的报告生成。在IU X光和MIMIC-CXR数据集上的广泛实验表明，MRG-LLM在医学报告生成方面达到了目前最先进的性能。我们的代码将公开发布。

> Medical report generation from imaging data remains a challenging task in clinical practice. While large language models (LLMs) show great promise in addressing this challenge, their effective integration with medical imaging data still deserves in-depth exploration. In this paper, we present MRG-LLM, a novel multimodal large language model (MLLM) that combines a frozen LLM with a learnable visual encoder and introduces a dynamic prompt customization mechanism. Our key innovation lies in generating instance-specific prompts tailored to individual medical images through conditional affine transformations derived from visual features. We propose two implementations: prompt-wise and promptbook-wise customization, enabling precise and targeted report generation. Extensive experiments on IU X-ray and MIMIC-CXR datasets demonstrate that MRG-LLM achieves state-of-the-art performance in medical report generation. Our code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2506.15477)