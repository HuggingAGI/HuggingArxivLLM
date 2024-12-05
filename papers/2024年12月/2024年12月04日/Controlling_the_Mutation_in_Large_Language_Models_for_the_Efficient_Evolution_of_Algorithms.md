# 对大型语言模型中的变异加以控制，以促进算法的高效演进

发布时间：2024年12月04日

`LLM应用` `进化计算` `代码优化`

> Controlling the Mutation in Large Language Models for the Efficient Evolution of Algorithms

# 摘要

> 大型语言模型（LLMs）与进化计算（EC）相融合，为元启发式算法的自动化设计带来了极具前景的模式。然而，现有的诸如大型语言模型进化算法（LLaMEA）等框架，常常在变异机制的控制上不够精准，致使解空间探索效率低下，可能导致收敛效果欠佳。受遗传算法理论的启发，本文在LLM驱动的进化框架中引入了新颖的变异控制手段。具体而言，我们提出了动态变异提示，能自适应地调控变异率，并借助重尾幂律分布来平衡探索与利用。使用GPT-3.5-turbo和GPT-4o模型开展的实验显示，GPT-3.5-turbo未能遵循特定的变异指令，而GPT-4o能够依据精心设计的动态提示来调整其变异。进一步的实验表明，在使用GPT-4o时，引入这些动态率能够提升LLaMEA的收敛速度和适应性。此项工作为在代码优化任务中更有效地控制基于LLM的变异开了个好头，为自动化元启发式设计的进一步发展铺平了道路。

> The integration of Large Language Models (LLMs) with evolutionary computation (EC) has introduced a promising paradigm for automating the design of metaheuristic algorithms. However, existing frameworks, such as the Large Language Model Evolutionary Algorithm (LLaMEA), often lack precise control over mutation mechanisms, leading to inefficiencies in solution space exploration and potentially suboptimal convergence. This paper introduces a novel approach to mutation control within LLM-driven evolutionary frameworks, inspired by theory of genetic algorithms. Specifically, we propose dynamic mutation prompts that adaptively regulate mutation rates, leveraging a heavy-tailed power-law distribution to balance exploration and exploitation. Experiments using GPT-3.5-turbo and GPT-4o models demonstrate that GPT-3.5-turbo fails to adhere to the specific mutation instructions, while GPT-4o is able to adapt its mutation based on the prompt engineered dynamic prompts. Further experiments show that the introduction of these dynamic rates can improve the convergence speed and adaptability of LLaMEA, when using GPT-4o. This work sets the starting point for better controlled LLM-based mutations in code optimization tasks, paving the way for further advancements in automated metaheuristic design.

[Arxiv](https://arxiv.org/abs/2412.03250)