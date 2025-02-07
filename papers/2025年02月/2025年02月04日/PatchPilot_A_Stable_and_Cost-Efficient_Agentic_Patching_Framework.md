# PatchPilot: 稳定高效的智能体补丁框架

发布时间：2025年02月04日

`Agent

理由：这篇论文主要讨论了一种名为PatchPilot的智能修补代理，它结合了大型语言模型（LLMs）和非机器学习工具，用于软件修补任务。论文详细描述了PatchPilot的设计和实现，包括其基于人类的规划流程和五个模块（重现、定位、生成、验证和优化）。这些内容表明该论文的核心是开发和应用一种智能代理系统，因此应归类为Agent。` `软件工程` `自动化`

> PatchPilot: A Stable and Cost-Efficient Agentic Patching Framework

# 摘要

> # 摘要
近期研究开发了多种修补代理，将大型语言模型（LLMs）与非机器学习工具结合，并在顶级软件修补基准SWE-Bench上取得了显著成果。现有修补代理可分为两类：基于代理的规划方法依赖LLMs进行规划，而基于人类的规划方法则遵循预定义流程。总体来看，基于代理的方法修补性能高，但成本高且稳定性不足；基于人类的方法则更稳定高效，但受限于工作流程，修补性能有所折损。本文提出PatchPilot，一种智能修补代理，在修补效果、稳定性和成本效益之间实现了平衡。PatchPilot采用了一种新颖的基于人类的规划流程，包含五个模块：重现、定位、生成、验证和优化（优化为PatchPilot独有）。我们为每个模块设计了定制化方案，以提升其效能和效率。通过在SWE-Bench上的大量实验，PatchPilot展现了优于现有开源方法的性能，同时保持低成本（每个实例不到1美元）和高稳定性。我们还通过详细的消融研究验证了各模块的关键设计。

> Recent research builds various patching agents that combine large language models (LLMs) with non-ML tools and achieve promising results on the state-of-the-art (SOTA) software patching benchmark, SWE-Bench. Based on how to determine the patching workflows, existing patching agents can be categorized as agent-based planning methods, which rely on LLMs for planning, and human-based planning methods, which follow a pre-defined workflow. At a high level, agent-based planning methods achieve high patching performance but with a high cost and limited stability. Human-based planning methods, on the other hand, are more stable and efficient but have key workflow limitations that compromise their patching performance. In this paper, we propose PatchPilot, an agentic patcher that strikes a balance between patching efficacy, stability, and cost-efficiency. PatchPilot proposes a novel human-based planning workflow with five components: reproduction, localization, generation, validation, and refinement (where refinement is unique to PatchPilot). We introduce novel and customized designs to each component to optimize their effectiveness and efficiency. Through extensive experiments on the SWE-Bench benchmarks, PatchPilot shows a superior performance than existing open-source methods while maintaining low cost (less than 1$ per instance) and ensuring higher stability. We also conduct a detailed ablation study to validate the key designs in each component.

[Arxiv](https://arxiv.org/abs/2502.02747)