# 开放词汇语义分割中的高效冗余削减

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了如何利用大规模视觉语言模型（如CLIP）来改进开放词汇语义分割（OVSS）任务。虽然论文中提到的CLIP模型本身是一个视觉语言模型，但论文的核心在于如何应用这些模型来解决具体的计算机视觉任务（即OVSS）。因此，这篇论文属于LLM应用类别，因为它涉及将大型语言模型（或视觉语言模型）应用于具体的实际问题中。` `计算机视觉` `语义分割`

> Efficient Redundancy Reduction for Open-Vocabulary Semantic Segmentation

# 摘要

> # 摘要
开放词汇语义分割（OVSS）是一项开放世界任务，旨在将图像中的每个像素分配给由任意文本描述定义的特定类别。最近，大规模视觉语言模型的突破性进展展示了其强大的开放词汇理解能力，极大地推动了OVSS的发展。然而，现有方法大多面临性能不足或延迟过长的问题。本研究提出了ERR-Seg，一个通过减少冗余来平衡准确性和效率的创新框架。ERR-Seg包含一个无需训练的通道减少模块（CRM），利用CLIP等视觉语言模型的先验知识筛选出最相关的类别，同时舍弃其他类别。此外，它还结合了高效语义上下文融合（ESCF）与空间级和类别级序列减少策略，显著节省了内存和计算资源，且不影响准确性。此外，ERR-Seg还引入了分层语义模块（HSM），利用中间层特征提取的分层语义来增强OVSS的表现。与ADE20K-847设置下的现有最优方法相比，ERR-Seg在mIoU上提升了5.6%，并将延迟降低了67.3%。

> Open-vocabulary semantic segmentation (OVSS) is an open-world task that aims to assign each pixel within an image to a specific class defined by arbitrary text descriptions. Recent advancements in large-scale vision-language models have demonstrated their open-vocabulary understanding capabilities, significantly facilitating the development of OVSS. However, most existing methods suffer from either suboptimal performance or long latency. This study introduces ERR-Seg, a novel framework that effectively reduces redundancy to balance accuracy and efficiency. ERR-Seg incorporates a training-free Channel Reduction Module (CRM) that leverages prior knowledge from vision-language models like CLIP to identify the most relevant classes while discarding others. Moreover, it incorporates Efficient Semantic Context Fusion (ESCF) with spatial-level and class-level sequence reduction strategies. CRM and ESCF result in substantial memory and computational savings without compromising accuracy. Additionally, recognizing the significance of hierarchical semantics extracted from middle-layer features for closed-set semantic segmentation, ERR-Seg introduces the Hierarchical Semantic Module (HSM) to exploit hierarchical semantics in the context of OVSS. Compared to previous state-of-the-art methods under the ADE20K-847 setting, ERR-Seg achieves +$5.6\%$ mIoU improvement and reduces latency by $67.3\%$.

[Arxiv](https://arxiv.org/abs/2501.17642)