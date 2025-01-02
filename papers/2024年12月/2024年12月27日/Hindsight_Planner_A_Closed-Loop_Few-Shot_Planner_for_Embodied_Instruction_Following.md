# Hindsight Planner：一款用于具身指令跟随的闭环少样本规划工具

发布时间：2024年12月27日

`Agent` `人工智能` `任务规划`

> Hindsight Planner: A Closed-Loop Few-Shot Planner for Embodied Instruction Following

# 摘要

> 这项工作致力于运用大型语言模型（LLMs）为具身指令跟随（EIF）打造任务规划器。以往的工作通常训练规划器去模仿专家轨迹，将此视作监督任务。尽管这些方法能获得不错的性能表现，但往往欠缺足够的稳健性。一旦采取了次优行动，规划器就可能遭遇分布外状态，进而导致任务失败。与此不同，我们把任务设定为部分可观测马尔可夫决策过程（POMDP），并期望在少样本假设下开发出稳健的规划器。于是，我们提出了带有适应模块和创新后见之明方法的闭环规划器，旨在尽可能利用更多信息来辅助规划器。我们在ALFRED数据集上的实验显示，我们的规划器在少样本假设下表现出色。我们的少样本代理的性能首次接近甚至超越了全样本监督代理的性能。

> This work focuses on building a task planner for Embodied Instruction Following (EIF) using Large Language Models (LLMs). Previous works typically train a planner to imitate expert trajectories, treating this as a supervised task. While these methods achieve competitive performance, they often lack sufficient robustness. When a suboptimal action is taken, the planner may encounter an out-of-distribution state, which can lead to task failure. In contrast, we frame the task as a Partially Observable Markov Decision Process (POMDP) and aim to develop a robust planner under a few-shot assumption. Thus, we propose a closed-loop planner with an adaptation module and a novel hindsight method, aiming to use as much information as possible to assist the planner. Our experiments on the ALFRED dataset indicate that our planner achieves competitive performance under a few-shot assumption. For the first time, our few-shot agent's performance approaches and even surpasses that of the full-shot supervised agent.

[Arxiv](https://arxiv.org/abs/2412.19562)