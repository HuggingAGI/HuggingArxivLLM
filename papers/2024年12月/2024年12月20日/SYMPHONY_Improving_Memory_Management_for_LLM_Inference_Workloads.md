# SYMPHONY：优化 LLM 推理工作负载的内存管理

发布时间：2024年12月20日

`LLM应用` `人工智能` `服务引擎`

> SYMPHONY: Improving Memory Management for LLM Inference Workloads

# 摘要

> 大型语言模型（LLMs）在诸如聊天机器人、代码编辑器和会话代理等应用中的部署日益增多。LLMs 的关键特性在于能与人类或外部工具开展多轮互动，从而完成各类任务。多轮互动中的每一个新请求都取决于中间状态，尤其是正在进行的互动中来自先前请求的键值（K，V）缓存。现有的服务引擎要么重新计算 K，V 缓存，要么将其卸载至主内存。性能分析显示，重新计算会导致超过 99％的处理令牌冗余。另一方面，从 GPU 内存卸载 K，V 缓存会使推理服务变为有状态，造成整个集群的负载不均衡。为应对这些挑战，我们研发了 SYMPHONY。SYMPHONY 借助多轮工作负载能提供额外提示这一发现，使得 K，V 缓存能够从关键服务路径迁移出去。利用这些提示，SYMPHONY 动态迁移 K，V 缓存，实现推理请求的细粒度调度。我们的实验表明，与最先进的基线相比，SYMPHONY 能够处理超过 8 倍的请求数量，且延迟情况相近。

> Large Language Models (LLMs) are increasingly being deployed in applications such as chatbots, code editors, and conversational agents. A key feature of LLMs is their ability to engage in multi-turn interactions with humans or external tools, enabling a wide range of tasks. Each new request in a multi-turn interaction depends on the intermediate state, specifically the key-value (K,V) caches, from previous requests in the ongoing interaction. Existing serving engines either recompute the K,V caches or offload them to main memory. Profiling reveals that recomputation can result in over 99% of processed tokens being redundant. On the other hand, offloading K,V caches from GPU memory makes inference serving stateful, leading to load imbalances across the cluster. To address these challenges, we developed SYMPHONY. SYMPHONY leverages the observation that multi-turn work loads provide additional hints that allow K,V caches to be migrated off the critical serving path. By utilizing these hints, SYMPHONY dynamically migrates K,V caches to enable finegrained scheduling of inference requests. Our experiments demonstrate that SYMPHONY can handle over 8x the number of requests compared to state-of-the-art baselines, with a similar latency profile.

[Arxiv](https://arxiv.org/abs/2412.16434)