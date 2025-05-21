# LODGE：联合分层任务规划与基于实例的领域模型学习

发布时间：2025年05月15日

`LLM应用` `机器人` `规划系统`

> LODGE: Joint Hierarchical Task Planning and Learning of Domain Models with Grounded Execution

# 摘要

> 大型语言模型（LLMs）能够根据自然语言指令利用隐性世界知识进行规划，但常常生成需要修正的错误计划。与直接预测计划不同，近期方法致力于学习一个可解问题域，使其能够使用经典规划器针对不同目标状态进行求解。然而，这些方法需要大量的人工反馈才能获得有用的模型。我们通过学习分层领域来克服这一局限，其中低层级的谓词和动作被组合成高层级的对应项，并通过模拟来验证其先决条件和效果。这种分层方法在长时域规划中特别强大，而基于LLM的规划方法通常在这一领域表现不佳。此外，我们引入了一个中心错误推理器，以确保不同规划层级之间的一致性。在两个具有挑战性的国际规划竞赛（IPC）领域和一个长时域机器人操作任务上的评估表明，与最先进的领域合成和LLM模组化规划方法相比，我们的方法不仅取得了更高的规划成功率，还构建了高质量的领域模型。资源、视频和详细实验结果可在https://claudius-kienle.github.io/lodge/获取。

> Large Language Models (LLMs) enable planning from natural language instructions using implicit world knowledge, but often produce flawed plans that require refinement. Instead of directly predicting plans, recent methods aim to learn a problem domain that can be solved for different goal states using classical planners. However, these approaches require significant human feedback to obtain useful models. We address this shortcoming by learning hierarchical domains, where low-level predicates and actions are composed into higher-level counterparts, and by leveraging simulation to validate their preconditions and effects. This hierarchical approach is particularly powerful for long-horizon planning, where LLM-based planning approaches typically struggle. Furthermore, we introduce a central error reasoner to ensure consistency among the different planning levels. Evaluation on two challenging International Planning Competition (IPC) domains and a long-horizon robot manipulation task demonstrates higher planning success rates than state-of-the-art domain synthesis and LLM-modulo planning methods, while constructing high-quality models of the domain. Resources, videos and detailed experiment results are available at https://claudius-kienle.github.io/lodge/.

[Arxiv](https://arxiv.org/abs/2505.13497)