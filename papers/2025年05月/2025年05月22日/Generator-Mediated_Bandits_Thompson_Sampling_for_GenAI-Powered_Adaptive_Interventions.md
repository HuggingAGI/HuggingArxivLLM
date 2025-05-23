# 生成器中介的多臂强盗问题：基于生成AI的自适应干预策略的汤普森采样方法

发布时间：2025年05月22日

`Agent` `移动健康` `个性化决策系统`

> Generator-Mediated Bandits: Thompson Sampling for GenAI-Powered Adaptive Interventions

# 摘要

> 生成式人工智能（GenAI）模型的最新进展使得能够生成适应最新用户情境的个性化内容。在个性化决策系统中，虽然通常使用带宽方法来建模，但GenAI的引入为原本经典的顺序学习问题带来了新的结构。在GenAI驱动的干预中，智能体选择一个查询，但环境会经历一个从生成模型中随机抽取的响应。标准的带宽方法并没有显式地考虑这种结构，其中动作仅通过随机且可观察的治疗来影响奖励。我们提出了基于生成器的带宽-汤普森采样（GAMBITTS），这是一种专为这种动作/治疗分离设计的带宽方法，以大型语言模型生成文本的移动健康干预作为动机案例。GAMBITTS显式地建模了治疗过程和奖励生成过程，并利用交付的治疗信息来加速策略学习，相对于标准方法更为高效。通过分解治疗和奖励中的不确定性来源，我们为GAMBITTS建立了后悔界，并确定了其在某些条件下能够获得比标准带宽方法更强的保证。在模拟研究中，GAMBITTS通过利用观察到的治疗来更准确地估计期望奖励，始终优于传统的算法。

> Recent advances in generative artificial intelligence (GenAI) models have enabled the generation of personalized content that adapts to up-to-date user context. While personalized decision systems are often modeled using bandit formulations, the integration of GenAI introduces new structure into otherwise classical sequential learning problems. In GenAI-powered interventions, the agent selects a query, but the environment experiences a stochastic response drawn from the generative model. Standard bandit methods do not explicitly account for this structure, where actions influence rewards only through stochastic, observed treatments. We introduce generator-mediated bandit-Thompson sampling (GAMBITTS), a bandit approach designed for this action/treatment split, using mobile health interventions with large language model-generated text as a motivating case study. GAMBITTS explicitly models both the treatment and reward generation processes, using information in the delivered treatment to accelerate policy learning relative to standard methods. We establish regret bounds for GAMBITTS by decomposing sources of uncertainty in treatment and reward, identifying conditions where it achieves stronger guarantees than standard bandit approaches. In simulation studies, GAMBITTS consistently outperforms conventional algorithms by leveraging observed treatments to more accurately estimate expected rewards.

[Arxiv](https://arxiv.org/abs/2505.16311)