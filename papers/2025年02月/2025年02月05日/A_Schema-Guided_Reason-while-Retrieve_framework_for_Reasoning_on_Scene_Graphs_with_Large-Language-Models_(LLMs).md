# 模式引导的“边推理边检索”框架：基于LLMs的场景图推理

发布时间：2025年02月05日

`Agent

理由：这篇论文描述了一个基于模式引导的检索-推理框架（SG-RwR），其中使用了两个协作的代码编写LLM代理（推理器和检索器）来进行场景图的推理和规划。这些代理通过迭代协作完成任务，并且论文强调了代理之间的协作和任务规划。因此，这篇论文主要关注的是多代理系统的设计和应用，属于Agent分类。` `人工智能` `空间推理`

> A Schema-Guided Reason-while-Retrieve framework for Reasoning on Scene Graphs with Large-Language-Models (LLMs)

# 摘要

> # 摘要
场景图作为一种结构化和可序列化的环境表示，已在大语言模型（LLMs）的空间推理中崭露头角。本研究提出SG-RwR，一种基于模式引导的检索-推理框架，用于场景图的推理和规划。我们采用两个协作的代码编写LLM代理：（1）推理器，负责任务规划和信息查询生成；（2）检索器，根据查询提取图信息。两代理通过迭代协作，实现顺序推理和对图信息的自适应关注。与以往研究不同，两代理仅通过场景图模式而非完整图数据进行提示，这通过限制输入标记减少了幻觉，并推动推理器抽象生成推理轨迹。检索器基于模式理解，以编程方式查询场景图数据，实现对图的动态和全局关注，增强推理与检索的对齐。实验表明，我们的框架在数值问答和规划任务中超越了现有基于LLM的方法，且即使在缺乏代理级演示的情况下，也能从任务级少样本示例中受益。项目代码将公开发布。

> Scene graphs have emerged as a structured and serializable environment representation for grounded spatial reasoning with Large Language Models (LLMs). In this work, we propose SG-RwR, a Schema-Guided Retrieve-while-Reason framework for reasoning and planning with scene graphs. Our approach employs two cooperative, code-writing LLM agents: a (1) Reasoner for task planning and information queries generation, and a (2) Retriever for extracting corresponding graph information following the queries. Two agents collaborate iteratively, enabling sequential reasoning and adaptive attention to graph information. Unlike prior works, both agents are prompted only with the scene graph schema rather than the full graph data, which reduces the hallucination by limiting input tokens, and drives the Reasoner to generate reasoning trace abstractly.Following the trace, the Retriever programmatically query the scene graph data based on the schema understanding, allowing dynamic and global attention on the graph that enhances alignment between reasoning and retrieval. Through experiments in multiple simulation environments, we show that our framework surpasses existing LLM-based approaches in numerical Q\&A and planning tasks, and can benefit from task-level few-shot examples, even in the absence of agent-level demonstrations. Project code will be released.

[Arxiv](https://arxiv.org/abs/2502.03450)