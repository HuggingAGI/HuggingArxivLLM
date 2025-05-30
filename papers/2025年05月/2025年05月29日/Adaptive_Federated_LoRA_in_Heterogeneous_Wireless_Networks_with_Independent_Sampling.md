# # 在异构无线网络中实现独立采样的自适应联邦低秩适配

发布时间：2025年05月29日

`LLM理论` `联邦学习` `模型优化`

> Adaptive Federated LoRA in Heterogeneous Wireless Networks with Independent Sampling

# 摘要

> 联邦LoRA作为一种有前途的技术，通过减少可训练参数数量，能够在分布式设备上高效微调大型语言模型（LLMs）。然而，现有方法往往未能充分考虑系统和数据异质性在理论和实践中的影响，因此无法优化整体训练效率，尤其是在实际运行时间方面。本文提出了一种自适应联邦LoRA策略，结合独立客户端采样，旨在最小化计算和通信异质性下的联邦微调收敛实际运行时间。我们首先为具有任意独立客户端采样的联邦LoRA推导出一个新的收敛界限，值得注意的是，这不需要严格的有界梯度假设。然后，我们引入了一种自适应带宽分配方案，考虑了客户端资源异质性和系统带宽限制。基于推导出的理论，我们制定了一个非凸优化问题并求解，以联合确定LoRA采样率和采样概率，目标是最小化收敛的实际运行时间。我们还开发了一种高效且低复杂度的算法来近似求解。最后，大量实验表明，与现有最先进的方法相比，我们的方法在各种模型和数据集上显著减少了实际训练时间。


> Federated LoRA has emerged as a promising technique for efficiently fine-tuning large language models (LLMs) on distributed devices by reducing the number of trainable parameters. However, existing approaches often inadequately overlook the theoretical and practical implications of system and data heterogeneity, thereby failing to optimize the overall training efficiency, particularly in terms of wall-clock time. In this paper, we propose an adaptive federated LoRA strategy with independent client sampling to minimize the convergence wall-clock time of federated fine-tuning under both computation and communication heterogeneity. We first derive a new convergence bound for federated LoRA with arbitrary and independent client sampling, notably without requiring the stringent bounded gradient assumption. Then, we introduce an adaptive bandwidth allocation scheme that accounts for heterogeneous client resources and system bandwidth constraints. Based on the derived theory, we formulate and solve a non-convex optimization problem to jointly determine the LoRA sketching ratios and sampling probabilities, aiming to minimize wall-clock convergence time. An efficient and low-complexity algorithm is developed to approximate the solution. Finally, extensive experiments demonstrate that our approach significantly reduces wall-clock training time compared to state-of-the-art methods across various models and datasets.

[Arxiv](https://arxiv.org/abs/2505.23555)