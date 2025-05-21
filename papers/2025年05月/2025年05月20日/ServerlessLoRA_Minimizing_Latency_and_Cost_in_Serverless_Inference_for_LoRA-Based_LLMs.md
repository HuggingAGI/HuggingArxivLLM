# # ServerlessLoRA：为基于LoRA的大型语言模型实现低延迟与低成本的无服务器推理。

发布时间：2025年05月20日

`LLM应用` `云计算`

> ServerlessLoRA: Minimizing Latency and Cost in Serverless Inference for LoRA-Based LLMs

# 摘要

> 无服务器计算凭借其按需付费的模式、精细的GPU资源管理和快速扩展能力，迅速成为服务大型语言模型（LLM）推理的热门选择。然而，我们的研究发现，尽管当前无服务器计算在处理通用LLM方面表现出色，但在应对低秩适配（LoRA）推理时却存在三大关键瓶颈：1）函数间存在99%的无谓权重重复，2）高昂的模型加载外工件加载延迟，3）处理多个LoRA LLM时资源竞争加剧。这些问题不仅导致GPU资源的巨大浪费，还显著增加了Time-To-First-Token（TTFT）时间，并推高了运营成本。为了解决这些挑战，我们推出了ServerlessLoRA——一个专为更高效、更经济地服务LoRA LLM设计的创新无服务器推理系统。ServerlessLoRA通过在隔离的LoRA函数间实现安全的主干LLM共享，有效减少了冗余。我们创新性地设计了一种预加载方法，预先加载全面的LoRA工件，从而将冷启动延迟降至最低。此外，ServerlessLoRA采用了感知资源争用的批处理和卸载策略，有效缓解了突发工作负载下的GPU资源冲突。在工业级工作负载的实验中，与现有的最佳LLM推理解决方案相比，ServerlessLoRA将TTFT时间降低了高达86%，并将成本削减了高达89%。这一成果展示了ServerlessLoRA在提升效率和降低成本方面的显著优势。

> Serverless computing has grown rapidly for serving Large Language Model (LLM) inference due to its pay-as-you-go pricing, fine-grained GPU usage, and rapid scaling. However, our analysis reveals that current serverless can effectively serve general LLM but fail with Low-Rank Adaptation (LoRA) inference due to three key limitations: 1) massive parameter redundancy among functions where 99% of weights are unnecessarily duplicated, 2) costly artifact loading latency beyond LLM loading, and 3) magnified resource contention when serving multiple LoRA LLMs. These inefficiencies lead to massive GPU wastage, increased Time-To-First-Token (TTFT), and high monetary costs.
  We propose ServerlessLoRA, a novel serverless inference system designed for faster and cheaper LoRA LLM serving. ServerlessLoRA enables secure backbone LLM sharing across isolated LoRA functions to reduce redundancy. We design a pre-loading method that pre-loads comprehensive LoRA artifacts to minimize cold-start latency. Furthermore, ServerlessLoRA employs contention aware batching and offloading to mitigate GPU resource conflicts during bursty workloads. Experiment on industrial workloads demonstrates that ServerlessLoRA reduces TTFT by up to 86% and cuts monetary costs by up to 89% compared to state-of-the-art LLM inference solutions.

[Arxiv](https://arxiv.org/abs/2505.14468)