# # 面向机器学习工程智能体的强化学习

发布时间：2025年09月01日

`强化学习` `基础理论`

> Reinforcement Learning for Machine Learning Engineering Agents

# 摘要

> 现有解决机器学习工程等任务的智能体依赖提示强大的语言模型，因此无法通过积累经验实现自我提升。本文研究表明，基于较弱模型并通过强化学习（RL）持续改进的智能体，性能可超越依赖更大但静态模型的智能体。我们发现该场景下RL面临两大核心挑战：其一，智能体的动作执行时长存在差异（例如，为不同解决方案运行代码），这会导致异步策略梯度更新偏向执行更快但质量较差的次优解。为此，我们提出在分布式异步RL框架中引入时长感知梯度更新机制，以强化高成本但高回报的动作学习。其二，仅将测试集性能作为奖励信号会导致反馈不足——几乎正确的程序与彻底失败的程序被同等对待。我们设计了环境工具化方案来提供部分奖励，将“差一点正确”的程序与早期失败（如数据加载阶段）的程序区分开：该工具化方法通过独立的静态语言模型在程序中插入打印语句，记录智能体的实验进展，进而从中提取部分奖励作为学习信号。在机器学习工程基准（MLEBench）上的实验显示，通过RL训练的小模型（Qwen2.5-3B）进行梯度更新后，在12个Kaggle任务中平均超越使用智能体框架提示的大模型（Claude-3.5-Sonnet）达22%。

> Existing agents for solving tasks such as ML engineering rely on prompting powerful language models. As a result, these agents do not improve with more experience. In this paper, we show that agents backed by weaker models that improve via reinforcement learning (RL) can outperform agents backed by much larger, but static models. We identify two major challenges with RL in this setting. First, actions can take a variable amount of time (e.g., executing code for different solutions), which leads to asynchronous policy gradient updates that favor faster but suboptimal solutions. To tackle variable-duration actions, we propose duration- aware gradient updates in a distributed asynchronous RL framework to amplify high-cost but high-reward actions. Second, using only test split performance as a reward provides limited feedback. A program that is nearly correct is treated the same as one that fails entirely. To address this, we propose environment instrumentation to offer partial credit, distinguishing almost-correct programs from those that fail early (e.g., during data loading). Environment instrumentation uses a separate static language model to insert print statement to an existing program to log the agent's experimental progress, from which partial credit can be extracted as reward signals for learning. Our experimental results on MLEBench suggest that performing gradient updates on a much smaller model (Qwen2.5-3B) trained with RL outperforms prompting a much larger model (Claude-3.5-Sonnet) with agent scaffolds, by an average of 22% across 12 Kaggle tasks.

[Arxiv](https://arxiv.org/abs/2509.01684)