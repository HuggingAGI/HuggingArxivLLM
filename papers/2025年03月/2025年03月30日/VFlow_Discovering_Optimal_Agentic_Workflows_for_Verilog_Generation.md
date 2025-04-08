# VFlow：优化 Verilog 生成的智能体工作流程

发布时间：2025年03月30日

`LLM应用` `硬件设计自动化` `半导体行业`

> VFlow: Discovering Optimal Agentic Workflows for Verilog Generation

# 摘要

> 硬件设计自动化在高效生成高质量Verilog代码方面面临诸多挑战。本文介绍了一种名为VFlow的自动化框架，专注于优化Verilog代码生成的工作流。与现有方法依赖预定义提示策略不同，VFlow采用蒙特卡洛树搜索（MCTS），寻找能够最大化代码质量同时最小化计算成本的大型语言模型调用序列。VFlow扩展了AFLOW方法论，引入了针对硬件设计需求的专用算子，包括语法验证、基于仿真的验证以及综合优化。在VerilogEval基准测试中的实验结果表明，VFlow表现优异，平均通过率@1达到83.6%，较现有最优的PromptV提升了6.1%，较直接调用LLM的提升幅度更是达到36.9%。尤为重要的是，VFlow显著提升了小型模型的能力，使DeepSeek-V3的性能达到GPT-4的141.2%，同时将API成本降低至原来的13%。这些结果表明，通过智能优化的工作流，成本较低的LLMs在硬件设计任务中能够超越大型模型，这可能为先进数字电路开发工具的普及以及半导体行业的创新加速带来重要影响。

> Hardware design automation faces challenges in generating high-quality Verilog code efficiently. This paper introduces VFlow, an automated framework that optimizes agentic workflows for Verilog code generation. Unlike existing approaches that rely on pre-defined prompting strategies, VFlow leverages Monte Carlo Tree Search (MCTS) to discover effective sequences of Large Language Models invocations that maximize code quality while minimizing computational costs. VFlow extends the AFLOW methodology with domain-specific operators addressing hardware design requirements, including syntax validation, simulation-based verification, and synthesis optimization. Experimental evaluation on the VerilogEval benchmark demonstrates VFlow's superiority, achieving an 83.6% average pass@1 rate-a 6.1\% improvement over state-of-the-art PromptV and a 36.9\% gain compared to direct LLM invocation. Most significantly, VFlow enhances the capabilities of smaller models, enabling DeepSeek-V3 to achieve 141.2\% of GPT-4o's performance while reducing API costs to just 13\%. These findings indicate that intelligently optimized workflows enable cost-efficient LLMs to outperform larger models on hardware design tasks, potentially democratizing access to advanced digital circuit development tools and accelerating innovation in the semiconductor industry

[Arxiv](https://arxiv.org/abs/2504.03723)