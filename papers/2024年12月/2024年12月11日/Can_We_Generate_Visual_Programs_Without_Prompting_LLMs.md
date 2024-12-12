# 我们能够在不提示 LLMs 的情况下生成可视化程序吗？

发布时间：2024年12月11日

`LLM应用` `视觉编程` `视觉任务`

> Can We Generate Visual Programs Without Prompting LLMs?

# 摘要

> 视觉编程能促使 LLM（大型语言模型）为诸如视觉问答（VQA）这样的视觉任务生成可执行代码。基于提示的方法不仅难以改进，而且在时间和金钱方面都不可靠且成本高。我们的目标是开发一个高效的视觉编程系统，要做到 1）在推理时不使用基于提示的 LLM  2）不需要大量的程序和答案注释。我们开发了一种合成数据增强方法和基于将程序解耦为称为模板的更高级技能及相应参数的替代程序生成方法。我们的结果显示，借助数据增强，无提示的较小 LLM（$pprox$ 1B 参数）能与最先进的模型相媲美，而且还有推理速度大幅提升的优势。

> Visual programming prompts LLMs (large language mod-els) to generate executable code for visual tasks like visual question answering (VQA). Prompt-based methods are difficult to improve while also being unreliable and costly in both time and money. Our goal is to develop an efficient visual programming system without 1) using prompt-based LLMs at inference time and 2) a large set of program and answer annotations. We develop a synthetic data augmentation approach and alternative program generation method based on decoupling programs into higher-level skills called templates and the corresponding arguments. Our results show that with data augmentation, prompt-free smaller LLMs ($\approx$ 1B parameters) are competitive with state-of-the art models with the added benefit of much faster inference

[Arxiv](https://arxiv.org/abs/2412.08564)