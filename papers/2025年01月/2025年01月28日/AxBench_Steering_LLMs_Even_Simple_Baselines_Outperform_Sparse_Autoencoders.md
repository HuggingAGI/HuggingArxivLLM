# AxBench: 引导LLMs？简单基线模型竟优于稀疏自编码器

发布时间：2025年01月28日

`LLM理论

理由：这篇论文主要讨论了语言模型输出的精细控制方法，包括提示、微调和基于表示的技术，并提出了一个新的基准AxBench来比较这些方法。论文还提出了一种新的弱监督表示方法（ReFT-r1），并对其进行了实验验证。这些内容主要涉及语言模型的理论和方法改进，因此归类为LLM理论。` `机器学习`

> AxBench: Steering LLMs? Even Simple Baselines Outperform Sparse Autoencoders

# 摘要

> # 摘要
语言模型输出的精细控制对安全性和可靠性至关重要。提示和微调是常用的方法，但研究人员也提出了多种基于表示的技术，如稀疏自编码器（SAEs）、线性人工断层扫描、监督控制向量、线性探测和表示微调。目前，这些方法之间缺乏直接比较的基准。为此，我们推出了AxBench，一个用于控制和概念检测的大规模基准，并在Gemma-2-2B和9B上进行了实验。结果显示，提示在控制任务中表现最佳，微调次之；而在概念检测中，基于表示的方法（如均值差异）表现最优。SAEs在这两项任务中均不占优势。我们提出了一种新的弱监督表示方法（Rank-1表示微调；ReFT-r1），它在两项任务中均表现出色，同时弥补了提示方法在可解释性上的不足。此外，我们还训练并公开了ReFT-r1和DiffMean的SAE规模特征字典。

> Fine-grained steering of language model outputs is essential for safety and reliability. Prompting and finetuning are widely used to achieve these goals, but interpretability researchers have proposed a variety of representation-based techniques as well, including sparse autoencoders (SAEs), linear artificial tomography, supervised steering vectors, linear probes, and representation finetuning. At present, there is no benchmark for making direct comparisons between these proposals. Therefore, we introduce AxBench, a large-scale benchmark for steering and concept detection, and report experiments on Gemma-2-2B and 9B. For steering, we find that prompting outperforms all existing methods, followed by finetuning. For concept detection, representation-based methods such as difference-in-means, perform the best. On both evaluations, SAEs are not competitive. We introduce a novel weakly-supervised representational method (Rank-1 Representation Finetuning; ReFT-r1), which is competitive on both tasks while providing the interpretability advantages that prompting lacks. Along with AxBench, we train and publicly release SAE-scale feature dictionaries for ReFT-r1 and DiffMean.

[Arxiv](https://arxiv.org/abs/2501.17148)