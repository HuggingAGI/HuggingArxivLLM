# Pangu Pro MoE：通过分组专家混合实现高效稀疏性设计

发布时间：2025年05月27日

`LLM理论` `人工智能` `高性能计算`

> Pangu Pro MoE: Mixture of Grouped Experts for Efficient Sparsity

# 摘要

> 专家混合模型（MoE）在大型语言模型中的应用，以较小的执行成本实现了更大的模型参数量和学习能力。这是因为每个输入令牌仅激活一小部分参数。然而，我们发现某些专家被激活的频率远高于其他专家，这在并行运行专家于不同设备时会导致系统效率低下。为此，我们提出了分组专家混合模型（MoGE），在选择阶段对专家进行分组，相较于传统MoE，MoGE在本质上能更好地平衡专家的工作负载。它限制令牌在每个预定义的专家组内激活相同数量的专家。当模型执行分布在多个设备上时，这种架构设计确保了设备间计算负载的均衡，显著提升了吞吐量，特别是在推理阶段。此外，我们在昇思NPU上构建了基于MoGE的720亿参数稀疏模型——盘古Pro MoE，其中每个令牌激活160亿参数。通过广泛的系统仿真研究，我们对盘古Pro MoE的配置进行了优化，使其在昇思300I双卡和800I A2上达到最佳性能。实验表明，MoGE确实能带来更好的专家负载均衡和更高效的执行，无论是模型训练还是推理阶段。盘古Pro MoE的推理性能达到每卡1148 token/s，通过推测加速可进一步提升至1528 token/s每卡，优于同规模的320亿和720亿参数密集模型。此外，我们在昇思300I双卡上实现了卓越的性价比。研究结果表明，昇思NPU能够通过大规模并行化训练盘古Pro MoE，使其成为参数量低于1000亿的领先模型，超越如GLM-Z1-32B和Qwen3-32B等知名开源模型。

> The surgence of Mixture of Experts (MoE) in Large Language Models promises a small price of execution cost for a much larger model parameter count and learning capacity, because only a small fraction of parameters are activated for each input token. However, it is commonly observed that some experts are activated far more often than others, leading to system inefficiency when running the experts on different devices in parallel. Therefore, we introduce Mixture of Grouped Experts (MoGE), which groups the experts during selection and balances the expert workload better than MoE in nature. It constrains tokens to activate an equal number of experts within each predefined expert group. When a model execution is distributed on multiple devices, this architectural design ensures a balanced computational load across devices, significantly enhancing throughput, particularly for the inference phase. Further, we build Pangu Pro MoE on Ascend NPUs, a sparse model based on MoGE with 72 billion total parameters, 16 billion of which are activated for each token. The configuration of Pangu Pro MoE is optimized for Ascend 300I Duo and 800I A2 through extensive system simulation studies. Our experiments indicate that MoGE indeed leads to better expert load balancing and more efficient execution for both model training and inference on Ascend NPUs. The inference performance of Pangu Pro MoE achieves 1148 tokens/s per card and can be further improved to 1528 tokens/s per card by speculative acceleration, outperforming comparable 32B and 72B Dense models. Furthermore, we achieve an excellent cost-to-performance ratio for model inference on Ascend 300I Duo.Our studies show that Ascend NPUs are capable of training Pangu Pro MoE with massive parallelization to make it a leading model within the sub-100B total parameter class, outperforming prominent open-source models like GLM-Z1-32B and Qwen3-32B.

[Arxiv](https://arxiv.org/abs/2505.21411)