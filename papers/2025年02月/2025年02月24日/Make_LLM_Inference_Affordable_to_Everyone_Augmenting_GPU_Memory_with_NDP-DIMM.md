# 让 LLM 推理触手可及：借助 NDP-DIMM 扩展 GPU 内存

发布时间：2025年02月24日

`LLM应用

理由：这篇论文探讨了如何在消费级硬件上高效部署大型语言模型（LLMs），通过创新的系统设计和硬件利用，优化了模型的推理性能。这属于LLM的应用层面，因为它关注的是模型的实际部署和性能提升，而非模型本身的理论或架构创新。` `人工智能`

> Make LLM Inference Affordable to Everyone: Augmenting GPU Memory with NDP-DIMM

# 摘要

> 千亿规模的大型语言模型（LLMs）通常需要部署在昂贵的服务器级GPU上，这些GPU配备大容量存储的HBM和强大的计算能力。随着LLM辅助服务的普及，如何在成本较低的硬件上实现高效的LLM推理成为了趋势。为此，研究者们尝试将LLM参数从昂贵的GPU迁移到主机内存。然而，主机内存与GPU内存之间的带宽限制成为了性能提升的瓶颈。

    本研究提出了一种名为Hermes的经济高效系统，通过利用 commodity DRAM DIMM 中的近数据处理（NDP）技术，显著提升了单个消费级GPU的推理性能。研究发现，LLMs内在的激活稀疏性将权重参数自然划分为两类：热神经元和冷神经元。其中，热神经元仅占所有权重参数的约20%，却承担了80%的计算负载；而冷神经元占80%的参数，却仅负责20%的计算任务。基于这一发现，我们提出了一种创新的异构计算策略：将热神经元分配到单个计算高效的GPU，同时将冷神经元卸载到 NDP-DIMM 模块中（这些模块提供大内存容量但计算能力有限）。

    由于激活稀疏性的动态特性，系统需要实时划分热/冷神经元，并在多个 NDP-DIMM 模块之间进行自适应重映射。为此，我们开发了一个轻量级预测器，用于优化 GPU 和 NDP-DIMM 之间的实时神经元分区和调整。同时，我们引入了基于窗口的在线调度机制，以维持 NDP-DIMM 模块之间的负载均衡。实验结果表明，Hermes系统成功实现了在消费级硬件上部署 LLaMA2-70B 模型，推理速度达到13.75 个代币/秒，并较现有基于卸载的推理系统实现了平均75.24倍的性能提升。

> The billion-scale Large Language Models (LLMs) need deployment on expensive server-grade GPUs with large-storage HBMs and abundant computation capability. As LLM-assisted services become popular, achieving cost-effective LLM inference on budget-friendly hardware becomes the trend. Extensive researches relocate LLM parameters from expensive GPUs to host memory. However, the restricted bandwidth between the host and GPU memory limits the inference performance.
  This work introduces Hermes, a budget-friendly system that leverages the near-data processing (NDP) within commodity DRAM DIMMs to enhance the performance of a single consumer-grade GPU, achieving efficient LLM inference. The inherent activation sparsity in LLMs naturally divides weight parameters into two categories, termed ``hot" and ``cold" neurons, respectively. Hot neurons, which consist of only approximately 20\% of all weight parameters, account for 80\% of the total computational load, while cold neurons make up the other 80\% of parameters but are responsible for just 20\% of the computational load. Therefore, we propose a heterogeneous computing strategy: mapping hot neurons to a single computation-efficient GPU, while offloading cold neurons to NDP-DIMMs, which offer large memory size but limited computation capabilities. Meanwhile, the dynamic nature of activation sparsity needs a real-time partition of hot/cold neurons and adaptive remapping of cold neurons across multiple NDP-DIMM modules. Therefore, we introduce a lightweight predictor optimizing real-time neuron partition and adjustment between GPU and NDP-DIMMs. We also utilize a window-based online scheduling mechanism to maintain load balance among NDP-DIMM modules. Hermes facilitates the deployment of LLaMA2-70B on consumer-grade hardware at 13.75 tokens/s and realizes an average 75.24$\times$ speedup over the state-of-the-art offloading-based inference system.

[Arxiv](https://arxiv.org/abs/2502.16963)