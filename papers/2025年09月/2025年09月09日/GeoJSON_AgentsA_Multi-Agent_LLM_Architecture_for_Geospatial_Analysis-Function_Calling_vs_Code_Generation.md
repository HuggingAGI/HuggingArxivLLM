# GeoJSON Agents：面向地理空间分析的多智能体大型语言模型架构—函数调用 vs 代码生成

发布时间：2025年09月09日

`Agent` `交通运输`

> GeoJSON Agents:A Multi-Agent LLM Architecture for Geospatial Analysis-Function Calling vs Code Generation

# 摘要

> 大型语言模型（LLMs）在任务自动化与自然语言理解领域已取得显著进展，但由于缺乏地理信息系统（GIS）专业能力，其应用仍存在局限。为此，我们提出GeoJSON智能体——一种多智能体大语言模型架构。该框架将自然语言任务转化为结构化的GeoJSON操作指令，并借助两种主流大语言模型增强技术处理空间数据：函数调用与代码生成。架构包含任务解析、智能体协作和结果整合三个核心组件，旨在提升GIS自动化的性能与可扩展性。规划智能体负责将自然语言任务解析为结构化的GeoJSON指令；随后，专业的工作智能体根据分配的角色协同完成空间数据处理与分析，具体通过调用预定义函数API或动态生成并执行基于Python的空间分析代码实现；最后，系统将多轮执行的结果整合为可复用、符合标准的GeoJSON文件。为系统评估这两种方法的性能，我们构建了包含70个不同复杂度任务的基准数据集，并以OpenAI的GPT-4o作为核心模型开展实验。结果显示，基于函数调用的GeoJSON智能体准确率达85.71%，基于代码生成的智能体则达到97.14%，二者均显著优于性能最优的通用模型（48.57%）。进一步分析发现，代码生成技术具备更高的灵活性，而函数调用方法则拥有更稳定的执行效果。

> LLMs have made substantial progress in task automation and natural language understanding.However,without expertise in GIS,they continue to encounter limitations.To address these issues, we propose GeoJSON Agents-a multi-agent LLM architecture.This framework transforms natural language tasks into structured GeoJSON operation commands and processes spatial data using two widely adopted LLM enhancement techniques:Function Calling and Code Generation.The architecture consists of three components-task parsing,agent collaboration,and result integration-aimed at enhancing both the performance and scalability of GIS automation.The Planner agent interprets natural language tasks into structured GeoJSON commands.Then,specialized Worker agents collaborate according to assigned roles to perform spatial data processing and analysis,either by invoking predefined function APIs or by dynamically generating and executing Python-based spatial analysis code.Finally,the system integrates the outputs from multiple execution rounds into reusable,standards-compliant GeoJSON files.To systematically evaluate the performance of the two approaches,we constructed a benchmark dataset of 70 tasks with varying complexity and conducted experiments using OpenAI's GPT-4o as the core model.Results indicate that the Function Calling-based GeoJSON Agent achieved an accuracy of 85.71%,while the Code Generation-based agent reached 97.14%,both significantly outperforming the best-performing general-purpose model (48.57%).Further analysis reveals that the Code Generation provides greater flexibility,whereas the Function Calling approach offers more stable execution.This study is the first to introduce an LLM multi-agent framework for GeoJSON data and to compare the strengths and limitations of two mainstream LLM enhancement methods,offering new perspectives for improving GeoAI system performance.

[Arxiv](https://arxiv.org/abs/2509.08863)