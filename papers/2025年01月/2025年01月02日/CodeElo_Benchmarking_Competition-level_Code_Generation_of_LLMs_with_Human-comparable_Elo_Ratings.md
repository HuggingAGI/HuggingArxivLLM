# CodeElo：以与人类可比的 Elo 评级为基准，对 LLMs 的竞赛级代码生成能力进行测试

发布时间：2025年01月02日

`LLM应用` `软件开发` `代码竞赛`

> CodeElo: Benchmarking Competition-level Code Generation of LLMs with Human-comparable Elo Ratings

# 摘要

> 随着现有大型语言模型（LLMs）的代码推理能力持续提升，以及 OpenAI o1 和 o3 等推理模型实现突破，开发更具挑战性和综合性、能有效测试其复杂竞赛级编码能力的基准测试的需求愈发迫切。现有的基准测试，如 LiveCodeBench 和 USACO，因缺乏私人测试用例、不支持特殊评委以及执行环境不一致等存在缺陷。为填补这一空缺，我们推出了 CodeElo，这是首个有效应对所有这些挑战的标准化竞赛级代码生成基准测试。CodeElo 基准测试主要依托官方的 CodeForces 平台，并尽可能与之契合。我们整理了 CodeForces 上近六个月的竞赛题目，包含竞赛分区、题目难度评级和题目算法标签等详细信息。我们引入了独特的评判方式，即直接向平台提交题目，并开发了可靠的 Elo 评分计算系统，该系统与平台一致，可与人类参与者相比，且方差更低。通过在 CodeElo 上进行测试，我们首次给出了 30 个现有的热门开源和 3 个专有的 LLMs 的 Elo 评分。结果显示，o1-mini 和 QwQ-32B-Preview 表现突出，Elo 评分分别达 1578 和 1261，而其他模型即便面对最简单的问题也表现不佳，在所有人类参与者中处于最低的 20%。此外，还开展了详细的分析实验，以提供不同算法的性能见解以及 C++和 Python 使用的比较，为未来研究指明方向。

> With the increasing code reasoning capabilities of existing large language models (LLMs) and breakthroughs in reasoning models like OpenAI o1 and o3, there is a growing need to develop more challenging and comprehensive benchmarks that effectively test their sophisticated competition-level coding abilities. Existing benchmarks, like LiveCodeBench and USACO, fall short due to the unavailability of private test cases, lack of support for special judges, and misaligned execution environments. To bridge this gap, we introduce CodeElo, a standardized competition-level code generation benchmark that effectively addresses all these challenges for the first time. CodeElo benchmark is mainly based on the official CodeForces platform and tries to align with the platform as much as possible. We compile the recent six months of contest problems on CodeForces with detailed information such as contest divisions, problem difficulty ratings, and problem algorithm tags. We introduce a unique judging method in which problems are submitted directly to the platform and develop a reliable Elo rating calculation system that aligns with the platform and is comparable with human participants but has lower variance. By testing on our CodeElo, we provide the Elo ratings of 30 existing popular open-source and 3 proprietary LLMs for the first time. The results show that o1-mini and QwQ-32B-Preview stand out significantly, achieving Elo ratings of 1578 and 1261, respectively, while other models struggle even with the easiest problems, placing in the lowest 20 percent among all human participants. Detailed analysis experiments are also conducted to provide insights into performance across algorithms and comparisons between using C++ and Python, which can suggest directions for future studies.

[Arxiv](https://arxiv.org/abs/2501.01257)