# 大型模型训练中的拖后腿现象：用假设分析探索影响因素

发布时间：2025年05月08日

`LLM应用` `分布式计算` `系统性能优化`

> Understanding Stragglers in Large Model Training Using What-if Analysis

# 摘要

> 大型语言模型（LLM）的训练是当今最耗资源的分布式计算任务之一，通常需要数千个GPU并频繁在不同机器之间进行同步。这种工作负载模式使其容易受到慢节点（stragglers）的影响，即少数运行缓慢的工作节点可能导致整个训练过程停滞。在字节跳动，我们发现慢节点并非总是由硬件故障引起，而是可能由多种复杂因素共同导致。本研究旨在通过分析字节跳动LLM训练集群中收集的五个月的运行日志，对LLM训练中的慢节点问题进行全面研究。我们的核心方法是假设分析（what-if analysis），即模拟无慢节点的理想场景，并与实际运行情况进行对比。我们利用此方法研究以下问题：（1）慢节点如何频繁影响训练任务，以及它们对任务性能有何影响；（2）慢节点是否表现出时间或空间上的规律性；（3）慢节点的潜在根本原因是什么？

> Large language model (LLM) training is one of the most demanding distributed computations today, often requiring thousands of GPUs with frequent synchronization across machines. Such a workload pattern makes it susceptible to stragglers, where the training can be stalled by few slow workers. At ByteDance we find stragglers are not trivially always caused by hardware failures, but can arise from multiple complex factors. This work aims to present a comprehensive study on the straggler issues in LLM training, using a five-month trace collected from our ByteDance LLM training cluster. The core methodology is what-if analysis that simulates the scenario without any stragglers and contrasts with the actual case. We use this method to study the following questions: (1) how often do stragglers affect training jobs, and what effect do they have on job performance; (2) do stragglers exhibit temporal or spatial patterns; and (3) what are the potential root causes for stragglers?

[Arxiv](https://arxiv.org/abs/2505.05713)