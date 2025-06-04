# Tru-POMDP：基于假设树与开放性POMDP的不确定性任务规划方法

发布时间：2025年06月03日

`Agent

理由：这篇论文探讨了家庭服务机器人在现实环境中的任务规划问题，结合了大型语言模型（LLMs）和基于POMDP的规划方法，提出了一种创新的规划器Tru-POMDP。它主要关注智能体（agent）在不确定性环境中的规划和决策，属于智能体应用的范畴。` `机器人技术` `任务规划`

> Tru-POMDP: Task Planning Under Uncertainty via Tree of Hypotheses and Open-Ended POMDPs

# 摘要

> 在现实世界中运行的家庭服务机器人需要在充满不确定性的环境中进行任务规划。这些任务往往面临模糊的人类指令、未知的对象位置以及多样化对象类型，导致了巨大的开放性不确定性和无限扩展的规划空间。为了解决这些挑战，我们提出了Tru-POMDP，这是一种结合了大型语言模型（LLMs）生成结构化信念与基于POMDP的规划方法的创新规划器。Tru-POMDP通过层次化的假设树（TOH）系统地查询LLM，构建关于可能世界状态和人类目标的高质量粒子信念。我们还设计了一个开放性的POMDP模型，能够在这些LLM生成的假设上实现严格的贝叶斯信念追踪和高效的信念空间规划。在多样化厨房环境下的复杂物体整理任务中进行的实验表明，Tru-POMDP显著优于现有的基于LLM和LLM-树搜索的混合规划器，不仅成功率更高，计划质量更优，而且对模糊性和遮挡的鲁棒性更强，规划效率也显著提升。


> Task planning under uncertainty is essential for home-service robots operating in the real world. Tasks involve ambiguous human instructions, hidden or unknown object locations, and open-vocabulary object types, leading to significant open-ended uncertainty and a boundlessly large planning space. To address these challenges, we propose Tru-POMDP, a planner that combines structured belief generation using Large Language Models (LLMs) with principled POMDP planning. Tru-POMDP introduces a hierarchical Tree of Hypotheses (TOH), which systematically queries an LLM to construct high-quality particle beliefs over possible world states and human goals. We further formulate an open-ended POMDP model that enables rigorous Bayesian belief tracking and efficient belief-space planning over these LLM-generated hypotheses. Experiments on complex object rearrangement tasks across diverse kitchen environments show that Tru-POMDP significantly outperforms state-of-the-art LLM-based and LLM-tree-search hybrid planners, achieving higher success rates with significantly better plans, stronger robustness to ambiguity and occlusion, and greater planning efficiency.

[Arxiv](https://arxiv.org/abs/2506.02860)