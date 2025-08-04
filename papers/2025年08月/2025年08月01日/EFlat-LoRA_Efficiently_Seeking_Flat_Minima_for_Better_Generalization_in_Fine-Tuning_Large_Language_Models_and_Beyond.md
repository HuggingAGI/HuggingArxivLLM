# EFlat-LoRA：高效寻优，提升大语言模型微调的泛化能力及更广泛的场景中的应用

发布时间：2025年08月01日

`LLM理论` `计算机视觉`

> EFlat-LoRA: Efficiently Seeking Flat Minima for Better Generalization in Fine-Tuning Large Language Models and Beyond

# 摘要

> 目前，关于低秩适配（LoRA）的表达能力与泛化能力之间的关系研究较少。锐度感知最小化（SAM）通过引导模型收敛到局部平坦的最小值，有效提升了卷积神经网络（CNN）和Transformer的泛化性能。然而，由于缺乏有效的工具来实证研究平坦最小值或开发相关理论方法，LoRA的锐度与泛化能力之间的联系尚未得到充分探索。针对这一问题，我们提出了Flat-LoRA及其高效版本EFlat-LoRA，旨在为LoRA寻找平坦最小值。从理论上讲，我们证明了全参数空间中的扰动可以被成功转移到低秩子空间中，从而避免了低秩子空间中多个矩阵扰动可能带来的潜在干扰。通过在大型语言模型和视觉语言模型上的大量实验，我们发现EFlat-LoRA不仅保持了与LoRA相当的优化效率，同时在性能上也达到了相当甚至更优的水平。例如，在使用RoBERTa-large的GLUE数据集上，EFlat-LoRA分别比LoRA和完整的微调方法高出1.0%和0.5%的平均性能。在视觉语言模型中，例如Qwen-VL-Chat在SQA和VizWiz数据集上的性能分别提高了1.5%和1.0%。这些实证结果进一步验证了LoRA的泛化能力与锐度密切相关，而这一点在之前的方法中被忽视了。

> Little research explores the correlation between the expressive ability and generalization ability of the low-rank adaptation (LoRA). Sharpness-Aware Minimization (SAM) improves model generalization for both Convolutional Neural Networks (CNNs) and Transformers by encouraging convergence to locally flat minima. However, the connection between sharpness and generalization has not been fully explored for LoRA due to the lack of tools to either empirically seek flat minima or develop theoretical methods. In this work, we propose Flat-LoRA and its efficient version i.e., EFlat-LoRA, to seek flat minima for LoRA. Concretely, we theoretically demonstrate that perturbations in the full parameter space can be transferred to the low-rank subspace. This approach eliminates the potential interference introduced by perturbations across multiple matrices in the low-rank subspace. Our extensive experiments on large language models and vision-language models demonstrate that EFlat-LoRA achieves optimize efficiency comparable to that of LoRA while simultaneously attaining comparable or even better performance. For example, on the GLUE dataset with RoBERTa-large, EFlat-LoRA outperforms LoRA and full fine-tuning by 1.0% and 0.5% on average, respectively. On vision-language models e.g., Qwen-VL-Chat shows performance improvements of 1.5% and 1.0% on SQA and VizWiz datasets, respectively. These empirical results also verify that the generalization of LoRA is closely related to sharpness, which is omitted by previous methods.

[Arxiv](https://arxiv.org/abs/2508.00522)