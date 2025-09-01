# RoboInspector：揭秘LLM驱动的机器人操作中策略代码的不可靠性

发布时间：2025年08月29日

`LLM应用` `工业与制造`

> RoboInspector: Unveiling the Unreliability of Policy Code for LLM-enabled Robotic Manipulation

# 摘要

> 大型语言模型（LLMs）凭借卓越的推理与代码生成能力，让机器人操作仅需一条指令即可启动——LLM通过生成控制机器人的策略代码来执行各类任务。然而，尽管LLMs不断进步，现实任务的多样化需求与用户指令的复杂性仍使可靠策略代码的生成立为一大挑战：实际应用中，不同用户对同一任务可能给出不同指令，这极易导致策略代码生成出现偏差。为此，我们设计了RoboInspector分析框架，从操作任务复杂性与指令粒度两个维度，揭示并剖析LLM驱动机器人操作时策略代码的不可靠性。我们在两个主流框架中，针对任务、指令与LLM的168种组合开展了全面实验，结果发现四种导致操作失败的核心不可靠行为。我们详细阐述了这些行为的表现及其深层原因，为降低不可靠性提供了实践开发思路。此外，我们还提出一种基于失败策略代码反馈的优化方案，在模拟与现实环境中，该方案将LLM驱动机器人操作的策略代码生成可靠性提升了最高35%。

> Large language models (LLMs) demonstrate remarkable capabilities in reasoning and code generation, enabling robotic manipulation to be initiated with just a single instruction. The LLM carries out various tasks by generating policy code required to control the robot. Despite advances in LLMs, achieving reliable policy code generation remains a significant challenge due to the diverse requirements of real-world tasks and the inherent complexity of user instructions. In practice, different users may provide distinct instructions to drive the robot for the same task, which may cause the unreliability of policy code generation. To bridge this gap, we design RoboInspector, a pipeline to unveil and characterize the unreliability of the policy code for LLM-enabled robotic manipulation from two perspectives: the complexity of the manipulation task and the granularity of the instruction. We perform comprehensive experiments with 168 distinct combinations of tasks, instructions, and LLMs in two prominent frameworks. The RoboInspector identifies four main unreliable behaviors that lead to manipulation failure. We provide a detailed characterization of these behaviors and their underlying causes, giving insight for practical development to reduce unreliability. Furthermore, we introduce a refinement approach guided by failure policy code feedback that improves the reliability of policy code generation by up to 35% in LLM-enabled robotic manipulation, evaluated in both simulation and real-world environments.

[Arxiv](https://arxiv.org/abs/2508.21378)