# AgentGroupChat-V2：分而治之正是基于大型语言模型的多智能体系统所需要的

发布时间：2025年06月18日

`Agent` `多智能体系统`

> AgentGroupChat-V2: Divide-and-Conquer Is What LLM-Based Multi-Agent System Need

# 摘要

> 基于大型语言模型的多智能体系统在社交模拟和复杂任务解决领域展现出了巨大的潜力。然而，现有的框架在系统架构设计、跨领域通用性以及性能保障方面面临着严峻挑战，特别是在任务复杂度和智能体数量增加时。我们推出了AgentGroupChat-V2，一个通过三大核心创新解决这些挑战的新型框架：(1) 一种分治式全并行架构，能够将用户查询分解为层次化任务森林结构，实现依赖关系管理和分布式并发处理。(2) 一个自适应协作引擎，可根据任务特性动态选择异构大型语言模型组合及交互模式。(3) 结合分治策略的智能体组织优化方法，实现高效的问题分解。大量实验表明，AgentGroupChat-V2在多个领域均表现出色，GSM8K准确率达到91.50%（领先最佳基线5.6个百分点），在竞赛级AIME任务中准确率达30.4%（几乎是其他方法的两倍），HumanEval通过率@1达79.20%。随着任务难度的增加，性能优势更加显著，在Level 5 MATH问题上，相较于现有最优基线，提升超过11个百分点。这些结果证实了AgentGroupChat-V2为构建高效通用的大型语言模型多智能体系统提供了全面解决方案，并在复杂推理场景中具有显著优势。代码可在https://github.com/MikeGu721/AgentGroupChat-V2获取。

> Large language model based multi-agent systems have demonstrated significant potential in social simulation and complex task resolution domains. However, current frameworks face critical challenges in system architecture design, cross-domain generalizability, and performance guarantees, particularly as task complexity and number of agents increases. We introduces AgentGroupChat-V2, a novel framework addressing these challenges through three core innovations: (1) a divide-and-conquer fully parallel architecture that decomposes user queries into hierarchical task forest structures enabling dependency management and distributed concurrent processing. (2) an adaptive collaboration engine that dynamically selects heterogeneous LLM combinations and interaction modes based on task characteristics. (3) agent organization optimization strategies combining divide-and-conquer approaches for efficient problem decomposition. Extensive experiments demonstrate AgentGroupChat-V2's superior performance across diverse domains, achieving 91.50% accuracy on GSM8K (exceeding the best baseline by 5.6 percentage points), 30.4% accuracy on competition-level AIME (nearly doubling other methods), and 79.20% pass@1 on HumanEval. Performance advantages become increasingly pronounced with higher task difficulty, particularly on Level 5 MATH problems where improvements exceed 11 percentage points compared to state-of-the-art baselines. These results confirm that AgentGroupChat-V2 provides a comprehensive solution for building efficient, general-purpose LLM multi-agent systems with significant advantages in complex reasoning scenarios. Code is available at https://github.com/MikeGu721/AgentGroupChat-V2.

[Arxiv](https://arxiv.org/abs/2506.15451)