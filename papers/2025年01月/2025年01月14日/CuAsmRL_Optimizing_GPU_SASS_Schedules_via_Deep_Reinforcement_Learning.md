# CuAsmRL: 利用深度强化学习优化 GPU SASS 调度

发布时间：2025年01月14日

`Agent

理由：这篇论文主要讨论的是使用强化学习（RL）代理来自动优化GPU SASS调度，以提高大型语言模型（LLMs）的计算性能。核心内容围绕如何训练一个RL代理来模拟人类专家的手动调度过程，并通过迭代操作来优化调度。因此，这篇论文的重点在于强化学习代理的应用和优化，属于Agent分类。` `GPU优化` `编译器`

> CuAsmRL: Optimizing GPU SASS Schedules via Deep Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）因其庞大的计算需求而备受关注。为了降低成本，研究人员开发了专门的CUDA内核，通过融合多个张量操作来最大化GPU的利用率。然而，这些专门的内核可能仍未充分发挥性能，因为CUDA汇编专家指出，手动优化GPU SASS调度可以带来更好的性能，而试错法常被用于手动寻找最佳调度。
    在本研究中，我们采用了一种自动优化GPU SASS调度的方法，并将其集成到现有的编译器框架中。自动优化的核心在于训练一个强化学习（RL）代理，模拟人类专家进行手动调度的过程。为此，我们设计了一个汇编游戏，RL代理可以在其中探索最佳GPU SASS调度。游戏从一个	extit{-O3}优化的SASS调度开始，RL代理通过迭代操作改变当前调度。如果改变后的调度在GPU上执行时获得更高的吞吐量，则会产生正向奖励。实验表明，CuAsmRL可以透明地提升现有专门CUDA内核的性能，最高提升26%，平均提升9%。此外，它还揭示了自动学习的潜在优化手段。

> Large language models (LLMs) are remarked by their substantial computational requirements. To mitigate the cost, researchers develop specialized CUDA kernels, which often fuse several tensor operations to maximize the utilization of GPUs as much as possible. However, those specialized kernels may still leave performance on the table as CUDA assembly experts show that manual optimization of GPU SASS schedules can lead to better performance, and trial-and-error is largely employed to manually find the best GPU SASS schedules.
  In this work, we employ an automatic approach to optimize GPU SASS schedules, which thus can be integrated into existing compiler frameworks. The key to automatic optimization is training an RL agent to mimic how human experts perform manual scheduling. To this end, we formulate an assembly game, where RL agents can play to find the best GPU SASS schedules. The assembly game starts from a \textit{-O3} optimized SASS schedule, and the RL agents can iteratively apply actions to mutate the current schedules. Positive rewards are generated if the mutated schedules get higher throughput by executing on GPUs. Experiments show that CuAsmRL can further improve the performance of existing specialized CUDA kernels transparently by up to $26\%$, and on average $9\%$. Moreover, it is used as a tool to reveal potential optimization moves learned automatically.

[Arxiv](https://arxiv.org/abs/2501.08071)