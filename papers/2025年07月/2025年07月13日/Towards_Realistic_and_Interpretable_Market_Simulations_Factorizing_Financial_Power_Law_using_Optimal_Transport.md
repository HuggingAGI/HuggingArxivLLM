# 构建现实且可解释的市场模拟：基于最优传输方法分解金融幂律

发布时间：2025年07月13日

`其他` `金融市场模拟`

> Towards Realistic and Interpretable Market Simulations: Factorizing Financial Power Law using Optimal Transport

# 摘要

> 我们通过人工市场模拟研究了股票收益幂律分布背后的机制。传统金融理论假设价格波动服从高斯分布，但实证研究一致表明，收益分布的尾部遵循幂律分布。此前研究为这一现象提出了多种假设，有的归因于投资者行为，有的归因于机构需求失衡。然而，这些因素很少被同时建模以评估其单独和联合贡献。真实金融市场的复杂性使得利用现有数据分离单一组件的贡献变得困难。

为解决这一问题，我们构建了人工市场，并使用最优传输（OT）作为定量相似性度量进行受控实验。我们提出的框架逐步将行为成分引入代理模型，使我们能够通过OT距离将每个模拟输出与实证数据进行比较。结果显示，价格的信息效应在再现幂律行为中起主导作用，且多个组件协同互动以放大这一效应。

> We investigate the mechanisms behind the power-law distribution of stock returns using artificial market simulations. While traditional financial theory assumes Gaussian price fluctuations, empirical studies consistently show that the tails of return distributions follow a power law. Previous research has proposed hypotheses for this phenomenon -- some attributing it to investor behavior, others to institutional demand imbalances. However, these factors have rarely been modeled together to assess their individual and joint contributions. The complexity of real financial markets complicates the isolation of the contribution of a single component using existing data. To address this, we construct artificial markets and conduct controlled experiments using optimal transport (OT) as a quantitative similarity measure. Our proposed framework incrementally introduces behavioral components into the agent models, allowing us to compare each simulation output with empirical data via OT distances. The results highlight that informational effect of prices plays a dominant role in reproducing power-law behavior and that multiple components interact synergistically to amplify this effect.

[Arxiv](https://arxiv.org/abs/2507.09863)