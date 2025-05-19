# 任务规划中，具身智能体能否理解模糊的人类指令？让我们一起探索 REI-Bench 的研究成果！

发布时间：2025年05月16日

`LLM应用

理由：这篇论文探讨了基于大型语言模型（LLM）的机器人任务规划在处理模糊指令时的挑战，并提出了改进方法。它属于LLM的实际应用，特别是在机器人与人类交互中的具体问题解决。` `机器人` `人机交互`

> REI-Bench: Can Embodied Agents Understand Vague Human Instructions in Task Planning?

# 摘要

> 机器人任务规划通过将人类指令转化为可执行的动作序列，帮助机器人完成复杂任务。尽管基于大型语言模型（LLM）的任务规划器表现出色，但它们依赖于人类指令的清晰无误。然而，现实中的用户往往并非专家，他们的指令充满模糊性，尤其在老年人和儿童中更为普遍。本文研究了人类指令中模糊指代表达式（REs）对基于LLM的机器人任务规划的影响。为此，我们提出了首个包含模糊REs的机器人任务规划基准（REI-Bench），发现REs的模糊性会导致机器人规划成功率骤降，幅度高达77.9%。我们还发现，多数失败案例源于规划器中缺少关键物体。为解决这一问题，我们提出了一种简单而有效的方法：任务导向的上下文理解，该方法能为机器人生成清晰指令，在性能上优于现有方法，达到当前最优水平。这项工作通过提升机器人任务规划的实用性，特别是在服务非专家用户方面，为机器人与人类交互（HRI）研究领域做出了重要贡献。

> Robot task planning decomposes human instructions into executable action sequences that enable robots to complete a series of complex tasks. Although recent large language model (LLM)-based task planners achieve amazing performance, they assume that human instructions are clear and straightforward. However, real-world users are not experts, and their instructions to robots often contain significant vagueness. Linguists suggest that such vagueness frequently arises from referring expressions (REs), whose meanings depend heavily on dialogue context and environment. This vagueness is even more prevalent among the elderly and children, who robots should serve more. This paper studies how such vagueness in REs within human instructions affects LLM-based robot task planning and how to overcome this issue. To this end, we propose the first robot task planning benchmark with vague REs (REI-Bench), where we discover that the vagueness of REs can severely degrade robot planning performance, leading to success rate drops of up to 77.9%. We also observe that most failure cases stem from missing objects in planners. To mitigate the REs issue, we propose a simple yet effective approach: task-oriented context cognition, which generates clear instructions for robots, achieving state-of-the-art performance compared to aware prompt and chains of thought. This work contributes to the research community of human-robot interaction (HRI) by making robot task planning more practical, particularly for non-expert users, e.g., the elderly and children.

[Arxiv](https://arxiv.org/abs/2505.10872)