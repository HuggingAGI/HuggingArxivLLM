# TRPrompt: 基于文本奖励的引导式感知查询提示优化

发布时间：2025年07月24日

`LLM应用

论文摘要讨论了提示优化在提升大型语言模型推理能力中的作用，并提出了一种新的框架（TRPrompt），该框架通过整合文本反馈来优化提示生成。这属于LLM的应用层面，因为它专注于如何优化模型的使用，而不是模型本身的理论或架构。` `提示优化`

> TRPrompt: Bootstrapping Query-Aware Prompt Optimization from Textual Rewards

# 摘要

> 提示优化能显著提升大型语言模型（LLM）的推理能力，而无需对目标模型进行参数更新。基于启发式"逐步思考"的方法，该领域主要沿着两个方向发展：一方面，研究者采用基于文本反馈的方法，通过无监督训练从通用LLM中提取更优质的提示；另一方面，另有研究依赖数值奖励，专门训练用于生成最优提示的提示模型。本文中，我们引入了Textual Reward Prompt框架（TRPrompt），该框架通过直接将文本反馈整合到提示模型的训练过程中，统一了上述两种方法。我们的框架无需预先收集数据集，并且能够通过生成提示的反馈进行迭代优化。当结合LLM对"优质"提示的理解能力时，文本奖励提供的高分辨率信号使我们能够训练出一个提示模型，该模型能为来自具有挑战性的数学数据集GSMHard和MATH的问题生成最先进的特定查询提示。

> Prompt optimization improves the reasoning abilities of large language models (LLMs) without requiring parameter updates to the target model. Following heuristic-based "Think step by step" approaches, the field has evolved in two main directions: while one group of methods uses textual feedback to elicit improved prompts from general-purpose LLMs in a training-free way, a concurrent line of research relies on numerical rewards to train a special prompt model, tailored for providing optimal prompts to the target model. In this paper, we introduce the Textual Reward Prompt framework (TRPrompt), which unifies these approaches by directly incorporating textual feedback into training of the prompt model. Our framework does not require prior dataset collection and is being iteratively improved with the feedback on the generated prompts. When coupled with the capacity of an LLM to internalize the notion of what a "good" prompt is, the high-resolution signal provided by the textual rewards allows us to train a prompt model yielding state-of-the-art query-specific prompts for the problems from the challenging math datasets GSMHard and MATH.

[Arxiv](https://arxiv.org/abs/2507.18618)