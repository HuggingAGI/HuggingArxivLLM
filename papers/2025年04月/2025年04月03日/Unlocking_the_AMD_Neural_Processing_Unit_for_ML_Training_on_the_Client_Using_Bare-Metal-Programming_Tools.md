# 解锁AMD神经处理单元：使用裸金属编程工具实现客户端机器学习训练

发布时间：2025年04月03日

`LLM应用` `边缘计算` `硬件加速`

> Unlocking the AMD Neural Processing Unit for ML Training on the Client Using Bare-Metal-Programming Tools

# 摘要

> 近年来，随着对定制性、隐私性、性能和可用性的关注，客户端机器学习（ML）任务的执行吸引了越来越多的关注。硬件制造商已开始在其消费设备处理器中集成神经处理单元（NPUs），以优化常见机器学习任务的能效和吞吐量。AMD的NPU作为其Ryzen AI处理器的一部分，是首批集成到x86处理器芯片中的此类加速器之一。与限制程序员使用预配置库不同，AMD支持对NPU进行裸机编程。

本文探索了在客户端利用AMD NPU通过裸机工具链加速大型语言模型GPT-2权重微调的潜力。边缘端微调使模型能够针对特定使用场景进行私有定制。据我们所知，这是首次将此类加速器用于客户端侧的训练。我们将耗时的矩阵乘法操作从CPU转移到NPU，实现了2.8倍以上的加速。这在吞吐量（ mains电源和电池电源下分别提高了1.7倍和1.2倍的FLOPS/s）和能效（电池电源下提高了1.4倍的FLOPS/Ws）方面显著提升了模型的端到端性能。本文详细介绍了我们的实现方法，并深入探讨了NPU硬件和裸机工具流。


> There has been a growing interest in executing machine learning (ML) workloads on the client side for reasons of customizability, privacy, performance, and availability. In response, hardware manufacturers have begun to incorporate so-called Neural Processing Units (NPUs) into their processors for consumer devices. Such dedicated hardware optimizes both power efficiency and throughput for common machine learning tasks. AMD's NPU, part of their Ryzen AI processors, is one of the first such accelerators integrated into a chip with an x86 processor. AMD supports bare-metal programming of their NPU rather than limiting programmers to pre-configured libraries.
  In this paper, we explore the potential of using a bare-metal toolchain to accelerate the weight fine-tuning of a large language model, GPT-2, entirely on the client side using the AMD NPU. Fine-tuning on the edge allows for private customization of a model to a specific use case. To the best of our knowledge, this is the first time such an accelerator has been used to perform training on the client side. We offload time-intensive matrix multiplication operations from the CPU onto the NPU, achieving a speedup of over 2.8x for these operations. This improves end-to-end performance of the model in terms of throughput (1.7x and 1.2x speedup in FLOPS/s on mains and battery power, respectively) and energy efficiency (1.4x improvement in FLOPS/Ws on battery power). We detail our implementation approach and present an in-depth exploration of the NPU hardware and bare-metal tool-flow.

[Arxiv](https://arxiv.org/abs/2504.03083)