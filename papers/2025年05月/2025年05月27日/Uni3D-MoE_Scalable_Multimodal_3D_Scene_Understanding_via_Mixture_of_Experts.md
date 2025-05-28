# Uni3D-MoE：通过专家混合实现可扩展的多模态三维场景理解

发布时间：2025年05月27日

`LLM应用` `3D技术` `多模态`

> Uni3D-MoE: Scalable Multimodal 3D Scene Understanding via Mixture of Experts

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展在全面理解3D场景方面展现了巨大潜力。然而，现有方法通常仅依赖单一或有限的3D模态，导致场景表示不完整，解释精度受限。此外，不同类型的查询天然依赖于不同模态，统一处理所有模态标记可能无法有效捕捉特定查询的上下文。为解决这些问题，我们提出了Uni3D-MoE——一种基于稀疏混合专家（MoE）的3D MLLM，专为自适应3D多模态融合设计。具体而言，Uni3D-MoE整合了多视图RGB和深度图像、鸟瞰图（BEV）地图、点云及体素表示等多种3D模态。在核心，我们的框架采用基于稀疏MoE的大型语言模型中的可学习路由机制，在标记级别动态选择专家。每个专家根据学习到的模态偏好专注处理特定类型的多模态标记，从而实现灵活协作，满足多样化的任务需求。在标准3D场景理解基准测试和专门数据集上的广泛评估证实了Uni3D-MoE的卓越效果。

> Recent advancements in multimodal large language models (MLLMs) have demonstrated considerable potential for comprehensive 3D scene understanding. However, existing approaches typically utilize only one or a limited subset of 3D modalities, resulting in incomplete representations of 3D scenes and reduced interpretive accuracy. Furthermore, different types of queries inherently depend on distinct modalities, indicating that uniform processing of all modality tokens may fail to effectively capture query-specific context. To address these challenges, we propose Uni3D-MoE, a sparse Mixture-of-Experts (MoE)-based 3D MLLM designed to enable adaptive 3D multimodal fusion. Specifically, Uni3D-MoE integrates a comprehensive set of 3D modalities, including multi-view RGB and depth images, bird's-eye-view (BEV) maps, point clouds, and voxel representations. At its core, our framework employs a learnable routing mechanism within the sparse MoE-based large language model, dynamically selecting appropriate experts at the token level. Each expert specializes in processing multimodal tokens based on learned modality preferences, thus facilitating flexible collaboration tailored to diverse task-specific requirements. Extensive evaluations on standard 3D scene understanding benchmarks and specialized datasets demonstrate the efficacy of Uni3D-MoE.

[Arxiv](https://arxiv.org/abs/2505.21079)