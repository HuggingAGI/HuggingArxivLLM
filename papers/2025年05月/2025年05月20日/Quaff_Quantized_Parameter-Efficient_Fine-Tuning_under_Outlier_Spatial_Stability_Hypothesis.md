# 夸夫：量化参数高效微调新方法——基于异常空间稳定性假设

发布时间：2025年05月20日

`LLM应用

理由：这篇论文专注于优化大型语言模型（LLMs）在资源受限设备上的部署，提出了新的量化方法（Quaff），以平衡性能和计算资源。这属于LLM的应用层面优化，因此归类为LLM应用。` `人工智能` `边缘计算`

> Quaff: Quantized Parameter-Efficient Fine-Tuning under Outlier Spatial Stability Hypothesis

# 摘要

> 大型语言模型（LLMs）在多个领域取得了令人兴奋的成就，但在资源受限的个人设备上部署时，仍面临任务特定微调带来的高昂计算和内存需求的挑战。虽然量化为高效微调提供了一条路径，但现有方法在平衡性能和开销方面仍显不足，要么导致高计算/内存成本，要么无法解决激活异常值问题，这是量化微调的关键瓶颈。

为了解决这些挑战，我们提出了激活异常空间稳定性假设（OSSH）：在微调过程中，某些激活异常值通道在整个训练迭代中保持稳定的空域位置。基于OSSH，我们提出了Quaff，一个针对LLMs的量化参数高效微调框架，通过针对性的动量缩放优化低精度激活表示。Quaff利用轻量级操作动态抑制不变通道中的异常值，避免了全精度权重存储和全局缩放，同时减少了量化误差。

在十个基准测试中的广泛实验验证了OSSH，并展示了Quaff的有效性。具体而言，在GPQA推理基准测试中，与全精度微调相比，Quaff实现了1.73倍的延迟降低和30%的内存节省，同时在Phi-3模型上提高了0.6%的准确性，成功平衡了效率、性能和部署能力之间的三重权衡。通过支持消费级GPU微调（例如RTX 2080 Super）而无需牺牲模型实用性，Quaff推动了个性化LLM部署的民主化。代码可在https://github.com/Little0o0/Quaff.git获取。

> Large language models (LLMs) have made exciting achievements across various domains, yet their deployment on resource-constrained personal devices remains hindered by the prohibitive computational and memory demands of task-specific fine-tuning. While quantization offers a pathway to efficiency, existing methods struggle to balance performance and overhead, either incurring high computational/memory costs or failing to address activation outliers, a critical bottleneck in quantized fine-tuning. To address these challenges, we propose the Outlier Spatial Stability Hypothesis (OSSH): During fine-tuning, certain activation outlier channels retain stable spatial positions across training iterations. Building on OSSH, we propose Quaff, a Quantized parameter-efficient fine-tuning framework for LLMs, optimizing low-precision activation representations through targeted momentum scaling. Quaff dynamically suppresses outliers exclusively in invariant channels using lightweight operations, eliminating full-precision weight storage and global rescaling while reducing quantization errors. Extensive experiments across ten benchmarks validate OSSH and demonstrate Quaff's efficacy. Specifically, on the GPQA reasoning benchmark, Quaff achieves a 1.73x latency reduction and 30% memory savings over full-precision fine-tuning while improving accuracy by 0.6% on the Phi-3 model, reconciling the triple trade-off between efficiency, performance, and deployability. By enabling consumer-grade GPU fine-tuning (e.g., RTX 2080 Super) without sacrificing model utility, Quaff democratizes personalized LLM deployment. The code is available at https://github.com/Little0o0/Quaff.git.

[Arxiv](https://arxiv.org/abs/2505.14742)