# CollaPipe：面向异构边缘网络中协同LLM训练的自适应分段优化流水线并行技术

发布时间：2025年09月24日

`Agent` `交通运输`

> CollaPipe: Adaptive Segment-Optimized Pipeline Parallelism for Collaborative LLM Training in Heterogeneous Edge Networks

# 摘要

> 智能移动应用需求的持续增长，使得基于Transformer的大型语言模型（LLMs）的多智能体协作在移动边缘计算（MEC）网络中变得不可或缺。但由于计算负荷重、端到端延迟高以及模型泛化能力有限，在此类环境中训练LLMs仍面临诸多挑战。为此，我们提出了CollaPipe——一种混合分布式学习框架，它将协作式流水线并行与联邦聚合相融合，以支持自进化智能网络。在CollaPipe中，编码器部分被自适应分割为不同大小的段，部署在移动设备上进行流水线并行训练；解码器则部署在边缘服务器，负责处理生成任务。随后，通过联邦聚合完成全局模型更新。为提升训练效率，我们构建了联合优化问题，实现模型段、微批次、带宽及传输功率的自适应分配。我们推导并利用闭式收敛界，设计出基于李雅普诺夫优化的动态段调度与资源分配（DSSDA）算法，确保系统在长期约束下的稳定性。在Transformer和BERT模型的下游任务上进行的大量实验显示，CollaPipe计算效率提升高达15.09%，端到端延迟降低至少48.98%，单设备内存使用减少一半以上，从而实现了异构动态通信环境下的在线学习。

> The increasing demand for intelligent mobile applications has made multi-agent collaboration with Transformer-based large language models (LLMs) essential in mobile edge computing (MEC) networks. However, training LLMs in such environments remains challenging due to heavy computation, high end-to-end latency, and limited model generalization. We introduce CollaPipe, a hybrid distributed learning framework that integrates collaborative pipeline parallelism with federated aggregation to support self-evolving intelligent networks. In CollaPipe, the encoder part is adaptively partitioned into variable-sized segments and deployed across mobile devices for pipeline-parallel training, while the decoder is deployed on edge servers to handle generative tasks. Then we perform global model update via federated aggregation. To enhance training efficiency, we formulate a joint optimization problem that adaptively allocates model segments, micro-batches, bandwidth, and transmission power. We derive and use a closed-form convergence bound to design an Dynamic Segment Scheduling and Resource Allocation (DSSDA) algorithm based on Lyapunov optimization, ensuring system stability under long-term constraints. Extensive experiments on downstream tasks with Transformer and BERT models show that CollaPipe improves computation efficiency by up to 15.09%, reduces end-to-end latency by at least 48.98%, and cuts single device memory usage by more than half, enabling online learning in heterogeneous and dynamic communication environments.

[Arxiv](https://arxiv.org/abs/2509.19855)