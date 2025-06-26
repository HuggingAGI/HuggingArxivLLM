# KAG-Thinker：基于知识增强生成，实现大型语言模型的交互式思考与深度推理

发布时间：2025年06月24日

`LLM应用` `问答系统` `对话系统`

> KAG-Thinker: Interactive Thinking and Deep Reasoning in LLMs via Knowledge-Augmented Generation

# 摘要

> 本文中，我们介绍 KAG-Thinker，它将 KAG 升级为一个多轮交互式思考和深度推理框架，由专门的参数轻量化大型语言模型 (LLM) 提供支持。该方法构建结构化的思考过程，显著提升大型语言模型在特定领域知识库上的问答任务中推理过程的逻辑连贯性和上下文一致性。遵循 KAG 的 	extbf{逻辑形式} 引导的检索和推理技术路线，该框架首先通过 	extbf{广度分解} 将复杂问题分解为可独立解决的子问题（即逻辑形式）。每个逻辑形式以自然语言和逻辑函数两种等价形式表示，并分类处理为知识检索或推理分析任务。任务间的依赖关系和参数传递通过逻辑函数接口显式建模。在求解过程中，检索函数负责执行检索任务，获取指定知识单元的一跳结构化和非结构化信息；数学和推理函数则用于推理分析任务。值得注意的是，在知识检索子任务中，LLMs 和外部知识源被视为等价的知识库。我们通过 	extbf{知识边界} 模块利用自信度校准和反思推理等机制确定最优知识来源，并通过 	extbf{深度求解} 模块增强知识获取的全面性……

> In this paper, we introduce KAG-Thinker, which upgrade KAG to a multi-turn interactive thinking and deep reasoning framework powered by a dedicated parameter-light large language model (LLM). Our approach constructs a structured thinking process for solving complex problems, enhancing the the logical coherence and contextual consistency of the reasoning process in question-answering (Q&A) tasks on domain-specific knowledge bases (KBs) within LLMs. Following the \textbf{Logical Form} guided retrieval and reasoning technology route of KAG, this framework first decomposes complex questions into independently solvable sub-problems (which are also referred to as logical forms) through \textbf{breadth decomposition}. Each such logical form is represented in two equivalent forms-natural language and logical function-and subsequently classified as either a Knowledge Retrieval or Reasoning Analysis task. Dependencies and parameter passing between these tasks are explicitly modeled via logical function interfaces. In the solving process, the Retrieval function performs retrieval tasks. It retrieves one-hop structured and unstructured information of specified knowledge unit. While the Math and Deduce functions are used to perform reasoning analysis tasks. Secondly, it is worth noting that, in the Knowledge Retrieval sub-problem tasks, LLMs and external knowledge sources are regarded as equivalent KBs. We use the \textbf{knowledge boundary} module to determine the optimal source using self-regulatory mechanisms such as confidence calibration and reflective reasoning, and use the \textbf{depth solving} module to enhance the comprehensiveness of knowledge acquisition...

[Arxiv](https://arxiv.org/abs/2506.17728)