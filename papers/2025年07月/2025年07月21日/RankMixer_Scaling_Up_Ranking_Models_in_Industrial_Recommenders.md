# RankMixer：工业推荐系统中排名模型的规模化提升

发布时间：2025年07月21日

`LLM应用` `推荐系统` `广告技术`

> RankMixer: Scaling Up Ranking Models in Industrial Recommenders

# 摘要

> 大规模语言模型（LLMs）的最新进展激发了人们对扩展推荐系统的浓厚兴趣。然而，实践中仍面临两大挑战：工业级推荐系统的训练和服务必须满足严格的延迟限制和高吞吐量需求；传统排名模型中的特征交叉模块大多基于CPU时代设计，无法充分利用现代GPU算力，导致低计算效率（MFU）和较差的扩展性。为此，我们提出了RankMixer——一种专为统一且可扩展特征交互架构设计的硬件感知模型。RankMixer继承了Transformer的高并行性优势，创新性地以多头Token混合模块替代了传统的二次自注意力机制，显著提升了计算效率。同时，RankMixer通过Per-token FFNs实现了特征子空间建模与跨空间交互的完美结合。我们进一步通过稀疏MoE变体将其扩展至十亿参数规模，以提升模型的投资回报率。针对专家训练中的不足与不平衡问题，我们引入了动态路由策略。实验结果表明，RankMixer在万亿规模的生产数据集上展现了卓越的扩展能力。通过将传统低效特征模块替换为RankMixer，我们成功将模型MFU从4.5%提升至45%，并将排名模型的参数规模扩大100倍，同时保持了推理延迟的稳定。通过在推荐、广告和搜索三大核心场景中的在线A/B测试，我们验证了RankMixer的广泛适用性。最终，我们成功部署了10亿密集参数的RankMixer模型进行全流量服务，不仅未增加服务成本，还实现了用户活跃天数提升0.2%和应用内总使用时长增加0.5%的显著效果。

> Recent progress on large language models (LLMs) has spurred interest in scaling up recommendation systems, yet two practical obstacles remain. First, training and serving cost on industrial Recommenders must respect strict latency bounds and high QPS demands. Second, most human-designed feature-crossing modules in ranking models were inherited from the CPU era and fail to exploit modern GPUs, resulting in low Model Flops Utilization (MFU) and poor scalability. We introduce RankMixer, a hardware-aware model design tailored towards a unified and scalable feature-interaction architecture. RankMixer retains the transformer's high parallelism while replacing quadratic self-attention with multi-head token mixing module for higher efficiency. Besides, RankMixer maintains both the modeling for distinct feature subspaces and cross-feature-space interactions with Per-token FFNs. We further extend it to one billion parameters with a Sparse-MoE variant for higher ROI. A dynamic routing strategy is adapted to address the inadequacy and imbalance of experts training. Experiments show RankMixer's superior scaling abilities on a trillion-scale production dataset. By replacing previously diverse handcrafted low-MFU modules with RankMixer, we boost the model MFU from 4.5% to 45%, and scale our ranking model parameters by 100x while maintaining roughly the same inference latency. We verify RankMixer's universality with online A/B tests across three core application scenarios (Recommendation, Advertisement and Search). Finally, we launch 1B Dense-Parameters RankMixer for full traffic serving without increasing the serving cost, which improves user active days by 0.2% and total in-app usage duration by 0.5%.

[Arxiv](https://arxiv.org/abs/2507.15551)