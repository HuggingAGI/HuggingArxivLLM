# 通过可扩展的离线强化学习与Transformer打造人类级别的竞技宝可梦

发布时间：2025年04月06日

`Agent` `战略游戏`

> Human-Level Competitive Pokémon via Scalable Offline Reinforcement Learning with Transformers

# 摘要

> # 竞争宝可梦单打（CPS）  
竞争宝可梦单打（CPS）是一款备受喜爱的战略游戏，玩家需在可能持续超过100个随机回合的战斗中，利用不完全信息来击败对手。当前，CPS领域的AI研究主要采用启发式树搜索和在线自对弈技术，但这款游戏也可能为研究基于大型数据集离线训练的自适应策略提供一个理想平台。  
我们开发了一种创新的管道，能够从旁观者视角的日志中重建代理的第一人称视角，从而解锁了一个跨越十多年的大型真实人类战斗数据集，且该数据集每天都在不断增长。这一数据集支持一种黑箱方法，即仅通过输入轨迹来训练大型序列模型，使其能够适应对手，而无需进行任何显式的搜索。  
我们在宝可梦最古老（同时也是部分观测性最强）的四代游戏的硬核竞争环境中，研究了从模仿学习到离线RL，再到基于自对弈数据的离线微调的逐步演进。最终，我们的代理在与近期的LLM代理和强大的启发式搜索引擎的对比中表现更优。当以匿名身份与人类玩家进行在线对战时，我们最强的代理进入了活跃玩家排名的前10%。

> Competitive Pokémon Singles (CPS) is a popular strategy game where players learn to exploit their opponent based on imperfect information in battles that can last more than one hundred stochastic turns. AI research in CPS has been led by heuristic tree search and online self-play, but the game may also create a platform to study adaptive policies trained offline on large datasets. We develop a pipeline to reconstruct the first-person perspective of an agent from logs saved from the third-person perspective of a spectator, thereby unlocking a dataset of real human battles spanning more than a decade that grows larger every day. This dataset enables a black-box approach where we train large sequence models to adapt to their opponent based solely on their input trajectory while selecting moves without explicit search of any kind. We study a progression from imitation learning to offline RL and offline fine-tuning on self-play data in the hardcore competitive setting of Pokémon's four oldest (and most partially observed) game generations. The resulting agents outperform a recent LLM Agent approach and a strong heuristic search engine. While playing anonymously in online battles against humans, our best agents climb to rankings inside the top 10% of active players.

[Arxiv](https://arxiv.org/abs/2504.04395)