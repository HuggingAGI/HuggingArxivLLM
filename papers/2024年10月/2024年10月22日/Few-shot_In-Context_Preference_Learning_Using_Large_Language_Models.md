# 基于大型语言模型的少样本上下文偏好学习

发布时间：2024年10月22日

`Agent

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来加速从人类偏好中学习奖励函数的过程，并提出了ICPL方法。该方法通过生成和优化奖励函数来提升强化学习中的效率。虽然涉及LLM的应用，但其核心在于强化学习中的奖励函数设计，属于智能体（Agent）的范畴，因此分类为Agent。` `人工智能`

> Few-shot In-Context Preference Learning Using Large Language Models

# 摘要

> # 摘要
设计奖励函数是强化学习的核心，但在处理复杂行为时往往颇具挑战。RLHF通过从人类偏好中学习奖励函数，取代了手工编码的奖励函数，从而缓解了这一难题。然而，由于这些奖励通常是从零开始学习的，效率往往较低。我们探索了LLMs是否能够通过将一系列人类偏好转化为奖励代码来提升效率。为此，我们提出了ICPL方法，利用LLM的基础能力，加速从偏好中学习奖励函数。ICPL通过环境上下文和任务描述生成奖励函数，并基于人类对策略视频的排名不断优化这些函数。实验表明，ICPL的效率远超RLHF，甚至能与使用真实奖励函数的方法一较高下。此外，我们在人类参与的实验中验证了ICPL的有效性，证明其不仅适用于合成环境，还能在真实场景中发挥作用。更多详情和视频请访问https://sites.google.com/view/few-shot-icpl/home。

> Designing reward functions is a core component of reinforcement learning but can be challenging for truly complex behavior. Reinforcement Learning from Human Feedback (RLHF) has been used to alleviate this challenge by replacing a hand-coded reward function with a reward function learned from preferences. However, it can be exceedingly inefficient to learn these rewards as they are often learned tabula rasa. We investigate whether Large Language Models (LLMs) can reduce this query inefficiency by converting an iterative series of human preferences into code representing the rewards. We propose In-Context Preference Learning (ICPL), a method that uses the grounding of an LLM to accelerate learning reward functions from preferences. ICPL takes the environment context and task description, synthesizes a set of reward functions, and then repeatedly updates the reward functions using human rankings of videos of the resultant policies. Using synthetic preferences, we demonstrate that ICPL is orders of magnitude more efficient than RLHF and is even competitive with methods that use ground-truth reward functions instead of preferences. Finally, we perform a series of human preference-learning trials and observe that ICPL extends beyond synthetic settings and can work effectively with humans-in-the-loop. Additional information and videos are provided at https://sites.google.com/view/few-shot-icpl/home.

[Arxiv](https://arxiv.org/abs/2410.17233)