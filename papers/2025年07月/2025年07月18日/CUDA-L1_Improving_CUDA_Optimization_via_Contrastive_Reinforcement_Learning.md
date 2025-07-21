# CUDA-L1：借助对比强化学习优化CUDA性能

发布时间：2025年07月18日

`LLM应用` `高性能计算` `机器学习`

> CUDA-L1: Improving CUDA Optimization via Contrastive Reinforcement Learning

# 摘要

> 大型语言模型的飞速发展推动了GPU计算资源需求的指数级增长，这一趋势迫切需要自动化的CUDA优化策略。尽管当前先进的LLM（如R1、o1）在代码生成方面展现出潜力，但它们在提升CUDA性能方面却鲜有建树。本文介绍的CUDA-L1，正是一个专为CUDA优化设计的自动化强化学习框架。

CUDA-L1在CUDA优化任务中表现卓越：在NVIDIA A100上训练后，它在KernelBench的250个CUDA内核上实现了平均17.7倍的加速，峰值加速甚至达到了449倍。值得注意的是，尽管CUDA-L1是针对A100进行优化的，但它在其他GPU架构上同样表现出色：在H100上实现了平均17.8倍的加速，在RTX 3090上为19.0倍，在L40上为16.5倍，在H800上为14.7倍，在H20上为13.9倍。除了这些令人瞩目的基准测试结果，CUDA-L1还具备以下显著特性：1) 能够发现多种CUDA优化技术，并学习如何将它们战略性地结合以实现最佳性能；2) 揭示了CUDA优化的基本原理；3) 能够识别不明显的性能瓶颈，并拒绝那些看似有益却可能损害性能的优化方案。

CUDA-L1的能力证明，强化学习仅通过基于加速的奖励信号，就可以将原本表现不佳的LLM转变为高效的CUDA优化器，而无需依赖人类专业知识或领域知识。更重要的是，经过训练的RL模型能够将其获得的推理能力扩展至新的内核。这一范式不仅为CUDA操作的自动化优化开辟了新途径，更有望显著提升GPU效率，有效缓解日益增长的GPU计算资源压力。

> The exponential growth in demand for GPU computing resources, driven by the rapid advancement of Large Language Models, has created an urgent need for automated CUDA optimization strategies. While recent advances in LLMs show promise for code generation, current SOTA models (e.g. R1, o1) achieve low success rates in improving CUDA speed. In this paper, we introduce CUDA-L1, an automated reinforcement learning framework for CUDA optimization.
  CUDA-L1 achieves performance improvements on the CUDA optimization task: trained on NVIDIA A100, it delivers an average speedup of x17.7 across all 250 CUDA kernels of KernelBench, with peak speedups reaching x449. Furthermore, the model also demonstrates excellent portability across GPU architectures, achieving average speedups of x17.8 on H100, x19.0 on RTX 3090, x16.5 on L40, x14.7 on H800, and x13.9 on H20 despite being optimized specifically for A100. Beyond these benchmark results, CUDA-L1 demonstrates several remarkable properties: 1) Discovers a variety of CUDA optimization techniques and learns to combine them strategically to achieve optimal performance; 2) Uncovers fundamental principles of CUDA optimization; 3) Identifies non-obvious performance bottlenecks and rejects seemingly beneficial optimizations that harm performance.
  The capabilities of CUDA-L1 demonstrate that reinforcement learning can transform an initially poor-performing LLM into an effective CUDA optimizer through speedup-based reward signals alone, without human expertise or domain knowledge. More importantly, the trained RL model extend the acquired reasoning abilities to new kernels. This paradigm opens possibilities for automated optimization of CUDA operations, and holds promise to substantially promote GPU efficiency and alleviate the rising pressure on GPU computing resources.

[Arxiv](https://arxiv.org/abs/2507.14111)