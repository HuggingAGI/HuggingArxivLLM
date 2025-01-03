# ReflecTool: 打造具备反思能力的工具增强型临床智能体

发布时间：2024年10月23日

`Agent

理由：这篇论文主要介绍了一个名为ClinicalAgent Bench（CAB）的医疗智能体基准，并提出了ReflecTool这一框架，用于在临床环境中高效利用领域特定工具。论文的核心内容围绕智能体（Agent）的设计、优化和推理过程展开，强调了智能体在复杂临床任务中的适应性和有效性。因此，这篇论文应归类为Agent。` `临床智能体`

> ReflecTool: Towards Reflection-Aware Tool-Augmented Clinical Agents

# 摘要

> # 摘要
大型语言模型（LLMs）在医疗领域展现出巨大潜力，能够辅助完成临床笔记生成和患者沟通等任务。然而，当前LLMs仅限于文本沟通，难以应对临床环境中多样化的信息形式。尽管临床智能体在多样化信号互动中表现出色，但它们仅适用于单一场景，难以广泛推广。为此，我们提出了ClinicalAgent Bench（CAB），一个涵盖五个关键临床维度的18项任务的综合医疗智能体基准。基于此，我们推出了ReflecTool，这一新颖框架擅长在两个阶段内高效利用领域特定工具。优化阶段通过保存成功解决过程和工具经验，逐步扩展长期记忆；推理阶段则从长期记忆中检索成功案例，指导工具选择策略，并通过迭代优化和候选选择两种验证方法改进工具使用。在ClinicalAgent Benchmark上的实验表明，ReflecTool比纯LLMs高出10分以上，比现有智能体方法高出3分，展现了其在复杂临床任务中的卓越适应性和有效性。

> Large Language Models (LLMs) have shown promising potential in the medical domain, assisting with tasks like clinical note generation and patient communication. However, current LLMs are limited to text-based communication, hindering their ability to interact with diverse forms of information in clinical environments. Despite clinical agents succeeding in diverse signal interaction, they are oriented to a single clinical scenario and hence fail for broader applications. To evaluate clinical agents holistically, we propose ClinicalAgent Bench~(CAB), a comprehensive medical agent benchmark consisting of 18 tasks across five key realistic clinical dimensions. Building on this, we introduce ReflecTool, a novel framework that excels at utilizing domain-specific tools within two stages. The first optimization stage progressively enlarges a long-term memory by saving successful solving processes and tool-wise experience of agents in a tiny pre-defined training set. In the following inference stage, ReflecTool can search for supportive successful demonstrations from already built long-term memory to guide the tool selection strategy, and a verifier improves the tool usage according to the tool-wise experience with two verification methods--iterative refinement and candidate selection. Extensive experiments on ClinicalAgent Benchmark demonstrate that ReflecTool surpasses the pure LLMs with more than 10 points and the well-established agent-based methods with 3 points, highlighting its adaptability and effectiveness in solving complex clinical tasks.

[Arxiv](https://arxiv.org/abs/2410.17657)