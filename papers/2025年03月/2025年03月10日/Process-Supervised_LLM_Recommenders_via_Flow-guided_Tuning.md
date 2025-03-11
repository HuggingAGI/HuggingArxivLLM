# 基于流指导调优的流程监督LLM推荐器

发布时间：2025年03月10日

`LLM应用` `推荐系统` `个性化推荐`

> Process-Supervised LLM Recommenders via Flow-guided Tuning

# 摘要

> 虽然大型语言模型（LLMs）越来越多地被应用于推荐系统中，但传统的监督微调（SFT）方法由于其最大似然目标，容易放大流行度偏差，影响推荐的多样性和公平性。为了解决这一问题，我们提出了基于流指导的微调推荐器（Flower），它通过生成流网络（GFlowNet）框架替换了传统的SFT方法，该框架通过令牌级别的奖励传播实施过程监督。Flower的核心创新在于将项目级别的奖励分解为构成令牌的奖励，从而实现令牌生成概率与其奖励信号的直接对齐。这种机制带来了三个关键进展：（1）通过经验分布匹配缓解流行度偏差并增强公平性，（2）通过GFlowNet的比例采样保持多样性，（3）通过可调节的令牌奖励灵活整合个性化偏好。实验结果表明，Flower在分布拟合能力、公平性、多样性和准确性方面都优于传统的SFT方法，展示了其在提升基于LLM的推荐系统方面的潜力。代码实现已开源，可通过https://github.com/Mr-Peach0301/Flower获取。

> While large language models (LLMs) are increasingly adapted for recommendation systems via supervised fine-tuning (SFT), this approach amplifies popularity bias due to its likelihood maximization objective, compromising recommendation diversity and fairness. To address this, we present Flow-guided fine-tuning recommender (Flower), which replaces SFT with a Generative Flow Network (GFlowNet) framework that enacts process supervision through token-level reward propagation. Flower's key innovation lies in decomposing item-level rewards into constituent token rewards, enabling direct alignment between token generation probabilities and their reward signals. This mechanism achieves three critical advancements: (1) popularity bias mitigation and fairness enhancement through empirical distribution matching, (2) preservation of diversity through GFlowNet's proportional sampling, and (3) flexible integration of personalized preferences via adaptable token rewards. Experiments demonstrate Flower's superior distribution-fitting capability and its significant advantages over traditional SFT in terms of fairness, diversity, and accuracy, highlighting its potential to improve LLM-based recommendation systems. The implementation is available via https://github.com/Mr-Peach0301/Flower

[Arxiv](https://arxiv.org/abs/2503.07377)