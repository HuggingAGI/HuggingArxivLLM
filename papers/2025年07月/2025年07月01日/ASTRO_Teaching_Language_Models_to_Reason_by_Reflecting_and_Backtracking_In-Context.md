# ASTRO：教语言模型通过反思与回溯实现推理

发布时间：2025年07月01日

`LLM应用` `教育技术`

> ASTRO: Teaching Language Models to Reason by Reflecting and Backtracking In-Context

# 摘要

> # ASTRO 框架介绍  
我们推出 ASTRO（自回归搜索教学推理器），一个训练语言模型模拟搜索算法推理的框架。通过合成数据集，ASTRO 教导模型内化结构化的搜索行为，显著提升了包括 Llama 3 在内的模型推理能力。在数学问题解决上，ASTRO 实现了 16.0% 至 26.9% 的性能提升，尤其在复杂问题上表现突出。这表明，搜索启发的训练为增强开放语言模型的推理能力提供了一种系统化的方法。

> We introduce ASTRO, the "Autoregressive Search-Taught Reasoner", a framework for training language models to reason like search algorithms, explicitly leveraging self-reflection, backtracking, and exploration in their outputs. Recently, training large language models (LLMs) via reinforcement learning (RL) has led to the advent of reasoning models with greatly enhanced reasoning capabilities. Open-source replications of reasoning models, while successful, build upon models that already exhibit strong reasoning capabilities along with search behavior observed even before RL. As a result, it is yet unclear how to boost the reasoning capabilities of other non-reasoner models including Llama 3. ASTRO teaches such models to internalize structured search behavior through a synthetic dataset derived from Monte Carlo Tree Search (MCTS) over mathematical problem-solving trajectories. By converting search traces into natural language chain-of-thoughts that capture both successes and recoveries from failure, ASTRO bootstraps models with a rich prior for exploration during RL. We finetune our models on these search-derived traces and further improve performance via RL with verifiable rewards. We apply ASTRO to the Llama 3 family of models and achieve absolute performance gains of 16.0% on MATH-500, 26.9% on AMC 2023, and 20.0% on AIME 2024, especially improving upon challenging problems that require iterative correction. Our results demonstrate that search-inspired training offers a principled way to instill robust reasoning capabilities into open LLMs.

[Arxiv](https://arxiv.org/abs/2507.00417)