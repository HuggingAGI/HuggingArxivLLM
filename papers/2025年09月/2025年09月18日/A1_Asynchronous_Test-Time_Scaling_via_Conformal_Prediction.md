# A1: 基于Conformal预测的异步测试时扩展

发布时间：2025年09月18日

`LLM应用` `基础理论`

> A1: Asynchronous Test-Time Scaling via Conformal Prediction

# 摘要

> 大型语言模型（LLMs）借助测试时扩展提升性能，但现有方法却面临诸多难题，如同步开销大、内存瓶颈突出、延迟较高，尤其是在长推理链的推测性解码场景下。为此，我们提出A1（异步测试时扩展），这是一种具备统计保证的自适应推理框架，专门用于应对上述问题。A1通过优化计算强度，将同步问题确定为主要瓶颈；提出在线校准策略，实现异步推理；并设计三阶段拒绝采样流水线，支持顺序与并行扩展。在MATH、AMC23、AIME24、AIME25数据集以及多种草稿-目标模型族上的实验表明，A1实现了56.7倍的测试时扩展加速和4.14倍的吞吐量提升，同时能精准控制拒绝率、降低延迟与内存开销，且与单独使用目标模型扩展相比无精度损失。这些结果证实，A1是大规模LLM推理的高效且规范的解决方案。相关代码已开源至https://github.com/menik1126/asynchronous-test-time-scaling。

> Large language models (LLMs) benefit from test-time scaling, but existing methods face significant challenges, including severe synchronization overhead, memory bottlenecks, and latency, especially during speculative decoding with long reasoning chains. We introduce A1 (Asynchronous Test-Time Scaling), a statistically guaranteed adaptive inference framework that addresses these challenges. A1 refines arithmetic intensity to identify synchronization as the dominant bottleneck, proposes an online calibration strategy to enable asynchronous inference, and designs a three-stage rejection sampling pipeline that supports both sequential and parallel scaling. Through experiments on the MATH, AMC23, AIME24, and AIME25 datasets, across various draft-target model families, we demonstrate that A1 achieves a remarkable 56.7x speedup in test-time scaling and a 4.14x improvement in throughput, all while maintaining accurate rejection-rate control, reducing latency and memory overhead, and no accuracy loss compared to using target model scaling alone. These results position A1 as an efficient and principled solution for scalable LLM inference. We have released the code at https://github.com/menik1126/asynchronous-test-time-scaling.

[Arxiv](https://arxiv.org/abs/2509.15148)