# 基于大型语言模型的推荐系统策略探索

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来增强推荐系统中的强化学习策略，特别是在离线预训练和在线环境中的应用。论文提出的方法（iALP和A-iALP）通过LLM提取用户偏好并优化推荐策略，属于LLM在实际应用中的具体使用场景，因此应归类为LLM应用。` `推荐系统`

> Large Language Model driven Policy Exploration for Recommender Systems

# 摘要

> # 摘要
近年来，推荐系统（RS）通过引入强化学习（RL），将推荐问题建模为马尔可夫决策过程（MDP）。然而，基于静态用户数据训练的离线RL策略在动态在线环境中容易受到分布偏移的影响。此外，过度关注短期相关项目的利用可能会阻碍探索，导致次优推荐并影响长期用户收益。在线RL的RS在生产部署中也面临挑战，因为存在将用户暴露于未训练或不稳定策略的风险。大型语言模型（LLMs）为解决这一问题提供了新思路，能够模拟用户目标和偏好，用于离线预训练策略，从而增强在线环境中的初始推荐。有效管理分布偏移和平衡探索对于改进基于RL的RS至关重要，尤其是在利用LLM预训练时。为此，我们提出了一种基于LLM提取用户偏好的交互增强学习策略（iALP）。该方法通过用户状态提示LLM提取项目偏好，基于反馈学习奖励，并使用actor-critic框架更新RL策略。此外，为了在在线场景中部署iALP，我们引入了一种自适应变体A-iALP，包括简单的微调策略（A-iALP$_{ft}$）和自适应方法（A-iALP$_{ap}$），旨在缓解策略受损和探索受限的问题。在三个模拟环境中的实验表明，A-iALP显著提升了性能。

> Recent advancements in Recommender Systems (RS) have incorporated Reinforcement Learning (RL), framing the recommendation as a Markov Decision Process (MDP). However, offline RL policies trained on static user data are vulnerable to distribution shift when deployed in dynamic online environments. Additionally, excessive focus on exploiting short-term relevant items can hinder exploration, leading to suboptimal recommendations and negatively impacting long-term user gains. Online RL-based RS also face challenges in production deployment, due to the risks of exposing users to untrained or unstable policies. Large Language Models (LLMs) offer a promising solution to mimic user objectives and preferences for pre-training policies offline to enhance the initial recommendations in online settings. Effectively managing distribution shift and balancing exploration are crucial for improving RL-based RS, especially when leveraging LLM-based pre-training. To address these challenges, we propose an Interaction-Augmented Learned Policy (iALP) that utilizes user preferences distilled from an LLM. Our approach involves prompting the LLM with user states to extract item preferences, learning rewards based on feedback, and updating the RL policy using an actor-critic framework. Furthermore, to deploy iALP in an online scenario, we introduce an adaptive variant, A-iALP, that implements a simple fine-tuning strategy (A-iALP$_{ft}$), and an adaptive approach (A-iALP$_{ap}$) designed to mitigate issues with compromised policies and limited exploration. Experiments across three simulated environments demonstrate that A-iALP introduces substantial performance improvements

[Arxiv](https://arxiv.org/abs/2501.13816)