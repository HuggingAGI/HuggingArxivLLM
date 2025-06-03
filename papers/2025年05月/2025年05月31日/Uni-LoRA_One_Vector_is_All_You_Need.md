# # Uni-LoRA：一个向量，一切尽在掌握！

发布时间：2025年05月31日

`LLM理论` `优化算法`

> Uni-LoRA: One Vector is All You Need

# 摘要

> 低秩适配（LoRA）通过将权重更新限制在低秩矩阵中，已成为大型语言模型（LLMs）事实上的参数高效微调（PEFT）方法。近期，Tied-LoRA、VeRA和VB-LoRA等研究通过引入额外约束进一步提升了效率，缩小了可训练参数空间。本文提出，这些LoRA变体的参数空间减策略可统一纳入Uni-LoRA框架：LLM的LoRA参数空间作为高维向量空间$R^D$，可通过从子空间$R^d$（$d \ll D$）的投影重建。不同LoRA方法的核心差异在于投影矩阵$P \in R^{D 	imes d}$的选择。

现有LoRA变体多依赖分层或结构特定的投影方式，限制了跨层参数共享，影响了参数效率。为此，我们提出了一种高效且具理论依据的等距投影矩阵，支持全局参数共享并减少计算开销。在Uni-LoRA框架下，仅需一个向量即可重建整个LLM的LoRA参数——使其不仅是统一框架，更是"仅需一个向量"的解决方案。在GLUE、数学推理和指令调优基准上的大量实验表明，Uni-LoRA在实现参数效率新标杆的同时，在预测性能上也优于或持平于现有方法。

> Low-Rank Adaptation (LoRA) has become the de facto parameter-efficient fine-tuning (PEFT) method for large language models (LLMs) by constraining weight updates to low-rank matrices. Recent works such as Tied-LoRA, VeRA, and VB-LoRA push efficiency further by introducing additional constraints to reduce the trainable parameter space. In this paper, we show that the parameter space reduction strategies employed by these LoRA variants can be formulated within a unified framework, Uni-LoRA, where the LoRA parameter space, flattened as a high-dimensional vector space $R^D$, can be reconstructed through a projection from a subspace R^d, with $d \ll D$. We demonstrate that the fundamental difference among various LoRA methods lies in the choice of the projection matrix, $P \in R^{D \times d}$.Most existing LoRA variants rely on layer-wise or structure-specific projections that limit cross-layer parameter sharing, thereby compromising parameter efficiency. In light of this, we introduce an efficient and theoretically grounded projection matrix that is isometric, enabling global parameter sharing and reducing computation overhead. Furthermore, under the unified view of Uni-LoRA, this design requires only a single trainable vector to reconstruct LoRA parameters for the entire LLM - making Uni-LoRA both a unified framework and a "one-vector-only" solution. Extensive experiments on GLUE, mathematical reasoning, and instruction tuning benchmarks demonstrate that Uni-LoRA achieves state-of-the-art parameter efficiency while outperforming or matching prior approaches in predictive performance.

[Arxiv](https://arxiv.org/abs/2506.00799)