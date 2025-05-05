# # ICQuant：通过索引编码实现低比特 LLM 量化

发布时间：2025年05月01日

`LLM应用` `计算机科学` `模型压缩`

> ICQuant: Index Coding enables Low-bit LLM Quantization

# 摘要

> 大型语言模型（LLMs）的快速部署凸显了高效低比特后训练量化（PTQ）的必要性，因其内存成本高昂。在权重量化中，异常值的存在是一个关键挑战，它们会扩大量化范围并导致较大的误差。尽管提出了多种抑制异常值的技术，但它们要么无法有效缩小量化范围，要么会带来较高的比特开销。本文中，我们提出了一种名为ICQuant的新颖框架，该框架利用异常值统计信息设计了一种高效的索引编码方案，用于异常值感知的仅权重量化。与现有需要【数学公式】比特开销才能将量化范围减半的抑制异常值技术相比，ICQuant仅需【数学公式】比特；在极端压缩场景（例如每权重2-3比特）下，这是一项重大节省。ICQuant可以在任何现有量化器之上使用，以消除异常值，从而提升量化质量。仅使用每权重2.3比特和简单的标量量化器，ICQuant将2比特Llama3-70B模型的零-shot准确率相对于QTIP和QuIP#提高了高达130%和150%；并且在无需微调的情况下，其性能与最佳已知微调量化器（PV-tuning）相当。

> The rapid deployment of Large Language Models (LLMs) highlights the need for efficient low-bit post-training quantization (PTQ), due to their high memory costs. A key challenge in weight quantization is the presence of outliers, which inflate quantization ranges and lead to large errors. While a number of outlier suppression techniques have been proposed, they either: fail to effectively shrink the quantization range, or incur (relatively) high bit overhead. In this paper, we present ICQuant, a novel framework that leverages outlier statistics to design an efficient index coding scheme for outlier-aware weight-only quantization. Compared to existing outlier suppression techniques requiring $\approx 1$ bit overhead to halve the quantization range, ICQuant requires only $\approx 0.3$ bits; a significant saving in extreme compression regimes (e.g., 2-3 bits per weight). ICQuant can be used on top of any existing quantizers to eliminate outliers, improving the quantization quality. Using just 2.3 bits per weight and simple scalar quantizers, ICQuant improves the zero-shot accuracy of the 2-bit Llama3-70B model by up to 130% and 150% relative to QTIP and QuIP#; and it achieves comparable performance to the best-known fine-tuned quantizer (PV-tuning) without fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.00850)