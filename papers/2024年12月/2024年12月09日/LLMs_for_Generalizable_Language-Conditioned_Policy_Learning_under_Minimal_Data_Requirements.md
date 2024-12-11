# LLMs 用于在最小数据需求下的可泛化语言条件策略学习

发布时间：2024年12月09日

`Agent` `自主智能体`

> LLMs for Generalizable Language-Conditioned Policy Learning under Minimal Data Requirements

# 摘要

> 为开发能执行人类以自然语言指定的复杂多步骤决策任务的自主智能体，现有的强化学习方法往往需要昂贵的有标签数据集或实时实验权限。而且，传统方法在推广至未见过的目标和状态时常常遭遇难题，限制了其实用性。本文推出了 TEDUO，这是用于离线语言条件策略学习的全新训练流程。TEDUO 基于易于获取的无标签数据集运行，适用于所谓的野外评估，即智能体碰到此前未曾见过的目标和状态。为应对此类数据和评估设置带来的挑战，我们的方法借助大型语言模型（LLMs）的先验知识和遵循指令的能力，提升预先收集的离线数据的保真度，实现对新目标和状态的灵活推广。实证结果显示，LLMs 在我们的框架中扮演数据增强器和推广器的双重角色，有助于高效且数据高效地学习可推广的语言条件策略。

> To develop autonomous agents capable of executing complex, multi-step decision-making tasks as specified by humans in natural language, existing reinforcement learning approaches typically require expensive labeled datasets or access to real-time experimentation. Moreover, conventional methods often face difficulties in generalizing to unseen goals and states, thereby limiting their practical applicability. This paper presents TEDUO, a novel training pipeline for offline language-conditioned policy learning. TEDUO operates on easy-to-obtain, unlabeled datasets and is suited for the so-called in-the-wild evaluation, wherein the agent encounters previously unseen goals and states. To address the challenges posed by such data and evaluation settings, our method leverages the prior knowledge and instruction-following capabilities of large language models (LLMs) to enhance the fidelity of pre-collected offline data and enable flexible generalization to new goals and states. Empirical results demonstrate that the dual role of LLMs in our framework-as data enhancers and generalizers-facilitates both effective and data-efficient learning of generalizable language-conditioned policies.

[Arxiv](https://arxiv.org/abs/2412.06877)