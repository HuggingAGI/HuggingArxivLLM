# 用于使大型语言模型能从相关性推断因果关系的提示策略

发布时间：2024年12月18日

`LLM应用` `因果推理` `语言模型`

> Prompting Strategies for Enabling Large Language Models to Infer Causation from Correlation

# 摘要

> 大型语言模型（LLMs）的推理能力愈发受到关注。在本次研究中，我们聚焦于因果推理，致力于解决基于相关信息确立因果关系这一极具挑战性的任务，不少大型语言模型在此方面表现欠佳。为此，我们引入了一种提示策略，将原任务拆解为固定的子问题，每个子问题对应正式因果发现算法——PC 算法的一个步骤。所提出的 PC-SubQ 提示策略，通过依次用一个子问题进行提示，并将前一个（些）子问题的答案添加到下一个子问题的提示中，引导大型语言模型遵循这些算法步骤。我们在现有的因果基准 Corr2Cause 上对我们的方法进行评估：实验表明，将 PC-SubQ 与基线提示策略相比，五个大型语言模型的性能均有提升。在修改变量名称或改写表达式时，结果对因果查询的扰动具有较强的稳定性。

> The reasoning abilities of Large Language Models (LLMs) are attracting increasing attention. In this work, we focus on causal reasoning and address the task of establishing causal relationships based on correlation information, a highly challenging problem on which several LLMs have shown poor performance. We introduce a prompting strategy for this problem that breaks the original task into fixed subquestions, with each subquestion corresponding to one step of a formal causal discovery algorithm, the PC algorithm. The proposed prompting strategy, PC-SubQ, guides the LLM to follow these algorithmic steps, by sequentially prompting it with one subquestion at a time, augmenting the next subquestion's prompt with the answer to the previous one(s). We evaluate our approach on an existing causal benchmark, Corr2Cause: our experiments indicate a performance improvement across five LLMs when comparing PC-SubQ to baseline prompting strategies. Results are robust to causal query perturbations, when modifying the variable names or paraphrasing the expressions.

[Arxiv](https://arxiv.org/abs/2412.13952)