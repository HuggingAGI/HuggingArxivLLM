# 探索现实世界中的时间知识图谱对齐方法

发布时间：2025年07月19日

`其他` `知识图谱` `时间序列`

> Towards Temporal Knowledge Graph Alignment in the Wild

# 摘要

> # 时间知识图谱对齐 (TKGA)

时间知识图谱对齐（TKGA）致力于识别异构时间知识图谱（TKGs）中等价的实体，以实现融合并提升其完备性。尽管已有若干方法被提出以应对这一任务，但大多数方法假设不同TKGs之间具有统一的时间元素标准和简化的时序结构。它们无法处理现实世界中的TKGA（TKGA-Wild），其中多尺度时间元素交织和跨源时序结构失衡普遍存在。

为填补这一空白，我们研究了TKGA-Wild任务，并提出了一种新颖且有效的解决方案——HyDRA。HyDRA是首个通过多尺度超图检索增强生成重新定义任务的方案，以应对TKGA-Wild的挑战。此外，我们为HyDRA设计了一种新型的尺度交织协同机制，该机制整合了同尺度交互和跨尺度冲突检测。该机制旨在缓解多源时序不完整性导致的碎片化问题，并解决由复杂且不均匀的时间事件密度分布引发的不一致性，从而提升模型处理现实世界时序对齐复杂性的能力。

最后，目前尚无标准基准能够捕捉TKGA-Wild的这些挑战并对现有方法进行有效评估。为此，我们正式提出了TKGA-Wild的基准挑战，并通过建立两个新数据集（BETA和WildBETA）来验证方法的有效性。在新数据集和六个代表性基准上的广泛实验表明，BETA和WildBETA更能反映现实世界的挑战。同时，HyDRA为TKGA-Wild提出了新的范式，在24种竞争基线上始终保持更优性能，同时保持了强大的效率和可扩展性。

> Temporal Knowledge Graph Alignment (TKGA) seeks to identify equivalent entities across heterogeneous temporal knowledge graphs (TKGs) for fusion to improve their completeness. Although some approaches have been proposed to tackle this task, most assume unified temporal element standards and simplified temporal structures across different TKGs. They cannot deal with TKGA in the wild (TKGA-Wild), where multi-scale temporal element entanglement and cross-source temporal structural imbalances are common. To bridge this gap, we study the task of TKGA-Wild and propose HyDRA, a new and effective solution. HyDRA is the first to reformulate the task via multi-scale hypergraph retrieval-augmented generation to address the challenges of TKGA-Wild.In addition, we design a new scale-weave synergy mechanism for HyDRA, which incorporates intra-scale interactions and cross-scale conflict detection. This mechanism is designed to alleviate the fragmentation caused by multi-source temporal incompleteness and resolves inconsistencies arising from complex and uneven temporal event density distributions, thereby enhancing the model capacity to handle the intricacies of real-world temporal alignment. Finally, there is no standard benchmark that captures these challenges of TKGA-Wild and effectively evaluates existing methods. To this end, we formally propose to benchmark challenges for TKGA-Wild and validate the effectiveness of the method by establishing two new datasets(BETA and WildBETA). Extensive experiments on the new datasets and six representative benchmarks show that BETA and WildBETA better reflect real-world challenges. Meanwhile, HyDRA proposes a new paradigm for TKGA-Wild, consistently outperforming 24 competitive baselines, while maintaining strong efficiency and scalability.

[Arxiv](https://arxiv.org/abs/2507.14475)