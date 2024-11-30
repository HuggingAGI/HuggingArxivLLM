# 大型语言模型是否具备进行分析推理的能力呢？

发布时间：2024年03月06日

`LLM应用`

> Can Large Language Models do Analytical Reasoning?

# 摘要

> 这篇论文深入探索了在体育领域运用高级分析推理技术的前沿大型语言模型。我们的研究重点是让大型语言模型去完成诸如统计NBA与NFL比赛每节各队得分的任务。两大重要发现如下：首先，在我们测试的一系列模型中，GPT-4脱颖而出，展现卓越效能，紧随其后的是Claude-2.1，而GPT-3.5、Gemini-Pro及Llama-2-70b相对落后。我们对比了三种不同的提示技巧以及一种“分治法”，发现后者最为高效，它能将逐次比赛数据细化为便于处理的小段，逐个解决后再整合结果。此外，我们也尝试了链式思考（CoT）策略，这一策略对于GPT-4和Claude-2.1等特定模型具有显著提升作用，使它们的准确率大大提高；但对GPT-3.5和Gemini-Pro等其他模型的效果则微乎其微，甚至可能带来负面影响。其次，出乎意料的是，尽管多数模型在计算NFL季度得分上表现出色，包括GPT-4在内的许多模型在精确统计NBA季度总得分上却面临挑战。为此，我们通过大量实验探究了影响分析推理任务复杂度的因素，最后总结出任务难度与上下文长度、信息密集程度以及相关背景信息的提供密切相关。此项研究揭示了分析推理任务复杂性的本质，并为今后大型语言模型的研发提供了宝贵的启示与方向。

> This paper explores the cutting-edge Large Language Model with analytical reasoning on sports. Our analytical reasoning embodies the tasks of letting large language models count how many points each team scores in a quarter in the NBA and NFL games. Our major discoveries are in two folds. Firstly, we find among all the models we employed, GPT-4 stands out in effectiveness, followed by Claude-2.1, with GPT-3.5, Gemini-Pro, and Llama-2-70b lagging behind. Specifically, we compare three different prompting techniques and a divide-and-conquer approach, we find that the latter was the most effective. Our divide-and-conquer approach breaks down play-by-play data into smaller, more manageable segments, solves each piece individually, and then aggregates them together. Besides the divide-and-conquer approach, we also explore the Chain of Thought (CoT) strategy, which markedly improves outcomes for certain models, notably GPT-4 and Claude-2.1, with their accuracy rates increasing significantly. However, the CoT strategy has negligible or even detrimental effects on the performance of other models like GPT-3.5 and Gemini-Pro. Secondly, to our surprise, we observe that most models, including GPT-4, struggle to accurately count the total scores for NBA quarters despite showing strong performance in counting NFL quarter scores. This leads us to further investigate the factors that impact the complexity of analytical reasoning tasks with extensive experiments, through which we conclude that task complexity depends on the length of context, the information density, and the presence of related information. Our research provides valuable insights into the complexity of analytical reasoning tasks and potential directions for developing future large language models.

[Arxiv](https://arxiv.org/abs/2403.04031)