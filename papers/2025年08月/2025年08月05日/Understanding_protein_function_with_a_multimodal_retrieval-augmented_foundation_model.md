# 构建一个多模态检索增强型蛋白质功能分析模型

发布时间：2025年08月05日

`LLM应用

论文摘要：蛋白质语言模型（PLMs）通过学习自然蛋白质序列的概率分布，掌握了蛋白质理解和设计的能力。近期研究发现，尽管扩展这些模型能提升结构预测的精度，但对突变的理解和蛋白质功能预测的表示质量似乎并无显著改善。为此，我们推出了PoET-2——一个多模态、增强检索的蛋白质基础模型。PoET-2创新性地结合了特定家族进化约束的上下文学习，并可选配结构条件，从而能够生成更高质量的蛋白质序列分布。它采用了层级变换编码器，确保对序列上下文顺序的等方差处理，并通过双解码器架构，同时实现因果和遮蔽语言建模目标，使PoET-2既能以全生成模式运行，也能在双向表示学习模式下发挥作用。在零样本变异效应预测方面，PoET-2表现卓越，尤其擅长评估涉及多个突变和复杂插入缺失突变的情况。在监督学习场景中，PoET-2的嵌入表示优于现有方法，尤其在处理小规模数据集时，其学习序列-功能关系的能力更为突出。这项研究充分展示了将检索增强与多模态、家族中心建模相结合，对于推动蛋白质基础模型发展的巨大潜力。

LLM应用` `生物技术` `蛋白质工程`

> Understanding protein function with a multimodal retrieval-augmented foundation model

# 摘要

> 蛋白质语言模型（PLMs）通过学习自然蛋白质序列的概率分布，掌握了蛋白质理解和设计的能力。近期研究发现，尽管扩展这些模型能提升结构预测的精度，但对突变的理解和蛋白质功能预测的表示质量似乎并无显著改善。为此，我们推出了PoET-2——一个多模态、增强检索的蛋白质基础模型。PoET-2创新性地结合了特定家族进化约束的上下文学习，并可选配结构条件，从而能够生成更高质量的蛋白质序列分布。它采用了层级变换编码器，确保对序列上下文顺序的等方差处理，并通过双解码器架构，同时实现因果和遮蔽语言建模目标，使PoET-2既能以全生成模式运行，也能在双向表示学习模式下发挥作用。在零样本变异效应预测方面，PoET-2表现卓越，尤其擅长评估涉及多个突变和复杂插入缺失突变的情况。在监督学习场景中，PoET-2的嵌入表示优于现有方法，尤其在处理小规模数据集时，其学习序列-功能关系的能力更为突出。这项研究充分展示了将检索增强与多模态、家族中心建模相结合，对于推动蛋白质基础模型发展的巨大潜力。

> Protein language models (PLMs) learn probability distributions over natural protein sequences. By learning from hundreds of millions of natural protein sequences, protein understanding and design capabilities emerge. Recent works have shown that scaling these models improves structure prediction, but does not seem to improve mutation understanding and representation quality for protein function prediction. We introduce PoET-2, a multimodal, retrieval-augmented protein foundation model that incorporates in-context learning of family-specific evolutionary constraints with optional structure conditioning to learn generative distributions over protein sequences. PoET-2 uses a hierarchical transformer encoder that is equivariant to sequence context ordering and a dual decoder architecture with both causal and masked language modeling objectives, allowing PoET-2 to operate in both fully generative and bidirectional representation learning modes. PoET-2 achieves state-of-the-art performance on zero-shot variant effect prediction, excelling at scoring variants with multiple mutations and challenging indel mutations. In supervised settings, PoET-2 embeddings outperform previous methods for learning sequence-function relationships, especially with small datasets. This work highlights the benefits of combining retrieval augmentation with multimodal, family-centric modeling for advancing protein foundation models.

[Arxiv](https://arxiv.org/abs/2508.04724)