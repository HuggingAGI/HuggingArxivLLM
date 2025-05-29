# 盘古嵌入版：高效双系统大语言模型推理器，元认知增强

发布时间：2025年05月28日

`LLM应用`

> Pangu Embedded: An Efficient Dual-system LLM Reasoner with Metacognition

# 摘要

> 本研究推出Pangu Embedded，一款在昇腾神经处理单元（NPUs）上开发的高效大型语言模型（LLM）推理器，具备灵活的快慢思考能力。该推理器成功解决了现有推理优化型LLMs中的高计算成本和长推理延迟问题。我们采用两阶段训练框架构建Pangu Embedded。第一阶段通过迭代蒸馏过程对模型进行微调，并在迭代中进行模型融合，以有效聚合互补知识。随后在昇腾集群上进行强化学习，采用结合陈旧同步并行和优先级数据队列的容延迟调度器进行优化。强化学习过程由多源自适应奖励系统（MARS）指导，该系统利用确定性指标和轻量级LLM评估器为数学、编程和通用问题解决任务生成动态、任务特定的奖励信号。第二阶段引入双系统框架，赋予Pangu Embedded处理常规查询的“快”模式和处理复杂推理的“慢”模式。该框架支持手动模式切换供用户控制，以及一种自动、复杂感知的模式选择机制，能够在延迟和推理深度之间动态分配计算资源。在AIME 2024、GPQA和LiveCodeBench等基准测试中的实验结果表明，70亿参数规模的Pangu Embedded超越了同规模的Qwen3-8B和GLM4-9B等模型。它在一个统一的模型架构内实现了快速响应和最先进的推理质量，展示了开发强大且实际可部署的LLM推理器的一个有希望的方向。

> This work presents Pangu Embedded, an efficient Large Language Model (LLM) reasoner developed on Ascend Neural Processing Units (NPUs), featuring flexible fast and slow thinking capabilities. Pangu Embedded addresses the significant computational costs and inference latency challenges prevalent in existing reasoning-optimized LLMs. We propose a two-stage training framework for its construction. In Stage 1, the model is finetuned via an iterative distillation process, incorporating inter-iteration model merging to effectively aggregate complementary knowledge. This is followed by reinforcement learning on Ascend clusters, optimized by a latency-tolerant scheduler that combines stale synchronous parallelism with prioritized data queues. The RL process is guided by a Multi-source Adaptive Reward System (MARS), which generates dynamic, task-specific reward signals using deterministic metrics and lightweight LLM evaluators for mathematics, coding, and general problem-solving tasks. Stage 2 introduces a dual-system framework, endowing Pangu Embedded with a "fast" mode for routine queries and a deeper "slow" mode for complex inference. This framework offers both manual mode switching for user control and an automatic, complexity-aware mode selection mechanism that dynamically allocates computational resources to balance latency and reasoning depth. Experimental results on benchmarks including AIME 2024, GPQA, and LiveCodeBench demonstrate that Pangu Embedded with 7B parameters, outperforms similar-size models like Qwen3-8B and GLM4-9B. It delivers rapid responses and state-of-the-art reasoning quality within a single, unified model architecture, highlighting a promising direction for developing powerful yet practically deployable LLM reasoners.

[Arxiv](https://arxiv.org/abs/2505.22375)