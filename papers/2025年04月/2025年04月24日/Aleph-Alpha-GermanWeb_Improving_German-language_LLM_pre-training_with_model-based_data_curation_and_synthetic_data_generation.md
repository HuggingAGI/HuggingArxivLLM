# # Aleph-Alpha-GermanWeb：基于模型的数据整理与合成数据生成提升德语LLM预训练效果

发布时间：2025年04月24日

`LLM理论

论文摘要讨论了数据质量对大型语言模型（LLMs）性能的影响，并详细介绍了数据整理管道和合成数据生成的方法。研究重点在于如何通过改进数据质量来提升模型的训练效果，属于理论层面的探讨，因此归类为LLM理论。` `数据科学`

> Aleph-Alpha-GermanWeb: Improving German-language LLM pre-training with model-based data curation and synthetic data generation

# 摘要

> 数据规模的扩展对大型语言模型 (LLMs) 至关重要，但近期研究表明，数据质量同样能显著提升模型性能和训练效率。我们开发了一个德语数据整理管道，结合启发式和基于模型的过滤技术，并引入合成数据生成。通过这一管道，我们创建了大规模德语预训练数据集 Aleph-Alpha-GermanWeb，其数据来源包括：(1) Common Crawl 网络数据，(2) FineWeb2，以及 (3) 以真实有机网络数据为条件生成的合成数据。我们通过预训练一个 10 亿参数的 Llama 风格模型和一个 80 亿参数的无词表分层自回归变换器 (HAT) 来评估该数据集。在包括 MMMLU 在内的德语基准测试中，与仅使用 FineWeb2 相比，Aleph-Alpha-GermanWeb 实现了显著的性能提升。即使在 80 亿参数规模下，当 FineWeb2 被增强为包含维基百科等人工整理的高质量数据源时，这一优势仍然存在。我们的研究结果进一步证明，基于模型的数据整理和合成数据生成能够显著提升 LLM 预训练数据集的质量。

> Scaling data quantity is essential for large language models (LLMs), yet recent findings show that data quality can significantly boost performance and training efficiency. We introduce a German-language dataset curation pipeline that combines heuristic and model-based filtering techniques with synthetic data generation. We use our pipeline to create Aleph-Alpha-GermanWeb, a large-scale German pre-training dataset which draws from: (1) Common Crawl web data, (2) FineWeb2, and (3) synthetically-generated data conditioned on actual, organic web data. We evaluate our dataset by pre-training both a 1B Llama-style model and an 8B tokenizer-free hierarchical autoregressive transformer (HAT). A comparison on German-language benchmarks, including MMMLU, shows significant performance gains of Aleph-Alpha-GermanWeb over FineWeb2 alone. This advantage holds at the 8B scale even when FineWeb2 is enriched by human-curated high-quality data sources such as Wikipedia. Our findings support the growing body of evidence that model-based data curation and synthetic data generation can significantly enhance LLM pre-training datasets.

[Arxiv](https://arxiv.org/abs/2505.00022)