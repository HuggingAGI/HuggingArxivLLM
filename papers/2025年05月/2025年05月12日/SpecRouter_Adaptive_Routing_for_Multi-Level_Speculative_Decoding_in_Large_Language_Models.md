# SpecRouter：面向大型语言模型的多级推测解码自适应路由

发布时间：2025年05月12日

`LLM应用

理由：这篇论文主要探讨了大型语言模型推理过程中的优化策略，提出了一种动态自适应的框架来提高推理效率和适应性。虽然涉及模型链和性能优化，但属于应用层面的改进，而非理论模型或特定技术（如RAG或Agent）的研究。因此，归类为LLM应用。` `计算机科学` `云计算`

> SpecRouter: Adaptive Routing for Multi-Level Speculative Decoding in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在推理质量和计算成本之间面临关键权衡：更大模型能力更强但延迟显著增加，而小模型运行更快但能力较弱。现有服务策略通常采用固定模型规模或静态两阶段推测解码，无法动态适应用户请求复杂性变化或系统性能波动。

本文提出了一种名为\systemname{}的新颖框架，将 LLM 推理重新构想为一个多级推测解码解决的自适应路由问题。基于实时反馈，\systemname{}动态构建和优化推理“路径”（模型链），克服了静态方法的局限性。我们的贡献包括：

1. 一种基于性能分析（执行时间）和预测相似性度量（源自 token 分布差异）的	extbf{自适应模型链调度}机制，能够持续选择最优的草稿和验证模型序列，从而最小化每个生成 token 的预测延迟。
2. 一种	extbf{多级协作验证}框架，其中选定链中的中间模型可以验证推测 token，从而减轻最终最强目标模型的验证负担。
3. 一个	extbf{同步状态管理系统}，为链中异构模型提供高效一致的 KV 缓存处理，包括针对多级推测固有的异步批处理的精确低开销回滚。

初步实验验证了我们方法的有效性。

> Large Language Models (LLMs) present a critical trade-off between inference quality and computational cost: larger models offer superior capabilities but incur significant latency, while smaller models are faster but less powerful. Existing serving strategies often employ fixed model scales or static two-stage speculative decoding, failing to dynamically adapt to the varying complexities of user requests or fluctuations in system performance. This paper introduces \systemname{}, a novel framework that reimagines LLM inference as an adaptive routing problem solved through multi-level speculative decoding. \systemname{} dynamically constructs and optimizes inference "paths" (chains of models) based on real-time feedback, addressing the limitations of static approaches. Our contributions are threefold: (1) An \textbf{adaptive model chain scheduling} mechanism that leverages performance profiling (execution times) and predictive similarity metrics (derived from token distribution divergence) to continuously select the optimal sequence of draft and verifier models, minimizing predicted latency per generated token. (2) A \textbf{multi-level collaborative verification} framework where intermediate models within the selected chain can validate speculative tokens, reducing the verification burden on the final, most powerful target model. (3) A \textbf{synchronized state management} system providing efficient, consistent KV cache handling across heterogeneous models in the chain, including precise, low-overhead rollbacks tailored for asynchronous batch processing inherent in multi-level speculation. Preliminary experiments demonstrate the validity of our method.

[Arxiv](https://arxiv.org/abs/2505.07680)