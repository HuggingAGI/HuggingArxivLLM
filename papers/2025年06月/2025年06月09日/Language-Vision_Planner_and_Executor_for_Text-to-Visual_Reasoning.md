# 语言-视觉规划与执行系统，用于文本到视觉推理

发布时间：2025年06月09日

`Agent` `视觉推理` `多模态应用`

> Language-Vision Planner and Executor for Text-to-Visual Reasoning

# 摘要

> 大型语言模型（LLMs）与视觉模型的突破推动了多模态视觉文本推理能力的快速发展。然而，现有视觉语言模型（VLMs）在泛化性能上仍存在不足。受LLMs在视觉推理领域的最新进展启发，本文提出了一种名为VLAgent的AI系统。该系统通过基于LLMs的自动化流程，结合规划脚本与执行验证，实时生成并执行逐步视觉推理计划。

在任务规划阶段，VLAgent利用上下文学习微调LLMs，为每个用户提交的文本-视觉推理任务生成逐步规划器。在计划执行阶段，VLAgent逐步优化神经符号可执行模块的组合，以生成高置信度推理结果。VLAgent具有三大独特设计特点：

1. 通过上下文学习提升规划生成质量，减少错误逻辑步骤、错误程序和LLMs幻觉，从而增强逻辑推理能力。
2. 设计了一种语法学-语义解析器，在启动计划执行器之前识别并纠正LLMs生成规划脚本中的额外逻辑错误。
3. 采用集成方法提升步骤执行器的泛化性能。

在GQA、MME、NLVR2和VQAv2四个视觉推理基准测试上的广泛实验表明，与现有代表性的VLMs和基于LLMs的视觉组合方法（如ViperGPT和VisProg）相比，VLAgent在多模态文本-视觉推理应用中实现了显著的性能提升。这一优势得益于VLAgent后端引擎中的新型优化模块（SS-Parser、Plan Repairer、Output Verifiers）。代码和数据将在论文接受后公开。

> The advancement in large language models (LLMs) and large vision models has fueled the rapid progress in multi-modal visual-text reasoning capabilities. However, existing vision-language models (VLMs) to date suffer from generalization performance. Inspired by recent development in LLMs for visual reasoning, this paper presents VLAgent, an AI system that can create a step-by-step visual reasoning plan with an easy-to-understand script and execute each step of the plan in real time by integrating planning script with execution verifications via an automated process supported by VLAgent. In the task planning phase, VLAgent fine-tunes an LLM through in-context learning to generate a step-by-step planner for each user-submitted text-visual reasoning task. During the plan execution phase, VLAgent progressively refines the composition of neuro-symbolic executable modules to generate high-confidence reasoning results. VLAgent has three unique design characteristics: First, we improve the quality of plan generation through in-context learning, improving logic reasoning by reducing erroneous logic steps, incorrect programs, and LLM hallucinations. Second, we design a syntax-semantics parser to identify and correct additional logic errors of the LLM-generated planning script prior to launching the plan executor. Finally, we employ the ensemble method to improve the generalization performance of our step-executor. Extensive experiments with four visual reasoning benchmarks (GQA, MME, NLVR2, VQAv2) show that VLAgent achieves significant performance enhancement for multimodal text-visual reasoning applications, compared to the exiting representative VLMs and LLM based visual composition approaches like ViperGPT and VisProg, thanks to the novel optimization modules of VLAgent back-engine (SS-Parser, Plan Repairer, Output Verifiers). Code and data will be made available upon paper acceptance.

[Arxiv](https://arxiv.org/abs/2506.07778)