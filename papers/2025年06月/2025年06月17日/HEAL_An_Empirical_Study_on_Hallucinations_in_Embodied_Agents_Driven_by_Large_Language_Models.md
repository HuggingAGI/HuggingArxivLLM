# HEAL：关于大型语言模型驱动的具身智能体幻觉现象的实证研究

发布时间：2025年06月17日

`Agent` `智能体` `认知科学`

> HEAL: An Empirical Study on Hallucinations in Embodied Agents Driven by Large Language Models

# 摘要

> 大型语言模型 (LLMs) 正逐渐成为具身智能体 (embodied agents) 的认知核心。但由用户指令与物理环境脱节引发的幻觉，可能导致导航错误，例如寻找不存在的冰箱。本文首次系统研究了基于 LLM 的具身智能体在场景-任务不一致情况下执行长时段任务时的幻觉现象。我们旨在揭示幻觉的发生程度、触发幻觉的不一致类型，以及当前模型的应对方式。通过构建基于现有基准的幻觉探测集，我们实现了比基础提示高出 40 倍的幻觉率。在两个模拟环境中评估 12 个模型后发现，尽管模型具备推理能力，但无法解决场景-任务不一致问题，这凸显了处理不可行任务的基本局限。我们还为每种场景提供了可操作的见解，为开发更健壮和可靠的规划策略提供了指导。

> Large language models (LLMs) are increasingly being adopted as the cognitive core of embodied agents. However, inherited hallucinations, which stem from failures to ground user instructions in the observed physical environment, can lead to navigation errors, such as searching for a refrigerator that does not exist. In this paper, we present the first systematic study of hallucinations in LLM-based embodied agents performing long-horizon tasks under scene-task inconsistencies. Our goal is to understand to what extent hallucinations occur, what types of inconsistencies trigger them, and how current models respond. To achieve these goals, we construct a hallucination probing set by building on an existing benchmark, capable of inducing hallucination rates up to 40x higher than base prompts. Evaluating 12 models across two simulation environments, we find that while models exhibit reasoning, they fail to resolve scene-task inconsistencies-highlighting fundamental limitations in handling infeasible tasks. We also provide actionable insights on ideal model behavior for each scenario, offering guidance for developing more robust and reliable planning strategies.

[Arxiv](https://arxiv.org/abs/2506.15065)