# EICopilot: 基于LLM驱动的代理，在大规模知识图谱中搜索与探索企业信息

发布时间：2025年01月23日

`Agent

理由：这篇论文描述了一个基于智能体的系统EICopilot，该系统用于在大型在线知识图谱中高效搜索和探索企业注册数据。EICopilot通过聊天机器人形式部署，利用大型语言模型（LLMs）解析自然语言查询，并自动生成和执行Gremlin脚本。该系统结合了数据预处理管道、综合推理管道和查询掩码策略，展示了智能体在复杂任务中的应用。因此，这篇论文应归类为Agent。` `企业信息` `知识图谱`

> EICopilot: Search and Explore Enterprise Information over Large-scale Knowledge Graphs with LLM-driven Agents

# 摘要

> # 摘要
本文提出EICopilot，一种基于智能体的创新方案，用于在大型在线知识图谱中高效搜索和探索企业注册数据，如法律实体、注册资本和主要股东信息。传统方法依赖文本查询和手动子图探索，耗时且低效。EICopilot通过百度企业搜索以聊天机器人形式部署，利用大型语言模型（LLMs）解析自然语言查询，自动生成并执行Gremlin脚本，快速生成复杂企业关系的摘要。其核心创新包括：1）数据预处理管道，将代表性查询编译并注释为向量数据库，支持上下文学习（ICL）；2）综合推理管道，结合思维链与ICL，优化知识图谱搜索的Gremlin脚本生成；3）新颖的查询掩码策略，提升意图识别，增强脚本准确性。实验表明，EICopilot在速度和准确性上均优于基线方法，其中\emph{Full Mask}变体将语法错误率降至10.00%，执行正确率高达82.14%。这些特性使EICopilot成为企业信息搜索领域探索大规模知识图谱的突破性工具。

> The paper introduces EICopilot, an novel agent-based solution enhancing search and exploration of enterprise registration data within extensive online knowledge graphs like those detailing legal entities, registered capital, and major shareholders. Traditional methods necessitate text-based queries and manual subgraph explorations, often resulting in time-consuming processes. EICopilot, deployed as a chatbot via Baidu Enterprise Search, improves this landscape by utilizing Large Language Models (LLMs) to interpret natural language queries. This solution automatically generates and executes Gremlin scripts, providing efficient summaries of complex enterprise relationships. Distinct feature a data pre-processing pipeline that compiles and annotates representative queries into a vector database of examples for In-context learning (ICL), a comprehensive reasoning pipeline combining Chain-of-Thought with ICL to enhance Gremlin script generation for knowledge graph search and exploration, and a novel query masking strategy that improves intent recognition for heightened script accuracy. Empirical evaluations demonstrate the superior performance of EICopilot, including speed and accuracy, over baseline methods, with the \emph{Full Mask} variant achieving a syntax error rate reduction to as low as 10.00% and an execution correctness of up to 82.14%. These components collectively contribute to superior querying capabilities and summarization of intricate datasets, positioning EICopilot as a groundbreaking tool in the exploration and exploitation of large-scale knowledge graphs for enterprise information search.

[Arxiv](https://arxiv.org/abs/2501.13746)