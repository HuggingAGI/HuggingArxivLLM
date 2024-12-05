# AdvDreamer 发问：视觉语言模型真的能应对现实世界中的 3D 变化吗？

发布时间：2024年12月03日

`LLM应用` `计算机视觉`

> AdvDreamer Unveils: Are Vision-Language Models Truly Ready for Real-World 3D Variations?

# 摘要

> 视觉语言模型（VLMs）展现出了出色的泛化能力，但其在动态的现实场景中的鲁棒性却大多未被探究。为系统评估 VLM 对现实世界 3D 变化的鲁棒性，我们提出了 AdvDreamer，这是首个能从单视图图像生成物理可重现的对抗性 3D 变换（Adv-3DT）样本的框架。AdvDreamer 融合了先进的生成技术与两项关键创新，旨在刻画自然图像中 3D 变化的最坏情况分布。为确保对抗效果和方法的通用性，我们引入了逆语义概率目标，在基本的视觉 - 文本对齐空间进行对抗优化，能在不同的 VLM 架构和下游任务中通用。为减小生成样本与现实样本的分布差异，同时保持物理可重现性，我们设计了自然度奖励模型，在对抗优化时提供正则化反馈，避免收敛到幻觉和不自然的元素。借助 AdvDreamer，我们创建了 MM3DTBench，这是首个用于衡量 VLM 对 3D 变化鲁棒性的 VQA 数据集。对不同架构的代表性 VLM 进行的大量评估表明，现实世界中的 3D 变化可能对各类任务中的模型性能造成严重威胁。

> Vision Language Models (VLMs) have exhibited remarkable generalization capabilities, yet their robustness in dynamic real-world scenarios remains largely unexplored. To systematically evaluate VLMs' robustness to real-world 3D variations, we propose AdvDreamer, the first framework that generates physically reproducible adversarial 3D transformation (Adv-3DT) samples from single-view images. AdvDreamer integrates advanced generative techniques with two key innovations and aims to characterize the worst-case distributions of 3D variations from natural images. To ensure adversarial effectiveness and method generality, we introduce an Inverse Semantic Probability Objective that executes adversarial optimization on fundamental vision-text alignment spaces, which can be generalizable across different VLM architectures and downstream tasks. To mitigate the distribution discrepancy between generated and real-world samples while maintaining physical reproducibility, we design a Naturalness Reward Model that provides regularization feedback during adversarial optimization, preventing convergence towards hallucinated and unnatural elements. Leveraging AdvDreamer, we establish MM3DTBench, the first VQA dataset for benchmarking VLMs' 3D variations robustness. Extensive evaluations on representative VLMs with diverse architectures highlight that 3D variations in the real world may pose severe threats to model performance across various tasks.

[Arxiv](https://arxiv.org/abs/2412.03002)