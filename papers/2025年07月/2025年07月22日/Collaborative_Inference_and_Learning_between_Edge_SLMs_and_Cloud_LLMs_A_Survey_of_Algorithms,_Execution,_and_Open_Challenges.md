# 边缘 SLM 与云端 LLM 协作推理与学习综述：算法、执行及开放挑战

发布时间：2025年07月22日

`LLM应用` `边缘智能`

> Collaborative Inference and Learning between Edge SLMs and Cloud LLMs: A Survey of Algorithms, Execution, and Open Challenges

# 摘要

> 随着大型语言模型 (LLMs) 的发展，仅将其部署在云端或压缩以适应边缘设备已无法满足需求，原因在于延迟、隐私、成本和个人化等方面的考虑。本文综述了一种协作范式，其中基于云端的 LLMs 与边缘部署的小语言模型 (SLMs) 在推理和训练两个层面实现跨层协作。我们提出了一个统一的边缘-云端协作策略分类法。在推理层面，我们将方法划分为任务分配、任务分割以及基于混合的协作模式，涵盖自适应调度、资源感知卸载、推测解码和模块化路由，粒度细化至任务与令牌级别。在训练层面，我们回顾了分布式自适应技术，包括参数对齐、剪枝、双向蒸馏和小模型引导优化。此外，我们还总结了相关数据集、基准测试和部署案例，并强调了隐私保护方法和垂直领域应用。本文综述为 LLM-SLM 协作提供了首个系统性基础，通过系统与算法的协同设计，实现了高效、可扩展且值得信赖的边缘-云端智能。

> As large language models (LLMs) evolve, deploying them solely in the cloud or compressing them for edge devices has become inadequate due to concerns about latency, privacy, cost, and personalization. This survey explores a collaborative paradigm in which cloud-based LLMs and edge-deployed small language models (SLMs) cooperate across both inference and training. We present a unified taxonomy of edge-cloud collaboration strategies. For inference, we categorize approaches into task assignment, task division, and mixture-based collaboration at both task and token granularity, encompassing adaptive scheduling, resource-aware offloading, speculative decoding, and modular routing. For training, we review distributed adaptation techniques, including parameter alignment, pruning, bidirectional distillation, and small-model-guided optimization. We further summarize datasets, benchmarks, and deployment cases, and highlight privacy-preserving methods and vertical applications. This survey provides the first systematic foundation for LLM-SLM collaboration, bridging system and algorithm co-design to enable efficient, scalable, and trustworthy edge-cloud intelligence.

[Arxiv](https://arxiv.org/abs/2507.16731)