# SAGE：面向语义理解的真实基准

发布时间：2025年09月25日

`LLM应用` `基础理论`

> SAGE: A Realistic Benchmark for Semantic Understanding

# 摘要

> 随着大型语言模型（LLMs）在传统基准测试中表现卓越，亟需更具挑战性的评估框架来深入探究语义理解的深层维度。为此，我们提出SAGE（语义对齐与泛化评估）——一个严格的基准测试，用于评估嵌入模型和相似度度量在五大类别上的表现：人类偏好对齐、变换鲁棒性、信息敏感性、聚类性能及检索鲁棒性。与现有专注于单一能力的基准不同，SAGE通过对抗性条件、噪声变换及细微的人类判断任务，在30多个数据集上全面评估语义理解能力。我们对9个嵌入模型和经典度量的综合评估发现，不同方法间存在显著性能差距，没有任何一种方法能在所有维度上都表现卓越。例如，尽管OpenAI的text-embedding-3-large等最先进嵌入模型在人类偏好对齐上表现突出（得分0.682，而最佳经典度量为0.591），但在信息敏感性任务上，经典度量却显著超越了它们——Jaccard相似度得分达0.905，而顶级嵌入模型仅为0.794。SAGE还揭示了关键的性能权衡：OpenAI的text-embedding-3-small虽取得最高聚类性能（0.483），却极度脆弱，鲁棒性得分垫底（0.011）。SAGE暴露了当前语义理解能力的关键短板，为模型在实际部署中的鲁棒性提供了更贴合现实的评估。

> As large language models (LLMs) achieve strong performance on traditional benchmarks, there is an urgent need for more challenging evaluation frameworks that probe deeper aspects of semantic understanding. We introduce SAGE (Semantic Alignment & Generalization Evaluation), a rigorous benchmark designed to assess both embedding models and similarity metrics across five categories: Human Preference Alignment, Transformation Robustness, Information Sensitivity, Clustering Performance, and Retrieval Robustness. Unlike existing benchmarks that focus on isolated capabilities, SAGE evaluates semantic understanding through adversarial conditions, noisy transformations, and nuanced human judgment tasks across 30+ datasets. Our comprehensive evaluation of 9 embedding models and classical metrics reveals significant performance gaps, with no single approach excelling across all dimensions. For instance, while state-of-the-art embedding models like OpenAI's text-embedding-3-large dominate in aligning with human preferences (0.682 vs. 0.591 for the best classical metric), they are significantly outperformed by classical metrics on information sensitivity tasks, where Jaccard Similarity achieves a score of 0.905 compared to the top embedding score of 0.794. SAGE further uncovers critical trade-offs: OpenAI's text-embedding-3-small achieves the highest clustering performance (0.483) but demonstrates extreme brittleness with the lowest robustness score (0.011). SAGE exposes critical limitations in current semantic understanding capabilities and provides a more realistic assessment of model robustness for real-world deployment.

[Arxiv](https://arxiv.org/abs/2509.21310)