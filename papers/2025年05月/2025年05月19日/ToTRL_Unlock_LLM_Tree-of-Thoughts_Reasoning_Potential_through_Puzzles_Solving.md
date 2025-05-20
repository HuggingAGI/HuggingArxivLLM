# ToTRL：通过解谜题释放LLM的树状推理潜力

发布时间：2025年05月19日

`LLM理论` `智能游戏`

> ToTRL: Unlock LLM Tree-of-Thoughts Reasoning Potential through Puzzles Solving

# 摘要

> 大型语言模型（LLMs）在长链式思维（CoT）推理中表现出色，但过度的自我反思导致输出冗长。我们提出了树式思维（ToT）方法，通过构建推理树结构，实现多路径推理的并行生成与优化。基于此，我们开发了树式思维强化学习（ToTRL）框架，引导LLMs发展更高效的推理策略。在解谜游戏中训练LLMs，通过解决复杂约束问题，进一步提升其推理能力。实验结果表明，我们的ToTQwen3-8B模型在复杂推理任务中表现优异。

> Large language models (LLMs) demonstrate significant reasoning capabilities, particularly through long chain-of-thought (CoT) processes, which can be elicited by reinforcement learning (RL). However, prolonged CoT reasoning presents limitations, primarily verbose outputs due to excessive introspection. The reasoning process in these LLMs often appears to follow a trial-and-error methodology rather than a systematic, logical deduction. In contrast, tree-of-thoughts (ToT) offers a conceptually more advanced approach by modeling reasoning as an exploration within a tree structure. This reasoning structure facilitates the parallel generation and evaluation of multiple reasoning branches, allowing for the active identification, assessment, and pruning of unproductive paths. This process can potentially lead to improved performance and reduced token costs. Building upon the long CoT capability of LLMs, we introduce tree-of-thoughts RL (ToTRL), a novel on-policy RL framework with a rule-based reward. ToTRL is designed to guide LLMs in developing the parallel ToT strategy based on the sequential CoT strategy. Furthermore, we employ LLMs as players in a puzzle game during the ToTRL training process. Solving puzzle games inherently necessitates exploring interdependent choices and managing multiple constraints, which requires the construction and exploration of a thought tree, providing challenging tasks for cultivating the ToT reasoning capability. Our empirical evaluations demonstrate that our ToTQwen3-8B model, trained with our ToTRL, achieves significant improvement in performance and reasoning efficiency on complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.12717)