# GDS智能体：图算法推理智能体

发布时间：2025年08月28日

`Agent` `基础理论`

> GDS Agent: A Graph Algorithmic Reasoning Agent

# 摘要

> 大型语言模型（LLMs）在多模态信息处理与推理方面已展现出惊人能力。通过函数调用集成工具并结合检索增强技术后，基于LLM的复合系统能够访问封闭数据源并解答相关问题。然而，在处理和推理大规模图结构数据时，这些系统仍面临挑战。本技术报告中，我们介绍了GDS（图数据科学）智能体。GDS智能体在模型上下文协议（MCP）服务器中集成了一整套图算法工具，并包含算法结果的预处理（检索）与后处理流程。该服务器可与任何现代LLM开箱即用。GDS智能体让用户能够提出任何隐含且本质上需对数据进行图算法推理的问题，并快速得到准确且有依据的答案。我们还提出了一个新基准，用于评估中间工具调用和最终响应结果。结果显示，GDS智能体能够处理各类图任务。我们还针对更开放式的任务提供了详细案例研究，并分析了智能体的薄弱场景。最后，我们探讨了尚存的挑战及未来发展路线图。

> Large language models (LLMs) have shown remarkable multimodal information processing and reasoning ability. When equipped with tools through function calling and enhanced with retrieval-augmented techniques, compound LLM-based systems can access closed data sources and answer questions about them. However, they still struggle to process and reason over large-scale graph-structure data. We introduce the GDS (Graph Data Science) agent in this technical report. The GDS agent introduces a comprehensive set of graph algorithms as tools, together with preprocessing (retrieval) and postprocessing of algorithm results, in a model context protocol (MCP) server. The server can be used with any modern LLM out-of-the-box. GDS agent allows users to ask any question that implicitly and intrinsically requires graph algorithmic reasoning about their data, and quickly obtain accurate and grounded answers. We also introduce a new benchmark that evaluates intermediate tool calls as well as final responses. The results indicate that GDS agent is able to solve a wide spectrum of graph tasks. We also provide detailed case studies for more open-ended tasks and study scenarios where the agent struggles. Finally, we discuss the remaining challenges and the future roadmap.

[Arxiv](https://arxiv.org/abs/2508.20637)