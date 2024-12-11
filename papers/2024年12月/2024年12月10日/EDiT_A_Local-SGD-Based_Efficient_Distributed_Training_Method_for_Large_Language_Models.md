# EDiT：一种针对大型语言模型的基于局部 SGD 的高效分布式训练方式

发布时间：2024年12月10日

`LLM应用` `分布式训练` `大型语言模型`

> EDiT: A Local-SGD-Based Efficient Distributed Training Method for Large Language Models

# 摘要

> 分布式训练方法对大型语言模型（LLMs）意义重大。然而，现有的分布式训练方法常受通信瓶颈、掉队情况和有限弹性的影响。本地 SGD 方法虽已被提出以应对这些问题，但其因额外内存开销及对效率和稳定性关注不够，有效性仅限于小规模训练。为解决这些难题，我们提出 EDiT 这一创新的高效分布式训练方法，它把定制的本地 SGD 方法与模型分片技术相结合，提升大规模训练效率。EDiT 在正向传播时进行分层参数同步，降低通信和内存开销，实现计算与通信的重叠。此外，EDiT 采用伪梯度惩罚策略抑制损失峰值，确保训练稳定并提升性能。另外，我们引入 A-EDiT，即 EDiT 的完全异步变体，以适应异构集群。基于 EDiT/A-EDiT，我们开展了一系列实验来验证 LLMs 的大规模异步训练，并进行了全面分析。实验结果显示 EDiT/A-EDiT 性能卓越，使其成为在各种计算生态系统中进行分布式 LLM 训练的可靠解决方案。

> Distributed training methods are crucial for large language models (LLMs). However, existing distributed training methods often suffer from communication bottlenecks, stragglers, and limited elasticity. Local SGD methods have been proposed to address these issues, but their effectiveness remains limited to small-scale training due to additional memory overhead and lack of concerns on efficiency and stability. To tackle these issues, we propose EDiT, an innovative Efficient Distributed Training method that combines a tailored Local SGD approach with model sharding techniques to enhance large-scale training efficiency. EDiT performs layer-wise parameter synchronization during forward pass, reducing communication and memory overhead and enabling the overlap of computation and communication. Besides, EDiT employs a pseudo gradient penalty strategy to suppress loss spikes, which ensures training stability and improve performance. Additionally, we introduce A-EDiT, a fully asynchronous variant of EDiT that accommodates heterogeneous clusters. Building on EDiT/A-EDiT, we conduct a series of experiments to validate large-scale asynchronous training for LLMs, accompanied by comprehensive analyses. Experimental results demonstrate the superior performance of EDiT/A-EDiT, establishing them as robust solutions for distributed LLM training in diverse computational ecosystems.

[Arxiv](https://arxiv.org/abs/2412.07210)