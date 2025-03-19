# 基于LLM的MARL系统指导方案

发布时间：2025年03月16日

`Agent` `人工智能` `智能体系统`

> LLM-Mediated Guidance of MARL Systems

# 摘要

> 在复杂的多智能体环境中，多智能体强化学习（MARL）系统实现高效学习和理想行为面临重大挑战。本研究探索了将MARL与大型语言模型（LLM）介导的干预相结合的潜力，以引导智能体走向更理想的行为模式。具体而言，我们研究了如何利用LLMs来解释和促进干预，从而塑造多个智能体的学习轨迹。

我们试验了两种类型的干预，称为控制器：自然语言（NL）控制器和基于规则（RB）控制器。NL控制器使用LLM来模拟人类似乎的干预，显示出比RB控制器更强的影响。我们的研究发现，智能体特别受益于早期干预，从而实现更高效的训练和更高的性能。两种干预类型均优于无干预的基线，凸显了基于LLM的指导在加速训练和提升复杂环境下MARL性能方面的潜力。

> In complex multi-agent environments, achieving efficient learning and desirable behaviours is a significant challenge for Multi-Agent Reinforcement Learning (MARL) systems. This work explores the potential of combining MARL with Large Language Model (LLM)-mediated interventions to guide agents toward more desirable behaviours. Specifically, we investigate how LLMs can be used to interpret and facilitate interventions that shape the learning trajectories of multiple agents. We experimented with two types of interventions, referred to as controllers: a Natural Language (NL) Controller and a Rule-Based (RB) Controller. The NL Controller, which uses an LLM to simulate human-like interventions, showed a stronger impact than the RB Controller. Our findings indicate that agents particularly benefit from early interventions, leading to more efficient training and higher performance. Both intervention types outperform the baseline without interventions, highlighting the potential of LLM-mediated guidance to accelerate training and enhance MARL performance in challenging environments.

[Arxiv](https://arxiv.org/abs/2503.13553)