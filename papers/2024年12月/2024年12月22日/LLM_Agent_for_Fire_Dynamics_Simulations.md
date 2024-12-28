# 用于火灾动力学模拟的 LLM 代理

发布时间：2024年12月22日

`Agent` `计算流体动力学`

> LLM Agent for Fire Dynamics Simulations

# 摘要

> 在借助基础模型（如大型语言模型（LLMs））来加快复杂科学工作流程方面，已取得显著进展。在本项工作中，我们推出了 FoamPilot，这是一个概念验证型的 LLM 代理，旨在提升 FireFOAM 的可用性，FireFOAM 是利用流行的计算流体动力学（CFD）开源工具箱 OpenFOAM 构建的用于火灾动力学和灭火模拟的专用求解器。FoamPilot 具备三项核心功能：代码洞察、案例配置和模拟评估。代码洞察采用检索增强生成（RAG），替代传统的关键字搜索，旨在帮助开发人员和经验丰富的用户高效导航和总结 FireFOAM 的源代码。在案例配置方面，该代理能理解用户的自然语言请求，并相应修改现有模拟设置，以支持中级用户。FoamPilot 的作业执行功能致力于管理在高性能计算（HPC）环境中的模拟提交和执行，并为经验较少的用户提供模拟结果的初步分析。每个功能都收获了不错的成果，尤其是在简单任务上，同时也明确了在更复杂任务上进一步大幅改进的机会。将这些功能整合到单个 LLM 代理中，是为了给使用 FireFOAM 进行对提升消防安全至关重要的复杂模拟的工程师和科学家加快模拟工作流程。

> Significant advances have been achieved in leveraging foundation models, such as large language models (LLMs), to accelerate complex scientific workflows. In this work we introduce FoamPilot, a proof-of-concept LLM agent designed to enhance the usability of FireFOAM, a specialized solver for fire dynamics and fire suppression simulations built using OpenFOAM, a popular open-source toolbox for computational fluid dynamics (CFD). FoamPilot provides three core functionalities: code insight, case configuration and simulation evaluation. Code insight is an alternative to traditional keyword searching leveraging retrieval-augmented generation (RAG) and aims to enable efficient navigation and summarization of the FireFOAM source code for developers and experienced users. For case configuration, the agent interprets user requests in natural language and aims to modify existing simulation setups accordingly to support intermediate users. FoamPilot's job execution functionality seeks to manage the submission and execution of simulations in high-performance computing (HPC) environments and provide preliminary analysis of simulation results to support less experienced users. Promising results were achieved for each functionality, particularly for simple tasks, and opportunities were identified for significant further improvement for more complex tasks. The integration of these functionalities into a single LLM agent is a step aimed at accelerating the simulation workflow for engineers and scientists employing FireFOAM for complex simulations critical for improving fire safety.

[Arxiv](https://arxiv.org/abs/2412.17146)