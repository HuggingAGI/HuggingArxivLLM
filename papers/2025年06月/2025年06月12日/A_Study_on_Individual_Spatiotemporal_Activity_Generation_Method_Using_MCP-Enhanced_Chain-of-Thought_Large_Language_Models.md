# # 个体时空活动生成方法研究
基于MCP增强链式思维大语言模型

发布时间：2025年06月12日

`LLM应用` `城市规划` `智能城市`

> A Study on Individual Spatiotemporal Activity Generation Method Using MCP-Enhanced Chain-of-Thought Large Language Models

# 摘要

> 人类时空行为模拟在城市规划研究中扮演着关键角色，但传统基于规则和统计的方法存在计算成本高、泛化能力弱及扩展性差的问题。虽然大型语言模型（LLMs）展现出作为“世界模拟器”的潜力，但在时空推理方面仍面临挑战，包括空间认知有限、缺乏物理约束理解及群体同质化倾向。本文提出了一种结合链式思维（CoT）推理与模型上下文协议（MCP）的框架，旨在提升LLMs在模拟与验证数据模式相匹配的时空行为方面的能力。该框架通过五阶段认知框架实现类人逐步推理，并借助六类MCP工具进行全面数据处理：时间管理、空间导航、环境感知、个人记忆、社会协作及体验评估。以上海陆家嘴地区的实验为例，验证了该框架在1000个生成样本中的有效性。实验结果表明，生成数据与真实移动信号数据高度相似，不同基础模型的生成质量评分均在7.86至8.36之间。并行处理实验显示效率提升，当从2个进程扩展至12个进程时，每个样本的生成时间从1.30分钟减少至0.17分钟。这项研究为将CoT推理与MCP相结合用于城市行为建模提供了新思路，推动了LLMs在城市计算中的应用，并为合成移动数据的生成提供了一种实用方法。该框架为智能城市规划、交通预测及参与式城市设计等应用奠定了基础。


> Human spatiotemporal behavior simulation is critical for urban planning research, yet traditional rule-based and statistical approaches suffer from high computational costs, limited generalizability, and poor scalability. While large language models (LLMs) show promise as "world simulators," they face challenges in spatiotemporal reasoning including limited spatial cognition, lack of physical constraint understanding, and group homogenization tendencies. This paper introduces a framework integrating chain-of-thought (CoT) reasoning with Model Context Protocol (MCP) to enhance LLMs' capability in simulating spatiotemporal behaviors that correspond with validation data patterns. The methodology combines human-like progressive reasoning through a five-stage cognitive framework with comprehensive data processing via six specialized MCP tool categories: temporal management, spatial navigation, environmental perception, personal memory, social collaboration, and experience evaluation. Experiments in Shanghai's Lujiazui district validate the framework's effectiveness across 1,000 generated samples. Results demonstrate high similarity with real mobile signaling data, achieving generation quality scores of 7.86 to 8.36 across different base models. Parallel processing experiments show efficiency improvements, with generation times decreasing from 1.30 to 0.17 minutes per sample when scaling from 2 to 12 processes. This work contributes to integrating CoT reasoning with MCP for urban behavior modeling, advancing LLMs applications in urban computing and providing a practical approach for synthetic mobility data generation. The framework offers a foundation for smart city planning, transportation forecasting, and participatory urban design applications.

[Arxiv](https://arxiv.org/abs/2506.10853)