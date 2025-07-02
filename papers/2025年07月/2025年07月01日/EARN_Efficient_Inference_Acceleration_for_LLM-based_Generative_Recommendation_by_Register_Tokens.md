# EARN：基于注册令牌的高效推理加速方法，提升基于LLM的生成推荐效果

发布时间：2025年07月01日

`LLM应用` `推荐系统` `人工智能`

> EARN: Efficient Inference Acceleration for LLM-based Generative Recommendation by Register Tokens

# 摘要

> 基于大型语言模型的生成推荐（LLMRec）虽然取得了显著成功，但因 KV 缓存的高计算开销和内存压力，导致推理延迟问题突出。现有 KV 缓存优化方法存在明显局限：缓存压缩在推荐任务的短解码步骤下效果有限，而提示压缩可能丢失关键交互历史。通过深入分析 LLMRec 中的注意力模式，我们发现两大关键现象：1）层间注意力稀疏性反转，早期层保留密集信息模式，后期层则冗余显著；2）双注意力汇聚现象，注意力分数集中于输入序列的头尾标记。基于此，我们提出 EARN，一个高效推理框架，利用早期层将信息压缩至输入序列边界处的寄存器标记，后续层仅关注这些标记。在三个数据集、两种 LLMRec 方法及两种 LLM 架构上的实验表明，EARN 实现了 3.79 倍加速和 80.8% KV 缓存减少，且准确性超越通用微调方法。本研究有效弥合了 LLMRec 中效率与效果的鸿沟，为工业应用提供了实际部署优势。

> Large Language Model-based generative recommendation (LLMRec) has achieved notable success, but it suffers from high inference latency due to massive computational overhead and memory pressure of KV Cache. Existing KV Cache reduction methods face critical limitations: cache compression offers marginal acceleration given recommendation tasks' short decoding steps, while prompt compression risks discarding vital interaction history. Through systematic analysis of attention patterns in LLMRec, we uncover two pivotal insights: 1) layer-wise attention sparsity inversion where early layers retain dense informative patterns while later layers exhibit high redundancy, and 2) dual attention sinks phenomenon where attention scores concentrate on both head and tail tokens of input sequences. Motivated by these insights, we propose EARN, an efficient inference framework that leverages the early layers to compress information into register tokens placed at the input sequence boundaries, then focuses solely on these tokens in the subsequent layers. Extensive experiments on three datasets, two LLMRec methods and two LLM architectures demonstrate EARN's superiority, achieving up to 3.79x speedup and 80.8% KV Cache reduction with better accuracy than the general finetuning approach. Our work bridges the efficiency-effectiveness gap in LLMRec, offering practical deployment advantages for industrial scenarios.

[Arxiv](https://arxiv.org/abs/2507.00715)