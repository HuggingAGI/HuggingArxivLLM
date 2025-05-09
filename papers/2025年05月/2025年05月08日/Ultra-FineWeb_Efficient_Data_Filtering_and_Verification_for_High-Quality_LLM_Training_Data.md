# 超精细网络：高效筛选与验证高质量大语言模型训练数据

发布时间：2025年05月08日

`其他` `数据科学` `机器学习`

> Ultra-FineWeb: Efficient Data Filtering and Verification for High-Quality LLM Training Data

# 摘要

> 数据质量已成为提升模型性能的关键因素，随着大型语言模型（LLMs）的快速发展，模型驱动的数据过滤方法已成为获取高质量数据的主要手段。然而，这一方法仍面临两大主要挑战：(1) 缺乏高效的数据验证策略，难以及时提供数据质量反馈；(2) 训练分类器时种子数据的选择缺乏明确标准，严重依赖人类专业知识，导致一定程度的主观性。  
为应对这些挑战，我们提出了创新的解决方案。首先，引入了一种高效验证策略，能够在极低的计算成本下快速评估数据对 LLM 训练的影响。其次，基于优质种子数据对 LLM 训练有益的假设，结合提出的验证策略，优化了正负样本选择，并提出了一种高效的数据过滤流水线。  
这一流水线不仅提升了过滤效率、分类器质量和鲁棒性，还大幅降低了实验和推理成本。我们采用基于 fastText 的轻量级分类器，并成功将过滤流水线应用于 FineWeb 和 Chinese FineWeb 数据集，最终构建了更高质量的 Ultra-FineWeb 数据集。Ultra-FineWeb 包含约 1 万亿个英文标记和 1200 亿个中文标记。  
实证结果显示，基于 Ultra-FineWeb 训练的 LLM 在多个基准任务中表现出显著的性能提升，验证了我们的流水线在提升数据质量和训练效率方面的有效性。

> Data quality has become a key factor in enhancing model performance with the rapid development of large language models (LLMs). Model-driven data filtering has increasingly become a primary approach for acquiring high-quality data. However, it still faces two main challenges: (1) the lack of an efficient data verification strategy makes it difficult to provide timely feedback on data quality; and (2) the selection of seed data for training classifiers lacks clear criteria and relies heavily on human expertise, introducing a degree of subjectivity. To address the first challenge, we introduce an efficient verification strategy that enables rapid evaluation of the impact of data on LLM training with minimal computational cost. To tackle the second challenge, we build upon the assumption that high-quality seed data is beneficial for LLM training, and by integrating the proposed verification strategy, we optimize the selection of positive and negative samples and propose an efficient data filtering pipeline. This pipeline not only improves filtering efficiency, classifier quality, and robustness, but also significantly reduces experimental and inference costs. In addition, to efficiently filter high-quality data, we employ a lightweight classifier based on fastText, and successfully apply the filtering pipeline to two widely-used pre-training corpora, FineWeb and Chinese FineWeb datasets, resulting in the creation of the higher-quality Ultra-FineWeb dataset. Ultra-FineWeb contains approximately 1 trillion English tokens and 120 billion Chinese tokens. Empirical results demonstrate that the LLMs trained on Ultra-FineWeb exhibit significant performance improvements across multiple benchmark tasks, validating the effectiveness of our pipeline in enhancing both data quality and training efficiency.

[Arxiv](https://arxiv.org/abs/2505.05427)