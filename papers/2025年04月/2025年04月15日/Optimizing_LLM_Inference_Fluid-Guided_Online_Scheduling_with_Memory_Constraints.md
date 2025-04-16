# 优化 LLM 推理：基于流体的引导在线调度，在内存约束下

发布时间：2025年04月15日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在推理过程中的优化问题，特别是针对内存受限的情况。文中提出了新的调度算法来提高LLMs的推理效率，这属于LLM的应用层面。` `计算机科学` `工业工程`

> Optimizing LLM Inference: Fluid-Guided Online Scheduling with Memory Constraints

# 摘要

> 大型语言模型（LLMs）在当今应用中不可或缺，但其推理过程需要大量计算资源，尤其是在内存受限的情况下。本文将LLM推理优化建模为一个多阶段在线调度问题，其中连续的提示到达和KV缓存的增长使得传统调度方法难以奏效。我们开发了一种流体动力学近似方法，为算法设计提供基准。基于此，我们提出了“等待累积推理阈值”（WAIT）算法，该算法利用多个阈值在已知输出长度的情况下对到达的提示进行最优调度，并将其扩展为“嵌套WAIT”以处理未知输出长度的情况。理论分析表明，这两种算法在高负载条件下均能实现近优性能，能够在吞吐量、延迟和首次令牌生成时间（TTFT）之间实现平衡。实验结果表明，与现有基线相比，使用Llama-7B模型在A100 GPU上进行的实验，采用合成数据集和真实世界数据集，均实现了吞吐量的提升和延迟的降低。这项研究将运筹学与机器学习相结合，为内存受限条件下LLMs的高效部署提供了严格的框架。


> Large Language Models (LLMs) are indispensable in today's applications, but their inference procedure -- generating responses by processing text in segments and using a memory-heavy Key-Value (KV) cache -- demands significant computational resources, particularly under memory constraints. This paper formulates LLM inference optimization as a multi-stage online scheduling problem where sequential prompt arrivals and KV cache growth render conventional scheduling ineffective. We develop a fluid dynamics approximation to provide a tractable benchmark that guides algorithm design. Building on this, we propose the Waiting for Accumulated Inference Threshold (WAIT) algorithm, which uses multiple thresholds to schedule incoming prompts optimally when output lengths are known, and extend it to Nested WAIT for cases with unknown output lengths. Theoretical analysis shows that both algorithms achieve near-optimal performance against the fluid benchmark in heavy traffic conditions, balancing throughput, latency, and Time to First Token (TTFT). Experiments with the Llama-7B model on an A100 GPU using both synthetic and real-world datasets demonstrate improved throughput and reduced latency relative to established baselines like vLLM and Sarathi. This work bridges operations research and machine learning, offering a rigorous framework for the efficient deployment of LLMs under memory constraints.

[Arxiv](https://arxiv.org/abs/2504.11320)