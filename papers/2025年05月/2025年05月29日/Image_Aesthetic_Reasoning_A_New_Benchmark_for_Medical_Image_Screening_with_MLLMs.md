# 图像美学推理：基于多语言大模型的医学图像筛查新基准

发布时间：2025年05月29日

`LLM应用` `医学图像` `多模态模型`

> Image Aesthetic Reasoning: A New Benchmark for Medical Image Screening with MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在多模态理解和生成等领域具有广泛应用。尽管扩散模型（DM）和统一多模态模型的发展显著提升了图像生成性能，但图像筛选研究却寥寥无几，且多模态模型在这一领域表现欠佳，主要源于数据不足及美学推理能力较弱。针对这些问题，本研究从数据和方法两方面提出完整解决方案。

在数据方面，我们构建了一个包含1500多个样本的医学图像筛选数据集，每个样本包含医学图像、四张生成图像和一个多项选择答案。该数据集从以下四个方面评估美学推理能力：	extit{(1) 外观变形，(2) 物理光影原则，(3) 布局摆放，(4) 扩展合理性}。

在方法方面，我们采用长链思维（CoT）和动态比例准确性奖励的组相对策略优化（DPA-GRPO），显著提升了多模态模型的图像美学推理能力。实验结果表明，即使是GPT-4o和Qwen-VL-Max等顶尖闭源模型，在美学推理上也表现平平。而通过强化学习方法，我们仅用较小规模的模型便超越了现有模型的性能。

我们相信，医学图像筛选的研究成果未来将成为图像美学推理的重要参考。

> Multimodal Large Language Models (MLLMs) are of great application across many domains, such as multimodal understanding and generation. With the development of diffusion models (DM) and unified MLLMs, the performance of image generation has been significantly improved, however, the study of image screening is rare and its performance with MLLMs is unsatisfactory due to the lack of data and the week image aesthetic reasoning ability in MLLMs. In this work, we propose a complete solution to address these problems in terms of data and methodology. For data, we collect a comprehensive medical image screening dataset with 1500+ samples, each sample consists of a medical image, four generated images, and a multiple-choice answer. The dataset evaluates the aesthetic reasoning ability under four aspects: \textit{(1) Appearance Deformation, (2) Principles of Physical Lighting and Shadow, (3) Placement Layout, (4) Extension Rationality}. For methodology, we utilize long chains of thought (CoT) and Group Relative Policy Optimization with Dynamic Proportional Accuracy reward, called DPA-GRPO, to enhance the image aesthetic reasoning ability of MLLMs. Our experimental results reveal that even state-of-the-art closed-source MLLMs, such as GPT-4o and Qwen-VL-Max, exhibit performance akin to random guessing in image aesthetic reasoning. In contrast, by leveraging the reinforcement learning approach, we are able to surpass the score of both large-scale models and leading closed-source models using a much smaller model. We hope our attempt on medical image screening will serve as a regular configuration in image aesthetic reasoning in the future.

[Arxiv](https://arxiv.org/abs/2505.23265)