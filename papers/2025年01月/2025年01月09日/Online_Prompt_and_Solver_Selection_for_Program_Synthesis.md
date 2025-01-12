# 程序合成中的在线提示与求解器选择

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何通过在线学习算法（多臂赌博机算法）来选择最优的符号求解器或LLM与提示组合，以最大化任务完成的效果。这涉及到LLM在实际应用中的优化和选择问题，属于LLM在程序合成领域的应用场景。因此，将其分类为LLM应用是合适的。` `程序合成` `在线学习`

> Online Prompt and Solver Selection for Program Synthesis

# 摘要

> # 摘要
大型语言模型（LLMs）在程序合成领域展现了强大的能力，但这种能力并非在所有任务、模型和提示风格中都普遍适用。某些情况下，特定LLM或提示风格表现更佳，甚至符号求解器可能是更好的选择。因此，用户面临的挑战不仅在于选择合适的LLM，还要确定最佳的调用方式。非专业用户若选择不当，不仅会影响任务完成的数量和时间，还可能在使用商业API时产生额外成本。我们将这一问题转化为在线学习问题，采用多臂赌博机算法来选择最优的符号求解器或LLM与提示组合，以最大化奖励函数（如解决时间、任务数量或成本）。我们开发了一个名为CYANEA的系统，并在排序函数合成、语法引导合成竞赛以及SMT问题生成的查询上进行了测试。结果显示，CYANEA比单一最佳求解器多解决了37.2%的查询，且结果接近虚拟最佳求解器的4%以内。

> Large Language Models (LLMs) demonstrate impressive capabilities in the domain of program synthesis. This level of performance is not, however, universal across all tasks, all LLMs and all prompting styles. There are many areas where one LLM dominates, one prompting style dominates, or where calling a symbolic solver is a better choice than an LLM. A key challenge for the user then, is to identify not only when an LLM is the right choice of solver, and the appropriate LLM to call for a given synthesis task, but also the right way to call it. A non-expert user who makes the wrong choice, incurs a cost both in terms of results (number of tasks solved, and the time it takes to solve them) and financial cost, if using a closed-source language model via a commercial API. We frame this choice as an online learning problem. We use a multi-armed bandit algorithm to select which symbolic solver, or LLM and prompt combination to deploy in order to maximize a given reward function (which may prioritize solving time, number of synthesis tasks solved, or financial cost of solving). We implement an instance of this approach, called CYANEA, and evaluate it on synthesis queries from the literature in ranking function synthesis, from the syntax-guided synthesis competition, and fresh, unseen queries generated from SMT problems. CYANEA solves 37.2\% more queries than the best single solver and achieves results within 4\% of the virtual best solver.

[Arxiv](https://arxiv.org/abs/2501.05247)