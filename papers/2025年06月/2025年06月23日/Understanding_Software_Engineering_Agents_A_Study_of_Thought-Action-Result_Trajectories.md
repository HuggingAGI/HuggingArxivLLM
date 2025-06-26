# 认识软件工程代理：一项关于思维-行动-结果轨迹的研究

发布时间：2025年06月23日

`Agent

摘要讨论了基于LLM的代理在软件工程任务中的应用，分析了它们的思考-行动-结果轨迹，揭示了行为模式和反模式，为改进代理设计提供了见解。` `软件工程` `人工智能`

> Understanding Software Engineering Agents: A Study of Thought-Action-Result Trajectories

# 摘要

> 基于大型语言模型（LLM）的代理正越来越多地被用于自动化复杂的软件工程任务，例如程序修复和问题解决。这些代理通过自主生成自然语言思考、调用外部工具以及迭代优化解决方案来运作。尽管它们被广泛应用，但这些代理的内部决策过程仍然 largely 未被探索，限制了我们对它们运行动态和失败模式的理解。

本文中，我们对三个最先进的基于 LLM 的代理的思考-行动-结果轨迹进行了大规模实证研究：	extsc{RepairAgent}、	extsc{AutoCodeRover} 和 	extsc{OpenHands}。我们将它们的交互日志统一为一种通用格式，捕捉了 120 条轨迹和 2822 次 LLM 交互，专注于程序修复和问题解决。我们的研究结合了对结构属性、行动模式和令牌使用量的定量分析，以及对推理连贯性和反馈整合的定性评估。我们识别出关键的轨迹特征，如迭代次数和令牌消耗、重复的行动序列，以及将思考、行动及其结果联系起来的语义连贯性。

我们的发现揭示了成功与失败执行之间区分的行为模式和反模式，为改进代理设计提供了可操作的见解，包括提示策略、故障诊断和反模式检测。我们发布了我们的数据集和标注框架，以支持对透明且健壮的自主软件工程代理的进一步研究。

> Large Language Model (LLM)-based agents are increasingly employed to automate complex software engineering tasks such as program repair and issue resolution. These agents operate by autonomously generating natural language thoughts, invoking external tools, and iteratively refining their solutions. Despite their widespread adoption, the internal decision-making processes of these agents remain largely unexplored, limiting our understanding of their operational dynamics and failure modes. In this paper, we present a large-scale empirical study of the thought-action-result trajectories of three state-of-the-art LLM-based agents: \textsc{RepairAgent}, \textsc{AutoCodeRover}, and \textsc{OpenHands}. We unify their interaction logs into a common format, capturing 120 trajectories and 2822 LLM interactions focused on program repair and issue resolution. Our study combines quantitative analyses of structural properties, action patterns, and token usage with qualitative assessments of reasoning coherence and feedback integration. We identify key trajectory characteristics such as iteration counts and token consumption, recurring action sequences, and the semantic coherence linking thoughts, actions, and their results. Our findings reveal behavioral motifs and anti-patterns that distinguish successful from failed executions, providing actionable insights for improving agent design, including prompting strategies, failure diagnosis, and anti-pattern detection. We release our dataset and annotation framework to support further research on transparent and robust autonomous software engineering agents.

[Arxiv](https://arxiv.org/abs/2506.18824)