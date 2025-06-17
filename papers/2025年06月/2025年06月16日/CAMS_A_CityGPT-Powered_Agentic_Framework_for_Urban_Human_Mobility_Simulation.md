# # CAMS：基于 CityGPT 的智能体框架，助力城市人类出行模拟

发布时间：2025年06月16日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于人类移动性模拟，提出了一种结合智能体框架和城市知识的CAMS框架。研究的核心在于利用LLMs的能力来改进移动性模拟，属于LLM的应用领域。` `城市规划`

> CAMS: A CityGPT-Powered Agentic Framework for Urban Human Mobility Simulation

# 摘要

> 人类移动性模拟在现实应用中发挥着重要作用。为克服传统数据驱动方法的局限性，研究人员尝试利用大型语言模型（LLMs）的常识知识和推理能力来加速移动性模拟。然而，现有方法存在城市空间建模不足、个体与集体移动模式整合效果不佳等关键缺陷。为此，我们提出了	extbf{C}ityGPT驱动的	extbf{A}gentic 	extbf{M}obility 	extbf{S}imulation（	extbf{CAMS}）框架，这是一个基于语言的城市基础模型的智能框架，专为城市空间中的人类移动性模拟设计。该框架包含三个核心模块：MobExtractor用于提取和生成模板移动模式，GeoGenerator用于生成锚点和候选地理空间知识，TrajEnhancer用于生成与真实轨迹偏好对齐的轨迹。实验结果表明，	extbf{CAMS}无需依赖外部地理空间信息即可实现卓越性能。通过全面建模个体与集体移动约束，	extbf{CAMS}能够生成更真实、更合理的轨迹。总体而言，	extbf{CAMS}开创了一种将智能体框架与城市知识丰富的LLMs相结合的新范式，为人类移动性模拟提供了创新解决方案。

> Human mobility simulation plays a crucial role in various real-world applications. Recently, to address the limitations of traditional data-driven approaches, researchers have explored leveraging the commonsense knowledge and reasoning capabilities of large language models (LLMs) to accelerate human mobility simulation. However, these methods suffer from several critical shortcomings, including inadequate modeling of urban spaces and poor integration with both individual mobility patterns and collective mobility distributions. To address these challenges, we propose \textbf{C}ityGPT-Powered \textbf{A}gentic framework for \textbf{M}obility \textbf{S}imulation (\textbf{CAMS}), an agentic framework that leverages the language based urban foundation model to simulate human mobility in urban space. \textbf{CAMS} comprises three core modules, including MobExtractor to extract template mobility patterns and synthesize new ones based on user profiles, GeoGenerator to generate anchor points considering collective knowledge and generate candidate urban geospatial knowledge using an enhanced version of CityGPT, TrajEnhancer to retrieve spatial knowledge based on mobility patterns and generate trajectories with real trajectory preference alignment via DPO. Experiments on real-world datasets show that \textbf{CAMS} achieves superior performance without relying on externally provided geospatial information. Moreover, by holistically modeling both individual mobility patterns and collective mobility constraints, \textbf{CAMS} generates more realistic and plausible trajectories. In general, \textbf{CAMS} establishes a new paradigm that integrates the agentic framework with urban-knowledgeable LLMs for human mobility simulation.

[Arxiv](https://arxiv.org/abs/2506.13599)