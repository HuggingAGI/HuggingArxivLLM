# 无线接入网络中强化学习的泛化能力研究

发布时间：2025年07月09日

`其他` `无线通信` `通信网络`

> Generalization in Reinforcement Learning for Radio Access Networks

# 摘要

> # 摘要
现代无线接入网络（RAN）运行在高度动态且异构的环境中，传统手动调优的基于规则的无线资源管理（RRM）算法在此环境下表现不佳。虽然强化学习（RL）在受限场景下能超越这些启发式方法，但部署环境的多样性与不可预测的无线条件带来了显著的泛化挑战。数据驱动的策略往往过度拟合训练条件，在未知场景下性能会下降。

为解决这一问题，我们提出了一种以泛化为中心的RL框架用于RAN控制，该框架包含以下三个特点：(i) 通过基于注意力的图表示对小区拓扑和节点属性进行编码；(ii) 应用领域随机化以拓宽训练分布；(iii) 在多个执行器上分散数据生成，同时在与O-RAN原则一致的云兼容架构中集中训练。

尽管泛化会增加计算和数据管理的复杂性，但我们的分布式设计通过在多样化的网络条件下扩展数据收集和训练来缓解这一问题。在五个5G基准测试中应用下行链路自适应，我们的策略在全缓冲MIMO/mMIMO场景下平均吞吐量和频谱效率提升了约10%（10% BLER目标），在高移动性场景下提升超过20%。它在全缓冲流量场景下与专用RL相匹配，并在增强型移动宽带（eMBB）和混合流量基准测试中分别实现了4倍和2倍的增益。在九小区部署中，GAT模型的吞吐量比MLP基线高出30%。这些结果，结合我们可扩展的架构，为使用单一可泛化的RL代理实现原生AI的6G RAN提供了一条路径。

> Modern RAN operate in highly dynamic and heterogeneous environments, where hand-tuned, rule-based RRM algorithms often underperform. While RL can surpass such heuristics in constrained settings, the diversity of deployments and unpredictable radio conditions introduce major generalization challenges. Data-driven policies frequently overfit to training conditions, degrading performance in unseen scenarios. To address this, we propose a generalization-centered RL framework for RAN control that: (i) encodes cell topology and node attributes via attention-based graph representations; (ii) applies domain randomization to broaden the training distribution; and (iii) distributes data generation across multiple actors while centralizing training in a cloud-compatible architecture aligned with O-RAN principles. Although generalization increases computational and data-management complexity, our distributed design mitigates this by scaling data collection and training across diverse network conditions. Applied to downlink link adaptation in five 5G benchmarks, our policy improves average throughput and spectral efficiency by ~10% over an OLLA baseline (10% BLER target) in full-buffer MIMO/mMIMO and by >20% under high mobility. It matches specialized RL in full-buffer traffic and achieves up to 4- and 2-fold gains in eMBB and mixed-traffic benchmarks, respectively. In nine-cell deployments, GAT models offer 30% higher throughput over MLP baselines. These results, combined with our scalable architecture, offer a path toward AI-native 6G RAN using a single, generalizable RL agent.

[Arxiv](https://arxiv.org/abs/2507.06602)