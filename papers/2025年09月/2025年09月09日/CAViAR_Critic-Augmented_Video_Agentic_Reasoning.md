# CAViAR：评论家增强的视频智能体推理

发布时间：2025年09月09日

`Agent` `媒体与娱乐`

> CAViAR: Critic-Augmented Video Agentic Reasoning

# 摘要

> 视频理解领域近年来进展显著，模型在短视频片段感知任务上的性能持续提升。然而，LVBench、Neptune和ActivityNet-RTL等多项最新基准测试显示，当查询复杂度增加、视频时长变长时，视频复杂推理任务的性能会随之下降。本研究提出核心问题：能否借助现有感知能力实现更复杂的视频推理？为此，我们开发了一个大型语言模型智能体，可将视频模块用作子智能体或工具。与Visual Programming、ViperGPT、MoReVQA等前人工作中采用固定流程解决查询的方式不同，该智能体通过每次调用模块的结果动态决定后续步骤。受文本推理领域研究启发，我们引入评判器来区分智能体生成的有效与无效序列。实验表明，智能体与评判器的协同在上述数据集上表现优异。

> Video understanding has seen significant progress in recent years, with models' performance on perception from short clips continuing to rise. Yet, multiple recent benchmarks, such as LVBench, Neptune, and ActivityNet-RTL, show performance wanes for tasks requiring complex reasoning on videos as queries grow more complex and videos grow longer. In this work, we ask: can existing perception capabilities be leveraged to successfully perform more complex video reasoning? In particular, we develop a large language model agent given access to video modules as subagents or tools. Rather than following a fixed procedure to solve queries as in previous work such as Visual Programming, ViperGPT, and MoReVQA, the agent uses the results of each call to a module to determine subsequent steps. Inspired by work in the textual reasoning domain, we introduce a critic to distinguish between instances of successful and unsuccessful sequences from the agent. We show that the combination of our agent and critic achieve strong performance on the previously-mentioned datasets.

[Arxiv](https://arxiv.org/abs/2509.07680)