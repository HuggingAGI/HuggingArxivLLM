# Speculative MoE：基于推测式标记与专家预调度的高效通信并行 MoE 推理方案

发布时间：2025年03月06日

`其他` `人工智能` `计算机科学`

> Speculative MoE: Communication Efficient Parallel MoE Inference with Speculative Token and Expert Pre-scheduling

# 摘要

> MoE（专家混合模型）成为能够将现代基于 transformer 的大型语言模型（LLMs）扩展到前所未有的规模的神经架构。然而，大型 MoE 对计算能力、内存容量和内存带宽的巨大需求，使得可扩展服务成为一个根本性挑战，而高效的并行推理已成为在延迟限制下实现足够吞吐量的必要条件。DeepSpeed-MoE，一个最先进的 MoE 推理框架，采用包含 EP（专家并行）、TP（张量并行）和 DP（数据并行）的 3D 并行范式。然而，我们的分析表明，DeepSpeed-MoE 的推理效率很大程度上受到 EP 的限制，EP 使用代价高昂的 all-to-all 集体操作来路由令牌激活。我们的工作旨在通过一种名为 Speculative MoE 的技术，通过战略性地减少 EP 的通信开销来提升 DeepSpeed-MoE。Speculative MoE 提供了两种投机性并行化方案，即投机性令牌混洗和投机性专家分组，用于预测杰出令牌的专家路由路径，并跨设备预调度令牌和专家，以无损方式减少 EP 的通信量。除了 DeepSpeed-MoE 之外，我们还将 Speculative MoE 集成到流行的 MoE 推理引擎 SGLang 中。实验表明，Speculative MoE 可以显著提升在快速同质和缓慢异构互连上的先进 MoE 推理框架性能。

> MoE (Mixture of Experts) prevails as a neural architecture that can scale modern transformer-based LLMs (Large Language Models) to unprecedented scales. Nevertheless, large MoEs' great demands of computing power, memory capacity and memory bandwidth make scalable serving a fundamental challenge and efficient parallel inference has become a requisite to attain adequate throughput under latency constraints. DeepSpeed-MoE, one state-of-the-art MoE inference framework, adopts a 3D-parallel paradigm including EP (Expert Parallelism), TP (Tensor Parallel) and DP (Data Parallelism). However, our analysis shows DeepSpeed-MoE's inference efficiency is largely bottlenecked by EP, which is implemented with costly all-to-all collectives to route token activation. Our work aims to boost DeepSpeed-MoE by strategically reducing EP's communication overhead with a technique named Speculative MoE. Speculative MoE has two speculative parallelization schemes, speculative token shuffling and speculative expert grouping, which predict outstanding tokens' expert routing paths and pre-schedule tokens and experts across devices to losslessly trim EP's communication volume. Besides DeepSpeed-MoE, we also build Speculative MoE into a prevailing MoE inference engine SGLang. Experiments show Speculative MoE can significantly boost state-of-the-art MoE inference frameworks on fast homogeneous and slow heterogeneous interconnects.

[Arxiv](https://arxiv.org/abs/2503.04398)