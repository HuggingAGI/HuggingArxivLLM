# 面向GPU的多样化掩码快速稀疏变换器的灵活操作融合方案

发布时间：2025年06月06日

`LLM应用

摘要讨论了大型语言模型中Transformer的优化，提出了STOF框架来提升计算效率，属于应用层面的优化，因此归类为LLM应用。` `计算机体系结构`

> Flexible Operator Fusion for Fast Sparse Transformer with Diverse Masking on GPU

# 摘要

> 大型语言模型凭借强大的理解能力在全球范围内广受欢迎。作为LLM的核心，通过并行化加速Transformer已成为热门研究方向。遮罩层通过引入稀疏性减少计算量，但此前研究较少关注稀疏Transformer的性能优化。此外，基于规则的方法忽视了混合操作符的融合机会，也无法适应不同序列长度。为解决这些问题，我们提出了STOF框架，该框架通过灵活的遮罩和GPU上的操作符融合优化了稀疏Transformer。我们首先统一了多头注意力的存储格式和内核实现，然后将融合方案映射到编译模板，并通过两阶段搜索引擎确定最优参数设置。实验结果显示，与现有最佳工作相比，STOF在多头注意力计算中实现了1.7倍的最大加速，在端到端推理中实现了1.5倍的最大加速。

> Large language models are popular around the world due to their powerful understanding capabilities. As the core component of LLMs, accelerating Transformer through parallelization has gradually become a hot research topic. Mask layers introduce sparsity into Transformer to reduce calculations. However, previous works rarely focus on the performance optimization of sparse Transformer. Moreover, rule-based mechanisms ignore the fusion opportunities of mixed-type operators and fail to adapt to various sequence lengths. To address the above problems, we propose STOF, a framework that incorporates optimizations for Sparse Transformer via flexible masking and operator fusion on GPU. We firstly unify the storage format and kernel implementation for the multi-head attention. Then, we map fusion schemes to compilation templates and determine the optimal parameter setting through a two-stage search engine. The experimental results show that compared to the state-of-the-art work, STOF achieves maximum speedups of 1.7x in MHA computation and 1.5x in end-to-end inference.

[Arxiv](https://arxiv.org/abs/2506.06095)