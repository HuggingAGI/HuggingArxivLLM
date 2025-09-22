# 基于拓扑感知通信对齐在超9600块GPU上高效预训练大型语言模型（LLMs）

发布时间：2025年09月19日

`其他` `基础理论`

> Efficient Pre-Training of LLMs via Topology-Aware Communication Alignment on More Than 9600 GPUs

# 摘要

> 大型语言模型（LLMs）的缩放定律揭示，通往机器智能的道路离不开大规模训练。因此，企业持续搭建大规模GPU集群，部署的训练任务往往横跨数千个计算节点。然而，LLM预训练因其复杂的通信模式面临独特挑战：GPU会在特定组内以稀疏却大容量的突发形式交换数据。低效的资源调度会加剧带宽争抢，进而造成训练性能不理想。本文介绍了Arnold——一个凝聚我们实践经验的调度系统，其核心是在大规模场景下将LLM通信模式与数据中心拓扑结构高效匹配。我们开展了深入的特性分析，明确了物理网络拓扑对LLM预训练任务的影响。基于这些发现，我们设计了一种调度算法，能让通信模式与现代数据中心的物理网络拓扑精准适配。模拟实验显示，该算法可将通信组的最大分布降低至多【数学公式】倍；在实际生产训练中，当使用超过【数学公式】个GPU时，调度系统将端到端性能提升了【数学公式】，为我们的训练流水线带来了显著优化。

> The scaling law for large language models (LLMs) depicts that the path towards machine intelligence necessitates training at large scale. Thus, companies continuously build large-scale GPU clusters, and launch training jobs that span over thousands of computing nodes. However, LLM pre-training presents unique challenges due to its complex communication patterns, where GPUs exchange data in sparse yet high-volume bursts within specific groups. Inefficient resource scheduling exacerbates bandwidth contention, leading to suboptimal training performance. This paper presents Arnold, a scheduling system summarizing our experience to effectively align LLM communication patterns with data center topology at scale. An in-depth characteristic study is performed to identify the impact of physical network topology to LLM pre-training jobs. Based on the insights, we develop a scheduling algorithm to effectively align communication patterns with the physical network topology in modern data centers. Through simulation experiments, we show the effectiveness of our algorithm in reducing the maximum spread of communication groups by up to $1.67$x. In production training, our scheduling system improves the end-to-end performance by $10.6\%$ when training with more than $9600$ GPUs, a significant improvement for our training pipeline.

[Arxiv](https://arxiv.org/abs/2509.15940)