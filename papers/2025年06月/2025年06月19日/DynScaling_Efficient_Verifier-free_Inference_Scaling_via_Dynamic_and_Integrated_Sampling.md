# # DynScaling：通过动态与集成采样实现高效的无需验证器推理扩展
DynScaling: Efficient Verifier-free Inference Scaling via Dynamic and Integrated Sampling

发布时间：2025年06月19日

`LLM应用` `人工智能`

> DynScaling: Efficient Verifier-free Inference Scaling via Dynamic and Integrated Sampling

# 摘要

> 推理时的缩放策略已被证明是一种有效的提升大型语言模型（LLM）性能的方法，但其实际应用常受限于对外部验证器的依赖或对现实计算约束的忽视。为此，我们提出了DynScaling，通过两大创新突破这些限制：一种集成的并行-顺序采样策略，以及一个基于多臂老虎机的动态预算分配框架。该采样策略通过构建合成的顺序推理链，将独立的并行响应统一，从而生成多样且连贯的推理路径。动态预算分配框架将计算资源分配建模为多臂老虎机问题，根据历史响应的不确定性自适应分配推理预算，从而提升计算效率。通过结合这些组件，DynScaling在实际资源约束下显著提升了LLM性能，且无需外部验证器。实验结果表明，与现有无验证器的推理缩放方法相比，DynScaling在任务性能和计算效率上均表现更优。

> Inference-time scaling has proven effective in boosting large language model (LLM) performance through increased test-time computation. Yet, its practical application is often hindered by reliance on external verifiers or a lack of optimization for realistic computational constraints. We propose DynScaling, which addresses these limitations through two primary innovations: an integrated parallel-sequential sampling strategy and a bandit-based dynamic budget allocation framework. The integrated sampling strategy unifies parallel and sequential sampling by constructing synthetic sequential reasoning chains from initially independent parallel responses, promoting diverse and coherent reasoning trajectories. The dynamic budget allocation framework formulates the allocation of computational resources as a multi-armed bandit problem, adaptively distributing the inference budget across queries based on the uncertainty of previously sampled responses, thereby maximizing computational efficiency. By combining these components, DynScaling effectively improves LLM performance under practical resource constraints without the need for external verifiers. Experimental results demonstrate that DynScaling consistently surpasses existing verifier-free inference scaling baselines in both task performance and computational cost.

[Arxiv](https://arxiv.org/abs/2506.16043)