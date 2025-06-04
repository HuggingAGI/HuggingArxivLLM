# 以硬件为中心的分析：DeepSeek的多头潜在注意力机制

发布时间：2025年06月03日

`LLM应用` `AI加速器` `计算架构`

> Hardware-Centric Analysis of DeepSeek's Multi-Head Latent Attention

# 摘要

> DeepSeek-V2中提出的多头潜在注意力机制（MLA），通过将查询、键和值张量投影到紧凑的潜在空间中，显著提升了大语言模型的运行效率。这种创新性架构不仅减少了键值缓存的大小，还大幅降低了内存带宽的需求，尤其在自回归解码阶段效果显著。本文首次从硬件角度对MLA进行深入分析，将其与传统多头注意力机制（MHA）进行对比，并评估其对加速器性能的影响。我们发现MLA存在两种执行方案——复用或重新计算潜在投影矩阵——这两种方案在计算和内存访问之间提供了独特的权衡。通过Stream设计空间探索框架，我们对多种硬件平台进行了建模，评估了MLA的吞吐量和能耗，发现MLA能够将注意力计算工作负载转移到计算受限的运行环境中。研究结果表明，MLA不仅降低了带宽的使用需求，还提供了与硬件约束相匹配的灵活执行策略。与MHA相比，MLA在带宽受限的硬件平台上展现出更加稳定和高效的性能。这些发现凸显了MLA作为未来AI加速器协同设计机会的重要性。

> Multi-Head Latent Attention (MLA), introduced in DeepSeek-V2, improves the efficiency of large language models by projecting query, key, and value tensors into a compact latent space. This architectural change reduces the KV-cache size and significantly lowers memory bandwidth demands, particularly in the autoregressive decode phase. This letter presents the first hardware-centric analysis of MLA, comparing it to conventional Multi-Head Attention (MHA) and evaluating its implications for accelerator performance. We identify two alternative execution schemes of MLA--reusing, resp. recomputing latent projection matrices--which offer distinct trade-offs between compute and memory access. Using the Stream design space exploration framework, we model their throughput and energy cost across a range of hardware platforms and find that MLA can shift attention workloads toward the compute-bound regime.
  Our results show that MLA not only reduces bandwidth usage but also enables adaptable execution strategies aligned with hardware constraints. Compared to MHA, it provides more stable and efficient performance, particularly on bandwidth-limited hardware platforms. These findings emphasize MLA's relevance as a co-design opportunity for future AI accelerators.

[Arxiv](https://arxiv.org/abs/2506.02523)