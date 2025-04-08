# 释放LLMs在密集检索中的力量：利用查询可能性建模

发布时间：2025年04月07日

`LLM应用` `信息检索`

> Unleashing the Power of LLMs in Dense Retrieval with Query Likelihood Modeling

# 摘要

> 密集检索是信息检索 (IR) 中的关键任务，也是重排序等下游任务的基础。近期，大型语言模型 (LLMs) 展示了强大的语义理解能力，吸引了研究密集检索的研究者。作为解码式生成模型，LLMs 在语言生成方面表现出色，但因缺乏对后续标记的关注而难以建模全局信息。受基于 IR 的经典词级语言建模方法，即查询似然 (QL) 模型的启发，我们希望通过最大化 QL 充分利用 LLMs 的生成能力。然而，我们并未直接用 QL 估计来对文档进行排序，而是引入了一个 QL 最大化的辅助任务，以更好地支持对比学习一个判别式检索器。我们将模型命名为 LLM-QL。为了在 QL 建模过程中将全局文档语义浓缩为单一向量，LLM-QL 包含两个主要组件：注意力终止 (AS) 和输入破坏 (IC)。AS 停止预测标记对前序标记的注意力，直到文档的最后一个标记。IC 在预测过程中对输入文档中的一部分标记进行遮蔽。在 MSMARCO 数据集上的实验表明，LLM-QL 的性能显著优于其他基于 LLM 的检索器，且使用 LLM-QL 估计的 QL 进行排序比词级 QL 有明显优势。

> Dense retrieval is a crucial task in Information Retrieval (IR) and is the foundation for downstream tasks such as re-ranking. Recently, large language models (LLMs) have shown compelling semantic understanding capabilities and are appealing to researchers studying dense retrieval. LLMs, as decoder-style generative models, are competent at language generation while falling short on modeling global information due to the lack of attention to tokens afterward. Inspired by the classical word-based language modeling approach for IR, i.e., the query likelihood (QL) model, we seek to sufficiently utilize LLMs' generative ability by QL maximization. However, instead of ranking documents with QL estimation, we introduce an auxiliary task of QL maximization to yield a better backbone for contrastively learning a discriminative retriever. We name our model as LLM-QL. To condense global document semantics to a single vector during QL modeling, LLM-QL has two major components, Attention Stop (AS) and Input Corruption (IC). AS stops the attention of predictive tokens to previous tokens until the ending token of the document. IC masks a portion of tokens in the input documents during prediction. Experiments on MSMARCO show that LLM-QL can achieve significantly better performance than other LLM-based retrievers and using QL estimated by LLM-QL for ranking outperforms word-based QL by a large margin.

[Arxiv](https://arxiv.org/abs/2504.05216)