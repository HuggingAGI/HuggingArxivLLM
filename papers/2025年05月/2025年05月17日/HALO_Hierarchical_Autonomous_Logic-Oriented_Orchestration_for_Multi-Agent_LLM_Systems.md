# HALO: 面向多智能体LLM系统的分层自主逻辑编排方法

发布时间：2025年05月17日

`Agent` `多智能体系统` `代码生成`

> HALO: Hierarchical Autonomous Logic-Oriented Orchestration for Multi-Agent LLM Systems

# 摘要

> # 摘要
由大型语言模型（LLMs）驱动的多智能体系统（MAS）在多种任务场景中展现了巨大潜力。然而，现有智能体系统通常依赖预定义角色设计和静态通信结构，导致在复杂环境和专家级任务中表现受限。为此，我们提出了基于分层推理架构的多智能体协作框架HALO。该框架包含三个核心组件：高层规划智能体负责任务分解，中层角色设计智能体实现子任务定制化，低层推理智能体执行具体任务。特别地，子任务执行被建模为结构化工作流搜索问题，通过蒙特卡洛树搜索（MCTS）系统性探索动作空间以构建最优推理路径。考虑到用户普遍缺乏提示工程经验，我们引入自适应提示优化模块，将原始查询转化为任务特定提示。在代码生成（HumanEval）、通用推理（MMLU）和算术推理（MATH）基准测试中，HALO展现出显著优势，平均性能较现有最优方法提升14.4%。尤其在MMLU的道德推理和MATH的代数推理任务中，性能分别提升13.3%和19.6%，凸显其处理专业级任务的卓越能力。HALO代码仓库已开源，地址为https://github.com/23japhone/HALO。


> Recent advancements in Multi-Agent Systems (MAS) powered by Large Language Models (LLMs) have demonstrated tremendous potential in diverse task scenarios. Nonetheless, existing agentic systems typically rely on predefined agent-role design spaces and static communication structures, limiting their adaptability as well as flexibility in complex interaction environments and leading to subpar performance on highly specialized and expert-level tasks. To address these issues, we introduce HALO, a multi-agent collaboration framework based on a hierarchical reasoning architecture. Specifically, we incorporate a high-level planning agent for task decomposition, mid-level role-design agents for subtask-specific agent instantiation, and low-level inference agents for subtask execution. Particularly, subtask execution is reformulated as a structured workflow search problem, where Monte Carlo Tree Search (MCTS) systematically explores the agentic action space to construct optimal reasoning trajectories. Additionally, as the majority of users lack expertise in prompt engineering, we leverage an Adaptive Prompt Refinement module to transform raw queries into task-specific prompts. Empirical evaluations on Code Generation (HumanEval), General Reasoning (MMLU), and Arithmetic Reasoning (MATH) benchmark datasets highlight the effectiveness of HALO, yielding a 14.4% average improvement over state-of-the-art baselines. Notably, HALO achieves up to 13.3% performance gain on the Moral Scenarios subject in the MMLU benchmark and up to 19.6% performance gain on the Algebra subarea in the MATH benchmark, indicating its advanced proficiency in tackling highly specialized and expert-level tasks. The code repository is available at https://github.com/23japhone/HALO.

[Arxiv](https://arxiv.org/abs/2505.13516)