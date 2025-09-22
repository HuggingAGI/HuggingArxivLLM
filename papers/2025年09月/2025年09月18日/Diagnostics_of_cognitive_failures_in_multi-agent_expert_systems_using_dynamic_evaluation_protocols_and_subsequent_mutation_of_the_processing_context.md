# 基于动态评估协议与处理上下文后续变异的多智能体专家系统认知故障诊断

发布时间：2025年09月18日

`Agent` `基础理论`

> Diagnostics of cognitive failures in multi-agent expert systems using dynamic evaluation protocols and subsequent mutation of the processing context

# 摘要

> 神经架构的快速演进——从多层感知机到大规模Transformer模型——让语言模型（LLMs）在配备记忆、规划能力和外部工具使用功能后，展现出新兴的智能体行为。但它们固有的随机性和多步骤决策过程，使得传统评估方法难以准确诊断智能体性能。为此，本研究提出了一个专家系统诊断框架，不仅能评估智能体表现，还能促进专家行为向基于LLM的智能体迁移。该框架整合了三部分：（i）精心整理的专家注释黄金数据集，（ii）通过受控行为变异生成的银数据集，以及（iii）基于LLM的智能体评判器，负责评分并提供针对性改进建议。这些建议被嵌入到向量化推荐图谱中，让专家干预能以可复用的改进轨迹形式在多个系统实例中推广。我们在多智能体招聘助手系统上对该框架进行了验证，结果显示它能揭示潜在认知缺陷（如表述偏见、提取偏移和工具误路由），同时引导智能体达成专家级的推理能力与风格。研究结果为随机且工具增强的LLM智能体实现标准化、可复现的专家行为迁移奠定了基础，推动评估从静态检测升级为主动的专家系统优化。

> The rapid evolution of neural architectures - from multilayer perceptrons to large-scale Transformer-based models - has enabled language models (LLMs) to exhibit emergent agentic behaviours when equipped with memory, planning, and external tool use. However, their inherent stochasticity and multi-step decision processes render classical evaluation methods inadequate for diagnosing agentic performance. This work introduces a diagnostic framework for expert systems that not only evaluates but also facilitates the transfer of expert behaviour into LLM-powered agents. The framework integrates (i) curated golden datasets of expert annotations, (ii) silver datasets generated through controlled behavioural mutation, and (iii) an LLM-based Agent Judge that scores and prescribes targeted improvements. These prescriptions are embedded into a vectorized recommendation map, allowing expert interventions to propagate as reusable improvement trajectories across multiple system instances. We demonstrate the framework on a multi-agent recruiter-assistant system, showing that it uncovers latent cognitive failures - such as biased phrasing, extraction drift, and tool misrouting - while simultaneously steering agents toward expert-level reasoning and style. The results establish a foundation for standardized, reproducible expert behaviour transfer in stochastic, tool-augmented LLM agents, moving beyond static evaluation to active expert system refinement.

[Arxiv](https://arxiv.org/abs/2509.15366)