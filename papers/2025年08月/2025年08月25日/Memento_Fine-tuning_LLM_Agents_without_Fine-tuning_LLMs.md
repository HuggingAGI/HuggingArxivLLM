# Memento：无需微调LLM即可微调LLM智能体

发布时间：2025年08月25日

`Agent` `基础理论`

> Memento: Fine-tuning LLM Agents without Fine-tuning LLMs

# 摘要

> 本文提出了一种适用于自适应大型语言模型（LLM）智能体的新型学习范式，无需对底层LLM进行微调。现有方法往往要么过于僵化，依赖静态手工设计的反思流程，要么计算成本高昂，需要对LLM模型参数进行梯度更新。相比之下，我们的方法通过基于记忆的在线强化学习，实现了低成本的持续适应。我们将其形式化为记忆增强马尔可夫决策过程（M-MDP），并配备神经案例选择策略以指导动作决策。过去的经验存储在情景记忆中，该记忆可以是可微的或非参数的。策略通过记忆重写机制根据环境反馈持续更新，而策略改进则通过高效的记忆读取（检索）实现。我们在深度研究场景中实例化了智能体模型，命名为\emph{Memento}，该模型在GAIA验证集上达到top-1（87.88% Pass@3），测试集准确率达79.40%；在DeepResearcher数据集上，F1分数达66.6%、PM达80.4%，性能超过最先进的基于训练的方法；同时，基于案例的记忆在分布外任务上带来了4.7%至9.6%的绝对分数提升。我们的方法为开发无需梯度更新即可持续实时学习的通用LLM智能体提供了可扩展且高效的途径，推动机器学习向开放式技能获取和深度研究场景迈进。代码可访问https://github.com/Agent-on-the-Fly/Memento获取。

> In this paper, we introduce a novel learning paradigm for Adaptive Large Language Model (LLM) agents that eliminates the need for fine-tuning the underlying LLMs. Existing approaches are often either rigid, relying on static, handcrafted reflection workflows, or computationally intensive, requiring gradient updates of LLM model parameters. In contrast, our method enables low-cost continual adaptation via memory-based online reinforcement learning. We formalise this as a Memory-augmented Markov Decision Process (M-MDP), equipped with a neural case-selection policy to guide action decisions. Past experiences are stored in an episodic memory, either differentiable or non-parametric. The policy is continually updated based on environmental feedback through a memory rewriting mechanism, whereas policy improvement is achieved through efficient memory reading (retrieval). We instantiate our agent model in the deep research setting, namely \emph{Memento}, which attains top-1 on GAIA validation ($87.88\%$ Pass@$3$) and $79.40\%$ on the test set. It reaches $66.6\%$ F1 and $80.4\%$ PM on the DeepResearcher dataset, outperforming the state-of-the-art training-based method, while case-based memory adds $4.7\%$ to $9.6\%$ absolute points on out-of-distribution tasks. Our approach offers a scalable and efficient pathway for developing generalist LLM agents capable of continuous, real-time learning without gradient updates, advancing machine learning towards open-ended skill acquisition and deep research scenarios. The code is available at https://github.com/Agent-on-the-Fly/Memento.

[Arxiv](https://arxiv.org/abs/2508.16153)