# 融合LLM决策与RL动作选择，优化RL策略以增强自适应干预效果

发布时间：2025年01月12日

`Agent

理由：这篇论文探讨了利用大型语言模型（LLMs）实时更新强化学习（RL）策略，以加速个性化健康适应性干预措施的开发。具体来说，LLM被用作RL行动选择的过滤器，通过基于文本的用户偏好动态调整行动选择。这种方法结合了LLM和RL，旨在优化RL策略并提升个性化水平。因此，这篇论文主要涉及Agent（智能体）的应用，特别是如何利用LLM来增强RL策略的个性化和适应性。` `个性化健康`

> Combining LLM decision and RL action selection to improve RL policy for adaptive interventions

# 摘要

> 强化学习（RL）在医疗领域，尤其是个性化健康适应性干预措施的开发中，应用越来越广泛。受大型语言模型（LLMs）成功的启发，我们探索利用LLMs实时更新RL策略，以加速个性化进程。通过基于文本的用户偏好动态调整行动选择，我们能够即时融入用户偏好。这里的“用户偏好”泛指个人偏好、约束、健康状况或表达喜好的陈述等。我们提出了一种混合方法，结合LLM响应和RL行动选择，以优化RL策略。在包含用户偏好的LLM提示下，LLM充当RL行动选择的过滤器。我们研究了多种提示策略和行动选择策略，并通过模拟环境生成基于文本的用户偏好，模拟影响行为动态的约束。结果表明，我们的方法能够有效考虑用户偏好，改进RL策略，从而提升适应性干预的个性化水平。

> Reinforcement learning (RL) is increasingly being used in the healthcare domain, particularly for the development of personalized health adaptive interventions. Inspired by the success of Large Language Models (LLMs), we are interested in using LLMs to update the RL policy in real time, with the goal of accelerating personalization. We use the text-based user preference to influence the action selection on the fly, in order to immediately incorporate the user preference. We use the term "user preference" as a broad term to refer to a user personal preference, constraint, health status, or a statement expressing like or dislike, etc. Our novel approach is a hybrid method that combines the LLM response and the RL action selection to improve the RL policy. Given an LLM prompt that incorporates the user preference, the LLM acts as a filter in the typical RL action selection. We investigate different prompting strategies and action selection strategies. To evaluate our approach, we implement a simulation environment that generates the text-based user preferences and models the constraints that impact behavioral dynamics. We show that our approach is able to take into account the text-based user preferences, while improving the RL policy, thus improving personalization in adaptive intervention.

[Arxiv](https://arxiv.org/abs/2501.06980)