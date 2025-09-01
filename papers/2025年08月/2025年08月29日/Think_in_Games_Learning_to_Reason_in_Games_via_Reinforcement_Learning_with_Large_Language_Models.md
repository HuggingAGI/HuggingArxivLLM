# 游戏思维：借助大型语言模型的强化学习在游戏中学习推理

发布时间：2025年08月29日

`Agent` `媒体与娱乐`

> Think in Games: Learning to Reason in Games via Reinforcement Learning with Large Language Models

# 摘要

> 大型语言模型（LLMs）在数学、编码等复杂推理任务上表现卓越，却常常在幼儿都能轻松搞定的简单交互任务上栽跟头。这种反差凸显了陈述性知识（“知道是什么”）与程序性知识（“知道怎么做”）之间的关键鸿沟。传统强化学习（RL）智能体虽能通过环境交互习得程序性知识，却往往是“黑箱”操作，还需海量训练数据；相比之下，LLMs虽坐拥海量世界知识和推理能力，却难以在交互场景中将静态知识有效转化为动态决策。为解决这一难题，我们提出“游戏思维”（TiG）框架——一种让LLMs通过与游戏环境直接交互培养程序性理解，同时保留其天生推理与解释能力的全新方案。具体来说，TiG将强化学习决策重构为语言建模任务：LLMs生成语言引导策略，再通过环境反馈驱动的在线强化学习对其进行迭代优化。实验结果显示，TiG成功弥合了陈述性与程序性知识的鸿沟，且相比传统强化学习方法，在数据和计算量需求大幅降低的情况下，仍达到了具有竞争力的性能。此外，TiG还能为决策过程提供逐步骤的自然语言解释，大幅提升了复杂交互任务的透明度与可解释性。

> Large language models (LLMs) excel at complex reasoning tasks such as mathematics and coding, yet they frequently struggle with simple interactive tasks that young children perform effortlessly. This discrepancy highlights a critical gap between declarative knowledge (knowing about something) and procedural knowledge (knowing how to do something). Although traditional reinforcement learning (RL) agents can acquire procedural knowledge through environmental interaction, they often operate as black boxes and require substantial training data. In contrast, LLMs possess extensive world knowledge and reasoning capabilities, but are unable to effectively convert this static knowledge into dynamic decision-making in interactive settings. To address this challenge, we propose Think in Games (TiG), a novel framework that empowers LLMs to develop procedural understanding through direct interaction with game environments, while retaining their inherent reasoning and explanatory abilities. Specifically, TiG reformulates RL-based decision-making as a language modeling task: LLMs generate language-guided policies, which are refined iteratively through online reinforcement learning based on environmental feedback. Our experimental results show that TiG successfully bridges the gap between declarative and procedural knowledge, achieving competitive performance with dramatically lower data and computational demands compared to conventional RL methods. Moreover, TiG provides step-by-step natural language explanations for its decisions, greatly improving transparency and interpretability in complex interactive tasks.

[Arxiv](https://arxiv.org/abs/2508.21365)