# ToTRL：解谜探索，释放大型语言模型的树状思维推理潜力

发布时间：2025年05月19日

`LLM理论

摘要中提到，大型语言模型（LLMs）在长链式思维（CoT）推理中表现优异，但推理过程冗长且缺乏系统性。作者提出了树式思维（ToT）方法，并开发了树式思维强化学习（ToTRL）框架，旨在改进LLM的推理能力。这些贡献属于对LLM理论和方法的研究，因此归类为LLM理论。` `人工智能`

> ToTRL: Unlock LLM Tree-of-Thoughts Reasoning Potential through Puzzles Solving

# 摘要

> 大型语言模型（LLMs）在长链式思维（CoT）推理中展现出显著优势，但其推理过程往往显得冗长且缺乏系统性。针对这一局限，我们提出了树式思维（ToT）方法，将推理建模为树状结构的探索过程。在此基础上，我们开发了树式思维强化学习（ToTRL），这是一种基于规则奖励的在线策略 RL 框架，旨在引导 LLMs 发展更高效的并行推理策略。通过在解谜游戏中训练，模型需要构建并探索复杂的思维树，从而有效培养其 ToT 推理能力。实验结果表明，我们的 ToTQwen3-8B 模型在复杂推理任务中实现了性能和效率的显著提升。

> Large language models (LLMs) demonstrate significant reasoning capabilities, particularly through long chain-of-thought (CoT) processes, which can be elicited by reinforcement learning (RL). However, prolonged CoT reasoning presents limitations, primarily verbose outputs due to excessive introspection. The reasoning process in these LLMs often appears to follow a trial-and-error methodology rather than a systematic, logical deduction. In contrast, tree-of-thoughts (ToT) offers a conceptually more advanced approach by modeling reasoning as an exploration within a tree structure. This reasoning structure facilitates the parallel generation and evaluation of multiple reasoning branches, allowing for the active identification, assessment, and pruning of unproductive paths. This process can potentially lead to improved performance and reduced token costs. Building upon the long CoT capability of LLMs, we introduce tree-of-thoughts RL (ToTRL), a novel on-policy RL framework with a rule-based reward. ToTRL is designed to guide LLMs in developing the parallel ToT strategy based on the sequential CoT strategy. Furthermore, we employ LLMs as players in a puzzle game during the ToTRL training process. Solving puzzle games inherently necessitates exploring interdependent choices and managing multiple constraints, which requires the construction and exploration of a thought tree, providing challenging tasks for cultivating the ToT reasoning capability. Our empirical evaluations demonstrate that our ToTQwen3-8B model, trained with our ToTRL, achieves significant improvement in performance and reasoning efficiency on complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.12717)