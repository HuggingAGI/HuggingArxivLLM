# # 深度求索模型训练过程中的内存分析

发布时间：2025年02月11日

`LLM理论` `模型训练` `资源管理`

> Memory Analysis on the Training Course of DeepSeek Models

# 摘要

> 我们对DeepSeek模型（如DeepSeek-v2和DeepSeek-v3）在训练过程中的GPU显存消耗进行了深入的理论分析。本研究旨在阐明不同分布式训练配置下的设备级显存需求。特别地，我们探讨了影响显存使用的关键因素，包括微批量大小、激活重计算策略、3D并行以及ZeRO优化等。需要指出的是，本报告中提及的训练策略并非DeepSeek的官方配置，而是通过研究这些策略，帮助我们更深入地理解大规模专家混合模型训练中的内存动态。

> We present a theoretical analysis of GPU memory consumption during the training of DeepSeek models such as DeepSeek-v2 and DeepSeek-v3. Our primary objective is to clarify the device-level memory requirements associated with various distributed training configurations. Specifically, we examine critical factors influencing memory usage, including micro-batch size, activation recomputation policies, 3D parallelism, and ZeRO optimizations. It is important to emphasize that the training policies discussed in this report are not representative of DeepSeek's official configurations. Instead, they are explored to provide a deeper understanding of memory dynamics in training of large-scale mixture-of-experts model.

[Arxiv](https://arxiv.org/abs/2502.07846)