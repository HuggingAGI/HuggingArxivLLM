# 加速混合专家模型：为超大规模语言模型提供高效推理方案

发布时间：2025年05月06日

`LLM理论` `人工智能`

> Faster MoE LLM Inference for Extremely Large Models

# 摘要

> 稀疏专家混合模型 (MoE) 正逐渐成为超大规模语言模型的主流方法。现有的优化工作主要集中在粗粒度 MoE 架构上。随着 DeepSeek Models 的出现，细粒度 MoE 模型逐渐流行，但对其研究仍然有限。因此，我们希望探讨不同服务负载下的效率动态。此外，细粒度模型允许部署者减少路由专家的数量，包括激活计数和总计数，这引发了一个问题：这种减少如何影响 MoE 效率与性能之间的权衡？我们的研究发现，尽管部署 MoE 模型带来了更大的挑战，但也提供了显著的优化机会。减少激活的专家数量可以在某些场景下带来显著的效率提升，同时仅导致轻微的性能下降。减少总专家数量带来的效率提升有限，但会导致严重的性能下降。我们的方法可以在不降低性能的情况下将吞吐量提高至少 10%。总体而言，我们得出结论：MoE 推理优化仍是一个具有巨大潜力的研究领域，值得进一步探索和改进。

> Sparse Mixture of Experts (MoE) large language models (LLMs) are gradually becoming the mainstream approach for ultra-large-scale models. Existing optimization efforts for MoE models have focused primarily on coarse-grained MoE architectures. With the emergence of DeepSeek Models, fine-grained MoE models are gaining popularity, yet research on them remains limited. Therefore, we want to discuss the efficiency dynamic under different service loads. Additionally, fine-grained models allow deployers to reduce the number of routed experts, both activated counts and total counts, raising the question of how this reduction affects the trade-off between MoE efficiency and performance. Our findings indicate that while deploying MoE models presents greater challenges, it also offers significant optimization opportunities. Reducing the number of activated experts can lead to substantial efficiency improvements in certain scenarios, with only minor performance degradation. Reducing the total number of experts provides limited efficiency gains but results in severe performance degradation. Our method can increase throughput by at least 10\% without any performance degradation. Overall, we conclude that MoE inference optimization remains an area with substantial potential for exploration and improvement.

[Arxiv](https://arxiv.org/abs/2505.03531)