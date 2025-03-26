# V-Seek：加速实现基于开源硬件的服务器级RISC-V平台上LLM推理

发布时间：2025年03月21日

`RISC-V` `计算机硬件` `芯片技术`

> V-Seek: Accelerating LLM Reasoning on Open-hardware Server-class RISC-V Platforms

# 摘要

> 大型语言模型（LLMs）的指数级增长主要依赖于基于GPU的系统。然而，CPU正逐渐成为一种灵活且更具成本效益的替代方案，尤其是在推理和推理任务方面。RISC-V凭借其开放且厂商中立的指令集架构，在这一领域迅速获得关注。然而，针对LLM工作负载的RISC-V硬件和相应的软件生态系统尚未完全成熟和优化，尤其是在需要特定领域调整的情况下。本文旨在填补这一空白，专注于优化Sophon SG2042上的LLM推理，该芯片是首款商用多核RISC-V CPU，具备向量处理能力。

在两近期针对推理优化的先进LLMs——DeepSeek R1 Distill Llama 8B和DeepSeek R1 Distill QWEN 14B上，我们在token生成和提示处理方面分别达到了4.32/2.29 token/s和6.54/3.68 token/s的速度，相较于我们的基准测试，性能提升了2.9倍至3.0倍。

> The recent exponential growth of Large Language Models (LLMs) has relied on GPU-based systems. However, CPUs are emerging as a flexible and lower-cost alternative, especially when targeting inference and reasoning workloads. RISC-V is rapidly gaining traction in this area, given its open and vendor-neutral ISA. However, the RISC-V hardware for LLM workloads and the corresponding software ecosystem are not fully mature and streamlined, given the requirement of domain-specific tuning. This paper aims at filling this gap, focusing on optimizing LLM inference on the Sophon SG2042, the first commercially available many-core RISC-V CPU with vector processing capabilities.
  On two recent state-of-the-art LLMs optimized for reasoning, DeepSeek R1 Distill Llama 8B and DeepSeek R1 Distill QWEN 14B, we achieve 4.32/2.29 token/s for token generation and 6.54/3.68 token/s for prompt processing, with a speed up of up 2.9x/3.0x compared to our baseline.

[Arxiv](https://arxiv.org/abs/2503.17422)