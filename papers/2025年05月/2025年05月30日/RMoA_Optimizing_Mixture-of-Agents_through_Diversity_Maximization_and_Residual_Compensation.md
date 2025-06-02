# RMoA：通过多样性最大化与残差补偿优化多智能体组合

发布时间：2025年05月30日

`Agent` `人工智能`

> RMoA: Optimizing Mixture-of-Agents through Diversity Maximization and Residual Compensation

# 摘要

> 尽管基于大型语言模型的多智能体系统在多项任务中表现优异，但仍然面临高计算开销、信息丢失和鲁棒性方面的限制。受ResNet残差学习的启发，我们提出了一种结合残差连接的混合智能体方法——Residual Mixture-of-Agents（RMoA），旨在提升效率和可靠性。我们创新性地设计了一种基于嵌入的多样性选择机制，通过向量相似度贪心选择响应，最大化模型响应中的信息利用率，同时最小化计算成本。为缓解迭代过程中的信息退化问题，我们引入了残差提取代理，通过捕捉层间响应差异保存跨层增量信息，并结合残差聚合代理实现分层信息整合。此外，我们还提出了一种自适应终止机制，根据残差收敛动态终止处理过程，进一步提升推理效率。RMoA在对齐、数学推理、代码生成和多任务理解等基准测试中达到了最先进的性能，同时显著降低了计算开销。代码可在https://github.com/mindhunter01/RMoA获取。

> Although multi-agent systems based on large language models show strong capabilities on multiple tasks, they are still limited by high computational overhead, information loss, and robustness. Inspired by ResNet's residual learning, we propose Residual Mixture-of-Agents (RMoA), integrating residual connections to optimize efficiency and reliability. To maximize information utilization from model responses while minimizing computational costs, we innovatively design an embedding-based diversity selection mechanism that greedily selects responses via vector similarity. Furthermore, to mitigate iterative information degradation, we introduce a Residual Extraction Agent to preserve cross-layer incremental information by capturing inter-layer response differences, coupled with a Residual Aggregation Agent for hierarchical information integration. Additionally, we propose an adaptive termination mechanism that dynamically halts processing based on residual convergence, further improving inference efficiency. RMoA achieves state-of-the-art performance on the benchmarks of across alignment, mathematical reasoning, code generation, and multitasking understanding, while significantly reducing computational overhead. Code is available at https://github.com/mindhunter01/RMoA.

[Arxiv](https://arxiv.org/abs/2505.24442)