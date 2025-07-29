# MazeEval：语言模型序列决策能力评测基准

发布时间：2025年07月27日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在空间推理和导航任务中的应用，特别是在无视觉输入的情况下的表现。研究通过引入MazeEval基准测试，评估了LLMs在不同语言环境下的空间推理能力，揭示了模型在空间导航中的局限性和依赖性。这属于对LLMs在特定任务中的应用研究，因此归类为LLM应用。` `机器人` `人工智能`

> MazeEval: A Benchmark for Testing Sequential Decision-Making in Language Models

# 摘要

> 随着大型语言模型（LLMs）在机器人和具身AI中的广泛应用，理解其空间推理能力对现实世界部署至关重要。尽管语言理解技术不断进步，现有研究仍缺乏对LLMs在无视觉线索情况下空间导航能力的评估，这对依赖有限感官信息的智能体尤为重要。本文通过引入MazeEval填补这一空白，该基准测试通过基于坐标的迷宫导航任务，孤立并评估LLMs的纯空间推理能力。

我们的方法采用函数调用接口，模型仅通过坐标反馈和距离墙壁信息在5×5到15×15网格的迷宫中进行导航，完全排除视觉输入以测试基础空间认知。我们对八种先进LLMs进行了评估，使用相同迷宫在英语和冰岛语环境下测试跨语言的空间能力迁移。

研究发现显示显著差异：OpenAI的O3模型在30×30规模迷宫中实现完美导航，而其他模型在9×9以上规模迷宫中表现灾难性，所有失败案例均因过度循环行为导致（重复访问同一单元格至少10次）。冰岛语环境中的模型性能显著下降，解决的迷宫规模比英语环境小3-4个等级，表明LLMs的空间推理能力源于语言模式，而非通用机制。

这些结果对全球LLM驱动自主系统部署具有重要启示，表明空间智能受限于训练数据可用性，并强调了跨语言背景下实现可靠导航所需的架构创新需求。

> As Large Language Models (LLMs) increasingly power autonomous agents in robotics and embodied AI, understanding their spatial reasoning capabilities becomes crucial for ensuring reliable real-world deployment. Despite advances in language understanding, current research lacks evaluation of how LLMs perform spatial navigation without visual cues, a fundamental requirement for agents operating with limited sensory information. This paper addresses this gap by introducing MazeEval, a benchmark designed to isolate and evaluate pure spatial reasoning in LLMs through coordinate-based maze navigation tasks. Our methodology employs a function-calling interface where models navigate mazes of varying complexity ($5\times 5$ to $15\times 15$ grids) using only coordinate feedback and distance-to-wall information, excluding visual input to test fundamental spatial cognition. We evaluate eight state-of-the-art LLMs across identical mazes in both English and Icelandic to assess cross-linguistic transfer of spatial abilities. Our findings reveal striking disparities: while OpenAI's O3 achieves perfect navigation for mazes up to size $30\times 30$, other models exhibit catastrophic failure beyond $9\times 9$ mazes, with 100% of failures attributed to excessive looping behavior where models revisit a cell at least 10 times. We document a significant performance degradation in Icelandic, with models solving mazes 3-4 sizes smaller than in English, suggesting spatial reasoning in LLMs emerges from linguistic patterns rather than language-agnostic mechanisms. These results have important implications for global deployment of LLM-powered autonomous systems, showing spatial intelligence remains fundamentally constrained by training data availability and highlighting the need for architectural innovations to achieve reliable navigation across linguistic contexts.

[Arxiv](https://arxiv.org/abs/2507.20395)