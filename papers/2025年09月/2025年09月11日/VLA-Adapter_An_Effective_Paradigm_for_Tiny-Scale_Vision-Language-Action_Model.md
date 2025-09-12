# VLA-Adapter：微型尺度视觉-语言-动作模型的高效范式

发布时间：2025年09月11日

`Agent` `工业与制造`

> VLA-Adapter: An Effective Paradigm for Tiny-Scale Vision-Language-Action Model

# 摘要

> 视觉-语言-动作（VLA）模型通常通过在机器人数据上预训练大规模视觉-语言模型（VLM）来弥合感知与动作空间的差距。尽管这种方法能显著提升性能，但也带来了高昂的训练成本。本文研究如何有效将视觉-语言（VL）表示与动作（A）桥接。我们提出VLA-Adapter——一种新范式，旨在降低VLA模型对大规模VLM和大量预训练的依赖。为此，我们首先系统分析了多种VL条件的有效性，并得出关键结论：哪些条件对弥合感知与动作空间至关重要。基于这些见解，我们提出带桥接注意力机制的轻量级策略模块，它能自主将最优条件注入动作空间。通过这种方式，我们的方法仅需0.5B参数的骨干网络，无需任何机器人数据预训练，即可实现高性能。在模拟和真实世界机器人基准测试上的大量实验表明，VLA-Adapter不仅达到了最先进水平的性能，还拥有迄今为止最快的推理速度。此外，得益于所提出的先进桥接范式，VLA-Adapter仅需单张消费级GPU、8小时即可训练出强大的VLA模型，极大降低了VLA模型的部署门槛。Project page: https://vla-adapter.github.io/.

> Vision-Language-Action (VLA) models typically bridge the gap between perceptual and action spaces by pre-training a large-scale Vision-Language Model (VLM) on robotic data. While this approach greatly enhances performance, it also incurs significant training costs. In this paper, we investigate how to effectively bridge vision-language (VL) representations to action (A). We introduce VLA-Adapter, a novel paradigm designed to reduce the reliance of VLA models on large-scale VLMs and extensive pre-training. To this end, we first systematically analyze the effectiveness of various VL conditions and present key findings on which conditions are essential for bridging perception and action spaces. Based on these insights, we propose a lightweight Policy module with Bridge Attention, which autonomously injects the optimal condition into the action space. In this way, our method achieves high performance using only a 0.5B-parameter backbone, without any robotic data pre-training. Extensive experiments on both simulated and real-world robotic benchmarks demonstrate that VLA-Adapter not only achieves state-of-the-art level performance, but also offers the fast inference speed reported to date. Furthermore, thanks to the proposed advanced bridging paradigm, VLA-Adapter enables the training of a powerful VLA model in just 8 hours on a single consumer-grade GPU, greatly lowering the barrier to deploying the VLA model. Project page: https://vla-adapter.github.io/.

[Arxiv](https://arxiv.org/abs/2509.09372)