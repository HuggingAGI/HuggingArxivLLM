# 群体期望策略优化：面向大型语言模型的稳定异构强化学习

发布时间：2025年08月25日

`强化学习` `基础理论`

> Group Expectation Policy Optimization for Stable Heterogeneous Reinforcement Learning in LLMs

# 摘要

> 随着单中心计算逐渐触及算力瓶颈，去中心化训练已成为必然趋势。强化学习（RL）后训练虽能提升大型语言模型（LLMs）性能，但因其采样与学习过程紧密耦合，在异构分布式环境中遭遇瓶颈。为此，我们提出HeteroRL——一种异步RL架构，通过解耦轨迹采样与参数学习，实现了在网络延迟下于地理分布式节点的稳健部署。我们发现，延迟引发的KL散度会因高方差导致重要性采样失效。为解决这一问题，我们提出组期望策略优化（GEPO），通过改进的采样机制有效降低重要性权重方差。理论分析表明，GEPO可实现指数级方差降低。实验结果显示，相比GRPO等方法，GEPO稳定性更优，即便在1800秒延迟下性能下降仍不足3%，充分证明了其在异构网络中去中心化RL的巨大潜力。

> As single-center computing approaches power constraints, decentralized training is becoming essential. Reinforcement Learning (RL) post-training enhances Large Language Models (LLMs) but faces challenges in heterogeneous distributed environments due to its tightly-coupled sampling-learning alternation. We propose HeteroRL, an asynchronous RL architecture that decouples rollout sampling from parameter learning, enabling robust deployment across geographically distributed nodes under network delays. We identify that latency-induced KL divergence causes importance sampling failure due to high variance. To address this, we propose Group Expectation Policy Optimization (GEPO), which reduces importance weight variance through a refined sampling mechanism. Theoretically, GEPO achieves exponential variance reduction. Experiments show it maintains superior stability over methods like GRPO, with less than 3% performance degradation under 1800-second delays, demonstrating strong potential for decentralized RL in heterogeneous networks.

[Arxiv](https://arxiv.org/abs/2508.17850)