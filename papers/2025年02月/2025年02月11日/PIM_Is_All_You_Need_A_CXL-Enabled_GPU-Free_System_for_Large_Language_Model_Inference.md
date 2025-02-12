# PIM即所需：基于CXL的无GPU大语言模型推理系统

发布时间：2025年02月11日

`LLM应用` `计算机体系结构`

> PIM Is All You Need: A CXL-Enabled GPU-Free System for Large Language Model Inference

# 摘要

> 大型语言模型（LLM）推理采用自回归方式逐个生成token，相较于仅编码器的Transformer和卷积神经网络等早期机器学习模型，其运算强度显著降低。同时，LLMs具有庞大的参数规模，并使用键值缓存存储上下文信息。现代LLMs支持长达100万个token的上下文窗口，以生成多样化的文本、音频和视频内容。每个提示对应的巨大键值缓存需要大容量内存，从而限制了推理批处理大小。低运算强度和有限的批处理规模都要求高内存带宽。然而，用于ML模型部署的当代硬件系统（如GPU和TPU）主要针对计算吞吐量进行了优化。这种不匹配对先进LLMs的高效部署提出了挑战，导致用户不得不为内存绑定的LLM推理任务支付昂贵但利用率低的计算资源。
我们提出CENT，一种基于CXL内存扩展、无需GPU的LLM推理系统。CENT利用CXL内存扩展能力容纳大规模LLMs，并借助近内存处理单元实现高内存带宽，从而无需昂贵的GPU。CENT通过可扩展的CXL网络支持设备间的点对点和集体通信原语。我们实现了多种并行策略，将LLMs分布于这些设备上。与支持最大批处理规模且平均功耗相近的GPU基线相比，CENT实现了2.3倍的更高吞吐量和2.3倍的更低能耗。CENT提升了总拥有成本（TCO），每美元生成的token数量是GPU的5.2倍。

> Large Language Model (LLM) inference uses an autoregressive manner to generate one token at a time, which exhibits notably lower operational intensity compared to earlier Machine Learning (ML) models such as encoder-only transformers and Convolutional Neural Networks. At the same time, LLMs possess large parameter sizes and use key-value caches to store context information. Modern LLMs support context windows with up to 1 million tokens to generate versatile text, audio, and video content. A large key-value cache unique to each prompt requires a large memory capacity, limiting the inference batch size. Both low operational intensity and limited batch size necessitate a high memory bandwidth. However, contemporary hardware systems for ML model deployment, such as GPUs and TPUs, are primarily optimized for compute throughput. This mismatch challenges the efficient deployment of advanced LLMs and makes users to pay for expensive compute resources that are poorly utilized for the memory-bound LLM inference tasks.
  We propose CENT, a CXL-ENabled GPU-Free sysTem for LLM inference, which harnesses CXL memory expansion capabilities to accommodate substantial LLM sizes, and utilizes near-bank processing units to deliver high memory bandwidth, eliminating the need for expensive GPUs. CENT exploits a scalable CXL network to support peer-to-peer and collective communication primitives across CXL devices. We implement various parallelism strategies to distribute LLMs across these devices. Compared to GPU baselines with maximum supported batch sizes and similar average power, CENT achieves 2.3$\times$ higher throughput and consumes 2.3$\times$ less energy. CENT enhances the Total Cost of Ownership (TCO), generating 5.2$\times$ more tokens per dollar than GPUs.

[Arxiv](https://arxiv.org/abs/2502.07578)