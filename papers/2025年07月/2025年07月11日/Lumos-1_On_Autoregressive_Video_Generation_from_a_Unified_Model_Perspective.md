# Lumos-1：统一模型视角下的自回归视频生成探索

发布时间：2025年07月11日

`LLM应用` `视频生成` `计算机视觉`

> Lumos-1: On Autoregressive Video Generation from a Unified Model Perspective

# 摘要

> 自回归大型语言模型（LLMs）统一了自然语言任务，并激发了自回归视频生成的初步探索。现有自回归视频生成器要么偏离标准LLM架构，要么依赖外部文本编码器，或因解码延迟过高。本文推出Lumos-1，一款保留LLM架构的自回归视频生成器，仅做了少量架构调整。为在LLMs中注入时空相关性，我们发现3D RoPE的有效性，并诊断其频率范围失衡问题。因此，我们提出MM-RoPE，一种保留文本RoPE特性，同时提供全面频率谱和3D位置缩放的方案，用于建模多模态时空数据。此外，Lumos-1采用遵守帧内双向性和帧间时序因果性的token依赖策略。基于此策略，我们发现由空间信息冗余导致的帧级损失失衡问题，并通过提出自回归离散扩散强制（AR-DF）解决。AR-DF在训练中引入时序管状遮蔽，并采用兼容的推理时遮蔽策略以避免质量下降。通过内存高效的训练技术，我们仅在48个GPU上预训练Lumos-1，其在GenEval、COSMOS-Video2World和OpenSoraPlan上的性能与EMU3、VBench-I2V和VBench-T2V相当。代码和模型可在https://github.com/alibaba-damo-academy/Lumos获取。

> Autoregressive large language models (LLMs) have unified a vast range of language tasks, inspiring preliminary efforts in autoregressive video generation. Existing autoregressive video generators either diverge from standard LLM architectures, depend on bulky external text encoders, or incur prohibitive latency due to next-token decoding. In this paper, we introduce Lumos-1, an autoregressive video generator that retains the LLM architecture with minimal architectural modifications. To inject spatiotemporal correlations in LLMs, we identify the efficacy of incorporating 3D RoPE and diagnose its imbalanced frequency spectrum ranges. Therefore, we propose MM-RoPE, a RoPE scheme that preserves the original textual RoPE while providing comprehensive frequency spectra and scaled 3D positions for modeling multimodal spatiotemporal data. Moreover, Lumos-1 resorts to a token dependency strategy that obeys intra-frame bidirectionality and inter-frame temporal causality. Based on this dependency strategy, we identify the issue of frame-wise loss imbalance caused by spatial information redundancy and solve it by proposing Autoregressive Discrete Diffusion Forcing (AR-DF). AR-DF introduces temporal tube masking during training with a compatible inference-time masking policy to avoid quality degradation. By using memory-efficient training techniques, we pre-train Lumos-1 on only 48 GPUs, achieving performance comparable to EMU3 on GenEval, COSMOS-Video2World on VBench-I2V, and OpenSoraPlan on VBench-T2V. Code and models are available at https://github.com/alibaba-damo-academy/Lumos.

[Arxiv](https://arxiv.org/abs/2507.08801)