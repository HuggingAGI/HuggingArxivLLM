# ExpertFlow：优化专家激活与令牌分配，提升专家混合推理效率

发布时间：2024年10月23日

`LLM应用

**理由**：这篇论文主要讨论了稀疏专家混合模型（MoE）在推理时的部署挑战，并提出了一个名为ExpertFlow的系统来提升推理效率。虽然涉及到了模型的结构和优化，但其核心关注点是如何在实际应用中提高LLM的推理性能，因此应归类为LLM应用。` `机器学习` `系统优化`

> ExpertFlow: Optimized Expert Activation and Token Allocation for Efficient Mixture-of-Experts Inference

# 摘要

> 稀疏专家混合模型（MoE）在性能上优于密集的LLMs，但其高内存需求在推理时带来了显著的部署挑战。现有卸载技术因僵化的专家缓存机制，难以适应动态路由，导致缓存利用率低或预测训练成本高。为此，我们推出了ExpertFlow，一个专为提升推理效率而设计的系统，通过灵活路由和高效专家调度减少开销并提升性能。其核心是基于预测路由路径的卸载机制，利用轻量级预测器在计算前准确预测路由路径，实现实时错误纠正，显著提高缓存命中率并减少专家传输频率，从而最小化I/O开销。此外，动态令牌调度策略通过重新排列输入令牌优化MoE推理，减少每批次激活的专家数量并提升计算效率。实验表明，ExpertFlow相比基线方法节省了高达93.72%的GPU内存，推理速度提升了2到10倍，展现了其在资源受限推理场景中的强大实用性。

> Sparse Mixture of Experts (MoE) models, while outperforming dense Large Language Models (LLMs) in terms of performance, face significant deployment challenges during inference due to their high memory demands. Existing offloading techniques, which involve swapping activated and idle experts between the GPU and CPU, often suffer from rigid expert caching mechanisms. These mechanisms fail to adapt to dynamic routing, leading to inefficient cache utilization, or incur prohibitive costs for prediction training. To tackle these inference-specific challenges, we introduce ExpertFlow, a comprehensive system specifically designed to enhance inference efficiency by accommodating flexible routing and enabling efficient expert scheduling between CPU and GPU. This reduces overhead and boosts system performance. Central to our approach is a predictive routing path-based offloading mechanism that utilizes a lightweight predictor to accurately forecast routing paths before computation begins. This proactive strategy allows for real-time error correction in expert caching, significantly increasing cache hit ratios and reducing the frequency of expert transfers, thereby minimizing I/O overhead. Additionally, we implement a dynamic token scheduling strategy that optimizes MoE inference by rearranging input tokens across different batches. This method not only reduces the number of activated experts per batch but also improves computational efficiency. Our extensive experiments demonstrate that ExpertFlow achieves up to 93.72\% GPU memory savings and enhances inference speed by 2 to 10 times compared to baseline methods, highlighting its effectiveness and utility as a robust solution for resource-constrained inference scenarios.

[Arxiv](https://arxiv.org/abs/2410.17954)