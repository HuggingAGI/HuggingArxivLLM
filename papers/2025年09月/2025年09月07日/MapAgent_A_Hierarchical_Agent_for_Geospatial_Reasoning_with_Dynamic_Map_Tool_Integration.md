# MapAgent：集成动态地图工具的地理空间推理分层智能体

发布时间：2025年09月07日

`Agent` `交通运输`

> MapAgent: A Hierarchical Agent for Geospatial Reasoning with Dynamic Map Tool Integration

# 摘要

> 智能体AI通过实现复杂推理与工具使用，大幅扩展了大型语言模型（LLMs）的能力。然而，多数现有框架专为数学、编码或网络自动化等领域打造，在需要空间推理、多跳规划和实时地图交互的地理空间任务上表现不佳。为解决这些挑战，我们提出MapAgent——一个分层多智能体即插即用框架，配备定制工具集与智能体支架，专为地图集成的地理空间推理设计。与现有扁平智能体方法不同（这些方法统一对待工具，在处理相似但略有差异的地理空间API时往往给LLM带来负担），MapAgent将规划与执行解耦：高层规划器将复杂查询分解为子目标，并路由至专门模块。对于工具密集型模块（如基于地图的服务），我们设计了专用地图工具智能体，能自适应并行协调相关API以高效获取查询所需的地理空间数据；而较简单模块（如解决方案生成或答案提取）则无需额外智能体开销即可运行。这种分层设计降低了认知负荷，提高了工具选择精度，并实现了相似API间的精确协同。我们在四个不同的地理空间基准测试（MapEval-Textual、MapEval-API、MapEval-Visual和MapQA）上对MapAgent进行了评估，结果显示其显著优于最先进的工具增强型和智能体基线。我们已在https://github.com/Hasebul/MapAgent开源了该框架。

> Agentic AI has significantly extended the capabilities of large language models (LLMs) by enabling complex reasoning and tool use. However, most existing frameworks are tailored to domains such as mathematics, coding, or web automation, and fall short on geospatial tasks that require spatial reasoning, multi-hop planning, and real-time map interaction. To address these challenges, we introduce MapAgent, a hierarchical multi-agent plug-and-play framework with customized toolsets and agentic scaffolds for map-integrated geospatial reasoning. Unlike existing flat agent-based approaches that treat tools uniformly-often overwhelming the LLM when handling similar but subtly different geospatial APIs-MapAgent decouples planning from execution. A high-level planner decomposes complex queries into subgoals, which are routed to specialized modules. For tool-heavy modules-such as map-based services-we then design a dedicated map-tool agent that efficiently orchestrates related APIs adaptively in parallel to effectively fetch geospatial data relevant for the query, while simpler modules (e.g., solution generation or answer extraction) operate without additional agent overhead. This hierarchical design reduces cognitive load, improves tool selection accuracy, and enables precise coordination across similar APIs. We evaluate MapAgent on four diverse geospatial benchmarks-MapEval-Textual, MapEval-API, MapEval-Visual, and MapQA-and demonstrate substantial gains over state-of-the-art tool-augmented and agentic baselines. We open-source our framwork at https://github.com/Hasebul/MapAgent.

[Arxiv](https://arxiv.org/abs/2509.05933)