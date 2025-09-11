# 以预训练大型语言模型为导师并复用建议加速强化学习算法收敛

发布时间：2025年09月10日

`强化学习` `基础理论`

> Accelerating Reinforcement Learning Algorithms Convergence using Pre-trained Large Language Models as Tutors With Advice Reusing

# 摘要

> 强化学习（RL）算法往往需要漫长训练才能派上用场，尤其是在稀疏奖励的复杂环境中。虽然奖励塑造、课程学习等技术可加速训练，但这些方法高度特定，离不开开发者在问题领域的专业素养与深耕经验。为破解这一难题，本研究探索了将预训练大型语言模型（LLMs）作为导师，与RL算法构建师生架构的有效性，推测LLM生成的指导能加快收敛速度。我们特别研究了重用LLM建议对RL收敛动态的影响。通过54种配置的大规模实证（涉及RL算法：DQN、PPO、A2C；LLM导师：Llama、Vicuna、DeepSeek；环境：Blackjack、Snake、Connect Four），结果显示：LLM辅导能显著加速RL收敛，同时保持相当的最优性能。此外，建议重用机制虽进一步缩短了训练时间，却让收敛动态稳定性有所下降。研究发现，LLM辅导总体上能改善收敛效果，但其有效性对具体任务、RL算法及LLM模型的组合颇为敏感。

> Reinforcement Learning (RL) algorithms often require long training to become useful, especially in complex environments with sparse rewards. While techniques like reward shaping and curriculum learning exist to accelerate training, these are often extremely specific and require the developer's professionalism and dedicated expertise in the problem's domain. Tackling this challenge, in this study, we explore the effectiveness of pre-trained Large Language Models (LLMs) as tutors in a student-teacher architecture with RL algorithms, hypothesizing that LLM-generated guidance allows for faster convergence. In particular, we explore the effectiveness of reusing the LLM's advice on the RL's convergence dynamics. Through an extensive empirical examination, which included 54 configurations, varying the RL algorithm (DQN, PPO, A2C), LLM tutor (Llama, Vicuna, DeepSeek), and environment (Blackjack, Snake, Connect Four), our results demonstrate that LLM tutoring significantly accelerates RL convergence while maintaining comparable optimal performance. Furthermore, the advice reuse mechanism shows a further improvement in training duration but also results in less stable convergence dynamics. Our findings suggest that LLM tutoring generally improves convergence, and its effectiveness is sensitive to the specific task, RL algorithm, and LLM model combination.

[Arxiv](https://arxiv.org/abs/2509.08329)