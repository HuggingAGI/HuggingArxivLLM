# 复杂图像修复问题的智能体系统

发布时间：2024年10月23日

`Agent

理由：这篇论文提出了一个名为AgenticIR的智能系统，该系统模拟人类图像处理的方法，包含多个关键阶段，并利用大型语言模型（LLMs）和视觉语言模型（VLMs）进行交互和推理。该系统通过动态操作一个图像修复（IR）模型工具箱来处理复杂的IR任务。这种系统设计符合“Agent”的定义，即一个能够感知环境、做出决策并执行任务的智能体。因此，这篇论文应被分类为Agent。` `计算机视觉` `图像处理`

> An Intelligent Agentic System for Complex Image Restoration Problems

# 摘要

> # 真实世界图像修复（IR）的复杂性通常需要结合多种专用模型来解决各种退化问题。受人类解决问题的启发，我们提出了AgenticIR，这是一个模拟人类图像处理方法的智能系统，包含五个关键阶段：感知、调度、执行、反思和重新调度。AgenticIR利用大型语言模型（LLMs）和视觉语言模型（VLMs），通过文本生成进行交互，动态操作一个IR模型工具箱。我们对VLMs进行微调以进行图像质量分析，并利用LLMs进行推理，逐步指导系统。为了弥补LLMs在特定IR知识和经验方面的不足，我们引入了一种自我探索方法，允许LLM观察并将修复结果总结为可参考的文档。实验表明，AgenticIR在处理复杂IR任务方面具有潜力，代表了在视觉处理中实现通用智能的一条有前途的路径。

> Real-world image restoration (IR) is inherently complex and often requires combining multiple specialized models to address diverse degradations. Inspired by human problem-solving, we propose AgenticIR, an agentic system that mimics the human approach to image processing by following five key stages: Perception, Scheduling, Execution, Reflection, and Rescheduling. AgenticIR leverages large language models (LLMs) and vision-language models (VLMs) that interact via text generation to dynamically operate a toolbox of IR models. We fine-tune VLMs for image quality analysis and employ LLMs for reasoning, guiding the system step by step. To compensate for LLMs' lack of specific IR knowledge and experience, we introduce a self-exploration method, allowing the LLM to observe and summarize restoration results into referenceable documents. Experiments demonstrate AgenticIR's potential in handling complex IR tasks, representing a promising path toward achieving general intelligence in visual processing.

[Arxiv](https://arxiv.org/abs/2410.17809)