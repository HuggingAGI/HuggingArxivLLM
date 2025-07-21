# LoopServe：用于多轮对话的双阶段自适应LLM推理加速系统

发布时间：2025年07月18日

`LLM应用` `人工智能` `对话系统`

> LoopServe: An Adaptive Dual-phase LLM Inference Acceleration System for Multi-Turn Dialogues

# 摘要

> 多轮对话在大型语言模型的实际应用中至关重要，如聊天机器人和虚拟助手。然而，随着对话历史的延长，现有模型面临计算和内存挑战，影响了交互效率。当前加速方法多依赖固定或位置启发式，难以适应多轮对话的动态特性。为此，我们提出了LoopServe，一个针对多轮对话的自适应双阶段推理加速框架。LoopServe的两大创新在于：预填充阶段的在线稀疏化，动态选择注意力矩阵的关键部分；解码阶段的渐进式键值压缩，自适应维护高效缓存。我们还发布了包含11个数据集的新基准测试，涵盖真实场景的对话依赖。实验表明，LoopServe在长上下文对话任务中显著优于现有方法，推理速度大幅提升。

> Multi-turn dialogues are essential in many real-world applications of large language models, such as chatbots and virtual assistants. As conversation histories become longer, existing large language models face increasing computational and memory challenges, which hinder their ability to provide efficient and responsive interactions. Most current acceleration methods either compress the context or optimize key value caching, but they often rely on fixed or position-based heuristics that do not adapt well to the dynamic and unpredictable patterns found in actual multi-turn conversations. In this paper, we present LoopServe, an adaptive dual-phase inference acceleration framework for large language models in multi-turn dialogues. LoopServe introduces two main innovations. First, it performs online sparsification during the prefilling phase by dynamically selecting the most important parts of the attention matrix for each new input. Second, it uses progressive key value compression during decoding by adaptively maintaining a relevant and efficient cache based on the most recently generated output tokens. We also propose a \href{https://huggingface.co/datasets/TreeAILab/Multi-turn_Long-context_Benchmark_for_LLMs}{new benchmark} with eleven multi-turn datasets that reflect realistic query positions and conversational dependencies. Extensive experiments demonstrate that LoopServe consistently achieves superior effectiveness compared to existing baselines and significantly accelerates LLM inference across a wide range of long-context dialogue tasks.

[Arxiv](https://arxiv.org/abs/2507.13681)