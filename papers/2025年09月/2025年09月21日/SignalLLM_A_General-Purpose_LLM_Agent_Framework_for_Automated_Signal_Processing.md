# SignalLLM：面向自动化信号处理的通用LLM智能体框架

发布时间：2025年09月21日

`Agent` `工业与制造`

> SignalLLM: A General-Purpose LLM Agent Framework for Automated Signal Processing

# 摘要

> 现代信号处理（SP）流程，无论是基于模型还是数据驱动，往往受限于复杂且碎片化的工作流程，严重依赖专家知识与人工操作，在数据有限时更难以实现自适应与泛化。相比之下，大型语言模型（LLMs）凭借强大的推理能力、丰富的通用知识、上下文学习及跨模态迁移能力，成为自动化和泛化SP工作流程的理想工具。受此启发，我们提出了SignalLLM——首个面向通用SP任务的基于LLM的通用智能体框架。与以往基于LLM的SP方法局限于特定应用或复杂提示工程不同，SignalLLM采用了系统化、模块化的架构设计：它借助上下文学习与领域特定检索，将高层SP目标拆解为结构化子任务，并通过自适应检索增强生成（RAG）与优化进行分层规划；随后，这些子任务通过基于提示的推理、跨模态推理、代码生成、模型调用或数据驱动的LLM辅助建模执行。其可泛化设计使其能在不同信号模态、任务类型和数据条件下灵活选择问题解决策略。我们通过通信与传感领域的五个代表性任务（如雷达目标检测、人类活动识别和文本压缩）验证了SignalLLM的多功能性和有效性，实验结果显示其性能优于传统方法和现有基于LLM的方法，尤其在少样本和零样本场景下表现突出。

> Modern signal processing (SP) pipelines, whether model-based or data-driven, often constrained by complex and fragmented workflow, rely heavily on expert knowledge and manual engineering, and struggle with adaptability and generalization under limited data. In contrast, Large Language Models (LLMs) offer strong reasoning capabilities, broad general-purpose knowledge, in-context learning, and cross-modal transfer abilities, positioning them as powerful tools for automating and generalizing SP workflows. Motivated by these potentials, we introduce SignalLLM, the first general-purpose LLM-based agent framework for general SP tasks. Unlike prior LLM-based SP approaches that are limited to narrow applications or tricky prompting, SignalLLM introduces a principled, modular architecture. It decomposes high-level SP goals into structured subtasks via in-context learning and domain-specific retrieval, followed by hierarchical planning through adaptive retrieval-augmented generation (RAG) and refinement; these subtasks are then executed through prompt-based reasoning, cross-modal reasoning, code synthesis, model invocation, or data-driven LLM-assisted modeling. Its generalizable design enables the flexible selection of problem solving strategies across different signal modalities, task types, and data conditions. We demonstrate the versatility and effectiveness of SignalLLM through five representative tasks in communication and sensing, such as radar target detection, human activity recognition, and text compression. Experimental results show superior performance over traditional and existing LLM-based methods, particularly in few-shot and zero-shot settings.

[Arxiv](https://arxiv.org/abs/2509.17197)