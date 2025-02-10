# 自适应思维图：整合链式、树状与图式结构的测试时自适应推理

发布时间：2025年02月07日

`LLM理论` `人工智能`

> Adaptive Graph of Thoughts: Test-Time Adaptive Reasoning Unifying Chain, Tree, and Graph Structures

# 摘要

> 大型语言模型 (LLMs) 虽然展现了强大的推理能力，但其表现受提示策略和模型规模的制约。尽管强化学习和微调能提升推理，却带来了高昂的计算与数据成本。我们提出自适应思维图谱 (Adaptive Graph of Thoughts, AGoT)，一个动态的图式推理框架，仅在推理阶段增强 LLM 的能力。不同于固定步长的思维链 (CoT) 或思维树 (ToT)，AGoT 递归分解复杂查询为结构化子问题，构建动态有向无环图 (DAG)，实现相互依赖的推理步骤。通过仅扩展需进一步分析的子问题，AGoT 融合链式、树式与图式范式优势，精准分配计算资源。我们在多跳检索、科学推理和数学解题的基准测试中验证了 AGoT，使其在科学推理任务 (GPQA) 上性能提升高达 46.2%，媲美强化学习方法，超越现有迭代方案。这表明，动态分解与结构化递归为提升 LLM 推理提供了高效可行的途径，助力实现更强大、通用的推理能力。

> Large Language Models (LLMs) have demonstrated impressive reasoning capabilities, yet their performance is highly dependent on the prompting strategy and model scale. While reinforcement learning and fine-tuning have been deployed to boost reasoning, these approaches incur substantial computational and data overhead. In this work, we introduce Adaptive Graph of Thoughts (AGoT), a dynamic, graph-based inference framework that enhances LLM reasoning solely at test time. Rather than relying on fixed-step methods like Chain of Thought (CoT) or Tree of Thoughts (ToT), AGoT recursively decomposes complex queries into structured subproblems, forming an dynamic directed acyclic graph (DAG) of interdependent reasoning steps. By selectively expanding only those subproblems that require further analysis, AGoT unifies the strengths of chain, tree, and graph paradigms into a cohesive framework that allocates computation where it is most needed. We validate our approach on diverse benchmarks spanning multi-hop retrieval, scientific reasoning, and mathematical problem-solving, achieving up to 46.2% improvement on scientific reasoning tasks (GPQA) - comparable to gains achieved through computationally intensive reinforcement learning approaches and outperforming state-of-the-art iterative approaches. These results suggest that dynamic decomposition and structured recursion offer a scalable, cost-effective alternative to post-training modifications, paving the way for more robust, general-purpose reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2502.05078)