# SmallThinker：专为本地部署优化的高效大型语言模型家族

发布时间：2025年07月28日

`LLM应用` `移动计算` `模型优化`

> SmallThinker: A Family of Efficient Large Language Models Natively Trained for Local Deployment

# 摘要

> 尽管前沿大型语言模型 (LLMs) 持续突破能力边界，但它们的部署仍受限于 GPU 驱动的云基础设施。我们通过 SmallThinker 挑战这一范式，SmallThinker 是一系列专为本地设备设计的 LLMs，而非简单适应：面对本地设备的三大挑战——计算能力较弱、内存有限和存储速度慢，我们从零开始构建 SmallThinker，使其在这些限制条件下依然能够高效运行。与传统方法主要通过压缩为云设计的现有模型不同，我们创新性地采用了一种部署感知架构，将约束转化为设计原则。首先，我们引入了一种结合细粒度专家混合机制 (MoE) 和稀疏前馈网络的两级稀疏结构，大幅降低了计算需求，同时保持了模型容量。其次，为克服慢存储的 I/O 瓶颈，我们设计了一个预注意力路由器，使我们的协同设计推理引擎能够在计算注意力的同时从存储中预取专家参数，有效隐藏了存储延迟，否则这种延迟会严重阻碍设备端推理。第三，为了提高内存效率，我们采用了 NoPE-RoPE 混合稀疏注意力机制，大幅减少了 KV 缓存需求。我们发布了 SmallThinker-4B-A0.6B 和 SmallThinker-21B-A3B，它们不仅实现了最先进的性能评分，甚至超越了更大的 LLMs。值得注意的是，我们的协同设计系统几乎消除了对昂贵 GPU 硬件的需求：在 Q4_0 量化下，两个模型在普通消费级 CPU 上的推理速度均超过 20 tokens/s，同时仅分别占用 1GB 和 8GB 的内存。SmallThinker 可在 hf.co/PowerInfer/SmallThinker-4BA0.6B-Instruct 和 hf.co/PowerInfer/SmallThinker-21BA3B-Instruct 公开获取。

> While frontier large language models (LLMs) continue to push capability boundaries, their deployment remains confined to GPU-powered cloud infrastructure. We challenge this paradigm with SmallThinker, a family of LLMs natively designed - not adapted - for the unique constraints of local devices: weak computational power, limited memory, and slow storage. Unlike traditional approaches that mainly compress existing models built for clouds, we architect SmallThinker from the ground up to thrive within these limitations. Our innovation lies in a deployment-aware architecture that transforms constraints into design principles. First, We introduce a two-level sparse structure combining fine-grained Mixture-of-Experts (MoE) with sparse feed-forward networks, drastically reducing computational demands without sacrificing model capacity. Second, to conquer the I/O bottleneck of slow storage, we design a pre-attention router that enables our co-designed inference engine to prefetch expert parameters from storage while computing attention, effectively hiding storage latency that would otherwise cripple on-device inference. Third, for memory efficiency, we utilize NoPE-RoPE hybrid sparse attention mechanism to slash KV cache requirements. We release SmallThinker-4B-A0.6B and SmallThinker-21B-A3B, which achieve state-of-the-art performance scores and even outperform larger LLMs. Remarkably, our co-designed system mostly eliminates the need for expensive GPU hardware: with Q4_0 quantization, both models exceed 20 tokens/s on ordinary consumer CPUs, while consuming only 1GB and 8GB of memory respectively. SmallThinker is publicly available at hf.co/PowerInfer/SmallThinker-4BA0.6B-Instruct and hf.co/PowerInfer/SmallThinker-21BA3B-Instruct.

[Arxiv](https://arxiv.org/abs/2507.20984)