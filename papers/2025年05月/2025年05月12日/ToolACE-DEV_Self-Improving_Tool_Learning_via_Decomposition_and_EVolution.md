# # ToolACE-DEV: 通过分解与进化实现自我改进的工具学习方法。

发布时间：2025年05月12日

`LLM应用` `工具学习` `模型增强`

> ToolACE-DEV: Self-Improving Tool Learning via Decomposition and EVolution

# 摘要

> 大型语言模型（LLMs）的工具使用能力使其能够访问最新的外部信息并处理复杂任务。然而，现有的增强能力的方法主要依赖于通过数据合成蒸馏先进模型，这不仅成本高昂，还常常引发数据兼容性问题，其根源在于先进模型与目标模型知识范围的巨大差异。为此，我们提出了ToolACE-DEV，一个自我改进的工具学习框架。首先，我们将工具学习目标分解为提升基础工具制造和工具使用能力的子任务。接着，我们引入了一种自我演进范式，使轻量级模型能够自我改进，从而减少对先进LLMs的依赖。通过广泛的实验，我们验证了该方法在不同规模和架构模型中的有效性。

> The tool-using capability of large language models (LLMs) enables them to access up-to-date external information and handle complex tasks. Current approaches to enhancing this capability primarily rely on distilling advanced models by data synthesis. However, this method incurs significant costs associated with advanced model usage and often results in data compatibility issues, led by the high discrepancy in the knowledge scope between the advanced model and the target model. To address these challenges, we propose ToolACE-DEV, a self-improving framework for tool learning. First, we decompose the tool-learning objective into sub-tasks that enhance basic tool-making and tool-using abilities. Then, we introduce a self-evolving paradigm that allows lightweight models to self-improve, reducing reliance on advanced LLMs. Extensive experiments validate the effectiveness of our approach across models of varying scales and architectures.

[Arxiv](https://arxiv.org/abs/2505.07512)