# 句子嵌入的集合论组合性研究

发布时间：2025年02月28日

`其他`

> Set-Theoretic Compositionality of Sentence Embeddings

# 摘要

> 句子编码器在NLP任务中发挥着关键作用，因此准确评估其组合性质至关重要。然而，现有方法主要关注特定任务性能，忽视了任务独立背景下句子嵌入的基本组合性质。我们利用经典集合论，提出基于三个核心“集合类”组合/操作的六项标准：	extit{TextOverlap}、	extit{TextDifference} 和 	extit{TextUnion}。我们系统评估了$7$个经典和$9$个基于LLM的句子编码器，发现SBERT在集合类组合性质上表现最佳，甚至超越了最新LLMs。此外，我们还推出一个包含约$192$K样本的新数据集，助力未来句子嵌入集合类组合性的基准测试。

> Sentence encoders play a pivotal role in various NLP tasks; hence, an accurate evaluation of their compositional properties is paramount. However, existing evaluation methods predominantly focus on goal task-specific performance. This leaves a significant gap in understanding how well sentence embeddings demonstrate fundamental compositional properties in a task-independent context. Leveraging classical set theory, we address this gap by proposing six criteria based on three core "set-like" compositions/operations: \textit{TextOverlap}, \textit{TextDifference}, and \textit{TextUnion}. We systematically evaluate $7$ classical and $9$ Large Language Model (LLM)-based sentence encoders to assess their alignment with these criteria. Our findings show that SBERT consistently demonstrates set-like compositional properties, surpassing even the latest LLMs. Additionally, we introduce a new dataset of ~$192$K samples designed to facilitate future benchmarking efforts on set-like compositionality of sentence embeddings.

[Arxiv](https://arxiv.org/abs/2502.20975)