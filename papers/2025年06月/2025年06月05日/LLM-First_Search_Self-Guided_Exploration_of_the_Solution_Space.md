# 基于LLM的搜索方法：解空间的自我引导探索

发布时间：2025年06月05日

`LLM应用` `大型语言模型` `推理规划`

> LLM-First Search: Self-Guided Exploration of the Solution Space

# 摘要

> 大型语言模型（LLMs）在推理和规划方面取得了显著提升，这得益于通过增加推理时的计算资源，并将问题解决视为一种搜索过程。尽管蒙特卡洛树搜索（MCTS）等方法在某些领域表现出色，但它们对固定探索超参数的依赖限制了其在不同难度任务中的适应性，使其在某些情况下难以实用或成本高昂。本文提出了一种名为	extbf{LLM-First Search (LFS)}的新型	extit{LLM Self-Guided Search}方法，通过赋予LLM自主控制搜索过程的能力，无需预先定义的搜索策略。与依赖外部启发式或固定策略不同，LLM根据其内部评分机制判断是继续当前搜索路径还是探索其他分支。这使得推理更加灵活且具有上下文敏感性，无需手动调整或特定任务的适应。我们在倒计时和数独任务上将LFS与三种经典的广泛使用的搜索算法进行了对比：Tree-of-Thoughts的广度优先搜索（ToT-BFS）、最佳优先搜索（BestFS）和蒙特卡洛树搜索（MCTS），这些算法均被用于在一系列具有挑战性的推理任务中取得最优结果。我们发现LFS (1) 在更具挑战性的任务上表现更优且无需额外调优，(2) 在计算效率上优于其他方法，尤其在使用更强模型时表现更佳，(3) 由于其LLM-First设计，能够更好地与更强模型扩展，(4) 在增加计算预算时能够更好地扩展。我们的代码可在\href{https://github.com/NathanHerr/LLM-First-Search}{LLM-First-Search}公开获取。

> Large Language Models (LLMs) have demonstrated remarkable improvements in reasoning and planning through increased test-time compute, often by framing problem-solving as a search process. While methods like Monte Carlo Tree Search (MCTS) have proven effective in some domains, their reliance on fixed exploration hyperparameters limits their adaptability across tasks of varying difficulty, rendering them impractical or expensive in certain settings. In this paper, we propose \textbf{LLM-First Search (LFS)}, a novel \textit{LLM Self-Guided Search} method that removes the need for pre-defined search strategies by empowering the LLM to autonomously control the search process via self-guided exploration. Rather than relying on external heuristics or hardcoded policies, the LLM evaluates whether to pursue the current search path or explore alternative branches based on its internal scoring mechanisms. This enables more flexible and context-sensitive reasoning without requiring manual tuning or task-specific adaptation. We evaluate LFS on Countdown and Sudoku against three classic widely-used search algorithms, Tree-of-Thoughts' Breadth First Search (ToT-BFS), Best First Search (BestFS), and MCTS, each of which have been used to achieve SotA results on a range of challenging reasoning tasks. We found that LFS (1) performs better on more challenging tasks without additional tuning, (2) is more computationally efficient compared to the other methods, especially when powered by a stronger model, (3) scales better with stronger models, due to its LLM-First design, and (4) scales better with increased compute budget. Our code is publicly available at \href{https://github.com/NathanHerr/LLM-First-Search}{LLM-First-Search}.

[Arxiv](https://arxiv.org/abs/2506.05213)