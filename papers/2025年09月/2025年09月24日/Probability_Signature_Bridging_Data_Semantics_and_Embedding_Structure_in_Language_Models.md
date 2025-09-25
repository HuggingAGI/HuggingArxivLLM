# 概率签名：架起语言模型中数据语义与嵌入结构的桥梁

发布时间：2025年09月24日

`LLM理论` `基础理论`

> Probability Signature: Bridging Data Semantics and Embedding Structure in Language Models

# 摘要

> 语言模型的嵌入空间被普遍认为能捕捉语义关系——比如，数字嵌入常呈现出与其自然序列对应的有序结构。但这类结构的形成机制至今仍不明确。本研究从数据分布入手，解释嵌入结构的形成。我们提出一组概率特征，用以反映标记间的语义关联。通过在复合加法任务上采用线性模型与前馈网络进行实验，并结合梯度流动力学的理论分析，结果表明这些概率特征对嵌入结构的影响显著。为进一步将分析推广至大型语言模型（LLMs），我们在Pile语料库子集上训练了Qwen2.5架构。结果显示，概率特征与嵌入结构高度一致，尤其在捕捉嵌入间的强成对相似性上表现突出。本研究揭示了数据分布指导嵌入结构形成的机制，为嵌入组织与语义模式的关联提供了全新解读。

> The embedding space of language models is widely believed to capture the semantic relationships; for instance, embeddings of digits often exhibit an ordered structure that corresponds to their natural sequence. However, the mechanisms driving the formation of such structures remain poorly understood. In this work, we interpret the embedding structures via the data distribution. We propose a set of probability signatures that reflect the semantic relationships among tokens. Through experiments on the composite addition tasks using the linear model and feedforward network, combined with theoretical analysis of gradient flow dynamics, we reveal that these probability signatures significantly influence the embedding structures. We further generalize our analysis to large language models (LLMs) by training the Qwen2.5 architecture on the subsets of the Pile corpus. Our results show that the probability signatures are faithfully aligned with the embedding structures, particularly in capturing strong pairwise similarities among embeddings. Our work uncovers the mechanism of how data distribution guides the formation of embedding structures, establishing a novel understanding of the relationship between embedding organization and semantic patterns.

[Arxiv](https://arxiv.org/abs/2509.20124)