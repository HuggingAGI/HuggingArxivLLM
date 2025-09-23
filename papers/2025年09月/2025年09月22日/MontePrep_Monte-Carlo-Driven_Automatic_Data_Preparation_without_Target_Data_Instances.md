# MontePrep：蒙特卡洛驱动的无目标数据实例自动数据准备

发布时间：2025年09月22日

`LLM应用` `基础理论`

> MontePrep: Monte-Carlo-Driven Automatic Data Preparation without Target Data Instances

# 摘要

> 在商业系统中，自动数据准备（ADP）的核心需求是将关系型数据从各类异构数据源迁移至符合标准化模式规范的目标系统。然而，传统方法往往依赖大量人工标注的监督信号或目标表数据访问权限，这极大限制了其在实际场景中的应用。为解决这些难题，我们提出了一种高效的端到端ADP框架MontePrep，该框架无需训练即可实现数据处理管道的自动合成，且完全不依赖目标实例数据。MontePrep的核心是将ADP任务转化为由开源大型语言模型（LLM）驱动的树状结构搜索问题，包含三个关键组件：数据准备操作沙箱（DPAS）、基础管道生成器（FPG）和执行感知管道优化器（EPO）。首先是数据准备操作沙箱（DPAS），这是一个轻量级的操作环境，用于引导基于搜索的管道生成过程，其设计能够有效避免探索不可行的管道方案。其次是基础管道生成器（FPG），用于增量构建可执行的数据处理管道，它借助LLM驱动的蒙特卡洛树搜索算法探索预定义的操作沙箱。最后是执行感知管道优化器（EPO），它通过调用管道从数据源到目标端的执行结果，评估FPG生成的管道可靠性。通过这一机制，无效管道被自动过滤，大幅提升了搜索过程的效率与准确性。大量实验结果表明，MontePrep性能显著优于五个当前最先进的对比方法，优势明显。

> In commercial systems, a pervasive requirement for automatic data preparation (ADP) is to transfer relational data from disparate sources to targets with standardized schema specifications. Previous methods rely on labor-intensive supervision signals or target table data access permissions, limiting their usage in real-world scenarios. To tackle these challenges, we propose an effective end-to-end ADP framework MontePrep, which enables training-free pipeline synthesis with zero target-instance requirements. MontePrep is formulated as an open-source large language model (LLM) powered tree-structured search problem. It consists of three pivot components, i.e., a data preparation action sandbox (DPAS), a fundamental pipeline generator (FPG), and an execution-aware pipeline optimizer (EPO). We first introduce DPAS, a lightweight action sandbox, to navigate the search-based pipeline generation. The design of DPAS circumvents exploration of infeasible pipelines. Then, we present FPG to build executable DP pipelines incrementally, which explores the predefined action sandbox by the LLM-powered Monte Carlo Tree Search. Furthermore, we propose EPO, which invokes pipeline execution results from sources to targets to evaluate the reliability of the generated pipelines in FPG. In this way, unreasonable pipelines are eliminated, thus facilitating the search process from both efficiency and effectiveness perspectives. Extensive experimental results demonstrate the superiority of MontePrep with significant improvement against five state-of-the-art competitors.

[Arxiv](https://arxiv.org/abs/2509.17553)