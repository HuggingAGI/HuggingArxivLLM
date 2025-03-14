# UniGoal：迈向通用零样本目标导向导航

发布时间：2025年03月13日

`LLM应用` `机器人` `人工智能`

> UniGoal: Towards Universal Zero-shot Goal-oriented Navigation

# 摘要

> 本文提出了一种通用的零样本目标导向导航框架。现有的零样本方法基于大型语言模型（LLM）为特定任务构建推理框架，在整体流程上差异很大，且无法在不同类型的任务目标之间进行泛化。为实现通用零样本导航的目标，我们提出了一种统一的图表示方法，以整合不同目标，包括物体类别、实例图像和文本描述。我们还将智能体的观察结果转换为一个在线维护的场景图。通过这种一致的场景和目标表示，我们保留了与纯文本相比的大部分结构信息，并能够利用LLM进行基于图的显式推理。具体而言，我们在每个时间点进行场景图和目标图之间的图匹配，并根据不同的匹配状态提出不同的策略来生成长期探索目标。当零匹配时，智能体首先迭代搜索目标子图。在部分匹配的情况下，智能体利用坐标投影和锚点对齐推断目标位置。最后，应用场景图修正和目标验证以实现完美匹配。我们还提出了一种黑名单机制，以实现阶段之间的鲁棒切换。在多个基准上的大量实验表明，我们的UniGoal在三个研究的导航任务中，仅使用一个模型就实现了最先进的零样本性能，甚至优于特定任务的零样本方法和监督通用方法。

> In this paper, we propose a general framework for universal zero-shot goal-oriented navigation. Existing zero-shot methods build inference framework upon large language models (LLM) for specific tasks, which differs a lot in overall pipeline and fails to generalize across different types of goal. Towards the aim of universal zero-shot navigation, we propose a uniform graph representation to unify different goals, including object category, instance image and text description. We also convert the observation of agent into an online maintained scene graph. With this consistent scene and goal representation, we preserve most structural information compared with pure text and are able to leverage LLM for explicit graph-based reasoning. Specifically, we conduct graph matching between the scene graph and goal graph at each time instant and propose different strategies to generate long-term goal of exploration according to different matching states. The agent first iteratively searches subgraph of goal when zero-matched. With partial matching, the agent then utilizes coordinate projection and anchor pair alignment to infer the goal location. Finally scene graph correction and goal verification are applied for perfect matching. We also present a blacklist mechanism to enable robust switch between stages. Extensive experiments on several benchmarks show that our UniGoal achieves state-of-the-art zero-shot performance on three studied navigation tasks with a single model, even outperforming task-specific zero-shot methods and supervised universal methods.

[Arxiv](https://arxiv.org/abs/2503.10630)