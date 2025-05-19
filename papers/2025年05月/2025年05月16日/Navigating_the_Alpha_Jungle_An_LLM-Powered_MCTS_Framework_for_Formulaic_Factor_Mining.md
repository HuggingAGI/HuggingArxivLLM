# 在复杂环境中导航：利用大型语言模型驱动的蒙特卡洛树搜索框架进行公式化因子挖掘

发布时间：2025年05月16日

`LLM应用` `量化投资`

> Navigating the Alpha Jungle: An LLM-Powered MCTS Framework for Formulaic Factor Mining

# 摘要

> Alpha因子挖掘在量化投资中至关重要，用于从复杂金融数据中识别具有预测性的信号。传统基于公式的Alpha因子挖掘依赖于人类的专业知识，而当代自动化方法，如基于遗传编程或强化学习的方法，往往存在搜索效率低下或生成难以解释的Alpha因子的问题。本文提出了一种结合大型语言模型（LLMs）与蒙特卡罗树搜索（MCTS）的新型框架，以克服这些限制。

我们的方法利用LLM的指令遵循和推理能力，在MCTS驱动的探索过程中迭代生成和优化符号Alpha公式。一项关键创新是通过每个候选因子的财务回测提供的丰富、定量反馈来引导MCTS探索，从而在广阔的搜索空间中实现高效导航。此外，我们引入了一种频繁子树避免机制，以提升搜索效率和Alpha因子的表现。

在真实股票市场数据上的实验结果表明，与现有方法相比，我们的LLM基框架在挖掘具有更优预测精度、交易表现和增强可解释性的Alpha因子方面表现更优，同时为基于公式的Alpha因子挖掘提供了一种更高效的解决方案。

> Alpha factor mining is pivotal in quantitative investment for identifying predictive signals from complex financial data. While traditional formulaic alpha mining relies on human expertise, contemporary automated methods, such as those based on genetic programming or reinforcement learning, often suffer from search inefficiency or yield poorly interpretable alpha factors. This paper introduces a novel framework that integrates Large Language Models (LLMs) with Monte Carlo Tree Search (MCTS) to overcome these limitations. Our approach leverages the LLM's instruction-following and reasoning capability to iteratively generate and refine symbolic alpha formulas within an MCTS-driven exploration. A key innovation is the guidance of MCTS exploration by rich, quantitative feedback from financial backtesting of each candidate factor, enabling efficient navigation of the vast search space. Furthermore, a frequent subtree avoidance mechanism is introduced to bolster search efficiency and alpha factor performance. Experimental results on real-world stock market data demonstrate that our LLM-based framework outperforms existing methods by mining alphas with superior predictive accuracy, trading performance, and improved interpretability, while offering a more efficient solution for formulaic alpha mining.

[Arxiv](https://arxiv.org/abs/2505.11122)