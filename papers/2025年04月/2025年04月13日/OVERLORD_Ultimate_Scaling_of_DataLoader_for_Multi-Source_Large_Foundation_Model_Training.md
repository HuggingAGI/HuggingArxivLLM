# # OVERLORD：用于多源大型基础模型训练的 DataLoader 终极扩展方案

发布时间：2025年04月13日

`其他` `分布式系统` `机器学习`

> OVERLORD: Ultimate Scaling of DataLoader for Multi-Source Large Foundation Model Training

# 摘要

> 现代大型基础模型（LFMs）的训练框架采用数据并行范式的数据加载器。尽管这种设计在实现上较为简单，但它带来了两个根本性的挑战。首先，由于注意力运算的二次计算复杂度，数据并行中的非均匀样本分布导致加载器间的工作负载严重失衡，从而降低了训练效率。此外，这一范式还阻碍了跨不同数据集的数据混合算法（如课程学习）的实现。其次，为了获取广泛的能力，LFMs的训练需要从多种来源摄入数据，每个来源都有不同的文件访问状态。将大规模数据集 colocated 在加载器实例中很容易超出本地 pod 的内存容量。此外，处理高延迟的来源需要更大的工作者池，进一步加剧了内存消耗。

我们提出了 OVERLORD，一个工业级的分布式数据加载架构，具有三个创新点：(1) 一个集中式声明式数据平面，支持弹性数据编排策略，例如长短期上下文、多模态和课程学习；(2) 通过角色特定的参与者（即源加载器和数据构造器）分离多源预处理，利用自动扩缩容来应对异构且不断变化的源预处理成本；(3) 带差异检查点的影子加载器，实现不间断的故障恢复。在扩展至数千个 GPU 的生产集群上部署，OVERLORD 实现了：(1) 4.5 倍的端到端训练吞吐量提升，(2) 至少 3.6 倍的 CPU 内存使用减少，后续实验将进一步改进。

> Modern frameworks for training large foundation models (LFMs) employ data loaders in a data parallel paradigm. While this design offers implementation simplicity, it introduces two fundamental challenges. First, due to the quadratic computational complexity of the attention operator, the non-uniform sample distribution over data-parallel ranks leads to a significant workload imbalance among loaders, which degrades the training efficiency. This paradigm also impedes the implementation of data mixing algorithms (e.g., curriculum learning) over different datasets. Second, to acquire a broad range of capability, LFMs training ingests data from diverse sources, each with distinct file access states. Colocating massive datasets within loader instances can easily exceed local pod memory capacity. Additionally, heavy sources with higher transformation latency require larger worker pools, further exacerbating memory consumption.
  We present OVERLORD, an industrial-grade distributed data loading architecture with three innovations: (1) A centralized and declarative data plane, which facilitates elastic data orchestration strategy, such as long-short context, multimodal, and curriculum learning; (2) Disaggregated multisource preprocessing through role-specific actors, i.e., Source Loaders and Data Constructors, leveraging autoscaling for Source Loaders towards heterogeneous and evolving source preprocessing cost; (3) Shadow Loaders with differential checkpointing for uninterrupted fault recovery. Deployed on production clusters scaling to multi-thousand GPU, OVERLORD achieves: (1) 4.5x end-to-end training throughput improvement, (2) a minimum 3.6x reduction in CPU memory usage, with further improvements to be added in later experiments.

[Arxiv](https://arxiv.org/abs/2504.09844)