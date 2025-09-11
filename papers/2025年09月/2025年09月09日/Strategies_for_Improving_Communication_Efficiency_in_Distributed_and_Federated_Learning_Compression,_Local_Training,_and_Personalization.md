# 分布式与联邦学习中提升通信效率的策略：压缩、本地训练及个性化

发布时间：2025年09月09日

`其他` `基础理论`

> Strategies for Improving Communication Efficiency in Distributed and Federated Learning: Compression, Local Training, and Personalization

# 摘要

> 分布式与联邦学习是在去中心化数据源上训练模型并保护隐私的核心范式，然而通信开销始终是主要瓶颈。本论文探索提升通信效率的策略，聚焦模型压缩、本地训练与个性化三大方向。我们构建了一个兼具收敛保证的有偏与无偏压缩算子统一框架，进而提出融合个性化的自适应本地训练策略，以加速收敛并缓解客户端漂移问题。其中，Scafflix通过平衡全局与个性化目标，在IID和非IID场景下均展现出卓越性能。我们还提出了保护隐私的剪枝框架，在优化稀疏性的同时降低通信成本；Cohort-Squeeze通过分层聚合减少跨设备开销，成为该框架的关键实现。最后，对称训练后剪枝方法SymWanda在高稀疏度下提升了鲁棒性，且无需重新训练即可保持精度。在基准数据集和大规模语言模型上的大量实验表明，该研究在准确性、收敛速度与通信效率间实现了良好平衡，为可扩展、高效的分布式学习提供了理论与实践指导。

> Distributed and federated learning are essential paradigms for training models across decentralized data sources while preserving privacy, yet communication overhead remains a major bottleneck. This dissertation explores strategies to improve communication efficiency, focusing on model compression, local training, and personalization. We establish a unified framework for biased and unbiased compression operators with convergence guarantees, then propose adaptive local training strategies that incorporate personalization to accelerate convergence and mitigate client drift. In particular, Scafflix balances global and personalized objectives, achieving superior performance under both IID and non-IID settings. We further introduce privacy-preserving pruning frameworks that optimize sparsity while minimizing communication costs, with Cohort-Squeeze leveraging hierarchical aggregation to reduce cross-device overhead. Finally, SymWanda, a symmetric post-training pruning method, enhances robustness under high sparsity and maintains accuracy without retraining. Extensive experiments on benchmarks and large-scale language models demonstrate favorable trade-offs among accuracy, convergence, and communication, offering theoretical and practical insights for scalable, efficient distributed learning.

[Arxiv](https://arxiv.org/abs/2509.08233)