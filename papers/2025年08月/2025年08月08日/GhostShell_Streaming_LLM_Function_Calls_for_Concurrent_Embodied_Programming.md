# GhostShell：流式LLM函数调用，助力并发式具身编程

发布时间：2025年08月08日

`LLM应用` `机器人` `人工智能`

> GhostShell: Streaming LLM Function Calls for Concurrent Embodied Programming

# 摘要

> # GhostShell：基于大型语言模型的流式行为编程方法

我们提出了一种创新方法 GhostShell，它利用大型语言模型（LLMs）实现具身系统的流式和并发行为编程。与依赖预先安排动作序列或行为树的传统方法不同，GhostShell 通过在 LLM 流式输出标记时逐步发布函数调用，使具身系统能够实时行动。

GhostShell 拥有三个核心组件：流式 XML 函数标记解析器、动态函数接口映射器，以及多通道调度器。该调度器协调跨通道的同步和异步函数调用，从而在 LLM 的指导下实现多机器人组件间的串并行动作协调。

我们通过在机器人原型 COCO 上进行涵盖 34 个真实交互任务和多个 LLM 后端的全面实验来评估 GhostShell。实验结果表明：

- 在 Claude-4-Sonnet 上，GhostShell 实现了 0.85 的先进行为正确性指标
- 响应时间比原生 LLM 函数调用 API 快达 66 倍
- 在长时多模态任务中，GhostShell 展现出强大的鲁棒性和泛化能力

这些结果证明了 GhostShell 在复杂任务中的优越性能和广泛应用潜力。

> We present GhostShell, a novel approach that leverages Large Language Models (LLMs) to enable streaming and concurrent behavioral programming for embodied systems. In contrast to conventional methods that rely on pre-scheduled action sequences or behavior trees, GhostShell drives embodied systems to act on-the-fly by issuing function calls incrementally as tokens are streamed from the LLM. GhostShell features a streaming XML function token parser, a dynamic function interface mapper, and a multi-channel scheduler that orchestrates intra-channel synchronous and inter-channel asynchronous function calls, thereby coordinating serial-parallel embodied actions across multiple robotic components under LLM guidance. We evaluate GhostShell on our robotic prototype COCO through comprehensive grounded experiments across 34 real-world interaction tasks and multiple LLM backends. The results demonstrate that our approach achieves a state-of-the-art Behavioral Correctness Metric of 0.85 with Claude-4-Sonnet, and up to 66X faster response times compared to native LLM function calling APIs. GhostShell also proves effective in long-horizon multimodal tasks, exhibiting strong robustness and generalization capabilities.

[Arxiv](https://arxiv.org/abs/2508.05298)