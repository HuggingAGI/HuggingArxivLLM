# 算法发现：进化搜索与强化学习的结合，助力大型语言模型

发布时间：2025年04月07日

`LLM应用` `优化算法`

> Algorithm Discovery With LLMs: Evolutionary Search Meets Reinforcement Learning

# 摘要

> 发现高效算法以解决复杂问题一直是数学和计算机科学领域中的重大难题，过去几十年间这一过程依赖大量的人类专业知识。近期，基于大型语言模型（LLMs）的进化搜索取得了突破性进展，尤其在数学和优化领域，展现出加速算法发现的潜力。然而，现有方法将LLM简单地视为静态生成器，未能充分利用进化探索过程中获得的信号来更新模型。在此工作中，我们提出通过强化学习（RL）微调持续优化作为搜索操作的LLM，从而增强基于LLM的进化搜索。我们的方法巧妙地将进化搜索作为探索策略，以发现改进的算法，同时RL根据这些发现优化LLM策略。我们在装箱问题、旅行商问题和扁平件问题这三个组合优化任务上的实验表明，将RL与进化搜索相结合能够显著提高改进算法的发现效率，充分展示了RL增强的进化策略在协助计算机科学家和数学家更高效地设计算法方面的巨大潜力。

> Discovering efficient algorithms for solving complex problems has been an outstanding challenge in mathematics and computer science, requiring substantial human expertise over the years. Recent advancements in evolutionary search with large language models (LLMs) have shown promise in accelerating the discovery of algorithms across various domains, particularly in mathematics and optimization. However, existing approaches treat the LLM as a static generator, missing the opportunity to update the model with the signal obtained from evolutionary exploration. In this work, we propose to augment LLM-based evolutionary search by continuously refining the search operator - the LLM - through reinforcement learning (RL) fine-tuning. Our method leverages evolutionary search as an exploration strategy to discover improved algorithms, while RL optimizes the LLM policy based on these discoveries. Our experiments on three combinatorial optimization tasks - bin packing, traveling salesman, and the flatpack problem - show that combining RL and evolutionary search improves discovery efficiency of improved algorithms, showcasing the potential of RL-enhanced evolutionary strategies to assist computer scientists and mathematicians for more efficient algorithm design.

[Arxiv](https://arxiv.org/abs/2504.05108)