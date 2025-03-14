# # Factorio 学习环境

发布时间：2025年03月06日

`LLM应用` `游戏AI` `自动化技术`

> Factorio Learning Environment

# 摘要

> 大型语言模型（LLMs）正在迅速达到现有基准的极限，这促使我们需要新的开放性评估方法。我们引入了基于游戏《Factorio》的Factorio学习环境（FLE），用于测试智能体在长期规划、程序合成和资源优化方面的能力。FLE提供了从基础自动化到每秒处理数百万资源单位的复杂工厂的指数级增长挑战。我们提供了两种设置：（1）实验室模式，包含八个结构化的固定资源任务；（2）开放模式，任务是建造一个在程序生成地图上最大的工厂，任务无限制。我们在两种设置下都证明了模型在空间推理方面仍然存在不足。在实验室模式中，LLMs表现出有前途的短期技能，但无法在受限环境中有效运作，反映出在错误分析方面的局限性。在开放模式中，尽管LLMs发现了提高增长的自动化策略（例如电力钻探），但未能实现复杂的自动化（例如电子电路制造）。

> Large Language Models (LLMs) are rapidly saturating existing benchmarks, necessitating new open-ended evaluations. We introduce the Factorio Learning Environment (FLE), based on the game of Factorio, that tests agents in long-term planning, program synthesis, and resource optimization. FLE provides exponentially scaling challenges -- from basic automation to complex factories processing millions of resource units per second. We provide two settings: (1) lab-play consisting of eight structured tasks with fixed resources, and (2) open-play with the unbounded task of building the largest factory on an procedurally generated map. We demonstrate across both settings that models still lack strong spatial reasoning. In lab-play, we find that LLMs exhibit promising short-horizon skills, yet are unable to operate effectively in constrained environments, reflecting limitations in error analysis. In open-play, while LLMs discover automation strategies that improve growth (e.g electric-powered drilling), they fail to achieve complex automation (e.g electronic-circuit manufacturing).

[Arxiv](https://arxiv.org/abs/2503.09617)