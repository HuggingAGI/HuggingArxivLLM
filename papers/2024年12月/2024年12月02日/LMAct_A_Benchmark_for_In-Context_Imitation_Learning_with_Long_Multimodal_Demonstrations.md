# LMAct：用于长多模态演示的上下文模仿学习的基准

发布时间：2024年12月02日

`Agent`

> LMAct: A Benchmark for In-Context Imitation Learning with Long Multimodal Demonstrations

# 摘要

> 如今最大的基础模型能力愈发通用，然而作为代理使用时，它们在简单的推理和决策任务中常表现欠佳，尽管它们熟知任务情况及解决方法。本文中，我们给出一个基准，用于压力测试这些模型在极长上下文环境（多达百万个标记）中的多模态决策能力，探究它们能否从众多专家示范中学习。我们对一系列先进的前沿模型作为策略进行评估，涉及一系列简单的交互式决策任务，如玩井字棋、国际象棋和雅达利游戏，在网格世界导航，解填字游戏以及控制模拟猎豹。我们衡量了 Claude 3.5 Sonnet、Gemini 1.5 Flash、Gemini 1.5 Pro、GPT-4o、o1-mini 和 o1-preview 在上下文（从无示范到多达 512 个完整剧集）中专家示范数量递增时的性能，将这些模型的多模态长上下文推理能力推向极限。在我们的任务里，当下的前沿模型鲜少能完全达到专家水平，凸显了我们基准的难度。提供更多示范通常作用不大，但部分模型在一些任务上会随着示范增多而稳步提升。我们研究了将观察结果编码为文本或图像的效果以及思维链提示的影响。总的来说，我们的结果表明，即便是当今最强大的模型，也往往难以仅通过上下文示范来模仿期望的行为。为助力量化其他旨在解决此问题的方法和未来创新的影响，我们开源了我们的基准，其在统一评估中涵盖了零样本、少样本和多样本情况。

> Today's largest foundation models have increasingly general capabilities, yet when used as agents, they often struggle with simple reasoning and decision-making tasks, even though they possess good factual knowledge of the task and how to solve it. In this paper, we present a benchmark to pressure-test these models' multimodal decision-making capabilities in the very long-context regime (up to one million tokens) and investigate whether they can learn from a large number of expert demonstrations in their context. We evaluate a wide range of state-of-the-art frontier models as policies across a battery of simple interactive decision-making tasks: playing tic-tac-toe, chess, and Atari, navigating grid worlds, solving crosswords, and controlling a simulated cheetah. We measure the performance of Claude 3.5 Sonnet, Gemini 1.5 Flash, Gemini 1.5 Pro, GPT-4o, o1-mini, and o1-preview under increasing amounts of expert demonstrations in the context $unicode{x2013}$ from no demonstrations up to 512 full episodes, pushing these models' multimodal long-context reasoning capabilities to their limits. Across our tasks, today's frontier models rarely manage to fully reach expert performance, showcasing the difficulty of our benchmark. Presenting more demonstrations often has little effect, but some models steadily improve with more demonstrations on a few tasks. We investigate the effect of encoding observations as text or images and the impact of chain-of-thought prompting. Overall, our results suggest that even today's most capable models often struggle to imitate desired behavior by generalizing purely from in-context demonstrations. To help quantify the impact of other approaches and future innovations aiming to tackle this problem, we open source our benchmark that covers the zero-, few-, and many-shot regimes in a unified evaluation.

[Arxiv](https://arxiv.org/abs/2412.01441)