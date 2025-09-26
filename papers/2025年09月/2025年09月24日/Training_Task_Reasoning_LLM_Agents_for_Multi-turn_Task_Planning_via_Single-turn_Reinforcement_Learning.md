# 基于单轮强化学习训练任务推理LLM智能体以实现多轮任务规划

发布时间：2025年09月24日

`Agent` `基础理论`

> Training Task Reasoning LLM Agents for Multi-turn Task Planning via Single-turn Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）在知识获取、推理与工具使用方面表现卓越，因此成为自主智能体应用的理想之选。然而，训练LLM智能体执行复杂的多轮任务规划时，面临着稀疏回合奖励、长时程信用分配难题，以及多轮交互场景下强化学习计算开销大等显著挑战。为此，本文提出一种新颖方法，将多轮任务规划转化为单轮任务推理问题，并通过组相对策略优化（GRPO）实现高效策略优化——该方法利用专家轨迹提供密集且可验证的奖励。理论分析表明，GRPO在单轮任务推理上的改进不仅能在最少回合内提升多轮任务成功率，还能泛化至更短时程的子任务。在复杂任务规划基准上的实验评估显示，我们采用单轮GRPO训练的15亿参数模型，性能优于最大140亿参数的基线模型，在超过30步的长时程规划任务中成功率达70%。此外，我们还从理论与实证层面验证了其强大的跨任务泛化能力——训练于复杂任务的模型能够成功完成所有更简单的子任务。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in knowledge acquisition, reasoning, and tool use, making them promising candidates for autonomous agent applications. However, training LLM agents for complex multi-turn task planning faces significant challenges, including sparse episode-wise rewards, credit assignment across long horizons, and the computational overhead of reinforcement learning in multi-turn interaction settings. To this end, this paper introduces a novel approach that transforms multi-turn task planning into single-turn task reasoning problems, enabling efficient policy optimization through Group Relative Policy Optimization (GRPO) with dense and verifiable reward from expert trajectories. Our theoretical analysis shows that GRPO improvement on single-turn task reasoning results in higher multi-turn success probability under the minimal turns, as well as the generalization to subtasks with shorter horizons. Experimental evaluation on the complex task planning benchmark demonstrates that our 1.5B parameter model trained with single-turn GRPO achieves superior performance compared to larger baseline models up to 14B parameters, with success rates of 70% for long-horizon planning tasks with over 30 steps. We also theoretically and empirically validate the strong cross-task generalizability that the models trained on complex tasks can lead to the successful completion of all simpler subtasks.

[Arxiv](https://arxiv.org/abs/2509.20616)