# InfiGUIAgent: 具备原生推理与反思能力的多模态通用GUI代理

发布时间：2025年01月08日

`Agent

理由：这篇论文介绍了一种基于多模态大型语言模型（MLLM）的图形用户界面（GUI）代理，名为 InfiGUIAgent。该代理通过两阶段监督微调管道进行训练，旨在提升 GUI 交互自动化任务的效果。论文的核心内容围绕代理的设计、训练和性能评估展开，属于 Agent 类别。` `人机交互` `自动化`

> InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection

# 摘要

> # 图形用户界面（GUI）代理
多模态大型语言模型（MLLMs）驱动的 GUI 代理在计算机和手机等设备上的任务自动化中展现了巨大潜力。然而，现有代理在多步推理和文本注释依赖方面存在局限，影响了其效果。我们推出了 	extit{InfiGUIAgent}，一种基于 MLLM 的 GUI 代理，采用两阶段监督微调管道进行训练。第一阶段强化了 GUI 理解和基础等核心技能，第二阶段则通过合成数据整合了分层推理和期望-反思推理技能，赋予代理原生推理能力。	extit{InfiGUIAgent} 在多个 GUI 基准测试中表现优异，证明了原生推理技能在提升 GUI 交互自动化任务中的重要作用。资源可在 url{https://github.com/Reallm-Labs/InfiGUIAgent} 获取。

> Graphical User Interface (GUI) Agents, powered by multimodal large language models (MLLMs), have shown great potential for task automation on computing devices such as computers and mobile phones. However, existing agents face challenges in multi-step reasoning and reliance on textual annotations, limiting their effectiveness. We introduce \textit{InfiGUIAgent}, an MLLM-based GUI Agent trained with a two-stage supervised fine-tuning pipeline. Stage 1 enhances fundamental skills such as GUI understanding and grounding, while Stage 2 integrates hierarchical reasoning and expectation-reflection reasoning skills using synthesized data to enable native reasoning abilities of the agents. \textit{InfiGUIAgent} achieves competitive performance on several GUI benchmarks, highlighting the impact of native reasoning skills in enhancing GUI interaction for automation tasks. Resources are available at url{https://github.com/Reallm-Labs/InfiGUIAgent}.

[Arxiv](https://arxiv.org/abs/2501.04575)