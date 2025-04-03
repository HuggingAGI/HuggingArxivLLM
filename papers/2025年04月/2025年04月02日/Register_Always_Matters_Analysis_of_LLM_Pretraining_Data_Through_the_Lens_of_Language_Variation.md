# # 语料库至关重要：透过语言变体的视角分析LLM预训练数据

发布时间：2025年04月02日

`LLM理论` `数据科学`

> Register Always Matters: Analysis of LLM Pretraining Data Through the Lens of Language Variation

# 摘要

> 预训练数据整理是LLM开发的关键环节，推动了对大规模网络语料库质量筛选的研究。从统计质量标志到基于LLM的标注系统，数据集被划分为不同类别，通常简化为二元分类：通过筛选的被视为有价值的例子，其余则被丢弃为无用或有害。然而，关于不同文本类型对模型性能的具体贡献，我们仍缺乏深入理解。本文首次利用文本类型（也称为体裁）——语料库语言学中广泛用于建模语言变异的标准——来整理预训练数据集，并探讨文本类型对LLM性能的影响。我们通过训练基于文本类型分类的数据模型，并使用标准基准进行评估，进行了比较研究，结果表明预训练数据的文本类型对模型性能有显著影响。我们揭示了预训练材料与最终模型之间的令人惊讶的关系：使用新闻类文本预训练效果不佳，而包含观点类文本（如评论和博客文章）则显著提升性能。尽管基于完整未筛选数据集训练的模型优于仅基于单一文本类型的数据集训练的模型，但将表现良好的文本类型（如如何指令、信息描述和观点类）相结合可带来重大改进。此外，对单个基准测试结果的分析揭示了特定文本类型作为预训练数据在优势和不足方面的关键差异。这些发现表明，文本类型是模型性能差异的重要解释因素，并为未来更谨慎的数据选择实践提供了支持。

> Pretraining data curation is a cornerstone in Large Language Model (LLM) development, leading to growing research on quality filtering of large web corpora. From statistical quality flags to LLM-based labeling systems, datasets are divided into categories, frequently reducing to a binary: those passing the filters deemed as valuable examples, others discarded as useless or detrimental. However, a more detailed understanding of the contribution of different kinds of texts to model performance is still largely lacking. In this article, we present the first study utilizing registers (also known as genres) - a widely used standard in corpus linguistics to model linguistic variation - to curate pretraining datasets and investigate the effect of register on the performance of LLMs. We perform comparative studies by training models with register classified data and evaluating them using standard benchmarks, and show that the register of pretraining data substantially affects model performance. We uncover surprising relationships between the pretraining material and the resulting models: using the News register results in subpar performance, and on the contrary, including the Opinion class, covering texts such as reviews and opinion blogs, is highly beneficial. While a model trained on the entire unfiltered dataset outperforms those trained on datasets limited to a single register, combining well-performing registers like How-to-Instructions, Informational Description, and Opinion leads to major improvements. Furthermore, analysis of individual benchmark results reveals key differences in the strengths and drawbacks of specific register classes as pretraining data. These findings show that register is an important explainer of model variation and can facilitate more deliberate future data selection practices.

[Arxiv](https://arxiv.org/abs/2504.01542)