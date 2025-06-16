# ACCORD：结合路由与动态注意力机制的自回归约束满足生成框架，用于组合优化问题

发布时间：2025年05月22日

`LLM应用` `运筹学` `计算机科学`

> ACCORD: Autoregressive Constraint-satisfying Generation for COmbinatorial Optimization with Routing and Dynamic attention

# 摘要

> 大型语言模型（LLMs）展现了令人瞩目的推理能力，但其直接应用于NP难的组合问题（CPs）仍鲜有探索。在本研究中，我们系统性地考察了LLMs在多种NP难组合优化任务中的推理能力，并引入了ACCORD：一种基于自回归约束满足生成的组合优化方法，结合了路由机制与动态注意力机制。

ACCORD采用了创新性的数据表示方法和模型架构，充分利用了LLMs的自回归特性以动态施加可行性约束，并通过基于注意力的路由机制激活特定问题的LoRA模块。我们还发布了包含六个NP难组合问题的ACCORD-90k监督数据集：TSP、VRP、背包问题、FlowShop、JSSP和BinPacking。

大量实验表明，基于80亿参数Llama模型构建的ACCORD模型，在面对标准提示和输入输出方法时表现更优，甚至超越了规模大得多的LLMs，如gpt-4。消融实验进一步证明，我们的输出结构提升了解决方案的可行性。

据我们所知，这是首个大规模、端到端的框架，用于探索LLMs在广泛组合优化问题中的应用。代码已公开发布于https://github.com/starjob42/ACCORD

> Large Language Models (LLMs) have demonstrated impressive reasoning capabilities, yet their direct application to NP-hard combinatorial problems (CPs) remains underexplored. In this work, we systematically investigate the reasoning abilities of LLMs on a variety of NP-hard combinatorial optimization tasks and introduce ACCORD: Autoregressive Constraint-satisfying generation for COmbinatorial optimization with Routing and Dynamic attention. ACCORD features a novel dataset representation and model architecture that leverage the autoregressive nature of LLMs to dynamically enforce feasibility constraints, coupled with attention-based routing to activate problem-specific LoRA modules. We also present the ACCORD-90k supervised dataset, covering six NP-hard combinatorial problems: TSP, VRP, Knapsack, FlowShop, JSSP, and BinPacking. Extensive experiments demonstrate that our ACCORD model, built on an 8B-parameter Llama backbone, consistently outperforms standard prompting and input-output methods, even when compared to much larger LLMs, such as gpt-4. Ablation studies further show that our output structure enhances solution feasibility. To the best of our knowledge, this is the first large-scale, end-to-end framework for exploring the applications of LLMs to a broad spectrum of combinatorial optimization problems. The codes are publicly available at https://github.com/starjob42/ACCORD

[Arxiv](https://arxiv.org/abs/2506.11052)