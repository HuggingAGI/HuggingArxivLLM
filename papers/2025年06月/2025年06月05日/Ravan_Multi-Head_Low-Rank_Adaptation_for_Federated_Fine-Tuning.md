# 联邦微调中的多头低秩自适应方法：Ravan

发布时间：2025年06月05日

`LLM应用

摘要中讨论了如何在边缘设备上使用联邦学习来微调大型语言模型（LLMs），并提出了一种名为Ravan的方法来优化这一过程。这属于LLM的实际应用场景，因此归类为LLM应用。` `联邦学习` `边缘计算`

> Ravan: Multi-Head Low-Rank Adaptation for Federated Fine-Tuning

# 摘要

> 大型语言模型尚未有效利用边缘设备数据，而联邦学习提供了一种无需上传私有数据即可协作微调LLMs的解决方案。为适应边缘设备的计算和通信限制，研究者提出了低秩适配（LoRA）等参数高效方法。然而，LoRA在联邦学习中因客户端异质性导致准确性下降。我们提出了	extsc{Ravan}，一种自适应多头LoRA方法，通过重新参数化权重更新为多个头的和，其中仅训练核心矩阵及其缩放因子，从而平衡参数效率与模型表达能力。这些缩放因子使优化专注于关键头，恢复高秩更新近似，且不增加通信参数。实验表明，	extsc{Ravan}在视觉和语言任务中将测试准确率提升2-8%，成为联邦微调LLMs的高效方案。

> Large language models (LLMs) have not yet effectively leveraged the vast amounts of edge-device data, and federated learning (FL) offers a promising paradigm to collaboratively fine-tune LLMs without transferring private edge data to the cloud. To operate within the computation and communication constraints of edge devices, recent literature on federated fine-tuning of LLMs proposes the use of low-rank adaptation (LoRA) and similar parameter-efficient methods. However, LoRA-based methods suffer from accuracy degradation in FL settings, primarily because of data and computational heterogeneity across clients. We propose \textsc{Ravan}, an adaptive multi-head LoRA method that balances parameter efficiency and model expressivity by reparameterizing the weight updates as the sum of multiple LoRA heads $s_i\textbf{B}_i\textbf{H}_i\textbf{A}_i$ in which only the core matrices $\textbf{H}_i$ and their lightweight scaling factors $s_i$ are trained. These trainable scaling factors let the optimization focus on the most useful heads, recovering a higher-rank approximation of the full update without increasing the number of communicated parameters since clients upload $s_i\textbf{H}_i$ directly. Experiments on vision and language benchmarks show that \textsc{Ravan} improves test accuracy by 2-8\% over prior parameter-efficient baselines, making it a robust and scalable solution for federated fine-tuning of LLMs.

[Arxiv](https://arxiv.org/abs/2506.05568)