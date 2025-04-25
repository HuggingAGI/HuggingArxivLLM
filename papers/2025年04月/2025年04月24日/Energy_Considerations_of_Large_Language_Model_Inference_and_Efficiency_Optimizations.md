# 大型语言模型推理中的能源考量与效率优化

发布时间：2025年04月24日

`LLM应用` `可持续发展`

> Energy Considerations of Large Language Model Inference and Efficiency Optimizations

# 摘要

> 大型语言模型（LLMs）规模和应用的扩大带来了日益增长的计算和环境成本。以往研究多聚焦于理想化条件下的延迟优化，却忽视了实际推理工作负载对能源消耗的影响。本研究系统分析了常见推理效率优化在自然语言处理（NLP）和生成人工智能（AI）任务中的能源影响，包括对话式AI和代码生成。我们提出了一种建模方法，通过分箱策略模拟输入-输出令牌分布和批次大小变化，近似实际LLM工作流。研究涵盖了软件框架、解码策略、GPU架构、在线与离线服务设置以及模型并行配置等多个维度。结果显示，推理优化的效果受工作负载特性、软件堆栈和硬件加速器的高度影响，表明基于FLOPs或理论GPU利用率的简单能源估计往往低估实际消耗。我们的研究表明，恰当应用推理效率优化可使总能源使用量较未经优化的基线减少高达73%。这些发现为可持续的LLM部署提供了基础，并为未来AI基础设施的节能设计指明了方向。

> As large language models (LLMs) scale in size and adoption, their computational and environmental costs continue to rise. Prior benchmarking efforts have primarily focused on latency reduction in idealized settings, often overlooking the diverse real-world inference workloads that shape energy use. In this work, we systematically analyze the energy implications of common inference efficiency optimizations across diverse Natural Language Processing (NLP) and generative Artificial Intelligence (AI) workloads, including conversational AI and code generation. We introduce a modeling approach that approximates real-world LLM workflows through a binning strategy for input-output token distributions and batch size variations. Our empirical analysis spans software frameworks, decoding strategies, GPU architectures, online and offline serving settings, and model parallelism configurations. We show that the effectiveness of inference optimizations is highly sensitive to workload geometry, software stack, and hardware accelerators, demonstrating that naive energy estimates based on FLOPs or theoretical GPU utilization significantly underestimate real-world energy consumption. Our findings reveal that the proper application of relevant inference efficiency optimizations can reduce total energy use by up to 73% from unoptimized baselines. These insights provide a foundation for sustainable LLM deployment and inform energy-efficient design strategies for future AI infrastructure.

[Arxiv](https://arxiv.org/abs/2504.17674)