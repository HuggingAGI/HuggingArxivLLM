# R2-T2：面向多模态专家混合模型的测试阶段重新路由技术

发布时间：2025年02月27日

`其他` `多模态` `模型优化`

> R2-T2: Re-Routing in Test-Time for Multimodal Mixture-of-Experts

# 摘要

> 在大型多模态模型（LMMs）中，视觉等非语言模态的感知能力往往无法与大型语言模型（LLMs）的强大推理能力相匹配，这限制了LMMs在复杂下游任务中的表现。近期研究通过将传统视觉编码器替换为专家混合模型（MoE），有效缓解了这一问题。MoE能够提供丰富、多粒度和多样化的表示，充分满足多样化的下游任务需求。多模态MoE的性能关键取决于其路由器，它通过为每个输入重新加权并混合不同专家的表示来实现优化。然而，我们发现经过端到端训练的路由器并不总能为每个测试样本生成最优的路由权重。为解决这一难题，我们提出了一种新颖且高效的“测试时刻重路由方法（R2-T2）”。该方法通过在测试时刻对路由权重向量进行局部优化，使其向测试样本邻域中正确预测样本的向量靠近，从而提升模型性能。我们设计了三种具有不同优化目标和邻域搜索空间的R2-T2策略。实验结果显示，R2-T2方法在各种具有挑战性的基准任务中，显著提升了现有先进LMMs的性能，而无需对任何基础模型参数进行重新训练。

> In large multimodal models (LMMs), the perception of non-language modalities (e.g., visual representations) is usually not on par with the large language models (LLMs)' powerful reasoning capabilities, deterring LMMs' performance on challenging downstream tasks. This weakness has been recently mitigated by replacing the vision encoder with a mixture-of-experts (MoE), which provides rich, multi-granularity, and diverse representations required by diverse downstream tasks. The performance of multimodal MoE largely depends on its router, which reweights and mixes the representations of different experts for each input. However, we find that the end-to-end trained router does not always produce the optimal routing weights for every test sample. To bridge the gap, we propose a novel and efficient method "Re-Routing in Test-Time(R2-T2) that locally optimizes the vector of routing weights in test-time by moving it toward those vectors of the correctly predicted samples in a neighborhood of the test sample. We propose three R2-T2 strategies with different optimization objectives and neighbor-search spaces. R2-T2 consistently and greatly improves state-of-the-art LMMs' performance on challenging benchmarks of diverse tasks, without training any base-model parameters.

[Arxiv](https://arxiv.org/abs/2502.20395)