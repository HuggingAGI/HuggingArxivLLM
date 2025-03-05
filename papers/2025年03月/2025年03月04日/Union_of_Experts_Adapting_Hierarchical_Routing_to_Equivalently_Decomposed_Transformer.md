# # 专家集合：构建适应层次路由机制的等价分解Transformer结构

发布时间：2025年03月04日

`LLM理论

摘要中的论文主要探讨了专家混合模型（MoE）在大型语言模型中的应用，提出了新的模型架构UoE，并对其进行了理论分析和优化。这属于模型理论层面的研究，因此归类为LLM理论。` `大规模模型优化` `计算效率提升`

> Union of Experts: Adapting Hierarchical Routing to Equivalently Decomposed Transformer

# 摘要

> 专家混合模型（MoE）在保持计算效率的同时提升了模型性能，非常适合大规模应用。然而，现有MoE中，专家各自独立工作，缺乏高质量交互，且未有效扩展到注意力块，限制了效率提升。为解决这些问题，我们提出专家联合模型（UoE），将Transformer分解为均衡专家组，并对输入数据和专家实施动态路由。UoE在MoE设计上有三大创新：（1）基于张量并行中的矩阵划分，对MLP和注意力块进行均衡专家分解。（2）开发基于补丁的数据选择和专家选择两种路由范式，实现跨级别路由。（3）设计了UoE模型架构，包括选择性多头注意力（SMHA）和专家联合MLP（UoME）。（4）实现路由和计算操作的并行化，并基于硬件分析优化效率。实验显示，UoE在图像和自然语言任务中优于全注意力、先进MoE和高效Transformer。源代码已开源：https://github.com/YujiaoYang-work/UoE。

> Mixture-of-Experts (MoE) enhances model performance while maintaining computational efficiency, making it well-suited for large-scale applications. However, expert in exist MoE paradigm works as an individual, thereby lacking high-quality expert interactions. Moreover, they have not been effectively extended to attention block, which constrains further efficiency improvements. To tackle these issues, we propose Union-of-Experts (UoE), which decomposes transformer into an equitant group of experts, and then implement dynamic routing on input data and experts. Our approach advances MoE design with three key innovations: (1) We conducted equitant expert decomposition on both MLP blocks and attention blocks based on matrix partition in tensor parallelism. (2) We developed two routing paradigms: patch wise data selection and expert selection, to apply routing across different levels. (3) We design the architecture of UoE model, including Selective Multi-Head Attention (SMHA) and Union-of-MLP-Experts (UoME). (4) We develop parallel implementation of UoE's routing and computation operation, and optimize efficiency based on the hardware processing analysis. The experiments demonstrate that the model employed with UoE surpass Full Attention, state-of-art MoEs and efficient transformers in several tasks across image and natural language domains. The source codes are available at https://github.com/YujiaoYang-work/UoE.

[Arxiv](https://arxiv.org/abs/2503.02495)