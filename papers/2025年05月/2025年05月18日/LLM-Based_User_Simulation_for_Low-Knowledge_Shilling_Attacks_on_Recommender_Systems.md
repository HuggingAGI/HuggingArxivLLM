# 基于大型语言模型的用户模拟：针对推荐系统中的低知识刷分攻击

发布时间：2025年05月18日

`Agent` `推荐系统`

> LLM-Based User Simulation for Low-Knowledge Shilling Attacks on Recommender Systems

# 摘要

> 推荐系统（RS）正面临日益严峻的投毒攻击威胁，攻击者通过注入虚假用户资料操控系统输出。传统攻击手段往往依赖简单的启发式方法，需要获取推荐系统的内部数据，且忽视了文本评论的操控潜力。本研究提出Agent4SR，一个基于大型语言模型（LLM）的创新框架，通过评分和评论生成实现低知识、高影响力的投毒攻击。Agent4SR模拟真实用户行为，通过编排对抗性交互、选择商品、分配评分和撰写评论，同时保持行为合理性。我们的设计包括目标用户资料构建、混合记忆检索，以及一种评论攻击策略，通过在无关评论中传播目标商品特征放大操控效果。在多个数据集和推荐系统架构上的实验表明，Agent4SR在有效性和隐蔽性方面均优于现有低知识基准方法。我们的研究揭示了由LLM驱动的智能体带来的新兴威胁，凸显了在现代推荐系统中加强防御的迫切需求。

> Recommender systems (RS) are increasingly vulnerable to shilling attacks, where adversaries inject fake user profiles to manipulate system outputs. Traditional attack strategies often rely on simplistic heuristics, require access to internal RS data, and overlook the manipulation potential of textual reviews. In this work, we introduce Agent4SR, a novel framework that leverages Large Language Model (LLM)-based agents to perform low-knowledge, high-impact shilling attacks through both rating and review generation. Agent4SR simulates realistic user behavior by orchestrating adversarial interactions, selecting items, assigning ratings, and crafting reviews, while maintaining behavioral plausibility. Our design includes targeted profile construction, hybrid memory retrieval, and a review attack strategy that propagates target item features across unrelated reviews to amplify manipulation. Extensive experiments on multiple datasets and RS architectures demonstrate that Agent4SR outperforms existing low-knowledge baselines in both effectiveness and stealth. Our findings reveal a new class of emergent threats posed by LLM-driven agents, underscoring the urgent need for enhanced defenses in modern recommender systems.

[Arxiv](https://arxiv.org/abs/2505.13528)