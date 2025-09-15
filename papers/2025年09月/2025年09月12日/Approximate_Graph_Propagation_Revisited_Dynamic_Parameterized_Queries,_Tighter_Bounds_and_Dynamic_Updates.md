# 近似图传播再探：动态参数化查询、更紧界与动态更新

发布时间：2025年09月12日

`RAG` `基础理论`

> Approximate Graph Propagation Revisited: Dynamic Parameterized Queries, Tighter Bounds and Dynamic Updates

# 摘要

> 我们重新研究了近似图传播（AGP）——这是一个能够涵盖多种图传播任务的统一框架，例如PageRank、图神经网络（GNNs）中的特征传播以及基于图的检索增强生成（RAG）。我们的研究聚焦于动态图与动态参数化查询场景：底层图会随时间演化（通过边的插入或删除更新），而输入查询参数则可根据应用需求动态指定。我们的首个发现颇具启发性：最先进的AGP-Static方案可调整以支持动态参数化查询，但仍存在一些亟待解决的问题。其一，AGP-Static的查询时间复杂度依赖于其查询算法采用子集采样最优算法的假设；但遗憾的是，当时这类算法尚未出现，若缺乏该最优算法，查询复杂度会额外增加【数学公式】的因子（其中n为图的顶点数）。其二，AGP-Static在动态图上表现欠佳，每次更新需耗时【数学公式】。为此，我们提出了更简洁的新算法AGP-Static++，它在保留AGP-Static近似保证的同时，将查询复杂度大致降低了【数学公式】倍。不过，AGP-Static++处理单次更新仍需【数学公式】时间。为更好适配动态图，我们进一步提出AGP-Dynamic算法，它实现了每次更新【数学公式】的摊销时间，大幅优化了前述单次更新【数学公式】的时间界限，同时维持了原有的查询复杂度与近似保证。最后，综合实验验证了这些理论改进：与基线方法相比，我们的算法在更新时间上加速比高达177倍，查询效率提升10倍。

> We revisit Approximate Graph Propagation (AGP), a unified framework which captures various graph propagation tasks, such as PageRank, feature propagation in Graph Neural Networks (GNNs), and graph-based Retrieval-Augmented Generation (RAG). Our work focuses on the settings of dynamic graphs and dynamic parameterized queries, where the underlying graphs evolve over time (updated by edge insertions or deletions) and the input query parameters are specified on the fly to fit application needs. Our first contribution is an interesting observation that the SOTA solution, AGP-Static, can be adapted to support dynamic parameterized queries; however several challenges remain unresolved. Firstly, the query time complexity of AGP-Static is based on an assumption of using an optimal algorithm for subset sampling in its query algorithm. Unfortunately, back to that time, such an algorithm did not exist; without such an optimal algorithm, an extra $O(\log^2 n)$ factor is required in the query complexity, where $n$ is the number of vertices in the graphs. Secondly, AGP-Static performs poorly on dynamic graphs, taking $O(n\log n)$ time to process each update. To address these challenges, we propose a new algorithm, AGP-Static++, which is simpler yet reduces roughly a factor of $O(\log^2 n)$ in the query complexity while preserving the approximation guarantees of AGP-Static. However, AGP-Static++ still requires $O(n)$ time to process each update. To better support dynamic graphs, we further propose AGP-Dynamic, which achieves $O(1)$ amortized time per update, significantly improving the aforementioned $O(n)$ per-update bound, while still preserving the query complexity and approximation guarantees. Last, our comprehensive experiments validate the theoretical improvements: compared to the baselines, our algorithm achieves speedups of up to $177\times$ on update time and $10\times$ on query efficiency.

[Arxiv](https://arxiv.org/abs/2509.10036)