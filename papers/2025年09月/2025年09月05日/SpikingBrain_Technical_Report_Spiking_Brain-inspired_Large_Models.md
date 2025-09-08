# # SpikingBrain技术报告：脉冲类脑大模型

发布时间：2025年09月05日

`LLM理论` `基础理论`

> SpikingBrain Technical Report: Spiking Brain-inspired Large Models

# 摘要

> 主流基于Transformer的大型语言模型存在严重的效率瓶颈：训练计算量随序列长度平方级增长，推理内存线性增加，制约了长文本处理能力。在非NVIDIA平台构建大模型时，稳定高效的训练也面临挑战。为此，我们提出SpikingBrain——一个受脑启发的模型家族，专为高效长上下文训练与推理而设计。该模型依托MetaX GPU集群，重点从三方面突破：（1）模型架构：采用带自适应脉冲神经元的线性及混合线性注意力结构；（2）算法优化：构建高效的转换式训练流水线与专用脉冲编码框架；（3）系统工程：定制适配MetaX硬件的训练框架、算子库及并行策略。
  借助这些技术，我们研发了两款模型：SpikingBrain-7B（线性大语言模型）和SpikingBrain-76B（混合线性专家混合（MoE）大语言模型）。它们验证了在非NVIDIA平台上开发大规模大语言模型的可行性。SpikingBrain仅用约1500亿token进行持续预训练，性能便媲美开源Transformer基线模型。我们的模型大幅提升了长序列训练效率，并实现了（部分）恒定内存占用与事件驱动的脉冲推理。例如，SpikingBrain-7B在处理400万token序列时，首token生成时间提速超100倍。在数百块MetaX C550 GPU上，模型可稳定训练数周，其中7B模型的浮点运算利用率（MFU）达23.4%。所提出的脉冲机制实现了69.15%的稀疏度，支持低功耗运行。总之，本研究证明了受脑启发的机制有望推动下一代高效、可扩展大模型的设计。

> Mainstream Transformer-based large language models face major efficiency bottlenecks: training computation scales quadratically with sequence length, and inference memory grows linearly, limiting long-context processing. Building large models on non-NVIDIA platforms also poses challenges for stable and efficient training. To address this, we introduce SpikingBrain, a family of brain-inspired models designed for efficient long-context training and inference. SpikingBrain leverages the MetaX GPU cluster and focuses on three aspects: (1) Model Architecture: linear and hybrid-linear attention architectures with adaptive spiking neurons; (2) Algorithmic Optimizations: an efficient, conversion-based training pipeline and a dedicated spike coding framework; (3) System Engineering: customized training frameworks, operator libraries, and parallelism strategies tailored to MetaX hardware.
  Using these techniques, we develop two models: SpikingBrain-7B, a linear LLM, and SpikingBrain-76B, a hybrid-linear MoE LLM. These models demonstrate the feasibility of large-scale LLM development on non-NVIDIA platforms. SpikingBrain achieves performance comparable to open-source Transformer baselines while using only about 150B tokens for continual pre-training. Our models significantly improve long-sequence training efficiency and deliver inference with (partially) constant memory and event-driven spiking behavior. For example, SpikingBrain-7B attains over 100x speedup in Time to First Token for 4M-token sequences. Training remains stable for weeks on hundreds of MetaX C550 GPUs, with the 7B model reaching a Model FLOPs Utilization of 23.4 percent. The proposed spiking scheme achieves 69.15 percent sparsity, enabling low-power operation. Overall, this work demonstrates the potential of brain-inspired mechanisms to drive the next generation of efficient and scalable large model design.

[Arxiv](https://arxiv.org/abs/2509.05276)