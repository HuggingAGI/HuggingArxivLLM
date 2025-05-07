# DYSTIL：基于大型语言模型的强化学习动态策略生成

发布时间：2025年05月06日

`LLM应用` `人工智能`

> DYSTIL: Dynamic Strategy Induction with Large Language Models for Reinforcement Learning

# 摘要

> 从专家演示中进行强化学习一直是强化学习领域中的难题。现有的先进方法通常采用行为克隆结合强化学习训练，但往往面临泛化能力差、采样效率低和模型解释性不佳的问题。受大型语言模型（LLMs）的强大推理能力启发，我们提出了一种名为DYSTIL（基于LLMs的动态策略归纳框架）的新型策略强化学习框架，以克服这些限制。DYSTIL通过动态查询一个策略生成的LLM，基于优势估计和专家演示生成文本策略，并通过策略优化逐步将生成的策略内化到强化学习智能体中，从而通过提升策略泛化能力和增强采样效率来改善其性能。它还提供了一个直接的文本通道，用于观察和解释训练过程中策略底层策略的演变。我们在Minigrid和BabyAI的具有挑战性的强化学习环境中测试了DYSTIL，并通过实验证明，DYSTIL在平均成功率上显著优于现有先进基线方法，平均成功率提升了17.75%，同时在学习过程中也具有更高的采样效率。

> Reinforcement learning from expert demonstrations has long remained a challenging research problem, and existing state-of-the-art methods using behavioral cloning plus further RL training often suffer from poor generalization, low sample efficiency, and poor model interpretability. Inspired by the strong reasoning abilities of large language models (LLMs), we propose a novel strategy-based reinforcement learning framework integrated with LLMs called DYnamic STrategy Induction with Llms for reinforcement learning (DYSTIL) to overcome these limitations. DYSTIL dynamically queries a strategy-generating LLM to induce textual strategies based on advantage estimations and expert demonstrations, and gradually internalizes induced strategies into the RL agent through policy optimization to improve its performance through boosting policy generalization and enhancing sample efficiency. It also provides a direct textual channel to observe and interpret the evolution of the policy's underlying strategies during training. We test DYSTIL over challenging RL environments from Minigrid and BabyAI, and empirically demonstrate that DYSTIL significantly outperforms state-of-the-art baseline methods by 17.75% in average success rate while also enjoying higher sample efficiency during the learning process.

[Arxiv](https://arxiv.org/abs/2505.03209)