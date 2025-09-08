# 自举任务空间助力自我提升

发布时间：2025年09月04日

`强化学习` `基础理论`

> Bootstrapping Task Spaces for Self-Improvement

# 摘要

> 许多任务领域的进步，都源于对先前解决方案的反复打磨与修正。训练能在推理时通过这类序列实现可靠自我提升的智能体，是强化学习（RL）的自然目标。然而，传统朴素方法假设固定的最大迭代深度，这种设定既成本高昂又带有随意性。我们提出探索性迭代（ExIt）——一类自动课程强化学习方法。它直接利用自我改进任务的循环结构，训练大型语言模型（LLMs）在推理时执行多步自我改进，同时仅在信息最丰富的单步迭代上进行训练。ExIt通过选择性采样情节中遇到的信息最丰富的中间部分历史来扩展任务空间，以便继续迭代，并将这些起点视为新的自我迭代任务实例，用于训练自我改进策略。ExIt还可以与显式探索机制结合，以维持更丰富的任务多样性。在竞赛数学、多轮工具使用、机器学习工程等多个领域，我们证明：无论是从单个还是多个任务实例起步，ExIt策略都能生成在保留任务实例上表现出强大推理时自我改进能力的策略，并且能在超出训练时平均迭代深度的步骤预算下持续迭代，以实现更高性能。

> Progress in many task domains emerges from repeated revisions to previous solution attempts. Training agents that can reliably self-improve over such sequences at inference-time is a natural target for reinforcement learning (RL), yet the naive approach assumes a fixed maximum iteration depth, which can be both costly and arbitrary. We present Exploratory Iteration (ExIt), a family of autocurriculum RL methods that directly exploits the recurrent structure of self-improvement tasks to train LLMs to perform multi-step self-improvement at inference-time while only training on the most informative single-step iterations. ExIt grows a task space by selectively sampling the most informative intermediate, partial histories encountered during an episode for continued iteration, treating these starting points as new self-iteration task instances to train a self-improvement policy. ExIt can further pair with explicit exploration mechanisms to sustain greater task diversity. Across several domains, encompassing competition math, multi-turn tool-use, and machine learning engineering, we demonstrate that ExIt strategies, starting from either a single or many task instances, can produce policies exhibiting strong inference-time self-improvement on held-out task instances, and the ability to iterate towards higher performance over a step budget extending beyond the average iteration depth encountered during training.

[Arxiv](https://arxiv.org/abs/2509.04575)