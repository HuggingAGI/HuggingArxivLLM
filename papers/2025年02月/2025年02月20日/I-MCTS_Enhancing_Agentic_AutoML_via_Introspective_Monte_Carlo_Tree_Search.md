# I-MCTS: 通过内省蒙特卡洛树搜索方法，我们能够有效提升智能体自动机器学习的能力

发布时间：2025年02月20日

`LLM应用` `机器学习` `自动化`

> I-MCTS: Enhancing Agentic AutoML via Introspective Monte Carlo Tree Search

# 摘要

> 近年来，大型语言模型（LLMs）在机器学习任务自动化方面展现出巨大潜力。然而，现有的基于LLM的自动化代理在生成多样性不足和次优代码方面仍面临挑战。尽管近期研究引入了蒙特卡洛树搜索（MCTS）来解决这些问题，但生成的思路质量和多样性仍然有限，同时用于节点选择的标量值反馈机制也存在不足。在本研究中，我们提出了内省式蒙特卡洛树搜索（I-MCTS），这是一种通过内省过程迭代扩展树节点的新方法。该过程会细致分析父节点和兄弟节点的解决方案及结果，从而实现搜索树中节点的持续优化，提升整体决策流程。此外，我们还引入了基于大型语言模型（LLM）的价值模型，以便在进行全面计算展开之前，直接评估每个节点的解决方案。通过一种混合奖励机制，我们实现了从LLM估计分数到实际性能分数的无缝过渡，使更高质量的节点能够被优先访问。应用于多种机器学习任务中，我们的方法与强大的开源AutoML代理相比，性能提升了6%的绝对值，充分证明了其在增强自动化机器学习系统中的有效性。

> Recent advancements in large language models (LLMs) have shown remarkable potential in automating machine learning tasks. However, existing LLM-based agents often struggle with low-diversity and suboptimal code generation. While recent work has introduced Monte Carlo Tree Search (MCTS) to address these issues, limitations persist in the quality and diversity of thoughts generated, as well as in the scalar value feedback mechanisms used for node selection. In this study, we introduce Introspective Monte Carlo Tree Search (I-MCTS), a novel approach that iteratively expands tree nodes through an introspective process that meticulously analyzes solutions and results from parent and sibling nodes. This facilitates a continuous refinement of the node in the search tree, thereby enhancing the overall decision-making process.Furthermore, we integrate a Large Language Model (LLM)-based value model to facilitate direct evaluation of each node's solution prior to conducting comprehensive computational rollouts. A hybrid rewarding mechanism is implemented to seamlessly transition the Q-value from LLM-estimated scores to actual performance scores. This allows higher-quality nodes to be traversed earlier.Applied to the various ML tasks, our approach demonstrates a6\% absolute improvement in performance compared to the strong open-source AutoML agents, showcasing its effectiveness in enhancing agentic AutoML systems.

[Arxiv](https://arxiv.org/abs/2502.14693)