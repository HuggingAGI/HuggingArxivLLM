# **EdgeVLA：高效视觉-语言-动作模型**

发布时间：2025年07月18日

`其他

理由：这篇论文主要探讨了视觉语言模型（VLMs）在机器人领域的应用，特别是在边缘设备上的高效推理和部署。虽然涉及语言模型，但其核心贡献在于模型优化和跨领域应用，因此更适合归类到其他。` `机器人` `机器人视觉`

> EdgeVLA: Efficient Vision-Language-Action Models

# 摘要

> 视觉语言模型（VLMs）应运而生，为解决机器人领域的数据稀缺性挑战提供了有力工具，并推动了通用视觉运动控制策略的发展。尽管像OpenVLA这样的模型展示了这一领域的潜力，但在资源受限的移动操作系统上部署大规模VLMs仍面临巨大挑战。本文提出了一种名为Edge VLA（EVLA）的创新方法，旨在显著提升视觉语言动作（VLA）模型的推理速度。EVLA不仅保留了模型的表示能力，还实现了在边缘设备上的实时性能。我们通过两大关键创新实现了这一目标：1) 革新性地取消末端执行器位置预测的自回归要求，使推理速度提升7倍；2) 充分发挥小型语言模型（SLMs）的效率优势，在显著降低计算需求的同时，保持与大型模型相当的训练性能。初步实验表明，EVLA在训练特性上与OpenVLA不相上下，同时在推理速度和内存效率方面实现了重大突破。为推动进一步研究，我们公开了模型检查点和训练\href{https://github.com/kscalelabs/evla}{代码库}。

> Vision-Language Models (VLMs) have emerged as a promising approach to address the data scarcity challenge in robotics, enabling the development of generalizable visuomotor control policies. While models like OpenVLA showcase the potential of this paradigm, deploying large-scale VLMs on resource-constrained mobile manipulation systems remains a significant hurdle. This paper introduces Edge VLA (EVLA), a novel approach designed to significantly enhance the inference speed of Vision-Language-Action (VLA) models. EVLA maintains the representational power of these models while enabling real-time performance on edge devices. We achieve this through two key innovations: 1) Eliminating the autoregressive requirement for end-effector position prediction, leading to a 7x speedup in inference, and 2) Leveraging the efficiency of Small Language Models (SLMs), demonstrating comparable training performance to larger models with significantly reduced computational demands. Our early results demonstrate that EVLA achieves comparable training characteristics to OpenVLA while offering substantial gains in inference speed and memory efficiency. We release our model checkpoints and training \href{https://github.com/kscalelabs/evla }{codebase} to foster further research.

[Arxiv](https://arxiv.org/abs/2507.14049)