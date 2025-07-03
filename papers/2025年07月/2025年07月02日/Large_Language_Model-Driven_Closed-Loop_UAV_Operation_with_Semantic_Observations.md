# 大型语言模型驱动的闭环无人机语义观测操作

发布时间：2025年07月02日

`LLM应用` `航空航天` `机器人`

> Large Language Model-Driven Closed-Loop UAV Operation with Semantic Observations

# 摘要

> 大型语言模型（LLMs）彻底革新了机器人自主性，包括无人机（UAVs）。近期研究表明，LLMs具有将人类指令转化为无人机操作可执行控制代码的潜力。然而，LLMs在逻辑推理和复杂决策方面仍面临挑战，这引发了人们对LLM驱动的无人机操作可靠性的担忧。本文中，我们提出了一种基于LLM的闭环控制框架，该框架通过两个LLM模块（即代码生成器和评估器）实现有效的反馈和优化，从而实现可靠的无人机操作。我们的框架将无人机操作的数值状态观测结果转化为自然语言轨迹描述，以增强评估器LLM对无人机动态的理解，从而生成精确的反馈。此外，我们的框架还支持基于模拟的优化过程，从而消除了在优化过程中由于错误代码执行对物理无人机造成的风险。我们在不同复杂度的无人机控制任务上进行了大量实验。实验结果表明，我们的框架能够实现基于LLMs的可靠无人机操作，在成功率和任务完成度方面显著优于基线方法，且随着任务复杂度的增加，优势更加明显。

> Large Language Models (LLMs) have revolutionized robotic autonomy, including Unmanned Aerial Vehicles (UAVs). Recent studies have demonstrated the potential of LLMs for translating human instructions into executable control code for UAV operations. However, LLMs still face challenges from logical reasoning and complex decision-making, leading to concerns about the reliability of LLM-driven UAV operations. In this paper, we propose a LLM-driven closed-loop control framework that enables reliable UAV operations powered by effective feedback and refinement using two LLM modules, i.e., a Code Generator and an Evaluator. Our framework transforms numerical state observations from UAV operations into natural language trajectory descriptions to enhance the evaluator LLM's understanding of UAV dynamics for precise feedback generation. Our framework also enables a simulation-based refinement process, and hence eliminates the risks to physical UAVs caused by incorrect code execution during the refinement. Extensive experiments on UAV control tasks with different complexities are conducted. The experimental results show that our framework can achieve reliable UAV operations using LLMs, which significantly outperforms baseline approaches in terms of success rate and completeness with the increase of task complexity.

[Arxiv](https://arxiv.org/abs/2507.01930)