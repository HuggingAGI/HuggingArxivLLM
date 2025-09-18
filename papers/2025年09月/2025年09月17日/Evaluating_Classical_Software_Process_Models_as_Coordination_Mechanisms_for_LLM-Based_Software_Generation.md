# 经典软件过程模型在基于LLM的软件生成中作为协调机制的评估

发布时间：2025年09月17日

`Agent` `基础理论`

> Evaluating Classical Software Process Models as Coordination Mechanisms for LLM-Based Software Generation

# 摘要

> [背景] 基于大型语言模型（LLM）的多智能体系统（MAS）正通过自主协作改变软件开发。瀑布模型、V模型、敏捷方法等传统软件过程提供的结构化协调模式，可被重新设计用于指导智能体交互。[目标] 本研究旨在探索如何将传统软件开发过程调整为基于LLM的MAS的协调框架，并考察其对代码质量、成本及生产力的影响。[方法] 我们在三种过程模型与四种GPT变体下开展了11个不同的软件项目，共进行132次运行。每个输出均采用标准化指标评估，包括规模（文件数、LOC）、成本（执行时间、token使用量）和质量（代码异味、AI与人工检测错误）。[结果] 过程模型和LLM选择均对系统性能产生显著影响：瀑布模型效率最优，V模型生成代码最为冗长，而敏捷方法虽计算成本较高，但代码质量最佳。[结论] 传统软件过程可有效应用于基于LLM的MAS，但每种过程都需在质量、成本与适应性之间权衡。过程选择应契合项目目标，无论是优先追求效率、健壮性还是结构化验证。

> [Background] Large Language Model (LLM)-based multi-agent systems (MAS) are transforming software development by enabling autonomous collaboration. Classical software processes such asWaterfall, V-Model, and Agile offer structured coordination patterns that can be repurposed to guide these agent interactions. [Aims] This study explores how traditional software development processes can be adapted as coordination scaffolds for LLM based MAS and examines their impact on code quality, cost, and productivity. [Method] We executed 11 diverse software projects under three process models and four GPT variants, totaling 132 runs. Each output was evaluated using standardized metrics for size (files, LOC), cost (execution time, token usage), and quality (code smells, AI- and human detected bugs). [Results] Both process model and LLM choice significantly affected system performance. Waterfall was most efficient, V-Model produced the most verbose code, and Agile achieved the highest code quality, albeit at higher computational cost. [Conclusions] Classical software processes can be effectively instantiated in LLM-based MAS, but each entails trade-offs across quality, cost, and adaptability. Process selection should reflect project goals, whether prioritizing efficiency, robustness, or structured validation.

[Arxiv](https://arxiv.org/abs/2509.13942)