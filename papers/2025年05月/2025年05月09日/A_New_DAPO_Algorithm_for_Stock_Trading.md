# # 股票交易中的新型DAPO算法  
一种新的DAPO算法在股票交易中的应用

发布时间：2025年05月09日

`LLM应用`

> A New DAPO Algorithm for Stock Trading

# 摘要

> 近期强化学习领域取得了显著进展，例如动态采样策略优化（DAPO）等方法，在与大型语言模型（LLMs）结合使用时表现尤为突出。受到这些成功案例的启发，我们不禁思考：类似的提升能否在金融交易领域实现？我们设计了一种交易代理，该代理结合了改进的组相对策略优化（GRPO）算法，并融入了DAPO的思想，同时利用基于LLM的风险和情绪信号（从财经新闻中提取）进行交易决策。在纳斯达克100指数（FNSPID数据集）上，我们的代理实现了230.49%的累计回报率和0.37的信息比率，超越了CPPO-DeepSeek基准模型。此外，该代理将训练时间从约8小时缩短至2.5小时（经过100个纪元），同时显著降低了内存使用。我们提出的RL-LLM框架为构建高效的数据驱动交易代理提供了可扩展的解决方案。代码已开源：https://github.com/Ruijian-Zha/FinRL-DAPO-SR/

> Recent advances in reinforcement learning, such as Dynamic Sampling Policy Optimization (DAPO), show strong performance when paired with large language models (LLMs). Motivated by this success, we ask whether similar gains can be realized in financial trading. We design a trading agent that combines an improved Group Relative Policy Optimization (GRPO) algorithm, augmented with ideas from DAPO, with LLM-based risk and sentiment signals extracted from financial news. On the NASDAQ-100 index (FNSPID dataset), our agent attains a cumulative return of 230.49 percent and an information ratio of 0.37, outperforming the CPPO-DeepSeek baseline. It also cuts training time from about 8 hours to 2.5 hours over 100 epochs while markedly reducing RAM usage. The proposed RL-LLM framework offers a scalable path toward data-efficient trading agents. Code: https://github.com/Ruijian-Zha/FinRL-DAPO-SR/

[Arxiv](https://arxiv.org/abs/2505.06408)