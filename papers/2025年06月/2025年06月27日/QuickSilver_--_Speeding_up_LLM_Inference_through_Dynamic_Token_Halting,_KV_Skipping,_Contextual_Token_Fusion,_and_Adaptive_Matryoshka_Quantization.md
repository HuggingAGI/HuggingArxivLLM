# QuickSilver -- 动态令牌终止、KV跳过、上下文令牌融合与自适应套娃量化加速LLM推理

发布时间：2025年06月27日

`LLM应用

理由：这篇论文专注于优化大型语言模型（LLM）的推理过程，提出了一个名为QuickSilver的框架，通过动态Token停止、KV缓存跳过和上下文Token融合等机制，显著减少了计算量和能源消耗，同时保持了模型性能。这些优化措施直接针对LLM的实际应用和部署中的效率问题，因此属于LLM应用类别。` `人工智能`

> QuickSilver -- Speeding up LLM Inference through Dynamic Token Halting, KV Skipping, Contextual Token Fusion, and Adaptive Matryoshka Quantization

# 摘要

> 在大型语言模型 (LLM) 的部署中，推理过程占据了大部分的延迟和能源消耗，往往超过总成本的90%。尽管训练效率已有显著提升，但在自回归解码场景下，推理优化仍然是一个关键瓶颈。现有的方法，如剪枝、量化、提前退出和推测性解码，通常需要重新训练、架构更改或破坏解码兼容性。

我们提出了QuickSilver，一个模块化的、基于token的框架，能够在不改变模型权重或结构的情况下，实现推理时的语义自适应。QuickSilver集成了四个协同机制：
  (i) 动态Token停止，用于停止具有收敛表示的token的计算；
  (ii) KV缓存跳过，选择性地抑制内存写入以减少注意力开销；
  (iii) 上下文Token融合，将冗余的token合并到共享路径中以缩短序列长度。

与推测性解码或MoE路由不同，QuickSilver完全在冻结的密集模型上运行，不需要辅助网络。在WikiText-103和C4数据集上，将QuickSilver应用于GPT-2和Llama-2，实现了高达39.6%的FLOP减少，同时困惑度下降可以忽略不计（<=0.2）。

> Inference accounts for the majority of latency and energy consumption in large language model (LLM) deployments, often exceeding 90% of total cost. While training-time efficiency has seen extensive progress, runtime optimization remains a key bottleneck, particularly under autoregressive decoding. Existing approaches -- such as pruning, quantization, early exits, and speculative decoding -- often require retraining, architectural changes, or disrupt decoding compatibility. We introduce QuickSilver, a modular, token-level framework that enables semantic adaptivity at inference time without altering model weights or structure. QuickSilver integrates four synergistic mechanisms:
  (i) Dynamic Token Halting, which halts computation for tokens with converged representations; (ii) KV Cache Skipping, which selectively suppresses memory writes to reduce attention overhead; and (iii) Contextual Token Fusion, which collapses redundant tokens into shared paths to shrink sequence length.
  Unlike speculative decoding or MoE routing, QuickSilver operates entirely on frozen, dense models and requires no auxiliary networks. Applied to GPT-2 and Llama-2 across WikiText-103 and C4, QuickSilver achieves up to 39.6% FLOP reduction with negligible perplexity degradation (<=0.2).

[Arxiv](https://arxiv.org/abs/2506.22396)