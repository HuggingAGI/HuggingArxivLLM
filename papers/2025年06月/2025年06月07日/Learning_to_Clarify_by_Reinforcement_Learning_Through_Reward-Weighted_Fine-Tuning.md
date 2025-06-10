# # Learning to Clarify by Reinforcement Learning Through Reward-Weighted Fine-Tuning  
**通过强化学习，利用奖励加权微调，掌握澄清之道**

发布时间：2025年06月07日

`Agent` `问答系统`

> Learning to Clarify by Reinforcement Learning Through Reward-Weighted Fine-Tuning

# 摘要

> 问答 (QA) 代理能够自动回答以自然语言提出的问题。在本研究中，我们致力于让 QA 代理学会提出澄清性问题。我们的方法的核心思想是模拟包含澄清性问题的对话，并通过强化学习 (RL) 从这些对话中学习。为了使 RL 在实际中可行，我们提出了并分析了离线 RL 目标，这些目标可以被看作是基于奖励加权的监督微调 (SFT)，并且可以在大型语言模型中轻松优化。我们的工作与最近基于 SFT 和直接偏好优化的方法形成鲜明对比，这些方法具有额外的超参数，并且不直接优化奖励。我们通过实证比较了这些方法，并报告了在优化奖励和语言质量方面的提升。

> Question answering (QA) agents automatically answer questions posed in natural language. In this work, we learn to ask clarifying questions in QA agents. The key idea in our method is to simulate conversations that contain clarifying questions and learn from them using reinforcement learning (RL). To make RL practical, we propose and analyze offline RL objectives that can be viewed as reward-weighted supervised fine-tuning (SFT) and easily optimized in large language models. Our work stands in a stark contrast to recently proposed methods, based on SFT and direct preference optimization, which have additional hyper-parameters and do not directly optimize rewards. We compare to these methods empirically and report gains in both optimized rewards and language quality.

[Arxiv](https://arxiv.org/abs/2506.06964)