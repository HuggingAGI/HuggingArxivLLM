# LLM推理模型能否替代经典规划？一项基准研究

发布时间：2025年07月31日

`LLM应用` `机器人` `任务规划`

> Can LLM-Reasoning Models Replace Classical Planning? A Benchmark Study

# 摘要

> 大型语言模型的最新进展激发了人们对它们在机器人任务规划中潜力的兴趣。尽管这些模型展现出强大的生成能力，但它们在生成结构化且可执行计划方面的有效性仍存疑。本文系统性地评估了当前一系列最先进语言模型的表现，这些模型直接使用规划领域定义语言（PDDL）的领域和问题文件进行提示，并将其规划性能与快速向下规划器（Fast Downward）在多种基准上进行对比。除了测量成功率外，我们还评估生成的计划在多大程度上能够转化为实际可执行的动作序列，从而识别出在这一设置下使用这些模型的优势与局限。我们的研究发现，尽管这些模型在较为简单的规划任务中表现良好，但它们在需要精确资源管理、一致状态跟踪和严格约束遵守的更复杂场景中仍然面临挑战。这些结果突显了将语言模型应用于真实世界环境下机器人规划所面临的基本挑战。通过揭示执行过程中出现的差距，我们希望引导未来研究走向结合语言模型与经典规划器的综合方法，从而提升自主机器人规划的可靠性和可扩展性。

> Recent advancements in Large Language Models have sparked interest in their potential for robotic task planning. While these models demonstrate strong generative capabilities, their effectiveness in producing structured and executable plans remains uncertain. This paper presents a systematic evaluation of a broad spectrum of current state of the art language models, each directly prompted using Planning Domain Definition Language domain and problem files, and compares their planning performance with the Fast Downward planner across a variety of benchmarks. In addition to measuring success rates, we assess how faithfully the generated plans translate into sequences of actions that can actually be executed, identifying both strengths and limitations of using these models in this setting. Our findings show that while the models perform well on simpler planning tasks, they continue to struggle with more complex scenarios that require precise resource management, consistent state tracking, and strict constraint compliance. These results underscore fundamental challenges in applying language models to robotic planning in real world environments. By outlining the gaps that emerge during execution, we aim to guide future research toward combined approaches that integrate language models with classical planners in order to enhance the reliability and scalability of planning in autonomous robotics.

[Arxiv](https://arxiv.org/abs/2507.23589)