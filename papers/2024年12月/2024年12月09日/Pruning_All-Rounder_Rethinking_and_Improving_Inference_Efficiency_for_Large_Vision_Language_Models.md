# 《修剪全能手：重新思索并提升大型视觉语言模型的推理效率》

发布时间：2024年12月09日

`LLM应用` `计算机视觉` `模型推理`

> Pruning All-Rounder: Rethinking and Improving Inference Efficiency for Large Vision Language Models

# 摘要

> 尽管大型视觉语言模型（LVLMs）成绩斐然，但其高昂的计算成本严重阻碍了其广泛应用。为提升推理效率，现有的多数方法依靠参数或令牌相关策略来降低计算需求。然而，这些方法往往需要复杂的训练流程，且难以始终选出最相关的令牌。在本文中，我们对上述挑战进行了系统分析，并为推理加速提供了一系列宝贵见解。基于这些发现，我们提出了一个全新框架——修剪全能者（PAR）。与以往工作不同，PAR 开发了一个元路由器，能自适应地组织跨令牌和层的修剪流。通过自监督学习的方式，我们的方法在性能和效率之间达到了出色的平衡。值得注意的是，PAR 灵活性极高，提供了多种修剪版本以应对各种修剪场景。此项工作的代码将会公开。

> Although Large Vision-Language Models (LVLMs) have achieved impressive results, their high computational cost poses a significant barrier to wider application. To enhance inference efficiency, most existing approaches depend on parameter-dependent or token-dependent strategies to reduce computational demands. However, these methods typically require complex training processes and struggle to consistently select the most relevant tokens. In this paper, we systematically analyze the above challenges and provide a series of valuable insights for inference acceleration. Based on these findings, we propose a novel framework, the Pruning All-Rounder (PAR). Different from previous works, PAR develops a meta-router to adaptively organize pruning flows across both tokens and layers. With a self-supervised learning manner, our method achieves a superior balance between performance and efficiency. Notably, PAR is highly flexible, offering multiple pruning versions to address a range of pruning scenarios. The code for this work will be made publicly available.

[Arxiv](https://arxiv.org/abs/2412.06458)