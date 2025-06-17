# 评估视觉语言模型在不同视觉上下文中的细胞类型推断能力

发布时间：2025年06月14日

`其他

理由：这篇论文主要研究视觉语言模型（VLMs）在组织病理学图像分类中的应用，虽然提到了LLMs，但重点在于视觉任务，并不直接属于LLM的应用或理论。因此，归类为“其他”。` `图像分类`

> Evaluating Cell Type Inference in Vision Language Models Under Varying Visual Context

# 摘要

> 视觉语言模型（VLMs）与大型语言模型（LLMs）齐头并进，取得了迅速发展。本研究评估了通过API访问的著名生成式VLM（如GPT-4.1和Gemini 2.5 Pro）在组织病理学图像分类任务中的能力，包括细胞分类。我们使用来自公共和私人来源的多样化数据集，应用零样本和一样本提示方法评估VLM的性能，并与定制训练的卷积神经网络（CNNs）进行比较。我们的研究结果表明，虽然一样本提示在零样本基础上显著提高了VLM的性能（【数学公式】基于Kappa分数，p≈1.005×10^-5），但这些通用型VLM在大多数任务上目前仍逊色于监督学习的CNN。这项工作强调了通过上下文学习将当前VLM应用于病理学等专业领域的潜力与局限性。所有用于重现本研究的代码和说明均可在仓库https://www.github.com/a12dongithub/VLMCCE中获取。

> Vision-Language Models (VLMs) have rapidly advanced alongside Large Language Models (LLMs). This study evaluates the capabilities of prominent generative VLMs, such as GPT-4.1 and Gemini 2.5 Pro, accessed via APIs, for histopathology image classification tasks, including cell typing. Using diverse datasets from public and private sources, we apply zero-shot and one-shot prompting methods to assess VLM performance, comparing them against custom-trained Convolutional Neural Networks (CNNs). Our findings demonstrate that while one-shot prompting significantly improves VLM performance over zero-shot ($p \approx 1.005 \times 10^{-5}$ based on Kappa scores), these general-purpose VLMs currently underperform supervised CNNs on most tasks. This work underscores both the promise and limitations of applying current VLMs to specialized domains like pathology via in-context learning. All code and instructions for reproducing the study can be accessed from the repository https://www.github.com/a12dongithub/VLMCCE.

[Arxiv](https://arxiv.org/abs/2506.12683)