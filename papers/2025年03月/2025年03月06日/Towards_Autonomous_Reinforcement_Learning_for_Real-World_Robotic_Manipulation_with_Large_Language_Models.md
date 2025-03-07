# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月06日

`LLM应用` `机器人` `自动化`

> Towards Autonomous Reinforcement Learning for Real-World Robotic Manipulation with Large Language Models

# 摘要

> 大型语言模型（LLMs）和视觉语言模型（VLMs）的最新进展为机器人领域的高层语义运动规划应用带来了重大突破。强化学习（RL）作为一种互补范式，使智能体能够通过与环境的交互和奖励信号自主优化复杂行为。然而，为RL设计有效的奖励函数仍然是一个难题，尤其是在现实任务中，稀疏奖励往往无法满足需求，而密集奖励的设计则需要复杂的过程。针对这一挑战，我们提出了一种名为自主强化学习的复杂人机交互环境（ARCHIE）的无监督流水线。该方法利用预训练的大型语言模型GPT-4，直接从自然语言任务描述中生成奖励函数。这些奖励函数被用于训练强化学习智能体在模拟环境中执行任务，我们对奖励生成过程进行了形式化处理，以提升其可行性。此外，GPT-4还实现了任务成功标准的自动化编码，从而形成了一种完全自动化、一次性将可读文本转化为可部署机器人技能的流程。我们通过在ABB YuMi协作机器人上进行广泛的模拟实验，验证了本方法在单臂和双臂操作任务中的实用性和有效性。所有任务均在真实机器人平台上进行了演示，进一步证明了其实际应用价值。


> Recent advancements in Large Language Models (LLMs) and Visual Language Models (VLMs) have significantly impacted robotics, enabling high-level semantic motion planning applications. Reinforcement Learning (RL), a complementary paradigm, enables agents to autonomously optimize complex behaviors through interaction and reward signals. However, designing effective reward functions for RL remains challenging, especially in real-world tasks where sparse rewards are insufficient and dense rewards require elaborate design. In this work, we propose Autonomous Reinforcement learning for Complex HumanInformed Environments (ARCHIE), an unsupervised pipeline leveraging GPT-4, a pre-trained LLM, to generate reward functions directly from natural language task descriptions. The rewards are used to train RL agents in simulated environments, where we formalize the reward generation process to enhance feasibility. Additionally, GPT-4 automates the coding of task success criteria, creating a fully automated, one-shot procedure for translating human-readable text into deployable robot skills. Our approach is validated through extensive simulated experiments on single-arm and bi-manual manipulation tasks using an ABB YuMi collaborative robot, highlighting its practicality and effectiveness. Tasks are demonstrated on the real robot setup.

[Arxiv](https://arxiv.org/abs/2503.04280)