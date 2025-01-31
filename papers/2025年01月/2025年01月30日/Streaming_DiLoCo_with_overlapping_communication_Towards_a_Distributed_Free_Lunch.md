# 流式 DiLoCo 与重叠通信：迈向分布式免费午餐

发布时间：2025年01月30日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的分布式训练方法，特别是如何通过改进通信策略来降低带宽需求并提高训练效率。这些改进涉及参数同步、训练过程的优化以及数据量化等技术，属于对LLM训练过程的理论和方法的研究。因此，这篇论文应归类为LLM理论。` `分布式计算` `机器学习`

> Streaming DiLoCo with overlapping communication: Towards a Distributed Free Lunch

# 摘要

> # 摘要
大型语言模型（LLMs）的训练通常分布在大量加速器上以缩短训练时间。由于每个梯度步骤都需要交换内部状态和参数梯度，所有设备必须通过低延迟高带宽的通信链路共置，以支持高交换比特量。最近，DiLoCo等分布式算法放宽了共置限制：加速器可分组为“工作者”，工作者间的同步仅偶尔进行。这意味着工作者可以通过较低带宽的通信链路连接，而不影响学习质量。然而，这些方法中，工作者间的通信仍需要与之前相同的峰值带宽，因为同步时所有参数需在所有工作者间交换。本文从三个方面改进DiLoCo：首先，我们按顺序同步参数子集，而非一次性同步所有参数，大幅降低峰值带宽；其次，允许工作者在同步时继续训练，减少挂钟时间；第三，对工作者间交换的数据进行量化，进一步降低带宽。通过合理结合这些改进，实验表明我们能够分布训练数十亿规模的参数，并保持与之前相当的质量，同时将所需带宽降低两个数量级。

> Training of large language models (LLMs) is typically distributed across a large number of accelerators to reduce training time. Since internal states and parameter gradients need to be exchanged at each and every single gradient step, all devices need to be co-located using low-latency high-bandwidth communication links to support the required high volume of exchanged bits. Recently, distributed algorithms like DiLoCo have relaxed such co-location constraint: accelerators can be grouped into ``workers'', where synchronizations between workers only occur infrequently. This in turn means that workers can afford being connected by lower bandwidth communication links without affecting learning quality. However, in these methods, communication across workers still requires the same peak bandwidth as before, as the synchronizations require all parameters to be exchanged across all workers. In this paper, we improve DiLoCo in three ways. First, we synchronize only subsets of parameters in sequence, rather than all at once, which greatly reduces peak bandwidth. Second, we allow workers to continue training while synchronizing, which decreases wall clock time. Third, we quantize the data exchanged by workers, which further reduces bandwidth across workers. By properly combining these modifications, we show experimentally that we can distribute training of billion-scale parameters and reach similar quality as before, but reducing required bandwidth by two orders of magnitude.

[Arxiv](https://arxiv.org/abs/2501.18512)