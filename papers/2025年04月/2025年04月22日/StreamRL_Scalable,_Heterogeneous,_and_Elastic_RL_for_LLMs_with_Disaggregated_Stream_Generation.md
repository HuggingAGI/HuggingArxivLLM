# StreamRL：专为LLMs设计的可扩展、异构且弹性强化学习，基于分散流生成

发布时间：2025年04月22日

`LLM应用` `分布式系统`

> StreamRL: Scalable, Heterogeneous, and Elastic RL for LLMs with Disaggregated Stream Generation

# 摘要

> 强化学习（RL）已成为大型语言模型（LLMs）的核心后训练技术。LLMs的强化学习过程分为生成和训练两个阶段：模型先在线生成样本，再利用这些样本计算奖励用于训练。传统观点认为，集中式架构（两个阶段共享资源）优于分散式架构（为每个阶段分配专用资源）。然而，在实际部署中，集中式架构因资源耦合问题而受限，两个阶段必须使用相同资源，这影响了其在大规模训练中的扩展性和成本效益。相比之下，分散式架构支持灵活资源分配，适应异构训练环境，并便于跨数据中心部署。

StreamRL从分散式架构的基本原则出发，解决了现有分散式RL框架中的两类性能瓶颈：数据流水线气泡（由阶段依赖引起）和偏态气泡（由长尾输出长度分布导致）。为解决数据流水线气泡，StreamRL通过流式生成打破了同步RL算法的阶段边界，并在异步RL中实现完全重叠。针对偏态气泡，StreamRL采用输出长度排序模型识别长尾样本，并通过偏态感知的调度和分配机制减少生成时间。实验表明，StreamRL的吞吐量较现有系统提升2.66倍，在异构、跨数据中心环境下，成本效益提升1.33倍。

> Reinforcement learning (RL) has become the core post-training technique for large language models (LLMs). RL for LLMs involves two stages: generation and training. The LLM first generates samples online, which are then used to derive rewards for training. The conventional view holds that the colocated architecture, where the two stages share resources via temporal multiplexing, outperforms the disaggregated architecture, in which dedicated resources are assigned to each stage. However, in real-world deployments, we observe that the colocated architecture suffers from resource coupling, where the two stages are constrained to use the same resources. This coupling compromises the scalability and cost-efficiency of colocated RL in large-scale training. In contrast, the disaggregated architecture allows for flexible resource allocation, supports heterogeneous training setups, and facilitates cross-datacenter deployment.
  StreamRL is designed with disaggregation from first principles and fully unlocks its potential by addressing two types of performance bottlenecks in existing disaggregated RL frameworks: pipeline bubbles, caused by stage dependencies, and skewness bubbles, resulting from long-tail output length distributions. To address pipeline bubbles, StreamRL breaks the traditional stage boundary in synchronous RL algorithms through stream generation and achieves full overlapping in asynchronous RL. To address skewness bubbles, StreamRL employs an output-length ranker model to identify long-tail samples and reduces generation time via skewness-aware dispatching and scheduling. Experiments show that StreamRL improves throughput by up to 2.66x compared to existing state-of-the-art systems, and improves cost-effectiveness by up to 1.33x in a heterogeneous, cross-datacenter setting.

[Arxiv](https://arxiv.org/abs/2504.15930)