# DASH: 基于输入感知的动态层跳过技术，实现高效LLM推理的马尔可夫决策策略

发布时间：2025年05月22日

`LLM应用` `计算效率`

> DASH: Input-Aware Dynamic Layer Skipping for Efficient LLM Inference with Markov Decision Policies

# 摘要

> 大型语言模型 (LLMs) 在广泛的 NLP 任务中表现出色。然而，其高昂的推理成本在实际部署中，特别是在对延迟敏感的场景中，是一个重大障碍。为了解决这一挑战，我们提出了 	extbf{DASH}，一个自适应层跳过框架，根据输入特性动态选择计算路径。我们将跳过过程建模为马尔可夫决策过程 (MDP)，使我们能够基于中间表示做出细致的 token 级别决策。为了缓解跳过可能导致的性能下降，我们引入了一种轻量级的补偿机制，将差异奖励注入到决策过程中。此外，我们设计了一个异步执行策略，将层计算与策略评估重叠，以最小化运行时开销。在多个 LLM 架构和 NLP 基准上的实验表明，我们的方法在保持具有竞争力的任务性能的同时，实现了显著的推理加速，超越了现有方法。

> Large language models (LLMs) have achieved remarkable performance across a wide range of NLP tasks. However, their substantial inference cost poses a major barrier to real-world deployment, especially in latency-sensitive scenarios. To address this challenge, we propose \textbf{DASH}, an adaptive layer-skipping framework that dynamically selects computation paths conditioned on input characteristics. We model the skipping process as a Markov Decision Process (MDP), enabling fine-grained token-level decisions based on intermediate representations. To mitigate potential performance degradation caused by skipping, we introduce a lightweight compensation mechanism that injects differential rewards into the decision process. Furthermore, we design an asynchronous execution strategy that overlaps layer computation with policy evaluation to minimize runtime overhead. Experiments on multiple LLM architectures and NLP benchmarks show that our method achieves significant inference acceleration while maintaining competitive task performance, outperforming existing methods.

[Arxiv](https://arxiv.org/abs/2505.17420)