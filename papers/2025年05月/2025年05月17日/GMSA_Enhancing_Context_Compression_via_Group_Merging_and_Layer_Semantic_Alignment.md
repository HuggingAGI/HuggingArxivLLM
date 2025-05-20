# GMSA: 基于组合并与层间语义对齐提升上下文压缩效果

发布时间：2025年05月17日

`LLM理论` `问答系统`

> GMSA: Enhancing Context Compression via Group Merging and Layer Semantic Alignment

# 摘要

> 大型语言模型（LLMs）在NLP任务中表现出色，但在处理长上下文时面临两大挑战：计算效率低和冗余信息多。本文提出了一种基于编码器-解码器架构的上下文压缩框架GMSA，通过缩短输入序列和减少冗余信息来解决这些问题。GMSA框架包含两个核心组件：组合并（Group Merging）和层语义对齐（LSA）。组合并能高效提取上下文摘要向量，而层语义对齐则通过将高层摘要与低层输入语义对齐，弥合层间语义差距。在训练中，GMSA通过自动编码器学习完整语义的软令牌，并结合知识提取微调（KEFT）优化下游任务表现。我们随机采样数据集中的压缩率进行训练，结果显示GMSA不仅在上下文恢复上超越传统方法，还以更少的编码器层实现更快收敛。在问答任务中，GMSA的端到端推理速度提升约2倍，性能远超原始提示和现有最优方法。

> Large language models (LLMs) have achieved impressive performance in a variety of natural language processing (NLP) tasks. However, when applied to long-context scenarios, they face two challenges, i.e., low computational efficiency and much redundant information. This paper introduces GMSA, a context compression framework based on the encoder-decoder architecture, which addresses these challenges by reducing input sequence length and redundant information. Structurally, GMSA has two key components: Group Merging and Layer Semantic Alignment (LSA). Group merging is used to effectively and efficiently extract summary vectors from the original context. Layer semantic alignment, on the other hand, aligns the high-level summary vectors with the low-level primary input semantics, thus bridging the semantic gap between different layers. In the training process, GMSA first learns soft tokens that contain complete semantics through autoencoder training. To furtherly adapt GMSA to downstream tasks, we propose Knowledge Extraction Fine-tuning (KEFT) to extract knowledge from the soft tokens for downstream tasks. We train GMSA by randomly sampling the compression rate for each sample in the dataset. Under this condition, GMSA not only significantly outperforms the traditional compression paradigm in context restoration but also achieves stable and significantly faster convergence with only a few encoder layers. In downstream question-answering (QA) tasks, GMSA can achieve approximately a 2x speedup in end-to-end inference while outperforming both the original input prompts and various state-of-the-art (SOTA) methods by a large margin.

[Arxiv](https://arxiv.org/abs/2505.12215)