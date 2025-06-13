# 跨多样团队策略泛化能力的基准测试：在竞技宝可梦中的研究

发布时间：2025年06月11日

`Agent` `多智能体学习`

> A Benchmark for Generalizing Across Diverse Team Strategies in Competitive Pokémon

# 摘要

> 如何让AI代理无需重新训练就能稳健适应截然不同的战略环境，是多智能体学习领域的重要挑战。宝可梦视频游戏锦标赛（VGC）正是这样一个极具代表性的领域，其团队配置的可能组合空间高达约$10^{139}$，远超Dota或星际争霸的规模。宝可梦VGC中团队构建的高离散性和组合性导致最优策略会因自身团队和对手团队的不同而发生显著变化，这使得策略泛化面临独特挑战。

为推动这一问题的研究，我们推出了VGC-Bench：一个提供关键基础设施、标准化评估协议、以及包含人类对战数据和多种基线方法的基准测试平台，涵盖从大型语言模型代理和行为克隆到强化学习和经验博弈论方法（如自对弈、虚拟对弈和双Oracle）等多种技术。在仅针对单一团队配置进行训练和评估的受限设置下，我们的方法能够击败职业VGC选手。

我们对所有基线方法进行了全面评估，测试范围覆盖了从小型到大型的团队配置，发现即使是在单一团队设置下表现最佳的算法，在面对团队规模扩大时也会遇到显著的性能瓶颈。因此，跨多种团队策略的策略泛化仍然是一个开放的挑战。

我们的代码已开源，地址为https://github.com/cameronangliss/VGC-Bench。

> Developing AI agents that can robustly adapt to dramatically different strategic landscapes without retraining is a central challenge for multi-agent learning. Pokémon Video Game Championships (VGC) is a domain with an extraordinarily large space of possible team configurations of approximately $10^{139}$ - far larger than those of Dota or Starcraft. The highly discrete, combinatorial nature of team building in Pokémon VGC causes optimal strategies to shift dramatically depending on both the team being piloted and the opponent's team, making generalization uniquely challenging. To advance research on this problem, we introduce VGC-Bench: a benchmark that provides critical infrastructure, standardizes evaluation protocols, and supplies human-play datasets and a range of baselines - from large-language-model agents and behavior cloning to reinforcement learning and empirical game-theoretic methods such as self-play, fictitious play, and double oracle. In the restricted setting where an agent is trained and evaluated on a single-team configuration, our methods are able to win against a professional VGC competitor. We extensively evaluated all baseline methods over progressively larger team sets and find that even the best-performing algorithm in the single-team setting struggles at scaling up as team size grows. Thus, policy generalization across diverse team strategies remains an open challenge for the community. Our code is open sourced at https://github.com/cameronangliss/VGC-Bench.

[Arxiv](https://arxiv.org/abs/2506.10326)