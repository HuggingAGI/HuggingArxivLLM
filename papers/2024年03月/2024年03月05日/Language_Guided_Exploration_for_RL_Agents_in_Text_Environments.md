# 针对文本环境中的强化学习（RL）智能体，我们提出语言指导的探索策略，利用自然语言引导智能体在复杂环境中高效探索和学习。

发布时间：2024年03月05日

`Agent`

> Language Guided Exploration for RL Agents in Text Environments

# 摘要

> 面对真实世界序列决策中的稀疏奖励与广阔决策空间难题，经验学习系统如“从零开始”的强化学习（RL）代理面临严峻挑战。而富含世界知识的大型语言模型（LLMs）能有效助力RL代理快速习得技能并适应变化。本研究创新性地提出了Language Guided Exploration（LGE）框架，通过运用预训练的语言模型GUIDE来为RL探索者EXPLORER提供关键决策指引。实验证明，在极具挑战性的文本环境ScienceWorld上，LGE不仅能大幅度超越常规RL代理的表现，而且在与行为克隆、文本决策变换器等精密方法的竞争中同样拔得头筹。

> Real-world sequential decision making is characterized by sparse rewards and large decision spaces, posing significant difficulty for experiential learning systems like $\textit{tabula rasa}$ reinforcement learning (RL) agents. Large Language Models (LLMs), with a wealth of world knowledge, can help RL agents learn quickly and adapt to distribution shifts. In this work, we introduce Language Guided Exploration (LGE) framework, which uses a pre-trained language model (called GUIDE ) to provide decision-level guidance to an RL agent (called EXPLORER). We observe that on ScienceWorld (Wang et al.,2022), a challenging text environment, LGE outperforms vanilla RL agents significantly and also outperforms other sophisticated methods like Behaviour Cloning and Text Decision Transformer.

[Arxiv](https://arxiv.org/abs/2403.03141)